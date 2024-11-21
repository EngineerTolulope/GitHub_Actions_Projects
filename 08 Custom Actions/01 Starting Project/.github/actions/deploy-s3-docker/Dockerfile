FROM python:3

COPY requirements.txt /requirements.txt

RUN pip install -r requirements.txt

RUN pip install --upgrade boto3 botocore

COPY deployment.py /deployment.py

CMD ["python", "/deployment.py"]