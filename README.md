**最后更新更新时间：2020-02-04 17:45**



![](notice.jpeg)



有一名正直的同学[@miaoshengyou](https://github.com/miaoshengyou)叫你们别再[吃人血馒头](https://github.com/kajweb/wqxuetang_downloader/issues/21)了。

![](D:\Code\crawler_project\wqxuetang_downloader\zhengzhi.png)

我一直在想，是什么钱支撑起文泉学堂运营的钱？如果是清华大学，回到本质是不是纳税人、country的钱？如果我们用这些钱提升国民教育有什么错？

如果作为清华大学的学生使用这个平台是否需要付费？

- 如果需要付费，他们在哪一部分付费了？
  - 图书馆代缴？
    - 图书馆的钱哪里来？
    - 学校的钱哪里来？
  - 学生个人缴费？
    - 学生学费是怎么构成的？

- 如果不需要付费，他们算不算阅读了盗版书？
- 

如果非要扯下去，就是我们没钱买书就对了



# 文泉学堂 离线阅读转换器（暂停更新）

文泉学堂解析工具自动生成pdf，**方便**用户通过离线的方式阅读文泉学堂**免费**的资源。切勿商用和广泛传播。-\_-

利用`python3`自动下载文泉学堂学堂提供的免费的pdf书籍（仅供测试，请24小时内删除）

## 🌙 有效性

| 时间             | 状态                                                         |
| ---------------- | ------------------------------------------------------------ |
| 2020-02-03 04:00 | 发布，下载丝滑流畅                                           |
| 2020-02-03 12:00 | 用户反馈，下载状态正常                                       |
| 2020-02-03 16:00 | 反馈下载超时，增加超时与自动重试，延长time sleep时间到2.5s   |
|                  | 通过正常页面阅读，发现加载速度慢                             |
| 2020-02-03 17:00 | 做个正常人，5秒看一个页面。挂着玩游戏吧……                    |
| 2020-02-03 17:27 | 下载过程中记得去img看一下有没有**没有加载**的图片，及时停掉等几分钟再重新启动。 |
|                  | 延长time sleep时间为5-10s（随机）                            |
| 2020-02-03 21:00 | 用的人太多了，卡死不动了。                                   |
| 2020-02-04 00:30 | 下载恢复，估计人都去睡觉了。                                 |
| 2020-02-04 00:50 | 下载异常，变成5k图片（估计是哪位老哥加班？）                 |
| 2020-02-04 01:08 | 修复下载异常，增加10k图片比对。没有增加5k图片比对（再次出现再说） |
| 2020-02-04 01:28 | 增加直接在命令行执行函数，直接运行`python main.py`即可       |
| 2020-02-04 02:39 | 被封IP、关了数据接口、单个ip访问上限等问题，被限制访问，访问全部定向到5k图片 |
| 2020-02-04 03:04 | 增加识别5k图片                                               |
| 2020-02-04 03:47 | 增加随机User-Agent，虽然没什么用                             |
| 2020-02-04 17:45 | 网站受资源限制，需要登录使用。并将该脚本定性为恶意爬虫。     |



## ❤免责声明

> 所发布的一切破解补丁、注册机和注册信息及软件的解密分析文章仅限用于学习和研究目的；不得将上述内容用于商业或者非法用途，否则，一切后果请用户自负。本站信息来自网络，版权争议与本站无关。您必须在下载后的24个小时之内，从您的电脑中彻底删除上述内容。如果您喜欢该程序，请支持正版软件，购买注册，得到更好的正版服务。如有侵权请邮件与我们联系处理。



## ⚡ 声明

**邮箱不接受使用问题，使用存在问题请在[`Issues`](https://github.com/kajweb/wqxuetang_downloader/issues)中提出**

若本应用侵犯了您的权益，或造成不利影响，请联系 lyy@iwwee.com 并提供微信号码，在确认身份后我将立即下架本应用。

欢迎 Star 和 Fork ~

如果你有什么问题请提 Issue



## 📃 LICENSE

[MIT](https://opensource.org/licenses/mit-license.php)



## 其他渠道

> 其他渠道未尝试与验证，不保证可以正常使用

[gumblex/wqxt_pdf](https://github.com/gumblex/wqxt_pdf) (Python)

[文泉学堂pdf一键下载](https://greasyfork.org/zh-CN/scripts/396025-文泉学堂pdf下载) (油猴脚本)   [github](https://github.com/Kevin0z0/wenquan-pdf-download)

[SweetInkSweetInk)/wqxuetang-pdf-downloader](https://github.com/SweetInk/wqxuetang-pdf-downloader) (Java)

[sinceNa/wqxuetang ](https://github.com/sinceNa/wqxuetang)(NodeJS)

[kdxcxs/wqDownloader](https://github.com/kdxcxs/wqDownloader)(PY代理)