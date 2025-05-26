---
title: "Sample Hugo Test Page"
date: 2025-05-26T10:00:00-00:00
draft: false
author: "Test Author"
description: "A comprehensive test page for Hugo website development"
tags: ["hugo", "markdown", "test", "web-development"]
categories: ["Development", "Testing"]
featured_image: "/images/sample-image.jpg"
---

# Welcome to This Test Page

This is a comprehensive test page for your Hugo website. It includes various Markdown elements and Hugo-specific features to help you verify that everything is working correctly.

## Text Formatting

Here's some **bold text** and *italic text*. You can also use ***bold and italic*** together. For inline code, use `backticks` like this.

### Strikethrough and Other Elements

~~This text is struck through~~

> This is a blockquote. It's useful for highlighting important information or quotes from other sources.

## Lists

### Unordered List
- First item
- Second item with a [link to Hugo documentation](https://gohugo.io/documentation/)
- Third item
  - Nested item
  - Another nested item

### Ordered List
1. First numbered item
2. Second numbered item
3. Third numbered item
   1. Nested numbered item
   2. Another nested numbered item

## Code Blocks

Here's a code block with syntax highlighting:

```javascript
function greetVisitor(name) {
    console.log(`Welcome to our Hugo site, ${name}!`);
    return `Hello, ${name}!`;
}

greetVisitor("Developer");
```

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello from Hugo!")
}
```

## Tables

| Feature | Status | Notes |
|---------|--------|-------|
| Markdown | ✅ Working | All basic features supported |
| Syntax Highlighting | ✅ Working | Multiple languages supported |
| Tables | ✅ Working | Clean formatting |
| Images | 🔄 Testing | Check image paths |

## Images

![Sample Image Alt Text](/images/sample-image.jpg "Sample Image Title")

*Note: Make sure your image paths are correct for your Hugo setup*

## Hugo Shortcodes

If you have custom shortcodes, you can test them here:

{{< youtube "dQw4w9WgXcQ" >}}

{{< figure src="/images/sample.jpg" title="Sample Figure" caption="This is a sample figure caption" >}}

## Math (if MathJax/KaTeX is enabled)

Inline math: $E = mc^2$

Block math:
$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$

## Custom HTML (if allowed)

<div class="custom-alert">
    <strong>Note:</strong> This is custom HTML content. Make sure your Hugo configuration allows raw HTML if needed.
</div>

## Metadata Testing

This page includes various front matter fields that you can use to test:
- Title and description for SEO
- Tags and categories for taxonomy
- Author information
- Featured images
- Publication date

## Links and References

- [Hugo Official Website](https://gohugo.io/)
- [Hugo Documentation](https://gohugo.io/documentation/)
- [Markdown Guide](https://www.markdownguide.org/)

## Horizontal Rule

---

## Final Notes

This test page should help you verify that:
1. Your Hugo site builds correctly
2. Markdown rendering works as expected
3. Front matter is processed properly
4. Any custom styling is applied correctly
5. Navigation and taxonomy features work

Feel free to modify this content to match your specific testing needs!

---

*Last updated: May 26, 2025*