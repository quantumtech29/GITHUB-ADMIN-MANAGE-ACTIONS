# 🚀 GITHUB-ADMIN-MANAGE-ACTIONS

A DevOps starter project focused on GitHub Actions, Docker containerization, and Node.js package publishing.

[![CI](https://github.com/nogibjj/devops-skills-with-GitHub/actions/workflows/main.yml/badge.svg)](https://github.com/nogibjj/devops-skills-with-GitHub/actions/workflows/main.yml)
[![Codespaces Prebuilds](https://github.com/nogibjj/devops-skills-with-GitHub/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/nogibjj/devops-skills-with-GitHub/actions/workflows/codespaces/create_codespaces_prebuilds)
[![AWS CodeBuild](https://codebuild.us-east-1.amazonaws.com/badges?...)](https://codebuild.us-east-1.amazonaws.com)
[!(https://docs.github.com/en/actions/tutorials/publish-packages/publish-nodejs-packages)
---

## ⚙️ GitHub Actions Highlights

- CI/CD pipelines triggered on release
- Docker builds and container pushes
- Node.js package publishing with secure token injection
- Codespaces prebuilds for instant dev environments

---

## 🐳 Docker Workflow

```bash
docker build .
docker image ls
docker run -p 127.0.0.1:8080:8080 <your-image-id>
