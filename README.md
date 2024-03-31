# pydio-cells-arm64-build-script
The dockerfile and basic docker compose file for build an arm64 container for pydio cells.
## How to use
Sample script to build the Docker image.
```bash
docker build --build-arg version=4.3.6 -t pydio/cells:arm64 .
```
The version is can be found at the pydio's [website](https://pydio.com/en/download) like `Stable version: 4.3.6`.  

Make sure the `image: pydio/cells:arm` in `docker-compose.yaml` is the same as what you tagged the image with.  

For the jq, please refer to https://github.com/jqlang/jq/releases.

