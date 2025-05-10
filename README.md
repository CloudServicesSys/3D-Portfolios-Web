## 🚀 Deployment Architecture

The project uses GitHub Actions for CI/CD, deploying a Vite-powered 3D React portfolio to an S3 bucket. CloudFront serves the static content globally with HTTPS.

```plaintext
GitHub → GitHub Actions → S3 → CloudFront → Dashboard (User)
