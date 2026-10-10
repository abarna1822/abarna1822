from pathlib import Path

readme = """<div align="center">

# Hi, I'm Abarna S 👋

### Full-Stack Developer | AI & Data Science Graduate

Building practical web applications, intelligent AI solutions, and data-driven products.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0A66C2?style=for-the-badge&logo=vercel&logoColor=white)](https://abarnas.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abarna--s/)
[![GitHub](https://img.shields.io/badge/GitHub-abarna1822-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abarna1822)

</div>

---

## 👩‍💻 About Me

- 🎓 B.Tech graduate in **Artificial Intelligence and Data Science**
- 💻 Interested in full-stack development, AI/ML, and data analytics
- 🤖 Building practical applications that address real-world problems
- 📊 Enjoy turning data into useful insights and interactive dashboards
- 🌱 Continuously learning and improving through hands-on projects

## 🧰 Tech Stack

### Languages & Web Development
<p>
  <img src="https://skillicons.dev/icons?i=python,js,html,css,react,flask" alt="Python, JavaScript, HTML, CSS, React and Flask icons" />
</p>

### AI, Machine Learning & Data Analytics

**Libraries and tools:** Scikit-learn, Pandas, NumPy, XGBoost, LightGBM, Prophet, SHAP, LIME, Plotly, Streamlit, Power BI

### Databases & Developer Tools
<p>
  <img src="https://skillicons.dev/icons?i=mysql,sqlite,git,github,vscode" alt="MySQL, SQLite, Git, GitHub and VS Code icons" />
</p>

## 🚀 Featured Projects

### 🩺 HepatoScan AI — Liver Cirrhosis Prediction
Machine-learning project focused on liver cirrhosis prediction, with explainability using SHAP and LIME and a Streamlit dashboard.

> Add the public repository link here after confirming the correct URL.

### 📈 Stock Forecasting Web App
A forecasting application using Python, Flask, XGBoost, and Prophet, with data upload and interactive visualizations.

[View repository](https://github.com/abarna1822/stock_forecasting_web)

### 📊 Institute Report Dashboard
Power BI dashboard for exploring institute data, student enrollment, and reporting insights.

[View repository](https://github.com/abarna1822/Institute_Report)

### 🛍️ ShopSphere
Web development project focused on an online shopping experience.

[View repository](https://github.com/abarna1822/Shop_sphere)

### 📉 Sales Report Dashboard
Data visualization project focused on sales and business performance.

[View repository](https://github.com/abarna1822/Sales_Report)

## 🤝 Connect With Me

- 🌐 **Portfolio:** https://abarnas.vercel.app/
- 💼 **LinkedIn:** https://www.linkedin.com/in/abarna--s/
- 🧑‍💻 **GitHub:** https://github.com/abarna1822

---

<div align="center">

*Build. Learn. Improve. Repeat.*

</div>
"""

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created {path} ({path.stat().st_size} bytes)")
