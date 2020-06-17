# Some codes for daily work

## Docker

- remove all untagged docker images

```
docker rmi $(docker images | grep "^<none>" | awk "{print $3}")

```