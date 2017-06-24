* CRM调用开通同一个服务 只能写一处通用调用的地方，不可以多处写；

* subs\_id,acct\_id,cust\_id在flex代码中需要使用字符串类型，不能使用int类型来定义；如果这些变量在一个对象中需要强转成字符串；tempSubs = {  
  SUBS\_PLAN\_ID : item.SUBS\_PLAN\_ID,  
  SUBS\_ID : String\(item.SUBS\_ID\)  
  };

* CRM产品，不允许给添加带任何项目前缀的脚本，以后SA把项目化的脚本添加到产品的单子上面，开发可以直接回退回去；
* 获取CONFIG\_ITEM\_PARAM表的数据 使用 如下方式：ConfigItemCache.instance\(\).getString\("CUSTOMER\_CARE/CC\_PUBLIC/SAME\_FLOW\_4\_SERV\_TYPE"\)

  ConfigItemCache.instance\(\).getLong\("INVENTORY.PUBLIC\_RES.BATCH\_THREAD\_NUM", 5\);



