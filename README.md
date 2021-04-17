目录 | 说明 | 默认构建库 | 启动方式
---  | --- | --- | ---
mysql5-utf8 | mysql 5.7 设置字符为 utf8 | registry.cn-chengdu.aliyuncs.com/canxing-registry/mysql:5.7-utf8 |
Elasticsearch | elasticsearch-prometheus-exporter 插件的 elasticsearch，tag 和 Dockerfile 所在文件夹名称一致 | registry.cn-chengdu.aliyuncs.com/canxing-registry/elasticsearch-prometheus-exporter |
kibana | 镜像下载缓慢，通过阿里云重新 tag  | registry.cn-chengdu.aliyuncs.com/canxing-registry/kibana/kibana:7.5.2 |
tools | 下载一些资源保存到镜像中 | |
tiller | 重新制作 | registry.cn-chengdu.aliyuncs.com/canxing-registry/tiller |
grafana-report | grafana panel 打印成 pdf，支持自定义 grafana 前缀。基础镜像 https://github.com/IzakMarais/reporter | registry.cn-chengdu.aliyuncs.com/canxing-registry/grafana-reporter:2.3.1 |
composer | 单纯的制作 1.7 tag 镜像，原 1.7 tag 镜像已经不再更新，有镜像漏洞问题 | registry.cn-chengdu.aliyuncs.com/canxing-registry/composer:1.7