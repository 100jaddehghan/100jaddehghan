<h1 align="center">Hey, I’m Sajad 👋</h1>

<p align="center"><strong>Python developer exploring DevSecOps</strong></p>

<p align="center">
  <a href="https://github.com/100jaddehghan/secure-delivery-lab"><img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&amp;logo=fastapi&amp;logoColor=white"></a>
  <a href="https://github.com/100jaddehghan/secure-delivery-lab/blob/main/Dockerfile"><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white"></a>
  <a href="https://github.com/100jaddehghan/secure-delivery-lab/actions"><img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&amp;logo=githubactions&amp;logoColor=white"></a>
</p>

---

## ⚡ Secure Delivery Lab

[![Secure delivery workflow status](https://github.com/100jaddehghan/secure-delivery-lab/actions/workflows/delivery.yml/badge.svg?branch=main)](https://github.com/100jaddehghan/secure-delivery-lab/actions/workflows/delivery.yml)

A small FastAPI service that demonstrates how a container earns its way into a registry.

| What happens | See it in action |
| --- | --- |
| A healthy build is tested, audited, scanned with Trivy, and published to GHCR | [Successful pipeline ↗](https://github.com/100jaddehghan/secure-delivery-lab/actions/runs/45274858635) |
| A change to the API response fails the health contract test | [Failed test demo ↗](https://github.com/100jaddehghan/secure-delivery-lab/pull/1) |
| A previous image can be selected by digest for rollback | [Rollback instructions ↗](https://github.com/100jaddehghan/secure-delivery-lab#roll-back) |

[Explore the source and setup instructions →](https://github.com/100jaddehghan/secure-delivery-lab#readme)

## 🐍 In the Python community

[Did the test fail for the right reason?](https://github.com/pytest-dev/pytest/discussions/15390#discussioncomment-19841835) I ran the same health check against two versions of the app and compared the failing assertion.
