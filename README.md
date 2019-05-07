# mybaits 代码生成

## 步骤

* 修改/src/main/resources/config.properties中的数据库连接参数。
* 修改/src/main/resources/generatorConfig.xml，在末尾添加表名和实体类名的映射关系。
* 在supply/supply-gen目录下执行mvn mybatis-generator:generate -e。elipse或idea都可以预先配置好，直接点击即可生成。
* 生成的代码在supply/supply-gen/src/main/java中，选择自己需要的代码复制到自己的工作目录下。
* 该模块只用来生成代码，生成的代码不需要提交，防止其他人修改时冲突。

