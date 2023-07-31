# mlproject_rep
complete project lineup 


Creating conda environment

conda create -p venv python==3.7 -y
conda activate venv/
OR

conda activate venv

To Add files to git

git add .
OR

git add <file_name>
Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status

git status
To check all version maintained by git

git log
To create version/commit all changes by git

git commit -m "message"
To send version/changes to github

git push origin main
To check remote url

git remote -v
To setup CI/CD pipeline in heroku we need 3 information

HEROKU_EMAIL = yuvinarwade@gmail.com
HEROKU_API_KEY =
HEROKU_APP_NAME = yuvrajnameapp
BUILD DOCKER IMAGE

docker build -t <image_name>:<tagname> .
tagname-latest .
Note: Image name for docker must be lowercase

To list docker image

docker images
Run docker image

docker run -p 5000:5000 -e PORT=5000 f8c749e73678
To check running container in docker

docker ps
Tos stop docker conatiner

docker stop <container_id>

new changes is done 
local host= http://127.0.0.1:5000/

deployment on elastic binstock-https://www.youtube.com/watch?v=gbJn2Ls2QsI

Step by step intution 

9 files changed, 41 insertions(+)
 create mode 100644 src/components/__init__.py
 create mode 100644 src/components/data_ingestion.py
 create mode 100644 src/components/data_transformation.py
 create mode 100644 src/components/model_trainer.py
 create mode 100644 src/pipeline/__init__.py
 create mode 100644 src/pipeline/exception.py
 create mode 100644 src/pipeline/logger.py
 create mode 100644 src/pipeline/predict_pipeline.py
 create mode 100644 src/pipeline/train_pipeline.py