# syntax=docker/dockerfile:1

FROM python:3.9-slim

WORKDIR /app
COPY . .
RUN pip3 install --no-cache-dir -r requirements.txt

ENTRYPOINT [ "python3" ]
CMD [ "app.py" ]