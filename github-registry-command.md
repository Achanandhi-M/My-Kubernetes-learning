Get the token from -> https.//github.com/settings/tokens/new?scopes=write:packages



export CR_PAT=ghp_XXXX

echo $CR_PAT | docker login ghcr.io -u <user-name> --password-stdin


docker tag <local-docker-image> ghcr.io/<user-name>/<image-name>:<version>

docker push  ghcr.io/<user-name>/<image-name>:<version>