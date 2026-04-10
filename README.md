# RBTI — Research Behavior Type Indicator

> MBTI已经过时，SBTI不够学术，RBTI来了。

面向PhD群体的讽刺科研人格测试。用100个计算机/工科/商科术语命名你的科研灵魂。

**在线体验**: [rbti.picasso-lab.com](https://rbti.picasso-lab.com)（部署中）

---

## 这是什么？

一个用 θ ← θ - α∇L(θ) 收敛到100的梯度下降公式来暗示人格总数的科研人格测试。

20道少而精的题目，10个维度精准定位你的科研人格：理论vs应用、深度vs广度、独立vs协作、代码vs数学、质量vs数量、计划vs即兴、好奇vs功利、学术vs工业、抗压vs脆弱、社交vs独处。

还有5种隐藏人格等你触发。

## 技术架构

```
index.html    ← 单文件SPA（HTML+CSS+JS，零依赖）
image/        ← low-poly卡通PNG（Gemini API生成）
```

纯静态，Cloudflare Pages部署，支持百万级并发。

## 致谢

- **灵感来源**: SBTI ([sbti.picasso-lab.com](https://sbti.picasso-lab.com))
- **创作者**: [小红书@momo](https://xhslink.com/m/52DE56o07sG)
- **托管**: Cloudflare Pages
- **域名**: Squarespace

## License

仅供娱乐。别拿它当学术评估、招聘筛选或导师匹配的依据。
