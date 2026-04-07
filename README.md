# shadowrocket-config

sr_ru_geo_full_proxy: geosite:ru + geoip:ru > direct, остальное в PROXY
sr_blocked_tier_1: geosite:ru + geoip:ru > direct, geosite:ru-blocked > proxy, остальное в DIRECT
sr_blocked_tier_2: geosite:ru + geoip:ru > direct, geosite:ru-blocked > proxy, остальное в DIRECT