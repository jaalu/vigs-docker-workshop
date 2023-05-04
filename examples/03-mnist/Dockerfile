FROM ubuntu:22.04
ENV BATCH_SIZE=128
RUN apt-get update && apt-get install -y python3 python3-pip
WORKDIR /experiment/
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY train.py train.py
CMD python3 train.py