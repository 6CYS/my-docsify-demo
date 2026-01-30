# 前端开发

> 前端技术栈学习笔记

## JavaScript

### 基础概念

```javascript
// ES6+ 特性
const greeting = (name) => {
  return `Hello, ${name}!`;
};

// 解构赋值
const { a, b } = { a: 1, b: 2 };

// 异步函数
async function fetchData() {
  const response = await fetch('/api/data');
  return response.json();
}
```

### 最佳实践

1. 使用 `const` 和 `let` 代替 `var`
2. 使用模板字符串进行字符串拼接
3. 善用解构赋值简化代码
4. 使用 async/await 处理异步操作

## CSS

### Flexbox 布局

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
```

### Grid 布局

```css
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
```

## 推荐资源

- [MDN Web Docs](https://developer.mozilla.org)
- [JavaScript.info](https://javascript.info)
- [CSS-Tricks](https://css-tricks.com)
