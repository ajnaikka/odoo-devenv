FROM odoo:15.0

USER root

COPY ./requirements.txt /mnt/extra-addons/requirements.txt

RUN set -e; \
    pip install --no-cache-dir -r /mnt/extra-addons/requirements.txt


