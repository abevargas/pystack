# Use an official Python runtime as a parent image
FROM python:latest

# Adding backend directory to make absolute filepaths consistent across services
WORKDIR /app/backend

# Install Python dependencies
RUN pip3 install --upgrade django graphene
