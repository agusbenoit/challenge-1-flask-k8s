FROM python:3.9-alpine

WORKDIR /app
COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

COPY . .

EXPOSE 8000
CMD ["python3", "app.py"]