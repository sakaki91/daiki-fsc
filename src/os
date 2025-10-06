#!/bin/bash

os=$(grep ^NAME= /etc/os-release | cut -d '=' -f2- | tr -d '"')
kernel=$(uname -rs)
uptime=$(uptime -p | cut -c4-)
echo "Operating System: $os"
echo "Kernel: $kernel"
echo "Uptime: $uptime"
