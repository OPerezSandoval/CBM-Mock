# Python image to use from Docker hub
FROM --platform=linux/amd64 python:3.9-slim

# Working Directory
WORKDIR /app

# Copy Directory contents into current directory
COPY . .

# Install all dependencies
RUN pip install -r requirements.txt

# Expose port 5001
EXPOSE 5001

#Run the application
CMD ["python", "app.py"]