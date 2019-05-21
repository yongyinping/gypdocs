针对开发工具进行常用设置，提升开发效率。  

#### 去除mapper.xml文件中写sql语句背景色
在编写 mybatis 的 mapper.xml 映射文件时会出现大面积的黄色背景，看着很不舒服。去掉的步骤如下：
* 打开idea的Settings，找到Editor -> Inspections的配置页面。
* 去掉SQL中No data sources configured（没有配置数据源） 选项 和 SQL dialect detection（SQL方言检测） 选项，点击 OK。
