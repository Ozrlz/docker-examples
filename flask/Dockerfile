FROM python:3.6.5

WORKDIR /usr/app/

ADD requirements.txt /

RUN pip install -r /requirements.txt

EXPOSE 5000

CMD ["python", "main.py"]