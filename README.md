# resume
[![Build](https://github.com/IoTcat/resume/actions/workflows/build.yml/badge.svg)](https://github.com/IoTcat/resume/actions/workflows/build.yml)

Yimian Liu's Resume

# PDF Version

[Yimian Liu's Resume](https://iotcat.github.io/resume/resume.pdf)


# Build
```shell
docker run --rm -v "$(pwd):/tmp" iotcat/latex latexmk -outdir=/tmp -pdf /tmp/resume.tex
```
