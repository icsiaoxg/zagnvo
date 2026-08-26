最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计消息发送确认机制配置实操
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.t786yd.asia/arts/652837.Doc

原标题：golang 重试退避机制代码实现
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.t786yd.asia/arts/480335.Doc

原标题：DNS TTL 配置域名切换生效
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.t786yd.asia/arts/934776.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.t786yd.asia/arts/800273.Doc

原标题：跨域偶现失败配置修复
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.t786yd.asia/arts/314558.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.t786yd.asia/arts/600398.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.t786yd.asia/arts/609074.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.t786yd.asia/arts/652109.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.t786yd.asia/arts/381672.Doc

原标题：golang 结构体 json 序列化坑点
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.t786yd.asia/arts/817516.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/713471.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.t786yd.asia/arts/795655.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.t786yd.asia/arts/048691.Doc

原标题：golang zap 日志按日期切割方案
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.t786yd.asia/arts/641051.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.t786yd.asia/arts/124699.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.t786yd.asia/arts/854798.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.t786yd.asia/arts/507286.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.t786yd.asia/arts/549623.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.t786yd.asia/arts/945086.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.t786yd.asia/arts/520597.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.t786yd.asia/arts/660594.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.t786yd.asia/arts/650966.Doc

原标题：新手快速上手 Git 版本控制实操指南
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.t786yd.asia/arts/720012.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.t786yd.asia/arts/944561.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.t786yd.asia/arts/910947.Doc

原标题：分布式锁失效问题排查修复
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.t786yd.asia/arts/986287.Doc

原标题：Git 代码冲突正确处理方式
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.t786yd.asia/arts/625415.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.t786yd.asia/arts/510893.Doc

原标题：golang es 分词器选型业务适配
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.t786yd.asia/arts/849736.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.t786yd.asia/arts/753052.Doc

原标题：快速入门对象存储基础使用场景
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.t786yd.asia/arts/284301.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.t786yd.asia/arts/024411.Doc

原标题：golang 简易埋点日志上报实现
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.t786yd.asia/arts/273957.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.t786yd.asia/arts/755005.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.t786yd.asia/arts/380704.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.t786yd.asia/arts/128695.Doc

原标题：数据库索引重建提升查询速度
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.t786yd.asia/arts/469293.Doc

原标题：golang redis 过期 key 监听业务
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/840029.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.t786yd.asia/arts/034790.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.t786yd.asia/arts/937629.Doc


二、踩坑排错｜Troubleshooting
原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.t786yd.asia/arts/544419.Doc

原标题：内存溢出问题现象识别排查
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.t786yd.asia/arts/786602.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.t786yd.asia/arts/385555.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.t786yd.asia/arts/493958.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.t786yd.asia/arts/834634.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.t786yd.asia/arts/711862.Doc

原标题：golang grpc protobuf 开发实操
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.t786yd.asia/arts/612709.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.t786yd.asia/arts/241030.Doc

原标题：golang 优雅处理数据库事务
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.t786yd.asia/arts/756300.Doc

原标题：golang 项目目录分层规范设计
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.t786yd.asia/arts/937092.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.t786yd.asia/arts/685984.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.t786yd.asia/arts/452243.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.t786yd.asia/arts/152541.Doc

原标题：数据库分表路由写入分片修正
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.t786yd.asia/arts/884846.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.t786yd.asia/arts/714932.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.t786yd.asia/arts/129913.Doc

原标题：golang 系统设计序列化性能选型对比
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.t786yd.asia/arts/308302.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.t786yd.asia/arts/225477.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.t786yd.asia/arts/395752.Doc

原标题：golang kafka offset 提交策略
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.t786yd.asia/arts/592557.Doc

原标题：css 变量主题切换方案实现
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.t786yd.asia/arts/904436.Doc

原标题：rebase 操作防止代码丢失
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.t786yd.asia/arts/290566.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.t786yd.asia/arts/894635.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.t786yd.asia/arts/530292.Doc

原标题：golang 分库分表简单路由实现
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.t786yd.asia/arts/826599.Doc

原标题：游标分页大数据查询性能提升
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.t786yd.asia/arts/164318.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.t786yd.asia/arts/610931.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.t786yd.asia/arts/530252.Doc

原标题：内存溢出问题现象识别排查
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.t786yd.asia/arts/405522.Doc

原标题：Docker 网络模式容器互通设置
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/673620.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.t786yd.asia/arts/820586.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.t786yd.asia/arts/679339.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.t786yd.asia/arts/826398.Doc

原标题：CI 流水线构建失败日志排查
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.t786yd.asia/arts/756292.Doc

原标题：golang 速率限制令牌桶实现
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.t786yd.asia/arts/273871.Doc

原标题：golang 容器健康检查接口开发
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.t786yd.asia/arts/253704.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.t786yd.asia/arts/385279.Doc

原标题：排错：前端缓存304异常更新不及时
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.t786yd.asia/arts/234300.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.t786yd.asia/arts/322551.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.t786yd.asia/arts/514573.Doc

三、实战开发｜Practice
原标题：项目实践：多租户数据隔离三种方案实操对比
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.t786yd.asia/arts/852369.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.t786yd.asia/arts/305576.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.t786yd.asia/arts/413900.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/310087.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.t786yd.asia/arts/893660.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.t786yd.asia/arts/500348.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.t786yd.asia/arts/928877.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.t786yd.asia/arts/551794.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.t786yd.asia/arts/691274.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.t786yd.asia/arts/746146.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.t786yd.asia/arts/162978.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.t786yd.asia/arts/525250.Doc

原标题：零基础理解进程、线程基础概念区别
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.t786yd.asia/arts/869714.Doc

原标题：Performance：JSON序列化性能优化实践
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.t786yd.asia/arts/785224.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.t786yd.asia/arts/253232.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.t786yd.asia/arts/782696.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.t786yd.asia/arts/583776.Doc

原标题：浮点计算精度错误处理方案
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/836500.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.t786yd.asia/arts/710152.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.t786yd.asia/arts/348391.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.t786yd.asia/arts/958999.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.t786yd.asia/arts/602876.Doc

原标题：多版本开发环境共存配置
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.t786yd.asia/arts/265338.Doc

原标题：分布式任务调度集群原型开发
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.t786yd.asia/arts/727727.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.t786yd.asia/arts/127223.Doc

原标题：数值类型溢出错乱问题修复
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.t786yd.asia/arts/088932.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.t786yd.asia/arts/270015.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.t786yd.asia/arts/144223.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.t786yd.asia/arts/947906.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.t786yd.asia/arts/237761.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.t786yd.asia/arts/118736.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.t786yd.asia/arts/437729.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.t786yd.asia/arts/340406.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.t786yd.asia/arts/955691.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.t786yd.asia/arts/504844.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.t786yd.asia/arts/056243.Doc

原标题：消息队列消费堆积扩容处理
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.t786yd.asia/arts/829251.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.t786yd.asia/arts/059744.Doc

原标题：文件监控服务自动重启开发
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.t786yd.asia/arts/131982.Doc

原标题：golang gin 框架接口开发实战
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.t786yd.asia/arts/213650.Doc

四、架构设计｜Architecture
原标题：golang docker 部署 prometheus 整套
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/473466.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.t786yd.asia/arts/369231.Doc

原标题：golang docker 部署 es 本地开发
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.t786yd.asia/arts/620795.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.t786yd.asia/arts/333808.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.t786yd.asia/arts/926922.Doc

原标题：golang 系统设计大文件上传架构
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.t786yd.asia/arts/488621.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.t786yd.asia/arts/042433.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.t786yd.asia/arts/189023.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.t786yd.asia/arts/403726.Doc

原标题：golang 空接口 interface 使用技巧
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.t786yd.asia/arts/938840.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.t786yd.asia/arts/278766.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.t786yd.asia/arts/759313.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.t786yd.asia/arts/262182.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.t786yd.asia/arts/996787.Doc

原标题：golang k8s job 一次性任务执行
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.t786yd.asia/arts/765432.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.t786yd.asia/arts/855153.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.t786yd.asia/arts/453920.Doc

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.t786yd.asia/arts/411305.Doc

?
