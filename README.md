# LLS-API

### 请求地址:

>https://app.lovelivesupport.com/lls-api/getAll.php

>https://app.llsupport.cn/lls-api/getAll.php

### 调用方式：
	
	HTTP GET

### 接口描述：

	LLSupport提供的开放性数据接口
	本API服务站点为公益性质运营方式，如果使用请参照一下文档并注明数据来源LLSupport

	注: 本站采用全域https方式加密 对于加密协议等详细信息访问SSLLabs查询
	.cn 为中国大陆地区内访问专线，针对中国大陆有较强的访问速度
	.com 为国际专用线路，为非中国大陆地区内有极好的访问速度



### 请求参数:

|字段名称       |字段说明         |类型            |必填            |字段选项        |
| -------------|:--------------:|:--------------:|:--------------:|:------:|
|type|请求类型|string|Y|card / live / event / maps / pair_card / c_card / card_s|

* 当type为card时，请求卡片有关信息:

	|字段名称       |字段说明         |类型            |必填            |字段选项        |
	| -------------|:--------------:|:--------------:|:--------------:|:------:|
	|id|编号|string|Y|0 / {unit_number}|
	|page|id=0时，page必填|string|Y|all / {page}|
	|lang|数据语言 默认为日本语|string|N|jp / en / cn / kr / tw|

	id=0&page=all 返回所有卡片基础信息

	```

	```


