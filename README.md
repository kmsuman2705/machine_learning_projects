# Machine_learning_projects

## Start machine learning project.

### Software and account Requirement.

1. [Github Account](https://github.com)

2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT CLI](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Creating conda environment

```
conda create -p venv python==3.7 -y
```

Conda activate

```
conda activate venv/
```

OR

```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git

```
git add .
```

OR

```
git add <file_name>
```

Note : To ignore file or folder from git we can write name of file/folder in .gitignore file
To check The git status

```
git status
```

To check all version maintained by git

```
git log
```

To create version/commit all changes by git

```
git commit -m "message"
```

To send version/changes to github

```
git push origin main
```

To check remote url

```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information

1. Versel_email =knsuman27@gmail.com
2. Versel_api_key =ZUtzDDrDR9YJSKZXMlRnBMxt
3. App_name = suman-kumar-mishras-projects

BUILD DOCKER IMAGE

```
docker build -t <image_name>:<tagname> .
```

Note: Image name for docker must be lowercase

To list docker image

```
docker images
```

Run docker image

```
docker run -p 5000:5000 -e PORT=5000 image id
```

To check running container in docker

```
docker ps
```

To stop docker container

```
docker stop <container_id>
```
