<h1 align="center">Hey, I’m Sajad 👋</h1>

<p align="center"><strong>Cybersecurity · Python &amp; FastAPI · Windows development</strong></p>

## About me

I work in cybersecurity and build tools with Python. I write FastAPI services, develop Windows applications, and build plugins when an existing tool needs one more feature.

I’ve recently started exploring DevOps hands-on with Docker and GitHub Actions. My current lab takes a small FastAPI service from commit to a tested, scanned container image.

🍵 I drink enough tea to need a health check for the kettle.

---

## ⚡ Featured projects

### [Secure Delivery Lab](https://github.com/100jaddehghan/secure-delivery-lab)

A FastAPI service with a GitHub Actions pipeline that tests the code, audits dependencies, scans the container with Trivy, and publishes the verified image to GHCR.

**`Test` → `Audit` → `Build` → `Scan` → `Publish`**

[Explore the project](https://github.com/100jaddehghan/secure-delivery-lab#readme) · [See a successful run](https://github.com/100jaddehghan/secure-delivery-lab/actions/runs/45274858635) · [See a failed test demo](https://github.com/100jaddehghan/secure-delivery-lab/pull/1)

### [Taraaz](https://github.com/100jaddehghan/Taraaz)

A bilingual Windows desktop app for tracking freelance projects, billable hours, and payments. Built with Python, PyQt6, and SQLite.

[See the dashboard and run the demo](https://github.com/100jaddehghan/Taraaz#readme)

## 🛠️ Notes from the lab

- [Which digest proves the scanned image is the one that got published?](https://github.com/docker/buildx/discussions/4244) A Docker Buildx discussion with real CI logs and a follow-up on verifying the platform manifest in GHCR.
- [How can you tell if a regression test failed for the right reason?](https://github.com/pytest-dev/pytest/discussions/15390#discussioncomment-19841835) The same health check, run against two versions of a FastAPI service.

Follow along here for more small DevSecOps labs, with CI runs and notes you can reproduce.
