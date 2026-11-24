<h1 align="center">Hey, I’m Sajad 👋</h1>

<p align="center"><strong>Python · DevOps · Security</strong></p>
<p align="center">I’m learning DevSecOps by building small Python services and taking them from commit to container.</p>

---

## ⚡ Featured project

### [Secure Delivery Lab](https://github.com/100jaddehghan/secure-delivery-lab)

A FastAPI service with a GitHub Actions pipeline that tests the code, audits dependencies, scans the container with Trivy, and publishes the verified image to GHCR.

**`Test` → `Audit` → `Build` → `Scan` → `Publish`**

[Explore the project](https://github.com/100jaddehghan/secure-delivery-lab#readme) · [See a successful run](https://github.com/100jaddehghan/secure-delivery-lab/actions/runs/45274858635) · [See a failed test demo](https://github.com/100jaddehghan/secure-delivery-lab/pull/1)

## 🛠️ Notes from the lab

- [Which digest proves the scanned image is the one that got published?](https://github.com/docker/buildx/discussions/4244) A Docker Buildx discussion with real CI logs and a follow-up on verifying the platform manifest in GHCR.
- [How can you tell if a regression test failed for the right reason?](https://github.com/pytest-dev/pytest/discussions/15390#discussioncomment-19841835) The same health check, run against two versions of a FastAPI service.

Follow along here for more small DevSecOps labs, with CI runs and notes you can reproduce.
