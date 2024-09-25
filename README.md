## Health Checks for hubverse packages

This repository runs health checks on released hubverse packages.

### Weekly R CMD check

Status: [![R CMD check workflow](https://github.com/hubverse-org/pkg-health-check/actions/workflows/check-standard.yaml/badge.svg)](https://github.com/hubverse-org/pkg-health-check/actions/workflows/check-standard.yaml)

The R ecosystem is constantly changing. While the individual packages run checks
on the development versions weekly, the packages hosted on the R-universe only
run their checks monthly. This workflow allows us to run weekly checks on the
released versions.
