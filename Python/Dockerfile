FROM python:3.9

WORKDIR /app

RUN pip install flask netifaces

COPY app.py /app

EXPOSE 8000

CMD ["python", "app.py"]
