# A Robot For Binance.com

## 币安交易机器人
含有以下不同机器人

- 买卖单机器人
- 盘口机器人
- 量化机器人
- 消息机器人

## 使用方法
1. env.example.php改为env.php
然后修改里面常量值的为自己的信息
2. php kx migrate:up 导入数据库
3. php kx robot:start 运行
4. php kx robot:stats 查看统计 