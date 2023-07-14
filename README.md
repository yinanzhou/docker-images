# Miscellaneous Docker Images

Dockerfile of public image repo on https://hub.docker.com/u/yinanzhou.

Main Repo: https://gitlab.com/yinanzhou/docker-images

## Images

* [`yinanzhou/firebase:database-emulator`](https://hub.docker.com/r/yinanzhou/firebase) - Firebase CLI tool + OpenJDK 17 + Firebase Database Emulator cached
* [`yinanzhou/hugo`](https://hub.docker.com/r/yinanzhou/hugo) - Hugo + Go
* [`yinanzhou/wrangler`](https://hub.docker.com/r/yinanzhou/wrangler) - Cloudflare Wrangler CLI

## Periodic Re-compile

On a monthly basis, a cron job is triggers rebuild and push updated version of all the images in this repo to Docker Hub.