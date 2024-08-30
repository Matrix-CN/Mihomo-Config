subconverter支持在配置文件中引用clash的.yaml格式rule-set，不过需要在链接前加上源文件类型：clash-classic、clash-ipcidr、clash-domain。例

ruleset=DIRECT,clash-ipcidr:https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/ChinaIPsBGP/ChinaIPsBGP_IP.yaml
ruleset=BiliBili,clash-classic:https://raw.githubusercontent.com/dler-io/Rules/main/Clash/Provider/Media/Bilibili.yaml
ruleset=AdBlock,clash-domain:https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/test/rule/Clash/Advertising/Advertising_Domain.yaml
