# shadowrocket-config
Всегда: geosite:ru + geoip:ru + geosite:checkers > direct
sr_ru_geo_full_proxy: остальное в PROXY
sr_blocked_tier_1: geosite:ru-blocked > proxy, остальное в DIRECT
sr_blocked_tier_2: geosite:meta + geosite:youtube > proxy, остальное в DIRECT