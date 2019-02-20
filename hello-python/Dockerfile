FROM python:2.7-alpine

WORKDIR /usr/src/app

ADD . ${WORDIR}

#RUN apt update
RUN pip install -r requirements.txt

CMD python app.py