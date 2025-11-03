# 👋 Hi, I'm Ancy Sneha A  

**Aspiring Data Analyst | Migration Specialist | .NET Developer**

Welcome to my data portfolio!  
I turn raw data into insights, dashboards, and stories that drive smarter decisions.

![Profile](./assets/profile.jpg)

---

## 🚀 Explore My Work

<div align="center">

| Category | Description |
|:--:|:--|
| [📊 Dashboards](dashboard.md) | Interactive Power BI and Tableau dashboards built to visualize KPIs and business insights. |
| [🎤 Presentations](presentation.md) | Data storytelling and reports that communicate insights clearly and visually. |

</div>

---

⭐ *“Transforming data into stories that inspire action.”*
/* assets/styles.css */

/* Basic page layout */
:root{
  --bg: #0f1724;
  --card: #0b1220;
  --muted: #98a0b3;
  --accent: #6ee7b7;
  --glass: rgba(255,255,255,0.03);
  --max-width: 980px;
  --radius: 12px;
  --shadow: 0 8px 24px rgba(3,7,18,0.6);
  --glass-border: rgba(255,255,255,0.04);
}

*{box-sizing:border-box}
html,body{
  margin:0;
  padding:0;
  height:100%;
  font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  background: linear-gradient(180deg,#071024 0%, #071833 60%);
  color: #ecf2ff;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  line-height:1.5;
}

/* container center */
main, .content {
  max-width: var(--max-width);
  margin: 36px auto;
  padding: 28px;
  background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  border: 1px solid var(--glass-border);
}

/* header */
h1{
  font-size: 2.1rem;
  margin: 0 0 8px 0;
  letter-spacing: -0.02em;
}
h2, h3 { color: #e6eefc; margin-top:1.4rem }
p.lead {
  color: var(--muted);
  margin: 6px 0 18px 0;
  font-size: 1rem;
}

/* profile image */
img[src*="profile"]{
  width:120px;
  height:120px;
  object-fit:cover;
  border-radius: 50%;
  border: 3px solid rgba(255,255,255,0.06);
  box-shadow: 0 6px 18px rgba(5,10,20,0.6);
  display:block;
  margin: 14px 0 22px;
}

/* category table -> make it look like cards */
table {
  width:100%;
  border-collapse: separate;
  border-spacing: 12px;
  margin: 8px 0 24px 0;
}
td, th {
  vertical-align: middle;
  padding: 0;
}

/* transform each table cell into a card */
table tr td:first-child,
table tr th:first-child {
  width: 42%;
}
table tr td:last-child,
table tr th:last-child {
  width: 58%;
}

/* card style */
.card {
  display:flex;
  align-items:center;
  gap:16px;
  padding: 14px;
  background: linear-gradient(180deg, rgba(255

