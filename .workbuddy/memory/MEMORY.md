# 长期记忆 - TGB 户外家具网站

## 项目基本信息
- **网站名称**：TGB 户外家具
- **本地文件路径**：c:\Users\Lenovo\WorkBuddy\20260409174735\（工作目录）和 c:\Users\Lenovo\Desktop\tgb-website（原始备份）
- **品牌色**：深森林绿 (#1a3a2f) + 金色 (#c9a962)
- **默认语言**：中文，支持中英文切换
- **线上地址**：https://shusan0817.github.io/tgb-website/（GitHub Pages）
- **GitHub**：shusan0817 / tgb-website

## 图片/视频文件映射
images 文件夹内的英文文件名对应关系：
- img01.png~img13.png，video01.mp4（均已重命名自微信中文文件名）
- 视频封面图：images/img12.png

## 已完成的主要功能
1. 核心页面（Hero、产品展示、Gallery展示区、工艺认证、会员体系）
2. Gallery区：6个工艺认证卡片 + 视频展示 + 3×3图片网格
3. 3级会员体系展示
4. 中英文切换功能
5. 移动端响应式布局
6. **PPT内容完整整合**（合兴公司简介27页PPT全部内容已映射到网站）
   - About区：公司发展时间线 + 工厂分布 + 合作优势 + 团队介绍 + 产品分类
   - Clients区：核心客户展示（Lowes/Michaels/Home Depot等）
   - Craft区：工艺特色 + 认证展示
   - **Process区（新增）**：12步端到端生产工艺流程 + 6项实验室测试设备
   - Cambodia Factory区：柬埔寨新工厂详细规格

## 近期修改记录
- 2026-04-12：将所有中文文件名重命名为英文，修复 Netlify/GitHub 404 问题
- 2026-04-12：从 Netlify 迁移至 GitHub Pages 部署
- 2026-04-13：**移除视频上的英文字幕叠加层**（`.video-overlay` div 及相关 CSS），让 Gallery 视频播放界面更简洁
- 2026-04-16：**新增生产工艺流程板块**（`#process`），整合PPT第13-19页的端到端制造流程和测试实验室展示
- 2026-04-17：**修复移动端字体溢出和布局问题**
- 2026-04-17：**将单页网站拆分为6个独立页面**（index.html首页 + about.html + products.html + craft.html + process.html + gallery.html），导航栏统一链接到各独立页面（全局 break-word、clamp() 响应式字号、Process 改为网格布局、Cambodia/Timeline/Clients 字号适配、Lightbox nowrap 修复等）

## 用户偏好
- 简洁直接，用"ok了"确认任务完成
- 遇到技术问题让 AI 处理，部署可以让 AI 帮忙 push
- 顺序迭代式工作流程
- 本地预览命令：`python -m http.server 8080`（在工作目录执行）
