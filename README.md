# a Django+Docker+Ci/CD course represented by the "DevOps Hobbies" channel on youtube
# django-ci-cd-NexusRegistry

## Generate Treafik pass
```bash
echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g
```
