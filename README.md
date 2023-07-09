# django-docker-ci-cd

## Generate Treafik pass
```bash
echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g
```
