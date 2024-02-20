# Self Usage Rules

## 更新日志

- 2024/02/05，经过多次测试QuantumultX在MacOS下无法解决公司内网域名解析问题，转而切换到Stash；
- 2024/02/20，增加 Google Gemini 访问规则；

## Stash

[配置](./stash/stash.conf)，需注意，通过 sub-store配置了订阅链接。

Stash基于Clash，社区有更多资料，配置逻辑更清晰，MacOS UI界面使用也更清晰。

### 配置更新日志

- 2024/02/05，更新了OpenAI相关规则，避免通过香港节点依然无法访问的问题。

## Quantumult X (已废弃)

<details>

[配置](./quantumultx/config.conf)，已包含订阅链接。

### 包含功能

- 内置[blackmatrix7](https://github.com/blackmatrix7)的开源分流规则
- 内置[KOP-XIAO](https://github.com/KOP-XIAO)的开源资源解析器和节点信息显示
- 内置[Peng-YM](https://github.com/Peng-YM)的Sub-Store订阅管理工具
- Quantumult X配置内置[chavyleung](https://github.com/chavyleung)的BoxJs脚本工具
- 内置香港最优节点选择、国内策略、国外策略和主流App分流规则以及美国、香港、日本、台湾、新加坡节点策略组
- Quantumult X配置增加Spotify重写解锁premium
- Quantumult X配置增加ChatGPT本地分流规则（访问前手动选择支持的节点）

## 脚本任务

- 流媒体解锁检测

## 图标扩展

*使用方法：打开App 长按 节点或策略 > 图标 > 点击右上角“+”，输入json链接*

- 国家地区图标【[country-icon.json](https://raw.githubusercontent.com/fanmingming/Rules/main/country-icon.json)】
- 策略图标【[filter-icon.json](https://raw.githubusercontent.com/fanmingming/Rules/main/filter-icon.json)】
- 机场图标【[airport-icon.json](https://raw.githubusercontent.com/fanmingming/Rules/main/airport-icon.json)】

> 策略与国家地区图标使用[erdongchanyo](https://github.com/erdongchanyo)的开源图标库，机场图标投稿【[请点这里](https://t.me/fanmingming)】

## GeoIP 库更新
使用方法：设置 -> 更多设置 -> GeoLite2 -> 资源，输入 [Loyalsoldier/geoip](https://raw.githubusercontent.com/Loyalsoldier/geoip/release/Country.mmdb) 链接，然后更新即可。

### Sub-Store & BoxJs

- 订阅管理工具，访问[https://sub.store](https://sub.store)
- BoxJs，访问[http://boxjs.com](http://boxjs.com)

</details>
