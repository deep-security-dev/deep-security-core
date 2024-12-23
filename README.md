# Deep Security Dev Project

This project integrates three repositories into a CI/CD pipeline using GitHub Actions, GitHub Packages, and GitHub Pages.

---

## Repositories

1. [**deep-security-core**](https://github.com/deep-security-dev/deep-security-core): Core application logic.
2. [**deep-security-utils**](https://github.com/deep-security-dev/deep-security-utils): Utility library.
3. [**deep-security-api**](https://github.com/deep-security-dev/deep-security-api): API service.

---

## Workflows

### Build and Upload Workflow
1. Pulls code from all repositories.
2. Scans code and built artifacts for vulnerabilities.
3. Uploads artifacts to GitHub Packages.

### Deploy Workflow
1. Downloads artifacts from GitHub Packages.
2. Scans downloaded artifacts for vulnerabilities.
3. Deploys the application to GitHub Pages.

---

## Deployment URL

The deployed application can be accessed at:
`https://deep-security-dev.github.io/deep-security-core/`

---

## Contributing

1. Fork the repository.
2. Clone your fork: `git clone https://github.com/deep-security-dev/<repo>.git`
3. Create a new branch: `git checkout -b feature-branch`
4. Commit your changes and create a pull request.
