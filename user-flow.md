# 电商用户消费交互流程

1. 浏览商品：用户进入电商网站或者 App，浏览产品。我们目前关注的是关键字搜索和类似产品推荐；
2. 商品详情：用户点击搜索结果或者类似产品推荐，进入商品详情页；详情页影响用户购买的因素有：商品价格、商品图片、商品描述、商品评价、商品促销活动等；
3. 售前询问客户服务：如果用户对商品有疑问，会点击咨询客服，询问商品的相关信息；
4. 加入购物车：如果用户对商品感兴趣，可以点击加入购物车，也可以直接点击购买；
5. 购买：用户点击购买，进入购买流程，包括选择收货地址、选择支付方式、选择配送方式等。

假设：

1. Shopee ID 用户以手机为主要设备，使用 Shopee App 浏览商品，购买商品；(Shopee 卖家后台应该可以提供这个数据，但是没有找到)

问题:

1. 用我们目前购买的关键字 (Kotak Makan) 搜索，列表页没有展示我们的产品，尝试多次都没有。加上 STARLEAD (STARLEAD Kotak Makan) 搜索，也没有我们的产品展示 (不知道是不是因为我是中国的 IP 地址。用美国的 IP 地址搜索也没有我们的产品展示）。初步确认跟 Average Ranking (Home > Shopee Ads > Product Search Ad Details) 有关，rank 太低的在搜索也不展示。
2. https://seller.shopee.co.id/datacenter/dashboard, Visitors, Page Views 总是在 1:2 左右，这个 Page Views 的比例很稳定，并且 Page Views 比例偏高（对比 Shopee 提供的教程里面附带的数据），流量来源令人怀疑。
3. https://seller.shopee.co.id/datacenter/products/analysis/overview, 同样对比 Shopee 教程附带的数据，Product Bounce Rate (41.99%) 偏低，附带教程里面的数据 60% 左右。
4. 订单量提升方法，降价和测试，每个单品都需要确定一个对标竞品（同质性最高，销量最高的）。商品定价和测评单的关系。测评成本和商品定价的平衡关系。我们的定价和竞争对手的定价关系。需要做多少单可以对比竞争对手的量。