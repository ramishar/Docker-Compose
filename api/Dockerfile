# Use python:3.9-slim as the base image
FROM python:3.9-slim

# Create a working directory /app inside the container
WORKDIR /app

# Copy the current directory contents to /app in the container
COPY . /app

# Install the requirements.txt file
RUN pip install -r requirements.txt

# Expose port 8080 inside the container
EXPOSE 8080

# Command to run the API using Uvicorn
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8080"]
