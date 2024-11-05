# Dockerfile
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy requirements.txt file
COPY requirements.txt .

# Install dependencies
RUN pip install -r requirements.txt

# Copy FastPI app
COPY . .

# Command to runt he FastAPI app using Uviconr
CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "80"]

