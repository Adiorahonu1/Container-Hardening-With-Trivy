FROM python:3.8-slim-buster

WORKDIR /app
COPY app.py .
RUN pip install flask==2.2.5

EXPOSE 5050
CMD ["python", "app.py"]

