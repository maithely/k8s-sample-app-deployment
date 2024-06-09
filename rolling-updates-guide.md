
**rolling-updates-guide.md:**
```markdown
# Rolling Updates Guide

Kubernetes deployments support rolling updates by default. To perform a rolling update, use the `helm upgrade` command with the new image version:
```bash
helm upgrade my-nginx charts/nginx --set image.tag=new-version
