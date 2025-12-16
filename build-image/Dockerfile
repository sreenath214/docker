FROM bash
CMD ["ping", "google.com"]




Examples: 

FROM python:3.12.2-slim
WORKDIR /app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY . . 
CMD ["python", "app.py"]

# Build the image
docker build -t application .

# Run container 
docker run -d -p 8000:8000 application 