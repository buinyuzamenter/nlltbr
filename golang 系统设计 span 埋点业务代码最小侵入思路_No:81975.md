最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.oadyto.asia/blog/7154282.sHtMl

原标题：golang 系统设计重试退避策略业务落地
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://book.oadyto.asia/blog/3293519.sHtMl

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.oadyto.asia/blog/0347702.sHtMl

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.oadyto.asia/blog/6930243.sHtMl

原标题：golang 协程泄露问题排查方法
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.oadyto.asia/blog/8420180.sHtMl

原标题：CI 流水线超时时间延长配置
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.oadyto.asia/blog/4127703.sHtMl

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.oadyto.asia/blog/2383375.sHtMl

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.oadyto.asia/blog/3994024.sHtMl

原标题：golang 系统设计参数校验统一处理方案
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.oadyto.asia/blog/3358679.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.oadyto.asia/blog/7938993.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.oadyto.asia/blog/4098522.sHtMl

原标题：RPC 接口字段增减兼容处理
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.oadyto.asia/blog/3968379.sHtMl

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.oadyto.asia/blog/0663098.sHtMl

原标题：Dockerfile 编写容器打包实战
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.oadyto.asia/blog/5967666.sHtMl

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.oadyto.asia/blog/6125506.sHtMl

原标题：golang ci 流水线环境变量管理方案
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.oadyto.asia/blog/1618866.sHtMl

原标题：golang docker 镜像构建最佳实践
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://book.oadyto.asia/blog/9393863.sHtMl

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.oadyto.asia/blog/7421564.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.oadyto.asia/blog/3715152.sHtMl

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.oadyto.asia/blog/4648944.sHtMl

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.oadyto.asia/blog/9757893.sHtMl

原标题：golang minio 预签名 url 临时访问
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.oadyto.asia/blog/0624843.sHtMl

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.oadyto.asia/blog/1995494.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.oadyto.asia/blog/0026498.sHtMl

原标题：端口占用释放资源重启服务
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.oadyto.asia/blog/5242323.sHtMl

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.oadyto.asia/blog/7183888.sHtMl

原标题：golang consul 服务发现简单示例
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.oadyto.asia/blog/5993860.sHtMl

原标题：golang 系统设计第三方接口调用封装思路
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.oadyto.asia/blog/0403194.sHtMl

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.oadyto.asia/blog/3426880.sHtMl

原标题：多版本开发环境共存配置
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.oadyto.asia/blog/4058928.sHtMl

原标题：零基础理解会话、Cookie、Session基础
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.oadyto.asia/blog/1243595.sHtMl

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.oadyto.asia/blog/2760978.sHtMl

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.oadyto.asia/blog/9951294.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.oadyto.asia/blog/6105203.sHtMl

原标题：安全复盘：定时任务权限过大风险管控
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.oadyto.asia/blog/2707982.sHtMl

原标题：部署实践：告警收敛避免告警风暴配置
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.oadyto.asia/blog/1319373.sHtMl

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.oadyto.asia/blog/8741618.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.oadyto.asia/blog/2454741.sHtMl

原标题：golang etcd watch 监听配置变更
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.oadyto.asia/blog/2622093.sHtMl

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://book.oadyto.asia/blog/2899161.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.oadyto.asia/blog/0399267.sHtMl

原标题：数据库连接池参数调优
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.oadyto.asia/blog/9652789.sHtMl

原标题：golang gin 静态资源访问配置
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.oadyto.asia/blog/9310013.sHtMl

原标题：golang docker 运行 etcd 本地测试
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.oadyto.asia/blog/5018389.sHtMl

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.oadyto.asia/blog/9047568.sHtMl

原标题：Performance：批量导入数据性能优化实践
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.oadyto.asia/blog/0266194.sHtMl

原标题：开发记录：文件锁实现多进程互斥实践
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.oadyto.asia/blog/3811612.sHtMl

原标题：踩坑：大事务引发数据库连接池耗尽
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.oadyto.asia/blog/4702057.sHtMl

原标题：golang docker 运行 etcd 本地测试
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.oadyto.asia/blog/1278410.sHtMl

原标题：Cookie Session 会话状态管理
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.oadyto.asia/blog/4702197.sHtMl

原标题：golang mysql exists in 性能对比
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.oadyto.asia/blog/8762178.sHtMl

原标题：文件编码统一随机乱码修复
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.oadyto.asia/blog/2275132.sHtMl

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.oadyto.asia/blog/3723438.sHtMl

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.oadyto.asia/blog/6148958.sHtMl

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.oadyto.asia/blog/8133857.sHtMl

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.oadyto.asia/blog/2320679.sHtMl

原标题：golang 协程 panic 捕获防止崩溃
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.oadyto.asia/blog/2396019.sHtMl

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.oadyto.asia/blog/3028852.sHtMl

原标题：安全复盘：消息队列未授权访问安全加固
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.oadyto.asia/blog/5588402.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.oadyto.asia/blog/4517839.sHtMl

原标题：灰度发布策略服务平滑升级
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.oadyto.asia/blog/9044547.sHtMl

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.oadyto.asia/blog/2528500.sHtMl

原标题：golang http 请求重试封装工具
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.oadyto.asia/blog/4723584.sHtMl

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.oadyto.asia/blog/1262466.sHtMl

原标题：golang mysql 批量导入数据实操
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.oadyto.asia/blog/3188762.sHtMl

原标题：golang net/http 超时全套配置
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.oadyto.asia/blog/5354859.sHtMl

原标题：golang 系统设计 commit 提交规范约定
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.oadyto.asia/blog/3719499.sHtMl

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.oadyto.asia/blog/0499469.sHtMl

原标题：实践：接口参数自动校验业务落地实践
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.oadyto.asia/blog/5456802.sHtMl

原标题：golang 系统设计指标埋点代码低侵入实现
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.oadyto.asia/blog/1987204.sHtMl

原标题：golang gin 路由分组权限管控
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.oadyto.asia/blog/0976433.sHtMl

原标题：GraphQL 接口查询优化实操
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://book.oadyto.asia/blog/9135615.sHtMl

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.oadyto.asia/blog/6368977.sHtMl

原标题：实践：前后端分离项目登录状态保持完整方案
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.oadyto.asia/blog/7734089.sHtMl

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.oadyto.asia/blog/4616826.sHtMl

原标题：golang 数据库批量更新性能优化
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.oadyto.asia/blog/8194493.sHtMl

原标题：大事务拆分回滚日志暴涨解决
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.oadyto.asia/blog/7114634.sHtMl

原标题：golang docker compose 环境变量
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.oadyto.asia/blog/4169495.sHtMl

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.oadyto.asia/blog/4602278.sHtMl

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.oadyto.asia/blog/3229262.sHtMl

三、实战开发｜Practice
原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.oadyto.asia/blog/7848629.sHtMl

原标题：文件分片上传断点续传功能
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.oadyto.asia/blog/9397865.sHtMl

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.oadyto.asia/blog/5946743.sHtMl

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.oadyto.asia/blog/7564431.sHtMl

原标题：全量回归测试提升代码质量
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.oadyto.asia/blog/7802686.sHtMl

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.oadyto.asia/blog/5967940.sHtMl

原标题：golang 系统设计开源项目贡献指南 contributing
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.oadyto.asia/blog/9660133.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.oadyto.asia/blog/8401087.sHtMl

原标题：实战项目：实现分布式任务调度最小原型
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.oadyto.asia/blog/5286979.sHtMl

原标题：golang ci 流水线自动部署 k8s 示例
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.oadyto.asia/blog/0150051.sHtMl

原标题：golang mysql 存储过程简单使用
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.oadyto.asia/blog/6935868.sHtMl

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.oadyto.asia/blog/5790054.sHtMl

原标题：快速入门ORM，实现简单数据库增删改查
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.oadyto.asia/blog/0683899.sHtMl

原标题：golang es 分页深分页性能优化
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.oadyto.asia/blog/0656092.sHtMl

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.oadyto.asia/blog/9331676.sHtMl

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://book.oadyto.asia/blog/4508792.sHtMl

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.oadyto.asia/blog/3470793.sHtMl

原标题：Practice：实现请求重试组件支持退避策略
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.oadyto.asia/blog/8350349.sHtMl

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.oadyto.asia/blog/0452643.sHtMl

原标题：golang 系统设计故障演练简单落地思路方法论
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.oadyto.asia/blog/8821169.sHtMl

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.oadyto.asia/blog/0227880.sHtMl

原标题：Architecture：日志、监控、告警整套可观测架构
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.oadyto.asia/blog/1220359.sHtMl

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.oadyto.asia/blog/3104243.sHtMl

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.oadyto.asia/blog/5789499.sHtMl

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.oadyto.asia/blog/2982671.sHtMl

原标题：golang 系统设计秒杀防超卖方案
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.oadyto.asia/blog/7140386.sHtMl

原标题：golang 系统设计 websocket 协议原理梳理
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.oadyto.asia/blog/4462316.sHtMl

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.oadyto.asia/blog/1576693.sHtMl

原标题：快速入门消息通知简单实现方案
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.oadyto.asia/blog/7416003.sHtMl

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.oadyto.asia/blog/2726502.sHtMl

原标题：端口占用访问失败排查方案
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://book.oadyto.asia/blog/1076392.sHtMl

原标题：golang 系统设计消息体序列化选型对比
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.oadyto.asia/blog/9275715.sHtMl

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.oadyto.asia/blog/4822102.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.oadyto.asia/blog/0324206.sHtMl

原标题：零基础理解幂等性基础概念与场景
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.oadyto.asia/blog/1958966.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.oadyto.asia/blog/0467279.sHtMl

原标题：请求工具封装统一异常处理
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.oadyto.asia/blog/0249640.sHtMl

原标题：实践：多配置文件合并加载组件实现
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.oadyto.asia/blog/9057545.sHtMl

原标题：前端大文件分片上传完整方案
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.oadyto.asia/blog/6869536.sHtMl

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.oadyto.asia/blog/6335707.sHtMl

四、架构设计｜Architecture
原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.oadyto.asia/blog/0923228.sHtMl

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.oadyto.asia/blog/6737824.sHtMl

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.oadyto.asia/blog/6018102.sHtMl

原标题：Security：业务操作审计日志安全留存
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.oadyto.asia/blog/6448425.sHtMl

原标题：golang websocket 消息广播实现
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.oadyto.asia/blog/7402269.sHtMl

原标题：golang docker volume 数据持久化
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.oadyto.asia/blog/9873324.sHtMl

原标题：golang 系统设计 changelog 变更日志维护
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.oadyto.asia/blog/0438281.sHtMl

原标题：新手快速上手 Git 版本控制实操指南
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.oadyto.asia/blog/2657241.sHtMl

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.oadyto.asia/blog/8849492.sHtMl

原标题：实战：多版本SDK兼容业务改造实践
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.oadyto.asia/blog/8876676.sHtMl

原标题：golang 系统设计故障演练简单思路
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.oadyto.asia/blog/4449124.sHtMl

原标题：图片上传预览格式大小处理
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.oadyto.asia/blog/1680270.sHtMl

原标题：golang docker 部署 kafka 本地调试
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://book.oadyto.asia/blog/7042283.sHtMl

原标题：golang 系统设计定时任务调度时间校准要点
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.oadyto.asia/blog/8013021.sHtMl

原标题：方案对比：定时任务框架选型与架构对比
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.oadyto.asia/blog/7808199.sHtMl

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.oadyto.asia/blog/8535451.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.oadyto.asia/blog/5310683.sHtMl

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.oadyto.asia/blog/1613750.sHtMl

?
