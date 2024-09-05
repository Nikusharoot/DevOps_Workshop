FROM python:3.13.0rc1-alpine3.20
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . /app
WORKDIR /app
EXPOSE 80
CMD python ./clarusshop.py 