создание Dockerfile и запись данных в него

pip install -r requirements.txt

docker build -t django:v1

docker run --name my_project -it -p 8000:8000 django:v1
