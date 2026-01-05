<!-- README.html -->
<h1>Sales Analysis Dashboard | SQL + Power BI</h1>
<h2>Skills Demonstrated</h2>
<p>
  SQL • Data Modeling • Power BI • DAX • KPI Design • Business Analytics
</p>

<h2>Overview</h2>
<p>
  End-to-end sales analytics project built from a real business request.
  The goal was to replace static Excel reports with <strong>interactive Power BI dashboards</strong> that help Sales teams
  <strong>track performance</strong>, identify <strong>top customers/products</strong>, and compare <strong>sales vs budget</strong>.
</p>

<hr />

<h2>Business Problem</h2>
<ul>
  <li>Limited visibility into <strong>which customers and products drive revenue</strong></li>
  <li>Manual Excel reporting made analysis and follow-ups slow</li>
  <li>Hard to track <strong>performance vs budget</strong></li>
  <li>No self-serve filtering for Sales users</li>
</ul>

<h2>Key Questions Answered</h2>
<ul>
  <li>How are <strong>internet sales performing over time</strong>?</li>
  <li>Are we <strong>over or under budget</strong>?</li>
  <li>Who are the <strong>top customers</strong> and <strong>top products</strong>?</li>
  <li>Which <strong>categories</strong> and <strong>regions</strong> generate the most sales?</li>
</ul>

<h2>Impact</h2>
<ul>
  <li>Enables faster, data-driven sales decisions</li>
  <li>Helps prioritize high-value customers and products</li>
  <li>Improves budget accountability via clear KPIs</li>
  <li>Reduces dependency on manual Excel analysis</li>
</ul>

<h2>How It Was Built</h2>
<ul>
  <li>Translated user stories into a <strong>star-schema</strong> data model (dimensions + facts)</li>
  <li>Cleaned and transformed data in <strong>SQL</strong> (joins, CASE logic, null handling)</li>
  <li>Built explicit relationships in <strong>Power BI</strong> (single-direction filtering)</li>
  <li>Created core KPIs in <strong>DAX</strong>:
    <ul>
      <li>Total Sales</li>
      <li>Total Budget</li>
      <li>Sales vs Budget (Variance)</li>
      <li>Sales / Budget (%)</li>
    </ul>
  </li>
  <li>Designed dashboards for clarity and self-serve exploration</li>
</ul>
<h2>Trade-offs & Assumptions</h2>
<ul>
  <li>Assumed <strong>Internet Sales</strong> as the primary revenue source based on business request</li>
  <li>Filtered data to the <strong>last two years</strong> to align with reporting relevance and performance</li>
  <li>Handled missing categorical values using <strong>business-friendly defaults</strong> instead of dropping records</li>
  <li>Used <strong>single-direction relationships</strong> to avoid ambiguous filtering and improve model stability</li>
  <li>Prioritized <strong>clarity and usability</strong> over advanced visuals to support self-serve analysis</li>
</ul>


<h2>Dashboards</h2>
<ul>
  
  <li><strong>Sales Overview</strong> – KPIs, Sales vs Budget trend, Top 10 Customers/Products, Map</li>
  <li><strong>Customer Details</strong> – Customer-level performance with time filtering</li>
  <li><strong>Product Details</strong> – Product/category-level breakdown</li>
</ul>
<p><em>Tip:</em> Add screenshots in <code>/assets</code> and link them below.</p>

<h3>Screenshots</h3>
<ul>
  <p align="center">
  <img src="Images/data model.png" alt="Fig 1: Data Model" width="500"/><br>
  <em>Figure 1: Data Model</em>
  </p>
  <p align="center">
  <img src="Images/sales overview.png" alt="Fig 2: Sales Overview" width="500"/><br>
  <em>Figure 2: Sales Overview</em>
  </p>
  <p align="center">
  <img src="Images/customer details.png" alt="Fig 3: Customer Details" width="500"/><br>
  <em>Figure 3: Customer Details</em>
  </p>
  <p align="center">
  <img src="Images/product details.png" alt="Fig 4: Product Details" width="500"/><br>
  <em>Figure 4: Product Details</em>
  </p>
  
</ul>

<h2>What I’d Improve Next</h2>
<ul>
  <li>Add <strong>incremental refresh</strong> and scheduled refresh for larger datasets</li>
  <li>Introduce <strong>row-level security (RLS)</strong> for role-based access (Sales Rep vs Manager)</li>
  <li>Enhance trend analysis with <strong>YoY / MoM growth metrics</strong></li>
  <li>Add <strong>drill-through pages</strong> for deeper customer and product analysis</li>
  <li>Optimize model performance using <strong>aggregation tables</strong> for scalability</li>
</ul>


