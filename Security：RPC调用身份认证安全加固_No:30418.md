最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Security：RPC调用身份认证安全加固
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/193322.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.lg6lyk.asia/arts/422396.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.lg6lyk.asia/arts/375958.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.lg6lyk.asia/arts/383029.Doc

原标题：设计思考：消息顺序性架构保证与业务妥协
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.lg6lyk.asia/arts/578958.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/537400.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.lg6lyk.asia/arts/278607.Doc

原标题：重复提交幂等防护再次讲解
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.lg6lyk.asia/arts/233254.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.lg6lyk.asia/arts/479889.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/979181.Doc

原标题：golang prometheus metrics 埋点开发
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.lg6lyk.asia/arts/611014.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/866566.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.lg6lyk.asia/arts/930729.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.lg6lyk.asia/arts/609288.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/857695.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.lg6lyk.asia/arts/968399.Doc

原标题：Practice：实现接口防重提交组件实践
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.lg6lyk.asia/arts/714706.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.lg6lyk.asia/arts/531258.Doc

原标题：golang kafka 批量发送消费优化
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.lg6lyk.asia/arts/778171.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://wiki.lg6lyk.asia/arts/249592.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.lg6lyk.asia/arts/427962.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.lg6lyk.asia/arts/489777.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.lg6lyk.asia/arts/526444.Doc

原标题：golang lru 缓存淘汰算法编写
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.lg6lyk.asia/arts/012598.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.lg6lyk.asia/arts/375174.Doc

原标题：服务健康检查监控接口开发
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.lg6lyk.asia/arts/677725.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.lg6lyk.asia/arts/124733.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.lg6lyk.asia/arts/452980.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.lg6lyk.asia/arts/208388.Doc

原标题：golang aes 对称加密解密示例
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/265177.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/234811.Doc

原标题：golang 消息队列 kafka 消费开发
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.lg6lyk.asia/arts/633574.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.lg6lyk.asia/arts/318250.Doc

原标题：开发测试生产多环境配置区分
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.lg6lyk.asia/arts/727395.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.lg6lyk.asia/arts/151234.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.lg6lyk.asia/arts/904630.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.lg6lyk.asia/arts/209257.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.lg6lyk.asia/arts/127925.Doc

原标题：golang docker compose 完整语法
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/899830.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.lg6lyk.asia/arts/174160.Doc


二、踩坑排错｜Troubleshooting
原标题：跨域偶现失败配置修复
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.lg6lyk.asia/arts/594779.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/863769.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.lg6lyk.asia/arts/195864.Doc

原标题：数据库死锁成因规避方案
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.lg6lyk.asia/arts/372080.Doc

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/415460.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.lg6lyk.asia/arts/104338.Doc

原标题：golang websocket 服务端开发
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.lg6lyk.asia/arts/600385.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.lg6lyk.asia/arts/524761.Doc

原标题：golang redis zset 延时队列实现
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.lg6lyk.asia/arts/319699.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.lg6lyk.asia/arts/481464.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.lg6lyk.asia/arts/971160.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.lg6lyk.asia/arts/653941.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.lg6lyk.asia/arts/382358.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.lg6lyk.asia/arts/563726.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.lg6lyk.asia/arts/271509.Doc

原标题：业务错误码体系设计方案
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.lg6lyk.asia/arts/381834.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.lg6lyk.asia/arts/593761.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/797873.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.lg6lyk.asia/arts/855139.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.lg6lyk.asia/arts/159186.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.lg6lyk.asia/arts/796717.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.lg6lyk.asia/arts/974183.Doc

原标题：OAuth2 第三方登录服务搭建
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.lg6lyk.asia/arts/973362.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.lg6lyk.asia/arts/127994.Doc

原标题：golang minio 分片上传断点续传
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.lg6lyk.asia/arts/631943.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.lg6lyk.asia/arts/428510.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.lg6lyk.asia/arts/169454.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.lg6lyk.asia/arts/506628.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.lg6lyk.asia/arts/616063.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.lg6lyk.asia/arts/334438.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/080074.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/931336.Doc

原标题：golang channel 通道并发处理
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.lg6lyk.asia/arts/155155.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.lg6lyk.asia/arts/826329.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/901445.Doc

原标题：golang 时间时区处理避坑指南
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.lg6lyk.asia/arts/634644.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.lg6lyk.asia/arts/247462.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/944022.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/334291.Doc

原标题：代码格式化工具团队统一风格
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.lg6lyk.asia/arts/434876.Doc

三、实战开发｜Practice
原标题：golang 系统设计热点数据缓存处理
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/418736.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.lg6lyk.asia/arts/420330.Doc

原标题：golang redis pipeline 批量操作
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.lg6lyk.asia/arts/463113.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.lg6lyk.asia/arts/019507.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.lg6lyk.asia/arts/472802.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/593724.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.lg6lyk.asia/arts/945171.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.lg6lyk.asia/arts/941765.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.lg6lyk.asia/arts/636769.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.lg6lyk.asia/arts/522622.Doc

原标题：golang mysql 事务回滚异常处理
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.lg6lyk.asia/arts/789379.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.lg6lyk.asia/arts/621732.Doc

原标题：golang 系统信号信号量处理
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.lg6lyk.asia/arts/859216.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.lg6lyk.asia/arts/916527.Doc

原标题：golang 静态编译缩小镜像体积
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.lg6lyk.asia/arts/049113.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.lg6lyk.asia/arts/085810.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/159417.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.lg6lyk.asia/arts/934636.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.lg6lyk.asia/arts/430594.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/389550.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.lg6lyk.asia/arts/686821.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/216631.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.lg6lyk.asia/arts/678768.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.lg6lyk.asia/arts/445991.Doc

原标题：消息队列消费堆积扩容处理
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.lg6lyk.asia/arts/268550.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.lg6lyk.asia/arts/128780.Doc

原标题：golang github actions 发布 release 包
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.lg6lyk.asia/arts/342473.Doc

原标题：golang kafka 同步异步消费对比
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.lg6lyk.asia/arts/715839.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.lg6lyk.asia/arts/978612.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.lg6lyk.asia/arts/012477.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.lg6lyk.asia/arts/295518.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.lg6lyk.asia/arts/930400.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.lg6lyk.asia/arts/482926.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.lg6lyk.asia/arts/892170.Doc

原标题：golang 信号量控制并发数量
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.lg6lyk.asia/arts/197226.Doc

原标题：ICMP 放通网络丢包问题修复
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.lg6lyk.asia/arts/333799.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.lg6lyk.asia/arts/386883.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.lg6lyk.asia/arts/917519.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.lg6lyk.asia/arts/469515.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.lg6lyk.asia/arts/788403.Doc

四、架构设计｜Architecture
原标题：定时任务周期调度 demo 开发
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.lg6lyk.asia/arts/126953.Doc

原标题：golang k8s 基础概念 pod deployment
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.lg6lyk.asia/arts/153546.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.lg6lyk.asia/arts/137032.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.lg6lyk.asia/arts/545622.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.lg6lyk.asia/arts/930260.Doc

原标题：短信服务封装失败自动重试
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.lg6lyk.asia/arts/863831.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.lg6lyk.asia/arts/718176.Doc

原标题：golang 系统设计容器 OOM 故障完整排查
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.lg6lyk.asia/arts/593545.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.lg6lyk.asia/arts/759589.Doc

原标题：ICMP 放通网络丢包问题修复
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.lg6lyk.asia/arts/260057.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.lg6lyk.asia/arts/194224.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.lg6lyk.asia/arts/861483.Doc

原标题：版本升级服务启动失败处理
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.lg6lyk.asia/arts/370524.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.lg6lyk.asia/arts/503393.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://wiki.lg6lyk.asia/arts/012638.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.lg6lyk.asia/arts/487380.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.lg6lyk.asia/arts/678780.Doc

原标题：依赖版本冲突兼容修复方案
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.lg6lyk.asia/arts/269061.Doc

?
