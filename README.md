# docker-images
示例
# Public Docker Hub image: defaults to the full multi-platform manifest and latest tag.
nginx:1.27
# Pull one platform only; platform is included in the destination tag.
--platform=linux/amd64 alpine:3.20
--platform=linux/arm64/v8 alpine:3.20
# Other public registries work by using their full image address.
ghcr.io/owner/public-image:1.2
quay.io/example/image:latest
# Private registries use the REGISTRY_AUTH_JSON repository secret.
registry.example.com/team/private-image:2.0
