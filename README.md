# nextcloud-kube
简单将nextcloud docker官方镜像重写了下，相较官方镜像更改了两点：
  1. 修改镜像为无状态（需进一步验证），解决多节点部署问题，参考了https://github.com/vfreex/kube-nextcloud
  2. 支持自定义custom_apps,主要解决app商店下载慢问题。
