# Using Pulumi YAML for S3 bucket Provisioning using GitHub Actions

## Installation
```
curl -fsSL https://get.pulumi.com | sh
pulumi stack new dev
pulumi stack select dev --non-interactive
pulumi preview -j
pulumi up --non-interactive
```