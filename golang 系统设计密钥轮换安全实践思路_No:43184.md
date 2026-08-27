最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计密钥轮换安全实践思路
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.izjkpkr.asia/blog/1240533.sHtMl

原标题：Practice：批量异步任务处理系统设计实现
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.izjkpkr.asia/blog/9123509.sHtMl

原标题：API 大版本不兼容平滑迁移
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.izjkpkr.asia/blog/0989243.sHtMl

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.izjkpkr.asia/blog/9612150.sHtMl

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.izjkpkr.asia/blog/9913658.sHtMl

原标题：golang 系统设计第三方接口 mock 单元测试
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.izjkpkr.asia/blog/7708973.sHtMl

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.izjkpkr.asia/blog/7408936.sHtMl

原标题：echarts 大数据渲染性能调优
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.izjkpkr.asia/blog/9320863.sHtMl

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.izjkpkr.asia/blog/7842051.sHtMl

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.izjkpkr.asia/blog/3791343.sHtMl

原标题：Redis 分布式锁高并发安全实现
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.izjkpkr.asia/blog/2795844.sHtMl

原标题：golang es 更新文档注意版本冲突
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.izjkpkr.asia/blog/5683540.sHtMl

原标题：golang 系统设计大表结构变更不停机方案
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.izjkpkr.asia/blog/5590338.sHtMl

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.izjkpkr.asia/blog/8582835.sHtMl

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.izjkpkr.asia/blog/0899366.sHtMl

原标题：零基础理解缓存基础原理与简单使用
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.izjkpkr.asia/blog/6764751.sHtMl

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.izjkpkr.asia/blog/6493085.sHtMl

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.izjkpkr.asia/blog/5321869.sHtMl

原标题：golang 系统设计请求签名校验完整方案
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.izjkpkr.asia/blog/2694122.sHtMl

原标题：异步任务堆积消费能力优化
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.izjkpkr.asia/blog/7571473.sHtMl

原标题：golang minio 对象存储接口开发
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.izjkpkr.asia/blog/1433520.sHtMl

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.izjkpkr.asia/blog/3027235.sHtMl

原标题：新手指南：项目本地编译输出产物解析
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.izjkpkr.asia/blog/3490854.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.izjkpkr.asia/blog/2757891.sHtMl

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://book.izjkpkr.asia/blog/9060086.sHtMl

原标题：轻量 API 后端接口服务快速开发
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.izjkpkr.asia/blog/5532015.sHtMl

原标题：golang k8s pod 优雅关闭流程讲解
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.izjkpkr.asia/blog/3704326.sHtMl

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.izjkpkr.asia/blog/8278055.sHtMl

原标题：Performance：数据库索引优化常见错误案例
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.izjkpkr.asia/blog/8921987.sHtMl

原标题：golang redis hyperloglog 基数统计
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.izjkpkr.asia/blog/1529695.sHtMl

原标题：容器资源限制防止宿主机过载
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.izjkpkr.asia/blog/9971531.sHtMl

原标题：git rebase 整理提交历史实操
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.izjkpkr.asia/blog/6027467.sHtMl

原标题：Spring 事务传播机制配置生效
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.izjkpkr.asia/blog/8562276.sHtMl

原标题：golang 项目 go mod 依赖管理
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.izjkpkr.asia/blog/8940794.sHtMl

原标题：快速上手简单信号处理脚本编写
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.izjkpkr.asia/blog/4688091.sHtMl

原标题：golang 系统设计数据库慢请求排查流程
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.izjkpkr.asia/blog/2368064.sHtMl

原标题：实践：静态站点自动化部署到GitHubPages
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.izjkpkr.asia/blog/4679645.sHtMl

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.izjkpkr.asia/blog/8265165.sHtMl

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.izjkpkr.asia/blog/8648198.sHtMl

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.izjkpkr.asia/blog/8925942.sHtMl


二、踩坑排错｜Troubleshooting
原标题：实战：GraphQL服务搭建与CRUD实操
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.izjkpkr.asia/blog/4706808.sHtMl

原标题：golang 系统设计大表结构变更不停机方案
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.izjkpkr.asia/blog/6121542.sHtMl

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.izjkpkr.asia/blog/0206658.sHtMl

原标题：不必要字符转义关闭业务异常
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.izjkpkr.asia/blog/2759934.sHtMl

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.izjkpkr.asia/blog/2909727.sHtMl

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.izjkpkr.asia/blog/9369385.sHtMl

原标题：Debug：Websocket频繁断开重连根因分析
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.izjkpkr.asia/blog/1257674.sHtMl

原标题：golang jaeger 链路追踪 go 接入
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.izjkpkr.asia/blog/0798676.sHtMl

原标题：Practice：实现接口mock动态返回不同响应
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.izjkpkr.asia/blog/3532404.sHtMl

原标题：HTTP 状态码请求头完整梳理
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.izjkpkr.asia/blog/3734988.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.izjkpkr.asia/blog/1903947.sHtMl

原标题：前端错误监控上报系统搭建
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.izjkpkr.asia/blog/6514384.sHtMl

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.izjkpkr.asia/blog/4266950.sHtMl

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.izjkpkr.asia/blog/4154242.sHtMl

原标题：开发记录：接口请求日志记录完整中间件实现
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.izjkpkr.asia/blog/8425320.sHtMl

原标题：golang 系统设计 http3 quic 简单原理了解
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.izjkpkr.asia/blog/4524467.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.izjkpkr.asia/blog/9609490.sHtMl

原标题：golang 消息队列 kafka 消费开发
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.izjkpkr.asia/blog/5650979.sHtMl

原标题：死信队列处理消息阻塞业务
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.izjkpkr.asia/blog/7392462.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.izjkpkr.asia/blog/7429242.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.izjkpkr.asia/blog/5928719.sHtMl

原标题：golang redis 热点 key 业务规避
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.izjkpkr.asia/blog/9084312.sHtMl

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.izjkpkr.asia/blog/9817924.sHtMl

原标题：请求工具封装统一异常处理
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.izjkpkr.asia/blog/4404053.sHtMl

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.izjkpkr.asia/blog/6899837.sHtMl

原标题：WSL 搭建 Windows Linux 开发环境
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.izjkpkr.asia/blog/6165598.sHtMl

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.izjkpkr.asia/blog/7544507.sHtMl

原标题：跨域偶现失败配置修复
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.izjkpkr.asia/blog/5686861.sHtMl

原标题：golang k8s service 服务暴露几种类型
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.izjkpkr.asia/blog/0752236.sHtMl

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.izjkpkr.asia/blog/6086658.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.izjkpkr.asia/blog/4955758.sHtMl

原标题：后端登录鉴权模块完整开发
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.izjkpkr.asia/blog/4779271.sHtMl

原标题：golang md5 sha 加密工具实现
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.izjkpkr.asia/blog/8272500.sHtMl

原标题：内存泄漏定位分析完整流程
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.izjkpkr.asia/blog/5295033.sHtMl

原标题：快速入门YAML配置文件语法与示例
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.izjkpkr.asia/blog/2264204.sHtMl

原标题：golang docker 部署 prometheus 整套
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.izjkpkr.asia/blog/3437547.sHtMl

原标题：golang elasticsearch 索引设计思路
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.izjkpkr.asia/blog/1626030.sHtMl

原标题：golang 系统设计接口参数防篡改校验
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.izjkpkr.asia/blog/0108546.sHtMl

原标题：避坑：版本升级之后项目直接无法启动
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.izjkpkr.asia/blog/5086399.sHtMl

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.izjkpkr.asia/blog/6398089.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计缓存预热缓存降级实现
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.izjkpkr.asia/blog/7763931.sHtMl

原标题：golang 协程 panic 捕获防止崩溃
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.izjkpkr.asia/blog/0338487.sHtMl

原标题：实战：基于内存实现简单消息广播组件
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.izjkpkr.asia/blog/8665208.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.izjkpkr.asia/blog/8970778.sHtMl

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.izjkpkr.asia/blog/7383861.sHtMl

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://book.izjkpkr.asia/blog/3348628.sHtMl

原标题：CI 流水线超时时间延长配置
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.izjkpkr.asia/blog/5209498.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.izjkpkr.asia/blog/2099537.sHtMl

原标题：golang 消息死信处理业务逻辑
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.izjkpkr.asia/blog/3395343.sHtMl

原标题：golang 系统设计服务优雅停机完整流程
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.izjkpkr.asia/blog/2940239.sHtMl

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.izjkpkr.asia/blog/8971084.sHtMl

原标题：golang 系统设计一致性哈希原理讲解
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.izjkpkr.asia/blog/6676425.sHtMl

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.izjkpkr.asia/blog/4868248.sHtMl

原标题：数值 key 浮点匹配异常规避
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.izjkpkr.asia/blog/8640966.sHtMl

原标题：golang 数据库批量更新性能优化
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.izjkpkr.asia/blog/7397097.sHtMl

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.izjkpkr.asia/blog/9595364.sHtMl

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.izjkpkr.asia/blog/1802738.sHtMl

原标题：golang redis hyperloglog 基数统计
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.izjkpkr.asia/blog/6822825.sHtMl

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://book.izjkpkr.asia/blog/8383760.sHtMl

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.izjkpkr.asia/blog/4196911.sHtMl

原标题：golang goroutine 协程基础实操
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.izjkpkr.asia/blog/5835492.sHtMl

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.izjkpkr.asia/blog/9215236.sHtMl

原标题：golang gitlab runner 部署与注册实操
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.izjkpkr.asia/blog/9791766.sHtMl

原标题：JWT 令牌过期异常处理
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://book.izjkpkr.asia/blog/0864355.sHtMl

原标题：vue pinia 状态管理实战教程
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.izjkpkr.asia/blog/2978406.sHtMl

原标题：golang mysql exists in 性能对比
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.izjkpkr.asia/blog/7136657.sHtMl

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.izjkpkr.asia/blog/7860976.sHtMl

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.izjkpkr.asia/blog/3794024.sHtMl

原标题：golang 系统设计回调签名校验防伪造实现
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.izjkpkr.asia/blog/5178502.sHtMl

原标题：Security：服务器最小权限账号运维实践
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.izjkpkr.asia/blog/6875450.sHtMl

原标题：golang 系统设计内部服务 mock 集成测试方案
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.izjkpkr.asia/blog/5695028.sHtMl

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.izjkpkr.asia/blog/9890543.sHtMl

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.izjkpkr.asia/blog/6456256.sHtMl

原标题：HelloCI：理解持续集成基础工作流程
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.izjkpkr.asia/blog/4000895.sHtMl

原标题：golang 系统设计密钥轮换安全实践思路
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.izjkpkr.asia/blog/1726276.sHtMl

原标题：接口压测定位系统性能瓶颈
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.izjkpkr.asia/blog/0486651.sHtMl

原标题：golang 系统设计数据库慢请求排查流程
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.izjkpkr.asia/blog/0837931.sHtMl

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.izjkpkr.asia/blog/0850545.sHtMl

原标题：golang docker 部署 prometheus 整套
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.izjkpkr.asia/blog/7192381.sHtMl

原标题：HTTPS 证书过期更新操作
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.izjkpkr.asia/blog/6521706.sHtMl

四、架构设计｜Architecture
原标题：Practice：实现简单信号处理优雅停机实践
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.izjkpkr.asia/blog/2986973.sHtMl

原标题：数据库分表存储大表优化方案
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.izjkpkr.asia/blog/1543743.sHtMl

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.izjkpkr.asia/blog/8231422.sHtMl

原标题：golang kafka 重试机制配置实操
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.izjkpkr.asia/blog/6865699.sHtMl

原标题：批量数据处理脚本编写技巧
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.izjkpkr.asia/blog/4533621.sHtMl

原标题：前端打包产物体积压缩优化
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.izjkpkr.asia/blog/6919399.sHtMl

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.izjkpkr.asia/blog/3821454.sHtMl

原标题：golang websocket 消息广播实现
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.izjkpkr.asia/blog/8978857.sHtMl

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.izjkpkr.asia/blog/1546120.sHtMl

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.izjkpkr.asia/blog/2782058.sHtMl

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.izjkpkr.asia/blog/5952750.sHtMl

原标题：Architecture：静态配置与动态配置架构分离
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.izjkpkr.asia/blog/9115981.sHtMl

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.izjkpkr.asia/blog/1905083.sHtMl

原标题：golang 系统设计 mq 消息丢失完整防护
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.izjkpkr.asia/blog/9614423.sHtMl

原标题：安全实践：接口速率限制防止暴力破解
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.izjkpkr.asia/blog/7892768.sHtMl

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.izjkpkr.asia/blog/4114960.sHtMl

原标题：排错：静态资源404，打包路径配置错误
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.izjkpkr.asia/blog/5287207.sHtMl

原标题：零基础理解读写分离基础思想
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.izjkpkr.asia/blog/4160535.sHtMl

?
