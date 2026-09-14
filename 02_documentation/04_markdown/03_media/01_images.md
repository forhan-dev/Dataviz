### 🖼️ Markdown Images  

Images in Markdown let you embed visuals directly into your documentation. They are equivalent to `<img>` tags in HTML but use a simpler syntax.  

---

## 🔑 Syntax  

```markdown
![Python Logo](https://code.visualstudio.com/assets/home/extension-python.png)
```

- `Python Logo` → description of the image (important for accessibility).  
- `https://code.visualstudio.com/assets/home/extension-python.png` → path or URL to the image.  

**Output:**  

![Python Logo](https://code.visualstudio.com/assets/home/extension-python.png)  

---

## 📊 Reference-Style Images  

You can also define images separately for cleaner Markdown:  

```markdown
![Python Logo][py]

[py]: https://code.visualstudio.com/assets/home/extension-python.png
```

**Output:**  

![Python Logo][py]

[py]: https://code.visualstudio.com/assets/home/extension-python.png

---

## 🌟 Best Practices  

- **Use alt text** for accessibility and clarity.  
- **Use relative paths** for internal resources.  
- **Use URLs** for external resources.  
- Keep images **small and relevant** — don’t overload documentation.  

---