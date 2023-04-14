FROM python:3

WORKDIR /var/tmp

ADD ./icap_server.py /sbin/
ADD ./requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 13440/tcp 13440/udp
CMD ["python", "/sbin/icap_server.py"]
