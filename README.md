# SQL_learning
- 查询所有列  select * from user_profile   *代表所有行或列 navicat上建立连接后 点击查询 输入并运行
- select device_id,gender,age,university from user_profile;   查询所需列 如果多语句则必须要冒号 单一查询也可加上，养成习惯
- select Distinct university from user_profile    DISTINCT 关键字用于去除查询结果中的重复值    查询所涉及到的大学
- #查询结果限制返回行数#  select device_id from user_profile limit 2
- limit 2  限制返回前两行

