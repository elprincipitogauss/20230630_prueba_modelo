# Use an official Python runtime as the base image
FROM python:3.9
# Set the working directory in the container
WORKDIR /app
# Copy the requirements.txt file to the container
COPY requirements.txt .
# Install the Python dependencies
RUN pip install --no-cache-dir -r requirements.txt
# Copy the rest of the application files to the container
COPY . .
# Expose a port (if required)
EXPOSE 8000
# Specify the command to run when the container starts
CMD ["python", "app.py"]