## 🚀 Deployment Architecture

The project uses GitHub Actions for CI/CD, deploying a Vite-powered 3D React portfolio to an S3 bucket. CloudFront serves the static content globally with HTTPS.

```plaintext
GitHub → GitHub Actions → S3 → CloudFront → Dashboard (User)
![Deployment Architecture](/architecture.png)


---

### 🔹 3. **Push and View on GitHub**

Once pushed:
- Visit your repo homepage
- Scroll to the `README.md`
- ✅ Image will render inline!

---

### ✅ If You Want to Use Raw GitHub Link Instead:

After uploading the image, this will work too:

```markdown
![Architecture](https://github.com/CloudServicesSys/3D-Portfolios-Web/blob/main/architecture.png)
