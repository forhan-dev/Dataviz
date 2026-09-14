### 💻 Markdown Code Blocks  

Code blocks in Markdown are used to display **formatted code snippets**. They preserve indentation, spacing, and syntax highlighting, making them essential for technical documentation.  

---

## 🔑 Types of Code Blocks  

- **Inline Code** → Wrap text with backticks `` ` ``  
  ```markdown
  Use `SELECT * FROM users;`
  ```  
  **Output:**   
  Use `SELECT * FROM users;`  

- **Fenced Code Blocks** → Use triple backticks ```` ``` ```` for multi-line code  
  ````markdown
  ```
  SELECT id, name
  FROM users
  WHERE active = true;
  ```
  ````

  **Output:**  
  ```
  SELECT id, name
  FROM users
  WHERE active = true;
  ```

  Fenced code blocks preserve:

  * Indentation
  * Line breaks
  * Spaces
  * Formatting
  * Code structure

- **Language-Specific Blocks** → Add language name after the opening backticks for syntax highlighting  
  ````markdown
  ```sql
  SELECT COUNT(*) FROM employees;
  ```
  ````

  **Output (with highlighting):**  
  ```sql
  SELECT COUNT(*) FROM employees;
  ```  

---

- Nested Code Blocks → Use four backticks ````` ```` ````` for the outer block  

  `````markdown
  ````markdown
  ```sql
  SELECT *
  FROM employees;
  ```
  ````
  `````

---

## 🌟 Best Practices  

- **Use inline code** for short commands or filenames.  
- **Use fenced blocks** for multi-line code.  
- Add a **language identifier** for syntax highlighting.  
- Keep code blocks **minimal and relevant** — avoid dumping entire scripts.  
- Combine with **headings** and **paragraphs** for context.  

---