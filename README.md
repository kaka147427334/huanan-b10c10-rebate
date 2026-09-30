# B10+C10 获取返利看板（华南大区）

固定在线链接：https://kaka147427334.github.io/huanan-b10c10-rebate/

## 更新方式（勿更换链接）
1. 替换源 Excel，修改 build/build_rebate.py 中的 SRC 路径；
2. 运行 python3 build/build_rebate.py，重新生成 deploy-rebate/index.html；
3. 用 GitHub Contents API PUT 覆盖本仓库 index.html（需带当前文件 sha），线上链接保持不变。

## 口径
- 档位：锁单达成率 >=120% 1500元/台，>=100% 1000，>=80% 500，<80% 0
- 预估返利 = 9月B10&C10交付实际 x 档位单价
- 开关项：交付达成率>=80% 且 8/9月退订率<=20%
