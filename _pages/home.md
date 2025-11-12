---
layout: home
author_profile: true
permalink: /
---

<!-- 顶部通栏导航条 CSS -->
<style>
/* 导航栏容器：顶部通栏 + 固定背景 */
.site-header .main-navigation,
.main-nav,
.nav-container {
  width: 100% !important;
  margin: 0 !important;
  padding: 0 !important;
  background-color: #2c3e50 !important; /* 导航栏背景色（深灰蓝，专业沉稳） */
  box-shadow: 0 2px 4px rgba(0,0,0,0.1) !important; /* 轻微阴影，增加层次感 */
}

/* 导航列表：水平填满 + 居中 */
.site-header .main-navigation ul,
.main-nav ul,
.nav-container ul,
.nav,
.nav-list,
.menu {
  list-style: none !important;
  padding: 0 !important;
  margin: 0 auto !important;
  display: flex !important;
  flex-wrap: nowrap !important; /* 不换行（小屏幕自动适配） */
  justify-content: center !important; /* 水平居中 */
  align-items: center !important; /* 垂直居中 */
  max-width: 1200px !important; /* 限制最大宽度，避免过宽 */
}

/* 导航项样式：融入导航栏 */
.site-header .main-navigation ul li,
.nav-list li,
.menu li {
  margin: 0 !important;
  padding: 0 !important;
}

/* 导航链接样式：无按钮感，融入通栏 */
.site-header .main-navigation ul li a,
.nav-list li a,
.menu li a {
  text-decoration: none !important;
  padding: 16px 24px !important; /* 上下内边距（控制导航栏高度），左右间距 */
  color: #ecf0f1 !important; /* 文字颜色（浅灰白） */
  font-size: 15px !important;
  font-weight: 500 !important;
  display: block !important;
  transition: background-color 0.3s ease !important; /* 悬停过渡动画 */
}

/* 鼠标悬停 + 当前页激活样式 */
.site-header .main-navigation ul li a:hover,
.nav-list li a:hover,
.site-header .main-navigation ul li a.active,
.nav-list li a.active {
  background-color: #3498db !important; /* 悬停背景色（亮蓝） */
  color: white !important;
}

/* 小屏幕响应式适配（避免挤压） */
@media (max-width: 768px) {
  .site-header .main-navigation ul,
  .nav-list {
    flex-wrap: wrap !important; /* 小屏幕自动换行 */
  }
  .site-header .main-navigation ul li a,
  .nav-list li a {
    padding: 12px 18px !important; /* 缩小内边距 */
    font-size: 14px !important;
  }
}

/* 调整首页内容与导航栏间距（避免紧贴） */
.page-content {
  margin-top: 20px !important;
}
</style>

## 关于我

我是天津医科大学医学技术学部医学影像学专业大四在读学生，专注医学影像处理与创新实践，具备扎实的专业基础和团队协作能力。

### 基本信息
- **姓名**：韩佳宁 | **性别**：男 | **出生日期**：2003年10月29日
- **籍贯**：河北唐山 | **联系电话**：13877132729
- **教育背景**：天津医科大学医学影像学专业 本科在读（2021-2025）

### 学业与技能
- **学业排名**：2024-2025学年 智育成绩4/31，综合成绩4/31
- **英语能力**：CET-4 610分，CET-6 564分，具备学术文献阅读与口语交流能力
- **专业技能**：掌握医学影像基础分析方法，熟练使用Microsoft Office、WPS等办公软件，具备团队协作与项目组织能力

### 获奖与成果
- **学术奖项**：
  - 2024年 天津医科大学校级二等奖学金
  - 2024年 中国国际大学生创新大赛 校级银奖（第四作者）、校级铜奖5次（第二/三作者）
  - 2024年 天津市大学生化学竞赛 个人理论知识竞赛三等奖
  - 2023年 中国国际大学生创新大赛 校级铜奖（团队负责人）
- **其他成果**：软件著作权1件
- **文体奖项**：2024年天津医科大学游泳比赛男子50m仰泳第三名

### 校园经历
- 2024-2025学年 医学影像学专业 学生信息站 站长
- 2021-至今 22影像班 学习委员
- 2022-2024学年 医学影像学专业促进会 权益联络部 干事
