FROM python:3.7

ADD packages.txt /srv/packages.txt
ADD emoji /srv/emoji
ADD flag /flag

RUN apt update && \
    apt install -y ghostscript && \
    pip install -r /srv/packages.txt

EXPOSE 8080

CMD ["python", "/srv/emoji/app.py"]