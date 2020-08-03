FROM registry.cn-chengdu.aliyuncs.com/canxing-registry/tiny-tools:latest
WORKDIR /root
RUN curl -o k3s.bin -sfL https://github.com/rancher/k3s/releases/download/v1.0.0/k3s
RUN curl -o k3s-airgap-images-amd64.tar -sfL https://github.com/rancher/k3s/releases/download/v1.0.0/k3s-airgap-images-amd64.tar

# 2.9.0 webui 为了 go-ipfs:0.6.0-rc6
RUN wget https://ipfs.io/api/v0/get/bafybeigkbbjnltbd4ewfj7elajsbnjwinyk6tiilczkqsibf3o7dcr6nn4 && \
    mv bafybeigkbbjnltbd4ewfj7elajsbnjwinyk6tiilczkqsibf3o7dcr6nn4 webui-2.9.0

RUN wget https://ipfs.io/api/v0/get/QmfQkD8pBSBCBxWEwFSu4XaDVSWK6bjnNuaWZjMyQbyDub && \
    mv QmfQkD8pBSBCBxWEwFSu4XaDVSWK6bjnNuaWZjMyQbyDub webui

RUN wget https://github.com/getlantern/lantern/releases/download/5.9.13/update_linux_amd64.bz2