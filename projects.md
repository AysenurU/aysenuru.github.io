---
layout: page
title: Projects
---

<style>
/* Container for all cards */
.cards-container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
  margin-top: 20px;
}

/* Individual card */
.card {
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  width: 300px;
  padding: 20px;
  transition: transform 0.3s, box-shadow 0.3s;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}

/* Card image */
.card img {
  width: 100%;
  border-radius: 8px;
  margin-bottom: 15px;
}

/* Card title */
.card h3 {
  margin: 0 0 10px 0;
  font-size: 1.3rem;
  text-align: center;
}

/* Card description */
.card p {
  font-size: 0.95rem;
  text-align: center;
  color: #333;
  margin-bottom: 10px;
}

/* Skills / business value */
.card p.skills {
  font-size: 0.85rem;
  font-weight: 500;
  color: #555;
  margin-bottom: 15px;
}

/* Button link */
.card a {
  text-decoration: none;
  background-color: #007acc;
  color: white;
  padding: 8px 16px;
  border-radius: 6px;
  transition: background-color 0.3s;
}

.card a:hover {
  background-color: #005fa3;
}

/* Responsive */
@media (max-width: 768px) {
  .cards-container {
    flex-direction: column;
    align-items: center;
  }
  .card {
    width: 90%;
  }
}
</style>

<div class="cards-container">

  <!-- Project 1 -->
  <div class="card">
    <img src="https://via.placeholder.com/300x180.png?text=SQL+Data+Warehouse" alt="Sales Analytics Data Warehouse">
    <h3>Sales Analytics Data Warehouse</h3>
    <p>End-to-end SQL Server Data Warehouse project simulating a real-world analytics environment.</p>
    <p class="skills">Skills: SQL, Data Warehousing, Star Schema, KPI Metrics, Analytics Engineering, Data Quality</p>
    <a href="https://github.com/AysenurU/sql-data-warehouse-project" target="_blank">View Project</a>
  </div>

  <!-- Project 2 -->
  <div class="card">
    <img src="https://via.placeholder.com/300x180.png?text=Retail+Analytics+SQL" alt="End-to-End Retail Analytics">
    <h3>End-to-End Retail Analytics (SQL)</h3>
    <p>SQL Data Warehouse using Bronze-Silver-Gold architecture to transform CRM & ERP data into analytics-ready datasets and KPI views.</p>
    <p class="skills">Skills: SQL, Data Warehousing, Star Schema, KPI Metrics, CRM & ERP Integration, Analytics Engineering</p>
    <a href="https://github.com/AysenurU/end-to-end-retail-analytics-sql" target="_blank">View Project</a>
  </div>

</div>
