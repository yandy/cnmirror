FROM node:22-bookworm

RUN set -eux; \
    sed -i 's/deb.debian.org/mirrors.aliyun.com/g' /etc/apt/sources.list.d/debian.sources; \
    npm config set registry https://registry.npmmirror.com
