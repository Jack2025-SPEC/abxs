<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AB资源服务器 - 官方主页</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, #1e88e5, #0d47a1);
            padding: 2rem 0;
            text-align: center;
            color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
        
        .logo {
            max-width: 120px;
            margin-bottom: 1rem;
        }
        
        h1 {
            margin: 0;
            font-size: 2rem;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }
        
        .tagline {
            font-style: italic;
            margin-top: 0.5rem;
            opacity: 0.9;
        }
        
        nav {
            background-color: #1565c0;
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
            transition: opacity 0.3s;
        }
        
        nav a:hover {
            opacity: 0.8;
            text-decoration: underline;
        }
        
        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }
        
        section {
            margin-bottom: 2rem;
            background-color: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        h2 {
            color: #0d47a1;
            border-bottom: 2px solid #e0e0e0;
            padding-bottom: 0.5rem;
            margin-top: 0;
        }
        
        .qq-group-info {
            background-color: #e3f2fd;
            padding: 1.5rem;
            border-radius: 8px;
            margin-bottom: 1.5rem;
        }
        
        .group-stats {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .stat-item {
            background-color: #bbdefb;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .rules-list li {
            margin-bottom: 0.8rem;
            padding-left: 1.2rem;
            position: relative;
        }
        
        .rules-list li:before {
            content: "•";
            position: absolute;
            left: 0;
            color: #1e88e5;
            font-weight: bold;
        }
        
        .join-button {
            display: inline-block;
            background: linear-gradient(135deg, #1e88e5, #0d47a1);
            color: white;
            padding: 0.8rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 1rem;
            transition: transform 0.3s;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        
        .join-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
        }
        
        footer {
            background-color: #0d47a1;
            color: white;
            text-align: center;
            padding: 1.5rem;
            margin-top: 2rem;
        }
        
        .checkbox-item {
            margin-bottom: 0.5rem;
        }
        
        @media (max-width: 768px) {
            nav a {
                display: block;
                margin: 0.5rem 0;
            }
            
            .group-stats {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        < img src="ab_logo.png" alt="AB资源服务器标志" class="logo">
        <h1>AB资源服务器</h1>
        <p class="tagline">创新自律 · 公平游戏 · 舒适交流</p >
    </header>
    
    <nav>
        <a href=" ">关于我们</a >
        <a href="#group">QQ群信息</a >
        <a href="#rules">群规条例</a >
        <a href="#server">服务器特色</a >
        <a href="#join">加入我们</a >
    </nav>
    
    <div class="container">
        <section id="about">
            <h2>关于AB资源服务器</h2>
            <p>欢迎来到AB资源服务器！我们是一个专注于为《我的世界》玩家提供公平、舒适游戏环境的资源型服务器。</p >
            <p>服务器创立于2024年，始终坚持"创新自律，杜绝滥用权利"的宗旨，致力于为玩家打造一个纯净的游戏交流平台。</p >
        </section>
        
        <section id="group" class="qq-group-info">
            <h2>官方QQ群信息</h2>
            <p><strong>群名称：</strong>AB Resource Server | AB资源</p >
            <p><strong>群号：</strong>369856947</p >
            <p><strong>当前成员：</strong>108人</p >
            
            <div class="group-stats">
                <div class="stat-item">活跃15人</div>
                <div class="stat-item">男44人</div>
                <div class="stat-item">南宁2人</div>
                <div class="stat-item">00后55人</div>
                <div class="stat-item">💬13%</div>
                <div class="stat-item">💬40%</div>
                <div class="stat-item">💬1%</div>
                <div class="stat-item">💬50%</div>
            </div>
            
            <div class="checkbox-item">
                <input type="checkbox" id="build-date" checked>
                <label for="build-date">建群时间：2024-07-23</label>
            </div>
            <div class="checkbox-item">
                <input type="checkbox" id="interests" checked>
                <label for="interests">兴趣：我的世界 | BloonsTD6 | 吗喽大战气球</label>
            </div>
        </section>
        
        <section id="rules">
            <h2>群规条例</h2>
            <p>为了维护良好的交流环境，请所有成员严格遵守以下规定：</p >
            <ul class="rules-list">
                <li>禁止在群内争吵或人身攻击</li>
                <li>严禁涉及黄、赌、毒等违法信息</li>
                <li>禁止谈论任何政治议题</li>
                <li>群内主要用途为玩家交流和服务器公告</li>
                <li>违反规定者将收到警告，三次警告后移出群聊</li>
                <li>情节严重者将交由警方处理</li>
            </ul>
            <p>我们期待每位成员都能自觉遵守规则，共同营造和谐的交流环境。</p >
        </section>
        
        <section id="server">
            <h2>服务器特色</h2>
            <p>AB资源服务器与其他服务器相比具有以下独特优势：</p >
            <ul class="rules-list">
                <li><strong>历史悠久：</strong>创立于2024年，运营经验丰富</li>
                <li><strong>公平环境：</strong>纯资源型服务器，0盈利模式</li>
                <li><strong>玩法经典：</strong>通过挖掘矿物升级装备的核心玩法</li>
                <li><strong>稳定可靠：</strong>为网易我的世界联机大厅小镇专门优化</li>
            </ul>
            <p>我们的服务器不设任何充值渠道，确保所有玩家都在完全公平的环境下游戏。</p >
        </section>
        
        <section id="join">
            <h2>如何加入我们</h2>
            <p>欢迎加入AB资源服务器的官方QQ群，获取最新服务器信息和玩家交流：</p >
            <p><strong>QQ群号：369856947</strong></p >
            <a href="https://jq.qq.com/?_wv=1027&k=YOUR_GROUP_KEY" class="join-button">立即加入QQ群</a >
            <p>加入群聊后，请仔细阅读群公告和群规，以便更好地融入我们的社区。</p >
        </section>
    </div>
    
    <footer>
        <p>© 2024 AB资源服务器 - 保留所有权利</p >
        <p>创新自律 · 杜绝滥用权利</p >
    </footer>
</body>
</html>

  
      