FROM python:3.9
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt --no-cache-dir
RUN pip install psycopg2-binary
#COPY .env /app/.env
CMD ["python", "manage.py", "runserver", "0:8080", "--settings=kittygram_backend.settings"]

