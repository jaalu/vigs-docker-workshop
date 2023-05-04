FROM ubuntu:22.04
ENV BATCH_SIZE=128
RUN apt-get update && apt-get install -y python3
COPY train.py /experiment/train.py
CMD python3 /experiment/train.py