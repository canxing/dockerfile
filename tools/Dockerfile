FROM registry.cn-chengdu.aliyuncs.com/canxing-registry/tiny-tools:latest
WORKDIR /root
RUN curl -o k3s.bin -sfL https://github.com/rancher/k3s/releases/download/v1.0.0/k3s
RUN curl -o k3s-airgap-images-amd64.tar -sfL https://github.com/rancher/k3s/releases/download/v1.0.0/k3s-airgap-images-amd64.tar
RUN wget https://ipfs.io/ipfs/Qmco94dYP733XwrUqFUhDtDG8RsqmGQ6UDPvnmH4Pvy2rv

RUN wget https://github.com/getlantern/lantern/releases/download/5.9.13/update_linux_amd64.bz2