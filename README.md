# docker-automated-build-bench

[![GuardRails badge](https://badges.production.guardrails.io/moul/docker-automated-build-bench.svg)](https://www.guardrails.io)

Benchmarking Docker automated builds

first goal: get the equivalent of [this](https://imagelayers.io/?images=golang:1.4,golang:1.4-onbuild,golang:1.4-wheezy,golang:1.4-cross) (real inheritance between images) using automated builds, and without manually triggering build of children images once a build is successfuly finished.

---

* Docker: https://hub.docker.com/r/moul/docker-automated-build-bench/
* Image layers: https://imagelayers.io/?images=moul%2Fdocker-automated-build-bench:aa,moul%2Fdocker-automated-build-bench:ab,moul%2Fdocker-automated-build-bench:ac,moul%2Fdocker-automated-build-bench:ba,moul%2Fdocker-automated-build-bench:bb,moul%2Fdocker-automated-build-bench:bc,moul%2Fdocker-automated-build-bench:d,moul%2Fdocker-automated-build-bench:ea,moul%2Fdocker-automated-build-bench:eb,moul%2Fdocker-automated-build-bench:ec
