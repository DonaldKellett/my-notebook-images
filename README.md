# my-notebook-images

My notebook images based on [Jupyter Docker Stacks](https://github.com/jupyter/docker-stacks), with useful libraries and extensions preloaded

## Goals

1. Create custom notebook images with libraries and extensions I find useful out of the box
1. Create custom notebook images used directly with [Podman](https://github.com/containers/podman) to streamline local development
1. Practice building and pushing custom multi-arch notebook images with [Buildah](https://github.com/containers/buildah)
1. Practice automating the OCI image build+push process with CI pipelines
1. Apply common sense best practices with image building

## Non-Goals

1. Create custom notebook images with libraries and extensions _everyone_ finds useful out of the box
1. Create custom notebook images which run directly on [Kubeflow](https://github.com/kubeflow/kubeflow) / [ODH](https://opendatahub.io/) / [RHOAI](https://www.redhat.com/en/products/ai/openshift-ai) for enterprise AI/ML use cases
1. Ensure that image CVEs are routinely patched by security hardening practices such as regularly reviewing dependencies and applying vulnerability scanners

## License

[BSD 3-Clause](./LICENSE)
