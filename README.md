Repository to create a docker image containing Rails 6 and ruby 2.6.5.

# Create a new rails project using this image

```bash
> docker run --rm -ti -v $(pwd):/workdir -w /workdir p91challenge/rails 
```

# Build the image

To build the image locally, use the following command:

```bash
> DOCKER_BUILDKIT=1 docker build -t p91challenge/rails .
```
