# 电商 AI 技能库

精心整理的电商 AI 技能文件集合仓库，方便浏览、复用与后续持续整理。

🌟 整了个discord群，如果你也感兴趣电商龙虾养殖，欢迎加入！🐝
https://discord.gg/yYjYQzjZf8

## 仓库内容

- `skills/`：先按电商业务分类组织，再按来源命名空间细分。
- `skills/<category>/finsilabs/`：包含从 `finsilabs/awesome-ecommerce-skills` 导入并映射到对应分类下的技能。
- `skills/<category>/openclaw/`：包含从 `openclaw/skills` 中导入的活跃电商相关技能。
- `README.md`：提供可浏览的技能目录，并附带可点击进入每个技能文件夹的链接。
- `LICENSE`：本仓库所使用的许可证文件。

## 分类目录

- `storefront-shopping-experience`
- `catalog-inventory`
- `pricing-promotions-loyalty`
- `checkout-payments-tax`
- `orders-shipping-returns`
- `customer-support-crm`
- `marketing-growth`
- `analytics-reporting`
- `platform-integrations-infrastructure`

## 技能目录

每个技能名称都直接链接到本仓库中的对应文件夹。

### 店铺前台与购物体验

| 技能 | 说明 |
|---|---|
| [accessibility-commerce](skills/storefront-shopping-experience/finsilabs/storefront-ui/accessibility-commerce/) | 通过符合 WCAG 2.1 AA 标准，让你的商店对所有用户可用，包括屏幕阅读器支持、键盘导航，以及无障碍购物车和结账流程。 |
| [b2b-commerce](skills/storefront-shopping-experience/finsilabs/business-operations/b2b-commerce/) | 通过企业账户、自定义目录、报价流程、采购订单和账期付款，支持批发和 B2B 销售。 |
| [faceted-navigation](skills/storefront-shopping-experience/finsilabs/storefront-ui/faceted-navigation/) | 让顾客可以同时按多个属性筛选商品，支持 URL 分享筛选状态、即时结果和移动端友好控件。 |
| [groupon-skill](skills/storefront-shopping-experience/openclaw/dejimarquis/groupon-skill/) | 在 Groupon 上查找本地优惠和折扣服务，例如换机油、瑜伽课、按摩、健身、餐饮等。 |
| [image-zoom-360](skills/storefront-shopping-experience/finsilabs/storefront-ui/image-zoom-360/) | 通过高清图片放大、360 度旋转视图和内嵌视频提升商品可信度，让顾客在购买前看得更清楚。 |
| [mega-menu-builder](skills/storefront-shopping-experience/finsilabs/storefront-ui/mega-menu-builder/) | 为大型商品目录构建丰富的导航超级菜单，支持商品图片、分类亮点、精选横幅和可键盘操作的下拉菜单。 |
| [product-comparison](skills/storefront-shopping-experience/finsilabs/storefront-ui/product-comparison/) | 让顾客选择多个商品并在表格中并排比较，通过突出差异帮助他们做出更合适的购买决策。 |
| [product-page-design](skills/storefront-shopping-experience/finsilabs/storefront-ui/product-page-design/) | 设计高转化商品详情页，包含图片画廊、规格选择器、社会证明和清晰的加入购物车按钮。 |
| [quick-view-modal](skills/storefront-shopping-experience/finsilabs/storefront-ui/quick-view-modal/) | 让顾客无需离开列表页即可预览商品详情并加入购物车，减少购物流程中的阻力。 |
| [recently-viewed-products](skills/storefront-shopping-experience/finsilabs/storefront-ui/recently-viewed-products/) | 使用浏览器存储展示顾客最近浏览过的商品，方便他们继续上次的浏览进度。 |
| [responsive-storefront](skills/storefront-shopping-experience/finsilabs/storefront-ui/responsive-storefront/) | 构建移动优先的店铺前台，包含拇指友好的导航、粘性加购按钮和为触屏优化的组件，以提升移动端转化率。 |
| [search-autocomplete](skills/storefront-shopping-experience/finsilabs/storefront-ui/search-autocomplete/) | 借助 Algolia 或 Elasticsearch 提供即时搜索建议、模糊纠错和按分类感知的结果，加快商品发现。 |
| [storefront-theming](skills/storefront-shopping-experience/finsilabs/storefront-ui/storefront-theming/) | 基于设计令牌和 CSS 自定义属性构建可主题化前台，支持白标、多品牌变体和深色模式。 |
| [wishlist-save-for-later](skills/storefront-shopping-experience/finsilabs/storefront-ui/wishlist-save-for-later/) | 让顾客把商品保存到愿望清单、分享给朋友，并在补货或降价时收到通知。 |

### 商品目录与库存

| 技能 | 说明 |
|---|---|
| [catalog-import-export](skills/catalog-inventory/finsilabs/catalog-inventory/catalog-import-export/) | 使用平台原生工具或专用应用批量导入导出完整商品目录，并支持校验和定时同步。 |
| [cogs-tracking-allocation](skills/catalog-inventory/finsilabs/catalog-inventory/cogs-tracking-allocation/) | 借助平台内置工具或财务集成追踪销售成本与落地成本，以计算每笔订单的准确毛利。 |
| [digital-products](skills/catalog-inventory/finsilabs/catalog-inventory/digital-products/) | 销售软件、电子书和其他数字下载内容，支持安全交付、许可证密钥生成、下载次数限制和过期控制。 |
| [inventory-tracking](skills/catalog-inventory/finsilabs/catalog-inventory/inventory-tracking/) | 在平台内实时追踪库存水平，支持库存预留、防止超卖以及缺货预售。 |
| [low-stock-alerts](skills/catalog-inventory/finsilabs/catalog-inventory/low-stock-alerts/) | 当商品库存低于自定义阈值时自动提醒，帮助你在缺货前及时补货。 |
| [merchandising-rules](skills/catalog-inventory/finsilabs/business-operations/merchandising-rules/) | 使用自动排序规则、人工覆盖和基于表现的排序算法，控制商品在集合页中的展示顺序。 |
| [multi-warehouse](skills/catalog-inventory/finsilabs/catalog-inventory/multi-warehouse/) | 管理多个仓库的库存，支持智能分配规则、仓间调拨和拆单履约路由。 |
| [product-bundles-kits](skills/catalog-inventory/finsilabs/catalog-inventory/product-bundles-kits/) | 通过平台应用销售商品组合或套装，支持自动扣减库存、套装定价和展示逻辑。 |
| [product-categorization](skills/catalog-inventory/finsilabs/catalog-inventory/product-categorization/) | 使用平台原生工具构建清晰的商品层级，包括集合、分类、标签和面包屑导航。 |
| [product-content-enrichment](skills/catalog-inventory/finsilabs/catalog-inventory/product-content-enrichment/) | 利用 AI 自动生成商品描述、提取属性并标注图片，大规模丰富商品目录内容。 |
| [product-data-modeling](skills/catalog-inventory/finsilabs/catalog-inventory/product-data-modeling/) | 基于平台原生数据模型组织商品目录，涵盖变体、属性、metafield 和商品关系。 |
| [variant-matrix](skills/catalog-inventory/finsilabs/catalog-inventory/variant-matrix/) | 使用平台变体工具生成并管理商品的尺码、颜色、材质等所有组合，并支持批量价格和库存管理。 |
| [vendor-management](skills/catalog-inventory/finsilabs/business-operations/vendor-management/) | 通过供应商门户管理采购订单、代发货路由、交付跟踪和供应商绩效评分。 |

### 定价、促销与会员体系

| 技能 | 说明 |
|---|---|
| [ab-testing-pricing](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/ab-testing-pricing/) | 以严谨的统计方法测试不同价格点，在跟踪转化率和利润影响的同时找出收益最大化价格。 |
| [coupon-management](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/coupon-management/) | 构建优惠券系统，支持百分比或固定金额折扣、每位顾客使用次数限制、过期时间和批量唯一券码生成。 |
| [discount-engine](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/discount-engine/) | 创建灵活的折扣系统，支持打折、减固定金额、买一送一、阶梯门槛和复杂条件规则。 |
| [dynamic-pricing](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/dynamic-pricing/) | 根据需求信号、竞品价格和库存水平自动调整价格，以提升营收并保持竞争力。 |
| [flash-sale-engine](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/flash-sale-engine/) | 运行限时促销，支持实时倒计时、单品限购、虚拟排队室和到期后自动恢复原价。 |
| [gift-cards](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/gift-cards/) | 销售和接受礼品卡，支持安全码生成、实时余额追踪、部分抵扣和有效期控制。 |
| [loyalty-points-system](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/loyalty-points-system/) | 用积分奖励复购顾客，顾客可在每次购买中累积并兑换折扣，逐步解锁更高等级权益。 |
| [price-rules-engine](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/price-rules-engine/) | 定义可叠加的价格规则，支持优先级排序、顾客分群定向、商品排除和自动组合折扣逻辑。 |
| [volume-pricing](skills/pricing-promotions-loyalty/finsilabs/pricing-promotions/volume-pricing/) | 提供按数量阶梯降价，让批发和大宗采购顾客在购物车中增加件数时自动看到更低价格。 |

### 结账、支付与税务

| 技能 | 说明 |
|---|---|
| [accounts-receivable-automation](skills/checkout-payments-tax/finsilabs/payments-checkout/accounts-receivable-automation/) | 自动化 B2B 应收账款流程，涵盖发票生成、付款跟踪、逾期催收序列和账龄分析看板。 |
| [buy-now-pay-later](skills/checkout-payments-tax/finsilabs/payments-checkout/buy-now-pay-later/) | 在结账时提供 Klarna、Afterpay 或 Affirm 分期付款，降低购买犹豫并提升客单价。 |
| [cart-logic](skills/checkout-payments-tax/finsilabs/payments-checkout/cart-logic/) | 构建稳健的购物车系统，支持新增、删除、更新、跨设备会话持久化以及登录用户购物车合并。 |
| [chargeback-management-prevention](skills/checkout-payments-tax/finsilabs/payments-checkout/chargeback-management-prevention/) | 通过欺诈评分、证据自动化、Visa CE 3.0 / Mastercom 集成和胜诉率优化来预防和管理拒付。 |
| [checkout-flow-optimization](skills/checkout-payments-tax/finsilabs/payments-checkout/checkout-flow-optimization/) | 设计高转化结账流程，包含地址自动补全、智能字段排序、进度指示和尽量少的操作阻力。 |
| [currency-hedging-management](skills/checkout-payments-tax/finsilabs/payments-checkout/currency-hedging-management/) | 管理多币种电商中的外汇风险，支持汇率追踪、对冲策略和已实现或未实现损益核算。 |
| [guest-checkout](skills/checkout-payments-tax/finsilabs/payments-checkout/guest-checkout/) | 允许顾客无需创建账号即可下单，并在购买后邀请其保存资料，以减少结账阻力并提高转化。 |
| [invoice-generation-automation](skills/checkout-payments-tax/finsilabs/payments-checkout/invoice-generation-automation/) | 自动生成专业发票，支持品牌定制、付款条款、行项目明细、税项拆分和会计系统集成。 |
| [multi-currency](skills/checkout-payments-tax/finsilabs/payments-checkout/multi-currency/) | 让国际顾客以本地货币浏览和支付，支持自动识别、实时汇率和本地化价格格式。 |
| [order-processing-pipeline](skills/checkout-payments-tax/finsilabs/payments-checkout/order-processing-pipeline/) | 实现可靠的订单状态机，在 webhook 驱动下让订单从待处理流转到支付、履约和送达。 |
| [payment-reconciliation-automation](skills/checkout-payments-tax/finsilabs/payments-checkout/payment-reconciliation-automation/) | 自动对账 Stripe、PayPal 和银行账户交易，支持异常处理、自动匹配规则和差异提醒。 |
| [payment-terms-optimization](skills/checkout-payments-tax/finsilabs/payments-checkout/payment-terms-optimization/) | 为 B2B 客户配置灵活账期，如 net-30/60/90，同时支持提前付款折扣、信用额度管理和自动催收。 |
| [payout-split-management](skills/checkout-payments-tax/finsilabs/payments-checkout/payout-split-management/) | 管理平台和市场场景下复杂的分账流程，支持商家打款、佣金计算、代扣税款和 1099 报表。 |
| [paypal-integration](skills/checkout-payments-tax/finsilabs/payments-checkout/paypal-integration/) | 使用 PayPal Commerce Platform SDK 为商店接入 PayPal、Venmo 和 Pay Later 按钮，支持一键快捷结账。 |
| [stripe-integration](skills/checkout-payments-tax/finsilabs/payments-checkout/stripe-integration/) | 基于 Stripe 构建安全支付流程，涵盖 Payment Intents、订阅计费、webhook 处理和欧洲 SCA 合规。 |
| [subscription-billing](skills/checkout-payments-tax/finsilabs/payments-checkout/subscription-billing/) | 销售循环订阅，支持自动扣费、失败付款催缴邮件、方案升级或降级按比例计费以及自助取消。 |
| [tax-calculation](skills/checkout-payments-tax/finsilabs/payments-checkout/tax-calculation/) | 使用 TaxJar 或 Avalara 在结账时准确计算销售税和增值税，并支持多州及国际税务辖区管理。 |
| [tax-compliance-automation](skills/checkout-payments-tax/finsilabs/payments-checkout/tax-compliance-automation/) | 自动化多辖区销售税、VAT 和 GST 合规流程，支持税务关联追踪、免税证明、自动申报和审计报表。 |
| [zinc-orders](skills/checkout-payments-tax/openclaw/a5huynh/universal-checkout/) | 通过 Zinc API（zinc.com）下单、列出和查询订单。适用于用户想从线上零售商购买商品、检查订单状态、查看近期订单或处理与 Zinc 电商下单 API 相关的场景。需要 `ZINC_API_KEY` 环境变量。 |

### 订单、物流与退货

| 技能 | 说明 |
|---|---|
| [dropshipping-integration](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/dropshipping-integration/) | 对接供应商 API，实现订单自动路由到代发货供应商、实时库存同步和逐单利润计算。 |
| [free-shipping-thresholds](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/free-shipping-thresholds/) | 通过展示距离免邮还差多少的进度条，鼓励顾客添加更多商品以提高订单金额。 |
| [international-shipping](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/international-shipping/) | 处理跨境订单，支持报关文件生成、关税与税费预估、HS 编码分配和受限商品拦截。 |
| [order-fulfillment-workflow](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/order-fulfillment-workflow/) | 使用数字化拣货、打包、发货流程优化仓库运营，支持条码扫描校验和自动装箱单生成。 |
| [order-management-system](skills/orders-shipping-returns/finsilabs/business-operations/order-management-system/) | 设计订单管理系统，将订单路由到合适仓库，处理拆单发货，并优雅管理缺货待发。 |
| [returns-management](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/returns-management/) | 端到端处理退货，包括生成预付费退货标签、执行退款或换货逻辑、更新库存并自动通知顾客。 |
| [returns-refund-policy](skills/orders-shipping-returns/finsilabs/business-operations/returns-refund-policy/) | 自动化退货退款流程，支持按商品类型配置退货时限、补货费和基于规则的审批逻辑。 |
| [same-day-delivery](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/same-day-delivery/) | 提供当日同城配送，支持地理区域管理、用户时段预约和配送员调度协同。 |
| [shipment-tracking](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/shipment-tracking/) | 通过聚合承运商 webhook 状态更新并主动发送配送通知，为顾客提供实时包裹追踪。 |
| [shipping-rate-calculator](skills/orders-shipping-returns/finsilabs/fulfillment-shipping/shipping-rate-calculator/) | 通过直接对接 UPS、FedEx、USPS 和 DHL 的费率 API，在结账时展示实时运费。 |

### 客服、支持与 CRM

| 技能 | 说明 |
|---|---|
| [customer-accounts](skills/customer-support-crm/finsilabs/customer-crm/customer-accounts/) | 让顾客可以注册、管理个人资料、保存多个地址，并通过平台内置账户系统查看完整订单历史。 |
| [customer-lifetime-value](skills/customer-support-crm/finsilabs/customer-crm/customer-lifetime-value/) | 计算并追踪每位顾客带来的净利润价值，再借助平台工具对高价值用户自动执行留存策略。 |
| [customer-segmentation](skills/customer-support-crm/finsilabs/customer-crm/customer-segmentation/) | 利用 Klaviyo、平台内置工具或自定义 RFM 分析，按购买行为、最近活跃度和消费水平对顾客分群。 |
| [customer-support-integration](skills/customer-support-crm/finsilabs/customer-crm/customer-support-integration/) | 将你的客服系统（Gorgias、Zendesk、Intercom）接入商店，让客服无需切换工具就能看到完整订单和顾客信息。 |
| [live-chat-commerce](skills/customer-support-crm/finsilabs/customer-crm/live-chat-commerce/) | 使用平台原生应用在前台加入实时聊天，让客服发送商品链接、回答购物车问题并促成成交。 |
| [personalization-engine](skills/customer-support-crm/finsilabs/customer-crm/personalization-engine/) | 基于浏览历史和购买模式，使用平台应用和推荐工具为每位顾客展示个性化商品推荐。 |
| [product-reviews-ratings](skills/customer-support-crm/finsilabs/customer-crm/product-reviews-ratings/) | 收集、审核并展示顾客评论与星级评分，支持聚合分数和适用于 Google 富结果的结构化数据。 |
| [referral-program](skills/customer-support-crm/finsilabs/customer-crm/referral-program/) | 通过带有唯一分享链接、阶梯奖励和内置防欺诈机制的老带新计划来扩大客户基础。 |
| [user-generated-content](skills/customer-support-crm/finsilabs/customer-crm/user-generated-content/) | 让顾客上传图片、提问和回答商品问题，并分享社会证明，以提升新访客的信任和转化。 |

### 营销与增长

| 技能 | 说明 |
|---|---|
| [affiliate-program](skills/marketing-growth/finsilabs/marketing-growth/affiliate-program/) | 使用唯一链接追踪联盟销售，管理佣金等级，自动打款，并识别虚假引荐以保护利润。 |
| [applovin-ads-integration](skills/marketing-growth/finsilabs/marketing-growth/applovin-ads-integration/) | 为移动电商应用接入 AppLovin MAX 聚合和广告投放，支持获客、再营销和应用内购买事件追踪。 |
| [cart-abandonment-recovery](skills/marketing-growth/finsilabs/marketing-growth/cart-abandonment-recovery/) | 为放弃购物车的用户设置定时邮件、短信和推送序列，用逐步增强的激励促使他们完成购买。 |
| [cart-recovery-sms](skills/marketing-growth/finsilabs/marketing-growth/cart-recovery-sms/) | 使用定向短信序列挽回弃购购物车，包含紧迫感文案、商品提醒、折扣激励和符合 TCPA 的订阅流程。 |
| [content-commerce](skills/marketing-growth/finsilabs/marketing-growth/content-commerce/) | 通过在内容文章中嵌入可购买商品卡片，把博客变成销售渠道，并追踪内容带来的营收。 |
| [conversion-rate-optimization](skills/marketing-growth/finsilabs/marketing-growth/conversion-rate-optimization/) | 通过审计结账流失、运行热力图分析并实施 CRO 最佳实践，系统提升每位访客带来的收入。 |
| [cross-sell-upsell-engine](skills/marketing-growth/finsilabs/marketing-growth/cross-sell-upsell-engine/) | 在结账页、购物车和购买后场景推荐互补或更高价商品，依据购买模式、浏览历史和利润优化。 |
| [customer-retention-engine](skills/marketing-growth/finsilabs/marketing-growth/customer-retention-engine/) | 构建针对流失风险用户的自动化留存活动，结合行为触发、个性化优惠和防流失工作流。 |
| [ecommerce-seo](skills/marketing-growth/finsilabs/marketing-growth/ecommerce-seo/) | 通过优化商品页元标签、Google Shopping 的 JSON-LD 结构化数据和自动 XML 站点地图来提升自然流量。 |
| [email-list-segmentation](skills/marketing-growth/finsilabs/marketing-growth/email-list-segmentation/) | 基于购买行为、RFM 分数、互动信号和生命周期阶段创建动态邮件分组，并自动做名单清洁与再平衡。 |
| [email-marketing-automation](skills/marketing-growth/finsilabs/marketing-growth/email-marketing-automation/) | 构建欢迎流程、购买后跟进、召回活动和浏览放弃邮件自动化，以推动重复收入。 |
| [exit-intent-popups](skills/marketing-growth/finsilabs/marketing-growth/exit-intent-popups/) | 使用针对性的退出意图弹窗捕捉即将离开的访客，展示个性化优惠、邮件收集表单，并遵循频控规则。 |
| [first-party-data-collection](skills/marketing-growth/finsilabs/marketing-growth/first-party-data-collection/) | 通过渐进式资料收集、零方数据问卷、偏好中心和测验式推荐构建第一方数据策略。 |
| [google-ads-ecommerce](skills/marketing-growth/finsilabs/marketing-growth/google-ads-ecommerce/) | 为电商构建并优化 Google Ads 广告活动，涵盖 Performance Max、购物广告 feed、转化追踪和以 ROAS 为目标的智能出价。 |
| [google-shopping-feed](skills/marketing-growth/finsilabs/marketing-growth/google-shopping-feed/) | 生成并优化 Google Merchant Center 商品 feed，确保商品以正确属性出现在 Google Shopping 广告中。 |
| [influencer-marketplace-integration](skills/marketing-growth/finsilabs/marketing-growth/influencer-marketplace-integration/) | 连接达人网络以发现创作者、管理活动 brief、跟踪交付成果，并衡量 Instagram、TikTok 和 YouTube 上的 ROI。 |
| [influencer-tracking](skills/marketing-growth/finsilabs/marketing-growth/influencer-tracking/) | 为每位创作者生成唯一 UTM 链接，归因销售，并将营收与投放成本对应，从而衡量达人活动 ROI。 |
| [lifecycle-marketing-automation](skills/marketing-growth/finsilabs/marketing-growth/lifecycle-marketing-automation/) | 以个性化消息、触发式工作流和分群活动自动化，覆盖从首次访问到忠诚用户的全生命周期阶段。 |
| [loyalty-program-optimization](skills/marketing-growth/finsilabs/marketing-growth/loyalty-program-optimization/) | 设计并优化分层会员计划，包含积分、奖励、专属权益和会员福利，以提升复购率和 CLV。 |
| [marketing-attribution-dashboard](skills/marketing-growth/finsilabs/marketing-growth/marketing-attribution-dashboard/) | 构建多触点归因看板，按渠道、活动和创意追踪营收，并提供综合 ROAS 分析和预算分配建议。 |
| [marketplace-advertising](skills/marketing-growth/finsilabs/marketing-growth/marketplace-advertising/) | 管理 Amazon、eBay 和 Walmart 等平台上的赞助商品广告，支持出价优化、关键词定向和 ACOS 追踪。 |
| [meta-ads-integration](skills/marketing-growth/finsilabs/marketing-growth/meta-ads-integration/) | 为电商配置和优化 Meta（Facebook/Instagram）广告，支持 Conversions API 服务端追踪、动态商品广告和商品目录同步。 |
| [predictive-personalization](skills/marketing-growth/finsilabs/marketing-growth/predictive-personalization/) | 使用机器学习模型预测顾客偏好，并基于行为信号提供个性化商品推荐、内容和优惠。 |
| [product-launch-campaigns](skills/marketing-growth/finsilabs/marketing-growth/product-launch-campaigns/) | 规划并执行多渠道新品发布活动，包括预热等待名单、VIP 提前访问、发布日编排和发布后持续放量。 |
| [push-notifications](skills/marketing-growth/finsilabs/marketing-growth/push-notifications/) | 发送浏览器推送通知，用于降价提醒、补货提醒和购物车提醒，无需顾客提供邮箱即可召回。 |
| [referral-viral-loops](skills/marketing-growth/finsilabs/marketing-growth/referral-viral-loops/) | 构建双边奖励的推荐裂变机制，支持唯一追踪链接、病毒系数优化和防止推荐滥用的防欺诈控制。 |
| [review-generation-engine](skills/marketing-growth/finsilabs/marketing-growth/review-generation-engine/) | 在购买后通过定时邮件和短信自动请求并收集评价，支持照片激励和虚假评论欺诈检测。 |
| [seasonal-campaign-automation](skills/marketing-growth/finsilabs/marketing-growth/seasonal-campaign-automation/) | 自动化黑五、节假日和购物节点的季节性营销活动，支持模板化工作流、倒计时序列和全年规划。 |
| [sms-marketing](skills/marketing-growth/finsilabs/marketing-growth/sms-marketing/) | 发起短信营销活动，支持订阅流程、受众分群，并满足 TCPA/GDPR 合规要求，以短信驱动营收。 |
| [social-commerce](skills/marketing-growth/finsilabs/marketing-growth/social-commerce/) | 将商品目录同步到 Instagram、TikTok 和 Facebook，启用可购物帖子和应用内结账能力。 |
| [social-proof-widgets](skills/marketing-growth/finsilabs/marketing-growth/social-proof-widgets/) | 展示实时社会证明，包括最近购买、评论数量、访客数量和已验证买家标识，以建立信任并提升转化。 |
| [tiktok-ads-integration](skills/marketing-growth/finsilabs/marketing-growth/tiktok-ads-integration/) | 为电商投放 TikTok 广告，支持 Events API 服务端追踪、Spark Ads、商品目录同步和购物广告。 |
| [tiktok-shop-integration](skills/marketing-growth/finsilabs/marketing-growth/tiktok-shop-integration/) | 将商品目录同步到 TikTok Shop，管理订单和库存，并启用直播购物和达人带货等可购物内容。 |
| [ugc-campaign-management](skills/marketing-growth/finsilabs/marketing-growth/ugc-campaign-management/) | 大规模获取、整理和展示用户生成内容，支持授权管理、品牌安全审核和增强信任的内容画廊。 |
| [video-commerce-integration](skills/marketing-growth/finsilabs/marketing-growth/video-commerce-integration/) | 启用可购物视频体验，包括直播购物、互动商品热点和直接从视频或直播内容中一键结账。 |
| [win-back-reactivation](skills/marketing-growth/finsilabs/marketing-growth/win-back-reactivation/) | 基于购买历史和沉默周期，用个性化回归优惠自动重新激活流失顾客。 |

### 数据分析与报表

| 技能 | 说明 |
|---|---|
| [ab-testing-ecommerce](skills/analytics-reporting/finsilabs/data-analytics/ab-testing-ecommerce/) | 对商品页、结账流程和定价运行受控实验，通过统计显著性检验找出转化表现最好的方案。 |
| [accounts-payable-management](skills/analytics-reporting/finsilabs/business-operations/accounts-payable-management/) | 管理供应商发票和付款流程，支持收货匹配、付款计划、提前付款折扣优化和对账工作流。 |
| [attribution-modeling](skills/analytics-reporting/finsilabs/data-analytics/attribution-modeling/) | 通过在带 UTM 的活动和渠道中实施多触点归因模型，理解哪些营销渠道真正驱动了购买。 |
| [cash-flow-forecasting](skills/analytics-reporting/finsilabs/data-analytics/cash-flow-forecasting/) | 基于历史销售模式、付款条款、季节趋势和应收款建模预测现金流，并支持情景规划和资金跑道追踪。 |
| [cost-allocation-analysis](skills/analytics-reporting/finsilabs/data-analytics/cost-allocation-analysis/) | 将销售成本、物流、营销和管理费用分摊到商品、渠道和订单上，以计算真实的单件和单单利润。 |
| [customer-analytics](skills/analytics-reporting/finsilabs/data-analytics/customer-analytics/) | 使用 RFM 评分、购买频率追踪、流失预测和队列分析来分析顾客行为并优化留存策略。 |
| [demand-forecasting](skills/analytics-reporting/finsilabs/business-operations/demand-forecasting/) | 使用历史销售数据、季节趋势和补货点预测未来库存需求，防止断货和积压。 |
| [ecommerce-budgeting-forecasting](skills/analytics-reporting/finsilabs/data-analytics/ecommerce-budgeting-forecasting/) | 为营销支出、库存采购和运营构建滚动预算，支持差异分析、情景建模和预算使用提醒。 |
| [ecommerce-data-warehouse](skills/analytics-reporting/finsilabs/data-analytics/ecommerce-data-warehouse/) | 构建电商数据仓库，包含星型模型表、ETL 流水线和适用于 BigQuery、Snowflake 或 Redshift 的 dbt 模型。 |
| [financial-analytics-dashboard](skills/analytics-reporting/finsilabs/data-analytics/financial-analytics-dashboard/) | 构建交互式财务 KPI 看板，支持自定义指标、下钻分析、差异解释和自动阈值提醒。 |
| [financial-reporting-dashboard](skills/analytics-reporting/finsilabs/data-analytics/financial-reporting-dashboard/) | 为电商构建损益表、资产负债表和现金流看板，支持按商品、渠道和时间维度下钻，用于管理层和投资人汇报。 |
| [marketing-spend-analysis](skills/analytics-reporting/finsilabs/data-analytics/marketing-spend-analysis/) | 追踪并分析所有渠道的营销花费，支持 ROAS 计算、边际收益递减分析和按平台预算重分配建议。 |
| [marketplace-fee-reconciliation](skills/analytics-reporting/finsilabs/data-analytics/marketplace-fee-reconciliation/) | 对账并分析 Amazon、eBay、Walmart 和 Etsy 的平台费用，支持净收入计算、费用分类和优化建议。 |
| [product-analytics](skills/analytics-reporting/finsilabs/data-analytics/product-analytics/) | 通过售罄率、浏览到购买转化率、滞销库存识别和分类报表来追踪商品表现。 |
| [profit-margin-analysis](skills/analytics-reporting/finsilabs/data-analytics/profit-margin-analysis/) | 按商品、分类、渠道和顾客分群分析毛利与净利，并支持成本归因、基准比较和趋势可视化。 |
| [revenue-recognition-accounting](skills/analytics-reporting/finsilabs/data-analytics/revenue-recognition-accounting/) | 针对订阅、套装和多元素组合实施 ASC 606 / IFRS 15 收入确认，支持递延收入追踪和会计分录。 |
| [sales-reporting-dashboard](skills/analytics-reporting/finsilabs/data-analytics/sales-reporting-dashboard/) | 构建高层销售看板，展示营收、客单价、转化率和队列分析，并支持按日期和渠道下钻。 |
| [unit-economics-tracking](skills/analytics-reporting/finsilabs/data-analytics/unit-economics-tracking/) | 按队列和渠道追踪获客成本、生命周期价值、回本周期和贡献利润，并附带盈利性基准和趋势分析。 |

### 平台、集成与基础设施

| 技能 | 说明 |
|---|---|
| [account-security](skills/platform-integrations-infrastructure/finsilabs/security-compliance/account-security/) | 使用暴力破解锁定、多因素认证、安全会话处理和撞库防护来保护顾客账户。 |
| [analytics-integration](skills/platform-integrations-infrastructure/finsilabs/integrations-apis/analytics-integration/) | 实施 GA4、Meta Pixel 和服务端埋点，并建立规范的数据层，以准确采集广告转化事件。 |
| [bot-protection](skills/platform-integrations-infrastructure/finsilabs/security-compliance/bot-protection/) | 使用 CAPTCHA 和行为检测阻止自动化机器人抓取目录、抢购限量库存或滥用结账流程。 |
| [commerce-api-gateway](skills/platform-integrations-infrastructure/finsilabs/headless-modern/commerce-api-gateway/) | 在单一 API 网关后聚合多个电商微服务，支持 GraphQL Federation、限流和统一认证。 |
| [commerce-js-integration](skills/platform-integrations-infrastructure/finsilabs/headless-modern/commerce-js-integration/) | 使用 Commerce.js SDK 构建轻量级无头商店，完成商品展示、购物车管理和结账，无需重型后端。 |
| [composable-commerce](skills/platform-integrations-infrastructure/finsilabs/headless-modern/composable-commerce/) | 基于 MACH 原则设计现代化商店架构，包含独立微服务、API 优先集成、云原生托管和无头前端。 |
| [data-retention-policies](skills/platform-integrations-infrastructure/finsilabs/security-compliance/data-retention-policies/) | 自动化订单和顾客数据生命周期管理，包括归档旧记录、按请求匿名化个人数据和定时清理过期数据。 |
| [database-optimization-commerce](skills/platform-integrations-infrastructure/finsilabs/infrastructure-performance/database-optimization-commerce/) | 通过合理索引、查询分析、只读副本和搜索引擎分流策略，加速缓慢的商品和订单查询。 |
| [ecommerce-caching](skills/platform-integrations-infrastructure/finsilabs/infrastructure-performance/ecommerce-caching/) | 使用分层缓存策略提升商店性能，包括 CDN 边缘缓存、Redis 应用缓存和购物车感知型失效机制。 |
| [edge-commerce](skills/platform-integrations-infrastructure/finsilabs/infrastructure-performance/edge-commerce/) | 借助 Cloudflare Workers 或 Vercel 在网络边缘运行地理路由、A/B 测试和个性化逻辑，降低全球延迟。 |
| [email-service-integration](skills/platform-integrations-infrastructure/finsilabs/integrations-apis/email-service-integration/) | 通过 SendGrid、SES 或 Postmark 发送可靠的事务邮件，例如订单确认和物流更新，并遵循可送达最佳实践。 |
| [erp-integration](skills/platform-integrations-infrastructure/finsilabs/integrations-apis/erp-integration/) | 通过中间件和异步队列，将商店与 SAP、NetSuite、Odoo 等 ERP 系统同步订单、库存和顾客数据。 |
| [financial-audit-trail](skills/platform-integrations-infrastructure/finsilabs/security-compliance/financial-audit-trail/) | 为所有财务交易建立不可篡改的审计追踪，支持用户归因、变更日志、防篡改检测和可供外部审计导出的记录。 |
| [financial-compliance-sox](skills/platform-integrations-infrastructure/finsilabs/security-compliance/financial-compliance-sox/) | 为电商实施符合 SOX 的财务控制，包含审计跟踪、职责分离、访问控制和合规交易日志。 |
| [flash-sale-scaling](skills/platform-integrations-infrastructure/finsilabs/infrastructure-performance/flash-sale-scaling/) | 为黑五和闪购活动做好扩容准备，支持自动伸缩、队列化订单处理和熔断机制，避免站点宕机。 |
| [fraud-detection](skills/platform-integrations-infrastructure/finsilabs/security-compliance/fraud-detection/) | 利用风险评分、3D Secure 挑战、频率检测和人工复核队列来防止欺诈订单。 |
| [gdpr-ecommerce](skills/platform-integrations-infrastructure/finsilabs/security-compliance/gdpr-ecommerce/) | 通过 Cookie 同意、按需导出顾客数据、删除权工作流和数据处理协议，让商店符合 GDPR。 |
| [image-optimization-cdn](skills/platform-integrations-infrastructure/finsilabs/infrastructure-performance/image-optimization-cdn/) | 通过自动缩放和转换商品图片到 WebP/AVIF、启用懒加载并通过 CDN 分发，提升商店速度。 |
| [jamstack-storefront](skills/platform-integrations-infrastructure/finsilabs/headless-modern/jamstack-storefront/) | 使用 Next.js 或 Astro 构建极速前台，将商品页预渲染为静态 HTML，并从电商 API 获取实时数据。 |
| [load-testing-commerce](skills/platform-integrations-infrastructure/finsilabs/infrastructure-performance/load-testing-commerce/) | 使用 k6 或 Artillery 在上线前模拟真实购物流量，找出结账和商品页的性能瓶颈。 |
| [magento-graphql](skills/platform-integrations-infrastructure/finsilabs/platform-magento/magento-graphql/) | 调用 Magento 的 GraphQL API 构建无头前台或 PWA Studio 前端，覆盖商品、购物车、结账和顾客操作。 |
| [magento-indexing-caching](skills/platform-integrations-infrastructure/finsilabs/platform-magento/magento-indexing-caching/) | 通过正确管理索引器、配置 Varnish 全页缓存和使用 Redis 做会话与对象缓存来加速 Magento。 |
| [magento-module-development](skills/platform-integrations-infrastructure/finsilabs/platform-magento/magento-module-development/) | 使用依赖注入、插件、观察者和服务契约开发自定义 Magento 2 模块，以干净地扩展核心能力。 |
| [magento-multi-store](skills/platform-integrations-infrastructure/finsilabs/platform-magento/magento-multi-store/) | 在 Magento 中配置多个网站和店铺视图，支持共享或独立目录、不同 URL 结构和店铺级设置。 |
| [marketplace-building](skills/platform-integrations-infrastructure/finsilabs/business-operations/marketplace-building/) | 构建多商家市场平台，支持卖家入驻、佣金规则、通过 Stripe Connect 自动打款和卖家后台。 |
| [marketplace-connectors](skills/platform-integrations-infrastructure/finsilabs/integrations-apis/marketplace-connectors/) | 在 Amazon、eBay 和 Walmart 上刊登商品，支持双向库存同步、自动创建刊登和订单导入商店。 |
| [medusa-development](skills/platform-integrations-infrastructure/finsilabs/headless-modern/medusa-development/) | 扩展开源 Medusa 电商平台，添加自定义服务、事件订阅器和 API 端点以满足独特业务需求。 |
| [monitoring-alerting-commerce](skills/platform-integrations-infrastructure/finsilabs/infrastructure-performance/monitoring-alerting-commerce/) | 使用看板实时追踪商店健康度，包括结账成功率、支付失败、购物车错误和自定义 SLO 告警。 |
| [multi-channel-selling](skills/platform-integrations-infrastructure/finsilabs/business-operations/multi-channel-selling/) | 在自有站点、Amazon、eBay 和批发渠道之间同步商品目录与库存，实现一套系统全渠道销售。 |
| [pci-dss-compliance](skills/platform-integrations-infrastructure/finsilabs/security-compliance/pci-dss-compliance/) | 通过正确划定环境范围、选择合适 SAQ 并实施必要控制，满足 PCI-DSS 支付安全要求。 |
| [pos-integration](skills/platform-integrations-infrastructure/finsilabs/integrations-apis/pos-integration/) | 将线下 POS 系统与线上商店打通，实现统一库存、共享顾客档案和全渠道订单管理。 |
| [product-information-management](skills/platform-integrations-infrastructure/finsilabs/integrations-apis/product-information-management/) | 将商品数据集中到 Akeneo 或 Salsify 等 PIM 系统，并自动将增强后的内容分发到所有销售渠道。 |
| [pwa-storefront](skills/platform-integrations-infrastructure/finsilabs/headless-modern/pwa-storefront/) | 把商店做成可安装的渐进式 Web App，支持离线浏览商品、推送通知和移动端主屏入口。 |
| [saleor-development](skills/platform-integrations-infrastructure/finsilabs/headless-modern/saleor-development/) | 构建并扩展基于 GraphQL 的 Saleor 无头电商平台，支持自定义应用、webhook 处理器和后台 UI 定制。 |
| [secure-checkout](skills/platform-integrations-infrastructure/finsilabs/security-compliance/secure-checkout/) | 通过强制 HTTPS、内容安全策略头、输入清洗和银行卡数据令牌化，强化结账安全。 |
| [sfcc-business-manager](skills/platform-integrations-infrastructure/finsilabs/platform-salesforce-cc/sfcc-business-manager/) | 通过 Business Manager 配置 Salesforce Commerce Cloud，管理目录、促销、站点偏好并运行 XML 导入导出任务。 |
| [sfcc-cartridge-development](skills/platform-integrations-infrastructure/finsilabs/platform-salesforce-cc/sfcc-cartridge-development/) | 构建基于 SFRA 的 Salesforce Commerce Cloud cartridge，使用控制器、ISML 模板和 hooks 定制前台行为。 |
| [sfcc-ocapi-scapi](skills/platform-integrations-infrastructure/finsilabs/platform-salesforce-cc/sfcc-ocapi-scapi/) | 集成 Salesforce Commerce Cloud 的无头 API（OCAPI 和 Shopper APIs），构建自定义前台和移动电商体验。 |
| [shopify-admin-api](skills/platform-integrations-infrastructure/finsilabs/platform-shopify/shopify-admin-api/) | 使用支持批量操作的 GraphQL Admin API 自动化 Shopify 店铺运营，包括商品、订单、库存和顾客。 |
| [shopify-app-development](skills/platform-integrations-infrastructure/finsilabs/platform-shopify/shopify-app-development/) | 使用 Remix、App Bridge、Polaris 组件和 OAuth 流程构建嵌入式 Shopify 应用。 |
| [shopify-checkout-extensions](skills/platform-integrations-infrastructure/finsilabs/platform-shopify/shopify-checkout-extensions/) | 使用 UI Extensions 自定义 Shopify 结账页的加购推荐和自定义字段，并用 Shopify Functions 编写无服务器折扣和运费逻辑。 |
| [shopify-hydrogen](skills/platform-integrations-infrastructure/finsilabs/headless-modern/shopify-hydrogen/) | 使用 Hydrogen React 框架和 Remix 路由构建定制 Shopify 前台，并部署到 Shopify Oxygen 边缘托管。 |
| [shopify-metafields](skills/platform-integrations-infrastructure/finsilabs/platform-shopify/shopify-metafields/) | 在 Shopify 任意资源上存储自定义数据，如商品、订单和顾客，使用类型化 metafield 定义，并可从 Liquid 和 Storefront API 访问。 |
| [shopify-storefront-api](skills/platform-integrations-infrastructure/finsilabs/platform-shopify/shopify-storefront-api/) | 使用 GraphQL Storefront API 和 Buy SDK 构建无头 Shopify 前端，覆盖商品查询、购物车管理和结账。 |
| [shopify-theme-development](skills/platform-integrations-infrastructure/finsilabs/platform-shopify/shopify-theme-development/) | 使用 Liquid 模板、JSON sections、动态 blocks 和主题应用扩展来构建和定制 Shopify 主题。 |
| [shopify-webhooks](skills/platform-integrations-infrastructure/finsilabs/platform-shopify/shopify-webhooks/) | 注册、校验并可靠处理 Shopify 的订单、库存和顾客 webhook 事件，支持 HMAC 校验和幂等处理。 |
| [webhook-architecture](skills/platform-integrations-infrastructure/finsilabs/integrations-apis/webhook-architecture/) | 构建可靠的事件投递系统，包含自动重试、HMAC 签名校验和死信队列，确保 webhook 不会丢失。 |
| [woocommerce-blocks](skills/platform-integrations-infrastructure/finsilabs/platform-woocommerce/woocommerce-blocks/) | 使用 Gutenberg blocks、服务端渲染、slot fills 和扩展 hooks 自定义 WooCommerce 购物车与结账页面。 |
| [woocommerce-performance](skills/platform-integrations-infrastructure/finsilabs/platform-woocommerce/woocommerce-performance/) | 通过优化数据库查询、清理 transients、启用 Redis 对象缓存和配置页面缓存来修复 WooCommerce 性能问题。 |
| [woocommerce-plugin-development](skills/platform-integrations-infrastructure/finsilabs/platform-woocommerce/woocommerce-plugin-development/) | 使用 action/filter hooks、Settings API 和 REST API 扩展来创建自定义 WooCommerce 插件，而无需修改核心。 |
| [woocommerce-rest-api](skills/platform-integrations-infrastructure/finsilabs/platform-woocommerce/woocommerce-rest-api/) | 使用 WooCommerce REST API 和密钥认证来集成或构建无头前端，支持商品、订单、顾客和优惠券操作。 |
| [woocommerce-subscriptions](skills/platform-integrations-infrastructure/finsilabs/platform-woocommerce/woocommerce-subscriptions/) | 为 WooCommerce 添加订阅商品，支持自动循环扣费、续费通知和订阅者自助管理。 |

路径中保留了来源归属信息。例如，一个 Shopify 技能会位于类似 `skills/platform-integrations-infrastructure/finsilabs/platform-shopify/...` 的分类路径下。

## 署名说明

如果你分发或二次改编这些导入的技能，请保留原始上游项目的版权和许可证声明。
