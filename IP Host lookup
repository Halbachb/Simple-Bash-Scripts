#!/bin/bash

for i in `seq 0 255`; do host $1.$i; done | grep " domain name" | cut -d " " -f 1,5 | sed -e 's/ /,/' > hosts.csv
