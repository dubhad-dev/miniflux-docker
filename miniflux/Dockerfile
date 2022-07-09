FROM miniflux/miniflux:2.0.37

COPY wait-for ./wait-for

EXPOSE 8080

CMD [ "sh", "-c", "./wait-for ${DB_HOST} -- /usr/bin/miniflux" ]
