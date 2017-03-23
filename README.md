# MongoDB

##命令

use xxx  创建xxx数据库
show dbs 查看所有的数据库 `新创建的数据库不在列表中，需要先插入记录`
db.user1.insert({"name":"carrie","password":"123"}); 创建名为user1的集合并插入记录
db.user1.save({"name":"carrie","password":"123"}); 创建或更新名为user1的集合并插入记录
db.createCollection('user') 创建名为user的集合
show collections 查看所有集合
db.user1.find() 查看所有记录
 
db.dropDatabase() 删除当前数据库的所有记录
db.user.drop() 删除名为user的数据库
