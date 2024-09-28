ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache ympd=1.3.0-r12

ENTRYPOINT [ "/init" ]
CMD []
COPY root /
