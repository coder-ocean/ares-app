FROM python:3.15-rc-bookworm

WORKDIR /app

ADD . /app

RUN pip install -r requirements.txt

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]