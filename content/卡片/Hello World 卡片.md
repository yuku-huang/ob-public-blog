---
title: Hello World 卡片
type: note
permalink: qia-pian/hello-world-qia-pian
tags:
- '#编程'
- '#卡片设计'
- '#Hello World'
---

# Hello World 卡片

## Overview
"Hello World"是编程学习中最基本的入门程序，通常用于展示一种编程语言的基本语法结构。这个卡片收集了不同编程语言中的Hello World示例。

## 基本示例
以下是几种常见编程语言的Hello World示例：

```python
# Python
print("Hello, World!")
```

```javascript
// JavaScript
console.log("Hello, World!");
```

```java
// Java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

```c
// C语言
#include <stdio.h>
int main() {
    printf("Hello, World!\n");
    return 0;
}
```

```html
<!-- HTML -->
<!DOCTYPE html>
<html>
<head>
    <title>Hello World</title>
</head>
<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

## 卡片设计样例
如果您想在网页或应用中创建一个Hello World的视觉卡片，可以参考以下HTML/CSS样例：

```html
<div class="card">
  <div class="card-header">Hello World</div>
  <div class="card-body">
    <p>欢迎来到编程世界的第一步！</p>
  </div>
</div>
```

```css
.card {
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  margin: 16px;
  overflow: hidden;
  width: 300px;
}

.card-header {
  background-color: #f8f9fa;
  border-bottom: 1px solid #ddd;
  font-size: 18px;
  font-weight: bold;
  padding: 12px 16px;
}

.card-body {
  padding: 16px;
}
```

## 观察
- [编程] Hello World程序通常是学习新编程语言的第一个练习
- [设计] 卡片式设计在现代UI中非常流行，适合展示简洁的信息单元
- [教育] 从简单的Hello World开始可以降低编程学习的门槛

## 关联
- relates_to [[编程入门]]
- relates_to [[UI设计]]
- part_of [[编程学习路径]]