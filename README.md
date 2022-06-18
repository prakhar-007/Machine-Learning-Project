###

Starting Machine learning Project

##

Requirements 

1. Github account 
2. Heroku account
3. VS Code IDE
4. GIT CLI
5. [Git Documentation](https://git-scm.com/docs/gittutorial)

##
Creating Conda Environment

```
conda create -p venv python == 3.7 -y
```

```
conda activate venv/
```

```
pip install -r requirements.txt
```

To add files in git

```
git add . 
```

OR

```
git add filename
```

##
Note: To ignore file or folder from git we can write file/folder name in .gitignore file

TO Check the git status 

```
git status
```

To Check all the versions maintained by git 

```
git log
```

To create version/commit all changes by git

```
git commit -m "message"
```

To send version/changes in Github

```
git push origin main
```

To check remote url

```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = srivastavaprakhar07@gmail.com
2. HEROKU_API_KEY = 
3. HEROKU_APP_NAME = 

Build Docker Image

```
docker build -t <image_name>:<tag_name> .
```
Note:  Image name in docker must be lowercase

To list docker image

```
docker images
```

Run docker image

```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

To check running container in docker

```
docker ps
```

Tos stop docker conatiner

```
docker stop <container_id>
```

```
python setup.py install
```



