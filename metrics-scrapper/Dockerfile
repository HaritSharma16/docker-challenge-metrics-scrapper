# Use a lightweight Python image as the base
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the application code into the container
COPY metrics-scrapper/app.py /app/

# Install dependencies
RUN pip install flask psutil

# Run the application
CMD ["python", "app.py"]

