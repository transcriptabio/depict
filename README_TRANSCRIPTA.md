# Transcripta Customizations

Compared to the main version, this fork includes customization of display
defaults in `cdkdepict-webapp/src/main/webapp/WEB-INF/static/depict.html`

## Build and push Transcripta-internal version

```sh
docker build -t cdkdepict -f docker/Dockerfile .
docker tag cdkdepict us-west1-docker.pkg.dev/rarebase-repo/cdkdepict/cdkdepict
docker push us-west1-docker.pkg.dev/rarebase-repo/cdkdepict/cdkdepict
```
