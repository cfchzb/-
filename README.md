spring:
  datasource:
    url: jdbc:mysql://127.0.0.1:3306/mybatis?userSSL=false&useUnicode=true&characterEncoding=UTF-8&serverTimezone=Asia/Shanghai
    username: root
    password: 123456
    driver-class-name: com.mysql.cj.jdbc.Driver
    
programmer:
  age: 20
  name: 伟大的李伟
  married: false
  hireDate: 2018/12/23
  salary: 66666.88
  random: ${random.int[1024,65536]}
  skill: {java: master, jquery: proficiency}
  company: [baidu,tengxun,alibaba]
