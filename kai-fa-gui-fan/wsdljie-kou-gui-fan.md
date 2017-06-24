* 当返回字段是list，必选时，返回：maxOccurs="unbounded"  type=xxx

* 当返回字段是list，可选时，返回：nillable="true"  minOccurs="0"  maxOccurs="unbounded"  type=xxx

* 当返回字段是string，必选时，返回：type=xxx

* 当返回字段是string，可选时，返回：nillable="true" minOccurs="0" type=xxx

* WS接口设置数组的方式：&lt;extension&gt;&lt;maxOccurs&gt;-1&lt;/maxOccurs&gt;&lt;/extension&gt;

* webservice的服务名需要以WS开头 ex:WSActivation 包括产品 定制 和 开通



