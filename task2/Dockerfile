FROM python:3.9-alpine

COPY . /app
WORKDIR /app
RUN pip install -r /app/requirements.txt
CMD ["python", "/app/manage.py", "runserver"]