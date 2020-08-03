FROM registry.cn-chengdu.aliyuncs.com/canxing-registry/tiny-tools:latest
RUN cd /root
RUN curl -o k3s.bin -sfL https://github.com/rancher/k3s/releases/download/v1.0.0/k3s
RUN curl -o k3s-airgap-images-amd64.tar -sfL https://github.com/rancher/k3s/releases/download/v1.0.0/k3s-airgap-images-amd64.tar
RUN curl -O -sfL https://ipfs.io/ipfs/Qmco94dYP733XwrUqFUhDtDG8RsqmGQ6UDPvnmH4Pvy2rv