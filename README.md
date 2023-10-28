# Stratix 

[![build-stratix](https://github.com/tulilirockz/stratix/actions/workflows/build.yml/badge.svg)](https://github.com/tulilirockz/stratix/actions/workflows/build.yml) 

Arch-based container for development purposes, It already has a lot of utilities and Paru installed by default

## Verification

These images are signed with sisgstore's [cosign](https://docs.sigstore.dev/cosign/overview/). You can verify the signature by downloading the `cosign.pub` key from this repo and running the following command:

    cosign verify --key cosign.pub ghcr.io/ublue-os/arch-distrobox
