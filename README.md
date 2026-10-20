<!DOCTYPE html>
<html lang="zh-CN">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title style="color: cornflowerblue;">个人主页</title>
<head>
<style>
     /* ===== 基础 ===== */
     * { box-sizing: border-box; }
     html {
       /* 锚点跳转时目标不被导航栏盖住 */
       scroll-padding-top: 64px;
     }
     body {
       margin: 0;
       padding-top: 64px;        /* 给固定导航栏留出高度 */
       font-family: "Microsoft YaHei", sans-serif;
       font-size: 17px;
       line-height: 1.7;
       color: #4abedb;
       background: #eef3f9;
     }
     /* ===== 固定导航栏 ===== */
     .nav {
       position: fixed;
       top: 0;
       left: 0;
       right: 0;
       z-index: 100;
       height: 64px;
       display: fiex;
       align-items: center;
       justify-content: center;
       gap: 30px;
       background: #ffffff;
       border-bottom: 1px solid #dde6ef;
     }
     .nav a {
       color: #4ba0e0;
       text-decoration: none;
       padding: 4px 2px;
       border-bottom: 2px solid transparent;
     }
     .nav a:hover {
       border-bottom-color: #6ab1e4;
     }
     /* ===== 内容卡片 ===== */
     main {
       max-width: 1000px;
       margin: 32px auto;
       padding: 36px;
       background: #ffffff;
       border-radius: 14px;
       box-shadow: 0 4px 20px rgba(36, 54, 75, .06);
     }
     h1 {
       margin: 0;
       font-size: 30px;
       color: #9cfedd;
     }
     h2 {
       margin: 0 0 14px;
       font-size: 22px;
       color: #484ad6; /* 粉色标题 和截图一致 */
     }
     h3 {
       margin: 0 0 8px;
       font-size: 19px;
       color:#9a64e0;
     }
     /* 只有直接放在 main 下的 h2 才需要上间距 */
     main > h2 { margin-top: 32px; }
     p { margin: 0 0 12px; }
     a { color: #6db8ea; }
     /* ===== 个人简介 ===== */
     .profile {
       display: flex;
       align-items: center;
       gap: 26px;
       margin-top: 26px;
       padding: 26px;
       background: #f4f8fc;
       border-radius: 12px;
     }
     .avatar {
       flex-shrink: 0;
       width: 100px;
       height: 134px;
       border-radius: 50%;
       background: linear-gradient(135deg, #cfe6fb, #a4d0f2);
       color: #6fa5cd;
       font-size: 42px;
       line-height: 96px;
       text-align: center;
     }
     /* ===== 作品列表 ===== */
     .works {
       display: flex;
       flex-wrap: wrap;
       gap: 18px;
     }
     .work {
       flex: 1 1 240px;
       display: flex;
       flex-direction: column;
       padding: 20px;
       background: #fbfcfe;
       border: 1px solid #dde6ef;
       border-radius: 12px;
     }
     .work a {
       margin-top: auto;
       font-weight: bold;
       text-decoration: none;
     }
     /* ===== 分隔区块 ===== */
     .details,
     .contact {
       margin-top: 32px;
       padding-top: 24px;
       border-top: 1px solid #e4ecf4;
     }
     footer {
       margin-top: 28px;
       text-align: center;
       color: #7b8ea3;
       font-size: 15px;
     }
   </style>
</head>
<body>
    <nav class="nav">
        <a href=" ">首页</a >
        <a href="#about">关于我</a >
        <a href="#works">我的作品</a >
        <a href="#contact">联系我</a >
    </nav>
    <main>
        <header id="home">
            <h1 style="color: rgb(147, 250, 224);">马一丹的个人主页</h1>
        </header>
        <section class="profile" id="about">
            <div class="avatar"><img src="avatar.jpg" alt="我的图片" width="100"></div>
            <div>
                <h2 style="color: rgb(112, 0, 181);" ;">你好啊，我是马一丹(｡ì _ í｡)</h2>
                <p style="color: deepskyblue;">我是2026级教育技术学专业的学生</p >
            </div>
        </section>
        <h2 id="works">我的作品</h2>
        
<artical cllass="work">
                <div class ="box">
                    <div style="padding:18px;border:1px solid #dde6ef;border-radius:12px;margin:12px 0;background:#fbfcfe;">
                <h3 style="color: rgb(80, 14, 124);">兴趣爱好</h3>
                <ul>
<li style="color: rgb(102, 236, 231);">书法</li>
<li style="color: rgb(102, 236, 231);">绘画</li>
<li style="color: rgb(102, 236, 231);">阅读</li>
<li style="color: rgb(102, 236, 231);">追番看动漫</li>
</ul>
                </div>
            </artical>
                                       
        
<artical class="work">
      <h3 style="color: rgb(63, 5, 164);">学习方向</h3>
       <ul>
<li style="color: hotpink;">学习Web程序设计</li>
<li style="color: hotpink;">学习人工智能</li>
<li style="color: hotpink;">学习教育学和教育技术导论</li>
<li style="color: hotpink;">学习Python程序设计</li>
<li style="color: hotpink;">学好英语</li>
</ul>
        </artical>
        <section class="contact id="contact">
        <h2 style="color: rgb(250, 219, 44);">联系我</h2>
    <p style="color: rgb(241, 209, 127);"><a href="https://github.com">我的GitHub</a ></p >
    <p style="color: rgb(241, 209, 127);">邮箱：1798395449@qq.com</p >
    <a href="https://github.com"></a >
        </section>
        <footer style="color: rgb(142, 255, 240);">马一丹的个人主页</footer>
    </main>
</body>
</html>
