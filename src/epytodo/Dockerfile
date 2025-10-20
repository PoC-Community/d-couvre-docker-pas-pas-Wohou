FROM python:3.7.5-alpine

WORKDIR /app

COPY . .

RUN apk add --no-cache mariadb-connector-c-dev gcc musl-dev

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python", "run.py"]
