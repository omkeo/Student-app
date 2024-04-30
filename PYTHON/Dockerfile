# Use the official Python image as the base image
FROM python:3.9-slim

# Set a working directory inside the container
WORKDIR /app

# Create a file named app.py and add the message
RUN echo "print('Hello, Docker!')" > app.py

# Command to run the application
CMD ["python", "app.py"]
