# 活动奖品表

| 字段名 | 类型 | 描述 | 默认值 | 是否为空 |
| :--- | :--- | :--- | :--- | :--- |
| id | int | 活动规则自增主键 |  | 否 |
| discount | decimal\(10,2\) | 折扣 | 0 | 否 |
| reback\_money | decimal\(10,2\) | 返现券 | 0 | 否 |
| reduce\_money | decimal\(10,2\) | 减免券 | 0 | 否 |
| give\_goods\_id | int | 赠送商品的id | 0 | 否 |
| give\_score | int | 赠送积分 | 0 | 否 |

#### ps:5个条件可以自由的组合,如果其中一个不使用,则直接置其值为0即可



