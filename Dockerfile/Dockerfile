FROM docker.io/pytorch/pytorch:2.5.1-cuda12.4-cudnn9-runtime

LABEL forked from https://github.com/little-file/stable-diffusion-webui
LABEL DEVEL=" github:little-file github link:https://github.com/little-file"


RUN conda install -y git && \
git clone https://github.com/little-file/stable-diffusion-webui.git


WORKDIR /workspace/stable-diffusion-webui



CMD [ "./webui.sh"]

