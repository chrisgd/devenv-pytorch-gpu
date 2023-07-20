# devenv-pytorch-gpu
Base project that sets up a Pytorch with GPU-enabled dev container for VSCode. This can just be used as a starting point for a Pytorch project or added to one to enable GPU support for machine learning.

Based on details from:
*  [https://](https://catalog.ngc.nvidia.com/orgs/nvidia/containers/pytorch)

You can pretty much just drop this into your top-level folder for VSCode. You need:

    https://www.docker.com
    GPU/compute drivers for your local platform (currently nvidia)

After that, you can reopen your repository and it should prompt you to open the dev environment.
