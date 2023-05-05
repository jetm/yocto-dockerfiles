# fedora-38-base
# Copyright (C) 2021 Intel Corporation
# Copyright (C) 2021-2022 Konsulko Group
# Copyright (C) 2023 Linaro Ltd
#
# SPDX-License-Identifier: GPL-2.0-only
#

FROM fedora:38

ENV LANG C.UTF-8

RUN dnf -y update && \
    dnf -y install \
	# These packages were copied straight from the Yocto Project reference
        # manual which is why they are not alphabetized 
        gawk \
        make \
        wget \
        tar \
        bzip2 \
        gzip \
        python3 \
        unzip \
        perl \
        patch \
        diffutils \
        diffstat \
        git \
        cpp \
        gcc \
        gcc-c++ \
        glibc-devel \
        texinfo \
        chrpath \
        ccache \
        perl-Data-Dumper \
        perl-Text-ParseWords \
        perl-Thread-Queue \
        perl-bignum \
        socat \
        python3-pexpect \
        findutils \
        which \
        file \
        cpio \
        python \
        python3-pip \
        xz \
        python3-GitPython \
        python3-jinja2 \
        SDL-devel \
        xterm \
        rpcgen \
	lz4 \
	zstd \
        \
        # These packages were added because of reasons such as fewer packages
        # being in the container image by default
        iproute \
        iputils \
        fluxbox \
        glibc-langpack-en \
        hostname \
        procps \
        python-unversioned-command \
        subversion \
        sudo \
        screen \
        tigervnc-server \
        tmux \
    glibc-locale-source \
    glibc-langpack-en

