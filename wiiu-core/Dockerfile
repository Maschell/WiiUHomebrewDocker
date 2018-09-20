FROM devkitpro/toolchain-base

MAINTAINER Maschell <maschell@gmx.de>

RUN apt-get install -y xxd p7zip-full

RUN dkp-pacman -Syyu --noconfirm devkitPPC general-tools && \
    dkp-pacman -Scc --noconfirm

ENV DEVKITPPC=${DEVKITPRO}/devkitPPC
