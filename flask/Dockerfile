# Use python 3.9.4 container image
FROM python:3.9.4

#Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD . /app

# Install the dependencies
RUN pip install -r requirements.txt

# run the command to start uwsgi
CMD ["uwsgi", "app.ini"]