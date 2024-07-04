FROM python:3.12.4-alpine3.20
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . /app
WORKDIR /app
EXPOSE 80
CMD python ./clarusshop.py 