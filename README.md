# Quantumult X 香港银行分流规则

将两份 Clash 香港银行规则合并并转换为 Quantumult X 格式。默认策略为 `direct`（直连）。

## 使用方法

将 [BankHK.list](./BankHK.list) 的内容加入 Quantumult X 配置的 `[filter_local]` 部分。若要使用其他策略，将规则末尾的 `direct` 替换为配置中对应的策略名。

## 来源

- [Accademia 的 BankHK.yaml](https://github.com/Accademia/Additional_Rule_For_Clash/blob/main/Bank/BankHK.yaml)
- [HenryChiao 的 bank-hk.list](https://github.com/HenryChiao/the_clash_ruleset/blob/main/The_Location_rule-set/Bank_rule-set/bank-hk.list)

规则域名源自以上项目；格式转换及合并由本仓库完成。具体银行 App 可能使用列表以外的域名。
