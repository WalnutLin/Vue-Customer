//获取所有用户信息
http://localhost:3000/users

//获取 id 为 1 的用户信息
http://localhost:3000/users/1

//获取公司的所有信息
http://localhost:3000/companies

//获取单个公司的所有信息
http://localhost:3000/companies/1

//获取所有公司 id 为 3 的用户
http://localhost:3000/companies/3/users

//根据公司名字获取公司信息
http://localhost:3000/companies?name=Apple

//根据多个名字获取公司信息
http://localhost:3000/companies?name=Apple&name=XiaoMi

//获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2

//升序排序 asc 升序 desc 降序
http://localhost:3000/companies?_soft=name&_order=asc

//获取年龄为 30 及 30 以上的
http://localhost:3000/users?age_gte=30

//获取年龄在 30 到 40 之间
http://localhost:3000/users?age_gte=30&age_lte=40

//搜索用户信息 名字带有 e 的
http://localhost:3000/users?q=e
