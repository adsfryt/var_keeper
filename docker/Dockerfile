FROM python:3.12-alpine
WORKDIR /app
COPY /src/app/requirements.txt /app
COPY /src/app /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
