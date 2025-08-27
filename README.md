from pathlib import Path

# Create a short README.md content
readme_content = """
# 📊 Learning NumPy

This repository contains my hands-on practice with **NumPy**, the core library for numerical computing in Python.

I’ve worked on real questions to understand concepts like:
- Array creation and manipulation
- Indexing, slicing, and filtering
- Broadcasting and arithmetic operations
- Matrix operations and conditional updates

All solutions are written in a clean and beginner-friendly way.  
Feel free to explore, try the problems, or contribute!

🔗 Ideal for beginners who prefer learning by doing.

---

**Let’s connect and grow together!** 🚀
"""

# Save to README.md
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content.strip())

readme_path.name
