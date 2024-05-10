FROM odoo:13.0

USER root

COPY ./requirements.txt /mnt/extra-addons/requirements.txt

RUN set -e; \
    pip3 install --no-cache-dir -r /mnt/extra-addons/requirements.txt


