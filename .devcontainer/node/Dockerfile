# [Choice] Node.js version: 18, 16, 14
ARG VARIANT=16
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-${VARIANT}

ARG USERNAME=node

# Add daprd to the path for the VS Code Dapr extension.
ENV PATH "$PATH:/home/${USERNAME}/.dapr/bin"

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
