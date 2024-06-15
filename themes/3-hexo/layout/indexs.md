# 今日观察

blog.joevan.top  https://blog.joevan.top  

Home - capy.lol  https://capy.lol/  

卡皮巴拉 | Kapibala  https://kapibala.icu/  

GitHub - superseriousbusiness/gotosocial: Fast, fun, small ActivityPub server.  https://github.com/superseriousbusiness/gotosocial  

GoToSocial Documentation  https://docs.gotosocial.org/en/latest/  

iOS14搭配快捷指令在手机上写hexo博客 - 知乎  https://zhuanlan.zhihu.com/p/346159204?utm_medium=social&utm_psn=1783399423356731392&utm_source=ZHShareTargetIDMore&utm_id=0  

study3d.com - GoToSocial  https://study3d.com/  

荒岛-分享创造快乐  https://lala.im/  

小米发布《小米澎湃OS技术白皮书》 - OSCHINA - 中文开源技术交流社区  https://www.oschina.net/news/270045  

2023 年度人工智能现状报告 (State of AI Report 2023) - OSCHINA - 中文开源技术交流社区  https://www.oschina.net/news/262155/state-of-ai-2023-report  

有道开源RAG引擎 QAnything 版本更新啦 - 有道技术团队的个人空间 - OSCHINA - 中文开源技术交流社区  https://my.oschina.net/youdaotech/blog/10894309  

    

一份谷歌写给 CTO 们的报告 - DORA 2023 版全面解读 - Bytebase的个人空间 - OSCHINA - 中文开源技术交流社区  https://my.oschina.net/u/6148470/blog/10118131  

特赞科技Tezign创始人及CEO范凌：人工智能与产业想象力_亿欧  https://www.iyiou.com/news/202307081048044  

轻量级PHP框架|专注WEB应用开发18年 · ThinkPHP  https://www.thinkphp.cn/  

行业应用 - 复志科技Raise3D中国官方网站  https://www.raise3d.cn/solutions/  

创见 tech2ipo 何时已不见？  

iPadly | 网址最短的中文 iPhone/iPad 资源导航站  http://ipad.ly/  

Build Web Apps with No-Code | Momen  https://momen.app/  

Xterminal - 更好用的开发工具，但不止于(SSH/控制台/More)  https://www.xterminal.cn/  

GitHub - fengxxc/wechatmp2markdown: 微信公众号文章转Markdown  https://github.com/fengxxc/wechatmp2markdown  

Pic Smaller – Compress JPEG, PNG, WEBP, AVIF, SVG and GIF images intelligently  https://picsmaller.com/  

电鸭社区-专注远程工作招聘交流-远程工作，从电鸭开始  https://eleduck.com/  

介绍 - NocoBase  https://docs-cn.nocobase.com/welcome/introduction  

NocoBase-开源、私有部署的轻量级无代码和低代码开发平台  https://cn.nocobase.com/  

Lemmy Cafe - A general purpose fediverse instance  https://lemmy.cafe/  

使用Docker部署GotoSocial - LemonCat  https://blog.kaixin.meme/2024/02/27/%E4%BD%BF%E7%94%A8docker%E9%83%A8%E7%BD%B2gotosocial/  

Joevan (@joevan@masto.nyc) - Mastodon NYC  https://masto.nyc/@joevan  

bad-licenses/hot-potato-license at master · ErikMcClure/bad-licenses · GitHub  https://github.com/ErikMcClure/bad-licenses/blob/master/hot-potato-license  

开源简读 - 追踪开源动态，挖掘技术创新，关注社区发展。  https://www.inkspcl.com/index.html  

解决 Hexo 部署 Github Pages 自定义域名失效的问题(即使已添加 CNAME）_gitpages cname值在哪里找到-CSDN博客  https://blog.csdn.net/weixin_41747528/article/details/102772937
                博客 下载 学习 社区 C知道 GitCode InsCode 会议 Hexo     搜索 登录 会员618 消息 历史 创作中心 发布
     解决 Hexo 部署 Github Pages 自定义域名失效的问题( 即使已添加 CNAME)
 桌子LZT
码龄6年 暂无认证
8 55万+ 81万+ 2万+
原创 周排名 总排名 访问 等级
445 8 31 12 113
积分 粉丝 获赞 评论 收藏
私信 关注
搜博主文章
热⻔文章
C++判断输入结束的简单方法(从键盘输 入+从文件读入) 9397
Web 图片引用之相对路径与绝对路径 7577
解决 Hexo 部署 Github Pages 自定义域名 失效的问题(即使已添加 CNAME)
3377
正确理解 CSS 权值(不应存在进制) 2047
【剑指Offer】输入一个链表，按链表值从 尾到头的顺序返回一个ArrayList (JAVA递 归实现) 883
分类专栏
Web前端 5篇 日常踩坑 1篇 软件设计师
算法笔记 1篇 C++练习 3篇 Java练习 1篇
最新评论
解决 Hexo 部署 Github Pages 自定义域... Grey.R: 非常感谢 我是hexo g -d没用，所
欢迎来我的博客查看原文。
当你自定义 Github Pages 域名时，是否出现了每次hexo deploy，自定义域名都失效的问题呢?
以下分两种情况讨论。
情形1:未添加 CNAME 解决方案:
1. 找到 hexo 博客根目录下的 source 文件夹。注意，不是主题的 source 文件夹。当 hexo 生 成静态⻚面时，根目录下的 source 文件夹中的内容，就会在生成的网⻚根目录中(你可以在部 署到github后，在仓库中查看，此时本地根目录下source文件夹的内容就在仓库的根目下)。
2. 新建一个文件，名为 CNAME ，内容为你的域名(不包括www.或http等等)。如图:
注意:
------- 名为 CNAME，全部大写，没有后缀。
------- 内容只包含一个域名，且不含 www. 或 http 等。 ------- 放到根目录下的source文件夹中。
3. hexog-d 执行完毕后登陆github，找到仓库，settings，查看域名是否已经更改，或者直接用域名尝试访问。
情形2:已添加 CNAME 解决方案:
1. 首先进入github仓库查看 CNAME是否出现在根目录中，如图所示:
若没有，则请返回第一种情况，认真检查自己的 CNAME 的路径是否正确。
2.若仓库根目录存在 CNAME 文件，请按照以下步骤检查: ------- 情形1步骤2中的注意点，是否都符合要求?
------- 若感觉符合要求!!!请你务必注意你的文件后缀!!!
新建无后缀文件可以使用touch命令。
使用命令行，cd 到指定目录，然后 touch filename，这样就新建了一个名为filename的无后缀文 件。
写在最后:
以上基本是我遇到的问题和解决方法，尤其是最后这个隐藏后缀以及直接删除后缀，困扰了我好几 个小时。希望能给像我一样的新人一点帮助!
这是我的邮箱，欢迎交流学习。
欢迎来踩我的博客!!
库，仓库名为 ，其中  是你的 GitHub 用户名。 2. 在本地安装
Hexo，并创建一个新的博客项目。 3. 配置“相He关xo推的荐 文么件?，将  部登分录的后 享设受置以为下，并将  设置为你在步骤1中创建的仓库的链接。 示例配置如下:  4. 在 Hexo 项目根目录使用以下命令进行部署:  这将会将生成的静态文件部署到 GitHub Pages。 5. 在你购
 下载海量资源
举报
  关买于的我域们名招提贤供纳商士处，商添务加合一作个寻CN求A报M道E 记录4，0将0-域66名0指-0向108客。服6. 在工作Gi时tH间ub8仓:3库0-中22的:00 设置⻚面，找到「Custom domain」选项，输入你的绑定域名。 7. 等待DNS记录生效，一般情况下需要几十分钟 区
   公安备案号11010502030143 京ICP备19004658号 京网文〔2020〕1039-165号 经营性网站备案信息 到几小时。 完成以上步骤后，你的 Hexo 博客就会通过你绑定的域名访问了。请注意，如果你的仓库是公开的，
北京互联网违法和不良信息举报中心 家⻓监护 网络110报警服务 中国互联网举报中心 Chrome商店下载 账号管理规范 版权与免责声明
 你的博客内容将对所有版人权可申⻅诉。出如版果物你许可想证要私营业有执博照客©，1可99以9-将20仓24库北设京创置新为乐私知有网，络并技术按有照限G公it司Hub 文档上的说明进行
立即登录
         配置。 希望能帮到你!如有任何问题，请随时问我。
桌子LZT 关注 12 14 10 专栏目录
                    
https://blog.csdn.net/weixin_41747528/article/details/102772937  
