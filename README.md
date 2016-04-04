# mybatis-code-generator
参考 http://git.oschina.net/free/Mapper/blob/master/wiki/mapper3/7.UseMBG.md

使用方式
修改`config.properties`中的数据库配置
修改`generatorConfig.xml`中的表名（%来匹配所有表）
修改`pom.xml`中的输出路径

运行
`mvn mybatis-generator:generate`即可
