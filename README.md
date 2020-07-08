# micro-weather-basic
# 技术
  1. SpringBoot
  2. Gradle
  3. Lombok
  4. HttpClient(RestTemple)
  5. Redis
 # 实现
  1. 获取天气数据
  2. 用户请求返回天气数据
    数据来源第三方API
    强依赖：导致其他系统调用接口有比较大的延时
    数据的搬运工-中介服务
    免费的接口存在风险
        请求次数
        并发数对第三方系统有影响
    解决办法：使用Redis来提升整个的应用的并发能力
  3. 展示
  4. 使用redis提升应用的并发访问能力
  
