# Mirror Master

This repository is responsible for mirroring (cloning) images from Docker Hub to our own GitHub Container Repository
at https://github.com/orgs/voriteam/packages.

## Add or update an image version
Images are created or updated by running a workflow. The process only takes a minute (literally), 
but may take longer for larger images.

1. Go to https://github.com/voriteam/mirror-master/actions/workflows/mirror-master.yml.
2. Click "Run workflow".
3. Input the DockerHub image name and version (e.g., `redis:7`).
4. Click "Run workflow".
