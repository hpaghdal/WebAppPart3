FROM python:3.8

EXPOSE 5000

WORKDIR /app

COPY ../../../Desktop/PythonDockerFlaskPycharm-master/app/requirements.txt /app
RUN pip install -r requirements.txt --upgrade pip

COPY ../../../Desktop/PythonDockerFlaskPycharm-master/app/app.py /app
CMD python app.py