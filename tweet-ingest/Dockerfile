FROM python:2

RUN pip install --upgrade pip
RUN pip install tweepy
RUN pip install --upgrade google-api-python-client
RUN pip install python-dateutil

ADD tweet-ingest/tweet-ingest.py /tweet-ingest.py
ADD python-utils/utils.py /utils.py

CMD python tweet-ingest.py