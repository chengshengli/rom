rom 坤腾固件仓库
=================

# HiWiFi
需要通过云平台打开开发者模式. 将固件上传到路由 /tmp 目录下
### B70/HC5962
<pre>
mtd write /tmp/xxx_sysupgrade.bin firmware
mtd erase firmware_backup
</pre>
