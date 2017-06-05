FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
WORKDIR /code
ADD requirements.txt /code/
RUN pip install -vvv --disable-pip-version-check --allow-unverified -r requirements.txt
ADD . /code/
