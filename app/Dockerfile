FROM python:3.10

WORKDIR usr/src/app

COPY req.txt .
RUN pip3 install -r req.txt
RUN pip3 install --no-cache-dir -r req.txt
COPY . .
