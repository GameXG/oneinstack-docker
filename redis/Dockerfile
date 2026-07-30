ARG REDIS_VERSION=8.4
FROM redis:${REDIS_VERSION}-alpine

LABEL org.opencontainers.image.title="OneinStack Redis"
LABEL org.opencontainers.image.source="https://github.com/Luan-X/oneinstack"

COPY redis.conf /usr/local/etc/redis/redis.conf

EXPOSE 6379
