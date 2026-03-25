Generate a complete GitHub-ready Markdown documentation structure for the following topic:

TOPIC: [Paste your topic here]
STAGES / SECTIONS: [List your main stages or sections here]

---

Requirements:

1. Create a MAIN TABLE OF CONTENTS at the top:

* Use internal anchor links (e.g., #section-name)
* Format:

  * [Section Name](#anchor-id)

---

2. For EACH stage/section:

* Create a section header using:

## 📘 Section Name <a id="anchor-id"></a>

* Automatically generate clean anchor IDs:

  * Lowercase
  * Replace spaces with hyphens
  * Remove special characters

---

3. If a section has subtopics:

* Create a SUB TABLE OF CONTENTS under that section
* Format:

  # 📚 Table of Contents

  * [Subtopic](#subtopic-anchor)

---

4. For each subtopic:

* Use:

### X.X Subtopic Name <a id="anchor-id"></a>

---

5. Maintain proper hierarchy:

* `#` → main title
* `##` → main sections
* `###` → subsections

---

6. Ensure:

* All links are clickable and correct
* No broken anchors
* GitHub-compatible Markdown
* Clean spacing and formatting

---

7. Add optional final sections if relevant:

# 🔥 FINAL FLOW <a id="final-flow"></a>

# 🧠 PRO INSIGHT <a id="pro-insight"></a>

---

8. Output ONLY Markdown. No explanations.

---

Example Input:

TOPIC: Ethical Hacking
STAGES:
0. Pre-Engagement (Planning & Legal)

1. Passive Reconnaissance (OSINT)
2. Active Reconnaissance

Subtopics for Stage 0:
0.1 Engagement Overview
0.2 Legal Authorization

---

Now generate the full structured Markdown document.
