FROM python:3.8-slim-buster

# copy app content
COPY . /app

#working directory is the current directory
WORKDIR /app

RUN pip3 install -r requirements.txt

ENTRYPOINT ["python"]

CMD ["app.py"]