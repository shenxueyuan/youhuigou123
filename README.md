# youhuigou
使用springboot，hibernate，jpa分布式开发淘宝客系统：
1：获取淘宝数据模块 com.get.data
2: 前台展示模块  com.display.fore           :9002/fore/...
http://127.0.0.1:9002/fore
/PayController/alipay    阿里支付：
    QueryProductController/queryProductByPidGet?RecParameter
    QueryPageController/queryPage?RecParameter
    SearchProductController/createIndexMappingUseIK?RecParameter
    SearchProductController/productSearch?RecParameter
3：后台管理模块  com.management.background  :9001/background/services/...
4：搜索服务模块  com.service.search          :9003/search/services/...
5：单点登录模块  com.login.sso
6：支付模块      com.pay
7：工具模块，一二级类目处理等 com.util,集群，redis,elasticsearch