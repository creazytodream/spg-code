# spg-code

## MyCommon项目
个人工具包

### 工具包中主要含个人平时累积工具类，仅供学习交流


|包名|类名|功能说明|
|----|----|------|
|collectionutil|MyListUtil|集合截取，从指定位置到结束位置，如果结束位置大于集合长度，则已集合长度作为结束位置|
|collectionutil|MyMapUtil|Map排序、截取操作|
|collectionutil|ValueComparableMap|自定义map，存入此map中是数据会按value值进行排序存放，[升序]|
|common|CommonUtil|获取请求方IP，URL短码生成|
|dateutil|N/A|日期工具|
|enumutil|N/A|枚举工具|
|httputil|N/A|http工具|
|jsonutil|N/A|json工具|
|logutil|N/A|日志工具|
|mapperutil|N/A|mybatis中mapper工具类，公共CRUD接口|
|md5|N/A|MD5工具|
|myexception|N/A|自定义异常|
|page|N/A|分页工具|
|pojo|N/A|pojo工具|
|strutil|N/A|字符串工具|
|threadpool|N/A|线程池工具|

## apidoc项目
使用swagger实现api接口的示例。

## configcenter项目
个人实验项目。

## dubbo项目
淘宝开源RPC框架。

## spg-common项目
与上面MyCommon基本一致。

## swagger-ui项目
开源swaggerapi项目。

## countView项目

>简易埋点系统，项目使用Redis和SpringMVC框架，实现网站PV量、按钮点击量、链接点击量、用户活跃量、用户IP分布等的统计。

###统计项说明

**项目主要统计功能包含：**

1. 统计网站PV量。
2. 统计页面按钮点击量。
3. 统计页面链接等的点击量。
4. 统计每天活跃用户数。
5. 统计每天活跃用户IP分布情况等。

###项目使用步骤说明：

1. 将本项目中commoncount.js拷贝到你需要做埋点的项目某个目录中。
2. 将commoncount.js引入引入你需要做埋点的页面。
3. 再给调用相应的方法做相应统计。

###commoncount.js功能说明
1. userActive();
2. 
