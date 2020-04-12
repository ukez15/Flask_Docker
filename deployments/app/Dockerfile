FROM python:3
WORKDIR /app
ADD https://github.com/Stephvan/Flask_Docker/tree/master/app /app
RUN apt-get update
RUN pip install -r ./requirements.txt
CMD [ "python", "app.py"]
