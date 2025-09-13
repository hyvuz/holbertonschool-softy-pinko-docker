FROM python:3.10-slim

WORKDIR /app
COPY ./api.py /app/api.py

RUN pip install flask flask-cors

EXPOSE 5252
CMD ["python", "api.py"]
