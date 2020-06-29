# production stage
FROM caddy:2 as production-stage
WORKDIR /usr/share/caddy
COPY . .
EXPOSE 2018
CMD ["caddy", "run", "--config=Caddyfile"]
