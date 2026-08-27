最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.lrdkoi.asia/blog/8222758.sHtMl

原标题：golang 系统设计 websocket 协议原理梳理
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.lrdkoi.asia/blog/0406530.sHtMl

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.lrdkoi.asia/blog/4618751.sHtMl

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.lrdkoi.asia/blog/5194332.sHtMl

原标题：WSL 搭建 Windows Linux 开发环境
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.lrdkoi.asia/blog/6209502.sHtMl

原标题：K8s 镜像拉取网络故障修复
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.lrdkoi.asia/blog/9068998.sHtMl

原标题：golang prometheus histogram 指标
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.lrdkoi.asia/blog/1828649.sHtMl

原标题：全量回归测试提升代码质量
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.lrdkoi.asia/blog/1651372.sHtMl

原标题：golang 系统设计配置热更新不重启服务实现
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.lrdkoi.asia/blog/2514112.sHtMl

原标题：golang k8s 命名空间资源隔离方案
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.lrdkoi.asia/blog/1902202.sHtMl

原标题：golang kafka 核心概念分区副本
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.lrdkoi.asia/blog/6354078.sHtMl

原标题：项目实践：分布式会话Redis存储落地实践
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.lrdkoi.asia/blog/0283622.sHtMl

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.lrdkoi.asia/blog/9066484.sHtMl

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.lrdkoi.asia/blog/8948947.sHtMl

原标题：golang 错误处理最佳实践汇总
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.lrdkoi.asia/blog/5280614.sHtMl

原标题：优化实践：预加载与懒加载业务场景取舍
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.lrdkoi.asia/blog/9009912.sHtMl

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.lrdkoi.asia/blog/3254426.sHtMl

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.lrdkoi.asia/blog/0100352.sHtMl

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.lrdkoi.asia/blog/6494867.sHtMl

原标题：单元测试用例编写入门实操
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.lrdkoi.asia/blog/6777828.sHtMl

原标题：程序日志分级输出规范实践
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.lrdkoi.asia/blog/8245538.sHtMl

原标题：Nginx 请求头大小上限调整
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.lrdkoi.asia/blog/7174166.sHtMl

原标题：golang 系统设计数据库慢查询治理方案
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.lrdkoi.asia/blog/3352491.sHtMl

原标题：数据库索引重建提升查询速度
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.lrdkoi.asia/blog/8885946.sHtMl

原标题：批量操作分批处理防止 OOM
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.lrdkoi.asia/blog/7943032.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.lrdkoi.asia/blog/8668428.sHtMl

原标题：golang redis 主从复制哨兵原理
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.lrdkoi.asia/blog/9668003.sHtMl

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.lrdkoi.asia/blog/5120563.sHtMl

原标题：Dockerfile 编写容器打包实战
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.lrdkoi.asia/blog/1876687.sHtMl

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.lrdkoi.asia/blog/2104272.sHtMl

原标题：golang 系统设计监控告警体系搭建思路
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.lrdkoi.asia/blog/6245869.sHtMl

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.lrdkoi.asia/blog/0167214.sHtMl

原标题：零基础理解模块化与组件化基础思想
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.lrdkoi.asia/blog/4280286.sHtMl

原标题：golang redis lua 脚本开发调试
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.lrdkoi.asia/blog/1625230.sHtMl

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.lrdkoi.asia/blog/0744891.sHtMl

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.lrdkoi.asia/blog/4512969.sHtMl

原标题：monorepo 项目多包管理最佳实践
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.lrdkoi.asia/blog/9449163.sHtMl

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.lrdkoi.asia/blog/7403719.sHtMl

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.lrdkoi.asia/blog/5687707.sHtMl

原标题：避坑：版本升级之后项目直接无法启动
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.lrdkoi.asia/blog/6542146.sHtMl


二、踩坑排错｜Troubleshooting
原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.lrdkoi.asia/blog/1639387.sHtMl

原标题：开发记录：容器日志标准输出采集实践方案
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.lrdkoi.asia/blog/6787803.sHtMl

原标题：golang redis 缓存击穿防护实现
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.lrdkoi.asia/blog/6770398.sHtMl

原标题：WSL 搭建 Windows Linux 开发环境
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.lrdkoi.asia/blog/0566781.sHtMl

原标题：golang 系统设计 api 网关核心能力梳理
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.lrdkoi.asia/blog/7868328.sHtMl

原标题：golang jwt 鉴权中间件完整示例
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.lrdkoi.asia/blog/2518574.sHtMl

原标题：零基础理解缓存基础原理与简单使用
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.lrdkoi.asia/blog/2836206.sHtMl

原标题：golang 系统设计分布式事务几种方案
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.lrdkoi.asia/blog/6152960.sHtMl

原标题：golang redis 客户端业务使用
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.lrdkoi.asia/blog/9400231.sHtMl

原标题：golang minio 分片上传断点续传
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.lrdkoi.asia/blog/9754455.sHtMl

原标题：开发记录：表单参数校验统一中间件实现
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.lrdkoi.asia/blog/7798106.sHtMl

原标题：golang 结构体 json 序列化坑点
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.lrdkoi.asia/blog/0279031.sHtMl

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.lrdkoi.asia/blog/0740354.sHtMl

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.lrdkoi.asia/blog/6226748.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.lrdkoi.asia/blog/6882112.sHtMl

原标题：golang 静态编译缩小镜像体积
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.lrdkoi.asia/blog/8609453.sHtMl

原标题：golang 系统设计 mq 消息重复消费处理
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.lrdkoi.asia/blog/0001406.sHtMl

原标题：Git 误提交撤销回退实操教程
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.lrdkoi.asia/blog/4151772.sHtMl

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.lrdkoi.asia/blog/8155876.sHtMl

原标题：Git 分支切换合并删除完整操作
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.lrdkoi.asia/blog/6432939.sHtMl

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.lrdkoi.asia/blog/3441911.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.lrdkoi.asia/blog/8715744.sHtMl

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://book.lrdkoi.asia/blog/7581806.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.lrdkoi.asia/blog/0345643.sHtMl

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.lrdkoi.asia/blog/1512576.sHtMl

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.lrdkoi.asia/blog/0115612.sHtMl

原标题：实践：多配置文件合并加载组件实现
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.lrdkoi.asia/blog/1530267.sHtMl

原标题：实践：静态站点自动化部署到GitHubPages
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.lrdkoi.asia/blog/2932294.sHtMl

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.lrdkoi.asia/blog/1917697.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.lrdkoi.asia/blog/0932533.sHtMl

原标题：项目脚手架模板生成工具
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://book.lrdkoi.asia/blog/8015423.sHtMl

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.lrdkoi.asia/blog/2218031.sHtMl

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.lrdkoi.asia/blog/6877870.sHtMl

原标题：HelloCI：理解持续集成基础工作流程
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.lrdkoi.asia/blog/3163930.sHtMl

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.lrdkoi.asia/blog/1540984.sHtMl

原标题：golang 系统设计灰度发布流量切分实现
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.lrdkoi.asia/blog/2537143.sHtMl

原标题：Practice：实现请求大小限制中间件防护大报文
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://book.lrdkoi.asia/blog/7170907.sHtMl

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://book.lrdkoi.asia/blog/2227016.sHtMl

原标题：开发记录：表单参数校验统一中间件实现
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.lrdkoi.asia/blog/0061708.sHtMl

原标题：golang docker 运行 etcd 本地测试
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.lrdkoi.asia/blog/0077796.sHtMl

三、实战开发｜Practice
原标题：环境变量不生效问题修复
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.lrdkoi.asia/blog/1150273.sHtMl

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.lrdkoi.asia/blog/8711661.sHtMl

原标题：golang kafka 消费者偏移量管理
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.lrdkoi.asia/blog/3821951.sHtMl

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.lrdkoi.asia/blog/0080272.sHtMl

原标题：golang gitlab runner 部署与注册实操
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.lrdkoi.asia/blog/1155808.sHtMl

原标题：安全笔记：CSP内容安全策略配置实践
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.lrdkoi.asia/blog/6964861.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.lrdkoi.asia/blog/4147033.sHtMl

原标题：golang redis 分布式计数器开发
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.lrdkoi.asia/blog/8742358.sHtMl

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.lrdkoi.asia/blog/8039113.sHtMl

原标题：文件分片上传断点续传功能
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.lrdkoi.asia/blog/8121159.sHtMl

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.lrdkoi.asia/blog/9904203.sHtMl

原标题：CI 构建缓存加速编译速度
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.lrdkoi.asia/blog/6605329.sHtMl

原标题：golang 分布式锁 redis 实现
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.lrdkoi.asia/blog/3932054.sHtMl

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.lrdkoi.asia/blog/5212788.sHtMl

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.lrdkoi.asia/blog/1663599.sHtMl

原标题：批量操作分批处理防止 OOM
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.lrdkoi.asia/blog/0633571.sHtMl

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.lrdkoi.asia/blog/6660467.sHtMl

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.lrdkoi.asia/blog/7944678.sHtMl

原标题：golang 内存 pprof 定位内存泄漏
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.lrdkoi.asia/blog/5718552.sHtMl

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://book.lrdkoi.asia/blog/6457115.sHtMl

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.lrdkoi.asia/blog/7364844.sHtMl

原标题：快速入门容器基础概念，理解镜像与容器
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.lrdkoi.asia/blog/8832536.sHtMl

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.lrdkoi.asia/blog/3263710.sHtMl

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.lrdkoi.asia/blog/3278783.sHtMl

原标题：记一次升级操作系统内核引发服务不稳定
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.lrdkoi.asia/blog/8507726.sHtMl

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.lrdkoi.asia/blog/1926157.sHtMl

原标题：接口压测定位系统性能瓶颈
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.lrdkoi.asia/blog/0665009.sHtMl

原标题：react hooks 常见陷阱避坑指南
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.lrdkoi.asia/blog/9661604.sHtMl

原标题：Security：反序列化漏洞风险识别与规避
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.lrdkoi.asia/blog/9689825.sHtMl

原标题：golang 简单爬虫请求防封禁
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.lrdkoi.asia/blog/8358130.sHtMl

原标题：golang redis 五种数据结构实战
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.lrdkoi.asia/blog/0034278.sHtMl

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.lrdkoi.asia/blog/4272297.sHtMl

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.lrdkoi.asia/blog/6375976.sHtMl

原标题：golang redis stream 消息队列实践
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.lrdkoi.asia/blog/9789459.sHtMl

原标题：golang 系统设计熔断降级架构讲解
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.lrdkoi.asia/blog/7080977.sHtMl

原标题：实战项目：实现分布式任务调度最小原型
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.lrdkoi.asia/blog/8098019.sHtMl

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.lrdkoi.asia/blog/6654373.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.lrdkoi.asia/blog/0948750.sHtMl

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.lrdkoi.asia/blog/9428899.sHtMl

原标题：CDN 缓存刷新获取最新静态资源
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.lrdkoi.asia/blog/4480419.sHtMl

四、架构设计｜Architecture
原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.lrdkoi.asia/blog/0092310.sHtMl

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.lrdkoi.asia/blog/6476958.sHtMl

原标题：CDN 缓存刷新获取最新静态资源
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.lrdkoi.asia/blog/7919992.sHtMl

原标题：开源项目构建失败排查步骤
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.lrdkoi.asia/blog/1039272.sHtMl

原标题：前后端交互跨域问题完整处理
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.lrdkoi.asia/blog/1464048.sHtMl

原标题：golang 系统设计指标聚合计算存储选型对比
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.lrdkoi.asia/blog/2056089.sHtMl

原标题：SourceMap 生成线上报错定位
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.lrdkoi.asia/blog/5907833.sHtMl

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.lrdkoi.asia/blog/8754855.sHtMl

原标题：golang 系统设计用户签到统计方案
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.lrdkoi.asia/blog/3680493.sHtMl

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.lrdkoi.asia/blog/2305109.sHtMl

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.lrdkoi.asia/blog/7348957.sHtMl

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.lrdkoi.asia/blog/9584867.sHtMl

原标题：系统时间同步定时任务偏移
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.lrdkoi.asia/blog/2284291.sHtMl

原标题：百万数据 Excel 导出内存优化
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.lrdkoi.asia/blog/9957636.sHtMl

原标题：nodejs 跨域中间件配置细节
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.lrdkoi.asia/blog/0912087.sHtMl

原标题：正则表达式文本处理实战案例
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.lrdkoi.asia/blog/6299756.sHtMl

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.lrdkoi.asia/blog/3209756.sHtMl

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.lrdkoi.asia/blog/8195657.sHtMl

?
