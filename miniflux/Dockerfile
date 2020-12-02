FROM miniflux/miniflux:2.0.25

ENV DB_HOST=

COPY wait-for ./wait-for

CMD [ "sh", "-c", "./wait-for ${DB_HOST} -- /usr/bin/miniflux" ]
