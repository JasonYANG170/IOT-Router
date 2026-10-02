# 凭据配置 / Credential configuration

在本地 src/wifi_credentials.local.h 中设置 PROJECT_WIFI_SSID 和 PROJECT_WIFI_PASSWORD（至少 8 个字符）；配置前不启动热点。

Create src/wifi_credentials.local.h with PROJECT_WIFI_SSID and PROJECT_WIFI_PASSWORD (at least eight characters). The access point remains disabled until configured.

已公开的真实凭据仍须撤销或更换。历史重写不能清除其他人的克隆、Fork 或 GitHub 缓存。

Revoke or rotate real credentials that were exposed. Rewriting history does not remove other clones, forks, or GitHub caches.
