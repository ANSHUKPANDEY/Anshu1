FROM python:alpine3.7
COPY . /app
WORKDIR /app
RUN sudo pip install -r flask
EXPOSE 5000
CMD python ./index.py
