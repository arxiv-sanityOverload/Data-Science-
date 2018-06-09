FROM python:3.6.4

MAINTAINER Prakritidevverma@arxivoverload.com 

RUN pip install --upgrade pip

RUN pip install awscli

RUN mkdir ~/pdftotext

COPY . ~/pdftotext/

RUN cd ~/pdftotext

RUN ls

RUN pip install -r ~/pdftotext/requirements.txt

CMD ["python" "~/pdftotext/pdftotext.py"]



