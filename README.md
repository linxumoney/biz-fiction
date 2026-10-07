# 📖 Biz Fiction — 商业叙事写作引擎

> 用写小说的方式写商业故事。让读者忘记自己在读「内容」，以为自己在看剧。

给我一个真实商业人物/事件，我输出 3000-5000 字的沉浸式叙事长文。

---

## ✨ 触发示例

```
/biz-fiction 中本聪与比特币诞生
/biz-fiction 张一鸣离开字节的那个下午
/biz-fiction 雷军第一次创业失败
/biz-fiction 马斯克收购 Twitter 的那个周末
```

---

## 🎬 核心写作法则

这套 Skill 提炼自真实的商业非虚构叙事，核心是7条写作法则：

### 1. 镜头三层切换
```
宏观（城市/天气）→ 中景（房间/人物）→ 微观（杯底冰块/屏幕反光）
```
微观镜头承载情绪，不直说感受，让细节说话。

### 2. 情绪不说，细节说
- ❌ 「他感到不安」
- ✅ 「他读了三遍。字面上每一个字都很正常，但他的心跳还是快了半拍。」

### 3. 对话永远有两层意思
表面意思 + 真实意思错位。读者在结局处猛然回想：「原来那句话早就是预兆。」

### 4. 商业信息一句话带过
不分析，不展开。事实 → 外部反应 → 主角判断，三句话搞定。

### 5. 人物用轨迹建立
不写成就，写动词轨迹。出生地越具体越有力，最后制造落差感。

### 6. 标准六章结构
引子 → 犹豫 → 决定 → 过程 → 转折 → 夜/余震

### 7. 结尾不给结论
最后一个具体画面，把判断权留给读者。

---

## 📁 文件结构

```
biz-fiction/
├── SKILL.md                      ← Claude Code skill 主文件
└── references/
    ├── style-rules.md            ← 完整写作法则（含大量正反例）
    ├── scene-templates.md        ← 开场/转折/结尾场景模板
    └── character-sheet.md        ← 人物建立方法
```

---

## 🚀 安装

```bash
git clone https://github.com/linxumoney/biz-fiction.git ~/.claude/skills/biz-fiction
```

然后在 Claude Code 中：
```
/biz-fiction 中本聪与比特币诞生
```

---

## 📡 关注我

这是「**[林序聊AI · 开源计划](https://github.com/linxumoney)**」的开源项目之一。

| 平台 | 链接 |
|------|------|
| 🐦 X (Twitter) | [@linxumoney](https://x.com/linxumoney) |
| 📺 YouTube | [@LinXuMoney](https://www.youtube.com/@LinXuMoney) |
| 💻 GitHub | [github.com/linxumoney](https://github.com/linxumoney) |

觉得有用的话，**点个 Star ⭐ 支持一下**。

---

## 📄 License

MIT License with Attribution — 可自由使用修改，须注明原作者：Lin Xu @linxumoney

---

## 📝 输出示例

| 示例 | 文件 |
|------|------|
| 中本聪 · 消失 | [examples/nakamoto.md](examples/nakamoto.md) |
| 埃隆·马斯克 · 那条推文 | [examples/musk.md](examples/musk.md) |

## 商业授权

个人学习、研究、测试和非商业使用可以。商业使用请先联系 **linxu.money@gmail.com** 获得授权，详见 [COMMERCIAL-LICENSING.md](COMMERCIAL-LICENSING.md)。

