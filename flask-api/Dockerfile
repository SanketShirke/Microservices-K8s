FROM python:alpine3.7

WORKDIR /app

COPY . /app

RUN pip install -r requirements.txt

ENV PORT 5000

EXPOSE 5000

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]
