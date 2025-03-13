FROM python:3.12-bookworm

RUN set -eux; \
    sed -i 's/deb.debian.org/mirrors.aliyun.com/g' /etc/apt/sources.list.d/debian.sources; \
    pip config set global.index-url https://mirrors.ustc.edu.cn/pypi/simple
