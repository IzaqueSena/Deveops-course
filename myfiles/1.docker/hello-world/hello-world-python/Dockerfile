# base image
FROM python:alpine3.10

# define work directory
WORKDIR /app 

# copy all files within context directory to /app folder
COPY . /app

# install all dependencies in the moment of image creation
RUN pip install -r requirements.txt

# listening on port 5000
EXPOSE 5000

# run application in the moment of container creation
CMD python ./main.py
