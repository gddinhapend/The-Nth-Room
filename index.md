# 第N实验室

<div style="text-align: right; margin-bottom: 20px;">
  <a href="./team.html" style="font-weight: bold; font-size: 1.2em; margin-right: 20px;">Team</a>
  <a href="./projects.html" style="font-weight: bold; font-size: 1.2em;">Projects</a>
</div>

---

欢迎来到 **第N实验室** 课题组主页！
我们致力于 **[无线电，无人机，测向小车]** 等前沿领域的研究。我们的口号是 **[我们永远不满足于现有方案，我们永远在探索更好、更优的第N种可能]**。

我们是一支融合无线电技术、无人机系统与智能小车平台的多元化创新团队。课题组以学生兴趣为主要驱动，由研究生带领本科生，在自主探索与项目实践中共同成长，形成了活跃而协作的良好氛围。
在无线电方向，我们具备从信号发射到接收定位的完整技术链经验，不仅能够DIY制作经典的80米波段测向信号源，也深入研究和应用手持式测向设备，致力于实现复杂环境下的精准信号定位。无人机方面，我们的探索涵盖从多旋翼飞行器的设计与控制到室内定位与自主导航等前沿课题。智能小车则作为验证环境感知、路径规划与自主决策算法的理想移动平台，团队成员在此平台上开展基于激光雷达与视觉算法的环境感知与自动驾驶研究。
团队鼓励学以致用，积极参与各类科技竞赛。这种以兴趣为导向、鼓励动手实践的氛围，有效激发了成员的创新潜能，并为我们未来在无人系统协同控制、智能传感等领域的深入探索奠定了坚实基础。

## 以下是我们课题组的一些项目展示

<style>
/* 全局样式：可选，为了让页面更干净 */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 20px;
    color: #333;
}

/* 定义容器，使用 CSS Grid 创建两行两列的网格 */
.grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr; /* 两列，每列等宽 */
    grid-template-rows: auto auto; /* 两行，高度自适应 */
    gap: 20px; /* 区域之间的间距 */
    margin-top: 30px;
}

/* 每个项目区域的样式 */
.project-card {
    background-color: #f9f9f9; /* 轻微的背景色，模拟无分割线 */
    padding: 20px;
    border-radius: 8px; /* 圆角边框 */
    box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* 轻微的阴影，增加立体感 */
    display: flex; /* 内部使用 Flexbox 布局 */
    flex-direction: column; /* 元素垂直堆叠 */
    position: relative; /* 用于定位右上角的标题 */
}

/* 项目标题的样式 */
.project-title {
    position: absolute; /* 绝对定位 */
    top: 15px; /* 距离顶部15px */
    right: 20px; /* 距离右侧20px */
    font-size: 1.2em;
    font-weight: bold;
    color: #0056b3; /* 链接颜色 */
    text-decoration: none; /* 默认无下划线 */
}

.project-title:hover {
    text-decoration: underline; /* 鼠标悬停时显示下划线 */
}

/* 项目图片容器的样式 */
.project-image-container {
    float: left; /* 让图片浮动到左侧 */
    margin-right: 15px; /* 图片右侧留出间距 */
    margin-bottom: 10px; /* 图片下方留出间距 */
    width: 100px; /* 控制图片宽度 */
    height: 100px; /* 控制图片高度 */
    overflow: hidden; /* 确保图片不超出容器 */
    border-radius: 4px; /* 图片也带一点圆角 */
}

.project-image-container img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* 裁剪图片以填充容器，保持比例 */
    display: block; /* 移除图片底部空白 */
}

/* 清除浮动，确保内容在图片下方正常排列 */
.project-description::after {
    content: "";
    display: table;
    clear: both;
}

/* 媒体查询：在小屏幕（例如手机）上，布局变为单列 */
@media (max-width: 768px) {
    .grid-container {
        grid-template-columns: 1fr; /* 单列布局 */
    }
    .project-title {
        position: static; /* 取消绝对定位 */
        text-align: left; /* 标题左对齐 */
        margin-bottom: 10px; /* 标题下方增加间距 */
        margin-right: 0;
    }
    .project-image-container {
        float: none; /* 取消浮动 */
        margin-right: 0;
        margin-bottom: 15px;
        width: 100%; /* 图片宽度自适应 */
        height: auto; /* 高度自适应 */
    }
    .project-image-container img {
        height: auto;
    }
}

</style>

<div class="grid-container">

    <div class="project-card">
        <a href="https://your-project1-link.com" class="project-title">多旋翼无人机</a>
        <div class="project-image-container">
            <img src="./picture/电赛无人机.jpg" alt="多旋翼无人机">
        </div>
        <div class="project-description">
            <p>飞控、机械结构和计算机CV三大系统的精密协同是多旋翼无人机的核心，也是我们组所研究的方向。小组汇聚了一群对多旋翼无人机技术怀有浓厚兴趣的探索者，我们因热爱而相聚，在动手实践中不断解锁飞行的奥秘。</p>
            <p>曾在CUADC比赛获得了全国三等奖</p>
        </div>
    </div>

    <div class="project-card">
        <a href="https://your-project2-link.com" class="project-title">信号源</a>
        <div class="project-image-container">
            <img src="./picture/信号源.jpg" alt="信号源">
        </div>
        <div class="project-description">
            <p>型号源是无线电测向比赛中，按特定频率和莫尔斯电码区分、隐蔽发射信号的“狐狸”电台。</p>
            <p></p>
        </div>
    </div>

    <div class="project-card">
        <a href="https://tgoe-1.github.io/car/" class="project-title">智能小车</a>
        <div class="project-image-container">
            <img src="./picture/智能小车.jpg" alt="智能小车">
        </div>
        <div class="project-description">
            <p>智能循迹小车是能自动识别并沿预设路径（黑线）行驶的机器人，具备避障与远程控制功能。</p>
            <p></p>
        </div>
    </div>

    <div class="project-card">
        <a href="https://your-project4-link.com" class="project-title">测向机</a>
        <div class="project-image-container">
            <img src="./picture/侧向机.jpg" alt="测向机">
        </div>
        <div class="project-description">
            <p>测向机是测定无线电波来波方向的专用接收设备，是无线电测向系统的终端。</p>
            <p></p>
        </div>
    </div>

</div>






如果您对我们的工作感兴趣，欢迎随时联系课题组负责人，郭丁丁老师：[郭丁丁老师主页](https://gddinhapend.github.io/gddresume/)
