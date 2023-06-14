# resume
[![Build Status](https://drone.yimian.xyz/api/badges/IoTcat/resume/status.svg)](https://drone.yimian.xyz/IoTcat/resume)

Yimian Liu's Resume

# PDF Version

[Yimian Liu's Resume](https://iotcat.github.io/resume/resume.pdf)


# Build
```shell
docker run --rm -v "$(pwd):/tmp" iotcat/latex latexmk -outdir=/tmp -pdf /tmp/resume.tex
```
