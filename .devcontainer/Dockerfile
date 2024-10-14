FROM mcr.microsoft.com/vscode/devcontainers/universal:linux

RUN apt-get purge --auto-remove python3.10
RUN apt-get purge --auto-remove python3.9
COPY conda-environment.yml .
RUN conda env create -f conda-environment.yml
