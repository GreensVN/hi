FROM mcr.microsoft.com/devcontainers/base:debian-12
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y --no-install-recommends \
    xfce4 xfce4-goodies \
    dbus-x11 x11-xserver-utils \
    tigervnc-standalone-server tigervnc-common \
    novnc websockify \
    supervisor \
    firefox-esr \
    locales tzdata \
    ca-certificates curl wget git nano \
    psmisc procps htop \
    unzip zip p7zip-full \
    fonts-dejavu fonts-noto-core fonts-noto-color-emoji \
  && apt-get clean && rm -rf /var/lib/apt/lists/*
