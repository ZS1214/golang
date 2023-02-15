# golang
本项目是基于golang，gorm实现操作mysql数据库的书籍管理系统。
可以通过postman实现测试，实现功能如下：
1. get    localhost:8080/book/        获取数据库全部书籍信息
2. get    localhost:8080/book/（id）  根据书籍id查询书籍信息
3. post   localhost:8080/book/        向数据库新添加书籍信息
4. put    localhost:8080/book/（id）  修改数据库指定id书籍信息 
5. delete localhost:8080/book/（id）  删除数据库指定id书籍信息
