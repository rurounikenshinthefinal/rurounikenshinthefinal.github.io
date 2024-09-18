---
title: "그래프2"
date: 2023-11-26T16:36:24+08:00
draft: false
description: "Mermaid로 그래프 그리기 예시"
noindex: false
featured: true
pinned: false
# comments: false
series:
 - 예시
categories:
 - 내용
tags:
 - 그래프
 - Mermaid
images:
  - https://example-images.razonyang.com/flowchart.webp?width=1920&height=1280
authors:
  - HB
  - HugoMods
---

## 使用 Mermaid 代码块

````markdown
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
````

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## 使用 Mermaid 短代码

```markdown
{{</* mermaid */>}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{</* /mermaid */>}}
```

{{< mermaid >}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{< /mermaid >}}

## 延伸阅读

- [Mermaid 官网](https://mermaid.js.org/)
- [Hugo Mermaid 模块](https://hugomods.com/docs/content/mermaid/)
