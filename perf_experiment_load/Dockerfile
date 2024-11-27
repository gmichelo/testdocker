FROM ubuntu

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update -y

RUN apt-get update -y \
    && apt-get install -y --no-install-recommends \
    openssh-client \
    gnupg lsb-release zip build-essential \
    zstd libcurl4-openssl-dev inetutils-ping \
    jq locales time \
    python3-pip python3-setuptools python3 python3-venv\
    rsync tmux libyaml-dev libffi-dev libpq-dev \
    tzdata pkg-config brotli netcat-openbsd \
    gettext gcc bash moreutils \
    libpng-dev libpixman-1-dev libcairo2-dev librsvg2-dev \
    libpango1.0-dev libjpeg8-dev libgif-dev libgeos-dev \
    lsof wget ca-certificates \
    cmake libgit2-dev pkg-config \
    xvfb x11-xserver-utils \
    libnss3 libgbm-dev libatk1.0-0 libatk-bridge2.0-0 libcups2 libgtk-3-0 \
    libssl-dev software-properties-common \
    parallel \
    && rm -rf /var/lib/apt/lists/* \
    && rm -rf /tmp/*
