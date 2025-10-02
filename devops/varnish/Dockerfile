# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Erivelton Jesus <eriveltongoncalo@gmail.com>" \
      org.label-schema.name="tremt-varnish" \
      org.label-schema.description="Treinamento TRE-MT Varnish image." \
      org.label-schema.vendor="Erivelton Jesus"

COPY etc/varnish.vcl /etc/varnish/default.vcl
