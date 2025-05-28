# Go Service with S3 template

This template instantiates a GitHub repository, an ArgoCD Application, Kubernetes reources, and an S3 bucket.

## Template composition

### Inputs

  1. Application name which is also used to name the GitHub repository.
  2. Owner of the GitHub repository
  3. Labels which are applied to Kubernetes manifests.
  4. S3 Bucket related information required to create the bucket.
