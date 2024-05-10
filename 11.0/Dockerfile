FROM odoo:11.0

USER root

COPY ./requirements.txt /mnt/extra-addons/requirements.txt

RUN set -e; \
    pip install --no-cache-dir -r /mnt/extra-addons/requirements.txt


