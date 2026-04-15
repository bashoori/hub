<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bita Digital Hub</title>
  <style>
    * {
      box-sizing: border-box;
    }

    html {
      -webkit-text-size-adjust: 100%;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
      background: linear-gradient(180deg, #f4f8fc 0%, #eaf1f7 100%);
      color: #0f172a;
      padding: 32px 16px;
    }

    a {
      color: #2563eb;
      text-decoration: none;
      overflow-wrap: anywhere;
      word-break: break-word;
    }

    a:hover {
      text-decoration: underline;
    }

    .page {
      max-width: 880px;
      margin: 0 auto;
      width: 100%;
    }

    .repo-title {
      font-size: 1rem;
      font-weight: 700;
      margin-bottom: 18px;
      padding-left: 2px;
    }

    .repo-title a {
      color: #2563eb;
    }

    .hub-shell {
      background: #ffffff;
      border: 1px solid #dbe5f0;
      border-radius: 20px;
      box-shadow: 0 14px 36px rgba(15, 23, 42, 0.08);
      padding: 26px 20px 22px;
      width: 100%;
      overflow: hidden;
    }

    .hero {
      text-align: center;
      padding: 8px 10px 24px;
      border-bottom: 1px solid #e5edf6;
    }

    .profile-img {
      width: 96px;
      height: 96px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 14px;
      border: 3px solid #e2e8f0;
      box-shadow: 0 6px 16px rgba(15, 23, 42, 0.08);
      background: #ffffff;
    }

    .hero h1 {
      margin: 0;
      font-size: 3rem;
      line-height: 1.08;
      font-weight: 800;
      color: #0f172a;
      letter-spacing: -0.02em;
    }

    .hero p {
      margin: 14px auto 0;
      max-width: 700px;
      color: #334155;
      line-height: 1.7;
      font-size: 1.05rem;
    }

    .hero .subtle {
      color: #475569;
      margin-top: 8px;
    }

    .section-card {
      margin-top: 16px;
      border: 1px solid #dce6f1;
      border-radius: 15px;
      overflow: hidden;
      background: #ffffff;
    }

    .section-header {
      padding: 14px 18px;
      font-size: 1.05rem;
      font-weight: 800;
      color: #0f172a;
      background: #f3f6fa;
      border-bottom: 1px solid #dce6f1;
      line-height: 1.4;
    }

    .section-header.blue {
      color: #ffffff;
      background: linear-gradient(90deg, #4d87df 0%, #3b82f6 100%);
      border-bottom: 1px solid #3b82f6;
    }

    .section-header.warm {
      background: #f5f1e7;
    }

    .section-body {
      padding: 16px 18px;
    }

    .section-body p {
      margin: 0;
      color: #475569;
      line-height: 1.8;
      font-size: 0.98rem;
    }

    .section-body ul {
      margin: 0;
      padding-left: 18px;
      color: #334155;
      line-height: 1.9;
      font-size: 0.98rem;
    }

    .section-body li + li {
      margin-top: 6px;
    }

    .project-name {
      font-weight: 700;
      color: #111827;
    }

    .writing-note {
      margin-top: 8px;
      color: #64748b;
      font-style: italic;
    }

    .connect-list {
      display: grid;
      gap: 8px;
    }

    .connect-item {
      padding: 10px 12px;
      border: 1px solid #dce6f1;
      border-radius: 10px;
      background: #fbfdff;
      color: #334155;
      line-height: 1.65;
      overflow-wrap: anywhere;
      word-break: break-word;
    }

    .footer-note {
      margin-top: 18px;
      padding-top: 14px;
      border-top: 1px solid #e5edf6;
      text-align: center;
      color: #64748b;
      font-size: 0.94rem;
      line-height: 1.7;
    }

    .visitor-counter {
      margin-bottom: 10px;
      color: #475569;
      font-size: 0.95rem;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .visitor-counter img {
      vertical-align: middle;
      max-width: 100%;
      height: auto;
    }

    @media (max-width: 768px) {
      body {
        padding: 20px 10px;
      }

      .hub-shell {
        padding: 18px 12px 16px;
        border-radius: 16px;
      }

      .hero {
        padding: 6px 4px 18px;
      }

      .hero h1 {
        font-size: 2.2rem;
      }

      .hero p {
        font-size: 0.98rem;
        line-height: 1.65;
      }

      .profile-img {
        width: 82px;
        height: 82px;
      }

      .section-header {
        font-size: 1rem;
        padding: 13px 14px;
      }

      .section-body {
        padding: 14px;
      }

      .section-body ul,
      .section-body p,
      .connect-item {
        font-size: 0.95rem;
      }

      .footer-note {
        font-size: 0.9rem;
      }
    }

    @media (max-width: 480px) {
      body {
        padding: 14px 8px;
      }

      .repo-title {
        font-size: 0.96rem;
        margin-bottom: 14px;
      }

      .hub-shell {
        padding: 14px 10px 14px;
        border-radius: 14px;
      }

      .hero h1 {
        font-size: 1.8rem;
        line-height: 1.12;
      }

      .hero p {
        font-size: 0.93rem;
        margin-top: 10px;
      }

      .profile-img {
        width: 72px;
        height: 72px;
      }

      .section-card {
        margin-top: 12px;
        border-radius: 13px;
      }

      .section-header {
        font-size: 0.98rem;
        padding: 12px 12px;
      }

      .section-body {
        padding: 12px;
      }

      .section-body ul {
        padding-left: 16px;
        font-size: 0.92rem;
        line-height: 1.8;
      }

      .section-body p,
      .connect-item,
      .footer-note,
      .visitor-counter {
        font-size: 0.9rem;
      }

      .connect-item {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <div class="page">
    <div class="repo-title">
      <a href="https://github.com/bashoori/hub">hub</a>
    </div>

    <div class="hub-shell">
      <div class="hero">
        <img
          src="https://raw.githubusercontent.com/bashoori/portfolio/main/docs/images/profile_resized.jpg"
          alt="Bita Ashoori"
          class="profile-img"
        />
        <h1>Bita Digital Hub</h1>
        <p>Building reliable data systems for real-world use.</p>
        <p class="subtle">Focused on pipelines, lakehouse architecture, and production data reliability.</p>
      </div>

      <div class="section-card">
        <div class="section-header">Now</div>
        <div class="section-body">
          <ul>
            <li>Preparing for DP-700 and deepening hands-on work in Microsoft Fabric</li>
            <li>Building end-to-end lakehouse pipelines with Fabric and Databricks</li>
            <li>Designing production-ready ETL workflows around real data problems</li>
          </ul>
        </div>
      </div>

      <div class="section-card">
        <div class="section-header blue">Work</div>
        <div class="section-body">
          <ul>
            <li>
              <span class="project-name">Global Retail Lakehouse</span>
              → <a href="https://github.com/bashoori/Global-Retail-Lakehouse-on-Microsoft-Fabric">GitHub Repo</a>
            </li>
            <li>
              <span class="project-name">Transit Data Warehouse</span>
              → <a href="https://github.com/bashoori/transit_data_warehouse">GitHub Repo</a>
            </li>
            <li>
              More projects → <a href="https://github.com/bashoori">GitHub</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="section-card">
        <div class="section-header">Thinking</div>
        <div class="section-body">
          <ul>
            <li>Pipelines fail silently more often than teams expect</li>
            <li>Schema drift is a design problem, not just a bug</li>
            <li>Reliable systems matter more than unnecessary complexity</li>
          </ul>
        </div>
      </div>

      <div class="section-card">
        <div class="section-header">Writing & Posts</div>
        <div class="section-body">
          <ul>
            <li>
              LinkedIn → <a href="https://www.linkedin.com/in/bitaashoori/recent-activity/all/">View posts</a>
            </li>
          </ul>
          <p class="writing-note">Thoughts on data engineering, real-world issues, and system design.</p>
        </div>
      </div>

      <div class="section-card">
        <div class="section-header">Connect</div>
        <div class="section-body">
          <div class="connect-list">
            <div class="connect-item">
              GitHub → <a href="https://github.com/bashoori">github.com/bashoori</a>
            </div>
            <div class="connect-item">
              LinkedIn → <a href="https://www.linkedin.com/in/bitaashoori/">linkedin.com/in/bitaashoori</a>
            </div>
            <div class="connect-item">
              Website → <a href="https://bitadigitalhub.com">bitadigitalhub.com</a>
            </div>
          </div>
        </div>
      </div>

      <div class="section-card">
        <div class="section-header warm">Coming Soon</div>
        <div class="section-body">
          <ul>
            <li>YouTube → documenting real data engineering projects and technical growth</li>
            <li>Instagram → short-form insights and learning journey</li>
            <li>Udemy Course → practical data engineering learning content in progress</li>
          </ul>
        </div>
      </div>

      <div class="footer-note">
        <div class="visitor-counter">
          <span>👀 Visitors:</span>
          <img
            src="https://komarev.com/ghpvc/?username=bita-digital-hub&label=views&color=0e75b6&style=flat"
            alt="visitor counter"
          />
        </div>
        This is not a traditional portfolio.<br />
        It is a live hub for what I am building, learning, and sharing.
      </div>
    </div>
  </div>
</body>
</html>
