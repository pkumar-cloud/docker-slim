## 1. Which base image do you want to use?
FROM python:3.8-slim

## 2. Set the working directory.
WORKDIR /app

## 3. Copy your source code file to the working directory.
COPY python-app.py .
#OR COPY python-app.py /app
#OR COPY . .

## 4. Define the command to run when the container starts.
CMD [ "python", "python-app.py" ]

#Command
# docker build -t python-app .
# docker run --rm --name myApp python-app
# docker run -it --rm --name myApp python-app /bin/sh
