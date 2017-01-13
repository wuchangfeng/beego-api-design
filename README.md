# beego-api-design
Design restful api with beego and generate doc automaticlly.[related article here.](http://allenwu.itscoder.com/use-beego-generate-api-and-know-swagger) and also you can test the api [Here.](https://goapi-ahme.rhcloud.com/swagger/)

**Sql**
``` sql
CREATE TABLE `app` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `create_date` datetime NOT NULL,
  `app_code` varchar(255) COLLATE utf8_unicode_ci NOT NULL,
  `app_name` varchar(255) COLLATE utf8_unicode_ci NOT NULL,
  `publish_date` date DEFAULT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `app_code` (`app_code`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci;
```

**GetAll**
![](https://ws2.sinaimg.cn/large/b10d1ea5jw1fbg0erwh4vj21kw17hdrt.jpg)

**Limit**
![](http://ww1.sinaimg.cn/large/b10d1ea5jw1fbg0jrd2ruj21kw17htky.jpg)




