# use a Python base image in version
FROM python:3.8
LABEL maintainer="Gbonjubola Adelokun"

COPY . /app
WORKDIR /app

# install packages defined in requirements.txt
RUN pip install -r requirements.txt

# expose the port 3111
EXPOSE 3111

# command to run on container start
CMD ./startup.sh
