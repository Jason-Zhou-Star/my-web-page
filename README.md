```html
<!DOCTYPE html>
<html>
<head>
<style>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 20px;
    background: #f8f9fa;
    line-height: 1.6;
    color: #2c3e50;
}

.slide {
    background: white;
    border-radius: 12px;
    padding: 40px;
    margin-bottom: 40px;
    box-shadow: 0 8px 30px rgba(0,0,0,0.05);
}

.cover {
    background: linear-gradient(135deg, #1a237e 0%, #0d47a1 100%);
    color: white;
    padding: 60px 40px;
    text-align: center;
}

.title {
    font-size: 28px;
    color: #1a237e;
    margin-bottom: 30px;
    padding-bottom: 15px;
    border-bottom: 3px solid #1a237e;
    font-weight: 600;
}

.cover .title {
    color: white;
    border: none;
    font-size: 36px;
    margin-bottom: 40px;
}

.data-box {
    background: #f8f9fa;
    border-left: 4px solid #1a237e;
    padding: 25px;
    margin: 15px 0;
    border-radius: 0 8px 8px 0;
}

.highlight {
    color: #0d47a1;
    font-weight: bold;
}

.flex-container {
    display: flex;
    justify-content: space-between;
    margin: 20px 0;
    gap: 30px;
    flex-wrap: wrap;
}

.flex-item {
    flex: 1;
    min-width: 300px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    padding: 25px;
}

.source-link {
    color: #1a73e8;
    text-decoration: none;
    font-size: 0.8em;
    transition: color 0.3s;
}

.source-link:hover {
    color: #0d47a1;
    text-decoration: underline;
}

.year-tag {
    display: inline-block;
    padding: 3px 8px;
    background: #e8eaf6;
    color: #1a237e;
    border-radius: 4px;
    font-size: 0.9em;
    margin-right: 10px;
}

.trend-table {
    width: 100%;
    border-collapse: collapse;
    margin: 15px 0;
}

.trend-table th {
    padding: 12px;
    background: #f8f9fa;
    color: #1a237e;
    text-align: left;
    font-weight: 500;
}

.trend-table td {
    padding: 12px;
    border-bottom: 1px solid #e0e0e0;
}

.trend-table tr:hover {
    background: #f8f9fa;
}

.terms-drawer {
    position: fixed;
    bottom: 0;
    right: 20px;
    width: 300px;
    background: white;
    border-radius: 8px 8px 0 0;
    box-shadow: 0 -2px 10px rgba(0,0,0,0.1);
    transform: translateY(calc(100% - 40px));
    transition: transform 0.3s;
    z-index: 1000;
}

.terms-drawer:hover {
    transform: translateY(0);
}

.terms-header {
    padding: 10px 20px;
    background: #1a237e;
    color: white;
    border-radius: 8px 8px 0 0;
    cursor: pointer;
}

.terms-content {
    padding: 20px;
}

.pending {
    color: #666;
    font-style: italic;
}
</style>
</head>
<body>

<div class="slide cover">
    <div class="title">韩日跨境电商市场深度分析报告</div>
    <h2 style="font-weight: 400; margin-bottom: 40px;">Market Analysis Report: South Korea & Japan Cross-border E-commerce</h2>
    <div style="margin-top: 60px;">
        <p>汇报人：海外电商业务部</p>
        <p>报告时间：2024年10月</p>
        <p style="font-size: 0.9em; margin-top: 20px;">基于已发布官方数据分析</p>
    </div>
</div>

<div class="slide">
    <div class="title">宏观经济概况</div>
    <div class="flex-container">
        <div class="flex-item">
            <h3 style="color: #1a237e;">韩国经济指标</h3>
            <div class="data-box">
  
                <p><span class="year-tag">2023年GDP</span><span class="highlight">1.71万亿美元</span></p>
                <p><span class="year-tag">人均GDP</span><span class="highlight">33,107美元</span></p>
                <p><span class="year-tag">GDP增长率</span><span class="highlight">1.4%</span></p>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.imf.org/en/Countries/KOR" target="_blank" class="source-link">数据来源：IMF, 2024</a>
                </div>
            </div>
            <div style="margin-top: 25px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">历史数据趋势</h4>
                <table class="trend-table">
                    <tr>
                        <th>年份</th>
                        <th>GDP规模</th>
                        <th>增长率</th>
                    </tr>
                    
                    <tr>
                        <td>2023</td>
                        <td>1.71万亿美元</td>
                        <td>+1.4%</td>
                    </tr>
                    <tr>
                        <td>2022</td>
                        <td>1.67万亿美元</td>
                        <td>+2.6%</td>
                    </tr>
                    <tr>
                        <td>2021</td>
                        <td>1.64万亿美元</td>
                        <td>+4.1%</td>
                    </tr>
                    <tr>
                        <td>2020</td>
                        <td>1.63万亿美元</td>
                        <td>-0.7%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.bok.or.kr/eng/main/main.do" target="_blank" class="source-link">数据来源：Bank of Korea</a>
                </div>
            </div>
        </div>
<div class="flex-item">
            <h3 style="color: #1a237e;">日本经济指标</h3>
            <div class="data-box">
                
                <p><span class="year-tag">2023年GDP</span><span class="highlight">4.23万亿美元</span></p>
                <p><span class="year-tag">人均GDP</span><span class="highlight">33,950美元</span></p>
                <p><span class="year-tag">GDP增长率</span><span class="highlight">1.9%</span></p>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.imf.org/en/Countries/JPN" target="_blank" class="source-link">数据来源：IMF, 2024</a>
                </div>
            </div>
            <div style="margin-top: 25px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">历史数据趋势</h4>
                <table class="trend-table">
                    <tr>
                        <th>年份</th>
                        <th>GDP规模</th>
                        <th>增长率</th>
                    </tr>
                    
                    <tr>
                        <td>2023</td>
                        <td>4.23万亿美元</td>
                        <td>+1.9%</td>
                    </tr>
                    <tr>
                        <td>2022</td>
                        <td>4.15万亿美元</td>
                        <td>+1.0%</td>
                    </tr>
                    <tr>
                        <td>2021</td>
                        <td>4.94万亿美元</td>
                        <td>+2.2%</td>
                    </tr>
                    <tr>
                        <td>2020</td>
                        <td>5.05万亿美元</td>
                        <td>-4.5%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.boj.or.jp/en/statistics" target="_blank" class="source-link">数据来源：Bank of Japan</a>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="slide">
    <div class="title">电商市场规模分析</div>
    <div class="flex-container">
        <div class="flex-item">
            <h3 style="color: #1a237e;">韩国电商市场</h3>
            <div class="data-box">
                
                <p><span class="year-tag">2023年总规模</span><span class="highlight">2,010亿美元</span></p>
                <p><span class="year-tag">电商渗透率</span><span class="highlight">35.9%</span></p>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.kostat.go.kr/portal/eng" target="_blank" class="source-link">数据来源：Statistics Korea, 2024</a>
                </div>
            </div>
            <div style="margin-top: 25px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">五年增长趋势</h4>
                <table class="trend-table">
                    <tr>
                        <th>年份</th>
                        <th>市场规模</th>
                        <th>同比增长</th>
                    </tr>
                   
                    <tr>
                        <td>2023</td>
                        <td>2,010亿美元</td>
                        <td>+15.2%</td>
                    </tr>
                    <tr>
                        <td>2022</td>
                        <td>1,745亿美元</td>
                        <td>+12.8%</td>
                    </tr>
                    <tr>
                        <td>2021</td>
                        <td>1,546亿美元</td>
                        <td>+17.5%</td>
                    </tr>
                    <tr>
                        <td>2020</td>
                        <td>1,316亿美元</td>
                        <td>+21.3%</td>
                    </tr>
                    <tr>
                        <td>2019</td>
                        <td>1,085亿美元</td>
                        <td>+14.2%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.kostat.go.kr/portal/eng" target="_blank" class="source-link">数据来源：Statistics Korea, Online Shopping Trends</a>
                </div>
            </div>
        </div>
        <div class="flex-item">
            <h3 style="color: #1a237e;">日本电商市场</h3>
            <div class="data-box">
                
                <p><span class="year-tag">2023年总规模</span><span class="highlight">2,386亿美元</span></p>
                <p><span class="year-tag">电商渗透率</span><span class="highlight">15.2%</span></p>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.meti.go.jp/english/statistics" target="_blank" class="source-link">数据来源：METI Japan, 2024</a>
                </div>
            </div>
            <div style="margin-top: 25px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">五年增长趋势</h4>
                <table class="trend-table">
                    <tr>
                        <th>年份</th>
                        <th>市场规模</th>
                        <th>同比增长</th>
                    </tr>
                 
                    <tr>
                        <td>2023</td>
                        <td>2,386亿美元</td>
                        <td>+7.8%</td>
                    </tr>
                    <tr>
                        <td>2022</td>
                        <td>2,213亿美元</td>
                        <td>+6.5%</td>
                    </tr>
                    <tr>
                        <td>2021</td>
                        <td>2,078亿美元</td>
                        <td>+9.2%</td>
                    </tr>
                    <tr>
                        <td>2020</td>
                        <td>1,903亿美元</td>
                        <td>+11.5%</td>
                    </tr>
                    <tr>
                        <td>2019</td>
                        <td>1,707亿美元</td>
                        <td>+6.8%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.meti.go.jp/english/statistics" target="_blank" class="source-link">数据来源：METI Japan, E-Commerce Market Survey</a>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="slide">
    <div class="title">主要电商平台份额分析</div>
    <div class="flex-container">
        <div class="flex-item">
            <h3 style="color: #1a237e;">韩国主要平台</h3>
            <div class="data-box">
               
                <div style="margin-top: 20px;">
                    <table class="trend-table">
                        <tr>
                            <th>平台</th>
                            <th>2023年</th>
                            <th>2022年</th>
                            <th>2021年</th>
                        </tr>
                        <tr>
                            <td>Coupang</td>
                            <td>41.5%</td>
                            <td>37.8%</td>
                            <td>33.2%</td>
                        </tr>
                        <tr>
                            <td>Naver Shopping</td>
                            <td>18.8%</td>
                            <td>17.5%</td>
                            <td>15.8%</td>
                        </tr>
                        <tr>
                            <td>Gmarket</td>
                            <td>13.8%</td>
                            <td>15.2%</td>
                            <td>16.5%</td>
                        </tr>
                        <tr>
                            <td>11Street</td>
                            <td>10.2%</td>
                            <td>11.5%</td>
                            <td>12.8%</td>
                        </tr>
                    </table>
                    <div style="text-align: right; margin-top: 10px;">
                        <a href="https://www.koreanclick.com/insights" target="_blank" class="source-link">数据来源：Korean Click, 2024</a>
                    </div>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">Coupang平台数据</span></p>
                <table class="trend-table">
                    <tr>
                        <td>入驻保证金</td>
                        <td class="pending">待查证</td>
                    </tr>
                    <tr>
                        <td>月服务费</td>
                        <td class="pending">待查证</td>
                    </tr>
                    <tr>
                        <td>佣金比例</td>
                        <td>10-15%</td>
                    </tr>
                    <tr>
                        <td>审核周期</td>
                        <td class="pending">待查证</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://partners.coupang.com" target="_blank" class="source-link">数据来源：Coupang Partner Portal</a>
                </div>
            </div>
        </div>
        <div class="flex-item">
            <h3 style="color: #1a237e;">日本主要平台</h3>
            <div class="data-box">
                
                <div style="margin-top: 20px;">
                    <table class="trend-table">
                        <tr>
                            <th>平台</th>
                            <th>2023年</th>
                            <th>2022年</th>
                            <th>2021年</th>
                        </tr>
                        <tr>
                            <td>Amazon Japan</td>
                            <td>27.8%</td>
                            <td>26.2%</td>
                            <td>24.5%</td>
                        </tr>
                        <tr>
                            <td>Rakuten</td>
                            <td>28.2%</td>
                            <td>29.5%</td>
                            <td>30.2%</td>
                        </tr>
                        <tr>
                            <td>Yahoo! Shopping</td>
                            <td>9.5%</td>
                            <td>10.2%</td>
                            <td>11.5%</td>
                        </tr>
                        <tr>
                            <td>PayPay Mall</td>
                            <td>6.8%</td>
                            <td>5.5%</td>
                            <td>4.2%</td>
                        </tr>
                    </table>
                    <div style="text-align: right; margin-top: 10px;">
                        <a href="https://www.digitalcommerce.jp" target="_blank" class="source-link">数据来源：DCAJ, 2024</a>
                    </div>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">Amazon Japan平台数据</span></p>
                <table class="trend-table">
                    <tr>
                        <td>入驻保证金</td>
                        <td>0美元</td>
                    </tr>
                    <tr>
                        <td>月服务费</td>
                        <td>39.99美元</td>
                    </tr>
                    <tr>
                        <td>佣金比例</td>
                        <td>8-15%</td>
                    </tr>
                    <tr>
                        <td>审核周期</td>
                        <td>10个工作日</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://services.amazon.co.jp" target="_blank" class="source-link">数据来源：Amazon JP Seller Central</a>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="slide">
    <div class="title">老年用品市场竞争格局</div>
    <div class="flex-container">
        <div class="flex-item">
            <h3 style="color: #1a237e;">韩国老年市场</h3>
            <div class="data-box">
                
                <p><span class="year-tag">2023年市场规模</span><span class="highlight">285亿美元</span></p>
                <p><span class="year-tag">老龄化率</span><span class="highlight">17.5%</span></p>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.khidi.or.kr/eps" target="_blank" class="source-link">数据来源：KHIDI Research, 2024</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">市场规模趋势</h4>
                <table class="trend-table">
                    <tr>
                        <th>年份</th>
                        <th>市场规模</th>
                        <th>增长率</th>
                    </tr>
                    <tr>
                        <td>2023</td>
                        <td>285亿美元</td>
                        <td>+15.2%</td>
                    </tr>
                    <tr>
                        <td>2022</td>
                        <td>247亿美元</td>
                        <td>+13.8%</td>
                    </tr>
                    <tr>
                        <td>2021</td>
                        <td>217亿美元</td>
                        <td>+12.5%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.khidi.or.kr/eps" target="_blank" class="source-link">数据来源：KHIDI Market Report</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">主要品牌市场份额</h4>
                <table class="trend-table">
                    <tr>
                        <th>品牌</th>
                        <th>2023年份额</th>
                        <th>主要品类</th>
                    </tr>
                    <tr>
                        <td>Bodyfriend</td>
                        <td>15.3%</td>
                        <td>康复器械</td>
                    </tr>
                    <tr>
                        <td>Ceragem</td>
                        <td>12.8%</td>
                        <td>保健器材</td>
                    </tr>
                    <tr>
                        <td>Kowa</td>
                        <td>8.5%</td>
                        <td>护理用品</td>
                    </tr>
                    <tr>
                        <td>其他品牌</td>
                        <td>63.4%</td>
                        <td>-</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.khidi.or.kr/eps" target="_blank" class="source-link">数据来源：KHIDI Brand Analysis</a>
                </div>
            </div>
        </div>
        <div class="flex-item">
            <h3 style="color: #1a237e;">日本老年市场</h3>
            <div class="data-box">
                
                <p><span class="year-tag">2023年市场规模</span><span class="highlight">412亿美元</span></p>
                <p><span class="year-tag">老龄化率</span><span class="highlight">29.1%</span></p>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.mhlw.go.jp/english/" target="_blank" class="source-link">数据来源：MHLW Japan, 2024</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">市场规模趋势</h4>
                <table class="trend-table">
                    <tr>
                        <th>年份</th>
                        <th>市场规模</th>
                        <th>增长率</th>
                    </tr>
                    <tr>
                        <td>2023</td>
                        <td>412亿美元</td>
                        <td>+8.5%</td>
                    </tr>
                    <tr>
                        <td>2022</td>
                        <td>380亿美元</td>
                        <td>+7.8%</td>
                    </tr>
                    <tr>
                        <td>2021</td>
                        <td>352亿美元</td>
                        <td>+7.2%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.mhlw.go.jp/english/" target="_blank" class="source-link">数据来源：MHLW Market Analysis</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <h4 style="color: #1a237e; margin-bottom: 15px;">主要品牌市场份额</h4>
                <table class="trend-table">
                    <tr>
                        <th>品牌</th>
                        <th>2023年份额</th>
                        <th>主要品类</th>
                    </tr>
                    <tr>
                        <td>Paramount Bed</td>
                        <td>18.5%</td>
                        <td>护理床品</td>
                    </tr>
                    <tr>
                        <td>Panasonic</td>
                        <td>15.2%</td>
                        <td>电子护理</td>
                    </tr>
                    <tr>
                        <td>France Bed</td>
                        <td>12.3%</td>
                        <td>康复器械</td>
                    </tr>
                    <tr>
                        <td>其他品牌</td>
                        <td>54.0%</td>
                        <td>-</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.mhlw.go.jp/english/" target="_blank" class="source-link">数据来源：MHLW Brand Analysis</a>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="slide">
    <div class="title">市场风险评估</div>
    <div class="flex-container">
        <div class="flex-item">
            <h3 style="color: #1a237e;">韩国市场风险指标</h3>
            <div class="data-box">
                <p><span class="year-tag">汇率风险</span></p>
                <table class="trend-table">
                    <tr>
                        <th>指标</th>
                        <th>2023年数据</th>
                        <th>来源</th>
                    </tr>
                    <tr>
                        <td>韩元汇率波动率</td>
                        <td>±5.2%</td>
                        <td>Bank of Korea</td>
                    </tr>
                    <tr>
                        <td>对美元汇率区间</td>
                        <td>1,250-1,350</td>
                        <td>Bank of Korea</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.bok.or.kr/eng/main/main.do" target="_blank" class="source-link">数据来源：Bank of Korea, 2023年报</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">跨境电商运营数据</span></p>
                <table class="trend-table">
                    <tr>
                        <th>指标</th>
                        <th>2023年数据</th>
                    </tr>
                    <tr>
                        <td>物流延误率</td>
                        <td>2.8%</td>
                    </tr>
                    <tr>
                        <td>跨境订单退货率</td>
                        <td>3.5%</td>
                    </tr>
                    <tr>
                        <td>消费者投诉率</td>
                        <td>0.8%</td>
                    </tr>
                    <tr>
                        <td>平均配送时间</td>
                        <td>3.2天</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.kostat.go.kr/portal/eng" target="_blank" class="source-link">数据来源：Korea Customs Service</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">政策合规要求</span></p>
                <table class="trend-table">
                    <tr>
                        <th>合规项目</th>
                        <th>具体要求</th>
                    </tr>
                    <tr>
                        <td>电商平台责任险</td>
                        <td>必须购买</td>
                    </tr>
                    <tr>
                        <td>消费者信息保护</td>
                        <td>需本地化存储</td>
                    </tr>
                    <tr>
                        <td>商品标签要求</td>
                        <td>韩文标签必选</td>
                    </tr>
                    <tr>
                        <td>售后服务时间</td>
                        <td>9:00-18:00必须</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.kca.go.kr/eng/" target="_blank" class="source-link">数据来源：Korea Consumer Agency</a>
                </div>
            </div>
        </div>
        <div class="flex-item">
            <h3 style="color: #1a237e;">日本市场风险指标</h3>
            <div class="data-box">
                <p><span class="year-tag">汇率风险</span></p>
                <table class="trend-table">
                    <tr>
                        <th>指标</th>
                        <th>2023年数据</th>
                        <th>来源</th>
                    </tr>
                    <tr>
                        <td>日元汇率波动率</td>
                        <td>±3.8%</td>
                        <td>Bank of Japan</td>
                    </tr>
                    <tr>
                        <td>对美元汇率区间</td>
                        <td>130-150</td>
                        <td>Bank of Japan</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.boj.or.jp/en/statistics" target="_blank" class="source-link">数据来源：Bank of Japan, 2023年报</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">跨境电商运营数据</span></p>
                <table class="trend-table">
                    <tr>
                        <th>指标</th>
                        <th>2023年数据</th>
                    </tr>
                    <tr>
                        <td>物流延误率</td>
                        <td>2.1%</td>
                    </tr>
                    <tr>
                        <td>跨境订单退货率</td>
                        <td>2.3%</td>
                    </tr>
                    <tr>
                        <td>消费者投诉率</td>
                        <td>0.5%</td>
                    </tr>
                    <tr>
                        <td>平均配送时间</td>
                        <td>4.5天</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.customs.go.jp/english/" target="_blank" class="source-link">数据来源：Japan Customs</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">政策合规要求</span></p>
                <table class="trend-table">
                    <tr>
                        <th>合规项目</th>
                        <th>具体要求</th>
                    </tr>
                    <tr>
                        <td>产品责任险</td>
                        <td>建议购买</td>
                    </tr>
                    <tr>
                        <td>消费者信息保护</td>
                        <td>符合APPI法案</td>
                    </tr>
                    <tr>
                        <td>商品标签要求</td>
                        <td>日文标签必选</td>
                    </tr>
                    <tr>
                        <td>售后服务时间</td>
                        <td>10:00-19:00必须</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.caa.go.jp/en/" target="_blank" class="source-link">数据来源：Consumer Affairs Agency, Japan</a>
                </div>
            </div>
        </div>
    </div>
</div>
<div class="slide">
    <div class="title">市场发展建议</div>
    <div class="flex-container">
        <div class="flex-item">
            <h3 style="color: #1a237e;">韩国市场策略建议</h3>
            <div class="data-box">
                <p><span class="year-tag">平台选择依据</span></p>
                <table class="trend-table">
                    <tr>
                        <th>平台</th>
                        <th>优势</th>
                        <th>特点</th>
                    </tr>
                    <tr>
                        <td>Coupang</td>
                        <td>市场份额41.5%</td>
                        <td>自建物流体系</td>
                    </tr>
                    <tr>
                        <td>Naver Shopping</td>
                        <td>流量优势</td>
                        <td>本土用户信任度高</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.koreanclick.com/insights" target="_blank" class="source-link">数据来源：Korean Click</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">品类机会分析</span></p>
                <table class="trend-table">
                    <tr>
                        <th>品类</th>
                        <th>市场规模</th>
                        <th>增长率</th>
                    </tr>
                    <tr>
                        <td>康复辅具</td>
                        <td>92.6亿美元</td>
                        <td>+15.3%</td>
                    </tr>
                    <tr>
                        <td>护理用品</td>
                        <td>80.7亿美元</td>
                        <td>+13.8%</td>
                    </tr>
                    <tr>
                        <td>保健器械</td>
                        <td>70.1亿美元</td>
                        <td>+12.5%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.khidi.or.kr/eps" target="_blank" class="source-link">数据来源：KHIDI Market Report</a>
                </div>
            </div>
        </div>
        <div class="flex-item">
            <h3 style="color: #1a237e;">日本市场策略建议</h3>
            <div class="data-box">
                <p><span class="year-tag">平台选择依据</span></p>
                <table class="trend-table">
                    <tr>
                        <th>平台</th>
                        <th>优势</th>
                        <th>特点</th>
                    </tr>
                    <tr>
                        <td>Amazon Japan</td>
                        <td>市场份额27.8%</td>
                        <td>FBA物流支持</td>
                    </tr>
                    <tr>
                        <td>Rakuten</td>
                        <td>本土最大</td>
                        <td>用户忠诚度高</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.digitalcommerce.jp" target="_blank" class="source-link">数据来源：DCAJ</a>
                </div>
            </div>
            <div class="data-box" style="margin-top: 20px;">
                <p><span class="year-tag">品类机会分析</span></p>
                <table class="trend-table">
                    <tr>
                        <th>品类</th>
                        <th>市场规模</th>
                        <th>增长率</th>
                    </tr>
                    <tr>
                        <td>护理用品</td>
                        <td>145亿美元</td>
                        <td>+8.5%</td>
                    </tr>
                    <tr>
                        <td>康复辅具</td>
                        <td>124亿美元</td>
                        <td>+7.8%</td>
                    </tr>
                    <tr>
                        <td>保健器械</td>
                        <td>94亿美元</td>
                        <td>+7.2%</td>
                    </tr>
                </table>
                <div style="text-align: right; margin-top: 10px;">
                    <a href="https://www.mhlw.go.jp/english/" target="_blank" class="source-link">数据来源：MHLW Market Analysis</a>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- 关键指标说明 -->
<div class="slide">
    <div class="title">关键指标说明</div>
    <div class="data-box">
        <table class="trend-table">
            <tr>
                <th>指标类别</th>
                <th>指标名称</th>
                <th>说明</th>
            </tr>
            <tr>
                <td>市场规模</td>
                <td>电商渗透率</td>
                <td>电商交易额占社会零售总额的比例</td>
            </tr>
            <tr>
                <td>市场规模</td>
                <td>市场份额</td>
                <td>企业/平台销售额占该市场总销售额的比例</td>
            </tr>
            <tr>
                <td>运营指标</td>
                <td>物流延误率</td>
                <td>未按承诺时间送达的订单占比</td>
            </tr>
            <tr>
                <td>运营指标</td>
                <td>退货率</td>
                <td>退货订单数量占总订单的比例</td>
            </tr>
            <tr>
                <td>运营指标</td>
                <td>客诉率</td>
                <td>投诉订单数量占总订单的比例</td>
            </tr>
            <tr>
                <td>财务指标</td>
                <td>汇率波动率</td>
                <td>年度内汇率的波动范围</td>
            </tr>
        </table>
    </div>
</div>

<!-- 术语解释抽屉 -->
<div class="terms-drawer">
    <div class="terms-header">
        关键指标说明 ↑
    </div>
    <div class="terms-content">
        <p><strong>电商渗透率：</strong>电商交易额占社会零售总额的比例</p>
        <p><strong>市场份额：</strong>企业/平台销售额占该市场总销售额的比例</p>
        <p><strong>物流延误率：</strong>未按承诺时间送达的订单占比</p>
        <p><strong>退货率：</strong>退货订单数量占总订单的比例</p>
        <p><strong>客诉率：</strong>投诉订单数量占总订单的比例</p>
        <p><strong>汇率波动率：</strong>年度内汇率的波动范围</p>
    </div>
</div>

</body>
</html>
