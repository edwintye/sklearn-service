FROM edwintye/sklearn-base:18.04

RUN apt-get -y update \
    && pip install --upgrade --no-cache-dir --compile pip \
    && pip install --no-cache-dir --compile \
       flask gevent gunicorn \
    && rm -rf /var/lib/apt/lists/*

CMD ["python3"]
