FROM python:3.6.1

MAINTAINER Sindre Sivertsen (sindrejohan1@gmail.com)

# Copy files from actual computer to a folder named django
RUN mkdir /django
# RUN apt-get install build-dep python-psycopg2
WORKDIR /django
COPY requirements.txt /django
RUN pip install -r requirements.txt

COPY . /django
 
