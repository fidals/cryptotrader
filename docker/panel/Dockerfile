FROM python

COPY ./panel /usr/src
WORKDIR /usr/src
RUN pip install -r requirements.txt

CMD flask run --host=0.0.0.0
