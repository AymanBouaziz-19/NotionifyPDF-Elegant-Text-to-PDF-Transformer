# 🧠 NotionifyPDF — Elegant Text-to-PDF Transformer  
by **Ayman Bouaziz** · CS Student at *Faculté des Sciences et Techniques de Al Hoceima* 🇲🇦  

> “Because your notes deserve to look as smart as you are.”  

---

## 🌟 Overview  
**NotionifyPDF** is a sleek Python tool that converts plain `.txt` modules or lessons into **Notion-styled academic PDFs** — combining minimal aesthetics with powerful layout logic.  
It uses the `reportlab` library to generate beautiful, structured PDFs with clean typography, smart code highlighting, and intuitive spacing — all inspired by Notion’s design system.

This project isn’t just about PDF creation —  
It’s about **turning learning materials into digital art.** ✨  

---

## 🎨 Features  

✅ **Notion-inspired layout** — clean fonts, soft colors, and minimal spacing  
✅ **Automatic headings detection** — transforms lesson sections into titles and subtitles  
✅ **Code block recognition** — detects “Copy Code” parts and formats them beautifully  
✅ **Academic typography** — Arial + Monospace fonts for readable elegance  
✅ **Instant transformation** — turn any `.txt` module into a polished `.pdf`  

---

## ⚙️ How It Works  

Just drop a `.txt` file (for example `Module_lesson.txt`) into your project folder and run:

```bash
python notion_style_variables_pdf.py
````

That’s it.
The script will automatically parse your text, identify sections, code blocks, and headings,
then produce a PDF named **`Module_NotionStyle.pdf`** with clean Notion-like visuals.

---

## 🧩 Example Input

**Module_lesson.txt**

```
1. Introduction
Variables in Python are used to store data.

Copy Code
x = 10
name = "Ayman"

2. Explanation
Python automatically assigns the data type.
```

**Result:**
A professional Notion-style PDF with clear titles, smooth paragraphs, and formatted code blocks.

---

## 🧰 Tech Stack

* 🐍 **Python 3**
* 🖋️ **ReportLab** — for PDF generation
* 🎨 **Custom Stylesheet System** — inspired by Notion & academic writing
* 🔤 **Inter & Monospace Fonts** — for perfect readability

---

## 🧑‍💻 For Developers

Want to customize it?
You can easily edit font colors, margins, or heading styles here:

```python
add_style_safe('BodyTextNotion', fontSize=12, textColor=colors.HexColor("#333"))
```

It’s all pure Python — no HTML, no LaTeX, just elegant, readable code.

---

## 🧠 Why I Built This

I wanted a way to convert my **computer science notes** into PDFs that look clean, organized, and professional — just like Notion.
So I created **NotionifyPDF**, where academic structure meets aesthetic simplicity.

> “A beautiful note makes learning more enjoyable — and that’s what inspired this tool.”

---

## 🏆 Future Plans

🪶 Add support for **Markdown input**
🌈 Add **theme customization** (light/dark mode)
🧾 Export directly from a **Notion page** via API
🔗 Integrate with **AI summarization** for lessons

---

## 👨‍🎓 About the Creator

**Ayman Bouaziz**
💻 CS Student at *Faculté des Sciences et Techniques de Al Hoceima*
🌍 Passionate about code, creativity, and human-centered design
🔗 [LinkedIn](https://www.linkedin.com/in/ayman-bouaziz-7ab181349) · [GitHub](https://github.com/aymanbouaziz-19)

---

## 💫 Final Words

> “Don’t just learn — create something that looks like learning.”
> — *Ayman Bouaziz*

⭐ If you like this project, give it a **star** on GitHub!
Your support helps turn more ideas into beautiful code 💡
