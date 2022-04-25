# proxy_rsshub

使用 GitHub Actions 反代 RSSHub + 多实例轮询。

https://github.com/wdssmq/proxy_rsshub

# 关于

<p><img src="https://img.shields.io/badge/-SEO%E6%98%AF%E5%95%A5%E8%81%94%E7%9B%9F-yellowgreen" title="SEO是啥联盟" alt="SEO是啥联盟"> <a target="_blank" title="Feed-FeedsPub" href="https://feeds.pub/feed/https%3A%2F%2Fwww.wdssmq.com%2Ffeed.php"><img src="https://img.shields.io/badge/Feed-FeedsPub-brightgreen" title="Feed-FeedsPub" alt="Feed-FeedsPub"></a> <a target="_blank" title="Feed-Inoreader" href="https://www.innoreader.com/feed/https%3A%2F%2Fwww.wdssmq.com%2Ffeed.php"><img src="https://img.shields.io/badge/Feed-Inoreader-blue" title="Feed-Inoreader" alt="Feed-Inoreader"></a> <a target="_blank" title="Feed-feed.wdssmq.com" href="https://feed.wdssmq.com"><img src="https://img.shields.io/badge/Feed-feed.wdssmq.com-yellow" title="Feed-feed.wdssmq.com" alt="Feed-feed.wdssmq.com"></a> <a target="_blank" title="爱发电-@wdssmq" href="https://afdian.net/@wdssmq"><img src="https://img.shields.io/badge/%E7%88%B1%E5%8F%91%E7%94%B5-%40wdssmq-blueviolet" title="爱发电-@wdssmq" alt="爱发电-@wdssmq"></a> <a target="_blank" title="mastodon-wdssmq" href="https://wxw.moe/@wdssmq"><img src="https://img.shields.io/mastodon/follow/142218?domain=https%3A%2F%2Fwxw.moe%2F" title="mastodon-wdssmq" alt="mastodon-wdssmq"></a> <a target="_blank" title="QQ-349467624" href="https://wpa.qq.com/msgrd?v=3&uin=349467624&site=qq&menu=yes"><img src="https://img.shields.io/badge/QQ-349467624-0086F9" title="QQ-349467624" alt="QQ-349467624"></a></p>

# 项目描述

软件名称
wdssmq/proxy_rsshub: 使用 GitHub Actions 反代 RSSHub + 多实例轮询

应用平台
GitHub Workflows / GitHub Actions
Python
推荐类型
【开发者自荐】

一句简介
定时抓取 RSSHub 站点内容并缓存在 GitHub 库中，RSSHub 实例故障或被源站屏蔽时也不需要更换阅读器中的地址；

应用简介

核心功能为 Python 实现，使用 GitHub Actions 定时触发；

需要编辑config.json添加订阅规则，执行时依次向所设置的 RSSHub 站点请求相应规则；

抓取成为后会保存在 xml 文件夹中，对应的链接地址自动更新至README.md中；

将匹配如下模式并自动替换——---start---(.|\n)*?---end---；

proxy_rsshub/.github/workflows/index.yml 内可设置执行间隔；【【对于 RSS 来说 6 小时已经很合理了吧】】

官方网站 && 应用商店地址
wdssmq/proxy_rsshub: 使用 GitHub Actions 反代 RSSHub + 多实例轮询：

https://github.com/wdssmq/proxy

# RSS 转存列表

获取 opml：[rss.opml](rss.opml "查看 opml")「[raw 直链](rss.opml?raw=true "raw 直链")」

---start---

2022-04-25 08:29:41

title: 沉冰浮水 的追番列表

path: [bilibili/user/bangumi/44744006](xml/bilibili_user_bangumi_44744006.xml "沉冰浮水 的追番列表") 「[raw](xml/bilibili_user_bangumi_44744006.xml?raw=true "沉冰浮水 的追番列表")」

title: ocarina 的 bilibili 空间

path: [bilibili/user/video/1397229](xml/bilibili_user_video_1397229.xml "ocarina 的 bilibili 空间") 「[raw](xml/bilibili_user_video_1397229.xml?raw=true "ocarina 的 bilibili 空间")」

title: 宅游星 的 bilibili 空间

path: [bilibili/user/video/324798](xml/bilibili_user_video_324798.xml "宅游星 的 bilibili 空间") 「[raw](xml/bilibili_user_video_324798.xml?raw=true "宅游星 的 bilibili 空间")」

title: 猎影娘 的 bilibili 空间

path: [bilibili/user/video/43619319](xml/bilibili_user_video_43619319.xml "猎影娘 的 bilibili 空间") 「[raw](xml/bilibili_user_video_43619319.xml?raw=true "猎影娘 的 bilibili 空间")」

title: 橙心资讯 的 bilibili 空间

path: [bilibili/user/video/28822227](xml/bilibili_user_video_28822227.xml "橙心资讯 的 bilibili 空间") 「[raw](xml/bilibili_user_video_28822227.xml?raw=true "橙心资讯 的 bilibili 空间")」

title: 影迷 qzm 的 bilibili 空间

path: [bilibili/user/video/108766690](xml/bilibili_user_video_108766690.xml "影迷 qzm 的 bilibili 空间") 「[raw](xml/bilibili_user_video_108766690.xml?raw=true "影迷 qzm 的 bilibili 空间")」

title: Azulim 搬运 的 bilibili 空间

path: [bilibili/user/video/508191](xml/bilibili_user_video_508191.xml "Azulim 搬运 的 bilibili 空间") 「[raw](xml/bilibili_user_video_508191.xml?raw=true "Azulim 搬运 的 bilibili 空间")」

title: 九重紫 的 bilibili 空间

path: [bilibili/user/video/225347042](xml/bilibili_user_video_225347042.xml "九重紫 的 bilibili 空间") 「[raw](xml/bilibili_user_video_225347042.xml?raw=true "九重紫 的 bilibili 空间")」

title: 小鸟游杏子 的 bilibili 空间

path: [bilibili/user/video/1069108539](xml/bilibili_user_video_1069108539.xml "小鸟游杏子 的 bilibili 空间") 「[raw](xml/bilibili_user_video_1069108539.xml?raw=true "小鸟游杏子 的 bilibili 空间")」

title: AIChannel 官方 的 bilibili 空间

path: [bilibili/user/video/1473830](xml/bilibili_user_video_1473830.xml "AIChannel 官方 的 bilibili 空间") 「[raw](xml/bilibili_user_video_1473830.xml?raw=true "AIChannel 官方 的 bilibili 空间")」

title: 小希小桃 Channel 的 bilibili 空间

path: [bilibili/user/video/5563350](xml/bilibili_user_video_5563350.xml "小希小桃 Channel 的 bilibili 空间") 「[raw](xml/bilibili_user_video_5563350.xml?raw=true "小希小桃 Channel 的 bilibili 空间")」

title: 田中姬铃木雏 Official 的 bilibili 空间

path: [bilibili/user/video/296909317](xml/bilibili_user_video_296909317.xml "田中姬铃木雏 Official 的 bilibili 空间") 「[raw](xml/bilibili_user_video_296909317.xml?raw=true "田中姬铃木雏 Official 的 bilibili 空间")」

title: 哔哩哔哩电影 的 bilibili 空间

path: [bilibili/user/video/15773384](xml/bilibili_user_video_15773384.xml "哔哩哔哩电影 的 bilibili 空间") 「[raw](xml/bilibili_user_video_15773384.xml?raw=true "哔哩哔哩电影 的 bilibili 空间")」

title: 葵歌剧摸鱼团 的 bilibili 空间

path: [bilibili/user/video/7078836](xml/bilibili_user_video_7078836.xml "葵歌剧摸鱼团 的 bilibili 空间") 「[raw](xml/bilibili_user_video_7078836.xml?raw=true "葵歌剧摸鱼团 的 bilibili 空间")」

title: 夏实萌惠_搬运 的 bilibili 空间

path: [bilibili/user/video/355167926](xml/bilibili_user_video_355167926.xml "夏实萌惠_搬运 的 bilibili 空间") 「[raw](xml/bilibili_user_video_355167926.xml?raw=true "夏实萌惠_搬运 的 bilibili 空间")」

title: 夏实萌惠_official 的 bilibili 空间

path: [bilibili/user/video/1416046076](xml/bilibili_user_video_1416046076.xml "夏实萌惠_official 的 bilibili 空间") 「[raw](xml/bilibili_user_video_1416046076.xml?raw=true "夏实萌惠_official 的 bilibili 空间")」

title: MMP 字幕搬运 的 bilibili 空间

path: [bilibili/user/video/278093107](xml/bilibili_user_video_278093107.xml "MMP 字幕搬运 的 bilibili 空间") 「[raw](xml/bilibili_user_video_278093107.xml?raw=true "MMP 字幕搬运 的 bilibili 空间")」

title: 虚拟女友 Yomemi 的 bilibili 空间

path: [bilibili/user/video/292044559](xml/bilibili_user_video_292044559.xml "虚拟女友 Yomemi 的 bilibili 空间") 「[raw](xml/bilibili_user_video_292044559.xml?raw=true "虚拟女友 Yomemi 的 bilibili 空间")」

title: 琴肥夢甜品加工坊 的 bilibili 空间

path: [bilibili/user/video/84399544](xml/bilibili_user_video_84399544.xml "琴肥夢甜品加工坊 的 bilibili 空间") 「[raw](xml/bilibili_user_video_84399544.xml?raw=true "琴肥夢甜品加工坊 的 bilibili 空间")」

title: 琴吹夢_official 的 bilibili 空间

path: [bilibili/user/video/442426299](xml/bilibili_user_video_442426299.xml "琴吹夢_official 的 bilibili 空间") 「[raw](xml/bilibili_user_video_442426299.xml?raw=true "琴吹夢_official 的 bilibili 空间")」


---end---
