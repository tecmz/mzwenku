# 魔众文库系统

魔众文库系统基于文档系统知识，建立平台与领域，打造流量、用户、付费和变现的闭环，帮助您更好的搭建文库系统。

## 运行环境


```
操作系统
Linux/Unix 或&nbsp;&nbsp;Windows
软件环境
Laravel 5.1的运行环境
Apache/Nginx , PHP 5.5.9+ / PHP 7.0 , MySQL 5.0+
```

## 系统截图



## 版本迭代



### V7.2.0

**发布时间**：2024-10-15

- [新功能] 图片上传新增支持 svg 格式文件
- [新功能] 用户登录传输用户密码加密
- [新功能] 前端加密基础库
- [新功能] ComplexFieldsList 组件支持 textarea 输入
- [新功能] 富文本支持编辑器直接粘贴多张图片功能
- [新功能] UEditorPlus升级到 v4.1.0
- [系统优化] 自定义字段序列化为空时异常处理
- [系统优化] 链接生成参数合并过滤异常的 amp; 字段
- [系统优化] 图片上传增加处理提示，避免出现无状态情况
- [系统优化] 下载短信通知模板支持仅配置Alias的方式，避免模板申请异常问题
- [系统优化] 图片可视化设计库尺寸缩放问题优化
- [系统优化] 多语言获取方法优化，提高性能支持
- [系统优化] 后台菜单注册闭包检测
- [系统优化] 多语言语言检测获取功能优化
- [系统优化] 快捷支持弹窗交互方式优化
- [Bug修复] 图片选择直接弹出相机问题
- [Bug修复] 图片、文件选择窗口初始化快速点击自定义输入时自动跳转文件库 Tab 问题
- [Bug修复] 微信小程序变异失败的问题
- [Bug修复] 微信小程序banner显示异常问题



### V7.1.0

**发布时间**：2024-08-30

- [新功能] 分销订单增加到账时间和到账状态
- [新功能] 鼠标右击逻辑判断懒加载，后台管理菜单权限控制
- [新功能] CheckBox 组件支持表单最小宽度设置，支持更多选项传入方式
- [新功能] URL安全的 Base64 编码和解码方法
- [新功能] 项目静态资源文件增加 .nvmrc 文件，方便开发者使用 nvm 管理 node 版本
- [新功能] Grid 增加 hookPreQuery 支持数据查询前的钩子处理
- [新功能] 昨日交易数据，快捷支付链接优化
- [新功能] ComplexFields 组件支持图片链接字段类型
- [新功能] 图片可视化设计增加图片占位符显示
- [新功能] H5、小程序底部导航栏采用原生导航
- [新功能] 列表和结果页面会自动隐藏无文档的辅助分类功能
- [新功能] 模型查询条件支持自定义过滤功能 ModelUtil::queryRemoveCondition
- [新功能] 文档店铺增加数据统计字段，方便统计店铺数据
- [系统优化] 后台首页 Dashboard 报表格式优化
- [系统优化] FileUtil 生成随机文件路径后缀为空时路径拼接方式优化
- [系统优化] 模型字段数据库报错文案转换优化，自动识别长度超长问题
- [系统优化] 爬虫机器人检测规则优化，支持更多机器人识别
- [系统优化] 文库最新专题列表显示方式优化
- [系统优化] 推荐店铺显示样式优化
- [Bug修复] Laravel9 中 sql_mode 的 only_full_group_by 问题
- [Bug修复] 几处 collection 不兼容问题
- [Bug修复] data-tab-open 打开页面菜单栏高亮不消失问题
- [Bug修复] 链接变动自动触发失效问题修复
- [Bug修复] 日志文件为空时，日志查看界面显示异常问题
- [Bug修复] 头像裁剪保存页面样式优化，图标不显示修复



### V7.0.0

**发布时间**：2024-08-07

- [新功能] RandomImageProvider 逻辑升级重构，支持更丰富的随机图片生成
- [新功能] 资源篮订单参数字段
- [新功能] 首页推荐店铺功能，需要在后台 文库系统 &rarr; 文库店铺 开启推荐
- [系统优化] Grid 快捷编辑请求失败，页面自动刷新回复原状态
- [系统优化] 魔众文档转换后端菜单结构优化
- [系统优化] 后台文库增强、文库专题配置功能合并
- [Bug修复] 后台用户管理开启手机邮箱时，空字段唯一索引冲突问题
- [Bug修复] 多语言 LM 方法参数不生效问题



### V6.9.0

**发布时间**：2024-07-16

- [新功能] ValueUtil 和 ArrayUtil.firstValidValue 方法，支持获取第一个有效值
- [新功能] Provider 和 Biz 增加 listAllEnabled 方法，支持查询所有启用数据
- [新功能] Grid 增改差页面支持标题自定义，使用 pageTitleAdd、pageTitleEdit、pageTitleShow 属性
- [新功能] VIP 开通页面交互形式优化
- [新功能] VIP 优惠券功能集成，支持折扣券
- [新功能] WebUploader 内置 JS 组件升级
- [新功能] 可完全自定义上传功能定制的特性 UploadScript Hook
- [新功能] 用户文件、图片上传支持前端直传云存储（需要安装模块支持）
- [新功能] Grid 批量操作弹窗支持自定义大小 ( data-dialog-width、data-dialog-width 属性)
- [新功能] 参数占位处理工具类 ParamUtil ，支持处理参数占位符
- [新功能] Json 组件 API 数据配置显示优化
- [新功能] Grid 表格操作支持底部操作区域（方法 footOperatePrepend）
- [系统优化] Json 组件 API 模式支持处理响应内容
- [系统优化] 轮播类型添加修改是否为空判断
- [系统优化] BizTrait 增加 first 和 firstName 方法，支持查询第一条数据
- [系统优化] Grid 中批量操作快捷监听优化 data-batch-dialog-operate
- [系统优化] 多语言 i18n 渲染方式优化
- [系统优化] 用户登录事件 MemberUserLoginedEvent 参数异常问题
- [系统优化] CurlUtil 请求头格式校验，避免错误传参导致的异常
- [Bug修复] 富文本编辑器高度自适应概率性失效问题
- [Bug修复] MultiSelect 组件数据回显异常修复
- [Bug修复] uni-app 打包脚本在 windows 环境下运行异常问题
- [Bug修复] CurlUtil 中 GET 请求方法大小写引起的异常问题



### V6.8.0

**发布时间**：2024-06-27

- [新功能] 模型操作增加 insertIfNotExists 方法，支持快捷插入数据
- [新功能] 专题文档支持批量一键加入资源篮功能和现实数量
- [系统优化] 图片处理工具类水印处理方法增加图片类型检查
- [系统优化] 并发访问原子类性能优化
- [系统优化] JsonKeyValue 字段显示优化
- [系统优化] EChart 折线图样式优化
- [系统优化] AgentUtil 工具类新增浏览器版本判断，方便不同场景兼容
- [系统优化] Response 下载方法浏览器兼容优化
- [系统优化] 低版本 Safari 浏览器文档下载降级兼容处理
- [系统优化] 代码清理和重构优化
- [系统优化] 搜索蜘蛛检测工具类优化
- [系统优化] 统计代码条件判断后置，系统性能优化
- [系统优化] 组件 JsonIdItems 数据预览接口返回兼容 .records 格式
- [系统优化] 组件 Image、File、Video、Audio 支持一键恢复默认值
- [系统优化] 优化桌面添加应用显示图标方式
- [Bug修复] 用户注册弹窗异常验证码发送异常问题
- [Bug修复] 文档审核通过后审核拒绝不生效问题



### V6.7.0

**发布时间**：2024-06-14

- [新功能] 标签使用业务支持 allTagsValue 和 allVisible 方法
- [新功能] 命令超时运行函数
- [新功能] 优化 Nav 组件，支持链式调用，支持弹窗打开
- [新功能] 后台安全提醒修改密码链接不存在问题
- [新功能] 增加命令执行函数和数组多键值排序方法
- [新功能] 文件流式下载工具类，加密方式默认使用安全 Key
- [新功能] 用户上传数据表模型表
- [新功能] Grid、Form、Detail 支持自定义 view 和 viewData
- [新功能] 后台支持自定义样式文件 modstart.admin.styles
- [新功能] Hidden 组件支持序列化类型，避免入库异常
- [系统优化] 在 Linux 系统下，artisan 命令运行用户检测，避免 root 运行引起的权限问题
- [系统优化] LockUtil 加锁方法优化
- [系统优化] 时间辅助函数方法优化
- [系统优化] 超长表格 loading 效果不可见问题
- [系统优化] 命令行批量导入过滤空值
- [系统优化] 临时文件清理调度默认调整到后台运行
- [系统优化] Code 换行符默认替换为 \n 问题
- [系统优化] ZIP文件预览最多支持1000个文件，避免文件太多造成的数据库字段超长
- [系统优化] Grid 增加按钮默认使用 titleAdd 属性
- [系统优化] Grid 列表错误异常渲染优化
- [系统优化] 网站统计报表实时查询数据库插入冲突问题
- [系统优化] 记录是否存在方法优化
- [Bug修复] 手机快速注册登录密码设置控件不是password修复
- [Bug修复] VIP设置赠送积分但积分设置为0时异常问题
- [Bug修复] Laravel9下关联模型数据异常问题
- [Bug修复] 游客下载异常问题
- [Bug修复] 已登录绑定授权信息，开启自动绑定账户时，绑定账户异常问题
- [Bug修复] 后台自动跳转到第一个有权限菜单异常问题
- [Bug修复] PDF转文字异常问题修复



### V6.6.0

**发布时间**：2024-05-24

- [新功能] Echarts 组件重构，支持饼图和散点图
- [新功能] 后台左侧菜单支持鼠标滚动拖拽，方便管理超长菜单
- [新功能] 后台登录背景默认使用系统自带背景
- [新功能] 为所有组件新增 data-field 属性，方便获取组件数据
- [新功能] 用户过期时间精确到时分秒，支持更精确的过期时间控制
- [新功能] 升级支持支付宝授权登录最新方式
- [新功能] 开发者工具模块新建操作优化，支持多种预定义模板代码
- [新功能] 日志界面重构，全新日志查看体验
- [新功能] 文档预览增加字数统计，支持纯文本的文档字数统计（历史文档需要重新转换）
- [新功能] 图标增加 eye-close
- [新功能] 链接选择弹窗增加默认类型过滤
- [新功能] 后台左上角标题支持自定义，修改 modstart.php 中 admin.title 配置
- [新功能] JS 库新增 MS.util.sprintf 方法
- [新功能] Code组件编辑默认调整为代码编辑器，支持多种语言设置
- [新功能] Vue文件Widget支持style，支持自定义样式
- [新功能] 分销功能
- [新功能] 后台快速选择用户 AdminMemberSelector 组件
- [新功能] 后台标准返回 redirect 支持静默跳转
- [系统优化] 后台多标签切换浏览器页面标题显示优化
- [系统优化] 内容为空样式间隙大小优化
- [系统优化] 异常上报内容显示优化
- [系统优化] 后台首页概况无权限时，尝试跳转第一个有权限的页面
- [系统优化] 注册登录文案提示优化
- [系统优化] 用户移动端微信授权登录页面跳转问题
- [系统优化] 界面直接显示折扣后的价格和积分
- [系统优化] PDF文件总页数获取逻辑，支持多种方式获取
- [系统优化] 文档PDF解析文本SDK优化升级
- [系统优化] bool值表单联动判断
- [系统优化] 移除 WenkuDocPdfConverted 事件，优化转换逻辑
- [系统优化] 文件库文件删除脏数据异常问题
- [系统优化] 组件jsonKeyValue列表和详情显示优化
- [系统优化] GridFilter增加hidden属性，支持自定义条件回调
- [系统优化] CurlUtil 请求头 referer 默认值调整为空
- [系统优化] 事件触发工具类参数优化
- [系统优化] code组件重复编码问题
- [系统优化] 用户中心菜单配置开关
- [系统优化] 支付中心新增退款事件 OrderRefundedEvent
- [Bug修复] 模块管理配置缓存失效问题
- [Bug修复] 最近新闻链接不跳转问题修复
- [Bug修复] 文库资源蓝删除失效问题
- [Bug修复] 非模型字段在复制和编辑时填充异常问题



### V6.5.0

**发布时间**：2024-04-07

- [新功能] 文档上传解析后保留的字数可设置，优化数据库空间存储
- [新功能] 支付结算工具类增加详细日志，方便问题排查
- [新功能] 桌面图标增加引导操作
- [新功能] 后台登录背景移动端显示自适应
- [新功能] 后台白色清爽主题，可通过设置 ADMIN_THEME=default 切换后台主题
- [新功能] 后台用户列表支持一键登录，方便管理员快速登录用户中心（默认关闭，需要在模块管理中开启）
- [新功能] Time组件增加秒存储方式，方便存储时间精确到秒
- [新功能] 邮件发送成功与否增加判断
- [新功能] AdminConfigBuilder 增加 pageAppend 方法，方便在页面中追加内容
- [新功能] AdminConfigBuilder 增加 hookFormWrap 方法，方便自定义组建表单
- [新功能] 运营报表-用户数据页面，支持统计报表和每日明细
- [新功能] 后台支持 Widget 动态请求，方便开发者自定义页面内容
- [新功能] 文库增加文档浏览和下载明细、文库增加文档浏览和下载报表
- [新功能] 时间工具增加日期范围限定功能
- [新功能] 搜索 like 关键词转义方法，模糊搜索时不再受特殊字符影响
- [新功能] 运营报表-网站访问页面，合并设置和详细页面
- [新功能] Text 新增 asLink 方法，支持内容以链接形式展示
- [新功能] 支持 modstart:module-list 命令，列出当前系统已安装、系统配置模块
- [新功能] 专题增加SEO关键词和SEO描述，支持自定义
- [新功能] KeyPoolManager 支持通用多个 Key 轮询快速开发
- [新功能] 通用导航增加变量自动替换支持
- [系统优化] 后台报表数据最后一个元素水平间隙优化
- [系统优化] 特权文档相关提示文案优化
- [系统优化] 文档是自己时，提示文案优化
- [系统优化] 付费文档和VIP特权文档显示文案优化
- [系统优化] modstart_config 缓存失效问题优化
- [Bug修复] 重新转换转换也是不生肖问题
- [Bug修复] 专题分类详情页面封面概率性不显示问题
- [Bug修复] 文档打包下载支付成功跳转链接404问题
- [Bug修复] 用户名字符长度提示文案异常问题
- [Bug修复] i18n 语言包文字书写错误纠正
- [Bug修复] 文库搜索关键词显示结构异常优化



### V6.4.0

**发布时间**：2024-03-19

- [新功能] 鼠标禁止右击 RightClickForbidden 模块
- [新功能] 页面滚动进度条 PageProgressBar
- [新功能] 管理登录背景 AdminLoginBackground
- [新功能] 后台登录提示 AdminLoginNotice 功能
- [新功能] 日志查看器 LogViewer 功能
- [新功能] 随机用户头像 MemberRandomAvatarTecmz 功能
- [新功能] 网页复制追加文字 CopyAppender 功能
- [新功能] 升级 XGPlayer 库，更好支持 HLS 视频播放
- [新功能] 文档上传后会自动解析前N页的文字信息，0表示不解析
- [Bug修复] 文档下载名称非法字符替换优化
- [Bug修复] 用户已安装模块概率性出现不能识别问题



### V6.3.0

**发布时间**：2024-03-14

- [新功能] 支付结算页面增加说明标题和内容
- [新功能] 财务概况增加最近7日和30日收款金额统计
- [新功能] Display 组件 asLink 参数支持回调模式，支持自定义链接
- [新功能] 首页增加今日收款金额统计报表
- [新功能] 桌面快捷应用，支持将网页快捷方式添加到桌面（安装 DesktopApp）
- [新功能] 最新转换模式游客最大预览页数限制不生效问题
- [新功能] 默认增加百度统计配置
- [系统优化] 模块管理模块缓存优化，模块存在真实性判断
- [系统优化] 后台登录界面左侧宽度自动增加样式问题，标题边距调整
- [系统优化] GridFilter 筛选 range 查找逻辑优化
- [系统优化] 后台管理首页服务器信息显示优化
- [系统优化] 后台首页概况页面重构完成
- [Bug修复] 开启图片压缩，图片压缩失败的情况下继续上传
- [Bug修复] 多语言部分书写错误
- [Bug修复] 默认用户开通积分赠送不生效问题修复



### V6.2.0

**发布时间**：2024-03-04

- [新功能] 系统全局消息提示 UI 全新优化
- [新功能] JS 库增加【ijs】类型字符串，支持默认可执行代码
- [新功能] 资源篮是否启用可配置
- [新功能] 文库分类批量导入功能，支持多级自动创建导入
- [新功能] 分类快捷操作工具类 CategoryUtil
- [新功能] 用户设置实名认证后才能上传，增加实名认证引导界面
- [新功能] 实名认证界面增加选择图标和文案优化
- [系统优化] 后台登录界面自适应不同设备，界面升级
- [Bug修复] 抖音授权登录异常问题
- [Bug修复] 免费资源篮提交跳转异常问题
- [Bug修复] 专题分类列表筛选不生效问题修复



### V6.1.0

**发布时间**：2024-02-29

- [新功能] 抖音授权登录
- [新功能] 默认图标增加抖音图标（iconfont icon-douyin）
- [新功能] 专题增加多级分类，最多支持四级
- [新功能] 后台文档上传支持直接添加到专题（模块支持WenkuAdminUpload）
- [新功能] JS 库增强 MS.ui.elementMover，支持元素动态移动效果
- [新功能] Decimal 组件增加 unit、unitPosition 属性，支持单位显示
- [新功能] 文库资源篮功能，支持批量一次性支付金额、积分购买文档
- [新功能] 用户积分新增冻结、提交、取消三阶段操作功能
- [新功能] 用户积分流水增加其他信息，支持冻结交易、管理员变更等信息展示
- [新功能] 用户积分后台操作支持记录管理员 ID
- [新功能] 后台用户钱包流水增加其他信息，可记录后台管理员变更信息
- [新功能] 用户前台积分冻结记录显示功能
- [新功能] 图片上传是否压缩可通过配置文件配置（默认开启压缩）
- [新功能] 富文本编辑器迷你版增加 markdown 内容导入功能
- [新功能] Curl 工具类请求增加 writeFunctionCallback 参数，支持流式请求
- [新功能] JS 库增加 markdown 操作工具类，支持 markdown 转 html
- [系统优化] 搜索引擎蜘蛛检测库优化
- [系统优化] 授权方式（支付宝、QQ）主题色优化
- [Bug修复] 文档下载在配置推广压缩包和直接跳转链接的情况下，下载链接异常问题



### V6.0.0

**发布时间**：2024-02-22

- [新功能] 队列调度支持work-max-jobs属性，支持进程批量处理
- [新功能] 用户删除事件触发 MemberUserDeletedEvent
- [新功能] 文档重试命令 Wenku:ConvertRetry 增加是否只解析文档内容选项
- [新功能] 进程运行命令runInNewProcess，支持进程隔离运行
- [新功能] 时间工具类增加tomorrowDate方法
- [新功能] UEditorPlus 版本到 3.8.0
- [新功能] Form 表单组件增加 hookResponse 属性，支持自定义返回数据
- [新功能] 文件上传事件增加参数，用于区别用户、后台等文件上传类型
- [新功能] Select 组件增加 gridEditable 属性，支持表格编辑模式
- [新功能] 增加浏览数量虚拟数量
- [新功能] Redis 增加 isEnableSuccess 判断是否启用成功
- [新功能] 文档详情页面增加辅助分类显示
- [系统优化] 动画样式类优化
- [系统优化] 异常错误日志 URL 获取优化，提高定位效率
- [Bug修复] 小程序扫码登录弹窗异常问题
- [Bug修复] 修复概率性文字解析异常问题
- [Bug修复] 标签操作长度判断异常问题修复
- [Bug修复] 用户删除自动清除授权登录信息
- [Bug修复] 文库内容页面canonical多一个斜杠问题



### V5.9.0

**发布时间**：2024-01-11

- [新功能] Values 组件新增 countFixed 属性，固定显示数量
- [新功能] 后台框架页面增加禁止搜索引擎爬取 meta 标签
- [新功能] Request::mergeQueries 合并请求参数按参数名称排序，避免同业不同链问题
- [新功能] Form 支持原生 Response 直接返回，便于处理文件下载等表单
- [新功能] 文档重试命令 Wenku:ConvertRetry 新增是否只转换失败文档选项
- [新功能] 用户授权登录时如果手机/邮箱已存在，直接关联已有用户
- [新功能] 增加用户账号申诉功能，支持用户自助找回账号、账号禁用申诉等用途
- [新功能] 请求输入 getBase64File 自动检测 Base64 文件前缀
- [新功能] 用户后台授权登录详细数据列表支持弹窗查看
- [新功能] 文档内容自动OCR解析功能，提高SEO优化效果
- [新功能] 后台文库管理分页调整为 10，100，,100
- [新功能] 后台文库管理增加虚拟数量批量修改功能
- [新功能] NumberRange 组件支持，用于输入数字范围
- [新功能] 后台增加随机虚拟数量，文档上传时随机生成虚拟数量
- [新功能] 用户VIP开通界面增加划线价
- [新功能] VIP开通界面增加最近开通用户列表和倒计时，促进用户开通率
- [新功能] 用户自动注册前缀可设置，优化用户显示逻辑
- [新功能] 小程序增加自动更新提示逻辑
- [新功能] 移动端VIP页面全新升级
- [新功能] AdminConfigBuilder 增加配置保存检查回调函数，支持配置与检查
- [系统优化] 用户账号管理界面按钮均调整为圆角样式
- [系统优化] AES加密函数解密异常时错误优化
- [系统优化] 文件回收站删除文件自动清理逻辑优化
- [系统优化] 授权登录默认注册为用户昵称（昵称不可作为登录用户名）



### V5.8.0

**发布时间**：2023-12-18

- [新功能] 有移动端链接时，后台链接选择自动识别电脑端和移动端筛选
- [新功能] ComplexFieldsList 组件支持链接和颜色选择
- [新功能] 用户文件上传增加type字段，区分文件类型
- [新功能] CurlUtil::mockUserAgent 支持模拟真实UA
- [新功能] 图片水印工具类全面优化，支持文字单行、文字多行、图片单个、图片多个
- [新功能] 用户密码增加强度校验，支持不限、字母数字、长度限制
- [新功能] 辅助分类增加Mini显示模式，布局更合理
- [新功能] 用户授权自动绑定开关，支持授权后立即登录
- [系统优化] 文档图标全新升级，支持更多类型
- [系统优化] 系统图标样式统一优化
- [系统优化] RedisQueue一处多进程调度性能问题
- [系统优化] 移动端文档详情预览支持压缩文件，部分重构
- [系统优化] UEditor 图片抓取特殊 URL 文件类型判断优化，新增真实 UserAgent
- [系统优化] 组件when方法数据类型优化
- [Bug修复] 一处LayUI树tree多选问题
- [Bug修复] 后台 Job 执行时候，资源全路径修正问题
- [Bug修复] 多系统集成时文库搜索链接异常问题
- [Bug修复] 一处图片分片上传异常问题
- [Bug修复] 概率性用户VIP时间异常问题



### V5.7.0

**发布时间**：2023-12-06

- [新功能] 模块资源软链接命令 modstart:module-link-asset
- [新功能] 文件上传管理页面支持图标显示，支持顺序选择
- [新功能] DataRefProvider 提供文件引用提供者模块
- [新功能] LayUI 升级到最新版
- [新功能] Tree 组件增加选项是否独立模式 independentEnable
- [新功能] 文档辅助分类组启用分类树为完全能独立选择模式
- [新功能] 短信验证注册时可支持同时设置登录密码
- [新功能] 系统命令行安装和界面安装方式文档支持
- [新功能] 财务中心&rarr;全部订单新增&quot;业务订单ID&quot;筛选条件
- [新功能] 富文本支持文档一键导入，支持Word文档（docx）、Markdown文档（md）
- [系统优化] 系统响应默认处理函数优化处理方式
- [系统优化] 模块安装解压超时时间调整为 600 秒
- [系统优化] 前端 MS.dialog 在 layer 未加载时降级为原生
- [系统优化] Robot 蜘蛛检测 UserAgent 完善
- [系统优化] 数据表单 Grid 常规模式和简单模式底层重构完成
- [系统优化] 用户管理后台用户注册登录设置页面文案优化
- [系统优化] 用户VIP页面条目是否可视移动端接口优化
- [Bug修复] 用户积分记录更新异常问题修复
- [Bug修复] 搜索页面格式筛选条件未按照预设展示



### V5.6.0

**发布时间**：2023-11-13

- [新功能] 临时上传文件data_temp自动清除调度任务
- [新功能] 后台支持多语言切换，默认关闭，需修改配置文件自行开启
- [新功能] Number 组件增加 min、max、step 属性
- [新功能] 轮播图获取支持近图片过滤方法
- [新功能] 网站模板可自定义设置弹窗，主题可自定义参数设置
- [新功能] 布局视图页面全局增加 headPrepend section
- [新功能] 文库首页增加上传文档按钮
- [新功能] 前台右上角菜单增加用户中心下拉菜单
- [新功能] DWG文件格式支持（手动设置预览封面）
- [系统优化] 临时文件删除文件不存在时候删除失败修复
- [系统优化] 后台多Tab菜单点击显示优化问题
- [系统优化] 后台登录页面自动检测框架嵌套并刷新
- [系统优化] 错误页面返回状态码404、403优化
- [Bug修复] 用户中心显示异常问题
- [Bug修复] 文档压缩文件预览不显示问题修复
- [Bug修复] 文档列表历史数据部分封面不显示问题
- [Bug修复] PageHtmlUtil::render 增加自定义分页渲染函数参数



### V5.5.0

**发布时间**：2023-11-01

- [新功能] 内外网链接节流映射配置
- [新功能] 统一错误处理增加特定状态码错误页面
- [新功能] ComplexFieldsList 组件增加 select 类型
- [新功能] 文件夹选择上传增加过滤方式
- [新功能] 文库批量快捷上传，解决海量文档卡顿问题
- [新功能] 文库批量快捷上传功能
- [系统优化] 403错误页面样式升级调整
- [系统优化] 文档格式界面图标显示优化
- [系统优化] 用户中心上传的文档显示优化
- [系统优化] 封面编辑逻辑优化处理
- [系统优化] 视频 Banner 概率不播放问题
- [系统优化] 文库批量上传界面重构与完善
- [Bug修复] 后台用户数据统计异常问题修复
- [Bug修复] 批量上传命令文件获取异常修复



### V5.4.0

**发布时间**：2023-10-21

- [新功能] 富文本增加MP3文件等音频内容
- [新功能] ImageSelector支持show-preview-url参数，图片预览是否显示链接
- [新功能] 移动端增加c-rich-html组件，支持多端富文本兼容显示
- [新功能] 内核升级为3.8.0
- [新功能] 用户首页面板配置 MemberHomePanel
- [新功能] CRUDUtil新增scope获取，copyId新增默认值
- [新功能] 支持公共图片库（需安装DataGallery支持）
- [新功能] ENCRYPT_KEY默认系统数据加密密钥
- [新功能] 后台安全新增默认Key检测
- [系统优化] 后台 data-tab-open 打开菜单自动定位
- [系统优化] 微信小程序视频激励广告自动跳转登录
- [系统优化] 已过期的用户VIP，自动更新为普通用户
- [系统优化] 文库积分不足时进入积分充值引导页面
- [系统优化] 文档相关文案&quot;喜欢&quot;调整为&quot;点赞&quot;
- [系统优化] 文库文档Iframe预览模式下允许全屏显示问题
- [系统优化] 表单快速编辑功能优化
- [系统优化] 后台管理安全公告位置调整
- [Bug修复] 富文本字体设置不生效问题修复



### V5.3.0

**发布时间**：2023-09-18

- [新功能] 友情链接支持独立页面 /partner 访问
- [新功能] 用户注册成功站内信和欢迎邮件
- [新功能] 下载、收藏、喜欢虚拟数量可设置
- [新功能] MemberAuthProvider支持自定义账号对接方式
- [新功能] 广告位新增开始时间和结束时间
- [新功能] SiteUrlProvider增加按业务变更方法
- [新功能] 观看视频激励广告增加积分功能
- [新功能] 广告位新增微信小程序激励视频类型
- [系统优化] 富文本HTML过滤新增div标签
- [系统优化] 后台注册登录链接生成使用非路由生成
- [系统优化] 树状结构Select显示优化
- [系统优化] AES加密解密方法优化，支持更多模式
- [Bug修复] 数组随机获取异常问题修复



### V5.2.0

**发布时间**：2023-08-30

- [新功能] 动态页面支付支付方式新增AlipayWeb
- [新功能] 同时增加多个数据库表备注方法
- [新功能] 支持MS.ui.state库方法，历史状态管理
- [新功能] 富文本公式编辑默认替换为LatexEasy
- [新功能] 手机端Banner支持视频背景显示
- [新功能] Grid文本组件支持快捷编辑
- [新功能] Grid快捷编辑gridEditable支持函数回调方式
- [新功能] UEditorPlus升级v3.4.0
- [新功能] MS.Util.browser 浏览器判断工具类
- [新功能] 批量上传支持文件夹选择，自动筛选可上传文档
- [新功能] 文件上传Vue组件新增Flat模式和addFile方法
- [系统优化] 多语言翻译功能逻辑和多语言函数
- [系统优化] 示例域名修改为 example.com
- [系统优化] 面包屑分隔符样式优化
- [系统优化] 支付回调非法请求日志记录和错误提示优化
- [系统优化] 样式sm、md、lg、xl尺寸优化
- [系统优化] 图片类组件预览修改为contain模式
- [系统优化] VIP开通快捷支付概率性异常问题
- [系统优化] 表单提交时交互验证未完成逻辑优化
- [系统优化] 富文本编辑公式编辑组件重复去除
- [系统优化] 文库批量上传分类和辅助分类显示交互优化
- [Bug修复] 数字组件为0时默认值显示异常问题
- [Bug修复] 图片上传自动纠正方向和大小异常格式修复



### V5.1.0

**发布时间**：2023-08-13

- [新功能] ComplexFields组件支持slider输入子项
- [新功能] 系统默认绘图字体调整为阿里巴巴普惠体
- [新功能] 系统默认FontProvider
- [新功能] 内置Markdown编辑器修改为ToastUI
- [新功能] 升级webuploader，引入图片上传全局压缩功能
- [新功能] 文档下载自动打包ZIP，支持引流
- [系统优化] 顶部菜单用户中心增加退出按钮下拉菜单
- [系统优化] 安装向导伪静态测试浏览器缓存问题
- [系统优化] 模块市场、系统升级登录表单提交交互优化
- [Bug修复] 二维码生成类中文字符异常问题修复
- [Bug修复] 手机端文档下载面板默认为VIP异常问题
- [Bug修复] 组件Tags查看模式空值异常问题



### V5.0.0

**发布时间**：2023-07-23

- [新功能] 网站访问记录增加忽略爬虫开关功能，避免记录无效访问记录
- [新功能] FileUtil新增MIME转文件后缀方法
- [新功能] CurlUtil新增返回headerMap数据
- [新功能] GridFilter中like条件新增wordSplit模式，默认中文会分为单字查询，安装WordSpliter可对中文分词
- [新功能] StrUtil增加wordSplit通用分词功能
- [新功能] 文档回收站新增恢复功能
- [新功能] 本地转换文件页数超大时，可设置最大转换页数
- [新功能] GridFilter下拉组件全部（All）选项是否显示可配置
- [新功能] 浏览页面增加付费、免费筛选
- [新功能] 列表排序增加最新上传、下载量、浏览量排序
- [新功能] 当日额度用完引导升级和购买页面
- [新功能] BizException支持自定义特定异常视图
- [新功能] ComplexFields组件新增tip提示文字选项
- [新功能] DynamicFields增加多行文本框组件
- [新功能] VIP页面用户开通VIP增加快捷扫码支付
- [新功能] 会员VIP充值页面新增弹窗模式
- [新功能] 支付中心快速订单自动清理功能
- [新功能] Checkbox组件支持when条件模式
- [系统优化] 无转换器时候引导用户后台配置转换器
- [系统优化] 上传文档时辅助分类交互显示优化
- [系统优化] 后台管理多标签页面背景和Loading效果
- [系统优化] 按钮样式边框兼容性优化
- [系统优化] 系统主题色自动切换样式优化
- [系统优化] 快捷扫码支付界面显示优化
- [系统优化] 数据表格新增弹窗到标签返回列表自动刷新
- [系统优化] 表单输入组件边距样式优化
- [Bug修复] Tags组件数据表格显示异常问题
- [Bug修复] 用户授权登录头像后缀概率性获取异常问题修复
- [Bug修复] 上传文件概率性进度条不显示问题
- [Bug修复] 文档上传时进度条不显示问题
- [Bug修复] Tree组件默认值显示异常问题



### V4.9.0

**发布时间**：2023-07-11

- [新功能] 用户注册、登录、找回密码等页面增加canonical优化爬虫路径
- [新功能] 首页增加最近专题内容
- [新功能] 标签智能识别功能，支持后台预录入标签，前端自动识别标签
- [新功能] 文档详情页面新增文档简介和下载提示
- [新功能] 增加TRACK_LONG_SQL_THRESHOLD配置可配置慢查询阈值，默认5000ms
- [新功能] 文档列表/搜索结果实时显示分类数量（默认关闭，需后台开启）
- [系统优化] xForwardedHostVisitRedirect配置防止CDN域名多URL访问
- [系统优化] 页面description按照按照文档描述、标题的顺序取值
- [系统优化] 微信小程序下载按钮文字调整、顶部搜索框调整
- [系统优化] 后台菜单搜索父级包含关键词时自动显示子项



### V4.8.0

**发布时间**：2023-06-30

- [新功能] 手机、邮箱验证码校验失效日志
- [新功能] Json组件支持API请求通用配置模式 jsonMode(Json::MODE_API)
- [新功能] Form排序新增scope过滤
- [新功能] Form支持排序集合增加到头和尾sortAddPosition配置
- [新功能] 广告位重构，广告类型支持HTML代码、微信小程序广告
- [新功能] MS.eventManager对象，方便页面事件管理
- [新功能] 搜索结果新增分类筛选
- [新功能] 已审核文档禁止用户删除功能设置
- [新功能] 增加智能摘要数据相关标签
- [系统优化] 图片上传、视频上传、文件上传、音频上传组件重构
- [系统优化] 文件预览转换内存调整为不限制
- [系统优化] 首页友情链接UI优化调整
- [系统优化] 模块设置页面增加开发配置提醒，避免随意设置导致的功能异常
- [Bug修复] Number、Text组件默认值不生效问题
- [Bug修复] 下载弹窗显示异常问题



### V4.7.0

**发布时间**：2023-06-25

- [新功能] 导航支持三级菜单
- [新功能] 移动端游客下载成功提示页面
- [新功能] 字符串操作类新增按字节长度裁减UTF8串
- [新功能] 富文本清除格式时，默认移除Table、List上的样式
- [新功能] textarea组件autoHeight方法，可动态调整高度
- [新功能] 字符串操作类新增按特定字符分割方法
- [新功能] 上传附件浏览默认每页20个
- [新功能] 安装向导安装执行脚本超时时间默认为不限
- [新功能] ModelUtil新增上一条下一条记录查询方法
- [新功能] 后台审核页面快速构建工具类和字段
- [新功能] 上传文件删除事件DataDeletedEvent
- [新功能] 用户文件删除自动取消关联
- [新功能] Grid新增urlGrid参数，可设定数据接口
- [新功能] 模型操作方法新增 autoModel、isModel 判断方法
- [新功能] 模块系统配置获取方法modstart_module_config
- [新功能] table样式嵌套模式下显示异常优化
- [新功能] 智能验证码日志记录功能
- [新功能] GridFilter新增支持高级Handle查询方法
- [新功能] 字段增加formShowOnly属性，可设定只在表单中显示
- [新功能] 管理员RoleConfig和UserConfig配置，支持更多权限控制
- [新功能] getNextMaxZIndex增加强制刷新参数
- [新功能] Grid增加data-refresh-grid-on-close支持标签页关闭刷新
- [新功能] 用户评分新增快捷调用方式
- [新功能] MS.util.scrollTo增加param参数，偏移量可设置
- [新功能] 升级UEditorPlus为3.2.0
- [系统优化] 导航后台管理操作界面优化
- [系统优化] 图片懒加载部分场景图片不能显示问题
- [系统优化] 移动端自适应页面搜索框样式优化
- [系统优化] 性能追踪监控参数数据调整
- [系统优化] 微信支付配置信息异常提醒
- [系统优化] 一键CRUD方法优化补全
- [系统优化] 列表样式item-a图标显示优化
- [系统优化] 上传附件删除时是否存在判断
- [系统优化] 表单UI禁用状态背景样式
- [系统优化] 默认按钮样式优化
- [系统优化] 附件管理、文件上传全部优化
- [系统优化] 富文本代码显示样式优化
- [系统优化] 升级jQueryTimeago库，更好支持中文
- [系统优化] 字段默认值逻辑处理优化
- [Bug修复] 手机端支付中心游客支付不获取余额判断
- [Bug修复] register_phone接口不存在问题修复
- [Bug修复] 本地转换页数为1的文档概率性失败问题
- [Bug修复] 一处文件上传事件DataUploadedEvent异常问题
- [Bug修复] VUE多语言翻译带参数返回非中文问题



### V4.6.0

**发布时间**：2023-05-31

- [新功能] 支付中心新增PC快捷扫码支付功能
- [新功能] 支付中心后台管理菜单调整，合并部分功能
- [新功能] 用户PC充值页面适配快捷支付功能
- [新功能] StrUtil支持mbWordwrap分割UTF8字符串
- [新功能] 模块市场登录弹窗显示逻辑优化，支持模块一键购买
- [新功能] 轮播使用者remark参数，显示轮播提示
- [新功能] 财务中心增加退款订单展示
- [新功能] 增加退款方法调用，支持统一支付订单退款你操作
- [新功能] Chart组件，支持复杂图表绘制
- [新功能] 用户增长趋势显示最近30天记录
- [新功能] 文库辅助分类批量修改支持替换、追加、删除三种模式
- [新功能] 补全基础库缺少的依赖glob、date-fns、codepage
- [新功能] Lock锁工具类，方便原子处理
- [新功能] 用户增加授权登录原子化操作
- [新功能] 热门关键词增加长度限制
- [系统优化] 多处UI调整优化
- [系统优化] Grid筛选标签组回显值优化
- [系统优化] 数据表刷新滚动条位置锁定
- [系统优化] 弹窗页面框架结构优化，更好支持底部自定义按钮
- [系统优化] 会话工具类操作方法优化
- [Bug修复] 支付宝手机、支付宝PC支付通道记录异常问题
- [Bug修复] 配置数据为NULL异常问题修复
- [Bug修复] 积分兑换下载逻辑异常问题修复
- [Bug修复] 支付中心微信支付创建标题长度限制
- [Bug修复] 智能验证码H5显示异常问题修复
- [Bug修复] 用户授权登录绑定其他账号异常修复



### V4.5.0

**发布时间**：2023-05-09

- [新功能] 首页轮播图调整为等宽居中
- [新功能] 后台审核新增文档标题查重功能
- [新功能] 导出组件新增支持自定义字段选择功能
- [系统优化] 支付中心回调更新支付方式，解决支付方式记录异常问题
- [系统优化] 后台管理菜单样式优化调整
- [Bug修复] MySQL默认队列表索引长度太长问题
- [Bug修复] 小程序文档下载异常问题



### V4.4.0

**发布时间**：2023-04-25

- [新功能] 轮播图片快速调用方式BannerView
- [新功能] Values组件增加Grid和Detail显示优化
- [新功能] 用户注册IP长度限制
- [新功能] Grid过滤组件Range-Datetime增加快捷时间选取
- [新功能] Banner导航自动隐藏显示动画
- [新功能] 订单对账页面新增交易笔数和收款金额图表
- [新功能] 图表显示新增加另存为图片、数据视图功能
- [新功能] 文库文档详情页面增加默认封面
- [新功能] 用户PC端在线充值功能
- [新功能] 模块安装失败增加日志记录功能
- [新功能] 颜色处理函数，便捷处理主题色
- [新功能] ImageUrl图片信息新增文件大小
- [新功能] 辅助分类需设置启用的主分类ID，默认不启用
- [新功能] ManyRelation组件，支持多对多模型关联
- [新功能] 文档后台管理支持标题、描述、辅助分类、标签编辑
- [新功能] 虚拟文档数量后台可自定义
- [新功能] UEditorPlus升级3.1.0
- [新功能] 文档正文下方增加广告位置
- [新功能] 广告位数据获取接口
- [新功能] 移动端首页、文库详情页增加广告位
- [新功能] 文库首页集成标签云功能
- [新功能] 搜索结果页面调整为两列显示
- [新功能] Echarts基础库升级5.4.2
- [新功能] 后台文档管理批量修改辅助分类
- [新功能] 文档上传匿名显示功能
- [系统优化] 用户找回密码页面样式，增加密码找步骤
- [系统优化] FileUtil文件下载失败时异常捕获返回NULL
- [系统优化] 富文本字体显示大小
- [系统优化] config默认值为null时自动转换为字符串，避免缓存失效
- [系统优化] Tree组件子组件Key默认调整为_child
- [系统优化] 移动设备导航菜单过多自动启用垂直滑动
- [Bug修复] IPV6地址太长问题，自动截断



### V4.3.0

**发布时间**：2023-04-13

- [新功能] 用户VIP权益配置功能
- [新功能] 安装引导界面静态文件强制清除缓存
- [新功能] 文档转换配置举例说明文案
- [新功能] 广告位新增启用、禁用功能
- [新功能] 广告位增加滑动组件 AdView::slides
- [新功能] 广告位增加设备检测功能，适配桌面端和移动端展示不同内容
- [新功能] 新闻资讯增加NewsView快捷调用方式
- [新功能] Response::abortMsg支持JSON格式自动识别
- [新功能] HTML静态转换支持页面HTML懒加载，提升访问速度
- [系统优化] 代码目录结构重新整理，优化命名空间，弃用标记
- [系统优化] 列表默认数量从调整为24个条目
- [系统优化] 后台Grid图片预览采用Contain模式
- [系统优化] UEditorPlus富文本编辑器图片自动抓取忽略URL优化
- [系统优化] 用户注册自动关联默认VIP和默认分组
- [Bug修复] 「下载浏览全部」不生效问题
- [Bug修复] 首页Banner和菜单层级问题修复
- [Bug修复] Admin配置页面config获取数组逻辑异常问题
- [Bug修复] Checkbox组件默认值不生效问题修复



### V4.2.1

**发布时间**：2023-04-04

- [Bug修复] JS部分异常问题修复



### V4.2.0

**发布时间**：2023-04-04

- [新功能] Select组件和Grid筛选新增selectSearch属性，选项可搜索
- [新功能] Number、Decimal、Currency组件添加符号显示（signShow）和自动着色（autoColor）配置
- [新功能] 调整文库配置文案
- [新功能] LayUI升级到最新版，移除独立Layer
- [新功能] 移动端UI设计重构
- [新功能] 轮播图增加背景颜色和container模式，适配大屏模式的显示
- [新功能] 文库首页改版，页面列表样式改版
- [新功能] 为jQuery新增serializeJson方法
- [新功能] 请求错误新增具体错误码和错误信息
- [新功能] 文档后台审核界面升级
- [系统优化] 用户消息模板查找路径
- [系统优化] 安装配置文件缺少数据库端口配置问题修复
- [Bug修复] 文档审核批量拒绝不生效问题处理



### V4.1.0

**发布时间**：2023-03-27

- [新功能] 底部样式统一调整深色，丰富内容
- [新功能] 基本设置支持其他备案信息
- [新功能] 网站信息新增联系信息，支持邮箱电话等联系方式
- [新功能] 折线图表数据库使用优化
- [新功能] ModStartRequestHandled事件
- [新功能] 网站默认宽度调整为60rem
- [新功能] AdminUser表单组件
- [新功能] 系统样式随机颜色升级
- [新功能] 积分充值适配支付中心业务
- [新功能] 后台用户钱包充值订单
- [新功能] 短信发送使用任务队列替代同步发送
- [新功能] 文档下载逻辑重构，支持游客下载到邮箱或短信
- [新功能] 用户后台增加文档浏览量和下载量信息
- [新功能] HTML页面预览显示样式错乱问题修复
- [新功能] 数据库字符集默认调整为utf8mb4
- [新功能] 用户后台积分流水、现金流水增加用户ID筛选
- [新功能] 后台待审核链接在新标签页打开
- [新功能] GridFilter增加数字和文本范围查询
- [新功能] 文件即将上传和文件上传完成事件
- [新功能] 支付中心新增H5配置动态返回功能
- [系统优化] Decimal数据输入内容过滤和处理
- [系统优化] 后台用户管理操作方式优化
- [Bug修复] 文档被下载和被浏览数值异常问题



### V4.0.0

**发布时间**：2023-03-20

- [新功能] 支持文档转静态HTML，大幅度提升SEO效果
- [新功能] 文档转换时自动清除历史文件
- [新功能] 组件验证规则支持数组添加，自动过滤空值
- [新功能] 非首页和搜索结果页顶部显示搜索框，可随时搜索内容
- [新功能] Values组件新增viewMode，支持mini一行显示模式
- [新功能] 文档搜索结果增加类型、排序、页数筛选
- [新功能] 文件列表增加文档页数筛选功能
- [新功能] 邮件发送SMTP客户端对接
- [新功能] 用户登录日志记录，方便进行登录安全日志分析
- [新功能] 网页首页标题新增加副标题
- [新功能] data-header-sticky-disable特性可部分页面禁止头部滚动
- [新功能] UEditorPlus升级3.0.0
- [新功能] 安装向导增加zip和curl的PHP扩展检测
- [新功能] 数据库调整为严格模式（字段截取抛出异常）
- [系统优化] 表单处理JS部分代码逻辑重构
- [系统优化] 视图文件命名统一优化调整
- [系统优化] 搜索引擎爬虫引导，增加部分链接ref=nofollow属性
- [系统优化] 余额支付在用户未登录时不显示
- [系统优化] 文库移动端样式优化
- [系统优化] 富文本编辑器UEditor样式缓存问题
- [系统优化] 文档删除文件自动删除逻辑
- [Bug修复] 后台管理角色增加异常问题
- [Bug修复] 本地PNG图片转换异常问题修复
- [Bug修复] PNG图片转换从第二页开始的问题



### V3.9.0

**发布时间**：2023-03-14

- [新功能] 适配新闻资讯功能模块
- [新功能] 顶部导航只保留登录按钮功能
- [新功能] 移动端注册登录支持智能验证码
- [新功能] 标签云页面UI升级
- [新功能] 用户中心功能UI升级
- [新功能] 账号自助注销功能，用户可自主申请注销账号
- [新功能] 文库专题功能
- [新功能] 集成用户认证功能
- [新功能] 每日免费下载免费文档数量可配置
- [新功能] 友情链接图片链接懒加载
- [新功能] 字段Rules数据类型从字符串调整为数组
- [新功能] 本地转换支持转换为PNG图片
- [系统优化] 图片懒加载组件加载中图片更新
- [系统优化] 用户设置后台界面帮助文字说明文案修改
- [系统优化] 用户VIP等级过期时间可为空，留空表示永久等级
- [系统优化] 内容评分界面文案和样式优化
- [系统优化] 用户VIP等级编辑设置界面参数按模块分区



### V3.8.0

**发布时间**：2023-03-10

- [新功能] 安装显示增加数据库端口
- [新功能] 文档不存在时返回404页面异常
- [新功能] 页面滑动新增body-scroll-far特性
- [新功能] 动态变更页面标签页标题方法
- [新功能] RepositoryFilter新增clear方法，用于清除仓库条件
- [新功能] 标签云适配后台多标签打开模式
- [新功能] FileUtil新增流下载方法函数
- [新功能] 魔众API云端转换接口开通说明
- [新功能] 友情链接标题可设置，样式显示优化
- [新功能] 友情链接新增启用/禁用状态
- [新功能] 后台登录界面显示ICP备案编号
- [新功能] 全局异常处理忽略部分非法请求日志记录
- [新功能] 模块控制器中支持全路径视图路径解析
- [新功能] 基础导入导出功能新增CSV、Excel多表格支持
- [新功能] 内容审核Job新增快速创建方法
- [新功能] UEditorPlus升级2.9.0
- [新功能] 用户批量导出功能，可通过 exportEnable 配置
- [新功能] 用户VIP页面改版，新增VIP简要说明
- [新功能] 用户表新增用户消息字段，记录用户未读消息数量
- [新功能] 上传时获取后缀名开关可配置
- [新功能] 下载时跳转真实路径后台可配置
- [新功能] 后台主题浅色模式，.env 配置 ADMIN_THEME=light 切换浅色
- [新功能] 后台页面打开支持配置是否显示标签页，.env 配置 ADMIN_TABS_ENABLE=false 关闭
- [新功能] MS.util.getNextMaxZIndex() 方法，动态获取下一个最大的z-index
- [新功能] 用户注册新增第三方验证码功能
- [新功能] 静态资源支持自带参数并保留文件Hash
- [新功能] 默认空头像图片重新设计
- [系统优化] 模块名称非法时自动过滤，避免模块加载异常
- [系统优化] 后台多标签模式标题动态显示优化
- [系统优化] 用户中心样式文件修改修改
- [系统优化] 支付中心订单支付成功/失败时跳转地址为空优化
- [系统优化] 内容审核抽象提供者使用方式简化
- [系统优化] 侧边栏菜单样式显示优化
- [系统优化] 用户修改头像页面重构优化，防止裁减图片过大
- [系统优化] modstart_config 函数根据默认值类型默认自动反序列化JSON
- [系统优化] Checkbox 组件序列化保存时对数字字符串默认转数字
- [系统优化] 用户消息中心样式优化，操作更便捷
- [系统优化] 后台清除缓存操作菜单简化操作，直接点击操作
- [系统优化] 顶部导航二级菜单增加图标支持



### V3.7.0

**发布时间**：2023-02-11

- [新功能] 财务概况页面，支持财务状况总览
- [新功能] 多语言文件支持放置在 resources/lang 目录下
- [新功能] 后台支持通用文章链接跳转功能
- [新功能] 轮播图底部导航图标显示优化
- [新功能] 调整HTML过滤规则缓存目录为 cache/purifier
- [新功能] MS.header前端组件对象获取支持多个头部
- [新功能] 系统打包支持系统Meta信息
- [新功能] 文档云转换新增是否开启开关
- [新功能] 后台登录背景默认为纯色背景
- [新功能] Grid中新增和修改弹窗默认增加窗口关闭方法
- [系统优化] 文件上传兼容多云存储驱动，可配置
- [系统优化] 调整支付中心日志记录细化统一
- [系统优化] 后台页面Tab点击触发时鼠标移动忽略规则
- [系统优化] 后台升级图标样式，大小显示优化
- [系统优化] 性能跟踪代码性能优化，提升执行效率
- [系统优化] 多层代理获取真实IP异常问题
- [系统优化] 后台管理员日志记录数据序列化优化
- [系统优化] 导入页面兼容后台多标签方式展示
- [系统优化] 新窗口新增页面兼容多标签模式
- [Bug修复] CountUp小数不生效问题
- [Bug修复] 用户名邮箱正则异常问题优化
- [Bug修复] values组件增加项不生效问题修复
- [Bug修复] 导航栏新窗口打开异常问题修复
- [Bug修复] 后台多标签页面关闭窗口样式激活修复
- [Bug修复] 组件SelectRemote和CanCascade条件显示异常问题
- [Bug修复] 导航轮播适配最新版本方法调用
- [Bug修复] 微信支付订单提交时统一ID重复问题修复



### V3.6.0

**发布时间**：2022-12-29

- [新功能] 文件写入方法新增是否成功返回
- [新功能] 富文本附件显示样式调整，图标替换为SVG
- [新功能] 用户名长度可后台配置（默认为3）
- [新功能] 禁止注册时允许设置以授权方式注册
- [新功能] 任务调度新增上次运行时间设定
- [新功能] 任务调度记录调度日志和调度结果
- [新功能] 文库系统301跳转首页功能
- [新功能] 响应新增永久重定向方法 redirectPermanently
- [新功能] 文库系统301跳转首页功能
- [新功能] 补全部分数据库模型文件
- [新功能] 文件上传预期错误重传机制
- [新功能] 数字动态增长组件，数字动态显示效果
- [新功能] 支持设置实名认证后上传文档功能
- [新功能] UEditorPlus升级2.7.0版本
- [新功能] 文库文档删除事件WenkuDocDeleted
- [新功能] 用户管理详情新增性别显示
- [新功能] 富文本过滤规则调整优化
- [新功能] 后台管理菜单当前计算支持 active 属性
- [新功能] Dialog组件默认值为非字符串时初始化异常
- [新功能] 内核增加 SelectRemote 组件，支持动态下拉组件
- [新功能] 移动端文档首页、文档列表页面支持分享
- [新功能] 文库文档后台可替换上传
- [新功能] 后台可批量上传文库文档（需安装 WenkuAdminUpload 模块支持）
- [新功能] 文档可单独设置是否支持VIP特权免费下载
- [新功能] 所有组件新增tip参数，用于Grid、Form、Detail提示说明
- [新功能] ArrayPackage数组输入数据包处理器
- [新功能] VIP用户等级新增可见字段，控制前端是否展示
- [新功能] 后台页面支持多标签多开方式
- [新功能] 后台文档管理新增分类筛选条件
- [新功能] 文档下载时支持事件触发
- [新功能] 邮件发送任务支持HTML传入模式
- [新功能] 文档转换重构，支持多种文档转换器
- [新功能] 文库上传支持类型后端可配置
- [新功能] 模块市场页面刷新兼容TAB标签
- [系统优化] 拼接链接过滤空值参数优化
- [系统优化] 部分浏览器富文本编辑字体问题优化
- [系统优化] 文件升级文件权限检测显示优化
- [系统优化] 富文本源码模式下光标显示错位问题优化
- [系统优化] 账号资料邮箱绑定绑定界面根据注册方式优化
- [系统优化] 用户删除逻辑修复部分已知问题
- [系统优化] 文库用户首页页面显示优化
- [系统优化] 前端页面弹窗提示组件显示抖动优化
- [系统优化] Excel通用批量导入界面功能优化
- [系统优化] 后台菜单关键词搜索不生效问题
- [系统优化] 筛选条件树状选择器支持枚举和数据模型
- [系统优化] 后台管理左侧菜单工具栏优化
- [Bug修复] 原子操作声场概率性异常问题
- [Bug修复] 根据文档名称检测重复异常问题修复
- [Bug修复] 富文本源码模式下内容编辑不生效问题修复
- [Bug修复] 浏览器自适应或尺寸变更时轮播自动更新
- [Bug修复] Detail页面为模型时异常问题
- [Bug修复] values 组件缺省值自动填充问题修复



### V3.5.0

**发布时间**：2022-11-18

- [新功能] 文档批量重试命令 Wenku:ConvertRetry
- [新功能] 文档批量上传命令 Wenku:BatchImport
- [新功能] 文档预览页数可独立设置，默认为最大预览页数
- [新功能] 预览页数后台可批量修改
- [新功能] 文档下载记录可根据文档标题模糊搜索
- [新功能] 适配SiteUrlBiz方便生成SiteMap链接
- [新功能] 后台用户总数统计非删除用户数量
- [新功能] 已删除用户调用时显示为&quot;已删除用户&quot;
- [新功能] 小程序页面分享功能
- [新功能] 移动端新增Tree、Bin预览模式
- [系统优化] 模块配置加载异常时显示提示
- [系统优化] 邮件发送队列名称默认调整为default
- [系统优化] 富文本编辑器UEditorPlus升级v2.6.0
- [系统优化] 文件处理工具类权限异常时屏蔽错误信息
- [系统优化] 文档页面分享功能重构
- [系统优化] ElementUI数字输入组件边框样式
- [系统优化] 后台登录页面跳转链接渲染异常问题
- [系统优化] 用户头像保存数据获取格式校验
- [系统优化] 模块市场登录框和用户信息框优化
- [系统优化] 升级登录框优化
- [系统优化] 捕获处理MethodNotAllowed异常
- [Bug修复] 部分下载方式下载数量不能自动计算问题
- [Bug修复] 文档订单为0时购买逻辑优化



### V3.4.0

**发布时间**：2022-10-27

- [新功能] 系统升级调用命令容错处理
- [新功能] 数据库兼容MySQL8.0
- [新功能] OpenApi和Api中间件新增AccessGate
- [新功能] 文件上传表新增大类和分类索引
- [新功能] 游客订单功能显示
- [新功能] 用户注册处理器新增排序字段
- [新功能] ProviderTrait新增是否排序自动检测
- [新功能] 模块新增标签属性功能
- [新功能] 用户注册登录弹窗逻辑兼容处理
- [新功能] 富文本标签A新增download属性过滤
- [新功能] 游客最大预览页数限制功能
- [新功能] 网站地址配置项
- [新功能] 导航后台支持图标字段
- [新功能] 安装向导根路径配置错误检测提醒
- [新功能] 后台文库管理新增页码跳转
- [新功能] 是否多用户组判断方法inGroupIds
- [新功能] 可以设置用户是否能上传文档
- [新功能] 文库详情页面增加标签显示
- [新功能] 页面能调用文档简介，便于搜索引擎索引
- [新功能] 评价新增后台内容链接标题
- [新功能] 批量审核、批量转换重试
- [新功能] 批量修改文档浏览量
- [新功能] 移动端补全部分缺失依赖
- [新功能] 后台文库管理增加状态和转换状态筛选
- [新功能] 用户手机登录时自动注册
- [新功能] 快捷注册用户用户名新增手机号、UID、手机号后四位占位符
- [新功能] 后台AdminMemberInfo字段显示字段可配置
- [系统优化] 系统升级界面日志颜色优化
- [系统优化] 系统集成时源代码编辑行距问题优化
- [系统优化] 支付中心回调日志优化完善
- [系统优化] 模块市场显示样式和文案
- [系统优化] 路由请求定义优化
- [系统优化] 后台登录背景大小为全屏
- [系统优化] 压缩文件解压编码问题修复
- [系统优化] 当前用户组返回逻辑处理
- [系统优化] 文库文件为本地时CDN下载路径问题
- [系统优化] 远程文件拉取到本地时超时时间调整为600秒
- [系统优化] 魔众API相关接口调用超时时间调整为600秒
- [Bug修复] 数据库队列并发死锁问题
- [Bug修复] 后台评价管理链接异常问题
- [Bug修复] 用户VIP下载重复时异常问题



### V3.3.0

**发布时间**：2022-10-05

- [新功能] 增加Button组件，支持表单快捷提交
- [新功能] 富文本组件新增htmlFilter属性，定制配置过滤
- [新功能] 用户钱包充值接口功能
- [新功能] 所有文档任意状态可重试转换
- [新功能] 手机快捷注册自动设置用户名和昵称
- [新功能] 富文本过滤图片新增data-formula-image属性
- [新功能] 用户VIP开通赠送积分功能开启
- [新功能] 授权登录绑定手机和邮箱可配置
- [新功能] 后台新增重新触发事件操作
- [新功能] 订单新增支付事件是否成功状态
- [新功能] 随机字符串新增大写和小写可读字符串
- [新功能] 后台文档列表选择弹窗功能
- [新功能] 文库文档页面预览增加Loading动画
- [新功能] 支持EPUB文件上传和下载功能
- [新功能] 用户新增Meta信息，用于底层临时存储部分关联信息
- [新功能] Request新增isGet方法用于判断GET请求方式
- [新功能] 用户注册IP信息
- [新功能] TextAjaxRequest组件部分属性重构和新增方法
- [新功能] 后台登录背景优化
- [系统优化] 用户中心功能设置界面重构
- [系统优化] 配置函数根据默认值类型自动推断
- [系统优化] 用户VIP开通支付实现方式
- [Bug修复] 支付宝创建支付字段太长问题
- [Bug修复] 后台用户状态修改失败问题
- [Bug修复] 后台文档批量删除功能失效问题



### V3.2.0

**发布时间**：2022-08-25

- [新功能] 登录界面全新改版大气美观
- [新功能] 支持ZIP文档上传和文件列表预览
- [新功能] 批量设置积分、现金、标签功能
- [新功能] UEditorPlus升级到2.3.0
- [新功能] bodyProperties可为body标签增加属性
- [新功能] 图标库新增 check-simple
- [新功能] Cookie库新增属性参数
- [新功能] 用户授权模块微信小程序优化
- [新功能] 微信H5支付功能
- [新功能] 后台管理员角色新增备注字段
- [新功能] 后台用户列表新增用户信息和修改账号操作
- [新功能] Grid编辑操作名称可自定义
- [新功能] 转换中的文档也可重试转换
- [新功能] 后台文档列表积分和金额可编辑
- [新功能] 文档下载提示文案配置
- [新功能] 文档图片预览新增延迟加载功能
- [新功能] 会员新增时VIP过期时间调整为非必须
- [新功能] FileUtil新增文件大小精简格式化
- [新功能] 队列任务处理超时时间调整为3600秒
- [新功能] 公安备案信息后台可配置
- [新功能] 后台手动增加会员触发事件
- [系统优化] 富文本自动抓取图片优化为串行抓取，避免批量接口超时问题
- [系统优化] 新增字段VIP信息缓存问题
- [系统优化] 文件上传和文件管理逻辑优化
- [系统优化] 富文本远程图片自动抓取逻辑优化
- [系统优化] 字段组件一处渲染异常日志记录问题
- [系统优化] Recycle相关操作类（可使用Recycle模块替代）
- [系统优化] 网站标题连接符优化
- [系统优化] Model工具多表Join功能优化
- [系统优化] 后台用户管理创建和编辑界面重构完成
- [系统优化] Cookie 中 SameSite 默认调整为 Lax
- [Bug修复] Response下载文件部分浏览器异常
- [Bug修复] 后台手动增加用户时后台不显示的问题
- [Bug修复] 一处基础授权登录信息获取异常问题
- [Bug修复] 手机首页标题异常问题
- [Bug修复] 升级Laravel版本造成的安装路径检测异常



### V3.1.0

**发布时间**：2022-08-01

- [新功能] 后台用户列表新增授权登录标记
- [新功能] 后台管理用户批量禁用账户的功能
- [新功能] 后台管理用户信息查看列表新增用户ID
- [新功能] 系统升级提醒开关可配置
- [新功能] 系统升级关闭开关可配置
- [新功能] 模块市场预览包功能支持
- [新功能] 模块管理模块升级判断逻辑修改
- [新功能] 文库转换失败重试功能
- [新功能] 适配关键词分词搜索（需WordSpliter模块支持）
- [新功能] 文件上传切片最大2M，分片文件根据配置动态清除
- [新功能] Type类型数据新增导出JS配置文件
- [新功能] Json组件增加高度可配置参数
- [新功能] Grid新增批量弹窗快捷操作方式
- [新功能] Response新增停止执行抛出消息的方法
- [新功能] 富文本组件新增 editor-ready 自定义事件
- [系统优化] UEditorPlus升级为v2.2.0
- [系统优化] 字符串工具类中的特殊字符处理重复
- [系统优化] 富文本编辑移除地图功能
- [系统优化] 富文本文件抓取CDN域名逻辑
- [系统优化] UEditor下拉、颜色选择、组件错位优化
- [系统优化] 文库转换日志记录更合理
- [系统优化] HttpException正常请求错误消息不记录
- [Bug修复] uniapp筛选组件与标题设置冲突问题修复
- [Bug修复] 导入弹窗模板文件框架JS不生效问题



### V3.0.0

**发布时间**：2022-07-01

- [新功能] 模块目录非法时自动过滤
- [新功能] 安全检测新增安装向导文件删除检测
- [新功能] 用户登录页面样式优化调整
- [新功能] 静态资源打包新增文件类型
- [新功能] 用户默认登录方式可切换用户名密码或手机验证码
- [新功能] 手机验证码快捷登录方式
- [新功能] 富文本图片编辑宽高为空时自动清除图片宽度和高度
- [新功能] 用户登录跳转URL安全验证可配置
- [新功能] 创建文件夹失败时记录日志
- [新功能] 手机验证码快捷注册方式
- [新功能] 账号删除功能，后台可手动删除用户
- [新功能] 注销账号功能，用户可主动申请注销账号
- [新功能] 用户积分名称全局可修改
- [新功能] 接口不存在时提示显示接口路径
- [新功能] 后台新增用户钱包流水详情列表
- [新功能] 后台新增用户积分流水详情列表
- [新功能] 用户中心微信小程序授权绑定逻辑优化调整
- [新功能] 标签云标签重建功能
- [新功能] 文档列表新增封面模式和简单标题列表模式
- [新功能] 首页文档列表模式设置
- [系统优化] 搜索框样式优化，优化Grid列表样式和Tab样式
- [系统优化] Grid 文件预览显示优化
- [系统优化] 文件显示多语言显示优化
- [系统优化] 后台登录验证码缓存问题
- [系统优化] 用户消息发送模板查找逻辑升级
- [系统优化] 调整用户设置相关菜单到用户中心
- [系统优化] 用户授权登录OpenId绑定key逻辑
- [Bug修复] IFRAME预览模式转换自定义封面不生效
- [Bug修复] Form 新增规则校验失效问题
- [Bug修复] 静态资源JS打包异常时文件没有复制问题
- [Bug修复] 手机版授权登录问题修复
- [Bug修复] 我的文档下载操作失效问题



### V2.9.0

**发布时间**：2022-05-27

- [新功能] 友情链接、首页轮播位置调整（需重新设置）
- [新功能] Windows本地文档转换功能优化
- [新功能] 前端依赖补全
- [新功能] 免登陆购买下载文档
- [新功能] VIP用户每日免费下载付费文档数量
- [新功能] 移动端我的页面样式优化
- [新功能] 移动端搜索页面返回操作
- [新功能] 日志新增Rotate特性，避免历史日志堆积
- [新功能] 后台问题反馈调整为新Tab显示
- [新功能] 富文本过滤新增HTML5标签
- [新功能] 启用富文本UEditorPlus
- [新功能] 用户登录完成默认跳转到用户中心
- [新功能] 接口异常友好提示
- [新功能] 默认支持webp图片文件格式
- [新功能] 用户名最少3个字符限制
- [新功能] Hook新增DialogPageHeadAppend和DialogPageBodyAppend
- [系统优化] 富文本HTML行高显示，大字体显示异常
- [系统优化] 文件选择组件显示样式优化
- [系统优化] 用户中心&rarr;我的文档标题搜索使用模糊匹配
- [系统优化] 接口异常返回信息提示
- [系统优化] 文件上传获取路径为空问题
- [系统优化] 配置值为空时缓存设置和存储优化



### V2.8.0

**发布时间**：2022-04-24

- [新功能] 用户中心新增退出登录
- [新功能] 图标大小统一调整优化
- [新功能] 模块市场登录增加微信扫一扫
- [新功能] 404页面和500错误页面美化升级
- [新功能] 系统初始化安装引导文件升级
- [新功能] 导航栏搜索框（非首页和搜索页面显示）
- [新功能] 文档推荐功能，推荐的文档会显示在首页
- [新功能] 文档修改页面重构
- [新功能] 首页提供者同时支持适配手机端和电脑端
- [新功能] 文档列表新增文档格式筛选功能
- [新功能] 支持按后缀格式筛选
- [新功能] 新增余额支付功能
- [新功能] 系统升级文件写入权限检查校验
- [新功能] UEditor支持本地视频插入
- [新功能] 管理日志列表增加管理员字段
- [系统优化] 内容增加/编辑默认遮罩层点击不关闭
- [系统优化] Select组件Key不存在时候友好显示
- [系统优化] Env文件解析功能优化
- [系统优化] 富文本编辑器添加视频小屏适配
- [系统优化] 富文本编辑器图片可配置对其方式，可二次编辑
- [Bug修复] 管理菜单为URL时不能自动定位当前
- [Bug修复] 模块卸载版本检测失效问题



### V2.7.0

**发布时间**：2022-03-28

- [新功能] UNIAPP手机端
- [系统优化] 标签样式显示方式
- [系统优化] 上传错误时显示提醒错误信息
- [系统优化] 转换任务失败时异常记录
- [Bug修复] 后台浮动确定区域左侧宽度问题调整
- [Bug修复] 多级导航菜单不能返回全部的问题



### V2.6.0

**发布时间**：2022-03-21

- [新功能] 后台应用概况显示系统名称
- [新功能] 新增文档收藏功能
- [新功能] 用户VIP界面优化，增加主标题和副标题
- [新功能] 下载文件名使用文档标题
- [新功能] 用户VIP页面不登录访问不受限
- [新功能] 用户中心新增已下载的文档
- [新功能] 文档喜欢功能
- [新功能] 用户钱包功能
- [新功能] 增加文库文档购买功能
- [新功能] 集成用户评分系统
- [新功能] 增加标签云，增加标签搜索
- [新功能] 广告位（文档内容、文档右侧、列表右侧）
- [新功能] 文库水印功能
- [新功能] 文档回收站，已软删除的文档可物理删除（包括文件）
- [新功能] 意见反馈功能模块
- [系统优化] 后台待审核文档显示优化
- [系统优化] 表格无数据时内容优化（增加图标）
- [系统优化] 手机页面搜索页列表显示
- [系统优化] 表格刷新自动跳转到顶部优化
- [Bug修复] 文档下载次数更新不及时的问题
- [Bug修复] 管理员审核文档时看不到文档内容
- [Bug修复] 后台链接选择同类别不能自动合并问题



### V2.5.0

**发布时间**：2022-03-14

- [新功能] UEditor 粘贴图片自动上传功能
- [新功能] 文库自定义封面
- [新功能] 增加文库批量上传功能
- [新功能] 文档状态拆分转换状态和审核状态
- [新功能] 文档转换失败时支持配置默认预览图片
- [新功能] 后台管理员文档审核功能可关闭
- [新功能] 增加热门搜索功能
- [系统优化] 后台界面显示优化升级
- [系统优化] 优化弹窗重复导入的异常问题
- [系统优化] 优化用户区域显示界面
- [Bug修复] 文件选择弹窗自定义输入链接不生效问题



### V2.4.0

**发布时间**：2022-03-02

- [新功能] Banner批量删除功能
- [新功能] 导航批量删除功能
- [新功能] 导航位置Tab切换
- [新功能] 本地模块筛选Tab，只显示本地模块
- [新功能] 可升级模块筛选，显示系统可升级的模块
- [新功能] 后端管理分类最大调整为4级
- [新功能] 文件上传事件触发 DataFileUploadedEvent，增加 DriverName
- [新功能] 管理员登录成功、登录失败、退出事件触发
- [系统优化] Windows命令兼容问题
- [系统优化] 前端分类筛选不限制问题修复
- [系统优化] 列表显示数量调整为默认16个
- [系统优化] GridFilter 下拉选择、单选匹配逻辑优化
- [系统优化] 长请求监控、长SQL监控、多SQL请求监控
- [系统优化] 表单页面组件overflow显示优化
- [系统优化] Decimal 组件不能为负数问题
- [系统优化] Detail 记录不存在显示问题
- [Bug修复] 列表子分类不显示问题



### V2.3.0

**发布时间**：2022-02-05

- [新功能] 后台菜单快捷搜索（支持汉字、简拼、全拼）
- [系统优化] 状态组件显示优化
- [系统优化] 普通表单提交Loading优化
- [系统优化] 后台自动升级Token存储优化
- [Bug修复] 修复已知若干问题



### V2.2.0

**发布时间**：2022-01-06

- [新功能] 轮播文字内容新增动画
- [新功能] 后台菜单一键展开所有菜单功能
- [新功能] 数据表格列未设置宽度自动适配
- [新功能] 管理员增加手机号和邮箱字段
- [新功能] 文件选择弹窗增加文件链接复制功能
- [新功能] 安装助手新增显示应用名称和版本
- [新功能] 新增富文本显示优化
- [新功能] 会员隐私协议可配置
- [系统优化] 字段ID默认固定宽度去除
- [系统优化] 视图查找顺序重构优化
- [系统优化] 完成网站ICO图标更新
- [系统优化] 字段渲染模式异常捕获
- [Bug修复] 顶部导航Logo手机端高度适应问题
- [Bug修复] 自定义字段详情显示异常问题



### V2.1.0

**发布时间**：2021-12-08

- [新功能] 升级页面登录内容优化
- [系统优化] 新增模块时系统自动升级优化
- [系统优化] 富文本前台iframe显示尺寸优化
- [系统优化] 后台管理框架Logo显示
- [系统优化] 清理Laravel优化文件缓存
- [系统优化] 页面SEO全面优化
- [系统优化] 小窗口表单显示边距调整
- [系统优化] 文章系统展示SEO优化
- [Bug修复] 快速CRUD中hookSaving调用异常
- [Bug修复] 前端UrlEncode为数字时处理异常



### V2.0.0

**发布时间**：2021-11-01

- [新功能] 升级ModStart，模块灵活集成
- [新功能] 文库分类
- [新功能] 文库转换提供Provider模式，方便云端集成
- [新功能] 增加默认Bin模式文档转换
- [系统优化] 界面优化，功能升级



### V1.0.0

**发布时间**：2021-10-01



## 演示地址

[https://mzwenku.demo.tecmz.com/](https://mzwenku.demo.tecmz.com/)

## 下载试用

[http://tecmz.com/product/mzwenku](http://tecmz.com/product/mzwenku)