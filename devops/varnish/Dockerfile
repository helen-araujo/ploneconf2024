# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Helen Araujo <collective@plone.org>" \
      org.label-schema.name="ploneconf2024-varnish" \
      org.label-schema.description="Treinamento Conferencia Plone Varnish image." \
      org.label-schema.vendor="Helen Araujo"

COPY etc/varnish.vcl /etc/varnish/default.vcl
