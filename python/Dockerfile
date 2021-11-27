FROM ubuntu:latest
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update -y
RUN apt-get install -y tzdata
RUN apt-get install -y python3-pip 
RUN apt-get -y install tesseract-ocr
RUN apt-get -y install libtesseract-dev
RUN pip install pillow
RUN pip install pytesseract
RUN pip install opencv-python-headless
RUN pip install matplotlib ipykernel

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

WORKDIR /app/python

CMD python3 test.py
