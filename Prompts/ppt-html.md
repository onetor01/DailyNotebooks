---
key: 4grx57wq
---

# ppt-html

# Prompt: 生成可演示 HTML 幻灯片

## 输入

主题:  
时长: 分钟  
听众:  
核心观点:

## 输出

**一段完整的 HTML**(从 `<!DOCTYPE html>` 到 `</html>`)。要求:

- 单文件,所有 CSS / JS 内联,**严禁外部资源**
- 用 CSS `display:none` / `.active` 类做翻页,键盘 ← → Space 切换
- 顶部有进度条 `第 N / M 页`
- 每页布局:左上角小标题 + 中部 bullets + 底部 logo 占位
- 字号:标题 64px、要点 36px
- 配色:深底白字(#0E1116 / #FFFFFF)+ 品牌色强调(用 CSS 变量)
- 总页数 = ceil(minutes / 2)

&nbsp;