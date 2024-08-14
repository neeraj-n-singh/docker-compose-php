# Use the official Python image
FROM python:3.8-slim

# Set the working directory
WORKDIR /app

# Copy the application code
COPY app/ /app/

# Install Flask
RUN pip install Flask

# Expose port 5000
EXPOSE 5000

# Run the Flask app
CMD ["python", "app.py"]
