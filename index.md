<style>
  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    background: linear-gradient(180deg, #f7fafc 0%, #edf3f8 100%);
    padding: 40px 20px;
    color: #0f172a;
  }

  a {
    color: #2563eb;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .hub-shell {
    max-width: 920px;
    margin: 0 auto;
    background: #ffffff;
    border: 1px solid #e6edf5;
    border-radius: 20px;
    box-shadow: 0 14px 36px rgba(15, 23, 42, 0.08);
    padding: 34px 28px;
  }

  .hero {
    text-align: center;
    padding-bottom: 26px;
    border-bottom: 1px solid #e8eef5;
  }

  .hero h1 {
    margin: 0;
    font-size: 3em;
    font-weight: 800;
    color: #0f172a;
    line-height: 1.1;
  }

  .hero p {
    margin: 14px auto 0;
    max-width: 760px;
    color: #334155;
    line-height: 1.7;
    font-size: 1.18em;
  }

  .section-card {
    margin-top: 20px;
    border: 1px solid #e3ebf5;
    border-radius: 16px;
    overflow: hidden;
    background: #ffffff;
    box-shadow: 0 6px 18px rgba(15, 23, 42, 0.04);
  }

  .section-header {
    padding: 14px 18px;
    font-size: 1.6em;
    font-weight: 700;
    color: #0f172a;
    background: linear-gradient(180deg, #f8fbff 0%, #eef4fb 100%);
    border-bottom: 1px solid #e3ebf5;
  }

  .section-header.blue {
    background: linear-gradient(90deg, #4f8fe8 0%, #3b82f6 100%);
    color: #ffffff;
  }

  .section-header.soft {
    background: linear-gradient(180deg, #f8fafc 0%, #f1f5f9 100%);
  }

  .section-header.warm {
    background: linear-gradient(180deg, #f8f4ea 0%, #f5efe2 100%);
  }

  .section-body {
    padding: 18px 22px;
  }

  .section-body p {
    margin: 0;
    color: #475569;
    line-height: 1.8;
    font-size: 1.03em;
  }

  .section-body ul {
    margin: 0;
    padding-left: 22px;
    color: #334155;
    line-height: 1.9;
  }

  .section-body li + li {
    margin-top: 6px;
  }

  .project-title {
    font-weight: 700;
    color: #111827;
  }

  .connect-list {
    display: grid;
    gap: 10px;
  }

  .connect-item {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 12px 14px;
    border: 1px solid #e6edf5;
    border-radius: 12px;
    background: #fbfdff;
    color: #334155;
    font-size: 1.02em;
  }

  .footer-note {
    margin-top: 22px;
    padding-top: 18px;
    border-top: 1px solid #e8eef5;
    text-align: center;
    color: #64748b;
    font-size: 0.98em;
  }

  @media (max-width: 768px) {
    body {
      padding: 18px 10px;
    }

    .hub-shell {
      padding: 20px 14px;
      border-radius: 16px;
    }

    .hero h1 {
      font-size: 2.2em;
    }

    .hero p {
      font-size: 1.04em;
    }

    .section-header {
      font-size: 1.35em;
    }
  }
</style>

<div class="hub-shell">

  <div class="hero">
    <h1>Bita Digital Hub</h1>
    <p>
      Building data systems that hold up in real-world usage
    </p>
    <p>
      Focused on pipelines, lakehouse architectures, and production data reliability
    </p>
  </div>

  <div class="section-card">
    <div class="section-header soft">Now</div>
    <div class="section-body">
      <ul>
        <li>Preparing for DP-700 (Microsoft Fabric)</li>
        <li>Building end-to-end lakehouse pipelines with Fabric and Databricks</li>
        <li>Designing production-ready ETL workflows</li>
      </ul>
    </div>
  </div>

  <div class="section-card">
    <div class="section-header blue">Work</div>
    <div class="section-body">
      <ul>
        <li>
          <span class="project-title">Global Retail Lakehouse</span>
          →
          <a href="https://github.com/bashoori/Global-Retail-Lakehouse-on-Microsoft-Fabric">GitHub Repo</a>
        </li>
        <li>
          <span class="project-title">Transit Data Warehouse</span>
          →
          <a href="https://github.com/bashoori/transit_data_warehouse">GitHub Repo</a>
        </li>
      </ul>
    </div>
  </div>

  <div class="section-card">
    <div class="section-header soft">Thinking</div>
    <div class="section-body">
      <ul>
        <li>Pipelines fail silently more often than teams expect</li>
        <li>Schema drift is a design problem, not just a bug</li>
        <li>Reliable systems matter more than unnecessary complexity</li>
      </ul>
    </div>
  </div>

  <div class="section-card">
    <div class="section-header soft">Writing & Posts</div>
    <div class="section-body">
      <ul>
        <li>
          LinkedIn Posts →
          <a href="https://www.linkedin.com/in/bitaashoori/recent-activity/all/">View posts</a>
        </li>
      </ul>
    </div>
  </div>

  <div class="section-card">
    <div class="section-header soft">Connect</div>
    <div class="section-body">
      <div class="connect-list">
        <div class="connect-item">
          GitHub →
          <a href="https://github.com/bashoori">github.com/bashoori</a>
        </div>
        <div class="connect-item">
          LinkedIn →
          <a href="https://www.linkedin.com/in/bitaashoori/">linkedin.com/in/bitaashoori</a>
        </div>
        <div class="connect-item">
          Website →
          <a href="https://bitadigitalhub.com">bitadigitalhub.com</a>
        </div>
      </div>
    </div>
  </div>

  <div class="section-card">
    <div class="section-header warm">Coming Soon</div>
    <div class="section-body">
      <ul>
        <li>YouTube → data engineering journey and real projects</li>
        <li>Instagram → short-form insights and learning journey</li>
        <li>Udemy Course → in progress</li>
      </ul>
    </div>
  </div>

  <div class="footer-note">
    This space is not a traditional portfolio. It is a live hub for what I am building, learning, and sharing.
  </div>

</div>
