FROM python:3.9-slim
COPY /frontend /app
WORKDIR /app
RUN pip install flask
RUN pip install requests
CMD ["python", "app.py"]

