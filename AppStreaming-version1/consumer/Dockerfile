FROM python:3

WORKDIR /usr/src/app

COPY consumer.py ./

RUN pip3 install kafka-python

CMD ["python3", "./consumer.py"]