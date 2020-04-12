FROM python:3
ADD https://github.com/Stephvan/Flask_Docker/tree/master/app /
WORKDIR /app
RUN apt-get update
RUN pip install -r requirements.txt
CMD [ "python", "app.py"]
