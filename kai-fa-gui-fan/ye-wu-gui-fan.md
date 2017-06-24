* CRM调用开通同一个服务 只能写一处通用调用的地方，不可以多处写；
* 资源文件的描述不能再代码中写死，java使用MessageSource
* subs\_id,acct\_id,cust\_id在flex代码中需要使用字符串类型，不能使用int类型来定义；如果这些变量在一个对象中需要强转成字符串；tempSubs = {
  SUBS\_PLAN\_ID : item.SUBS\_PLAN\_ID,
  SUBS\_ID : String\(item.SUBS\_ID\)
  };
* CRM产品，不允许给添加带任何项目前缀的脚本，以后SA把项目化的脚本添加到产品的单子上面，开发可以直接回退回去；
* JAVA-----&gt;FLEX 这一段逻辑如果以前用的是DTO传输的那么后面增加需求只能用DTO，如果以前用的是BO传输的，那么增加需求的时候也只能使用BO传输；不允许把以前的BO转成DTO或者



