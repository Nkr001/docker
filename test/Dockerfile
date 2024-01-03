# Use an official Python runtime as a base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /usr/src/app

# Install Boto3 (AWS SDK for Python)
RUN pip install boto3

# Copy the rest of the application code to the container
COPY . .

# Define the command to run your application
CMD ["python", "your_script.py"]

