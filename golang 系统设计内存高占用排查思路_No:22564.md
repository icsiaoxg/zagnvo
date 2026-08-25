最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内存高占用排查思路
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3015868.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1941615.sHtMl

原标题：开发生产环境资源路径统一
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6487646.sHtMl

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0267320.sHtMl

原标题：线程调度优化减少上下文切换
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0562426.sHtMl

原标题：golang 系统设计限流熔断降级组合使用
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9313949.sHtMl

原标题：golang 协程 panic 捕获防止崩溃
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8719263.sHtMl

原标题：golang 系统设计消息队列降级业务开关实现
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1104712.sHtMl

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8908161.sHtMl

原标题：golang redis 五种数据结构实战
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1365532.sHtMl

原标题：golang redis 主从复制哨兵原理
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3355072.sHtMl

原标题：新手教程：本地环境变量配置全流程
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4881610.sHtMl

原标题：端口占用访问失败排查方案
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4220828.sHtMl

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8611121.sHtMl

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2149711.sHtMl

原标题：热更新开发环境配置教程
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2136624.sHtMl

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7524949.sHtMl

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9283849.sHtMl

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7007365.sHtMl

原标题：依赖安装失败全方位排错
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6935646.sHtMl

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9574804.sHtMl

原标题：git rebase 整理提交历史实操
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1088889.sHtMl

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1742835.sHtMl

原标题：安全复盘：定时任务权限过大风险管控
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4537933.sHtMl

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5000701.sHtMl

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0556344.sHtMl

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2321679.sHtMl

原标题：golang proto 默认值坑点梳理
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9454896.sHtMl

原标题：nodejs 内存溢出问题排查修复
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1392422.sHtMl

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7228075.sHtMl

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6197883.sHtMl

原标题：golang redis 过期策略内存淘汰
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1275828.sHtMl

原标题：运维笔记：线上服务健康检查脚本编写
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7311137.sHtMl

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8936358.sHtMl

原标题：Nginx 反向代理路由配置实战
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3748768.sHtMl

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3062457.sHtMl

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1874914.sHtMl

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5635077.sHtMl

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9527663.sHtMl

原标题：快速上手简单性能监控指标查看
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5346692.sHtMl


二、踩坑排错｜Troubleshooting
原标题：DNS 解析异常第三方调用故障
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2450146.sHtMl

原标题：golang http client 连接池调优
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7894982.sHtMl

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2080351.sHtMl

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1252757.sHtMl

原标题：golang 时间时区处理避坑指南
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6032655.sHtMl

原标题：golang 配置热更新不重启服务
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6495487.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0739286.sHtMl

原标题：golang 系统设计唯一索引业务使用场景
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4792570.sHtMl

原标题：nestjs 权限守卫鉴权实现方案
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8738499.sHtMl

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1640794.sHtMl

原标题：golang 系统设计压测工具 wrk 使用实操
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4521757.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5280839.sHtMl

原标题：golang 告警推送钉钉机器人实现
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0022394.sHtMl

原标题：定时任务重复执行分布式锁
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0442735.sHtMl

原标题：golang toml 配置文件解析教程
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7897275.sHtMl

原标题：程序信号中断退出处理逻辑
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4139521.sHtMl

原标题：消息队列消费堆积扩容处理
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2934986.sHtMl

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7462312.sHtMl

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2798682.sHtMl

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4948957.sHtMl

原标题：消息队列生产消费模型入门
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7433971.sHtMl

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0887675.sHtMl

原标题：GraphQL 接口查询优化实操
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2950020.sHtMl

原标题：golang excel 简单读写操作示例
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2180416.sHtMl

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4762621.sHtMl

原标题：GraphQL 接口查询优化实操
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1092975.sHtMl

原标题：零基础理解数据库事务基础ACID概念
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1965305.sHtMl

原标题：golang 系统设计结构化日志字段规范约定
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1586169.sHtMl

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3566047.sHtMl

原标题：Architecture：事件溯源架构模式适用业务场景
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1657599.sHtMl

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1895084.sHtMl

原标题：模拟登录鉴权权限判断示例
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6484198.sHtMl

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0836885.sHtMl

原标题：记一次限流组件误配置把正常用户拦截
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4290206.sHtMl

原标题：配置外部化线上部署防错误
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3095874.sHtMl

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1655059.sHtMl

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4866676.sHtMl

原标题：golang 系统设计消息发送确认机制配置实操
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5659695.sHtMl

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0567593.sHtMl

原标题：零基础理解版本控制核心概念与工作流
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7595759.sHtMl

三、实战开发｜Practice
原标题：调优方案：CDN优化静态资源访问延迟
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8229244.sHtMl

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5783646.sHtMl

原标题：实战：数据库索引设计，复合索引最佳实践
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8905160.sHtMl

原标题：nodejs 日志轮转生产环境配置
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2501964.sHtMl

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8320592.sHtMl

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6732040.sHtMl

原标题：多规则数据脱敏组件开发
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8449676.sHtMl

原标题：限流组件计数器令牌桶模式实现
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9947205.sHtMl

原标题：Git 分支切换合并删除完整操作
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3237327.sHtMl

原标题：进程线程并发基础概念讲解
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1318553.sHtMl

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3116274.sHtMl

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7465162.sHtMl

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9313425.sHtMl

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8210509.sHtMl

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6485540.sHtMl

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9078504.sHtMl

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9386598.sHtMl

原标题：请求重试组件退避策略实现
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2721030.sHtMl

原标题：golang 系统设计指标埋点代码低侵入实现
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0546922.sHtMl

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7111331.sHtMl

原标题：实践：灰度流量切分简易实现方案
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1916717.sHtMl

原标题：golang 配置热更新不重启服务
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6788840.sHtMl

原标题：全平台系统环境变量配置
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6500212.sHtMl

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0848647.sHtMl

原标题：golang 系统设计文件存储选型对比
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5384999.sHtMl

原标题：golang 系统设计 ci 流水线安全管控思路
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/6012263.sHtMl

原标题：排错：前端缓存304异常更新不及时
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/0505539.sHtMl

原标题：golang redis 地理位置 geo 使用
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2782107.sHtMl

原标题：golang mysql 字符集排序规则设置
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9067132.sHtMl

原标题：golang redis 过期 key 监听业务
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4640203.sHtMl

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8941017.sHtMl

原标题：零基础理解HTTP常用请求头与状态码
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9634937.sHtMl

原标题：git cherry‑pick 规范操作防 bug
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3208050.sHtMl

原标题：实践：静态站点自动化部署到GitHubPages
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1214281.sHtMl

原标题：golang 协程泄露问题排查方法
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8358723.sHtMl

原标题：Docker 多阶段构建镜像瘦身
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5613793.sHtMl

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2217684.sHtMl

原标题：CI 流水线超时时间延长配置
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7617542.sHtMl

原标题：golang minio 分片上传断点续传
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9357392.sHtMl

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1284241.sHtMl

四、架构设计｜Architecture
原标题：缓存过期打散防止缓存雪崩
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1216755.sHtMl

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/9829500.sHtMl

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4572400.sHtMl

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/4147305.sHtMl

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8353101.sHtMl

原标题：避坑：请求未设置read超时无限挂起连接
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5495328.sHtMl

原标题：文件读写与异常捕获代码示例
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3564437.sHtMl

原标题：golang redis 分布式计数器开发
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8017796.sHtMl

原标题：开发环境变量配置全平台教程
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/3167761.sHtMl

原标题：新手教程：gitrebase基础使用与风险提示
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8618474.sHtMl

原标题：入门实战：搭建简易静态网页项目
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1190799.sHtMl

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5398543.sHtMl

原标题：前端虚拟列表大数据渲染优化
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5691274.sHtMl

原标题：golang csv 读写批量数据处理
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/8647315.sHtMl

原标题：golang grafana 监控面板简单配置
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/1794777.sHtMl

原标题：golang 系统设计 changelog 变更日志维护
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/5988576.sHtMl

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/7128570.sHtMl

原标题：代理 HTTPS 证书访问异常处理
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://zhishi.9sxn1j.asia/blog/2029198.sHtMl

?
