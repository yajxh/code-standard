* CRM调用开通同一个服务 只能写一处通用调用的地方，不可以多处写；
* 资源文件的描述不能再代码中写死，java使用MessageSource
* subs\_id,acct\_id,cust\_id在flex代码中需要使用字符串类型，不能使用int类型来定义；如果这些变量在一个对象中需要强转成字符串；tempSubs = {
  SUBS\_PLAN\_ID : item.SUBS\_PLAN\_ID,
  SUBS\_ID : String\(item.SUBS\_ID\)
  };



