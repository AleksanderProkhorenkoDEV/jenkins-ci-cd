# jenkins-playground
___
Recently I do a course of CI/CD with Jenkins, now I propose to do a repository where I can practice and share what I've learned. 
___
## Develop stack
* Docker
* Jenkins
* Git/Github
___
## Roadmap
### Fase 1 — Base environment
- [ ] Run Jenkins in Docker
- [ ] Jenkins initial setup (essential plugins, admin user)
- [ ] Docker Compose with Jenkins

### Fase 2 — First pipelines
- [ ] Basic declarative pipeline (stages: build, test, deploy)
- [ ] Environment variables in pipelines
- [ ] Credentials and secrets management
- [ ] Artifacts: save and publish build results

### Fase 3 — Docker agents
- [ ] Configure Docker agents in Jenkins
- [ ] Pipeline with Node.js agent
- [ ] Pipeline with Python agent
- [ ] Pipeline with Maven (Java) agent

### Fase 4 — Git integration
- [ ] Run Gitea as a local Git repository
- [ ] Connect Jenkins with Gitea
- [ ] Automatic build triggers with webhooks
- [ ] Multibranch Pipeline (one job per branch)

### Fase 5 — Code quality
- [ ] Run SonarQube in Docker
- [ ] Integrate SonarQube in the pipeline
- [ ] Quality gates: fail build on poor code quality

### Fase 6 — Best practices
- [ ] Shared Libraries: reusable code across pipelines
- [ ] Pipeline as Code: everything versioned in Git
- [ ] Conventional commits in the repository
- [ ] Full environment with Docker Compose (Jenkins + Gitea + SonarQube)
