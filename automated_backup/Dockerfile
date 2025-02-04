FROM python:3.13.1-slim
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
CMD ["pytest", "tests"]
