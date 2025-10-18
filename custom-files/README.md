# Custom Files

This directory contains custom firmware files and patches that will be copied during the build process.

## QCN9074 Firmware
Place your custom QCN9074 firmware files here and they will be automatically copied to `/lib/firmware/ath11k/QCN9074/hw1.0/` during the build.

## Usage
1. Place your custom firmware file(s) in this directory
2. Update the workflow to copy the specific file(s) you need
3. The files will be included in the final OpenWRT image
