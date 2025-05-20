# Python base image

FROM python:3.12.1

# Set work directory

WORKDIR /app

# Copy all files into the container

COPY . .

# Install dependencies

RUN pip install --upgrade pip
RUN pip install flask

# Expose the port the app runs on

EXPOSE 80

# Run the application

CMD ["python", "matches.py"]
