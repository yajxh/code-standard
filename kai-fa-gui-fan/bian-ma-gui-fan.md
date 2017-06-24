* 所有的DTO都需要实现Serializable这个接口；
* JAVA-----&gt;FLEX 这一段逻辑如果以前用的是DTO传输的那么后面增加需求只能用DTO，如果以前用的是BO传输的，那么增加需求的时候也只能使用BO传输；不允许把以前的BO转成DTO或者把DTO转成BO，这样很容丢失数据；
* 资源文件的描述不能再代码中写死，java使用MessageSource
* 不允许直接校验从DICT中获取的boolean对象，禁止写如下代码： !dict.getBoolean\("INDEPPROD\_FLAG"\) ；



