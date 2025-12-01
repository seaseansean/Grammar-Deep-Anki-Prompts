Grammar-Deep-Anki-Prompts
AI Prompts for generating grammar-deep Anki cards. Supports Russian (and easily adaptable to German/Latin/Slavic languages)
# Grammar-Deep Anki Prompts

[![GitHub Stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO_NAME?style=social)](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/stargazers)
[![License](https://img.shields.io/github/license/YOUR_USERNAME/YOUR_REPO_NAME)](LICENSE)

一个用于生成**语法深度解析** Anki 卡片的 AI 提示词（Prompt）集合。本项目专为俄语、德语等**强变格变位语言**的学习者设计，旨在利用 LLM 自动化生成最困难的语法细节，大幅提高词汇学习效率。



##  核心 (Why This Prompt?)

传统的 Anki 笔记侧重于单词和释义。本Prompt的核心在于**自动深度分析**，解决了复杂语言学习中的几大问题：
* **快速便捷（Quick and convenient）**：如果说不借助AI工具，自己通过在线字典查阅，制作Flashcard非常耗时，通常1分钟才能做好一张
* **格位 (Case Tracking):** 自动解析例句中名词和形容词的**格位**（如俄语的六格、德语的四格），标注原形和变格后的形式。
* **复数&变格体（Plural/Case forms）:** 为名词提供复数形式，为形容词提供性数形式，为动词提供完整的**变位表和体 (Aspect)**。
* **例句难度自由设置（A1-C2）：** 确保例句难度适中，便于理解和应用。

---

##  如何使用 (Getting Started)

1.  **选择提示词：** 根据您的 AI 平台语言偏好，复制 `prompt_russian_en.md` 或 `prompt_russian_cn.md` 的内容。
2.  **粘贴指令：** 将内容粘贴到您的大型语言模型（LLM）平台上（如 GPT-4,Gemini,Deepseek中），，推荐一开始‘’深度思考‘’，之后为了节约时间提高效率可以不用选择‘’深度思考‘’。
3.  **输入单词：** 在指令下方输入您想学习的俄语单词（无上限）。
4.  **导入 Anki：** 将 AI 输出的结构化文本复制到 Anki 字段中。

---

## 📊 效果演示 (Demo Screenshot)

以下是使用本 Prompt 生成的 Anki Flashcard 效果图。

### 名词示例
![Anki Flashcard 示例-名词](images/Anki_demo_noun.png)

### 动词示例
![Anki Flashcard 示例-动词](images/Anki_demo_verb.png)

### 形容词示例
![Anki Flashcard 示例-形容词](images/Anki_demo_adj.png)
```markdown
