# 第三方来源与许可

墨忆自己的界面、文案、图表和交互代码由项目作者编写。以下部分来自公开项目，按原许可使用。

## 词表数据

- 项目：**qwerty-learner**
- 仓库：<https://github.com/RealKai42/qwerty-learner>
- 许可：**GNU General Public License v3.0**
- 使用方式：从公开词典中提取单词、音标、释义，统一格式、去重并重新排序，生成 `data.js`。
- 版权：Copyright (c) qwerty-learner contributors。

qwerty-learner 的完整许可文本见本项目根目录的 [LICENSE](LICENSE)（GPL-3.0）。因为 `data.js` 是派生数据，本项目整体按 GPL-3.0 发布。

## FSRS 算法

- 项目：**Free Spaced Repetition Scheduler**
- 仓库：<https://github.com/open-spaced-repetition/free-spaced-repetition-scheduler>
- 许可：**MIT License**
- 使用方式：参考 FSRS-6 的调度公式与默认参数，在 `engine.js` 中独立实现；没有直接复制其源代码。
- 版权：Copyright (c) 2022 open-spaced-repetition-scheduler。

```text
MIT License

Copyright (c) 2022 open-spaced-repetition-scheduler

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 参考阅读

- 墨墨记忆算法文档：<http://memodocs.maimemo.com/docs/algorithm-intro>
- FSRS 算法 wiki：<https://github.com/open-spaced-repetition/awesome-fsrs/wiki/The-Algorithm>

墨忆不是墨墨官方产品，也不包含墨墨的界面素材、发音或私有数据。