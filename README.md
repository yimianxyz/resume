# resume
[![Build Status](https://drone.yimian.xyz/api/badges/IoTcat/resume/status.svg)](https://drone.yimian.xyz/IoTcat/resume)

Yimian Liu's Resume

# Build
```shell
docker run --rm -t --user="$(id -u):$(id -g)" --net=none -v "$(pwd):/tmp" leplusorg/latex latexmk -outdir=/tmp -pdf /tmp/resume.tex
```
