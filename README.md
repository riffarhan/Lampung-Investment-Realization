<!--
README.md (HTML mode)
Lampung Investment Realization Dashboard
-->

<div align="center" style="padding:22px 0 10px;">
  <h1 style="margin:0 0 6px;font-size:34px;line-height:1.15;">
    📊 Lampung Investment Realization Dashboard
  </h1>
  <p style="margin:0;color:#6a737d;">
    Data-driven decision support for Lampung Province (2023–2024)
  </p>

  <!-- 🔴 IMPORTANT NOTICE -->
  <div style="background:#fff3cd;color:#664d03;border:1px solid #ffeeba;border-radius:8px;padding:10px 16px;margin:14px 0;font-weight:600;max-width:600px;">
    ⚠️ This dashboard uses a <u>dummy dataset</u> for demonstration purposes only.  
    Figures do <u>not</u> represent actual investment data.
  </div>

  <div style="margin:12px 0 16px;display:flex;gap:8px;flex-wrap:wrap;justify-content:center;">
    <a href="https://public.tableau.com/shared/5HDHHKGJ9?:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener"
       style="display:inline-block;background:#0969da;color:#fff;border-radius:8px;padding:10px 14px;text-decoration:none;font-weight:600;">
      ▶️ View Live Dashboard (Tableau Public)
    </a>
    <a href="#-project-structure" style="display:inline-block;background:#f6f8fa;color:#24292f;border:1px solid #d0d7de;border-radius:8px;padding:10px 14px;text-decoration:none;font-weight:600;">
      📂 Project Structure
    </a>
    <a href="#-key-insights" style="display:inline-block;background:#f6f8fa;color:#24292f;border:1px solid #d0d7de;border-radius:8px;padding:10px 14px;text-decoration:none;font-weight:600;">
      💡 Key Insights
    </a>
  </div>

  <!-- Cover image -->
  <img src="assets/Dashboard_1.png" alt="Lampung Investment Dashboard Preview" style="max-width:1024px;width:100%;border:1px solid #d0d7de;border-radius:12px;">
</div>

<hr style="margin:28px 0 18px;border:none;border-top:1px solid #d8dee4;">

<h2 id="-highlights" style="margin-top:0;">🚀 Highlights</h2>
<ul>
  <li><b>KPI Overview</b> — Total realized investment, number of companies &amp; projects.</li>
  <li><b>Top Rankings</b> — Top-10/15 by <i>company</i>, <i>sector</i>, and <i>kabupaten/kota</i>.</li>
  <li><b>Interactive Filters</b> — Year, Region, Sector, and PMA/PMDN.</li>
  <li><b>Geo Distribution</b> — Map of investment concentration across Lampung.</li>
  <li><b>Detail Table</b> — Export-ready table following active filters.</li>
</ul>

<h2 id="-key-insights">📈 Key Insights (from dummy data)</h2>
<ul>
  <li><b>Total Investment (2023–2024):</b> Rp <i>20.55 Triliun</i> (dummy sample for demo).</li>
  <li><b>Composition:</b> PMDN ≈ 72% vs PMA ≈ 28%.</li>
  <li><b>Top District:</b> Kota Bandar Lampung; <b>Top Sector:</b> Industri Makanan.</li>
  <li><b>Standout contributors:</b> Sinar Pematang Mulia, Wika Beton, PLN (Persero), dlsb.</li>
</ul>

<h2 id="-tech-stack">🛠 Tech Stack</h2>
<table>
  <tr>
    <td><b>Visualization</b></td><td>Tableau Public</td>
  </tr>
  <tr>
    <td><b>Data Prep</b></td><td>Excel / Python (pandas)</td>
  </tr>
  <tr>
    <td><b>Mapping</b></td><td>Tableau Maps / Mapbox</td>
  </tr>
  <tr>
    <td><b>Data Source</b></td><td><b>Dummy dataset</b> (OSS/BKPM-like structure) for demonstration</td>
  </tr>
</table>

<h2 id="-project-structure">📦 Project Structure</h2>
<pre style="background:#f6f8fa;border:1px solid #d0d7de;border-radius:8px;padding:14px;overflow:auto;">
Lampung-Investment-Realization/
├── assets/
│   └
├── data/
│   ├── raw/                         
│   └── processed/                   
├── dashboard/
│   └── RealisasiInvestasi_Lampung.twbx
└── README.md
</pre>

<h2 id="-how-to-view">🔎 How to View</h2>
<ol>
  <li><b>Live (recommended):</b> <a href="https://public.tableau.com/shared/5HDHHKGJ9?:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener">Open on Tableau Public</a>.</li>
  <li><b>Local:</b> Download <code>.twbx</code> from <code>dashboard/</code> and open with Tableau Desktop.</li>
</ol>

<h2 id="-why-it-matters">🏛 Why It Matters</h2>
<p>
  This dashboard supports <b>RPJMD Lampung</b> priorities—accelerating investment, improving transparency,
  and enabling faster, evidence-based decisions across sectors and regions.  
  <b>Note:</b> All figures in this demo are fabricated for visualization purposes only.
</p>

<h2 id="-credits--license">📝 Credits &amp; License</h2>
<ul>
  <li>Built by <b>Tim Kajian Percepatan Pembangunan Provinsi Lampung</b> (demo dataset).</li>
  <li>License: <a href="LICENSE">MIT</a> — attribution appreciated.</li>
</ul>

<hr style="margin:24px 0;border:none;border-top:1px solid #d8dee4;">
<p align="center" style="color:#6a737d;">
  Made with ♥ for better, faster public policy in Lampung — dashboard for demonstration purposes.
</p>
