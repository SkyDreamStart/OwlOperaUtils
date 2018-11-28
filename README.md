# 本体操作类 OntoOperUtils
+ 基于https://pythonhosted.org/Owlready2
## 一、本体文件存储、读取 OntoFileOpera
- 读取本体文件

	```
	readOwl(cls, fileName):
	```
- 存储本体文件

	```
	saveOwl(cls, fileName)
	```
## 二、本体内容创建 OntoContentCreat
- 本体文件创建:

	```
	creatOwl(cls, fileName)
	```
- 本体对象创建:

	```
	creatOwlClass(cls, fileName, Name, proOwlName)
	```
- 本体关系创建

	```
	creatOwlRelat(cls, fileName, relationName, proRelatName, domainName, rangeName)
	```
- 本体备注创建

	```
	creatOwlAnno(cls, fileName, className, property, value)
	```
## 三、本体内容查询 OntoContentSearch
## 四、本体内容删除 OntoContentDelete
