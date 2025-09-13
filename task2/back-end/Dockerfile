FROM python:3.10-slim

WORKDIR /app
COPY ./api.py /app/api.py

RUN pip install flask

EXPOSE 5252
CMD ["python", "api.py"]
