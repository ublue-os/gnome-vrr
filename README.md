[![build-ublue](https://github.com/ublue-os/gnome-vrr/actions/workflows/build.yml/badge.svg)](https://github.com/ublue-os/gnome-vrr/actions/workflows/build.yml)

# GNOME VRR

A layer for building GNOME VRR from [this COPR](https://copr.fedorainfracloud.org/coprs/kylegospo/gnome-vrr/)

# Usage

# Features

## Verification

These images are signed with sisgstore's [cosign](https://docs.sigstore.dev/cosign/overview/). You can verify the signature by downloading the `cosign.pub` key from this repo and running the following command:

    cosign verify --key cosign.pub ghcr.io/ublue-os/ubuntu
