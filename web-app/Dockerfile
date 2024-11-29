# Use python:3.9-slim as the base image
FROM python:3.9-slim

# Create a working directory /app inside the container
WORKDIR /app

# Copy the current directory contents to /app in the container
COPY . /app

# Install the requirements.txt file
RUN pip install -r requirements.txt

# Expose port 5000 inside the container
EXPOSE 5000

# Command to run the application
CMD ["python", "app.py"]
