<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dutch Postcode Lottery: Donations 2016 - 2025</title>
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.min.js"></script>
<style>
  :root {
    --bg: #f7f7fb;
    --card: #ffffff;
    --ink: #575757;
    --ink-strong: #3a3a3a;
    --muted: #8a8a8a;
    --border: #e5e7eb;
    --accent: #00ACD7;
    --accent-2: #F18A6F;
    --c1: #00ACD7;
    --c2: #F18A6F;
    --c3: #2E5A6B;
    --c4: #E8B647;
    --warn-bg: #fff7ed;
    --warn-border: #fb923c;
  }
  * { box-sizing: border-box; }
  body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    background: var(--bg);
    color: var(--ink);
    line-height: 1.5;
  }
  header {
    background: linear-gradient(135deg, #00ACD7 0%, #F18A6F 100%);
    color: #fff;
    padding: 2rem 1.25rem;
  }
  header h1 { margin: 0; font-size: 1.5rem; font-weight: 700; }
  main { max-width: 1200px; margin: 0 auto; padding: 1.25rem; }
  section {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 1.25rem;
    margin-bottom: 1.25rem;
  }
  section h2 { margin-top: 0; font-size: 1.25rem; border-bottom: 2px solid var(--accent); padding-bottom: .4rem; display: inline-block; color: var(--ink-strong); }
  strong { color: var(--ink-strong); }
  .kpis { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: .75rem; margin: 1rem 0; }
  .kpi { background: #f9fafb; border: 1px solid var(--border); border-radius: 8px; padding: .85rem; }
  .kpi .label { font-size: .75rem; color: var(--muted); text-transform: uppercase; letter-spacing: .5px; }
  .kpi .value { font-size: 1.35rem; font-weight: 700; margin-top: .2rem; color: var(--ink-strong); }
  table { width: 100%; border-collapse: collapse; font-size: .88rem; color: var(--ink); }
  th, td { padding: .5rem .6rem; text-align: left; border-bottom: 1px solid var(--border); }
  th { background: #f3f4f6; font-weight: 600; position: sticky; top: 0; cursor: pointer; user-select: none; white-space: nowrap; color: var(--ink-strong); }
  th:hover { background: #e5e7eb; }
  th .arrow { color: var(--muted); font-size: .7rem; margin-left: .25rem; }
  td.num, th.num { text-align: right; font-variant-numeric: tabular-nums; }
  .table-wrap { overflow-x: auto; max-height: 560px; overflow-y: auto; border: 1px solid var(--border); border-radius: 8px; }
  .filter-row { display: flex; flex-wrap: wrap; gap: .5rem; margin-bottom: .75rem; align-items: center; }
  .filter-row input, .filter-row select {
    padding: .45rem .6rem; border: 1px solid var(--border); border-radius: 6px; font-size: .88rem; background: #fff; color: var(--ink);
  }
  .chart-wrap { position: relative; max-width: 520px; margin: 1rem auto; }
  .chart-wrap.wide { max-width: 100%; height: 420px; }
  .anomaly { background: var(--warn-bg); border: 1px solid var(--warn-border); border-left: 4px solid var(--warn-border); padding: .75rem 1rem; border-radius: 6px; margin: .5rem 0; font-size: .9rem; }
  .anomaly.ok { background: #ecfdf5; border-color: #34d399; }
  .anomaly strong { color: #9a3412; }
  .anomaly.ok strong { color: #065f46; }
  .pill { display: inline-block; padding: .15rem .5rem; border-radius: 999px; font-size: .72rem; font-weight: 600; }
  .pill.c1 { background: #e0f5fb; color: #006b87; }
  .pill.c2 { background: #fdeae3; color: #b94e30; }
  .pill.c3 { background: #dde8ed; color: #2E5A6B; }
  .pill.c4 { background: #fbf0d4; color: #8a6414; }
  details { margin-top: .5rem; }
  details summary { cursor: pointer; color: var(--muted); font-size: .85rem; }
  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 1.25rem; }
  @media (max-width: 760px) {
    .two-col { grid-template-columns: 1fr; }
    header h1 { font-size: 1.3rem; }
    th, td { padding: .4rem .4rem; font-size: .8rem; }
  }
  .footnote { color: var(--muted); font-size: .78rem; margin-top: .5rem; }
  .theme-filters { display: flex; gap: .75rem; flex-wrap: wrap; align-items: center; margin-bottom: 1rem; }
  .theme-filters select {
    padding: .45rem .6rem; border: 1px solid var(--border); border-radius: 6px; font-size: .88rem; background: #fff; color: var(--ink);
  }
  .toggle-group { display: inline-flex; border: 1px solid var(--border); border-radius: 8px; overflow: hidden; background: #fff; }
  .toggle-btn { background: #fff; border: 0; padding: .5rem .9rem; font-size: .85rem; font-weight: 600; color: var(--muted); cursor: pointer; border-right: 1px solid var(--border); font-family: inherit; }
  .toggle-btn:last-child { border-right: 0; }
  .toggle-btn.active { background: var(--accent); color: #fff; }
  .toggle-btn:hover:not(.active) { background: #f3f4f6; }
  #org-table tbody tr.org-row { cursor: pointer; }
  #org-table tbody tr.org-row > td { vertical-align: middle; padding: .5rem .6rem; line-height: 1.4; white-space: nowrap; }
  #org-table tbody tr.org-row:hover { background: #f5fbfd; }
  #org-table tbody tr.org-row.expanded { background: #e8f6fb; }
  .org-desc { font-size: .75rem; color: var(--muted); font-weight: 400; line-height: 1.4; margin-top: .2rem; white-space: normal; }
  #main-table tbody tr.don-row.has-desc { cursor: pointer; }
  #main-table tbody tr.don-row.has-desc:hover { background: #f5fbfd; }
  #main-table tbody tr.don-row.expanded { background: #e8f6fb; }
  #main-table tbody tr.don-row .chev { display: inline-block; width: 14px; color: var(--muted); transition: transform .15s ease; }
  #main-table tbody tr.don-row.expanded .chev { transform: rotate(90deg); color: var(--accent); }
  #main-table tbody tr.detail-row > td { background: #f3fafd; padding: .85rem 1rem; border-bottom: 2px solid var(--border); }
  #org-table tbody tr.org-row .chev { display: inline-block; width: 14px; color: var(--muted); transition: transform .15s ease; }
  #org-table tbody tr.org-row.expanded .chev { transform: rotate(90deg); color: var(--accent); }
  #org-table tbody tr.detail-row > td { background: #f3fafd; padding: .85rem 1rem; border-bottom: 2px solid var(--border); }
  .detail-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: .75rem; }
  .detail-card { background: #fff; border: 1px solid var(--border); border-left: 3px solid var(--accent); border-radius: 6px; padding: .65rem .8rem; }
  .detail-card .cat { font-size: .72rem; text-transform: uppercase; letter-spacing: .5px; color: var(--muted); font-weight: 600; }
  .detail-card .amt { font-size: 1.05rem; font-weight: 700; margin: .15rem 0; color: var(--ink-strong); }
  .detail-card .yrs { font-size: .78rem; color: var(--muted); }
  .origin-pill { display: inline-block; padding: .1rem .5rem; border-radius: 999px; font-size: .72rem; font-weight: 600; }
  .origin-pill.dutch { background: #fdeae3; color: #b94e30; }
  .origin-pill.intl { background: #e0f5fb; color: #006b87; }
  /* Header branding */
  .header-inner { display: flex; justify-content: space-between; align-items: center; max-width: 1200px; margin: 0 auto; flex-wrap: wrap; gap: .75rem; }
  .header-brand { display: flex; align-items: center; gap: .85rem; }
  .header-logo-img { height: 44px; width: auto; filter: brightness(0) invert(1); }
  .header-site { font-size: .8rem; opacity: .85; text-align: right; }
  .header-site a { color: #fff; text-decoration: none; border-bottom: 1px solid rgba(255,255,255,.4); }
  .header-site a:hover { border-bottom-color: #fff; }
  /* Footer */
  footer { background: #2a2a2a; color: #ccc; padding: 2rem 1.25rem; font-size: .82rem; line-height: 1.65; }
  .footer-inner { max-width: 1200px; margin: 0 auto; display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 2rem; }
  footer .f-title { color: #fff; font-weight: 700; font-size: .88rem; margin-bottom: .5rem; letter-spacing: .5px; }
  footer a { color: var(--accent); text-decoration: none; }
  footer a:hover { text-decoration: underline; }
  .footer-logo-img { height: 38px; width: auto; filter: brightness(0) invert(1); }
  footer .f-legal { font-size: .72rem; color: #999; line-height: 1.5; }
  footer .f-links a { display: inline-flex; align-items: center; gap: .35rem; margin-right: 1rem; margin-bottom: .35rem; }
  .f-newsletter { display: inline-block; margin-top: .5rem; padding: .5rem 1rem; background: var(--accent); color: #fff; border-radius: 6px; font-weight: 600; font-size: .82rem; text-decoration: none !important; }
  .f-newsletter:hover { background: #0095ba; }
  .f-divider { border: 0; border-top: 1px solid #444; margin: 1.25rem 0; }
  .f-bottom { max-width: 1200px; margin: 0 auto; text-align: center; font-size: .72rem; color: #888; }
  @media (max-width: 760px) {
    .footer-inner { grid-template-columns: 1fr; gap: 1.25rem; }
    .header-inner { flex-direction: column; align-items: flex-start; }
    .header-site { text-align: left; }
  }
</style>
</head>
<body>
<header>
  <div class="header-inner">
    <div class="header-brand">
      <img src="data:image/webp;base64,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" alt="HVFC — Fundraising · Impact · Talent" class="header-logo-img">
      <div style="width:1px; height:2.2rem; background:rgba(255,255,255,.35);"></div>
      <h1>Dutch Postcode Lottery: Donations 2016 - 2025</h1>
    </div>
    <div class="header-site">
      <a href="https://hvfc-international.com" target="_blank" rel="noopener">hvfc-international.com</a>
      <div style="font-size:.7rem; opacity:.7; margin-top:.25rem;">Version 0.12.0 - Released on May 26 2026</div>
    </div>
  </div>
</header>
<main>
  <section>
    <h2>Category Breakdown</h2>
    <div class="two-col">
      <div>
        <div class="table-wrap" style="max-height:none">
          <table id="category-table">
            <thead><tr><th>Category</th><th class="num">Organisations</th><th class="num">Total (€)</th><th class="num">% of Total</th></tr></thead>
            <tbody></tbody>
          </table>
        </div>
      </div>
      <div>
        <div class="chart-wrap"><canvas id="categoryChart"></canvas></div>
      </div>
    </div>
  </section>

  <section>
    <h2>Theme Analysis</h2>
    <div class="theme-filters">
      <div class="toggle-group" id="dutchToggle" role="group" aria-label="Dutch / International filter">
        <button type="button" class="toggle-btn active" data-dutch="all">All</button>
        <button type="button" class="toggle-btn" data-dutch="dutch">The Netherlands</button>
        <button type="button" class="toggle-btn" data-dutch="international">International</button>
      </div>
      <select id="themeYearFilter" aria-label="Year filter">
        <option value="">All years</option>
      </select>
    </div>
    <div class="chart-wrap wide"><canvas id="themeChart"></canvas></div>
    <div class="table-wrap" style="max-height:none; margin-top:1rem">
      <table id="theme-table">
        <thead><tr><th>Theme</th><th class="num">Multi-year partner</th><th class="num">One-time donation</th><th class="num">Extra contribution</th><th class="num">Dream Fund</th><th class="num">Total (€)</th><th class="num">% of Total</th></tr></thead>
        <tbody></tbody>
      </table>
    </div>
    <details>
      <summary>See which organisations are assigned to each theme</summary>
      <div id="theme-orgs" style="margin-top:.5rem; font-size:.82rem;"></div>
    </details>
  </section>

  <section>
    <h2>Organisations</h2>
    <p class="footnote" style="margin-top:-.25rem">Each organisation appears once, aggregated across all years. Click a row to see its donations broken down by category.</p>
    <div class="filter-row">
      <div class="toggle-group" id="orgDutchToggle" role="group" aria-label="Dutch / International filter">
        <button type="button" class="toggle-btn active" data-dutch="all">All</button>
        <button type="button" class="toggle-btn" data-dutch="dutch">The Netherlands</button>
        <button type="button" class="toggle-btn" data-dutch="international">International</button>
      </div>
      <input id="orgSearchInput" type="search" placeholder="Search organisation…">
      <select id="orgThemeFilter"><option value="">All themes</option></select>
      <span id="orgRowCount" style="color:var(--muted); font-size:.85rem;"></span>
    </div>
    <div class="table-wrap">
      <table id="org-table">
        <thead><tr>
          <th data-sort="organisation">Organisation <span class="arrow">⇅</span></th>
          <th data-sort="theme">Theme <span class="arrow">⇅</span></th>
          <th data-sort="origin">Recipient Country <span class="arrow">⇅</span></th>
          <th data-sort="total" class="num">Total donated (€) <span class="arrow">⇅</span></th>
          <th data-sort="count" class="num">Donations <span class="arrow">⇅</span></th>
          <th data-sort="years" class="num">Years active <span class="arrow">⇅</span></th>
        </tr></thead>
        <tbody></tbody>
      </table>
    </div>
  </section>

  <section>
    <h2>All Donations</h2>
    <div class="filter-row">
      <div class="toggle-group" id="mainDutchToggle" role="group" aria-label="Dutch / International filter">
        <button type="button" class="toggle-btn active" data-dutch="all">All</button>
        <button type="button" class="toggle-btn" data-dutch="dutch">The Netherlands</button>
        <button type="button" class="toggle-btn" data-dutch="international">International</button>
      </div>
      <input id="searchInput" type="search" placeholder="Search organisation…">
      <select id="categoryFilter"></select>
      <select id="yearFilter"><option value="">All years</option></select>
      <select id="themeFilter"><option value="">All themes</option></select>
      <span id="rowCount" style="color:var(--muted); font-size:.85rem;"></span>
    </div>
    <div class="table-wrap">
      <table id="main-table">
        <thead><tr>
          <th data-sort="organisation">Organisation <span class="arrow">⇅</span></th>
          <th data-sort="category">Category <span class="arrow">⇅</span></th>
          <th data-sort="theme">Theme <span class="arrow">⇅</span></th>
          <th data-sort="origin">Recipient Country <span class="arrow">⇅</span></th>
          <th data-sort="projectLocation">Project Location <span class="arrow">⇅</span></th>
          <th data-sort="year" class="num">Year <span class="arrow">⇅</span></th>
          <th data-sort="amount" class="num">Amount (€) <span class="arrow">⇅</span></th>
        </tr></thead>
        <tbody></tbody>
      </table>
    </div>
  </section>
</main>

<script>
const CSV_DATA = `Categorie,Organisatie,Bedrag,Jaar,,
Multi-year partner,Stichting DOEN,22508702,2016,,
Multi-year partner,Oranje Fonds,15000000,2016,,
Multi-year partner,Artsen zonder Grenzen,13500000,2016,,
Multi-year partner,LandschappenNL,13500000,2016,,
Multi-year partner,Natuurmonumenten,13500000,2016,,
Multi-year partner,Oxfam Novib,13500000,2016,,
Multi-year partner,UNICEF,13500000,2016,,
Multi-year partner,Wereld Natuur Fonds,13500000,2016,,
Multi-year partner,Kansfonds,10000000,2016,,
Multi-year partner,Vfonds,9979915,2016,,
Multi-year partner,VluchtelingenWerk Nederland,9000000,2016,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2016,,
Multi-year partner,Humanitas,4500000,2016,,
Multi-year partner,Amnesty International,3600000,2016,,
Multi-year partner,Plan International,3150000,2016,,
Multi-year partner,Cordaid,2700000,2016,,
Multi-year partner,Stichting Vluchteling,2700000,2016,,
Multi-year partner,Aidsfonds,2250000,2016,,
Multi-year partner,Greenpeace,2250000,2016,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2016,,
Multi-year partner,Terre des Hommes,2250000,2016,,
Multi-year partner,Postcode Lottery Green Challenge,1850000,2016,,
Multi-year partner,Clinton Foundation,1800000,2016,,
Multi-year partner,Dierenbescherming,1800000,2016,,
Multi-year partner,Natuur & Milieu,1800000,2016,,
Multi-year partner,Vogelbescherming Nederland,1800000,2016,,
Multi-year partner,Hivos,1350000,2016,,
Multi-year partner,ICCO,1350000,2016,,
Multi-year partner,IVN Natuureducatie,1350000,2016,,
Multi-year partner,Johan Cruyff Foundation,1350000,2016,,
Multi-year partner,Leprastichting,1350000,2016,,
Multi-year partner,Liliane Fonds,1350000,2016,,
Multi-year partner,Milieudefensie,1350000,2016,,
Multi-year partner,Peace Parks Foundation,1350000,2016,,
Multi-year partner,Solidaridad,1350000,2016,,
Multi-year partner,SOS Kinderdorpen,1350000,2016,,
Multi-year partner,UNHCR,1350000,2016,,
Multi-year partner,War Child,1350000,2016,,
Multi-year partner,World Food Programme,1350000,2016,,
Multi-year partner,African Parks Network,900000,2016,,
Multi-year partner,Amref Health Africa,900000,2016,,
Multi-year partner,ARK Rewilding Nederland,900000,2016,,
Multi-year partner,CARE Nederland,900000,2016,,
Multi-year partner,The Climate Group,900000,2016,,
Multi-year partner,European Climate Foundation,900000,2016,,
Multi-year partner,Free Press Unlimited,900000,2016,,
Multi-year partner,Goois Natuurreservaat,900000,2016,,
Multi-year partner,Human Rights Watch,900000,2016,,
Multi-year partner,IUCN NL,900000,2016,,
Multi-year partner,Mama Cash,900000,2016,,
Multi-year partner,PharmAccess,900000,2016,,
Multi-year partner,Rocky Mountain Institute,900000,2016,,
Multi-year partner,Rutgers,900000,2016,,
Multi-year partner,Save the Children Nederland,900000,2016,,
Multi-year partner,Sea Shepherd,900000,2016,,
Multi-year partner,Simavi,900000,2016,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2016,,
Multi-year partner,Wilde Ganzen,900000,2016,,
Multi-year partner,Aflatoun International,500000,2016,,
Multi-year partner,BiD Network,500000,2016,,
Multi-year partner,Carbon War Room,500000,2016,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2016,,
Multi-year partner,Commonland,500000,2016,,
Multi-year partner,Dance4Life,500000,2016,,
Multi-year partner,Defence for Children,500000,2016,,
Multi-year partner,Dokters van de Wereld,500000,2016,,
Multi-year partner,Dr. Denis Mukwege Foundation,500000,2016,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2016,,
Multi-year partner,Edukans,500000,2016,,
Multi-year partner,The Elders,500000,2016,,
Multi-year partner,Fairfood,500000,2016,,
Multi-year partner,Girls Not Brides,500000,2016,,
Multi-year partner,The Hunger Project,500000,2016,,
Multi-year partner,IMC Weekendschool,500000,2016,,
Multi-year partner,Kinderfonds MAMAS,500000,2016,,
Multi-year partner,Krajicek Foundation,500000,2016,,
Multi-year partner,LINDA.foundation,500000,2016,,
Multi-year partner,Lokale Fondsen Nederland,500000,2016,,
Multi-year partner,Marine Stewardship Council,500000,2016,,
Multi-year partner,Not On Our Watch,500000,2016,,
Multi-year partner,PAX,500000,2016,,
Multi-year partner,Prins Claus Fonds,500000,2016,,
Multi-year partner,Rafa Nadal Foundation,500000,2016,,
Multi-year partner,Resto VanHarte,500000,2016,,
Multi-year partner,Rewilding Europe,500000,2016,,
Multi-year partner,Right To Play,500000,2016,,
Multi-year partner,Scouting Nederland,500000,2016,,
Multi-year partner,AAP,500000,2016,,
Multi-year partner,De Vrolijkheid,500000,2016,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2016,,
Multi-year partner,Theirworld,500000,2016,,
Multi-year partner,Urgenda,500000,2016,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2016,,
Multi-year partner,Voedselbanken Nederland,500000,2016,,
Multi-year partner,Waddenvereniging,500000,2016,,
Multi-year partner,Wakker Dier,500000,2016,,
Multi-year partner,WOMEN Inc.,500000,2016,,
Multi-year partner,World Press Photo,500000,2016,,
Multi-year partner,YY Foundation,500000,2016,,
SUBTOTAAL Multi-year partner,99 organisaties,242738617,2016,,
One-time donation,Stichting voor Vluchteling-Studenten UAF,4000000,2016,,
One-time donation,Wildlife Justice Commission,2500000,2016,,
One-time donation,Oceana,2250000,2016,,
One-time donation,Circle Economy,1000000,2016,,
One-time donation,Free a Girl,1000000,2016,,
One-time donation,HealthNet,1000000,2016,,
One-time donation,KidsRights,1000000,2016,,
One-time donation,Urgenda,1000000,2016,,
One-time donation,VluchtelingenWerk Nederland,950000,2016,,
One-time donation,Plastic Soup Foundation,600000,2016,,
One-time donation,Stichting De Noordzee,500000,2016,,
One-time donation,Stichting DierenLot,500000,2016,,
One-time donation,Stichting MAX Maakt Mogelijk,500000,2016,,
One-time donation,Instituut Clingendael,400000,2016,,
SUBTOTAAL One-time donation,14 organisaties,17200000,2016,,
Extra contribution to multi-year partners,Natuurmonumenten,7770000,2016,,
Extra contribution to multi-year partners,Stichting DOEN,5000000,2016,,
Extra contribution to multi-year partners,War Child,2500000,2016,,
Extra contribution to multi-year partners,UNHCR,2384000,2016,,
Extra contribution to multi-year partners,ICCO,2120000,2016,,
Extra contribution to multi-year partners,PAX,2040000,2016,,
Extra contribution to multi-year partners,Stichting Kinderpostzegels Nederland,1990000,2016,,
Extra contribution to multi-year partners,Liliane Fonds,1800000,2016,,
Extra contribution to multi-year partners,LandschappenNL,1755000,2016,,
Extra contribution to multi-year partners,Marine Stewardship Council,1755000,2016,,
Extra contribution to multi-year partners,Vogelbescherming Nederland,1700000,2016,,
Extra contribution to multi-year partners,Vfonds,1500000,2016,,
Extra contribution to multi-year partners,Right To Play,1475000,2016,,
Extra contribution to multi-year partners,Natuur & Milieu,1446000,2016,,
Extra contribution to multi-year partners,Krajicek Foundation,1355000,2016,,
Extra contribution to multi-year partners,AAP,1335000,2016,,
Extra contribution to multi-year partners,Not On Our Watch,900000,2016,,
Extra contribution to multi-year partners,LINDA.foundation,426000,2016,,
SUBTOTAAL Extra bijdrage,18 organisaties,39251000,2016,,
Dream Fund,Hivos & Greenpeace - Alle ogen op de Amazone,14825000,2016,,
Dream Fund,Leprastichting,9375000,2016,,
SUBTOTAAL Dream Fund,2 organisaties,24200000,2016,,
TOTAAL 2016,133 entries,323389617,2016,,
Multi-year partner,Stichting DOEN,22503890,2017,,
Multi-year partner,Oranje Fonds,15000000,2017,,
Multi-year partner,Artsen zonder Grenzen,13500000,2017,,
Multi-year partner,LandschappenNL,13500000,2017,,
Multi-year partner,Natuurmonumenten,13500000,2017,,
Multi-year partner,Oxfam Novib,13500000,2017,,
Multi-year partner,UNICEF,13500000,2017,,
Multi-year partner,Wereld Natuur Fonds,13500000,2017,,
Multi-year partner,Kansfonds,10000000,2017,,
Multi-year partner,Vfonds,10000000,2017,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2017,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2017,,
Multi-year partner,Humanitas,4500000,2017,,
Multi-year partner,Amnesty International,3600000,2017,,
Multi-year partner,Plan International,3150000,2017,,
Multi-year partner,Cordaid,2700000,2017,,
Multi-year partner,Stichting Vluchteling,2700000,2017,,
Multi-year partner,Aidsfonds,2250000,2017,,
Multi-year partner,Greenpeace,2250000,2017,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2017,,
Multi-year partner,Terre des Hommes,2250000,2017,,
Multi-year partner,UNHCR,2250000,2017,,
Multi-year partner,Postcode Lottery Green Challenge,2200000,2017,,
Multi-year partner,Clinton Foundation,1800000,2017,,
Multi-year partner,Dierenbescherming,1800000,2017,,
Multi-year partner,Natuur & Milieu,1800000,2017,,
Multi-year partner,Vogelbescherming Nederland,1800000,2017,,
Multi-year partner,Hivos,1350000,2017,,
Multi-year partner,Human Rights Watch,1350000,2017,,
Multi-year partner,ICCO,1350000,2017,,
Multi-year partner,IVN Natuureducatie,1350000,2017,,
Multi-year partner,Johan Cruyff Foundation,1350000,2017,,
Multi-year partner,Leprastichting,1350000,2017,,
Multi-year partner,Liliane Fonds,1350000,2017,,
Multi-year partner,Milieudefensie,1350000,2017,,
Multi-year partner,Peace Parks Foundation,1350000,2017,,
Multi-year partner,Solidaridad,1350000,2017,,
Multi-year partner,SOS Kinderdorpen,1350000,2017,,
Multi-year partner,War Child,1350000,2017,,
Multi-year partner,World Food Programme,1350000,2017,,
Multi-year partner,African Parks Network,900000,2017,,
Multi-year partner,Amref Health Africa,900000,2017,,
Multi-year partner,ARK Rewilding Nederland,900000,2017,,
Multi-year partner,CARE Nederland,900000,2017,,
Multi-year partner,The Climate Group,900000,2017,,
Multi-year partner,European Climate Foundation,900000,2017,,
Multi-year partner,Free Press Unlimited,900000,2017,,
Multi-year partner,Goois Natuurreservaat,900000,2017,,
Multi-year partner,IUCN NL,900000,2017,,
Multi-year partner,KNCV Tuberculosefonds,900000,2017,,
Multi-year partner,Leonardo DiCaprio Foundation,900000,2017,,
Multi-year partner,Mama Cash,900000,2017,,
Multi-year partner,PharmAccess,900000,2017,,
Multi-year partner,Rocky Mountain Institute,900000,2017,,
Multi-year partner,Rutgers,900000,2017,,
Multi-year partner,Save the Children Nederland,900000,2017,,
Multi-year partner,Sea Shepherd,900000,2017,,
Multi-year partner,Simavi,900000,2017,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2017,,
Multi-year partner,Wilde Ganzen,900000,2017,,
Multi-year partner,AAP,500000,2017,,
Multi-year partner,Aflatoun International,500000,2017,,
Multi-year partner,Carbon War Room,500000,2017,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2017,,
Multi-year partner,Commonland,500000,2017,,
Multi-year partner,Dance4Life,500000,2017,,
Multi-year partner,Defence for Children,500000,2017,,
Multi-year partner,Dokters van de Wereld,500000,2017,,
Multi-year partner,Dr. Denis Mukwege Foundation,500000,2017,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2017,,
Multi-year partner,Edukans,500000,2017,,
Multi-year partner,The Elders,500000,2017,,
Multi-year partner,Fairfood,500000,2017,,
Multi-year partner,Girls Not Brides,500000,2017,,
Multi-year partner,Global Witness,500000,2017,,
Multi-year partner,The Hunger Project,500000,2017,,
Multi-year partner,IMC Weekendschool,500000,2017,,
Multi-year partner,JINC,500000,2017,,
Multi-year partner,Kinderfonds MAMAS,500000,2017,,
Multi-year partner,Krajicek Foundation,500000,2017,,
Multi-year partner,LINDA.foundation,500000,2017,,
Multi-year partner,Lokale Fondsen Nederland,500000,2017,,
Multi-year partner,Marine Stewardship Council,500000,2017,,
Multi-year partner,Not On Our Watch,500000,2017,,
Multi-year partner,PAX,500000,2017,,
Multi-year partner,Prins Claus Fonds,500000,2017,,
Multi-year partner,Rafa Nadal Foundation,500000,2017,,
Multi-year partner,Resto VanHarte,500000,2017,,
Multi-year partner,Rewilding Europe,500000,2017,,
Multi-year partner,Right To Play,500000,2017,,
Multi-year partner,Scouting Nederland,500000,2017,,
Multi-year partner,Stichting De Noordzee,500000,2017,,
Multi-year partner,De Vrolijkheid,500000,2017,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2017,,
Multi-year partner,Theirworld,500000,2017,,
Multi-year partner,Urgenda,500000,2017,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2017,,
Multi-year partner,Voedselbanken Nederland,500000,2017,,
Multi-year partner,Waddenvereniging,500000,2017,,
Multi-year partner,Wakker Dier,500000,2017,,
Multi-year partner,WOMEN Inc.,500000,2017,,
Multi-year partner,World Press Photo,500000,2017,,
Multi-year partner,YY Foundation,500000,2017,,
SUBTOTAAL Multi-year partner,103 organisaties,248253890,2017,,
One-time donation,Artsen zonder Grenzen,4300000,2017,,
One-time donation,Het Nederlandse Rode Kruis,4300000,2017,,
One-time donation,Stichting Vluchteling,4300000,2017,,
One-time donation,APOPO,1500000,2017,,
One-time donation,BRAC International,1500000,2017,,
One-time donation,350.org / Fossielvrij NL,1000000,2017,,
One-time donation,Habitat for Humanity Nederland,1000000,2017,,
One-time donation,Institute for War & Peace Reporting (IWPR),1000000,2017,,
One-time donation,Missing Chapter Foundation,1000000,2017,,
One-time donation,RNW Media,1000000,2017,,
One-time donation,SPARK,1000000,2017,,
One-time donation,Wetlands International,1000000,2017,,
SUBTOTAAL One-time donation,12 organisaties,22900000,2017,,
Extra contribution to multi-year partners,Waddenvereniging,5114000,2017,,
Extra contribution to multi-year partners,African Parks Network,2997000,2017,,
Extra contribution to multi-year partners,ICCO,2834000,2017,,
Extra contribution to multi-year partners,Oxfam Novib,2500000,2017,,
Extra contribution to multi-year partners,Greenpeace,2409000,2017,,
Extra contribution to multi-year partners,Save the Children Nederland,2400000,2017,,
Extra contribution to multi-year partners,SOS Kinderdorpen,2356000,2017,,
Extra contribution to multi-year partners,Amnesty International,2318000,2017,,
Extra contribution to multi-year partners,ARK Rewilding Nederland,2163000,2017,,
Extra contribution to multi-year partners,Girls Not Brides,2000000,2017,,
Extra contribution to multi-year partners,Amref Health Africa,1995000,2017,,
Extra contribution to multi-year partners,YY Foundation,1860000,2017,,
Extra contribution to multi-year partners,IVN Natuureducatie,1850000,2017,,
Extra contribution to multi-year partners,Scouting Nederland,1650000,2017,,
Extra contribution to multi-year partners,Vfonds,1650000,2017,,
Extra contribution to multi-year partners,Defence for Children,1640000,2017,,
Extra contribution to multi-year partners,UNICEF,1469000,2017,,
Extra contribution to multi-year partners,Commonland,1394000,2017,,
Extra contribution to multi-year partners,Wakker Dier,1375000,2017,,
Extra contribution to multi-year partners,Mama Cash,1253000,2017,,
Extra contribution to multi-year partners,Aidsfonds,1051000,2017,,
Extra contribution to multi-year partners,Centrum tegen Kinderhandel en Mensenhandel,1000000,2017,,
Extra contribution to multi-year partners,Dr. Denis Mukwege Foundation,965000,2017,,
Extra contribution to multi-year partners,Dokters van de Wereld,554000,2017,,
SUBTOTAAL Extra bijdrage,24 organisaties,46797000,2017,,
Dream Fund,Rutgers,11900000,2017,,
SUBTOTAAL Dream Fund,1 organisatie,11900000,2017,,
TOTAAL 2017,140 entries,329850890,2017,,
Multi-year partner,Stichting DOEN,22520159,2018,,
Multi-year partner,Oranje Fonds,15000000,2018,,
Multi-year partner,Artsen zonder Grenzen,13500000,2018,,
Multi-year partner,LandschappenNL,13500000,2018,,
Multi-year partner,Natuurmonumenten,13500000,2018,,
Multi-year partner,Oxfam Novib,13500000,2018,,
Multi-year partner,UNICEF,13500000,2018,,
Multi-year partner,Wereld Natuur Fonds,13500000,2018,,
Multi-year partner,Kansfonds,10000000,2018,,
Multi-year partner,Vfonds,10000000,2018,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2018,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2018,,
Multi-year partner,Humanitas,4500000,2018,,
Multi-year partner,Amnesty International,3600000,2018,,
Multi-year partner,Plan International,3150000,2018,,
Multi-year partner,Cordaid,2700000,2018,,
Multi-year partner,Stichting Vluchteling,2700000,2018,,
Multi-year partner,Aidsfonds,2250000,2018,,
Multi-year partner,Greenpeace,2250000,2018,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2018,,
Multi-year partner,Terre des Hommes,2250000,2018,,
Multi-year partner,UNHCR,2250000,2018,,
Multi-year partner,Postcode Lottery Green Challenge,2200000,2018,,
Multi-year partner,Clinton Foundation,1800000,2018,,
Multi-year partner,Dierenbescherming,1800000,2018,,
Multi-year partner,Natuur & Milieu,1800000,2018,,
Multi-year partner,Vogelbescherming Nederland,1800000,2018,,
Multi-year partner,Hivos,1350000,2018,,
Multi-year partner,Human Rights Watch,1350000,2018,,
Multi-year partner,ICCO,1350000,2018,,
Multi-year partner,IVN Natuureducatie,1350000,2018,,
Multi-year partner,Johan Cruyff Foundation,1350000,2018,,
Multi-year partner,Leprastichting,1350000,2018,,
Multi-year partner,Liliane Fonds,1350000,2018,,
Multi-year partner,Mama Cash,1350000,2018,,
Multi-year partner,Milieudefensie,1350000,2018,,
Multi-year partner,Peace Parks Foundation,1350000,2018,,
Multi-year partner,Solidaridad,1350000,2018,,
Multi-year partner,SOS Kinderdorpen,1350000,2018,,
Multi-year partner,Theirworld,1350000,2018,,
Multi-year partner,War Child,1350000,2018,,
Multi-year partner,World Food Programme,1350000,2018,,
Multi-year partner,African Parks Network,900000,2018,,
Multi-year partner,Amref Health Africa,900000,2018,,
Multi-year partner,ARK Rewilding Nederland,900000,2018,,
Multi-year partner,CARE Nederland,900000,2018,,
Multi-year partner,The Climate Group,900000,2018,,
Multi-year partner,Commonland,900000,2018,,
Multi-year partner,European Climate Foundation,900000,2018,,
Multi-year partner,Free Press Unlimited,900000,2018,,
Multi-year partner,Goois Natuurreservaat,900000,2018,,
Multi-year partner,IUCN NL,900000,2018,,
Multi-year partner,KNCV Tuberculosefonds,900000,2018,,
Multi-year partner,Leonardo DiCaprio Foundation,900000,2018,,
Multi-year partner,PharmAccess,900000,2018,,
Multi-year partner,Rewilding Europe,900000,2018,,
Multi-year partner,Rocky Mountain Institute,900000,2018,,
Multi-year partner,Rutgers,900000,2018,,
Multi-year partner,Save the Children Nederland,900000,2018,,
Multi-year partner,Sea Shepherd,900000,2018,,
Multi-year partner,The Sentry,900000,2018,,
Multi-year partner,Simavi,900000,2018,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2018,,
Multi-year partner,Wilde Ganzen,900000,2018,,
Multi-year partner,AAP,500000,2018,,
Multi-year partner,Aflatoun International,500000,2018,,
Multi-year partner,Both ENDS,500000,2018,,
Multi-year partner,Carbon War Room,500000,2018,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2018,,
Multi-year partner,Dance4Life,500000,2018,,
Multi-year partner,Defence for Children,500000,2018,,
Multi-year partner,Dokters van de Wereld,500000,2018,,
Multi-year partner,Dr. Denis Mukwege Foundation,500000,2018,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2018,,
Multi-year partner,Edukans,500000,2018,,
Multi-year partner,The Elders,500000,2018,,
Multi-year partner,Fairfood,500000,2018,,
Multi-year partner,Girls Not Brides,500000,2018,,
Multi-year partner,Global Witness,500000,2018,,
Multi-year partner,The Hunger Project,500000,2018,,
Multi-year partner,IMC Weekendschool,500000,2018,,
Multi-year partner,JINC,500000,2018,,
Multi-year partner,Kinderfonds MAMAS,500000,2018,,
Multi-year partner,Krajicek Foundation,500000,2018,,
Multi-year partner,LINDA.foundation,500000,2018,,
Multi-year partner,Lokale Fondsen Nederland,500000,2018,,
Multi-year partner,Marine Stewardship Council,500000,2018,,
Multi-year partner,Movies that Matter,500000,2018,,
Multi-year partner,PAX,500000,2018,,
Multi-year partner,Prins Claus Fonds,500000,2018,,
Multi-year partner,Rafa Nadal Foundation,500000,2018,,
Multi-year partner,Resto VanHarte,500000,2018,,
Multi-year partner,Right To Play,500000,2018,,
Multi-year partner,Roger Federer Foundation,500000,2018,,
Multi-year partner,Scouting Nederland,500000,2018,,
Multi-year partner,Stichting De Noordzee,500000,2018,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2018,,
Multi-year partner,De Vrolijkheid,500000,2018,,
Multi-year partner,Urgenda,500000,2018,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2018,,
Multi-year partner,Voedselbanken Nederland,500000,2018,,
Multi-year partner,Waddenvereniging,500000,2018,,
Multi-year partner,Wakker Dier,500000,2018,,
Multi-year partner,Wildlife Justice Commission,500000,2018,,
Multi-year partner,WOMEN Inc.,500000,2018,,
Multi-year partner,World Press Photo,500000,2018,,
Multi-year partner,YY Foundation,500000,2018,,
SUBTOTAAL Multi-year partner,107 organisaties,265720159,2018,,
One-time donation,Theirworld - Education in Emergencies,3150000,2018,,
One-time donation,War Child,2500000,2018,,
One-time donation,Greenpeace,2000000,2018,,
One-time donation,RAVON en Good Fish Foundation,2000000,2018,,
One-time donation,Wereld Natuur Fonds,2000000,2018,,
One-time donation,Amref Health Africa,1000000,2018,,
One-time donation,Forest Stewardship Council (FSC),1000000,2018,,
One-time donation,The Hague Institute for Innovation of Law (HiiL),1000000,2018,,
One-time donation,HIER klimaatbureau,1000000,2018,,
One-time donation,International Consortium of Investigative Journalists (ICIJ),1000000,2018,,
One-time donation,Justice and Peace - Shelter City Initiative,1000000,2018,,
One-time donation,Nederlandse Helsinki Comité,1000000,2018,,
One-time donation,Rare,1000000,2018,,
One-time donation,Young Africa,1000000,2018,,
One-time donation,Bellingcat,500000,2018,,
SUBTOTAAL One-time donation,15 organisaties,20150000,2018,,
Extra contribution to multi-year partners,Free Press Unlimited,3500000,2018,,
Extra contribution to multi-year partners,Peace Parks Foundation,3000000,2018,,
Extra contribution to multi-year partners,Terre des Hommes,2970000,2018,,
Extra contribution to multi-year partners,Rocky Mountain Institute,2800000,2018,,
Extra contribution to multi-year partners,IUCN NL,2400000,2018,,
Extra contribution to multi-year partners,Stichting Vluchteling,2400000,2018,,
Extra contribution to multi-year partners,Plan International,2160000,2018,,
Extra contribution to multi-year partners,European Climate Foundation,2000000,2018,,
Extra contribution to multi-year partners,IVN Natuureducatie,1950000,2018,,
Extra contribution to multi-year partners,Clinton Foundation,1850000,2018,,
Extra contribution to multi-year partners,De Natuur en Milieufederaties,1650000,2018,,
Extra contribution to multi-year partners,Urgenda,1605000,2018,,
Extra contribution to multi-year partners,PAX,1569000,2018,,
Extra contribution to multi-year partners,CARE Nederland,1500000,2018,,
Extra contribution to multi-year partners,Prins Claus Fonds,1305000,2018,,
Extra contribution to multi-year partners,World Press Photo,1190000,2018,,
Extra contribution to multi-year partners,JINC,850000,2018,,
Extra contribution to multi-year partners,Rafa Nadal Foundation,500000,2018,,
SUBTOTAAL Extra bijdrage,18 projecten,35199000,2018,,
Dream Fund,Vogelbescherming Nederland,15000000,2018,,
Dream Fund,Natuur & Milieu,8500000,2018,,
SUBTOTAAL Dream Fund,2 projecten,23500000,2018,,
TOTAAL 2018,142 entries,344569159,2018,,
Multi-year partner,Stichting DOEN,22500676,2019,,
Multi-year partner,Oranje Fonds,15000000,2019,,
Multi-year partner,Artsen zonder Grenzen,13500000,2019,,
Multi-year partner,LandschappenNL,13500000,2019,,
Multi-year partner,Natuurmonumenten,13500000,2019,,
Multi-year partner,Oxfam Novib,13500000,2019,,
Multi-year partner,UNICEF,13500000,2019,,
Multi-year partner,Wereld Natuur Fonds,13500000,2019,,
Multi-year partner,Kansfonds,10000000,2019,,
Multi-year partner,Vfonds,10000000,2019,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2019,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2019,,
Multi-year partner,Humanitas,4500000,2019,,
Multi-year partner,Amnesty International,3600000,2019,,
Multi-year partner,Plan International,3150000,2019,,
Multi-year partner,Cordaid,2700000,2019,,
Multi-year partner,Stichting Vluchteling,2700000,2019,,
Multi-year partner,Aidsfonds,2250000,2019,,
Multi-year partner,Greenpeace,2250000,2019,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2019,,
Multi-year partner,Terre des Hommes,2250000,2019,,
Multi-year partner,UNHCR,2250000,2019,,
Multi-year partner,Postcode Lottery Green Challenge,2200000,2019,,
Multi-year partner,Clinton Foundation,1800000,2019,,
Multi-year partner,Dierenbescherming,1800000,2019,,
Multi-year partner,Natuur & Milieu,1800000,2019,,
Multi-year partner,Vogelbescherming Nederland,1800000,2019,,
Multi-year partner,Hivos,1350000,2019,,
Multi-year partner,Human Rights Watch,1350000,2019,,
Multi-year partner,ICCO,1350000,2019,,
Multi-year partner,IVN Natuureducatie,1350000,2019,,
Multi-year partner,Johan Cruyff Foundation,1350000,2019,,
Multi-year partner,Leprastichting,1350000,2019,,
Multi-year partner,Liliane Fonds,1350000,2019,,
Multi-year partner,Mama Cash,1350000,2019,,
Multi-year partner,Milieudefensie,1350000,2019,,
Multi-year partner,Peace Parks Foundation,1350000,2019,,
Multi-year partner,Solidaridad,1350000,2019,,
Multi-year partner,SOS Kinderdorpen,1350000,2019,,
Multi-year partner,Theirworld,1350000,2019,,
Multi-year partner,War Child,1350000,2019,,
Multi-year partner,World Food Programme,1350000,2019,,
Multi-year partner,African Parks Network,900000,2019,,
Multi-year partner,Amref Health Africa,900000,2019,,
Multi-year partner,ARK Rewilding Nederland,900000,2019,,
Multi-year partner,CARE Nederland,900000,2019,,
Multi-year partner,The Climate Group,900000,2019,,
Multi-year partner,Commonland,900000,2019,,
Multi-year partner,Dr. Denis Mukwege Foundation,900000,2019,,
Multi-year partner,European Climate Foundation,900000,2019,,
Multi-year partner,Free Press Unlimited,900000,2019,,
Multi-year partner,Goois Natuurreservaat,900000,2019,,
Multi-year partner,IUCN NL,900000,2019,,
Multi-year partner,KNCV Tuberculosefonds,900000,2019,,
Multi-year partner,PharmAccess,900000,2019,,
Multi-year partner,Rewilding Europe,900000,2019,,
Multi-year partner,Rocky Mountain Institute,900000,2019,,
Multi-year partner,Rutgers,900000,2019,,
Multi-year partner,Save the Children Nederland,900000,2019,,
Multi-year partner,Sea Shepherd,900000,2019,,
Multi-year partner,The Sentry,900000,2019,,
Multi-year partner,Simavi,900000,2019,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2019,,
Multi-year partner,Wilde Ganzen,900000,2019,,
Multi-year partner,AAP,500000,2019,,
Multi-year partner,Aflatoun International,500000,2019,,
Multi-year partner,Both ENDS,500000,2019,,
Multi-year partner,Carbon War Room,500000,2019,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2019,,
Multi-year partner,Dance4Life,500000,2019,,
Multi-year partner,Defence for Children,500000,2019,,
Multi-year partner,Dokters van de Wereld,500000,2019,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2019,,
Multi-year partner,Edukans,500000,2019,,
Multi-year partner,The Elders,500000,2019,,
Multi-year partner,Fairfood,500000,2019,,
Multi-year partner,Girls Not Brides,500000,2019,,
Multi-year partner,Global Witness,500000,2019,,
Multi-year partner,The Hunger Project,500000,2019,,
Multi-year partner,IMC Weekendschool,500000,2019,,
Multi-year partner,JINC,500000,2019,,
Multi-year partner,Kinderfonds MAMAS,500000,2019,,
Multi-year partner,Krajicek Foundation,500000,2019,,
Multi-year partner,LINDA.foundation,500000,2019,,
Multi-year partner,Marine Stewardship Council,500000,2019,,
Multi-year partner,Movies that Matter,500000,2019,,
Multi-year partner,PAX,500000,2019,,
Multi-year partner,Prins Claus Fonds,500000,2019,,
Multi-year partner,Rafa Nadal Foundation,500000,2019,,
Multi-year partner,Resto VanHarte,500000,2019,,
Multi-year partner,Right To Play,500000,2019,,
Multi-year partner,Roger Federer Foundation,500000,2019,,
Multi-year partner,Scouting Nederland,500000,2019,,
Multi-year partner,Stichting De Noordzee,500000,2019,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2019,,
Multi-year partner,De Vrolijkheid,500000,2019,,
Multi-year partner,Urgenda,500000,2019,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2019,,
Multi-year partner,Voedselbanken Nederland,500000,2019,,
Multi-year partner,Waddenvereniging,500000,2019,,
Multi-year partner,Wakker Dier,500000,2019,,
Multi-year partner,Wildlife Justice Commission,500000,2019,,
Multi-year partner,WOMEN Inc.,500000,2019,,
Multi-year partner,World Press Photo,500000,2019,,
Multi-year partner,YY Foundation,500000,2019,,
SUBTOTAAL Multi-year partner,105 organisaties,251750676,2019,,
One-time donation,Stichting DOEN,4500000,2019,,
One-time donation,Deltaplan Biodiversiteitsherstel,1500000,2019,,
One-time donation,KidsRights,1500000,2019,,
One-time donation,Leger des Heils,1500000,2019,,
One-time donation,Thorn,1500000,2019,,
One-time donation,Amazon Frontlines,1000000,2019,,
One-time donation,Amref Health Africa,1000000,2019,,
One-time donation,Cordaid,1000000,2019,,
One-time donation,Fonds Slachtofferhulp en Centrum Seksueel Geweld,1000000,2019,,
One-time donation,Free a Girl,1000000,2019,,
One-time donation,Healthy Entrepreneurs,1000000,2019,,
One-time donation,Hivos,1000000,2019,,
One-time donation,ICCO en Solidaridad,1000000,2019,,
One-time donation,Oceana,1000000,2019,,
One-time donation,Oxfam Novib,1000000,2019,,
One-time donation,Plastic Soup Foundation,1000000,2019,,
One-time donation,Rewilding Europe,1000000,2019,,
One-time donation,SoortenNL,1000000,2019,,
One-time donation,SPARK,1000000,2019,,
One-time donation,Stichting leerKRACHT,1000000,2019,,
One-time donation,Trees for All,1000000,2019,,
One-time donation,Vogelbescherming Nederland,1000000,2019,,
One-time donation,100WEEKS,500000,2019,,
One-time donation,Sea Ranger Service,500000,2019,,
One-time donation,Space Buzz Foundation,500000,2019,,
One-time donation,Stichting Elisabeth Samson Huis,500000,2019,,
One-time donation,Resto VanHarte,300000,2019,,
SUBTOTAAL One-time donation,27 organisaties,29800000,2019,,
Extra contribution to multi-year partners,The Sentry,6300000,2019,,
Extra contribution to multi-year partners,IUCN NL,2825000,2019,,
Extra contribution to multi-year partners,Krajicek Foundation,2500000,2019,,
Extra contribution to multi-year partners,YY Foundation,2490000,2019,,
Extra contribution to multi-year partners,LandschappenNL,2462500,2019,,
Extra contribution to multi-year partners,De Natuur en Milieufederaties,2250000,2019,,
Extra contribution to multi-year partners,Kinderfonds MAMAS,2200000,2019,,
Extra contribution to multi-year partners,Aidsfonds,2050000,2019,,
Extra contribution to multi-year partners,Sea Shepherd,1980000,2019,,
Extra contribution to multi-year partners,Het Nederlandse Rode Kruis,1975000,2019,,
Extra contribution to multi-year partners,Natuurmonumenten,1796000,2019,,
Extra contribution to multi-year partners,De Vrolijkheid,1595000,2019,,
Extra contribution to multi-year partners,Edukans,1550000,2019,,
Extra contribution to multi-year partners,Free Press Unlimited,1485000,2019,,
Extra contribution to multi-year partners,Johan Cruyff Foundation,1000000,2019,,
Extra contribution to multi-year partners,Voedselbanken Nederland,510000,2019,,
SUBTOTAAL Extra bijdrage,16 projecten,34968500,2019,,
Dream Fund,"Wereld Natuur Fonds, African Parks Network en Peace Parks Foundation",16900000,2019,,
Dream Fund,Amref Health Africa en PharmAccess (extra bijdrage Dream Fund 2015),1750000,2019,,
SUBTOTAAL Dream Fund,2 projecten,18650000,2019,,
TOTAAL 2019,150 entries,335169176,2019,,
Multi-year partner,Stichting DOEN,22500330,2020,,
Multi-year partner,Oranje Fonds,15000000,2020,,
Multi-year partner,Artsen zonder Grenzen,13500000,2020,,
Multi-year partner,LandschappenNL,13500000,2020,,
Multi-year partner,Natuurmonumenten,13500000,2020,,
Multi-year partner,Oxfam Novib,13500000,2020,,
Multi-year partner,UNICEF,13500000,2020,,
Multi-year partner,Wereld Natuur Fonds,13500000,2020,,
Multi-year partner,Kansfonds,10000000,2020,,
Multi-year partner,Vfonds,10000000,2020,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2020,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2020,,
Multi-year partner,Humanitas,4500000,2020,,
Multi-year partner,Amnesty International,3600000,2020,,
Multi-year partner,Plan International,3150000,2020,,
Multi-year partner,Cordaid,2700000,2020,,
Multi-year partner,Stichting Vluchteling,2700000,2020,,
Multi-year partner,Aidsfonds,2250000,2020,,
Multi-year partner,Greenpeace,2250000,2020,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2020,,
Multi-year partner,Terre des Hommes,2250000,2020,,
Multi-year partner,UNHCR,2250000,2020,,
Multi-year partner,Postcode Lottery Green Challenge,2200000,2020,,
Multi-year partner,Clinton Foundation,1800000,2020,,
Multi-year partner,Dierenbescherming,1800000,2020,,
Multi-year partner,Natuur & Milieu,1800000,2020,,
Multi-year partner,Vogelbescherming Nederland,1800000,2020,,
Multi-year partner,Hivos,1350000,2020,,
Multi-year partner,Human Rights Watch,1350000,2020,,
Multi-year partner,ICCO,1350000,2020,,
Multi-year partner,IVN Natuureducatie,1350000,2020,,
Multi-year partner,Johan Cruyff Foundation,1350000,2020,,
Multi-year partner,Leprastichting,1350000,2020,,
Multi-year partner,Liliane Fonds,1350000,2020,,
Multi-year partner,Mama Cash,1350000,2020,,
Multi-year partner,Milieudefensie,1350000,2020,,
Multi-year partner,Peace Parks Foundation,1350000,2020,,
Multi-year partner,Solidaridad,1350000,2020,,
Multi-year partner,SOS Kinderdorpen,1350000,2020,,
Multi-year partner,Theirworld,1350000,2020,,
Multi-year partner,War Child,1350000,2020,,
Multi-year partner,World Food Programme,1350000,2020,,
Multi-year partner,African Parks Network,900000,2020,,
Multi-year partner,Amref Health Africa,900000,2020,,
Multi-year partner,ARK Rewilding Nederland,900000,2020,,
Multi-year partner,CARE Nederland,900000,2020,,
Multi-year partner,The Climate Group,900000,2020,,
Multi-year partner,Commonland,900000,2020,,
Multi-year partner,Dr. Denis Mukwege Foundation,900000,2020,,
Multi-year partner,European Climate Foundation,900000,2020,,
Multi-year partner,Free Press Unlimited,900000,2020,,
Multi-year partner,Goois Natuurreservaat,900000,2020,,
Multi-year partner,IUCN NL,900000,2020,,
Multi-year partner,KNCV Tuberculosefonds,900000,2020,,
Multi-year partner,PharmAccess,900000,2020,,
Multi-year partner,Rewilding Europe,900000,2020,,
Multi-year partner,Rocky Mountain Institute,900000,2020,,
Multi-year partner,Rutgers,900000,2020,,
Multi-year partner,Save the Children Nederland,900000,2020,,
Multi-year partner,Sea Shepherd,900000,2020,,
Multi-year partner,The Sentry,900000,2020,,
Multi-year partner,Simavi,900000,2020,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2020,,
Multi-year partner,Wilde Ganzen,900000,2020,,
Multi-year partner,AAP,500000,2020,,
Multi-year partner,Aflatoun International,500000,2020,,
Multi-year partner,Both ENDS,500000,2020,,
Multi-year partner,Carbon War Room,500000,2020,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2020,,
Multi-year partner,Dance4Life,500000,2020,,
Multi-year partner,Defence for Children,500000,2020,,
Multi-year partner,Dokters van de Wereld,500000,2020,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2020,,
Multi-year partner,Edukans,500000,2020,,
Multi-year partner,The Elders,500000,2020,,
Multi-year partner,Fairfood,500000,2020,,
Multi-year partner,Girls Not Brides,500000,2020,,
Multi-year partner,Global Witness,500000,2020,,
Multi-year partner,The Hunger Project,500000,2020,,
Multi-year partner,IMC Weekendschool,500000,2020,,
Multi-year partner,JINC,500000,2020,,
Multi-year partner,Kinderfonds MAMAS,500000,2020,,
Multi-year partner,Krajicek Foundation,500000,2020,,
Multi-year partner,LINDA.foundation,500000,2020,,
Multi-year partner,Marine Stewardship Council,500000,2020,,
Multi-year partner,Movies that Matter,500000,2020,,
Multi-year partner,PAX,500000,2020,,
Multi-year partner,Prins Claus Fonds,500000,2020,,
Multi-year partner,Rafa Nadal Foundation,500000,2020,,
Multi-year partner,Resto VanHarte,500000,2020,,
Multi-year partner,Right To Play,500000,2020,,
Multi-year partner,Roger Federer Foundation,500000,2020,,
Multi-year partner,Scouting Nederland,500000,2020,,
Multi-year partner,Stichting De Noordzee,500000,2020,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2020,,
Multi-year partner,De Vrolijkheid,500000,2020,,
Multi-year partner,Urgenda,500000,2020,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2020,,
Multi-year partner,Voedselbanken Nederland,500000,2020,,
Multi-year partner,Waddenvereniging,500000,2020,,
Multi-year partner,Wakker Dier,500000,2020,,
Multi-year partner,Wildlife Justice Commission,500000,2020,,
Multi-year partner,WOMEN Inc.,500000,2020,,
Multi-year partner,World Press Photo,500000,2020,,
Multi-year partner,YY Foundation,500000,2020,,
SUBTOTAAL Multi-year partner,105 organisaties,251750330,2020,,
One-time donation,Het Nederlandse Rode Kruis,4893000,2020,,
One-time donation,Artsen zonder Grenzen,4000000,2020,,
One-time donation,Hivos,4000000,2020,,
One-time donation,SamenSpeelFonds,2000000,2020,,
One-time donation,Fauna & Flora International,1500000,2020,,
One-time donation,One Acre Fund,1500000,2020,,
One-time donation,RNW Media,1500000,2020,,
One-time donation,Wetlands International,1500000,2020,,
One-time donation,"Theirworld, UNHCR & UNICEF",1350000,2020,,
One-time donation,Bellingcat,1000000,2020,,
One-time donation,Girls First Fund,1000000,2020,,
One-time donation,Impunity Watch,1000000,2020,,
One-time donation,Landelijk Samenwerkingsverband Actieve Bewoners & Social Enterprise NL,1000000,2020,,
One-time donation,Nadia's Initiative,1000000,2020,,
One-time donation,Schone Kleren Campagne,1000000,2020,,
One-time donation,Stichting DierenLot,1000000,2020,,
One-time donation,Tropenbos International,1000000,2020,,
One-time donation,Lighthouse Reports,500000,2020,,
One-time donation,Het Vergeten Kind,500000,2020,,
One-time donation,Voedselbanken Nederland,500000,2020,,
One-time donation,Women Engage for a Common Future,500000,2020,,
One-time donation,World Fish Migration Foundation,500000,2020,,
One-time donation,Dokters van de Wereld,430000,2020,,
SUBTOTAAL One-time donation,23 organisaties,32173000,2020,,
Extra contribution to multi-year partners,Amnesty International,2583000,2020,,
Extra contribution to multi-year partners,Stichting Kinderpostzegels Nederland,2195000,2020,,
Extra contribution to multi-year partners,ARK Rewilding Nederland,2185000,2020,,
Extra contribution to multi-year partners,Aflatoun International,1950000,2020,,
Extra contribution to multi-year partners,Wildlife Justice Commission,1943000,2020,,
Extra contribution to multi-year partners,"Waddenvereniging, Stichting De Noordzee & De Natuur en Milieufederaties",1922000,2020,,
Extra contribution to multi-year partners,Centrum tegen Kinderhandel en Mensenhandel,1195000,2020,,
SUBTOTAAL Extra bijdrage,7 projecten,13973000,2020,,
Dream Fund,KNCV Tuberculosefonds,11100000,2020,,
Dream Fund,Natuurmonumenten,5000000,2020,,
SUBTOTAAL Dream Fund,2 projecten,16100000,2020,,
TOTAAL 2020,137 entries,313996330,2020,,
Multi-year partner,Stichting DOEN,22948095,2021,,
Multi-year partner,Oranje Fonds,15000000,2021,,
Multi-year partner,Natuurmonumenten,13726918,2021,,
Multi-year partner,Artsen zonder Grenzen,13500000,2021,,
Multi-year partner,LandschappenNL,13500000,2021,,
Multi-year partner,Oxfam Novib,13500000,2021,,
Multi-year partner,UNICEF,13500000,2021,,
Multi-year partner,Wereld Natuur Fonds,13500000,2021,,
Multi-year partner,Kansfonds,10000000,2021,,
Multi-year partner,Vfonds,10000000,2021,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2021,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2021,,
Multi-year partner,Humanitas,4500000,2021,,
Multi-year partner,Cordaid,4050000,2021,,
Multi-year partner,Amnesty International,3600000,2021,,
Multi-year partner,Plan International,3150000,2021,,
Multi-year partner,Stichting Vluchteling,2700000,2021,,
Multi-year partner,Aidsfonds,2250000,2021,,
Multi-year partner,Greenpeace,2250000,2021,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2021,,
Multi-year partner,Terre des Hommes,2250000,2021,,
Multi-year partner,UNHCR,2250000,2021,,
Multi-year partner,Postcode Lottery Green Challenge,2200000,2021,,
Multi-year partner,Clinton Foundation,1800000,2021,,
Multi-year partner,Dierenbescherming,1800000,2021,,
Multi-year partner,Natuur & Milieu,1800000,2021,,
Multi-year partner,Vogelbescherming Nederland,1800000,2021,,
Multi-year partner,Fonds Slachtofferhulp,1350000,2021,,
Multi-year partner,Hivos,1350000,2021,,
Multi-year partner,Human Rights Watch,1350000,2021,,
Multi-year partner,IVN Natuureducatie,1350000,2021,,
Multi-year partner,Johan Cruyff Foundation,1350000,2021,,
Multi-year partner,Kinderhulp,1350000,2021,,
Multi-year partner,Leprastichting,1350000,2021,,
Multi-year partner,Liliane Fonds,1350000,2021,,
Multi-year partner,Mama Cash,1350000,2021,,
Multi-year partner,Milieudefensie,1350000,2021,,
Multi-year partner,Peace Parks Foundation,1350000,2021,,
Multi-year partner,Solidaridad,1350000,2021,,
Multi-year partner,SOS Kinderdorpen,1350000,2021,,
Multi-year partner,Theirworld,1350000,2021,,
Multi-year partner,War Child,1350000,2021,,
Multi-year partner,World Food Programme,1350000,2021,,
Multi-year partner,HandicapNL,1100000,2021,,
Multi-year partner,AMC Foundation Medicijn voor de maatschappij,1000000,2021,,
Multi-year partner,African Parks Network,900000,2021,,
Multi-year partner,Amref Health Africa,900000,2021,,
Multi-year partner,ARK Rewilding Nederland,900000,2021,,
Multi-year partner,CARE Nederland,900000,2021,,
Multi-year partner,The Climate Group,900000,2021,,
Multi-year partner,Commonland,900000,2021,,
Multi-year partner,Dr. Denis Mukwege Foundation,900000,2021,,
Multi-year partner,Diabetes Fonds,900000,2021,,
Multi-year partner,European Climate Foundation,900000,2021,,
Multi-year partner,Free Press Unlimited,900000,2021,,
Multi-year partner,Goois Natuurreservaat,900000,2021,,
Multi-year partner,Hartstichting,900000,2021,,
Multi-year partner,Hersenstichting,900000,2021,,
Multi-year partner,IUCN NL,900000,2021,,
Multi-year partner,Jantje Beton,900000,2021,,
Multi-year partner,KNCV Tuberculosefonds,900000,2021,,
Multi-year partner,KWF Kankerbestrijding,900000,2021,,
Multi-year partner,Longfonds,900000,2021,,
Multi-year partner,MDL Fonds,900000,2021,,
Multi-year partner,MIND,900000,2021,,
Multi-year partner,Nederlandse Brandwonden Stichting,900000,2021,,
Multi-year partner,Nierstichting,900000,2021,,
Multi-year partner,PharmAccess,900000,2021,,
Multi-year partner,Prinses Beatrix Spierfonds,900000,2021,,
Multi-year partner,ReumaNederland,900000,2021,,
Multi-year partner,Rewilding Europe,900000,2021,,
Multi-year partner,Rocky Mountain Institute,900000,2021,,
Multi-year partner,Rutgers,900000,2021,,
Multi-year partner,Save the Children Nederland,900000,2021,,
Multi-year partner,Sea Shepherd,900000,2021,,
Multi-year partner,The Sentry,900000,2021,,
Multi-year partner,Simavi,900000,2021,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2021,,
Multi-year partner,Wilde Ganzen,900000,2021,,
Multi-year partner,AAP,500000,2021,,
Multi-year partner,Aflatoun International,500000,2021,,
Multi-year partner,Both ENDS,500000,2021,,
Multi-year partner,Carbon War Room,500000,2021,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2021,,
Multi-year partner,Dance4Life,500000,2021,,
Multi-year partner,Defence for Children,500000,2021,,
Multi-year partner,Dokters van de Wereld,500000,2021,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2021,,
Multi-year partner,Edukans,500000,2021,,
Multi-year partner,The Elders,500000,2021,,
Multi-year partner,Fairfood,500000,2021,,
Multi-year partner,Girls Not Brides,500000,2021,,
Multi-year partner,Global Witness,500000,2021,,
Multi-year partner,The Hunger Project,500000,2021,,
Multi-year partner,IMC Weekendschool,500000,2021,,
Multi-year partner,Jeugdfonds Sport & Cultuur,500000,2021,,
Multi-year partner,JINC,500000,2021,,
Multi-year partner,Kinderfonds MAMAS,500000,2021,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2021,,
Multi-year partner,Krajicek Foundation,500000,2021,,
Multi-year partner,LINDA.foundation,500000,2021,,
Multi-year partner,Marine Stewardship Council,500000,2021,,
Multi-year partner,Movies that Matter,500000,2021,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2021,,
Multi-year partner,Stichting De Noordzee,500000,2021,,
Multi-year partner,PAX,500000,2021,,
Multi-year partner,Prins Claus Fonds,500000,2021,,
Multi-year partner,Rafa Nadal Foundation,500000,2021,,
Multi-year partner,Resto VanHarte,500000,2021,,
Multi-year partner,Right To Play,500000,2021,,
Multi-year partner,Roger Federer Foundation,500000,2021,,
Multi-year partner,Scouting Nederland,500000,2021,,
Multi-year partner,Urgenda,500000,2021,,
Multi-year partner,De Vrolijkheid,500000,2021,,
Multi-year partner,Voedselbanken Nederland,500000,2021,,
Multi-year partner,Waddenvereniging,500000,2021,,
Multi-year partner,Wakker Dier,500000,2021,,
Multi-year partner,Wildlife Justice Commission,500000,2021,,
Multi-year partner,WOMEN Inc.,500000,2021,,
Multi-year partner,World Press Photo,500000,2021,,
Multi-year partner,YY Foundation,500000,2021,,
Multi-year partner,EpilepsieNL,250000,2021,,
Multi-year partner,Fonds Gehandicaptensport,250000,2021,,
Multi-year partner,Make-A-Wish Nederland,250000,2021,,
Multi-year partner,Alzheimer Nederland,200000,2021,,
Multi-year partner,Bas van de Goor Foundation,200000,2021,,
Multi-year partner,Stichting het Gehandicapte Kind,200000,2021,,
Multi-year partner,Hulphond Nederland,200000,2021,,
Multi-year partner,Leergeld Nederland,200000,2021,,
Multi-year partner,Stichting Lezen en Schrijven,200000,2021,,
Multi-year partner,Stichting Life Goals Nederland,200000,2021,,
Multi-year partner,Metakids,200000,2021,,
Multi-year partner,Stichting MS Research,200000,2021,,
Multi-year partner,Stichting Jarige Job,200000,2021,,
Multi-year partner,Nederlandse Vereniging voor Autisme,200000,2021,,
Multi-year partner,Oogfonds,200000,2021,,
Multi-year partner,Nationaal Ouderenfonds,200000,2021,,
Multi-year partner,Pink Ribbon,200000,2021,,
Multi-year partner,Spieren voor Spieren,200000,2021,,
Multi-year partner,Het Vergeten Kind,200000,2021,,
Multi-year partner,Vier het Leven,200000,2021,,
Multi-year partner,Nationale Vereniging de Zonnebloem,200000,2021,,
Multi-year partner,Dirk Kuyt Foundation,100000,2021,,
Multi-year partner,Edwin van der Sar Foundation,100000,2021,,
Multi-year partner,Esther Vergeer Foundation,100000,2021,,
Multi-year partner,Giovanni van Bronckhorst Foundation,100000,2021,,
Multi-year partner,Stichting Herman van Veen Arts Center Fonds,100000,2021,,
Multi-year partner,Yvonne van Gennip Talent Fonds,100000,2021,,
SUBTOTAAL Multi-year partner,148 organisaties,259975013,2021,,
 , , , ,,
One-time donation,International Fund for Animal Welfare (IFAW),1500000,2021,,
One-time donation,Media Development Investment Fund (MDIF),1500000,2021,,
One-time donation,National Geographic Society,1500000,2021,,
One-time donation,Triggerise,1500000,2021,,
One-time donation,Bijzondere uitkeringen,1340744,2021,,
One-time donation,100WEEKS,1000000,2021,,
One-time donation,ActionAid Nederland,1000000,2021,,
One-time donation,Justdiggit,1000000,2021,,
One-time donation,Organized Crime and Corruption Reporting Project (OCCRP),1000000,2021,,
One-time donation,The Fund for Global Human Rights,1000000,2021,,
One-time donation,ParkinsonNL,900000,2021,,
One-time donation,Stichting ALS Nederland,900000,2021,,
One-time donation,Stichting IPSO,800000,2021,,
One-time donation,Stichting Refugee Company,750000,2021,,
One-time donation,Stichting De Schoolschrijver,650000,2021,,
One-time donation,Jeugdeducatiefonds,588000,2021,,
One-time donation,Break Free from Plastic (BFFP),500000,2021,,
One-time donation,De Buzinezzclub,500000,2021,,
One-time donation,Dona Daria,500000,2021,,
One-time donation,Global Fishing Watch,500000,2021,,
One-time donation,Kinderziekenhuizen van Oranje,500000,2021,,
One-time donation,Movement on the Ground,500000,2021,,
One-time donation,Red Umbrella Fund,500000,2021,,
One-time donation,Stichting Mainline,500000,2021,,
One-time donation,Stichting Move,500000,2021,,
One-time donation,Stichting Thuisgekookt,500000,2021,,
One-time donation,Wemos,500000,2021,,
One-time donation,Young Impact,500000,2021,,
One-time donation,Stichting Gilat,400000,2021,,
SUBTOTAAL One-time donation,29 organisaties,23328744,2021,,
 , , , ,,
Extra contribution to multi-year partners,Het Nederlandse Rode Kruis,3100000,2021,,
Extra contribution to multi-year partners,UNICEF,2334000,2021,,
Extra contribution to multi-year partners,Wilde Ganzen,2200000,2021,,
Extra contribution to multi-year partners,Wereld Natuur Fonds,2000000,2021,,
Extra contribution to multi-year partners,Cordaid,1800000,2021,,
Extra contribution to multi-year partners,IVN Natuureducatie,1800000,2021,,
Extra contribution to multi-year partners,Vogelbescherming Nederland,1700000,2021,,
Extra contribution to multi-year partners,Both ENDS,1380000,2021,,
Extra contribution to multi-year partners,Johan Cruyff Foundation,1000000,2021,,
Extra contribution to multi-year partners,KWF Kankerbestrijding,1000000,2021,,
Extra contribution to multi-year partners,AAP,750000,2021,,
Extra contribution to multi-year partners,Stichting MS Research,660000,2021,,
Extra contribution to multi-year partners,Dr. Denis Mukwege Foundation,500000,2021,,
Extra contribution to multi-year partners,Free Press Unlimited,500000,2021,,
Extra contribution to multi-year partners,MDL Fonds,500000,2021,,
Extra contribution to multi-year partners,HandicapNL,483000,2021,,
Extra contribution to multi-year partners,Stichting Lezen en Schrijven,375000,2021,,
Extra contribution to multi-year partners,EpilepsieNL,235000,2021,,
SUBTOTAAL Extra bijdrage,18 projecten,22317000,2021,,
Dream Fund,Solidaridad - Van Klimaatslachtoffers naar Klimaathelden,12731322,2021,,
SUBTOTAAL Dream Fund,1 project,12731322,2021,,
TOTAAL 2021,196 entries,318352079,2021,,
Multi-year partner,Stichting DOEN,18000000,2022,,
Multi-year partner,Oranje Fonds,15000000,2022,,
Multi-year partner,Artsen zonder Grenzen,13500000,2022,,
Multi-year partner,LandschappenNL,13500000,2022,,
Multi-year partner,Oxfam Novib,13500000,2022,,
Multi-year partner,UNICEF,13500000,2022,,
Multi-year partner,Wereld Natuur Fonds,13500000,2022,,
Multi-year partner,Natuurmonumenten,13718655,2022,,
Multi-year partner,Kansfonds,10000000,2022,,
Multi-year partner,Vfonds,10000000,2022,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2022,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2022,,
Multi-year partner,Postcode Loterij Buurtfonds,5137146,2022,,
Multi-year partner,Humanitas,4500000,2022,,
Multi-year partner,Cordaid,4050000,2022,,
Multi-year partner,Amnesty International,3600000,2022,,
Multi-year partner,Plan International,3150000,2022,,
Multi-year partner,Stichting Vluchteling,2700000,2022,,
Multi-year partner,Aidsfonds,2250000,2022,,
Multi-year partner,Greenpeace,2250000,2022,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2022,,
Multi-year partner,Terre des Hommes,2250000,2022,,
Multi-year partner,UNHCR,2250000,2022,,
Multi-year partner,Clinton Foundation,1800000,2022,,
Multi-year partner,Dierenbescherming,1800000,2022,,
Multi-year partner,Natuur & Milieu,1800000,2022,,
Multi-year partner,Vogelbescherming Nederland,1800000,2022,,
Multi-year partner,Fonds Slachtofferhulp,1350000,2022,,
Multi-year partner,Hivos,1350000,2022,,
Multi-year partner,Human Rights Watch,1350000,2022,,
Multi-year partner,IVN Natuureducatie,1350000,2022,,
Multi-year partner,Johan Cruyff Foundation,1350000,2022,,
Multi-year partner,Kinderhulp,1350000,2022,,
Multi-year partner,Leprastichting,1350000,2022,,
Multi-year partner,Liliane Fonds,1350000,2022,,
Multi-year partner,Mama Cash,1350000,2022,,
Multi-year partner,Milieudefensie,1350000,2022,,
Multi-year partner,Peace Parks Foundation,1350000,2022,,
Multi-year partner,Solidaridad,1350000,2022,,
Multi-year partner,SOS Kinderdorpen,1350000,2022,,
Multi-year partner,War Child,1350000,2022,,
Multi-year partner,World Food Programme,1350000,2022,,
Multi-year partner,AMC Foundation Medicijn voor de maatschappij,1000000,2022,,
Multi-year partner,African Parks Network,900000,2022,,
Multi-year partner,Alzheimer Nederland,900000,2022,,
Multi-year partner,Amref Health Africa,900000,2022,,
Multi-year partner,ARK Rewilding Nederland,900000,2022,,
Multi-year partner,CARE Nederland,900000,2022,,
Multi-year partner,The Climate Group,900000,2022,,
Multi-year partner,Commonland,900000,2022,,
Multi-year partner,Dr. Denis Mukwege Foundation,900000,2022,,
Multi-year partner,Diabetes Fonds,900000,2022,,
Multi-year partner,European Climate Foundation,900000,2022,,
Multi-year partner,Free Press Unlimited,900000,2022,,
Multi-year partner,Goois Natuurreservaat,900000,2022,,
Multi-year partner,HandicapNL,900000,2022,,
Multi-year partner,Hartstichting,900000,2022,,
Multi-year partner,Hersenstichting,900000,2022,,
Multi-year partner,IUCN NL,900000,2022,,
Multi-year partner,Jantje Beton,900000,2022,,
Multi-year partner,KNCV Tuberculosefonds,900000,2022,,
Multi-year partner,KWF Kankerbestrijding,900000,2022,,
Multi-year partner,Longfonds,900000,2022,,
Multi-year partner,MDL Fonds,900000,2022,,
Multi-year partner,MIND,900000,2022,,
Multi-year partner,Nederlandse Brandwonden Stichting,900000,2022,,
Multi-year partner,Nierstichting,900000,2022,,
Multi-year partner,PharmAccess,900000,2022,,
Multi-year partner,Prinses Beatrix Spierfonds,900000,2022,,
Multi-year partner,ReumaNederland,900000,2022,,
Multi-year partner,Rewilding Europe,900000,2022,,
Multi-year partner,Rocky Mountain Institute,900000,2022,,
Multi-year partner,Rutgers,900000,2022,,
Multi-year partner,Save the Children Nederland,900000,2022,,
Multi-year partner,Sea Shepherd,900000,2022,,
Multi-year partner,The Sentry,900000,2022,,
Multi-year partner,Simavi,900000,2022,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2022,,
Multi-year partner,Theirworld,900000,2022,,
Multi-year partner,Voedselbanken Nederland,900000,2022,,
Multi-year partner,Wilde Ganzen,900000,2022,,
Multi-year partner,AAP,500000,2022,,
Multi-year partner,Aflatoun International,500000,2022,,
Multi-year partner,Both ENDS,500000,2022,,
Multi-year partner,Carbon War Room,500000,2022,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2022,,
Multi-year partner,Dance4Life,500000,2022,,
Multi-year partner,Defence for Children,500000,2022,,
Multi-year partner,Dokters van de Wereld,500000,2022,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2022,,
Multi-year partner,Edukans,500000,2022,,
Multi-year partner,The Elders,500000,2022,,
Multi-year partner,Fairfood,500000,2022,,
Multi-year partner,Girls Not Brides,500000,2022,,
Multi-year partner,Global Witness,500000,2022,,
Multi-year partner,The Hunger Project,500000,2022,,
Multi-year partner,IMC Weekendschool,500000,2022,,
Multi-year partner,Jeugdeducatiefonds,500000,2022,,
Multi-year partner,Jeugdfonds Sport & Cultuur,500000,2022,,
Multi-year partner,JINC,500000,2022,,
Multi-year partner,Kinderfonds MAMAS,500000,2022,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2022,,
Multi-year partner,Krajicek Foundation,500000,2022,,
Multi-year partner,LINDA.foundation,500000,2022,,
Multi-year partner,Marine Stewardship Council,500000,2022,,
Multi-year partner,Movies that Matter,500000,2022,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2022,,
Multi-year partner,Stichting De Noordzee,500000,2022,,
Multi-year partner,PAX,500000,2022,,
Multi-year partner,Prins Claus Fonds,500000,2022,,
Multi-year partner,Rafa Nadal Foundation,500000,2022,,
Multi-year partner,Resto VanHarte,500000,2022,,
Multi-year partner,Right To Play,500000,2022,,
Multi-year partner,Roger Federer Foundation,500000,2022,,
Multi-year partner,Scouting Nederland,500000,2022,,
Multi-year partner,Urgenda,500000,2022,,
Multi-year partner,Het Vergeten Kind,500000,2022,,
Multi-year partner,De Vrolijkheid,500000,2022,,
Multi-year partner,Waddenvereniging,500000,2022,,
Multi-year partner,Wakker Dier,500000,2022,,
Multi-year partner,Wildlife Justice Commission,500000,2022,,
Multi-year partner,WOMEN Inc.,500000,2022,,
Multi-year partner,World Press Photo,500000,2022,,
Multi-year partner,YY Foundation,500000,2022,,
Multi-year partner,Bas van de Goor Foundation,300000,2022,,
Multi-year partner,EpilepsieNL,300000,2022,,
Multi-year partner,Esther Vergeer Foundation,300000,2022,,
Multi-year partner,Fonds Gehandicaptensport,300000,2022,,
Multi-year partner,Stichting het Gehandicapte Kind,300000,2022,,
Multi-year partner,Hulphond Nederland,300000,2022,,
Multi-year partner,Stichting Jarige Job,300000,2022,,
Multi-year partner,Leergeld Nederland,300000,2022,,
Multi-year partner,Stichting Lezen en Schrijven,300000,2022,,
Multi-year partner,Stichting Life Goals Nederland,300000,2022,,
Multi-year partner,Make-A-Wish Nederland,300000,2022,,
Multi-year partner,Metakids,300000,2022,,
Multi-year partner,Stichting MS Research,300000,2022,,
Multi-year partner,Nederlandse Vereniging voor Autisme,300000,2022,,
Multi-year partner,Oogfonds,300000,2022,,
Multi-year partner,Nationaal Ouderenfonds,300000,2022,,
Multi-year partner,Spieren voor Spieren,300000,2022,,
Multi-year partner,Vier het Leven,300000,2022,,
Multi-year partner,Nationale Vereniging de Zonnebloem,300000,2022,,
Multi-year partner,Pink Ribbon,200000,2022,,
Multi-year partner,Dirk Kuyt Foundation,100000,2022,,
Multi-year partner,Edwin van der Sar Foundation,100000,2022,,
Multi-year partner,Giovanni van Bronckhorst Foundation,100000,2022,,
Multi-year partner,Stichting Herman van Veen Arts Center Fonds,100000,2022,,
Multi-year partner,Yvonne van Gennip Talent Fonds,100000,2022,,
SUBTOTAAL Multi-year partner,146 organisaties,275525099,2022,,
One-time donation,Bureau Burgerberaad,500000,2022,,
One-time donation,CNV Internationaal,1000000,2022,,
One-time donation,Drugs for Neglected Diseases Initiative,1000000,2022,,
One-time donation,Everyday Heroes,400000,2022,,
One-time donation,Freedom House,1000000,2022,,
One-time donation,Healthy Entrepreneurs,1000000,2022,,
One-time donation,IDFA Bertha Fonds,500000,2022,,
One-time donation,Internews,500000,2022,,
One-time donation,Maggies Centers Nederland,1000000,2022,,
One-time donation,Nederlandse Helsinki Comité,500000,2022,,
One-time donation,ProVeg Nederland,500000,2022,,
One-time donation,Ronald McDonald Kinderfonds,1000000,2022,,
One-time donation,Room to Read,500000,2022,,
One-time donation,SoortenNL,800000,2022,,
One-time donation,Space Buzz Foundation,500000,2022,,
One-time donation,Stichting ease,400000,2022,,
One-time donation,Stichting Join Us,500000,2022,,
One-time donation,Stichting KiKiD,400000,2022,,
One-time donation,Stichting Onderzoek Multinationale Ondernemingen,1000000,2022,,
One-time donation,Trees for All,1000000,2022,,
One-time donation,What Design Can Do,500000,2022,,
SUBTOTAAL One-time donation,21 organisaties,14500000,2022,,
Extra contribution to multi-year partners,Rutgers,4530000,2022,,
Extra contribution to multi-year partners,Oxfam Novib,4200000,2022,,
Extra contribution to multi-year partners,Free Press Unlimited,4000000,2022,,
Extra contribution to multi-year partners,Wereld Natuur Fonds en Het Rode Kruis,3000000,2022,,
Extra contribution to multi-year partners,Amref Health Africa,2000000,2022,,
Extra contribution to multi-year partners,De Natuur en Milieufederaties,2000000,2022,,
Extra contribution to multi-year partners,VluchtelingenWerk Nederland,2000000,2022,,
Extra contribution to multi-year partners,IUCN NL,1800000,2022,,
Extra contribution to multi-year partners,Longfonds,1500000,2022,,
Extra contribution to multi-year partners,LandschappenNL,1505000,2022,,
Extra contribution to multi-year partners,Stichting het Gehandicapte Kind,1200000,2022,,
Extra contribution to multi-year partners,Cordaid,1400000,2022,,
Extra contribution to multi-year partners,WOMEN Inc.,800000,2022,,
Extra contribution to multi-year partners,LINDA.foundation,660000,2022,,
Extra contribution to multi-year partners,World Food Programme,600000,2022,,
Extra contribution to multi-year partners,Vier het Leven,550000,2022,,
Extra contribution to multi-year partners,Dokters van de Wereld,500000,2022,,
Extra contribution to multi-year partners,Hivos,500000,2022,,
Extra contribution to multi-year partners,Jeugdfonds Sport & Cultuur,500000,2022,,
Extra contribution to multi-year partners,Leergeld Nederland,500000,2022,,
Extra contribution to multi-year partners,PAX,500000,2022,,
Extra contribution to multi-year partners,Roger Federer Foundation,500000,2022,,
Extra contribution to multi-year partners,Save the Children Nederland,500000,2022,,
Extra contribution to multi-year partners,Bas van de Goor Foundation,370000,2022,,
Extra contribution to multi-year partners,Krajicek Foundation,250000,2022,,
SUBTOTAAL Extra bijdrage,25 projecten,35865000,2022,,
Dream Fund,Commonland - Het Groene Goud,12000000,2022,,
SUBTOTAAL Dream Fund,1 project,12000000,2022,,
TOTAAL 2022,193 entries,337890099,2022,,
Categorie,Organisatie,Bedrag,Jaar,,
Multi-year partner,Stichting DOEN,18000000,2023,,
Multi-year partner,Oranje Fonds,15000000,2023,,
Multi-year partner,Artsen zonder Grenzen,13500000,2023,,
Multi-year partner,LandschappenNL,13500000,2023,,
Multi-year partner,Oxfam Novib,13500000,2023,,
Multi-year partner,UNICEF,13500000,2023,,
Multi-year partner,Wereld Natuur Fonds,13500000,2023,,
Multi-year partner,Natuurmonumenten,13714211,2023,,
Multi-year partner,Kansfonds,10000000,2023,,
Multi-year partner,Vfonds,10000000,2023,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2023,,
Multi-year partner,Het Nederlandse Rode Kruis,5400000,2023,,
Multi-year partner,Postcode Loterij Buurtfonds,4500000,2023,,
Multi-year partner,Humanitas,4500000,2023,,
Multi-year partner,Cordaid,4050000,2023,,
Multi-year partner,Amnesty International,3600000,2023,,
Multi-year partner,Plan International,3150000,2023,,
Multi-year partner,Stichting Vluchteling,2700000,2023,,
Multi-year partner,Aidsfonds,2250000,2023,,
Multi-year partner,Greenpeace,2250000,2023,,
Multi-year partner,De Natuur en Milieufederaties,2250000,2023,,
Multi-year partner,Terre des Hommes,2250000,2023,,
Multi-year partner,UNHCR,2250000,2023,,
Multi-year partner,Dierenbescherming,1800000,2023,,
Multi-year partner,Natuur & Milieu,1800000,2023,,
Multi-year partner,Vogelbescherming Nederland,1800000,2023,,
Multi-year partner,Clinton Foundation,1350000,2023,,
Multi-year partner,Fonds Slachtofferhulp,1350000,2023,,
Multi-year partner,Hivos,1350000,2023,,
Multi-year partner,Human Rights Watch,1350000,2023,,
Multi-year partner,IVN Natuureducatie,1350000,2023,,
Multi-year partner,Johan Cruyff Foundation,1350000,2023,,
Multi-year partner,Kinderhulp,1350000,2023,,
Multi-year partner,Leprastichting,1350000,2023,,
Multi-year partner,Liliane Fonds,1350000,2023,,
Multi-year partner,Mama Cash,1350000,2023,,
Multi-year partner,Milieudefensie,1350000,2023,,
Multi-year partner,Peace Parks Foundation,1350000,2023,,
Multi-year partner,Solidaridad,1350000,2023,,
Multi-year partner,SOS Kinderdorpen,1350000,2023,,
Multi-year partner,War Child,1350000,2023,,
Multi-year partner,World Food Programme,1350000,2023,,
Multi-year partner,Hersenstichting,1000000,2023,,
Multi-year partner,African Parks Network,900000,2023,,
Multi-year partner,Alzheimer Nederland,900000,2023,,
Multi-year partner,Amref Health Africa,900000,2023,,
Multi-year partner,ARK Rewilding Nederland,900000,2023,,
Multi-year partner,CARE Nederland,900000,2023,,
Multi-year partner,The Climate Group,900000,2023,,
Multi-year partner,Commonland,900000,2023,,
Multi-year partner,Dr. Denis Mukwege Foundation,900000,2023,,
Multi-year partner,Diabetes Fonds,900000,2023,,
Multi-year partner,European Climate Foundation,900000,2023,,
Multi-year partner,Free Press Unlimited,900000,2023,,
Multi-year partner,Goois Natuurreservaat,900000,2023,,
Multi-year partner,HandicapNL,900000,2023,,
Multi-year partner,Hartstichting,900000,2023,,
Multi-year partner,IUCN NL,900000,2023,,
Multi-year partner,Jantje Beton,900000,2023,,
Multi-year partner,KNCV Tuberculosefonds,900000,2023,,
Multi-year partner,KWF Kankerbestrijding,900000,2023,,
Multi-year partner,Longfonds,900000,2023,,
Multi-year partner,MDL Fonds,900000,2023,,
Multi-year partner,MIND,900000,2023,,
Multi-year partner,Nederlandse Brandwonden Stichting,900000,2023,,
Multi-year partner,Nierstichting,900000,2023,,
Multi-year partner,PharmAccess,900000,2023,,
Multi-year partner,Prinses Beatrix Spierfonds,900000,2023,,
Multi-year partner,ReumaNederland,900000,2023,,
Multi-year partner,Rewilding Europe,900000,2023,,
Multi-year partner,Rocky Mountain Institute,900000,2023,,
Multi-year partner,Rutgers,900000,2023,,
Multi-year partner,Save the Children Nederland,900000,2023,,
Multi-year partner,Sea Shepherd,900000,2023,,
Multi-year partner,The Sentry,900000,2023,,
Multi-year partner,Simavi,900000,2023,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,900000,2023,,
Multi-year partner,Theirworld,900000,2023,,
Multi-year partner,Voedselbanken Nederland,900000,2023,,
Multi-year partner,Wilde Ganzen,900000,2023,,
Multi-year partner,AAP,500000,2023,,
Multi-year partner,Aflatoun International,500000,2023,,
Multi-year partner,Both ENDS,500000,2023,,
Multi-year partner,Carbon War Room,500000,2023,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,500000,2023,,
Multi-year partner,Dance4Life,500000,2023,,
Multi-year partner,Defence for Children,500000,2023,,
Multi-year partner,Stichting DierenLot,500000,2023,,
Multi-year partner,Dokters van de Wereld,500000,2023,,
Multi-year partner,Dutch Caribbean Nature Alliance,500000,2023,,
Multi-year partner,Edukans,500000,2023,,
Multi-year partner,The Elders,500000,2023,,
Multi-year partner,Girls Not Brides,500000,2023,,
Multi-year partner,Global Witness,500000,2023,,
Multi-year partner,The Hunger Project,500000,2023,,
Multi-year partner,IMC Weekendschool,500000,2023,,
Multi-year partner,Jeugdeducatiefonds,500000,2023,,
Multi-year partner,Jeugdfonds Sport & Cultuur,500000,2023,,
Multi-year partner,JINC,500000,2023,,
Multi-year partner,Kinderfonds MAMAS,500000,2023,,
Multi-year partner,Stichting Kinderpostzegels Nederland,500000,2023,,
Multi-year partner,Krajicek Foundation,500000,2023,,
Multi-year partner,LINDA.foundation,500000,2023,,
Multi-year partner,Marine Stewardship Council,500000,2023,,
Multi-year partner,Movies that Matter,500000,2023,,
Multi-year partner,Nadia's Initiative,500000,2023,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,500000,2023,,
Multi-year partner,Stichting De Noordzee,500000,2023,,
Multi-year partner,PAX,500000,2023,,
Multi-year partner,Prins Claus Fonds,500000,2023,,
Multi-year partner,Rafa Nadal Foundation,500000,2023,,
Multi-year partner,Resto VanHarte,500000,2023,,
Multi-year partner,Right To Play,500000,2023,,
Multi-year partner,Roger Federer Foundation,500000,2023,,
Multi-year partner,Scouting Nederland,500000,2023,,
Multi-year partner,Urgenda,500000,2023,,
Multi-year partner,Het Vergeten Kind,500000,2023,,
Multi-year partner,De Vrolijkheid,500000,2023,,
Multi-year partner,Waddenvereniging,500000,2023,,
Multi-year partner,Wakker Dier,500000,2023,,
Multi-year partner,Wildlife Justice Commission,500000,2023,,
Multi-year partner,WOMEN Inc.,500000,2023,,
Multi-year partner,World Press Photo,500000,2023,,
Multi-year partner,YY Foundation,500000,2023,,
Multi-year partner,Nationale Vereniging de Zonnebloem,500000,2023,,
Multi-year partner,Bas van de Goor Foundation,300000,2023,,
Multi-year partner,Stichting De Buurt,300000,2023,,
Multi-year partner,EpilepsieNL,300000,2023,,
Multi-year partner,Esther Vergeer Foundation,300000,2023,,
Multi-year partner,Fonds Gehandicaptensport,300000,2023,,
Multi-year partner,Stichting het Gehandicapte Kind,300000,2023,,
Multi-year partner,Hulphond Nederland,300000,2023,,
Multi-year partner,Stichting Jarige Job,300000,2023,,
Multi-year partner,Leergeld Nederland,300000,2023,,
Multi-year partner,Stichting Lezen en Schrijven,300000,2023,,
Multi-year partner,Stichting Life Goals Nederland,300000,2023,,
Multi-year partner,Make-A-Wish Nederland,300000,2023,,
Multi-year partner,Metakids,300000,2023,,
Multi-year partner,Stichting MS Research,300000,2023,,
Multi-year partner,Nederlandse Vereniging voor Autisme,300000,2023,,
Multi-year partner,Oogfonds,300000,2023,,
Multi-year partner,Nationaal Ouderenfonds,300000,2023,,
Multi-year partner,Pink Ribbon,300000,2023,,
Multi-year partner,Spieren voor Spieren,300000,2023,,
Multi-year partner,Vier het Leven,300000,2023,,
Multi-year partner,Giovanni van Bronckhorst Foundation,100000,2023,,
Multi-year partner,Stichting Herman van Veen Arts Center Fonds,100000,2023,,
Multi-year partner,Yvonne van Gennip Talent Fonds,100000,2023,,
SUBTOTAAL Multi-year partner,147 organisaties,271314211,2023,,
One-time donation,Sam voor alle kinderen,5000000,2023,,
One-time donation,Stichting Kansengelijkheid Burgerschapsonderwijs,3000000,2023,,
One-time donation,Leger des Heils,2500000,2023,,
One-time donation,Wetlands International,1500000,2023,,
One-time donation,Land Life Company/Borneo Orangutang Survival Fund,1100000,2023,,
One-time donation,Front Line Defenders,1000000,2023,,
One-time donation,International Budget Partnership,1000000,2023,,
One-time donation,Lighthouse Reports,1000000,2023,,
One-time donation,RNW Media,1000000,2023,,
One-time donation,Vereniging SchuldHulpMaatje Nederland,1000000,2023,,
One-time donation,WeForest,1000000,2023,,
One-time donation,Women Win,920000,2023,,
One-time donation,Girls First Fund,910000,2023,,
One-time donation,Young Africa,807000,2023,,
One-time donation,Stichting Met je hart,800000,2023,,
One-time donation,Crisis Action,750000,2023,,
One-time donation,Land van Ons,750000,2023,,
One-time donation,MIND Us,750000,2023,,
One-time donation,World Animal Protection,750000,2023,,
One-time donation,Forbidden Stories,600000,2023,,
One-time donation,Stichting Hartekind,510000,2023,,
One-time donation,Enviu,500000,2023,,
One-time donation,FairWork,500000,2023,,
One-time donation,Truth Tellers Summit,500000,2023,,
One-time donation,Stichting Artsen voor Kinderen,450000,2023,,
One-time donation,Heifer Nederland,400000,2023,,
One-time donation,KLABU,400000,2023,,
One-time donation,Young Perspectives,400000,2023,,
One-time donation,Trombosestichting Nederland,303000,2023,,
One-time donation,Nice Place Foundation,250000,2023,,
One-time donation,Dirk Kuyt Foundation,200000,2023,,
SUBTOTAAL One-time donation,31 organisaties,31620000,2023,,
Extra contribution to multi-year partners,ARK Rewilding Nederland,2100000,2023,,
Extra contribution to multi-year partners,Greenpeace,2233000,2023,,
Extra contribution to multi-year partners,Postcode Loterij Buurtfonds,2481727,2023,,
Extra contribution to multi-year partners,Rewilding Europe,2200000,2023,,
Extra contribution to multi-year partners,Artsen zonder Grenzen,1908000,2023,,
Extra contribution to multi-year partners,UNHCR,1760000,2023,,
Extra contribution to multi-year partners,IVN Natuureducatie,1990000,2023,,
Extra contribution to multi-year partners,Edukans,1990000,2023,,
Extra contribution to multi-year partners,Jantje Beton,1541000,2023,,
Extra contribution to multi-year partners,Simavi,1450000,2023,,
Extra contribution to multi-year partners,Liliane Fonds,1279000,2023,,
Extra contribution to multi-year partners,Metakids,1200000,2023,,
Extra contribution to multi-year partners,The Sentry,1194000,2023,,
Extra contribution to multi-year partners,War Child,1000000,2023,,
Extra contribution to multi-year partners,Aidsfonds,895000,2023,,
Extra contribution to multi-year partners,CARE Nederland,800000,2023,,
Extra contribution to multi-year partners,Save the Children Nederland,800000,2023,,
Extra contribution to multi-year partners,De Vrolijkheid,630000,2023,,
Extra contribution to multi-year partners,Vfonds,500000,2023,,
Extra contribution to multi-year partners,Het Vergeten Kind,450000,2023,,
Extra contribution to multi-year partners,Stichting Lezen en Schrijven,477000,2023,,
Extra contribution to multi-year partners,HandicapNL,1603000,2023,,
Extra contribution to multi-year partners,Dr. Denis Mukwege Foundation,400000,2023,,
Extra contribution to multi-year partners,Pink Ribbon,287000,2023,,
SUBTOTAAL Extra bijdrage,24 projecten,33697727,2023,,
Dream Fund,Natuurmonumenten - Rotterdam de Boer op!,10000000,2023,,
Dream Fund,Natuur & Milieu en Stichting De Noordzee - De Rijke Noordzee,2600000,2023,,
SUBTOTAAL Dream Fund,2 projecten,12600000,2023,,
TOTAAL 2023,204 entries,349231938,2023,,
Multi-year partner,AAP,600000,2024,,
Multi-year partner,Aflatoun International,600000,2024,,
Multi-year partner,African Parks Network,1000000,2024,,
Multi-year partner,Aidsfonds,2500000,2024,,
Multi-year partner,Stichting ALS Nederland,600000,2024,,
Multi-year partner,Alzheimer Nederland,1000000,2024,,
Multi-year partner,Amnesty International,4000000,2024,,
Multi-year partner,Amref Health Africa,1000000,2024,,
Multi-year partner,ARK Rewilding Nederland,1000000,2024,,
Multi-year partner,Artsen zonder Grenzen,13500000,2024,,
Multi-year partner,Bas van de Goor Foundation,300000,2024,,
Multi-year partner,Bellingcat,600000,2024,,
Multi-year partner,Both ENDS,600000,2024,,
Multi-year partner,Stichting De Buurt,300000,2024,,
Multi-year partner,CARE Nederland,1000000,2024,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,600000,2024,,
Multi-year partner,Clinton Foundation,600000,2024,,
Multi-year partner,Commonland,1000000,2024,,
Multi-year partner,Cordaid,4050000,2024,,
Multi-year partner,Defence for Children,600000,2024,,
Multi-year partner,Dr. Denis Mukwege Foundation,1000000,2024,,
Multi-year partner,Diabetes Fonds,1000000,2024,,
Multi-year partner,Dierenbescherming,2500000,2024,,
Multi-year partner,Stichting DierenLot,600000,2024,,
Multi-year partner,Stichting DOEN,22706299,2024,,
Multi-year partner,Dokters van de Wereld,600000,2024,,
Multi-year partner,Dutch Caribbean Nature Alliance,600000,2024,,
Multi-year partner,Edukans,600000,2024,,
Multi-year partner,The Elders,600000,2024,,
Multi-year partner,EpilepsieNL,300000,2024,,
Multi-year partner,Esther Vergeer Foundation,300000,2024,,
Multi-year partner,European Climate Foundation,1000000,2024,,
Multi-year partner,Fonds Gehandicaptensport,300000,2024,,
Multi-year partner,Fonds Slachtofferhulp,1500000,2024,,
Multi-year partner,Free Press Unlimited,1000000,2024,,
Multi-year partner,Stichting het Gehandicapte Kind,300000,2024,,
Multi-year partner,Giovanni van Bronckhorst Foundation,100000,2024,,
Multi-year partner,Girls Not Brides,600000,2024,,
Multi-year partner,Global Witness,600000,2024,,
Multi-year partner,Goois Natuurreservaat,1000000,2024,,
Multi-year partner,Greenpeace,2500000,2024,,
Multi-year partner,HandicapNL,1000000,2024,,
Multi-year partner,Hartstichting,1000000,2024,,
Multi-year partner,Stichting Herman van Veen Arts Center Fonds,100000,2024,,
Multi-year partner,Hersenstichting,1000000,2024,,
Multi-year partner,Hivos,1500000,2024,,
Multi-year partner,Hulphond Nederland,300000,2024,,
Multi-year partner,Human Rights Watch,1500000,2024,,
Multi-year partner,Humanitas,4500000,2024,,
Multi-year partner,The Hunger Project,600000,2024,,
Multi-year partner,IMC Weekendschool,600000,2024,,
Multi-year partner,IUCN NL,1000000,2024,,
Multi-year partner,IVN Natuureducatie,1500000,2024,,
Multi-year partner,Jantje Beton,1000000,2024,,
Multi-year partner,Stichting Jarige Job,300000,2024,,
Multi-year partner,Jeugdeducatiefonds,600000,2024,,
Multi-year partner,Jeugdfonds Sport & Cultuur,600000,2024,,
Multi-year partner,JINC,600000,2024,,
Multi-year partner,Johan Cruyff Foundation,1500000,2024,,
Multi-year partner,Kansfonds,10000000,2024,,
Multi-year partner,Kinderfonds MAMAS,600000,2024,,
Multi-year partner,Kinderhulp,1500000,2024,,
Multi-year partner,Stichting Kinderpostzegels Nederland,600000,2024,,
Multi-year partner,KNCV Tuberculosefonds,1000000,2024,,
Multi-year partner,Krajicek Foundation,500000,2024,,
Multi-year partner,KWF Kankerbestrijding,1000000,2024,,
Multi-year partner,LandschappenNL,15000000,2024,,
Multi-year partner,Leergeld Nederland,300000,2024,,
Multi-year partner,Leprastichting,1500000,2024,,
Multi-year partner,Stichting Lezen en Schrijven,300000,2024,,
Multi-year partner,Stichting Life Goals Nederland,300000,2024,,
Multi-year partner,Liliane Fonds,1500000,2024,,
Multi-year partner,LINDA.foundation,600000,2024,,
Multi-year partner,Longfonds,1000000,2024,,
Multi-year partner,Make-A-Wish Nederland,300000,2024,,
Multi-year partner,Mama Cash,1500000,2024,,
Multi-year partner,MDL Fonds,1000000,2024,,
Multi-year partner,Metakids,300000,2024,,
Multi-year partner,Milieudefensie,1500000,2024,,
Multi-year partner,MIND,1000000,2024,,
Multi-year partner,Movies that Matter,500000,2024,,
Multi-year partner,Stichting MS Research,300000,2024,,
Multi-year partner,Nadia's Initiative,500000,2024,,
Multi-year partner,Natuur & Milieu,1800000,2024,,
Multi-year partner,De Natuur en Milieufederaties,2500000,2024,,
Multi-year partner,Natuurmonumenten,13500000,2024,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,600000,2024,,
Multi-year partner,Nederlandse Brandwonden Stichting,1000000,2024,,
Multi-year partner,Nederlandse Vereniging voor Autisme,300000,2024,,
Multi-year partner,Nierstichting,1000000,2024,,
Multi-year partner,Stichting De Noordzee,500000,2024,,
Multi-year partner,Obama Foundation,600000,2024,,
Multi-year partner,Oogfonds,300000,2024,,
Multi-year partner,Oranje Fonds,15000000,2024,,
Multi-year partner,Nationaal Ouderenfonds,300000,2024,,
Multi-year partner,Oxfam Novib,13500000,2024,,
Multi-year partner,ParkinsonNL,300000,2024,,
Multi-year partner,PAX,600000,2024,,
Multi-year partner,Peace Parks Foundation,1500000,2024,,
Multi-year partner,PharmAccess,1000000,2024,,
Multi-year partner,Pink Ribbon,300000,2024,,
Multi-year partner,Plan International,4000000,2024,,
Multi-year partner,Prins Claus Fonds,600000,2024,,
Multi-year partner,Prinses Beatrix Spierfonds,1000000,2024,,
Multi-year partner,Rafa Nadal Foundation,600000,2024,,
Multi-year partner,Resto VanHarte,600000,2024,,
Multi-year partner,ReumaNederland,1000000,2024,,
Multi-year partner,Rewilding Europe,1000000,2024,,
Multi-year partner,Right To Play,500000,2024,,
Multi-year partner,Rocky Mountain Institute,1500000,2024,,
Multi-year partner,Het Nederlandse Rode Kruis,6000000,2024,,
Multi-year partner,Roger Federer Foundation,600000,2024,,
Multi-year partner,Rutgers,1500000,2024,,
Multi-year partner,Save the Children Nederland,1000000,2024,,
Multi-year partner,Scouting Nederland,600000,2024,,
Multi-year partner,Sea Shepherd,1000000,2024,,
Multi-year partner,The Sentry,900000,2024,,
Multi-year partner,Simavi,1000000,2024,,
Multi-year partner,Solidaridad,1500000,2024,,
Multi-year partner,SOS Kinderdorpen,1500000,2024,,
Multi-year partner,Spieren voor Spieren,300000,2024,,
Multi-year partner,Terre des Hommes,2500000,2024,,
Multi-year partner,Theirworld,1000000,2024,,
Multi-year partner,UNHCR,2500000,2024,,
Multi-year partner,UNICEF,13500000,2024,,
Multi-year partner,Urgenda,600000,2024,,
Multi-year partner,Het Vergeten Kind,600000,2024,,
Multi-year partner,Vfonds,10000000,2024,,
Multi-year partner,Vier het Leven,300000,2024,,
Multi-year partner,Stichting Vluchteling,4000000,2024,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,1000000,2024,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2024,,
Multi-year partner,Voedselbanken Nederland,1000000,2024,,
Multi-year partner,Vogelbescherming Nederland,2500000,2024,,
Multi-year partner,De Vrolijkheid,600000,2024,,
Multi-year partner,Waddenvereniging,600000,2024,,
Multi-year partner,Wakker Dier,600000,2024,,
Multi-year partner,War Child,1500000,2024,,
Multi-year partner,Wereld Natuur Fonds,13500000,2024,,
Multi-year partner,Wilde Ganzen,1000000,2024,,
Multi-year partner,Wildlife Justice Commission,600000,2024,,
Multi-year partner,WOMEN Inc.,600000,2024,,
Multi-year partner,World Food Programme,1500000,2024,,
Multi-year partner,World Press Photo,600000,2024,,
Multi-year partner,Yvonne van Gennip Talent Fonds,100000,2024,,
Multi-year partner,YY Foundation,600000,2024,,
Multi-year partner,Nationale Vereniging de Zonnebloem,600000,2024,,
SUBTOTAAL,Multi-year partner 147 organisaties,290156299,2024,,
One-time donation,Ashoka,1500000,2024,,
One-time donation,ASKV Steunpunt Vluchtelingen,500000,2024,,
One-time donation,Buzz Women,600000,2024,,
One-time donation,Clooney Foundation for Justice,500000,2024,,
One-time donation,Forward Inc,600000,2024,,
One-time donation,Justice & Peace,1000000,2024,,
One-time donation,Koninklijke Nederlandse Reddingsmaatschappij,1000000,2024,,
One-time donation,Landelijk Samenwerkingsverband Actieve bewoners (LSA),500000,2024,,
One-time donation,Mondiaal FNV,960000,2024,,
One-time donation,National Geographic Society,1610000,2024,,
One-time donation,Progreso,530000,2024,,
One-time donation,Stichting 3X3 Unites,500000,2024,,
One-time donation,Stichting Anne-Bo,400000,2024,,
One-time donation,Stichting Cliniclowns Nederland,1000000,2024,,
One-time donation,Stichting Leeuw,600000,2024,,
One-time donation,Stichting Sheltersuit,450000,2024,,
One-time donation,Stichting Voedselbosbouw Nederland,450000,2024,,
One-time donation,Wij.Land,500000,2024,,
One-time donation,Women Engage for a Common Future,500000,2024,,
SUBTOTAAL,One-time donation 19 organisaties,13700000,2024,,
Extra contribution to multi-year partners,De Natuur en Milieufederaties,2360000,2024,,
Extra contribution to multi-year partners,Dierenbescherming,2500000,2024,,
Extra contribution to multi-year partners,Dutch Caribbean Nature Alliance,1725000,2024,,
Extra contribution to multi-year partners,EpilepsieNL,770000,2024,,
Extra contribution to multi-year partners,Fonds Slachtofferhulp,675000,2024,,
Extra contribution to multi-year partners,Hulphond Nederland,935000,2024,,
Extra contribution to multi-year partners,IMC Weekendschool,500000,2024,,
Extra contribution to multi-year partners,IUCN NL,4690000,2024,,
Extra contribution to multi-year partners,Kinderfonds MAMAS,1250000,2024,,
Extra contribution to multi-year partners,LandschappenNL,1775000,2024,,
Extra contribution to multi-year partners,Leprastichting,1250000,2024,,
Extra contribution to multi-year partners,Mama Cash,1500000,2024,,
Extra contribution to multi-year partners,Natuur & Milieu,1960000,2024,,
Extra contribution to multi-year partners,Prins Claus Fonds,1500000,2024,,
Extra contribution to multi-year partners,Prinses Beatrix Spierfonds,1665000,2024,,
Extra contribution to multi-year partners,ReumaNederland,1537000,2024,,
Extra contribution to multi-year partners,Rutgers,750000,2024,,
Extra contribution to multi-year partners,Solidaridad,2167000,2024,,
Extra contribution to multi-year partners,The Hunger Project,1600000,2024,,
Extra contribution to multi-year partners,Vereniging Nederlands Cultuurlandschap,1150000,2024,,
Extra contribution to multi-year partners,Vfonds,985000,2024,,
Extra contribution to multi-year partners,War Child,1895000,2024,,
SUBTOTAAL,Extra bijdrage 22 projecten,35139000,2024,,
Dream Fund,Longfonds & MIND - Project Bruis,13000000,2024,,
Dream Fund,Nierstichting - Samen voor de nieuwe generatie nieren,10000000,2024,,
SUBTOTAAL,Dream Fund 2 projecten,23000000,2024,,
TOTAAL 2024,190 entries (berekend),361995299,2024,,
Multi-year partner,AAP,600000,2025,,
Multi-year partner,Aflatoun International,600000,2025,,
Multi-year partner,African Parks Network,1000000,2025,,
Multi-year partner,Aidsfonds,2500000,2025,,
Multi-year partner,Stichting ALS Nederland,600000,2025,,
Multi-year partner,Alzheimer Nederland,1000000,2025,,
Multi-year partner,Amnesty International,4000000,2025,,
Multi-year partner,Amref Health Africa,1000000,2025,,
Multi-year partner,ARK Rewilding Nederland,1000000,2025,,
Multi-year partner,Artsen zonder Grenzen,13500000,2025,,
Multi-year partner,Bas van de Goor Foundation,300000,2025,,
Multi-year partner,Bellingcat,600000,2025,,
Multi-year partner,Both ENDS,600000,2025,,
Multi-year partner,De Buurt,300000,2025,,
Multi-year partner,CARE Nederland,1000000,2025,,
Multi-year partner,Centrum tegen Kinderhandel en Mensenhandel,600000,2025,,
Multi-year partner,Clinton Foundation,600000,2025,,
Multi-year partner,Commonland,1000000,2025,,
Multi-year partner,Cordaid,4050000,2025,,
Multi-year partner,Defence for Children,600000,2025,,
Multi-year partner,Dr. Denis Mukwege Foundation,1000000,2025,,
Multi-year partner,Diabetes Fonds,1000000,2025,,
Multi-year partner,Dierenbescherming,2500000,2025,,
Multi-year partner,Stichting Dierenlot,600000,2025,,
Multi-year partner,Stichting DOEN,18003520,2025,,
Multi-year partner,Dokters van de Wereld,600000,2025,,
Multi-year partner,Dutch Caribbean Nature Alliance,600000,2025,,
Multi-year partner,Edukans,600000,2025,,
Multi-year partner,The Elders,600000,2025,,
Multi-year partner,EpilepsieNL,300000,2025,,
Multi-year partner,Esther Vergeer Foundation,300000,2025,,
Multi-year partner,European Climate Foundation,1000000,2025,,
Multi-year partner,Fonds Gehandicaptensport,300000,2025,,
Multi-year partner,Nationaal Fonds Kinderhulp,1500000,2025,,
Multi-year partner,Fonds Slachtofferhulp,1500000,2025,,
Multi-year partner,Free Press Unlimited,1000000,2025,,
Multi-year partner,Stichting het Gehandicapte Kind,300000,2025,,
Multi-year partner,Giovanni van Bronckhorst Foundation,100000,2025,,
Multi-year partner,Girls Not Brides,600000,2025,,
Multi-year partner,Global Witness,600000,2025,,
Multi-year partner,Greenpeace,4000000,2025,,
Multi-year partner,HandicapNL,1000000,2025,,
Multi-year partner,Hartstichting,2500000,2025,,
Multi-year partner,Stichting Herman van Veen Arts Center Fonds,100000,2025,,
Multi-year partner,Hersenstichting,1000000,2025,,
Multi-year partner,Hivos,1500000,2025,,
Multi-year partner,Hulphond Nederland,300000,2025,,
Multi-year partner,Human Rights Watch,1500000,2025,,
Multi-year partner,Humanitas,4500000,2025,,
Multi-year partner,The Hunger Project,600000,2025,,
Multi-year partner,IMC Weekendschool,600000,2025,,
Multi-year partner,IUCN NL,1000000,2025,,
Multi-year partner,IVN Natuureducatie,1500000,2025,,
Multi-year partner,Jantje Beton,1000000,2025,,
Multi-year partner,Stichting Jarige Job,300000,2025,,
Multi-year partner,Jeugdeducatiefonds,600000,2025,,
Multi-year partner,Jeugdfonds Sport & Cultuur,600000,2025,,
Multi-year partner,JINC,600000,2025,,
Multi-year partner,Johan Cruyff Foundation,1500000,2025,,
Multi-year partner,Join Us,300000,2025,,
Multi-year partner,Kansfonds,10000000,2025,,
Multi-year partner,Kinderfonds MAMAS,600000,2025,,
Multi-year partner,Kinderpostzegels,600000,2025,,
Multi-year partner,KNCV Tuberculosefonds,1000000,2025,,
Multi-year partner,Krajicek Foundation,500000,2025,,
Multi-year partner,KWF Kankerbestrijding,4000000,2025,,
Multi-year partner,LandschappenNL,15000000,2025,,
Multi-year partner,Leergeld Nederland,300000,2025,,
Multi-year partner,Leprastichting,1500000,2025,,
Multi-year partner,Stichting Lezen en Schrijven,300000,2025,,
Multi-year partner,Stichting Life Goals Nederland,300000,2025,,
Multi-year partner,Liliane Fonds,1500000,2025,,
Multi-year partner,LINDA.foundation,600000,2025,,
Multi-year partner,Longfonds,1000000,2025,,
Multi-year partner,Make-A-Wish Nederland,300000,2025,,
Multi-year partner,Mama Cash,1500000,2025,,
Multi-year partner,MDL Fonds,1000000,2025,,
Multi-year partner,Metakids,300000,2025,,
Multi-year partner,Milieudefensie,1500000,2025,,
Multi-year partner,MIND,1000000,2025,,
Multi-year partner,Movies that Matter,500000,2025,,
Multi-year partner,Stichting MS Research,300000,2025,,
Multi-year partner,Nadia's Initiative,500000,2025,,
Multi-year partner,Natuur & Milieu,1800000,2025,,
Multi-year partner,De Natuur en Milieufederaties,2500000,2025,,
Multi-year partner,Natuurmonumenten,13500000,2025,,
Multi-year partner,Vereniging Nederlands Cultuurlandschap,600000,2025,,
Multi-year partner,Nederlandse Brandwonden Stichting,1000000,2025,,
Multi-year partner,Nederlandse Vereniging voor Autisme,300000,2025,,
Multi-year partner,Nice Place Foundation,300000,2025,,
Multi-year partner,Nierstichting,1000000,2025,,
Multi-year partner,Stichting De Noordzee,500000,2025,,
Multi-year partner,Obama Foundation,600000,2025,,
Multi-year partner,Oogfonds,300000,2025,,
Multi-year partner,Oranje Fonds,15000000,2025,,
Multi-year partner,Nationaal Ouderenfonds,300000,2025,,
Multi-year partner,Oxfam Novib,13500000,2025,,
Multi-year partner,ParkinsonNederland,300000,2025,,
Multi-year partner,PAX,600000,2025,,
Multi-year partner,Peace Parks Foundation,1500000,2025,,
Multi-year partner,PharmAccess,1000000,2025,,
Multi-year partner,Pink Ribbon,300000,2025,,
Multi-year partner,Plan International Nederland,4000000,2025,,
Multi-year partner,Postcode Loterij Buurtfonds,6300000,2025,,
Multi-year partner,Prins Claus Fonds,600000,2025,,
Multi-year partner,Prinses Beatrix Spierfonds,1000000,2025,,
Multi-year partner,Rafa Nadal Foundation,600000,2025,,
Multi-year partner,Resto VanHarte,600000,2025,,
Multi-year partner,ReumaNederland,1000000,2025,,
Multi-year partner,Rewilding Europe,1000000,2025,,
Multi-year partner,Right To Play,500000,2025,,
Multi-year partner,Rocky Mountain Institute,1500000,2025,,
Multi-year partner,Rode Kruis,6000000,2025,,
Multi-year partner,Roger Federer Foundation,600000,2025,,
Multi-year partner,Rutgers,1500000,2025,,
Multi-year partner,Save the Children Nederland,1500000,2025,,
Multi-year partner,Scouting Nederland,600000,2025,,
Multi-year partner,Sea Shepherd,1000000,2025,,
Multi-year partner,The Sentry,900000,2025,,
Multi-year partner,Solidaridad,1500000,2025,,
Multi-year partner,SOS Kinderdorpen,1500000,2025,,
Multi-year partner,Spieren voor Spieren,300000,2025,,
Multi-year partner,Terre des Hommes,2500000,2025,,
Multi-year partner,Theirworld,1000000,2025,,
Multi-year partner,Trees for All,600000,2025,,
Multi-year partner,UNHCR,2500000,2025,,
Multi-year partner,UNICEF,13500000,2025,,
Multi-year partner,Urgenda,600000,2025,,
Multi-year partner,Het Vergeten Kind,600000,2025,,
Multi-year partner,Vfonds,10000000,2025,,
Multi-year partner,Vier het Leven,300000,2025,,
Multi-year partner,Stichting Vluchteling,4000000,2025,,
Multi-year partner,Stichting voor Vluchteling-Studenten UAF,1000000,2025,,
Multi-year partner,VluchtelingenWerk Nederland,10000000,2025,,
Multi-year partner,Voedselbanken Nederland,1000000,2025,,
Multi-year partner,Vogelbescherming Nederland,2500000,2025,,
Multi-year partner,De Vrolijkheid,600000,2025,,
Multi-year partner,Waddenvereniging,600000,2025,,
Multi-year partner,Wakker Dier,600000,2025,,
Multi-year partner,War Child,1500000,2025,,
Multi-year partner,WaterAid,1000000,2025,,
Multi-year partner,Wereld Natuur Fonds,13500000,2025,,
Multi-year partner,Wilde Ganzen,1000000,2025,,
Multi-year partner,Wildlife Justice Commission,600000,2025,,
Multi-year partner,WOMEN Inc.,600000,2025,,
Multi-year partner,World Food Programme,1500000,2025,,
Multi-year partner,World Press Photo,600000,2025,,
Multi-year partner,Yvonne van Gennip Talent Fonds,100000,2025,,
Multi-year partner,YY Foundation,600000,2025,,
Multi-year partner,Nationale Vereniging de Zonnebloem,1000000,2025,,
SUBTOTAAL,Multi-year partner 150 organisaties,298853520,2025,,
One-time donation,Stichting Ambulance Wens,450000,2025,,
One-time donation,Stichting Armoedefonds,1000000,2025,,
One-time donation,COC Nederland,600000,2025,,
One-time donation,Cultural Emergency Response,750000,2025,,
One-time donation,DollyWood Foundation,350000,2025,,
One-time donation,Emma at Work,600000,2025,,
One-time donation,European AI & Society Fund,1000000,2025,,
One-time donation,Front Line Defenders,1000000,2025,,
One-time donation,Impact Hub Association,500000,2025,,
One-time donation,International Fund for Animal Welfare,1000000,2025,,
One-time donation,Stichting De Kindertelefoon,1500000,2025,,
One-time donation,KLABU,600000,2025,,
One-time donation,Stichting Long COVID,1000000,2025,,
One-time donation,Mensen met een Missie,1200000,2025,,
One-time donation,NewBees,420000,2025,,
One-time donation,Organized Crime and Corruption Reporting Project,600000,2025,,
One-time donation,Paris Peace Forum,300000,2025,,
One-time donation,Prinses Máxima Centrum Foundation,1500000,2025,,
One-time donation,Quiet Nederland,500000,2025,,
One-time donation,Rainforest Foundation,775000,2025,,
One-time donation,Re:wild,1000000,2025,,
One-time donation,Refugee Company,750000,2025,,
One-time donation,Rewilding Argentina,1000000,2025,,
One-time donation,Sovon Vogelonderzoek Nederland,600000,2025,,
SUBTOTAAL,One-time donation 24 organisaties,18995000,2025,,
Extra contribution to multi-year partners,ARK Rewilding Nederland,2800000,2025,,
Extra contribution to multi-year partners,CARE Nederland,1200000,2025,,
Extra contribution to multi-year partners,Cordaid,1700000,2025,,
Extra contribution to multi-year partners,Dokters van de Wereld,750000,2025,,
Extra contribution to multi-year partners,Esther Vergeer Foundation,600000,2025,,
Extra contribution to multi-year partners,Fonds Gehandicaptensport,500000,2025,,
Extra contribution to multi-year partners,Global Witness,1200000,2025,,
Extra contribution to multi-year partners,Hartstichting en Diabetes Fonds,4000000,2025,,
Extra contribution to multi-year partners,Hivos,1000000,2025,,
Extra contribution to multi-year partners,Human Right Watch,1700000,2025,,
Extra contribution to multi-year partners,IUCN NL,2000000,2025,,
Extra contribution to multi-year partners,Jeugdeducatiefonds,1000000,2025,,
Extra contribution to multi-year partners,Johan Cruyff Foundation en Kraijeck Foundation,400000,2025,,
Extra contribution to multi-year partners,Kansfonds en Humanitas,1100000,2025,,
Extra contribution to multi-year partners,Kinderpostzegels,2850000,2025,,
Extra contribution to multi-year partners,KNCV Tuberculosefonds,2200000,2025,,
Extra contribution to multi-year partners,Liliane Fonds,1700000,2025,,
Extra contribution to multi-year partners,Nationaal Ouderenfonds,1000000,2025,,
Extra contribution to multi-year partners,Nederlandse Vereniging voor Autisme,500000,2025,,
Extra contribution to multi-year partners,Stichting De Noordzee,500000,2025,,
Extra contribution to multi-year partners,Oogfonds,1500000,2025,,
Extra contribution to multi-year partners,Oxfam Novib,2500000,2025,,
Extra contribution to multi-year partners,Oranje Fonds,1000000,2025,,
Extra contribution to multi-year partners,Peace Parks Foundation,1000000,2025,,
Extra contribution to multi-year partners,PharmAccess,650000,2025,,
Extra contribution to multi-year partners,Plan International,2500000,2025,,
Extra contribution to multi-year partners,WaterAid Nederland,1900000,2025,,
Extra contribution to multi-year partners,Yvonne van Gennip Talent Fonds,500000,2025,,
Extra contribution to multi-year partners,Het Vergeten Kind,620000,2025,,
Extra contribution to multi-year partners,VluchtelingenWerk Nederland,3850000,2025,,
Extra contribution to multi-year partners,Wilde Ganzen,1500000,2025,,
Extra contribution to multi-year partners,Wildlife Justice Commission,1300000,2025,,
SUBTOTAAL,Extra bijdrage 32 projecten,47520000,2025,,
Dream Fund,HandicapNL - MBO op maat,3500000,2025,,
Dream Fund,World Food Programme - Fortifying the Future,8250000,2025,,
SUBTOTAAL,Dream Fund 2 projecten,11750000,2025,,
TOTAAL 2025 ,208 entries ,377118520,2025,,
`;
const CLASSIFICATION_CSV = `organisation_name,is_dutch,country,theme,
100WEEKS,TRUE,NL,International Aid & Human Rights,
APOPO,FALSE,Belgium/International,International Aid & Human Rights,
ASKV Steunpunt Vluchtelingen,TRUE,NL,International Aid & Human Rights,
ActionAid Nederland,TRUE,NL,International Aid & Human Rights,
Aflatoun International,TRUE,NL,International Aid & Human Rights,
Hivos & Amazon Frontlines,TRUE,NL,International Aid & Human Rights,
Amnesty International,TRUE,NL,International Aid & Human Rights,
BRAC International,TRUE,NL,International Aid & Human Rights,
Bellingcat,TRUE,NL,International Aid & Human Rights,
BiD Network,TRUE,NL,International Aid & Human Rights,
Both ENDS,TRUE,NL,International Aid & Human Rights,
CARE Nederland,TRUE,NL,International Aid & Human Rights,
CNV Internationaal,TRUE,NL,International Aid & Human Rights,
Centrum tegen Kinderhandel en Mensenhandel,TRUE,NL,International Aid & Human Rights,
Clinton Foundation,FALSE,USA,International Aid & Human Rights,
Clooney Foundation for Justice,FALSE,USA,International Aid & Human Rights,
Cordaid,TRUE,NL,International Aid & Human Rights,
Crisis Action,FALSE,UK,International Aid & Human Rights,
Dance4Life,TRUE,NL,International Aid & Human Rights,
Defence for Children,TRUE,NL,International Aid & Human Rights,
Dokters van de Wereld,TRUE,NL,International Aid & Human Rights,
Dr. Denis Mukwege Foundation,TRUE,NL,International Aid & Human Rights,
Edukans,TRUE,NL,International Aid & Human Rights,
FairWork,TRUE,NL,International Aid & Human Rights,
Fairfood,TRUE,NL,International Aid & Human Rights,
Forbidden Stories,FALSE,France,International Aid & Human Rights,
Forward Inc,TRUE,NL,International Aid & Human Rights,
Free Press Unlimited,TRUE,NL,International Aid & Human Rights,
Free a Girl,TRUE,NL,International Aid & Human Rights,
Freedom House,FALSE,USA,International Aid & Human Rights,
Front Line Defenders,FALSE,Ireland,International Aid & Human Rights,
Girls First Fund,FALSE,USA,International Aid & Human Rights,
Girls Not Brides,FALSE,UK,International Aid & Human Rights,
Global Witness,FALSE,UK,International Aid & Human Rights,
Habitat for Humanity Nederland,TRUE,NL,International Aid & Human Rights,
Heifer Nederland,TRUE,NL,International Aid & Human Rights,
Het Nederlandse Rode Kruis,TRUE,NL,International Aid & Human Rights,
Human Rights Watch,FALSE,USA,International Aid & Human Rights,
ICCO,TRUE,NL,International Aid & Human Rights,
ICCO en Solidaridad,TRUE,NL,International Aid & Human Rights,
Impunity Watch,TRUE,NL,International Aid & Human Rights,
Institute for War & Peace Reporting (IWPR),FALSE,UK,International Aid & Human Rights,
Instituut Clingendael,TRUE,NL,International Aid & Human Rights,
International Budget Partnership,FALSE,USA,International Aid & Human Rights,
International Consortium of Investigative Journalists (ICIJ),FALSE,USA,International Aid & Human Rights,
Internews,FALSE,USA,International Aid & Human Rights,
Justdiggit,TRUE,NL,International Aid & Human Rights,
Justice & Peace,TRUE,NL,International Aid & Human Rights,
Justice and Peace - Shelter City Initiative,TRUE,NL,International Aid & Human Rights,
KLABU,TRUE,NL,International Aid & Human Rights,
KidsRights,TRUE,NL,International Aid & Human Rights,
Kinderfonds MAMAS,TRUE,NL,International Aid & Human Rights,
Lighthouse Reports,TRUE,NL,International Aid & Human Rights,
Liliane Fonds,TRUE,NL,International Aid & Human Rights,
Mama Cash,TRUE,NL,International Aid & Human Rights,
Media Development Investment Fund (MDIF),FALSE,USA,International Aid & Human Rights,
Missing Chapter Foundation,TRUE,NL,International Aid & Human Rights,
Mondiaal FNV,TRUE,NL,International Aid & Human Rights,
Movement on the Ground,TRUE,NL,International Aid & Human Rights,
Nadia's Initiative,FALSE,International,International Aid & Human Rights,
Nederlandse Helsinki Comité,TRUE,NL,International Aid & Human Rights,
Not On Our Watch,FALSE,USA,International Aid & Human Rights,
Obama Foundation,FALSE,USA,International Aid & Human Rights,
One Acre Fund,FALSE,USA,International Aid & Human Rights,
Organized Crime and Corruption Reporting Project (OCCRP),FALSE,USA,International Aid & Human Rights,
Oxfam Novib,TRUE,NL,International Aid & Human Rights,
PAX,TRUE,NL,International Aid & Human Rights,
Plan International,TRUE,NL,International Aid & Human Rights,
Progreso,TRUE,NL,International Aid & Human Rights,
RNW Media,TRUE,NL,International Aid & Human Rights,
Rare,FALSE,USA,International Aid & Human Rights,
Red Umbrella Fund,TRUE,NL,International Aid & Human Rights,
Rutgers,TRUE,NL,International Aid & Human Rights,
SOS Kinderdorpen,TRUE,NL,International Aid & Human Rights,
SPARK,TRUE,NL,International Aid & Human Rights,
Save the Children Nederland,TRUE,NL,International Aid & Human Rights,
Schone Kleren Campagne,TRUE,NL,International Aid & Human Rights,
Simavi,TRUE,NL,International Aid & Human Rights,
Solidaridad,TRUE,NL,International Aid & Human Rights,
Stichting Artsen voor Kinderen,TRUE,NL,International Aid & Human Rights,
Stichting Kinderpostzegels Nederland,TRUE,NL,International Aid & Human Rights,
Stichting Onderzoek Multinationale Ondernemingen,TRUE,NL,International Aid & Human Rights,
Stichting Refugee Company,TRUE,NL,International Aid & Human Rights,
Stichting Vluchteling,TRUE,NL,International Aid & Human Rights,
Stichting voor Vluchteling-Studenten UAF,TRUE,NL,International Aid & Human Rights,
Terre des Hommes,TRUE,NL,International Aid & Human Rights,
The Elders,FALSE,UK,International Aid & Human Rights,
The Fund for Global Human Rights,FALSE,USA,International Aid & Human Rights,
The Hague Institute for Innovation of Law (HiiL),TRUE,NL,International Aid & Human Rights,
The Hunger Project,TRUE,NL,International Aid & Human Rights,
The Sentry,FALSE,USA,International Aid & Human Rights,
Theirworld,FALSE,UK,International Aid & Human Rights,
"Theirworld, UNHCR & UNICEF",FALSE,International,International,International Aid & Human Rights
Thorn,FALSE,USA,International Aid & Human Rights,
Triggerise,TRUE,NL,International Aid & Human Rights,
Truth Tellers Summit,FALSE,UK,International Aid & Human Rights,
UNHCR,TRUE,NL,International Aid & Human Rights,
UNICEF,TRUE,NL,International Aid & Human Rights,
Vfonds,TRUE,NL,International Aid & Human Rights,
VluchtelingenWerk Nederland,TRUE,NL,International Aid & Human Rights,
War Child,TRUE,NL,International Aid & Human Rights,
Wemos,TRUE,NL,International Aid & Human Rights,
Wilde Ganzen,TRUE,NL,International Aid & Human Rights,
Women Engage for a Common Future,TRUE,NL,International Aid & Human Rights,
Women Win,TRUE,NL,International Aid & Human Rights,
World Food Programme,FALSE,International (UN),International Aid & Human Rights,
YY Foundation,FALSE,International,International Aid & Human Rights,
Young Africa,TRUE,NL,International Aid & Human Rights,
350.org / Fossielvrij NL,TRUE,NL,Nature & Environment,
ARK Rewilding Nederland,TRUE,NL,Nature & Environment,
African Parks Network,FALSE,South Africa,Nature & Environment,
Break Free from Plastic (BFFP),FALSE,International,Nature & Environment,
Carbon War Room,FALSE,USA,Nature & Environment,
Circle Economy,TRUE,NL,Nature & Environment,
Commonland,TRUE,NL,Nature & Environment,
Commonland - Het Groene Goud,TRUE,NL,Nature & Environment,
De Natuur en Milieufederaties,TRUE,NL,Nature & Environment,
Deltaplan Biodiversiteitsherstel,TRUE,NL,Nature & Environment,
Dutch Caribbean Nature Alliance,TRUE,NL,Nature & Environment,
Enviu,TRUE,NL,Nature & Environment,
European Climate Foundation,TRUE,NL,Nature & Environment,
Fauna & Flora International,FALSE,UK,Nature & Environment,
Forest Stewardship Council (FSC),FALSE,Germany,Nature & Environment,
Global Fishing Watch,FALSE,USA,Nature & Environment,
Goois Natuurreservaat,TRUE,NL,Nature & Environment,
Greenpeace,TRUE,NL,Nature & Environment,
HIER klimaatbureau,TRUE,NL,Nature & Environment,
Hivos & Greenpeace - Alle ogen op de Amazone,TRUE,NL,Nature & Environment,
IUCN NL,TRUE,NL,Nature & Environment,
IVN Natuureducatie,TRUE,NL,Nature & Environment,
Land Life Company/Borneo Orangutang Survival Fund,TRUE,NL,Nature & Environment,
Land van Ons,TRUE,NL,Nature & Environment,
LandschappenNL,TRUE,NL,Nature & Environment,
Leonardo DiCaprio Foundation,FALSE,USA,Nature & Environment,
Marine Stewardship Council,FALSE,UK,Nature & Environment,
Milieudefensie,TRUE,NL,Nature & Environment,
National Geographic Society,FALSE,USA,Nature & Environment,
Natuur & Milieu,TRUE,NL,Nature & Environment,
Natuur & Milieu en Stichting De Noordzee - De Rijke Noordzee,TRUE,NL,Nature & Environment,
Natuurmonumenten,TRUE,NL,Nature & Environment,
Natuurmonumenten - Rotterdam de Boer op!,TRUE,NL,Nature & Environment,
Oceana,FALSE,USA,Nature & Environment,
Peace Parks Foundation,FALSE,South Africa,Nature & Environment,
Plastic Soup Foundation,TRUE,NL,Nature & Environment,
Postcode Lottery Green Challenge,TRUE,NL,Nature & Environment,
RAVON en Good Fish Foundation,TRUE,NL,Nature & Environment,
Rewilding Europe,TRUE,NL,Nature & Environment,
Rocky Mountain Institute,FALSE,USA,Nature & Environment,
Sea Ranger Service,TRUE,NL,Nature & Environment,
Sea Shepherd,TRUE,NL,Nature & Environment,
Solidaridad - Van Klimaatslachtoffers naar Klimaathelden,TRUE,NL,Nature & Environment,
SoortenNL,TRUE,NL,Nature & Environment,
Stichting De Noordzee,TRUE,NL,Nature & Environment,
Stichting Voedselbosbouw Nederland,TRUE,NL,Nature & Environment,
The Climate Group,FALSE,UK,Nature & Environment,
Trees for All,TRUE,NL,Nature & Environment,
Tropenbos International,TRUE,NL,Nature & Environment,
Urgenda,TRUE,NL,Nature & Environment,
Vereniging Nederlands Cultuurlandschap,TRUE,NL,Nature & Environment,
Vogelbescherming Nederland,TRUE,NL,Nature & Environment,
Waddenvereniging,TRUE,NL,Nature & Environment,
"Waddenvereniging,  Stichting De Noordzee & De Natuur en Milieufederaties",TRUE,NL,Nature & Environment,
WeForest,FALSE,Belgium,Nature & Environment,
Wereld Natuur Fonds,TRUE,NL,Nature & Environment,
Wereld Natuur Fonds en Het Rode Kruis,TRUE,NL,Nature & Environment,
"Wereld Natuur Fonds,  African Parks Network en Peace Parks Foundation",TRUE,NL,Nature & Environment,
Wetlands International,TRUE,NL,Nature & Environment,
Wij.Land,TRUE,NL,Nature & Environment,
Wildlife Justice Commission,TRUE,NL,Nature & Environment,
World Fish Migration Foundation,TRUE,NL,Nature & Environment,
Bijzondere uitkeringen,TRUE,NL,Social Welfare (Netherlands),
Bureau Burgerberaad,TRUE,NL,Social Welfare (Netherlands),
Buzz Women,TRUE,NL,Social Welfare (Netherlands),
De Buzinezzclub,TRUE,NL,Social Welfare (Netherlands),
De Vrolijkheid,TRUE,NL,Social Welfare (Netherlands),
Dona Daria,TRUE,NL,Social Welfare (Netherlands),
Everyday Heroes,TRUE,NL,Social Welfare (Netherlands),
Fonds Slachtofferhulp,TRUE,NL,Social Welfare (Netherlands),
Fonds Slachtofferhulp en Centrum Seksueel Geweld,TRUE,NL,Social Welfare (Netherlands),
Het Vergeten Kind,TRUE,NL,Social Welfare (Netherlands),
Humanitas,TRUE,NL,Social Welfare (Netherlands),
Jantje Beton,TRUE,NL,Social Welfare (Netherlands),
Jeugdeducatiefonds,TRUE,NL,Social Welfare (Netherlands),
Jeugdfonds Sport & Cultuur,TRUE,NL,Social Welfare (Netherlands),
Kansfonds,TRUE,NL,Social Welfare (Netherlands),
Kinderhulp,TRUE,NL,Social Welfare (Netherlands),
Koninklijke Nederlandse Reddingsmaatschappij,TRUE,NL,Social Welfare (Netherlands),
LINDA.foundation,TRUE,NL,Social Welfare (Netherlands),
Landelijk Samenwerkingsverband Actieve Bewoners & Social Enterprise NL,TRUE,NL,Social Welfare (Netherlands),
Landelijk Samenwerkingsverband Actieve bewoners (LSA),TRUE,NL,Social Welfare (Netherlands),
Leergeld Nederland,TRUE,NL,Social Welfare (Netherlands),
Leger des Heils,TRUE,NL,Social Welfare (Netherlands),
Lokale Fondsen Nederland,TRUE,NL,Social Welfare (Netherlands),
Make-A-Wish Nederland,TRUE,NL,Social Welfare (Netherlands),
Nationaal Ouderenfonds,TRUE,NL,Social Welfare (Netherlands),
Nationale Vereniging de Zonnebloem,TRUE,NL,Social Welfare (Netherlands),
Nice Place Foundation,TRUE,NL,Social Welfare (Netherlands),
Oranje Fonds,TRUE,NL,Social Welfare (Netherlands),
Postcode Loterij Buurtfonds,TRUE,NL,Social Welfare (Netherlands),
Sam voor alle kinderen,TRUE,NL,Social Welfare (Netherlands),
SamenSpeelFonds,TRUE,NL,Social Welfare (Netherlands),
Stichting DOEN,TRUE,NL,Social Welfare (Netherlands),
Stichting De Buurt,TRUE,NL,Social Welfare (Netherlands),
Stichting Elisabeth Samson Huis,TRUE,NL,Social Welfare (Netherlands),
Stichting Gilat,TRUE,NL,Social Welfare (Netherlands),
Stichting IPSO,TRUE,NL,Social Welfare (Netherlands),
Stichting Jarige Job,TRUE,NL,Social Welfare (Netherlands),
Stichting Join Us,TRUE,NL,Social Welfare (Netherlands),
Stichting KiKiD,TRUE,NL,Social Welfare (Netherlands),
Stichting Leeuw,TRUE,NL,Social Welfare (Netherlands),
Stichting Life Goals Nederland,TRUE,NL,Social Welfare (Netherlands),
Stichting MAX Maakt Mogelijk,TRUE,NL,Social Welfare (Netherlands),
Stichting Mainline,TRUE,NL,Social Welfare (Netherlands),
Stichting Move,TRUE,NL,Social Welfare (Netherlands),
Stichting Sheltersuit,TRUE,NL,Social Welfare (Netherlands),
Stichting Thuisgekookt,TRUE,NL,Social Welfare (Netherlands),
Vereniging SchuldHulpMaatje Nederland,TRUE,NL,Social Welfare (Netherlands),
Vier het Leven,TRUE,NL,Social Welfare (Netherlands),
Voedselbanken Nederland,TRUE,NL,Social Welfare (Netherlands),
WOMEN Inc.,TRUE,NL,Social Welfare (Netherlands),
Young Impact,TRUE,NL,Social Welfare (Netherlands),
AMC Foundation Medicijn voor de maatschappij,TRUE,NL,Health & Medical,
Aidsfonds,TRUE,NL,Health & Medical,
Alzheimer Nederland,TRUE,NL,Health & Medical,
Amref Health Africa,TRUE,NL,Health & Medical,
Amref Health Africa en PharmAccess (extra bijdrage Droomfonds 2015),FALSE,NL,Health & Medical,
Artsen zonder Grenzen,TRUE,NL,Health & Medical,
Bas van de Goor Foundation,TRUE,NL,Health & Medical,
Diabetes Fonds,TRUE,NL,Health & Medical,
Drugs for Neglected Diseases Initiative,FALSE,Switzerland,Health & Medical,
Edwin van der Sar Foundation,TRUE,NL,Health & Medical,
EpilepsieNL,TRUE,NL,Health & Medical,
Fonds Gehandicaptensport,TRUE,NL,Health & Medical,
HandicapNL,TRUE,NL,Health & Medical,
Hartstichting,TRUE,NL,Health & Medical,
HealthNet,TRUE,NL,Health & Medical,
Healthy Entrepreneurs,TRUE,NL,Health & Medical,
Hersenstichting,TRUE,NL,Health & Medical,
Hivos,TRUE,NL,Health & Medical,
KNCV Tuberculosefonds,TRUE,NL,Health & Medical,
KWF Kankerbestrijding,TRUE,NL,Health & Medical,
Kinderziekenhuizen van Oranje,TRUE,NL,Health & Medical,
Leprastichting,TRUE,NL,Health & Medical,
Longfonds,TRUE,NL,Health & Medical,
Longfonds & MIND - Project Bruis,TRUE,NL,Health & Medical,
MDL Fonds,TRUE,NL,Health & Medical,
MIND,TRUE,NL,Health & Medical,
MIND Us,TRUE,NL,Health & Medical,
Maggies Centers Nederland,TRUE,NL,Health & Medical,
Metakids,TRUE,NL,Health & Medical,
Nederlandse Brandwonden Stichting,TRUE,NL,Health & Medical,
Nederlandse Vereniging voor Autisme,TRUE,NL,Health & Medical,
Nierstichting,TRUE,NL,Health & Medical,
Nierstichting - Samen voor de nieuwe generatie nieren,TRUE,NL,Health & Medical,
Oogfonds,TRUE,NL,Health & Medical,
ParkinsonNL,TRUE,NL,Health & Medical,
PharmAccess,TRUE,NL,Health & Medical,
Pink Ribbon,TRUE,NL,Health & Medical,
Prinses Beatrix Spierfonds,TRUE,NL,Health & Medical,
Resto VanHarte,TRUE,NL,Health & Medical,
ReumaNederland,TRUE,NL,Health & Medical,
Ronald McDonald Kinderfonds,TRUE,NL,Health & Medical,
Spieren voor Spieren,TRUE,NL,Health & Medical,
Stichting ALS Nederland,TRUE,NL,Health & Medical,
Stichting Anne-Bo,TRUE,NL,Health & Medical,
Stichting Cliniclowns Nederland,TRUE,NL,Health & Medical,
Stichting Hartekind,TRUE,NL,Health & Medical,
Stichting MS Research,TRUE,NL,Health & Medical,
Stichting Met je hart,TRUE,NL,Health & Medical,
Stichting ease,TRUE,NL,Health & Medical,
Stichting het Gehandicapte Kind,TRUE,NL,Health & Medical,
Trombosestichting Nederland,TRUE,NL,Health & Medical,
Ashoka,TRUE,NL,Education & Sport,
Dirk Kuyt Foundation,TRUE,NL,Education & Sport,
Esther Vergeer Foundation,TRUE,NL,Education & Sport,
Giovanni van Bronckhorst Foundation,TRUE,NL,Education & Sport,
JINC,TRUE,NL,Education & Sport,
Krajicek Foundation,TRUE,NL,Education & Sport,
Rafa Nadal Foundation,FALSE,Spain,Education & Sport,
Right To Play,TRUE,NL,Education & Sport,
Roger Federer Foundation,FALSE,Switzerland,Education & Sport,
Room to Read,FALSE,USA,Education & Sport,
Scouting Nederland,TRUE,NL,Education & Sport,
Space Buzz Foundation,TRUE,NL,Education & Sport,
Stichting 3X3 Unites,TRUE,NL,Education & Sport,
Stichting leerKRACHT,TRUE,NL,Education & Sport,
Young Perspectives,TRUE,NL,Education & Sport,
Yvonne van Gennip Talent Fonds,TRUE,NL,Education & Sport,
AAP,TRUE,NL,Animal Welfare,
Dierenbescherming,TRUE,NL,Animal Welfare,
Hulphond Nederland,TRUE,NL,Animal Welfare,
International Fund for Animal Welfare (IFAW),TRUE,NL,Animal Welfare,
ProVeg Nederland,TRUE,NL,Animal Welfare,
Stichting DierenLot,TRUE,NL,Animal Welfare,
Wakker Dier,TRUE,NL,Animal Welfare,
World Animal Protection,TRUE,NL,Animal Welfare,
IMC Weekendschool,TRUE,NL,"Culture, Education & Sport",
Johan Cruyff Foundation,TRUE,NL,"Culture, Education & Sport",
Stichting De Schoolschrijver,TRUE,NL,"Culture, Education & Sport",
Stichting Kansengelijkheid Burgerschapsonderwijs,TRUE,NL,"Culture, Education & Sport",
Stichting Lezen en Schrijven,TRUE,NL,"Culture, Education & Sport",
Theirworld - Education in Emergencies,FALSE,UK,"Culture, Education & Sport",
IDFA Bertha Fonds,TRUE,NL,"Culture, Education & Sport",
Movies that Matter,TRUE,NL,"Culture, Education & Sport",
Prins Claus Fonds,TRUE,NL,"Culture, Education & Sport",
Stichting Herman van Veen Arts Center Fonds,TRUE,NL,"Culture, Education & Sport",
What Design Can Do,TRUE,NL,"Culture, Education & Sport",
World Press Photo,TRUE,NL,"Culture, Education & Sport",
Amazon Frontlines,FALSE,International,International Aid & Human Rights
`;
const ORG_OVERVIEW_CSV = `Organisations RAW SORT,organisations,is_dutch,country,theme,description,Joint Grant
100WEEKS,100WEEKS,TRUE,The Netherlands,International Aid & Human Rights,Organisation that supports poverty reduction and income security for people in low-income communities.,FALSE
350.org / Fossielvrij NL,350.org / Fossielvrij NL,TRUE,The Netherlands,Nature & Environment,Climate movement and Dutch campaign group working to end fossil fuel use and accelerate a just energy transition.,FALSE
AAP,AAP,TRUE,The Netherlands,Animal Welfare,"Animal welfare organisation that rescues, rehabilitates and rehomes exotic mammals from poor conditions.",FALSE
ActionAid Nederland,ActionAid Nederland,TRUE,The Netherlands,International Aid & Human Rights,"Dutch branch of ActionAid supporting global campaigns and projects on poverty, inequality and human rights.",FALSE
Aflatoun International,Aflatoun International,TRUE,The Netherlands,International Aid & Human Rights,Education NGO based in the Netherlands that develops social and financial education programmes for children and young people worldwide.,FALSE
African Parks Network,African Parks Network,TRUE,The Netherlands,Nature & Environment,Conservation organisation that manages and restores national parks in partnership with African governments and communities.,FALSE
Aidsfonds,Aidsfonds,TRUE,The Netherlands,Health & Medical,Dutch health charity focused on preventing HIV transmissions and improving treatment and support for people living with HIV.,FALSE
Alzheimer Nederland,Alzheimer Nederland,TRUE,The Netherlands,Health & Medical,Dutch organisation supporting people with dementia and their families and funding research into Alzheimer's disease.,FALSE
Amazon Frontlines,Amazon Frontlines,FALSE,United States,Nature & Environment,"Grassroots organisation based in California that works with Indigenous peoples in the Amazon to defend their land, culture and forests.",FALSE
AMC Foundation Medicijn voor de maatschappij,AMC Foundation Medicijn voor de maatschappij,TRUE,The Netherlands,Health & Medical,Dutch health foundation linked to Amsterdam UMC that supports medical innovation and projects with direct societal impact.,FALSE
Amnesty International,Amnesty International,TRUE,The Netherlands,International Aid & Human Rights,"Dutch section of the global Amnesty movement defending human rights through research, campaigns and advocacy.",FALSE
Amref Health Africa,Amref Health Africa,TRUE,The Netherlands,Health & Medical,Dutch office of Amref supporting health programmes in Africa to strengthen healthcare systems and communities.,FALSE
Amref Health Africa en PharmAccess (extra bijdrage Dream Fund 2015),Amref Health Africa en PharmAccess (extra bijdrage Dream Fund 2015),TRUE,The Netherlands,Health & Medical,Partnership programme of Amref and PharmAccess improving access to quality healthcare and health financing in Africa.,TRUE
APOPO,APOPO,FALSE,International,International Aid & Human Rights,"International NGO that trains detection rats to locate landmines and tuberculosis, making communities safer and improving health.",FALSE
ARK Rewilding Nederland,ARK Rewilding Nederland,TRUE,The Netherlands,Nature & Environment,"Dutch nature organisation that restores wilder, self-regulating ecosystems through rewilding projects across the Netherlands.",FALSE
Artsen zonder Grenzen,Artsen zonder Grenzen,TRUE,The Netherlands,Health & Medical,Dutch branch of Médecins Sans Frontières providing medical emergency aid in crisis and conflict zones worldwide.,FALSE
Ashoka,Ashoka,TRUE,The Netherlands,Education & Sport,"Network organisation that supports social entrepreneurs and change leaders through fellowships, support and collaboration.",FALSE
ASKV Steunpunt Vluchtelingen,ASKV Steunpunt Vluchtelingen,TRUE,The Netherlands,International Aid & Human Rights,"Amsterdam-based organisation offering legal, social and practical support to refugees and undocumented migrants.",FALSE
Bas van de Goor Foundation,Bas van de Goor Foundation,TRUE,The Netherlands,Health & Medical,Health foundation that uses sport and exercise to improve quality of life for people with diabetes.,FALSE
Bellingcat,Bellingcat,TRUE,The Netherlands,International Aid & Human Rights,"Investigative collective using open-source research to uncover truth about conflicts, human rights abuses and corruption.",FALSE
BiD Network,BiD Network,TRUE,The Netherlands,International Aid & Human Rights,Organisation that helps impact-driven small and medium enterprises in emerging markets access finance and business support.,FALSE
Bijzondere uitkeringen,Bijzondere uitkeringen,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch funding stream that provides special grants for social projects and individuals in vulnerable situations.,FALSE
Both ENDS,Both ENDS,TRUE,The Netherlands,International Aid & Human Rights,"Dutch NGO supporting environmental justice, human rights and sustainable development with partners in the Global South.",FALSE
BRAC International,BRAC International,TRUE,The Netherlands,International Aid & Human Rights,"International development organisation working to reduce poverty and inequality through programmes in health, education and livelihoods.",FALSE
Break Free from Plastic (BFFP),Break Free from Plastic (BFFP),FALSE,International,Nature & Environment,Global movement campaigning for a future free from plastic pollution and for major reductions in single-use plastics.,FALSE
Bureau Burgerberaad,Bureau Burgerberaad,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch organisation promoting citizens' assemblies and deliberative democracy to tackle complex social and climate issues.,FALSE
Buzz Women,Buzz Women,TRUE,The Netherlands,Social Welfare (Netherlands),"Organisation that empowers women in vulnerable communities through training, coaching and local savings or enterprise groups.",FALSE
Carbon War Room,Carbon War Room,FALSE,United States,Nature & Environment,International initiative that accelerates solutions to reduce carbon emissions by working with business and policymakers.,FALSE
CARE Nederland,CARE Nederland,TRUE,The Netherlands,International Aid & Human Rights,Dutch member of CARE that supports humanitarian aid and development programmes for people in crisis and poverty.,FALSE
Centrum tegen Kinderhandel en Mensenhandel,Centrum tegen Kinderhandel en Mensenhandel,TRUE,The Netherlands,International Aid & Human Rights,"Dutch centre that combats child trafficking and human trafficking through research, advocacy and specialist support.",FALSE
Circle Economy,Circle Economy,TRUE,The Netherlands,Nature & Environment,Amsterdam-based organisation that helps businesses and cities accelerate the transition to a circular economy.,FALSE
Clinton Foundation,Clinton Foundation,FALSE,United States,International Aid & Human Rights,"Philanthropic foundation that partners with governments, business and civil society on health, climate and economic inclusion programmes.",FALSE
Clooney Foundation for Justice,Clooney Foundation for Justice,FALSE,United States,International Aid & Human Rights,"Foundation that advances justice through strategic litigation, advocacy and support to human rights defenders worldwide.",FALSE
CNV Internationaal,CNV Internationaal,TRUE,The Netherlands,International Aid & Human Rights,International arm of Dutch trade union CNV that supports workers' rights and decent work with unions in low-wage countries.,FALSE
COC Nederland,COC Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),"National LGBTI+ advocacy organisation promoting equal rights, social acceptance and safety for queer people in the Netherlands.",FALSE
Commonland,Commonland,TRUE,The Netherlands,Nature & Environment,"Dutch organisation that develops large-scale landscape restoration projects that combine ecology, economy and local communities.",FALSE
Commonland - Het Groene Goud,Commonland - Het Groene Goud,TRUE,The Netherlands,Nature & Environment,"Programme under CommoThe Netherlandsand that supports regenerative agriculture and landscape restoration showcased in the film ""Het Groene Goud"".",FALSE
Cordaid,Cordaid,TRUE,The Netherlands,International Aid & Human Rights,"Dutch development and humanitarian organisation focused on fragile contexts, combining emergency aid with long-term development.",FALSE
Crisis Action,Crisis Action,FALSE,United Kingdom,International Aid & Human Rights,International NGO that helps civil society organisations coordinate advocacy to protect civilians in war and conflict.,FALSE
Cultural Emergency Response,Cultural Emergency Response,TRUE,The Netherlands,Culture,"Programme of the Prince Claus Fund that provides rapid support to protect cultural heritage in crisis zones worldwide, acting as a cultural ""ambulance"".",FALSE
Dance4Life,Dance4Life,TRUE,The Netherlands,International Aid & Human Rights,Dutch youth organisation using education and peer influence to improve sexual health and rights of young people worldwide.,FALSE
De Buurt,De Buurt,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch non-profit foundation that strengthens social cohesion by organising low-threshold neighbourhood activities across the country.,FALSE
De Buzinezzclub,De Buzinezzclub,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch social enterprise offering coaching and training to young people without work or education to improve their prospects.,FALSE
De Natuur en Milieufederaties,De Natuur en Milieufederaties,TRUE,The Netherlands,Nature & Environment,Network of provincial nature and environmental federations in the Netherlands that advocate for a healthy living environment.,FALSE
De Vrolijkheid,De Vrolijkheid,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch organisation that organises creative activities for children and young people in asylum seekers' centres.,FALSE
Defence for Children,Defence for Children,TRUE,The Netherlands,International Aid & Human Rights,Children's rights organisation that promotes and protects the rights of children in the Netherlands and worldwide.,FALSE
Deltaplan Biodiversiteitsherstel,Deltaplan Biodiversiteitsherstel,TRUE,The Netherlands,Nature & Environment,Dutch multi-stakeholder initiative to halt and reverse biodiversity loss in the Netherlands.,FALSE
Diabetes Fonds,Diabetes Fonds,TRUE,The Netherlands,Health & Medical,"Dutch health fund that finances research, prevention and better treatment for diabetes.",FALSE
Dierenbescherming,Dierenbescherming,TRUE,The Netherlands,Animal Welfare,"Dutch Society for the Protection of Animals, working to improve animal welfare through rescue, shelters and advocacy.",FALSE
Dirk Kuyt Foundation,Dirk Kuyt Foundation,TRUE,The Netherlands,Education & Sport,"Foundation that promotes sports participation for people with a disability or chronic illness, inspired by footballer Dirk Kuyt.",FALSE
Dokters van de Wereld,Dokters van de Wereld,TRUE,The Netherlands,International Aid & Human Rights,Dutch branch of Médecins du Monde providing medical and social support to people who otherwise miss out on healthcare.,FALSE
DollyWood Foundation,DollyWood Foundation,FALSE,United States,Education & Sport,"U.S. foundation behind Dolly Parton's Imagination Library, gifting free books to young children to foster early literacy.",FALSE
Dona Daria,Dona Daria,TRUE,The Netherlands,Social Welfare (Netherlands),"Rotterdam-based organisation promoting social inclusion, gender equality and participation in diverse urban communities.",FALSE
Dr. Denis Mukwege Foundation,Dr. Denis Mukwege Foundation,TRUE,The Netherlands,International Aid & Human Rights,Organisation that supports survivors of conflict-related sexual violence and works for justice and prevention worldwide.,FALSE
Drugs for Neglected Diseases Initiative,Drugs for Neglected Diseases Initiative,FALSE,Switzerland,Health & Medical,International non-profit R&D organisation developing treatments for neglected diseases affecting vulnerable populations.,FALSE
Dutch Caribbean Nature Alliance,Dutch Caribbean Nature Alliance,TRUE,The Netherlands,Nature & Environment,Network of nature organisations on the Dutch Caribbean islands focused on protecting biodiversity and marine and terrestrial parks.,FALSE
Edukans,Edukans,TRUE,The Netherlands,International Aid & Human Rights,Dutch NGO improving education quality and access for children and young people in low-income countries.,FALSE
Edwin van der Sar Foundation,Edwin van der Sar Foundation,TRUE,The Netherlands,Health & Medical,Foundation that supports people with brain damage and their families through rehabilitation projects and awareness.,FALSE
Emma at Work,Emma at Work,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch non-profit and social enterprise that supports young people with chronic physical conditions to develop skills and find suitable work.,FALSE
Enviu,Enviu,TRUE,The Netherlands,Nature & Environment,Impact-driven venture builder that launches social enterprises tackling environmental and social challenges.,FALSE
EpilepsieNL,EpilepsieNL,TRUE,The Netherlands,Health & Medical,Dutch organisation funding research and providing information and support for people living with epilepsy.,FALSE
Esther Vergeer Foundation,Esther Vergeer Foundation,TRUE,The Netherlands,Education & Sport,"Sports foundation that enables children with a disability to participate structurally in sport, inspired by wheelchair tennis player Esther Vergeer.",FALSE
European AI & Society Fund,European AI & Society Fund,FALSE,Belgium,International Aid & Human Rights,Fund hosted by the Network of European Foundations in Brussels that supports civil-society organisations to shape AI policy in the public interest and protect rights.,FALSE
European Climate Foundation,European Climate Foundation,TRUE,The Netherlands,Nature & Environment,Philanthropic organisation that supports climate and energy policies to reduce greenhouse gas emissions in Europe.,FALSE
Everyday Heroes,Everyday Heroes,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch initiative that provides small, direct financial support for people in vulnerable situations to achieve concrete goals.",FALSE
Fairfood,Fairfood,TRUE,The Netherlands,International Aid & Human Rights,"Dutch NGO working towards fair and sustainable food supply chains, especially for smallholder farmers and workers.",FALSE
FairWork,FairWork,TRUE,The Netherlands,International Aid & Human Rights,Organisation in the Netherlands that combats human trafficking and labour exploitation and supports affected workers.,FALSE
Fauna & Flora International,Fauna & Flora International,FALSE,United Kingdom,Nature & Environment,Conservation charity working globally to protect threatened species and ecosystems in collaboration with local partners.,FALSE
Fonds Gehandicaptensport,Fonds Gehandicaptensport,TRUE,The Netherlands,Health & Medical,Dutch fund that supports sports opportunities for people with disabilities.,FALSE
Fonds Slachtofferhulp,Fonds Slachtofferhulp,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch fund providing practical and psychological support for victims of crime, accidents and disasters.",FALSE
Fonds Slachtofferhulp en Centrum Seksueel Geweld,Fonds Slachtofferhulp en Centrum Seksueel Geweld,TRUE,The Netherlands,Social Welfare (Netherlands),Collaboration that strengthens support for victims of sexual violence through specialised services and victim support.,FALSE
Forbidden Stories,Forbidden Stories,FALSE,France,International Aid & Human Rights,"Journalism organisation that continues and publishes investigations of threatened, jailed or murdered reporters.",FALSE
Forest Stewardship Council (FSC),Forest Stewardship Council (FSC),FALSE,Germany,Nature & Environment,International certification system that promotes responsible forest management and sustainable timber and paper products.,FALSE
Forward Inc,Forward Inc,TRUE,The Netherlands,International Aid & Human Rights,Dutch organisation that supports refugees in starting and growing their own businesses through training and mentoring.,FALSE
Free a Girl,Free a Girl,TRUE,The Netherlands,International Aid & Human Rights,Dutch foundation combating sexual exploitation of children by rescuing girls and prosecuting perpetrators.,FALSE
Free Press Unlimited,Free Press Unlimited,TRUE,The Netherlands,International Aid & Human Rights,Media NGO that strengthens independent journalism and access to information in restrictive environments.,FALSE
Freedom House,Freedom House,FALSE,United States,International Aid & Human Rights,"US-based organisation that conducts research and advocacy on democracy, political freedom and human rights worldwide.",FALSE
Front Line Defenders,Front Line Defenders,FALSE,Ireland,International Aid & Human Rights,International organisation that protects human rights defenders at risk through rapid support and advocacy.,FALSE
Giovanni van Bronckhorst Foundation,Giovanni van Bronckhorst Foundation,TRUE,The Netherlands,Education & Sport,"Dutch foundation using sport and education programmes to support children's development, inspired by footballer Giovanni van Bronckhorst.",FALSE
Girls First Fund,Girls First Fund,FALSE,United States,International Aid & Human Rights,Global donor collaborative that funds community-based organisations working to end child marriage and support girls.,FALSE
Girls Not Brides,Girls Not Brides,FALSE,United Kingdom,International Aid & Human Rights,Global partnership of civil society organisations committed to ending child marriage and supporting girls' rights.,FALSE
Global Fishing Watch,Global Fishing Watch,FALSE,United States,Nature & Environment,International NGO that uses satellite data and transparency tools to combat illegal fishing and protect ocean ecosystems.,FALSE
Global Witness,Global Witness,FALSE,United Kingdom,International Aid & Human Rights,Investigative NGO exposing environmental and human rights abuses driven by corruption and natural resource exploitation.,FALSE
Goois Natuurreservaat,Goois Natuurreservaat,TRUE,The Netherlands,Nature & Environment,Regional nature organisation managing and protecting landscapes and biodiversity in the Gooi region of the Netherlands.,FALSE
Greenpeace,Greenpeace,TRUE,The Netherlands,Nature & Environment,"Environmental organisation using campaigns and non-violent direct action to protect nature and promote a green, peaceful future.",FALSE
Habitat for Humanity Nederland,Habitat for Humanity Nederland,TRUE,The Netherlands,International Aid & Human Rights,Dutch affiliate of Habitat for Humanity supporting safe and affordable housing projects worldwide.,FALSE
HandicapNL,HandicapNL,TRUE,The Netherlands,Health & Medical,Dutch organisation improving quality of life and participation for people with physical or mental disabilities.,FALSE
HandicapNL - MBO op maat,HandicapNL - MBO op maat,TRUE,The Netherlands,Education & Sport,"Dutch charity HandicapThe Netherlands's ""MBO op Maat"" programme develops tailored vocational learning pathways for young people with mild intellectual disabilities.",FALSE
Hartstichting,Hartstichting,TRUE,The Netherlands,Health & Medical,"Dutch Heart Foundation funding research, prevention and care to reduce cardiovascular disease.",FALSE
Hartstichting en Diabetes Fonds,Hartstichting en Diabetes Fonds,TRUE,The Netherlands,Health & Medical,"Dutch Heart Foundation and Diabetes Fonds fund research, prevention and better care for cardiovascular disease and diabetes in the Netherlands.",FALSE
HealthNet,HealthNet,TRUE,The Netherlands,Health & Medical,International NGO with a Dutch base that strengthens health systems and mental health care in fragile and conflict-affected settings.,TRUE
Healthy Entrepreneurs,Healthy Entrepreneurs,TRUE,The Netherlands,Health & Medical,Social enterprise that trains local health entrepreneurs to sell essential health products in remote communities.,FALSE
Heifer Nederland,Heifer Nederland,TRUE,The Netherlands,International Aid & Human Rights,Dutch office supporting Heifer's work with smallholder farmers to build sustainable livelihoods and food security.,FALSE
Hersenstichting,Hersenstichting,TRUE,The Netherlands,Health & Medical,Dutch Brain Foundation funding research and providing information on brain disorders and brain health.,FALSE
Het Nederlandse Rode Kruis,Het Nederlandse Rode Kruis,TRUE,The Netherlands,International Aid & Human Rights,"Dutch Red Cross providing emergency aid, disaster response and support to vulnerable people at home and abroad.",FALSE
Het Vergeten Kind,Het Vergeten Kind,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch organisation improving the situation of vulnerable children in difficult home or care situations in the Netherlands.,FALSE
HIER klimaatbureau,HIER klimaatbureau,TRUE,The Netherlands,Nature & Environment,Dutch climate organisation encouraging households and organisations to reduce CO? emissions and accelerate the energy transition.,FALSE
Hivos,Hivos,TRUE,The Netherlands,International Aid & Human Rights,"International development and human rights organisation guided by humanist values working with partners in Africa, Asia, Latin America and the Middle East.",FALSE
Hivos & Greenpeace - Alle ogen op de Amazone,Hivos & Greenpeace - Alle ogen op de Amazone,TRUE,The Netherlands,Nature & Environment,Joint campaign by Hivos and Greenpeace to protect the Amazon rainforest and Indigenous rights.,TRUE
Hulphond Nederland,Hulphond Nederland,TRUE,The Netherlands,Animal Welfare,Organisation that trains and places assistance dogs for people with physical or mental disabilities.,FALSE
Human Right Watch,Human Right Watch,TRUE,The Netherlands,International Aid & Human Rights,Human Rights Watch Netherlands office in Amsterdam supports global investigations and advocacy on human rights worldwide.,FALSE
Human Rights Watch,Human Rights Watch,FALSE,United States,International Aid & Human Rights,International human rights organisation that investigates abuses and advocates for justice and accountability worldwide.,FALSE
Humanitas,Humanitas,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch volunteers' organisation offering practical and social support for people who temporarily cannot manage alone.,FALSE
ICCO,ICCO,TRUE,The Netherlands,International Aid & Human Rights,"Dutch development organisation working with partners on inclusive development, food security and economic empowerment.",FALSE
ICCO en Solidaridad,ICCO en Solidaridad,TRUE,The Netherlands,International Aid & Human Rights,Joint programmes of ICCO and Solidaridad focusing on fair and sustainable value chains and smallholder livelihoods.,FALSE
IDFA Bertha Fonds,IDFA Bertha Fonds,TRUE,The Netherlands,"Culture, Education & Sport",Dutch fund that supports documentary filmmakers from the Global South and conflict regions through the IDFA festival network.,FALSE
IMC Weekendschool,IMC Weekendschool,TRUE,The Netherlands,"Culture, Education & Sport",Dutch educational programme offering inspiring weekend classes to children from under-resourced neighbourhoods.,FALSE
Impact Hub Association,Impact Hub Association,FALSE,Austria,International Aid & Human Rights,Global association headquartered in Austria that builds entrepreneurial communities and coworking hubs for social and environmental impact around the world.,FALSE
Impunity Watch,Impunity Watch,TRUE,The Netherlands,International Aid & Human Rights,Human rights NGO that researches impunity and supports victim-centred transitional justice processes.,FALSE
Institute for War & Peace Reporting (IWPR),Institute for War & Peace Reporting (IWPR),FALSE,United Kingdom,International Aid & Human Rights,Independent non-profit that trains local journalists and supports civic activists in conflict and crisis zones to promote reliable information and accountability. iwpr+1,FALSE
Instituut Clingendael,Instituut Clingendael,TRUE,The Netherlands,International Aid & Human Rights,"Dutch think tank specialising in international relations, diplomacy and conflict, providing research and training.",FALSE
International Budget Partnership,International Budget Partnership,FALSE,United States,International Aid & Human Rights,Global organisation that promotes transparent and inclusive public budgeting to reduce poverty and inequality.,FALSE
International Consortium of Investigative Journalists (ICIJ),International Consortium of Investigative Journalists (ICIJ),FALSE,United States,International Aid & Human Rights,Network of investigative journalists collaborating on cross-border investigations into corruption and power abuses.,FALSE
International Fund for Animal Welfare,International Fund for Animal Welfare,TRUE,The Netherlands,Animal Welfare,Stichting IFAW in The Hague raises funds and coordinates work to rescue animals and protect habitats as part of the global IFAW network.,FALSE
International Fund for Animal Welfare (IFAW),International Fund for Animal Welfare (IFAW),TRUE,The Netherlands,Animal Welfare,"International animal welfare organisation rescuing animals and protecting habitats through rescue, advocacy and field projects.",FALSE
Internews,Internews,FALSE,United States,International Aid & Human Rights,International media NGO that supports independent media and access to trustworthy information around the world.,FALSE
IUCN NL,IUCN NL,TRUE,The Netherlands,Nature & Environment,Dutch national committee of IUCN supporting nature conservation and environmental justice projects with partners worldwide.,FALSE
IVN Natuureducatie,IVN Natuureducatie,TRUE,The Netherlands,Nature & Environment,Dutch organisation promoting nature education and connecting people with local nature through activities and volunteer networks.,FALSE
Jantje Beton,Jantje Beton,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation encouraging children to play more outdoors by improving playgrounds and public space.,FALSE
Jeugdeducatiefonds,Jeugdeducatiefonds,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch fund that supports schools in disadvantaged areas to provide extra educational opportunities for pupils.,FALSE
Jeugdfonds Sport & Cultuur,Jeugdfonds Sport & Cultuur,TRUE,The Netherlands,Social Welfare (Netherlands),Funds sports and cultural activities for children from families that cannot afford membership or lessons.,FALSE
JINC,JINC,TRUE,The Netherlands,Education & Sport,Dutch organisation giving young people from under-resourced neighbourhoods a fair chance on the labour market through work experience and coaching.,FALSE
Johan Cruyff Foundation,Johan Cruyff Foundation,TRUE,The Netherlands,"Culture, Education & Sport","Foundation that creates safe play and sports spaces for children and stimulates participation, inspired by Johan Cruyff.",FALSE
Johan Cruyff Foundation en Kraijeck Foundation,Johan Cruyff Foundation en Kraijeck Foundation,TRUE,The Netherlands,Education & Sport,"Two Dutch foundations that create playgrounds and sports projects so children, especially in disadvantaged areas, can play and develop through sport.",FALSE
Join Us,Join Us,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that tackles loneliness among young people by offering group activities and training in more than 100 municipalities and oThe Netherlandsine.,FALSE
Justdiggit,Justdiggit,TRUE,The Netherlands,International Aid & Human Rights,Dutch NGO that uses nature-based solutions and landscape restoration to regreen degraded land in Africa.,FALSE
Justice & Peace,Justice & Peace,TRUE,The Netherlands,International Aid & Human Rights,Hague-based organisation that supports human rights defenders and promotes humane migration and peaceful societies.,FALSE
Justice and Peace - Shelter City Initiative,Justice and Peace - Shelter City Initiative,TRUE,The Netherlands,International Aid & Human Rights,Programme offering temporary safe haven in Dutch cities to human rights defenders at risk.,FALSE
Kansfonds,Kansfonds,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch fund supporting initiatives that help people in vulnerable situations belong and participate in society.,FALSE
Kansfonds en Humanitas,Kansfonds en Humanitas,TRUE,The Netherlands,Social Welfare (Netherlands),"Kansfonds supports projects for people in vulnerable situations, while Humanitas is a national volunteers' association offering practical and social support across Dutch communities.",FALSE
KidsRights,KidsRights,TRUE,The Netherlands,International Aid & Human Rights,Dutch children's rights organisation that supports child-led initiatives and awards the International Children's Peace Prize.,FALSE
Kinderfonds MAMAS,Kinderfonds MAMAS,TRUE,The Netherlands,International Aid & Human Rights,"Organisation that supports community-based ""MAMAS"" in South Africa who care for children growing up in poverty.",FALSE
Kinderhulp,Kinderhulp,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch fund that provides practical support to children in poverty in the Netherlands, such as clothing, bicycles and school items.",FALSE
Kinderpostzegels,Kinderpostzegels,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch charity that works with and for children to create equal opportunities, funded in part through its well-known school stamp campaign.",FALSE
Kinderziekenhuizen van Oranje,Kinderziekenhuizen van Oranje,TRUE,The Netherlands,Health & Medical,Dutch initiative connecting children's hospitals to improve care and experience for seriously ill children.,FALSE
KLABU,KLABU,TRUE,The Netherlands,International Aid & Human Rights,Social enterprise that builds sports clubs and sells sportswear to support refugees and displaced communities.,FALSE
KNCV Tuberculosefonds,KNCV Tuberculosefonds,TRUE,The Netherlands,Health & Medical,"Dutch TB foundation dedicated to the global fight against tuberculosis through research, care and control programmes.",FALSE
Koninklijke Nederlandse Reddingsmaatschappij,Koninklijke Nederlandse Reddingsmaatschappij,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch lifeboat institution providing professional voluntary sea rescue along the Dutch coast and iThe Netherlandsand waters.,FALSE
Krajicek Foundation,Krajicek Foundation,TRUE,The Netherlands,Education & Sport,Foundation that creates playgrounds and sport activities in disadvantaged neighbourhoods to help children develop.,FALSE
KWF Kankerbestrijding,KWF Kankerbestrijding,TRUE,The Netherlands,Health & Medical,"Dutch Cancer Society funding cancer research, prevention and patient support.",TRUE
Land Life Company/Borneo Orangutang Survival Fund,Land Life Company/Borneo Orangutang Survival Fund,TRUE,The Netherlands,Nature & Environment,Collaboration between Land Life Company and Borneo Orangutan Survival to restore forest and protect orangutans.,FALSE
Land van Ons,Land van Ons,TRUE,The Netherlands,Nature & Environment,Citizen cooperative that buys agricultural land in the Netherlands and transitions it to nature-inclusive farming.,FALSE
Landelijk Samenwerkingsverband Actieve Bewoners & Social Enterprise NL,Landelijk Samenwerkingsverband Actieve Bewoners & Social Enterprise NL,TRUE,The Netherlands,Social Welfare (Netherlands),Alliance promoting community-led initiatives and social enterprises that strengthen neighbourhoods.,FALSE
Landelijk Samenwerkingsverband Actieve bewoners (LSA),Landelijk Samenwerkingsverband Actieve bewoners (LSA),TRUE,The Netherlands,Social Welfare (Netherlands),National network of active residents' groups working on local democracy and community initiatives.,FALSE
LandschappenNL,LandschappenNL,TRUE,The Netherlands,Nature & Environment,Umbrella organisation for provincial landscape foundations that manage Dutch cultural landscapes and nature.,FALSE
Leergeld Nederland,Leergeld Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch network that supports children from low-income families with school-related costs so they can participate fully.,FALSE
Leger des Heils,Leger des Heils,TRUE,The Netherlands,Social Welfare (Netherlands),"Salvation Army in the Netherlands providing social work, shelter and support for people on the margins of society.",FALSE
Leonardo DiCaprio Foundation,Leonardo DiCaprio Foundation,FALSE,United States,Nature & Environment,Philanthropic foundation that supports environmental and climate solutions and the protection of wildlife.,FALSE
Leprastichting,Leprastichting,TRUE,The Netherlands,Health & Medical,"Dutch Leprosy Foundation working to detect, treat and prevent leprosy and its consequences worldwide.",FALSE
Lighthouse Reports,Lighthouse Reports,TRUE,The Netherlands,International Aid & Human Rights,Investigative journalism organisation that works with media partners to uncover abuses in areas like migration and climate.,FALSE
Liliane Fonds,Liliane Fonds,TRUE,The Netherlands,International Aid & Human Rights,"Dutch fund supporting children with disabilities in low-income countries to access care, education and participation.",FALSE
LINDA.foundation,LINDA.foundation,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that offers gift cards and support to families living in poverty in the Netherlands.,FALSE
Lokale Fondsen Nederland,Lokale Fondsen Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),Network that strengthens local community foundations across the Netherlands.,FALSE
Longfonds,Longfonds,TRUE,The Netherlands,Health & Medical,Dutch Lung Foundation funding research and advocating for clean air and better care for people with lung disease.,FALSE
Longfonds & MIND - Project Bruis,Longfonds & MIND - Project Bruis,TRUE,The Netherlands,Health & Medical,Joint project of Longfonds and MIND that supports people with lung disease and mental health challenges to stay active and connected.,FALSE
Maggies Centers Nederland,Maggies Centers Nederland,TRUE,The Netherlands,Health & Medical,"Dutch initiative related to Maggie's Centres that provides warm, informal support environments for people with cancer.",FALSE
Make-A-Wish Nederland,Make-A-Wish Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch branch of Make-A-Wish granting wishes to seriously ill children.,FALSE
Mama Cash,Mama Cash,TRUE,The Netherlands,International Aid & Human Rights,"Feminist fund that supports women's, girls', trans and intersex-led movements for human rights and social justice.",FALSE
Marine Stewardship Council,Marine Stewardship Council,FALSE,United Kingdom,Nature & Environment,International non-profit that sets standards for sustainable fishing and certifies fisheries and seafood products.,FALSE
MDL Fonds,MDL Fonds,TRUE,The Netherlands,Health & Medical,Dutch fund supporting research and better treatment for gastrointestinal and liver diseases.,TRUE
Media Development Investment Fund (MDIF),Media Development Investment Fund (MDIF),FALSE,United States,International Aid & Human Rights,Investment fund that supports independent media companies with finance and advice in challenging environments.,FALSE
Mensen met een Missie,Mensen met een Missie,TRUE,The Netherlands,International Aid & Human Rights,"Catholic mission-driven development organisation from The Hague that supports local partners combating exclusion, violence and injustice in conflict-affected countries.",FALSE
Metakids,Metakids,TRUE,The Netherlands,Health & Medical,Dutch health fund raising money for research into metabolic diseases in children.,FALSE
Milieudefensie,Milieudefensie,TRUE,The Netherlands,Nature & Environment,Dutch environmental organisation (Friends of the Earth Netherlands) campaigning for climate justice and a healthy environment.,FALSE
MIND,MIND,TRUE,The Netherlands,Health & Medical,Dutch mental health organisation that advocates for better mental healthcare and supports people with psychological problems.,FALSE
MIND Us,MIND Us,TRUE,The Netherlands,Health & Medical,Dutch foundation focusing on the mental wellbeing of young people and the prevention of psychological problems.,FALSE
Missing Chapter Foundation,Missing Chapter Foundation,TRUE,The Netherlands,International Aid & Human Rights,Organisation that brings children and decision-makers together so children's perspectives influence policy and business.,FALSE
Mondiaal FNV,Mondiaal FNV,TRUE,The Netherlands,International Aid & Human Rights,International programme of Dutch trade union FNV that supports unions and workers' rights worldwide.,FALSE
Movement on the Ground,Movement on the Ground,TRUE,The Netherlands,International Aid & Human Rights,"Dutch foundation that provides humane, community-based support to refugees in and around camps.",FALSE
Movies that Matter,Movies that Matter,TRUE,The Netherlands,"Culture, Education & Sport",Dutch foundation that uses film screenings and festivals to stimulate discussion on human rights and social justice.,FALSE
Nadia's Initiative,Nadia's Initiative,FALSE,United States,International Aid & Human Rights,"Survivor-led organisation founded by Nadia Murad that rebuilds communities in crisis and advocates for survivors of sexual violence, with a focus on the Yazidi homeland in Sinjar.",FALSE
Nationaal Fonds Kinderhulp,Nationaal Fonds Kinderhulp,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch fund that helps children and young people growing up in poverty in the Netherlands with practical support, from clothing to days out and education costs.",FALSE
Nationaal Ouderenfonds,Nationaal Ouderenfonds,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that combats loneliness and social isolation among older people in the Netherlands.,FALSE
National Geographic Society,National Geographic Society,FALSE,United States,Nature & Environment,"Global non-profit supporting science, exploration and education to deepen understanding of the planet.",FALSE
Nationale Vereniging de Zonnebloem,Nationale Vereniging de Zonnebloem,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch association that organises activities and holidays for people with a physical disability to reduce loneliness.,FALSE
Natuur & Milieu,Natuur & Milieu,TRUE,The Netherlands,Nature & Environment,"Dutch environmental organisation advocating for sustainable energy, mobility and food systems.",FALSE
Natuur & Milieu en Stichting De Noordzee - De Rijke Noordzee,Natuur & Milieu en Stichting De Noordzee - De Rijke Noordzee,TRUE,The Netherlands,Nature & Environment,"Joint programme improving nature in the North Sea, including restoring reefs and underwater biodiversity.",FALSE
Natuurmonumenten,Natuurmonumenten,TRUE,The Netherlands,Nature & Environment,"Dutch society that buys, protects and manages nature reserves and landscapes across the Netherlands.",FALSE
Natuurmonumenten - Rotterdam de Boer op!,Natuurmonumenten - Rotterdam de Boer op!,TRUE,The Netherlands,Nature & Environment,Programme encouraging farmers around Rotterdam to adopt nature-inclusive agriculture and open up land for nature.,FALSE
Nederlandse Brandwonden Stichting,Nederlandse Brandwonden Stichting,TRUE,The Netherlands,Health & Medical,"Dutch Burns Foundation supporting burn care, research and prevention.",FALSE
Nederlandse Helsinki Comité,Nederlandse Helsinki Comité,TRUE,The Netherlands,International Aid & Human Rights,"Netherlands Helsinki Committee is a human-rights NGO that strengthens rule of law, democratic institutions and protection of vulnerable groups in Europe and Central Asia.",FALSE
Nederlandse Vereniging voor Autisme,Nederlandse Vereniging voor Autisme,TRUE,The Netherlands,Health & Medical,Dutch association representing people with autism and their families and improving understanding and support.,FALSE
NewBees,NewBees,TRUE,The Netherlands,Social Welfare (Netherlands),Social enterprise that prepares newcomers and refugees in the Netherlands for work by matching them to traineeships with local organisations and businesses.,FALSE
Nice Place Foundation,Nice Place Foundation,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that creates inclusive meeting places and activities to strengthen social cohesion.,FALSE
Nierstichting,Nierstichting,TRUE,The Netherlands,Health & Medical,"Dutch Kidney Foundation funding research, prevention and better treatment for kidney disease.",FALSE
Nierstichting - Samen voor de nieuwe generatie nieren,Nierstichting - Samen voor de nieuwe generatie nieren,TRUE,The Netherlands,Health & Medical,Programme that accelerates innovation towards better dialysis and donor organ solutions for kidney patients.,FALSE
Not On Our Watch,Not On Our Watch,FALSE,United States,International Aid & Human Rights,Foundation originally founded by film-makers that supports efforts to end mass atrocities and human rights abuses.,FALSE
Obama Foundation,Obama Foundation,FALSE,United States,International Aid & Human Rights,"Foundation that inspires, trains and connects emerging leaders to tackle challenges in their communities.",FALSE
Oceana,Oceana,FALSE,United States,Nature & Environment,International ocean conservation organisation campaigning for science-based policies to restore marine abundance.,FALSE
One Acre Fund,One Acre Fund,FALSE,United States,International Aid & Human Rights,"Organisation that supports smallholder farmers in Africa with training, inputs and market access to improve harvests and incomes.",FALSE
Oogfonds,Oogfonds,TRUE,The Netherlands,Health & Medical,"Dutch Eye Fund supporting research, prevention and better care for eye diseases and visual impairment.",FALSE
Oranje Fonds,Oranje Fonds,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch fund that supports social initiatives that strengthen community spirit and participation.,FALSE
Organized Crime and Corruption Reporting Project,Organized Crime and Corruption Reporting Project,TRUE,The Netherlands,International Aid & Human Rights,Stichting OCCRP in Amsterdam supports a global network of investigative journalists exposing organised crime and corruption and publishing cross-border investigations.,FALSE
Organized Crime and Corruption Reporting Project (OCCRP),Organized Crime and Corruption Reporting Project (OCCRP),FALSE,United States,International Aid & Human Rights,Global network of investigative centres and journalists exposing organised crime and corruption.,FALSE
Oxfam Novib,Oxfam Novib,TRUE,The Netherlands,International Aid & Human Rights,"Dutch affiliate of Oxfam fighting inequality, poverty and injustice worldwide.",FALSE
Paris Peace Forum,Paris Peace Forum,FALSE,France,International Aid & Human Rights,"Annual forum and French association that convenes states, international organisations and civil society to develop projects for better global governance and peace.",FALSE
ParkinsonNederland,ParkinsonNederland,TRUE,The Netherlands,Health & Medical,"ParkinsonThe Netherlands is a Dutch health fund that finances research, innovation and information to improve prevention, treatment and quality of life for people with Parkinson's.",FALSE
ParkinsonNL,ParkinsonNL,TRUE,The Netherlands,Health & Medical,"Dutch health fund funding research, innovation and information to improve life for people with Parkinson's.",FALSE
PAX,PAX,TRUE,The Netherlands,International Aid & Human Rights,Dutch peace organisation that works with local partners in conflict areas to protect civilians and build just peace.,FALSE
Peace Parks Foundation,Peace Parks Foundation,FALSE,South Africa,Nature & Environment,Organisation that develops and manages transfrontier conservation areas in southern Africa in partnership with governments.,FALSE
PharmAccess,PharmAccess,TRUE,The Netherlands,Health & Medical,"Dutch organisation improving access to quality healthcare in Africa through health insurance, digital tools and quality standards.",FALSE
Pink Ribbon,Pink Ribbon,TRUE,The Netherlands,Health & Medical,Dutch initiative that raises awareness and funds for breast cancer research and support.,FALSE
Plan International,Plan International,TRUE,The Netherlands,International Aid & Human Rights,International child rights organisation promoting children's rights and equality for girls.,FALSE
Plan International Nederland,Plan International Nederland,TRUE,The Netherlands,International Aid & Human Rights,Dutch member of Plan International that raises funds and campaigns for children's rights and equality for girls in low- and middle-income countries.,FALSE
Plastic Soup Foundation,Plastic Soup Foundation,TRUE,The Netherlands,Nature & Environment,"Dutch NGO campaigning against plastic pollution and its effects on oceans, environment and health.",FALSE
Postcode Loterij Buurtfonds,Postcode Loterij Buurtfonds,TRUE,The Netherlands,Social Welfare (Netherlands),Fund that supports small-scale neighbourhood initiatives that strengthen social cohesion in Dutch communities.,FALSE
Postcode Lottery Green Challenge,Postcode Lottery Green Challenge,TRUE,The Netherlands,Nature & Environment,International competition rewarding start-ups with innovative green business plans that reduce CO? emissions.,FALSE
Prins Claus Fonds,Prins Claus Fonds,TRUE,The Netherlands,"Culture, Education & Sport","Dutch fund that supports artists, cultural practitioners and cultural heritage in contexts of repression or crisis.",FALSE
Prinses Beatrix Spierfonds,Prinses Beatrix Spierfonds,TRUE,The Netherlands,Health & Medical,Dutch fund supporting research and care for people with neuromuscular diseases.,FALSE
Prinses Máxima Centrum Foundation,Prinses Máxima Centrum Foundation,TRUE,The Netherlands,Health & Medical,"Stichting Prinses Máxima Centrum Foundation in Utrecht supports the Princess Máxima Centre for Paediatric Oncology, Europe's largest childhood cancer centre.",FALSE
Progreso,Progreso,TRUE,The Netherlands,International Aid & Human Rights,Dutch foundation supporting sustainable coffee and cocoa value chains and smallholder farmers' livelihoods.,FALSE
ProVeg Nederland,ProVeg Nederland,TRUE,The Netherlands,Animal Welfare,"Dutch branch of ProVeg promoting plant-based diets and reducing animal product consumption for animals, health and climate.",FALSE
Quiet Nederland,Quiet Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),"National umbrella for Quiet communities that relieve ""silent"" poverty in the Netherlands by offering members social support and small in-kind treats via local sponsors.",FALSE
Rafa Nadal Foundation,Rafa Nadal Foundation,FALSE,Spain,Education & Sport,Foundation using sport and education projects to support socially vulnerable children and young people.,FALSE
Rainforest Foundation,Rainforest Foundation,FALSE,United States,Nature & Environment,"Part of the Rainforest Foundation network, Rainforest Foundation US partners with Indigenous peoples to protect tropical forests and defend land and livelihood rights.",FALSE
Rare,Rare,FALSE,United States,International Aid & Human Rights,International NGO that uses behavioural science and community campaigns to encourage sustainable practices and conservation.,FALSE
RAVON en Good Fish Foundation,RAVON en Good Fish Foundation,TRUE,The Netherlands,Nature & Environment,Partnership that combines freshwater and marine species research with sustainable seafood guidance for consumers and businesses.,FALSE
Re:wild,Re:wild,TRUE,The Netherlands,International Aid & Human Rights,"First global fund by and for sex workers, hosted by Mama Cash in Amsterdam, that finances sex worker-led organisations advocating for health, labour and human rights.",FALSE
Red Umbrella Fund,Red Umbrella Fund,TRUE,The Netherlands,International Aid & Human Rights,"Dutch social enterprise supporting refugees to gain work experience, training and paid employment.",FALSE
Refugee Company,Refugee Company,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch non-profit that runs social neighbourhood restaurants where people can share affordable meals and meet others to reduce loneliness and social isolation.,FALSE
Resto VanHarte,Resto VanHarte,TRUE,The Netherlands,Health & Medical,Dutch organisation funding research and providing information and support for people with rheumatic diseases.,FALSE
ReumaNederland,ReumaNederland,TRUE,The Netherlands,Nature & Environment,Dutch organisation that organises wilderness trips and outdoor experiences to help people reconnect with nature and reduce stress.,FALSE
Rewilding Argentina,Rewilding Argentina,FALSE,Argentina,Nature & Environment,Argentine foundation that restores ecosystems by reintroducing native species and creating protected areas linked to nature-based tourism for local communities.,FALSE
Rewilding Europe,Rewilding Europe,TRUE,The Netherlands,Nature & Environment,Dutch-based foundation that advances rewilding and large-scale nature restoration across multiple European landscapes.,FALSE
Right To Play,Right To Play,TRUE,The Netherlands,Education & Sport,"Organisation that uses play and sport-based learning to protect, educate and empower children in vulnerable communities.",FALSE
RNW Media,RNW Media,TRUE,The Netherlands,International Aid & Human Rights,Dutch media NGO focusing on digital communities and oThe Netherlandsine platforms for young people in restrictive settings.,FALSE
Rocky Mountain Institute,Rocky Mountain Institute,FALSE,United States,Nature & Environment,Non-profit think tank that works globally to accelerate the clean energy transition and improve energy efficiency.,FALSE
Rode Kruis,Rode Kruis,TRUE,The Netherlands,International Aid & Human Rights,"The Netherlands Red Cross provides emergency aid and first-line support in crises at home and abroad, assisting people in need without discrimination.",FALSE
Roger Federer Foundation,Roger Federer Foundation,FALSE,Switzerland,Education & Sport,"Foundation supporting children's education projects, maiThe Netherlandsy in southern Africa and Switzerland.",FALSE
Ronald McDonald Kinderfonds,Ronald McDonald Kinderfonds,TRUE,The Netherlands,Health & Medical,Dutch fund linked to Ronald McDonald House Charities that provides accommodation and support for families of hospitalised children.,FALSE
Room to Read,Room to Read,FALSE,United States,Education & Sport,International NGO improving literacy and girls' education in low-income countries.,FALSE
Rutgers,Rutgers,TRUE,The Netherlands,International Aid & Human Rights,"Dutch centre of expertise on sexual and reproductive health and rights, working in the Netherlands and internationally.",FALSE
Sam voor alle kinderen,Sam voor alle kinderen,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch initiative that coordinates support for children in poverty, ensuring access to things like sports, culture and school items.",FALSE
SamenSpeelFonds,SamenSpeelFonds,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch fund that supports inclusive playgrounds where children with and without disabilities can play together.,FALSE
Save the Children Nederland,Save the Children Nederland,TRUE,The Netherlands,International Aid & Human Rights,Dutch member of Save the Children that advocates and raises funds for children's rights and protection worldwide.,FALSE
Schone Kleren Campagne,Schone Kleren Campagne,TRUE,The Netherlands,International Aid & Human Rights,Dutch Clean Clothes Campaign working for better working conditions and labour rights in the global garment industry.,FALSE
Scouting Nederland,Scouting Nederland,TRUE,The Netherlands,Education & Sport,National organisation for Scouting in the Netherlands offering youth development through outdoor and group activities.,FALSE
Sea Ranger Service,Sea Ranger Service,TRUE,The Netherlands,Nature & Environment,Dutch social enterprise training young people as Sea Rangers to carry out maritime conservation work and monitoring.,FALSE
Sea Shepherd,Sea Shepherd,TRUE,The Netherlands,Nature & Environment,Dutch arm of Sea Shepherd protecting marine wildlife through direct action and campaigns.,FALSE
Simavi,Simavi,TRUE,The Netherlands,International Aid & Human Rights,"Dutch NGO working on water, sanitation and menstrual health to support women and girls in low-income countries.",FALSE
Solidaridad,Solidaridad,TRUE,The Netherlands,International Aid & Human Rights,International network organisation based in the Netherlands promoting fair and sustainable supply chains for farmers and workers.,FALSE
Solidaridad - Van Klimaatslachtoffers naar Klimaathelden,Solidaridad - Van Klimaatslachtoffers naar Klimaathelden,TRUE,The Netherlands,Nature & Environment,Programme that helps communities vulnerable to climate change become climate heroes through resilient livelihoods.,FALSE
SoortenNL,SoortenNL,TRUE,The Netherlands,Nature & Environment,Dutch platform bringing together species protection organisations to monitor and conserve biodiversity.,FALSE
SOS Kinderdorpen,SOS Kinderdorpen,TRUE,The Netherlands,International Aid & Human Rights,Dutch office of SOS Children's Villages supporting family-based care and strengthening families to prevent child abandonment.,FALSE
Sovon Vogelonderzoek Nederland,Sovon Vogelonderzoek Nederland,TRUE,The Netherlands,Nature & Environment,"Dutch bird research association that organises nationwide bird monitoring and manages data to inform nature policy, conservation and ecological research.",FALSE
Space Buzz Foundation,Space Buzz Foundation,TRUE,The Netherlands,Education & Sport,"Dutch foundation that offers children a virtual ""astronaut experience"" to inspire care for the planet and interest in science.",FALSE
SPARK,SPARK,TRUE,The Netherlands,International Aid & Human Rights,Dutch NGO that supports young people in fragile states with higher education and entrepreneurship opportunities.,FALSE
Spieren voor Spieren,Spieren voor Spieren,TRUE,The Netherlands,Health & Medical,Dutch foundation that raises funds to help children with muscle diseases through research and better care.,FALSE
Stichting 3X3 Unites,Stichting 3X3 Unites,TRUE,The Netherlands,Education & Sport,Dutch foundation using 3x3 basketball to empower young people and build community leaders.,FALSE
Stichting ALS Nederland,Stichting ALS Nederland,TRUE,The Netherlands,Health & Medical,Dutch foundation funding research and care for people living with ALS and related motor neuron diseases.,FALSE
Stichting Ambulance Wens,Stichting Ambulance Wens,TRUE,The Netherlands,Health & Medical,Dutch foundation that fulfils last wishes of terminally ill patients by transporting them safely with specially equipped ambulances and volunteers.,FALSE
Stichting Anne-Bo,Stichting Anne-Bo,TRUE,The Netherlands,Health & Medical,Dutch foundation supporting children with cancer and their families with practical and emotional assistance.,FALSE
Stichting Armoedefonds,Stichting Armoedefonds,TRUE,The Netherlands,Social Welfare (Netherlands),"Foundation that combats poverty in the Netherlands by financially and in-kind supporting local initiatives such as food banks, clothing points and hygiene projects.",FALSE
Stichting Artsen voor Kinderen,Stichting Artsen voor Kinderen,TRUE,The Netherlands,International Aid & Human Rights,"Dutch organisation supporting vulnerable children with medical and social projects, often linked to the healthcare system.",FALSE
Stichting Cliniclowns Nederland,Stichting Cliniclowns Nederland,TRUE,The Netherlands,Health & Medical,Dutch foundation that sends specially trained clowns to visit children and people with dementia in care settings.,FALSE
Stichting De Buurt,Stichting De Buurt,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that strengthens social cohesion by organising accessible neighbourhood activities.,FALSE
Stichting De Kindertelefoon,Stichting De Kindertelefoon,TRUE,The Netherlands,Social Welfare (Netherlands),National helpline where children and young people in the Netherlands can anonymously talk or chat about any concern with trained volunteers.,FALSE
Stichting De Noordzee,Stichting De Noordzee,TRUE,The Netherlands,Nature & Environment,"Dutch NGO focused on protecting the North Sea's nature through research, advocacy and public engagement.",FALSE
Stichting De Schoolschrijver,Stichting De Schoolschrijver,TRUE,The Netherlands,"Culture, Education & Sport",Dutch foundation that brings children's authors into primary schools to improve language skills and reading pleasure.,FALSE
Stichting DierenLot,Stichting DierenLot,TRUE,The Netherlands,Animal Welfare,Dutch animal charity that supports local animal rescue organisations and emergency animal care.,FALSE
Stichting DOEN,Stichting DOEN,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch foundation that funds social enterprises, cultural initiatives and green innovations that contribute to a better world.",FALSE
Stichting ease,Stichting ease,TRUE,The Netherlands,Health & Medical,Dutch initiative offering psychosocial and practical support to people affected by serious illness.,FALSE
Stichting Elisabeth Samson Huis,Stichting Elisabeth Samson Huis,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation restoring the historic Elisabeth Samson House in Suriname and highlighting Black history and heritage.,FALSE
Stichting Gilat,Stichting Gilat,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that organises theatre performances for children in hospitals and care institutions.,FALSE
Stichting Hartekind,Stichting Hartekind,TRUE,The Netherlands,Health & Medical,Dutch foundation funding research and better care for children with congenital heart defects.,FALSE
Stichting Herman van Veen Arts Center Fonds,Stichting Herman van Veen Arts Center Fonds,TRUE,The Netherlands,"Culture, Education & Sport",Foundation that supports the Herman van Veen Arts Center and cultural education for children.,FALSE
Stichting het Gehandicapte Kind,Stichting het Gehandicapte Kind,TRUE,The Netherlands,Health & Medical,Dutch foundation creating inclusive play and sports opportunities for children with disabilities.,FALSE
Stichting IPSO,Stichting IPSO,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch umbrella for cancer information and support centres offering psychosocial care close to home.,FALSE
Stichting Jarige Job,Stichting Jarige Job,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that provides birthday boxes so children in poverty can celebrate their birthdays.,FALSE
Stichting Join Us,Stichting Join Us,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation tackling loneliness among young people through group activities and training.,FALSE
Stichting Kansengelijkheid Burgerschapsonderwijs,Stichting Kansengelijkheid Burgerschapsonderwijs,TRUE,The Netherlands,"Culture, Education & Sport",Foundation that promotes equal opportunities through citizenship education in Dutch schools.,FALSE
Stichting KiKiD,Stichting KiKiD,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that develops interactive lessons on social issues for young people in schools.,FALSE
Stichting Kinderpostzegels Nederland,Stichting Kinderpostzegels Nederland,TRUE,The Netherlands,International Aid & Human Rights,"Dutch foundation working with and for children, funded partly through the annual school stamp campaign.",FALSE
Stichting leerKRACHT,Stichting leerKRACHT,TRUE,The Netherlands,Education & Sport,Dutch foundation that helps schools improve education quality through continuous professional learning cultures.,FALSE
Stichting Leeuw,Stichting Leeuw,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch big cat rescue centre that rehabilitates lions and other big cats and raises awareness on captive wildlife.,FALSE
Stichting Lezen en Schrijven,Stichting Lezen en Schrijven,TRUE,The Netherlands,"Culture, Education & Sport",Dutch foundation working to reduce low literacy among adults and improve basic skills.,FALSE
Stichting Life Goals Nederland,Stichting Life Goals Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch organisation using sport as a means for social inclusion for people in vulnerable situations.,FALSE
Stichting Long COVID,Stichting Long COVID,TRUE,The Netherlands,Health & Medical,Dutch foundation based in Bilthoven that raises funds for biomedical research into causes and treatments of Long COVID and highlights its impact on patients' lives.,FALSE
Stichting Mainline,Stichting Mainline,TRUE,The Netherlands,Social Welfare (Netherlands),Harm reduction organisation that supports people who use drugs and advocates for health-oriented drug policy.,FALSE
Stichting MAX Maakt Mogelijk,Stichting MAX Maakt Mogelijk,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch foundation that supports vulnerable older people in the Netherlands and abroad with practical projects.,FALSE
Stichting Met je hart,Stichting Met je hart,TRUE,The Netherlands,Health & Medical,Dutch foundation that combats loneliness among older people through regular social dinners and meetings.,FALSE
Stichting Move,Stichting Move,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch organisation that connects students with children in underprivileged neighbourhoods to work on local projects together.,FALSE
Stichting MS Research,Stichting MS Research,TRUE,The Netherlands,Health & Medical,Dutch foundation funding research into multiple sclerosis and improving care for people with MS.,FALSE
Stichting Onderzoek Multinationale Ondernemingen,Stichting Onderzoek Multinationale Ondernemingen,TRUE,The Netherlands,International Aid & Human Rights,Dutch research organisation (SOMO) investigating multinationals' impact on people and the environment.,FALSE
Stichting Refugee Company,Stichting Refugee Company,TRUE,The Netherlands,International Aid & Human Rights,"Dutch foundation supporting refugees towards work and participation, often through social enterprises.",FALSE
Stichting Sheltersuit,Stichting Sheltersuit,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch foundation that produces and distributes warm, waterproof Sheltersuits for people experiencing homelessness and refugees.",FALSE
Stichting Thuisgekookt,Stichting Thuisgekookt,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch platform where home cooks share meals with neighbours who need support, such as elderly or carers.",FALSE
Stichting Vluchteling,Stichting Vluchteling,TRUE,The Netherlands,International Aid & Human Rights,Dutch refugee organisation providing emergency aid and protection to refugees and displaced people.,FALSE
Stichting Voedselbosbouw Nederland,Stichting Voedselbosbouw Nederland,TRUE,The Netherlands,Nature & Environment,Dutch foundation that promotes and develops food forests as a sustainable form of agriculture and nature.,FALSE
Stichting voor Vluchteling-Studenten UAF,Stichting voor Vluchteling-Studenten UAF,TRUE,The Netherlands,International Aid & Human Rights,Dutch foundation supporting refugee students and professionals in their studies and integration into the labour market.,TRUE
Terre des Hommes,Terre des Hommes,TRUE,The Netherlands,International Aid & Human Rights,Dutch branch of Terre des Hommes focusing on protection of children from exploitation worldwide.,FALSE
The Climate Group,The Climate Group,FALSE,United Kingdom,Nature & Environment,International non-profit that works with business and governments to accelerate climate action.,FALSE
The Elders,The Elders,FALSE,United Kingdom,International Aid & Human Rights,"Independent group of global leaders founded by Nelson Mandela to work for peace, justice and human rights.",FALSE
The Fund for Global Human Rights,The Fund for Global Human Rights,FALSE,United States,International Aid & Human Rights,International fund that provides long-term support to local human rights organisations around the world.,FALSE
The Hague Institute for Innovation of Law (HiiL),The Hague Institute for Innovation of Law (HiiL),TRUE,The Netherlands,International Aid & Human Rights,Dutch-based organisation that develops and scales people-centred justice innovations.,FALSE
The Hunger Project,The Hunger Project,TRUE,The Netherlands,International Aid & Human Rights,Global movement that empowers people in rural communities to end their own hunger and poverty.,FALSE
The Sentry,The Sentry,FALSE,United States,International Aid & Human Rights,Investigative organisation that tracks dirty money linked to war criminals and kleptocrats to disrupt their financial networks.,FALSE
Theirworld,Theirworld,FALSE,United Kingdom,International Aid & Human Rights,United Kingdom-based education charity working to end the global education crisis and ensure every child has access to quality schooling.,FALSE
Theirworld - Education in Emergencies,Theirworld - Education in Emergencies,FALSE,United Kingdom,"Culture, Education & Sport","Programme that focuses on education for children affected by conflict and crises, including refugee and displaced children.",FALSE
"Theirworld, UNHCR & UNICEF","Theirworld, UNHCR & UNICEF",FALSE,International,International Aid & Human Rights,"Tripartite collaboration supporting education and protection for refugee and displaced children, combining the expertise of all three organisations.",FALSE
Thorn,Thorn,FALSE,United States,International Aid & Human Rights,US-based non-profit that develops technology to defend children from sexual abuse and exploitation oThe Netherlandsine.,FALSE
Trees for All,Trees for All,TRUE,The Netherlands,Nature & Environment,Dutch foundation planting trees in the Netherlands and abroad to offset CO? and restore forests.,FALSE
Triggerise,Triggerise,TRUE,The Netherlands,International Aid & Human Rights,Social enterprise that uses digital platforms to connect young people to sexual and reproductive health services and products.,FALSE
Trombosestichting Nederland,Trombosestichting Nederland,TRUE,The Netherlands,Health & Medical,"Dutch foundation supporting research, awareness and prevention of thrombosis and blood clotting disorders.",FALSE
Tropenbos International,Tropenbos International,TRUE,The Netherlands,Nature & Environment,Dutch-based organisation that strengthens governance and sustainable management of tropical forests.,FALSE
Truth Tellers Summit,Truth Tellers Summit,FALSE,United Kingdom,International Aid & Human Rights,International gathering that supports investigative journalists and truth tellers working on corruption and abuses.,FALSE
UNHCR,UNHCR,TRUE,The Netherlands,International Aid & Human Rights,Dutch fundraising office for UNHCR supporting protection and assistance for refugees and displaced people worldwide.,FALSE
UNICEF,UNICEF,TRUE,The Netherlands,International Aid & Human Rights,Dutch committee that raises funds and advocates for UNICEF's work for children's rights worldwide.,FALSE
Urgenda,Urgenda,TRUE,The Netherlands,Nature & Environment,Dutch organisation that accelerates the sustainability transition and successfully litigated for stronger Dutch climate policy.,FALSE
Vereniging Nederlands Cultuurlandschap,Vereniging Nederlands Cultuurlandschap,TRUE,The Netherlands,Nature & Environment,Organisation dedicated to preserving and developing the traditional cultural landscapes of the Netherlands.,FALSE
Vereniging SchuldHulpMaatje Nederland,Vereniging SchuldHulpMaatje Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch association training volunteers to support people with financial problems and debts.,FALSE
Vfonds,Vfonds,TRUE,The Netherlands,International Aid & Human Rights,"Dutch fund that supports peace, freedom and democracy projects, often linked to war heritage and remembrance.",FALSE
Vier het Leven,Vier het Leven,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch organisation that organises accompanied outings to cultural events for older people who cannot go alone.,FALSE
VluchtelingenWerk Nederland,VluchtelingenWerk Nederland,TRUE,The Netherlands,International Aid & Human Rights,"Dutch Council for Refugees offering legal support, integration guidance and advocacy for refugees.",FALSE
Voedselbanken Nederland,Voedselbanken Nederland,TRUE,The Netherlands,Social Welfare (Netherlands),National umbrella for Dutch food banks distributing surplus food to people in poverty.,FALSE
Vogelbescherming Nederland,Vogelbescherming Nederland,TRUE,The Netherlands,Nature & Environment,Dutch BirdLife partner protecting wild birds and their habitats through conservation and advocacy.,FALSE
Waddenvereniging,Waddenvereniging,TRUE,The Netherlands,Nature & Environment,Dutch association dedicated to protecting the Wadden Sea's nature and landscape.,FALSE
"Waddenvereniging, Stichting De Noordzee & De Natuur en Milieufederaties","Waddenvereniging, Stichting De Noordzee & De Natuur en Milieufederaties",TRUE,The Netherlands,Nature & Environment,"Three Dutch nature organisations that protect the Wadden Sea, the North Sea and wider Dutch environment through advocacy, research and support for provincial green federations.",FALSE
Wakker Dier,Wakker Dier,TRUE,The Netherlands,Animal Welfare,Dutch animal rights organisation campaigning against factory farming and for better animal welfare.,FALSE
War Child,War Child,TRUE,The Netherlands,International Aid & Human Rights,"Dutch organisation supporting children affected by war with psychosocial support, education and protection.",FALSE
WaterAid,WaterAid,FALSE,United Kingdom,Health & Medical,"United Kingdom-based international charity that works with communities to improve access to safe water, sanitation and hygiene in low-income countries.",FALSE
WaterAid Nederland,WaterAid Nederland,TRUE,The Netherlands,International Aid & Human Rights,Dutch member of the WaterAid federation that continues Simavi's legacy by funding WASH projects and promoting gender-equal access to water and sanitation.,FALSE
WeForest,WeForest,FALSE,Belgium,Nature & Environment,International organisation that supports forest restoration projects to fight climate change and benefit local communities.,FALSE
Wemos,Wemos,TRUE,The Netherlands,International Aid & Human Rights,Dutch global health advocacy organisation that works for fair and effective health policies worldwide.,FALSE
Wereld Natuur Fonds,Wereld Natuur Fonds,TRUE,The Netherlands,Nature & Environment,Dutch branch of WWF focusing on global nature conservation and climate projects.,FALSE
Wereld Natuur Fonds en Het Rode Kruis,Wereld Natuur Fonds en Het Rode Kruis,TRUE,The Netherlands,Nature & Environment,Collaboration that combines nature conservation and humanitarian aid in climate-related crises.,FALSE
"Wereld Natuur Fonds, African Parks Network en Peace Parks Foundation","Wereld Natuur Fonds, African Parks Network en Peace Parks Foundation",TRUE,The Netherlands,Nature & Environment,"WWF-Netherlands, together with African Parks and Peace Parks Foundation, works on large-scale nature protection in southern Africa, including the KavangoZambezi transfrontier conservation area.",FALSE
Wetlands International,Wetlands International,TRUE,The Netherlands,Nature & Environment,International NGO headquartered in the Netherlands that conserves and restores wetlands for people and nature.,FALSE
What Design Can Do,What Design Can Do,TRUE,The Netherlands,"Culture, Education & Sport",International design platform based in the Netherlands that uses design to tackle social and environmental issues.,FALSE
Wij.Land,Wij.Land,TRUE,The Netherlands,Nature & Environment,"Dutch organisation working with farmers and partners to restore soils, biodiversity and landscapes in the peat meadow areas.",FALSE
Wilde Ganzen,Wilde Ganzen,TRUE,The Netherlands,International Aid & Human Rights,Dutch NGO that supports small-scale initiatives of people in the Netherlands and their partners in low-income countries.,FALSE
Wildlife Justice Commission,Wildlife Justice Commission,TRUE,The Netherlands,Nature & Environment,Hague-based organisation investigating and exposing transnational wildlife crime networks and seeking justice.,FALSE
Women Engage for a Common Future,Women Engage for a Common Future,TRUE,The Netherlands,International Aid & Human Rights,International network promoting environmental and gender justice by strengthening women's participation in decision-making.,FALSE
WOMEN Inc.,WOMEN Inc.,TRUE,The Netherlands,Social Welfare (Netherlands),"Dutch organisation that works for gender equality in health, work and money through campaigns and advocacy.",FALSE
Women Win,Women Win,TRUE,The Netherlands,International Aid & Human Rights,International organisation that uses sport and economic empowerment programmes to advance the rights of women and girls.,FALSE
World Animal Protection,World Animal Protection,TRUE,The Netherlands,Animal Welfare,"International animal welfare organisation that protects animals in communities, farming and the wild.",FALSE
World Fish Migration Foundation,World Fish Migration Foundation,TRUE,The Netherlands,Nature & Environment,Dutch foundation raising awareness and promoting solutions for free-flowing rivers and migratory fish.,FALSE
World Food Programme,World Food Programme,FALSE,Italy,International Aid & Human Rights,UN agency that provides food assistance in emergencies and works to improve long-term food security and nutrition worldwide.,FALSE
World Food Programme - Fortifying the Future,World Food Programme - Fortifying the Future,FALSE,Italy,Health & Medical,"UN World Food Programme project based out of its Rome headquarters that tackles ""hidden hunger"" by fortifying staple grains such as sorghum and whole-grain maize in countries like India, Senegal and Tanzania.",FALSE
World Press Photo,World Press Photo,TRUE,The Netherlands,"Culture, Education & Sport","Dutch foundation that organises the annual World Press Photo Contest and exhibitions, supporting visual journalism.",FALSE
Young Africa,Young Africa,TRUE,The Netherlands,International Aid & Human Rights,Organisation that runs vocational training centres and life skills programmes for youth in southern Africa.,FALSE
Young Impact,Young Impact,TRUE,The Netherlands,Social Welfare (Netherlands),Dutch initiative that empowers young people to take positive action in society through school and community projects.,FALSE
Young Perspectives,Young Perspectives,TRUE,The Netherlands,Education & Sport,Dutch organisation amplifying children's and young people's voices in policy and services that affect them.,FALSE
Yvonne van Gennip Talent Fonds,Yvonne van Gennip Talent Fonds,TRUE,The Netherlands,Education & Sport,Dutch fund that supports talented young athletes with financial aid for training and development.,FALSE
YY Foundation,YY Foundation,FALSE,Germany,International Aid & Human Rights,"Foundation linked to Professor Muhammad Yunus' social business movement that promotes social businesses to tackle poverty, unemployment and climate challenges.",FALSE
,,,,,,
`;
const PROJ_DESC_CSV = `Category ,Organisation,Amount,Year,Project Location,Project Description
One-time donation,Stichting voor Vluchteling-Studenten UAF,4000000,2016,The Netherlands,Funding for a large mentoring and support programme that allowed UAF to significantly increase the number of refugee students it could guide through Dutch higher education and into appropriate work.
One-time donation,Wildlife Justice Commission,2500000,2016,Global,"Start-up funding to set up the new Wildlife Justice Commission, which investigates transnational organised wildlife crime and pushes governments to prosecute."
One-time donation,Oceana,2250000,2016,The Netherlands (North Sea),Launch of Oceana's North Sea campaign for better protection and recovery of marine ecosystems in Dutch waters.
One-time donation,Circle Economy,1000000,2016,The Netherlands,Accelerating Circle Economy's work helping Dutch cities and businesses transition to a circular economy.
One-time donation,Free a Girl,1000000,2016,"India, Nepal, Bangladesh, Thailand, Netherlands, Brazil","Free a Girl's ""Lawyers for Lawyers / School for Justice"" programme to prosecute perpetrators of child sexual exploitation in India, Nepal, Bangladesh, Thailand, Brazil and the Netherlands."
One-time donation,HealthNet,1000000,2016,Global,HealthNet TPO's mental-health and trauma-care programmes in conflict-affected regions.
One-time donation,KidsRights,1000000,2016,Global,The International Children's Peace Prize and KidsRights' programmes defending children's rights worldwide.
One-time donation,Urgenda,1000000,2016,The Netherlands,"Accelerating Urgenda's ""Nederland 100% duurzaam"" action agenda and follow-up to the 2015 Climate Case ruling."
One-time donation,VluchtelingenWerk Nederland,950000,2016,The Netherlands,Additional refugee counselling in Dutch asylum centres and help with integration during the 2015/16 reception crisis.
One-time donation,Plastic Soup Foundation,600000,2016,Global,"Tackling marine plastic pollution, including the Beat the Microbead campaign against microplastics in cosmetics."
One-time donation,Stichting De Noordzee,500000,2016,The Netherlands (North Sea),"North Sea protection campaigns (sustainable fisheries, clean coasts, marine reserves)."
One-time donation,Stichting DierenLot,500000,2016,The Netherlands,Supporting local animal ambulances and small animal-welfare shelters across the Netherlands.
One-time donation,Stichting MAX Maakt Mogelijk,500000,2016,Moldova,"MAX Maakt Mogelijk's programmes supporting impoverished elderly people in Moldova (food parcels, home repairs, medical care)."
One-time donation,Instituut Clingendael,400000,2016,Middle East,Clingendael's Middle East research and dialogue programme.
Extra contribution to multi-year partners,Natuurmonumenten,7770000,2016,The Netherlands,"Making 40 Dutch nature reserves accessible to people with disabilities, and continued support for the Marker Wadden island-building project."
Extra contribution to multi-year partners,Stichting DOEN,5000000,2016,"Central & Eastern Europe, Latin America","DOEN's pioneer-financing programmes for green, social and creative front-runners in Central & Eastern Europe and Latin America."
Extra contribution to multi-year partners,War Child,2500000,2016,The Netherlands,"War Child's education programmes for children in conflict areas (top-up to the 2016 Dream Fund ""Can't Wait to Learn"" tablet-based education project)."
Extra contribution to multi-year partners,UNHCR,2384000,2016,Cameroon,UNHCR's emergency response for refugees from the Central African Republic sheltering in Cameroon.
Extra contribution to multi-year partners,ICCO,2120000,2016,Bangladesh,ICCO's livelihood and food-security programmes for smallholder farmers in Bangladesh.
Extra contribution to multi-year partners,PAX,2040000,2016,The Netherlands,PAX's peace and protection-of-civilians work.
Extra contribution to multi-year partners,Stichting Kinderpostzegels Nederland,1990000,2016,The Netherlands,Kinderpostzegels' programmes for vulnerable children in the Netherlands.
Extra contribution to multi-year partners,Liliane Fonds,1800000,2016,Tanzania,The Liliane Fonds' programme for children with disabilities in Tanzania.
Extra contribution to multi-year partners,LandschappenNL,1755000,2016,The Netherlands,"Co-funding the ""Red de Bij"" (Save the Bee) project with Natuur & Milieu to restore flowering landscapes for pollinators across the Netherlands."
Extra contribution to multi-year partners,Marine Stewardship Council,1755000,2016,Global (developing countries),Expanding MSC sustainable-fisheries certification to small-scale fisheries in developing countries.
Extra contribution to multi-year partners,Vogelbescherming Nederland,1700000,2016,The Netherlands,"Vogelbescherming's bird-protection programmes, including continuation of the ""Living on the Edge"" Sahel migratory-bird project."
Extra contribution to multi-year partners,vfonds,1500000,2016,The Netherlands,"vfonds' projects promoting peace, freedom and democracy in the Netherlands."
Extra contribution to multi-year partners,Right To Play,1475000,2016,"Rwanda, Netherlands",Right To Play's play-based education programmes in Rwanda and the Netherlands.
Extra contribution to multi-year partners,Natuur Milieu,1446000,2016,The Netherlands,"""Nederland Proeft"" (plant-based food campaign) and ""Project A15"" (first sustainable highway)."
Extra contribution to multi-year partners,Krajicek Foundation,1355000,2016,The Netherlands,Krajicek Playgrounds and sport-and-education programmes in disadvantaged Dutch neighbourhoods.
Extra contribution to multi-year partners,Stichting AAP,1335000,2016,Morocco,AAP's primate rescue and rehabilitation centre in Morocco (AAP Primadomus).
Extra contribution to multi-year partners,Not On Our Watch,900000,2016,Central & East Africa,"New multi-year partnership (500,000/year for 3 years) funding The Sentry network to expose and dismantle financial networks fuelling armed conflicts in Central and East Africa."
Extra contribution to multi-year partners,LINDA.foundation,426000,2016,The Netherlands,New multi-year partnership providing direct financial support to Dutch single-parent families living in poverty.
Dream Fund,Hivos & Greenpeace: Alle ogen op de Amazone,14825000,2016,"Brazil, Ecuador, Peru","Dream Fund project to protect 10 million hectares of threatened rainforest and indigenous territories in Brazil, Ecuador and Peru, using satellite monitoring, drones and indigenous-led surveillance technology."
Dream Fund,Leprastichting: Stop leprabesmetting!,9375000,2016,"India, Indonesia, Brazil","Dream Fund project (20172024) to break the chain of leprosy transmission in Brazil, India and Indonesia by preventively treating ~800,000 close contacts of patients with the PEP++ antibiotic regimen (rifampicin + clarithromycin)."
One-time donation,Artsen zonder Grenzen,4300000,2017,Global,"Extra emergency-aid deployment where humanitarian need is highest (Syria, Rohingya crisis, climate-related disasters)."
One-time donation,Het Nederlandse Rode Kruis,4300000,2017,Global,"Extra emergency-aid response to global humanitarian crises (Syria, Rohingya, climate-related emergencies)."
One-time donation,Stichting Vluchteling,4300000,2017,Global,"Extra emergency aid for the world's 65 million refugees, deployable in the most urgent crises."
One-time donation,APOPO,1500000,2017,Global,APOPO's HeroRATs that detect landmines and tuberculosis in mine-affected and high-TB-burden countries.
One-time donation,BRAC International,1500000,2017,Liberia,BRAC's Ultra-Poor Graduation programme for women in Liberia.
One-time donation,350.org / Fossielvrij NL,1000000,2017,Global,Fossielvrij NL's campaigns pushing Dutch pension funds and institutions to divest from fossil fuels.
One-time donation,Habitat for Humanity Nederland,1000000,2017,"Cambodja, Uganda",Habitat's safe-housing programmes in Cambodia and Uganda.
One-time donation,Institute for War & Peace Reporting (IWPR),1000000,2017,Global,IWPR's training and protection of local journalists in conflict and transition countries.
One-time donation,Missing Chapter Foundation,1000000,2017,The Netherlands,"Supporting Laurentien van Oranje's Missing Chapter, bringing children's perspectives into decision-making in Dutch organisations."
One-time donation,RNW Media,1000000,2017,Global,RNW Media's digital platforms enabling free expression and youth participation in restricted-media environments.
One-time donation,SPARK,1000000,2017,"Turkey, Jordan, Lebanon ","SPARK's higher-education scholarships and entrepreneurship support for Syrian refugees in Turkey, Jordan and Lebanon."
One-time donation,Wetlands International,1000000,2017,Global,Wetland conservation and climate-adaptation programmes.
Extra contribution to multi-year partners,Waddenvereniging,5114000,2017,The Netherlands,Definitive construction of the Vismigratierivier (fish-migration river) through the Afsluitdijk.
Extra contribution to multi-year partners,African Parks Network,2997000,2017,Tsjaad,Protection and management of Zakouma National Park in Chad.
Extra contribution to multi-year partners,ICCO,2834000,2017,Bangladesh,"""Birds, Bees and Business"", joint ICCO/Vogelbescherming project combining nature restoration and women's income in Burkina Faso."
Extra contribution to multi-year partners,Oxfam Novib,2500000,2017,Zimbabwe,Oxfam Novib's programmes in Zimbabwe.
Extra contribution to multi-year partners,Greenpeace,2409000,2017,Russia,Greenpeace's Arctic and Russian-forests campaigns.
Extra contribution to multi-year partners,Save the Children Nederland,2400000,2017,India,"""Surviving the Streets in India, The Invisibles"": registering and giving identity documents to 280,000 street children in India's 10 poorest cities."
Extra contribution to multi-year partners,SOS Kinderdorpen,2356000,2017,Global,SOS Children's Villages programmes for children who have lost or risk losing parental care.
Extra contribution to multi-year partners,Amnesty International,2318000,2017,Global,Amnesty's global human-rights protection and advocacy work.
Extra contribution to multi-year partners,ARK,2163000,2017,The Netherlands,ARK's rewilding and natural-process nature-development projects in the Netherlands.
Extra contribution to multi-year partners,Girls Not Brides,2000000,2017,Global,New multi-year partner contribution for the global Girls Not Brides partnership against child marriage.
Extra contribution to multi-year partners,Amref Flying Doctors,1995000,2017,Kenya,Amref's community-health and female-genital-cutting prevention programmes in Kenya.
Extra contribution to multi-year partners,YY Foundation,1860000,2017,Colombia,The Yunus & You (YY) Foundation's social-business and youth-employment programmes in Colombia.
Extra contribution to multi-year partners,IVN Natuureducatie,1850000,2017,The Netherlands,"Rollout of ""Tiny Forests"", 100 mini-forests in Dutch neighbourhoods and schools."
Extra contribution to multi-year partners,Scouting Nederland,1650000,2017,The Netherlands,Scouting Nederland's outdoor youth-development programmes.
Extra contribution to multi-year partners,vfonds,1650000,2017,The Netherlands,"vfonds' peace, freedom and democracy projects."
Extra contribution to multi-year partners,Defence for Children  ECPAT Nederland,1640000,2017,Global,The fight against child sexual exploitation and trafficking.
Extra contribution to multi-year partners,UNICEF,1469000,2017,"Bangui, Central African Republic","UNICEF's emergency response for children in Bangui, Central African Republic."
Extra contribution to multi-year partners,Commonland,1394000,2017,"Baviaanskloof, South Africa",Landscape restoration of the Baviaanskloof in South Africa using the 4 Returns model.
Extra contribution to multi-year partners,Wakker Dier,1375000,2017,The Netherlands,New multi-year partnership for Wakker Dier's campaigns against the bio-industry in the Netherlands.
Extra contribution to multi-year partners,Mama Cash,1253000,2017,Global,Mama Cash's global funding of feminist activist movements.
Extra contribution to multi-year partners,Aidsfonds,1051000,2017,Swaziland,Aidsfonds' HIV programmes in Swaziland (highest HIV-prevalence country).
Extra contribution to multi-year partners,Centrum tegen Kinderhandel en Mensenhandel,1000000,2017,The Netherlands,"New multi-year partnership funding the opening of a second CKM location in Rotterdam for victims of trafficking, abuse and exploitation."
Extra contribution to multi-year partners,Dr. Denis Mukwege Foundation,965000,2017,Congo,"The Mukwege Foundation's work with survivors of sexual violence in conflict, including Panzi Hospital in DRC."
Extra contribution to multi-year partners,Dokters van de Wereld,554000,2017,The Netherlands,Doctors of the World's healthcare for uninsured and undocumented people in the Netherlands.
Dream Fund,"Rutgers, Een veilige keuze voor vrouwen",11900000,2017,"Kenya, Ethiopia, West Africa","Dream Fund project ""She Makes Her Safe Choice"", making safe abortion methods and contraception available, and educating women in Kenya, Ethiopia and West Africa, to reduce the 22 million unsafe abortions a year worldwide."
One-time donation,Theirworld - Education in Emergencies,3150000,2018,Global,"Expanding education access for children in conflict areas (Theirworld's Education in Emergencies programme, presented by Gordon Brown)."
One-time donation,War Child,2500000,2018,"Sudan, Uganda, Lebanon, Jordan","War Child's psychosocial-support and education programmes for children affected by conflict in Sudan, Uganda, Lebanon and Jordan."
One-time donation,Greenpeace,2000000,2018,Brazil,Greenpeace's protection of the threatened Amazon region in Brazil.
One-time donation,RAVON en Good Fish Foundation,2000000,2018,The Netherlands,Making Dutch fish populations and aquaculture more sustainable and monitoring freshwater fish species.
One-time donation,Wereld Natuur Fonds,2000000,2018,Brazil,Protection of the threatened Amazon region in Brazil.
One-time donation,Amref Flying Doctors,1000000,2018,Africa,Amref's health programmes in Africa.
One-time donation,Forest Stewardship Council (FSC),1000000,2018,Global,Developing new technologies that strengthen FSC certification and make it accessible to forest owners of all sizes.
One-time donation,The Hague Institute for Innovation of Law (HiiL),1000000,2018,Global,"HiiL's ""Justice Innovation"" programme increasing access to justice for people in developing countries."
One-time donation,HIER klimaatbureau,1000000,2018,The Netherlands,Enabling HIER to scale up its grassroots support for Dutch citizens going gas-free and adopting community energy.
One-time donation,International Consortium of Investigative Journalists (ICIJ),1000000,2018,Global,"Expanding ICIJ's international network of investigative journalists (organisation behind the Panama Papers, Implant Files)."
One-time donation,Justice and Peace - Shelter City Initiative,1000000,2018,Global,Expanding the Shelter City network providing temporary safe haven for human-rights defenders at risk.
One-time donation,Netherlands Helsinki Committee,1000000,2018,"Poland, Russia, Turkey, Hungary","Rule-of-law and human-rights work in Poland, Russia, Turkey and Hungary."
One-time donation,Rare,1000000,2018,Indonesia,"Rare's behaviour-change ""Pride"" campaigns for community-led conservation in Indonesia."
One-time donation,Young Africa,1000000,2018,Southern Africa,Young Africa's vocational-skills training for disadvantaged youth in Southern Africa.
One-time donation,Bellingcat,500000,2018,Global,Setting up a Bellingcat open-source investigative-journalism training centre in the Netherlands.
Extra contribution to multi-year partners,Free Press Unlimited,3500000,2018,Global,"""A Safe World for the Truth"", new approach with CPJ, RSF, Bellingcat and Forensic Architecture to investigate violent crimes against journalists and end impunity."
Extra contribution to multi-year partners,Peace Parks Foundation,3000000,2018,"Angola, Botswana, Namibia, Zambia, Zimbabwe","Transfrontier conservation across Angola, Botswana, Namibia, Zambia and Zimbabwe (KAZA region)."
Extra contribution to multi-year partners,Terre des Hommes,2970000,2018,Global,"Follow-up to the ""Sweetie"" project against webcam sex with children."
Extra contribution to multi-year partners,Rocky Mountain Institute,2800000,2018,Nigeria and Ethiopia,Off-grid renewable-energy programmes accelerating clean energy access in Nigeria and Ethiopia.
Extra contribution to multi-year partners,IUCN NL,2400000,2018,South America,IUCN NL's work with local conservation groups against deforestation and illegal mining in South America.
Extra contribution to multi-year partners,Stichting Vluchteling,2400000,2018,The Netherlands,Emergency reception of refugees in the Netherlands.
Extra contribution to multi-year partners,Plan International Nederland,2160000,2018,Jordan,"""Talents Unlimited"", vocational-education project giving vulnerable Syrian refugee youth in Jordan a recognised diploma."
Extra contribution to multi-year partners,European Climate Foundation,2000000,2018,The Netherlands,ECF's strategic coordination of Dutch and European climate policy efforts.
Extra contribution to multi-year partners,IVN Natuureducatie,1950000,2018,The Netherlands,Nature-education programmes in Dutch schools and neighbourhoods.
Extra contribution to multi-year partners,Clinton Foundation and Rocky Mountain Institute,1850000,2018,Curaçao,Rebuilding Curaçao's energy system with renewables after Hurricane Irma's regional impact.
Extra contribution to multi-year partners,De Natuur en Milieufederaties,1650000,2018,The Netherlands,"Realising at least two ""Energietuinen"" (Energy Gardens) combining large-scale renewable-energy generation with nature and recreation."
Extra contribution to multi-year partners,Urgenda,1605000,2018,Global,"Supporting climate court cases worldwide, building on Urgenda's landmark Dutch climate ruling."
Extra contribution to multi-year partners,PAX,1569000,2018,Colombia,Peace-building work in Colombia following the FARC peace agreement.
Extra contribution to multi-year partners,CARE Nederland,1500000,2018,Jordan,CARE's support to Syrian refugees and host communities in Jordan.
Extra contribution to multi-year partners,Prins Claus Fonds,1305000,2018,Global,The Prince Claus Fund's Cultural Emergency Response and support to artists in conflict areas.
Extra contribution to multi-year partners,World Press Photo,1190000,2018,The Netherlands,The World Press Photo exhibition and visual-journalism programmes.
Extra contribution to multi-year partners,JINC,850000,2018,The Netherlands,"JINC's career-orientation and ""bliksemstages"" for disadvantaged Dutch youth."
Extra contribution to multi-year partners,Rafa Nadal Foundation,500000,2018,Spain,The Rafa Nadal Foundation's education-through-sport programmes in Spain.
Dream Fund,Vogelbescherming Nederland,15000000,2018,The Netherlands,"Dream Fund project ""Holwerd aan Zee"", creating a tidal lake behind the Frisian dike by opening it via a sluice, restoring bird habitat and salt-marsh nature (project ultimately discontinued in 2024)."
Dream Fund,Natuur Milieu,8500000,2018,The Netherlands,"Dream Fund project ""De Rijke Noordzee"", creating living reefs at the base of North Sea wind turbines to restore underwater biodiversity (with Stichting De Noordzee)."
One-time donation,Stichting DOEN - DOEN Participaties,4500000,2019,The Netherlands,"Capital injection for DOEN Participaties' impact-investment fund supporting pioneering green, social and creative enterprises."
One-time donation,Deltaplan Biodiversiteitsherstel,1500000,2019,The Netherlands,Launching citizen engagement and farmer/manager support for the Deltaplan Biodiversity Recovery in the Netherlands.
One-time donation,KidsRights,1500000,2019,Global,KidsRights' International Children's Peace Prize and global child-rights advocacy.
One-time donation,Leger des Heils,1500000,2019,The Netherlands,"The Salvation Army's ""buurthuiskamers"" (neighbourhood living rooms) tackling loneliness."
One-time donation,Thorn,1500000,2019,Global,Thorn's technology against online child sexual abuse material.
One-time donation,Amazon Frontlines,1000000,2019,Ecuador,Indigenous-led rainforest defence in Ecuador's Amazon.
One-time donation,Amref Flying Doctors,1000000,2019,"Africa, Kenya",Amref's community-health programmes in Kenya and Africa.
One-time donation,Cordaid,1000000,2019,Global,Cordaid Investment Management's impact-investing in fragile states.
One-time donation,Fonds Slachtofferhulp en Centrum Seksueel Geweld,1000000,2019,The Netherlands,Expanding the Centra Seksueel Geweld network providing acute care for victims of sexual violence in the Netherlands.
One-time donation,Free a Girl,1000000,2019,"Nepal, Brazil, India","Free a Girl's ""School for Justice"" training survivors as lawyers in Nepal, Brazil and India."
One-time donation,Healthy Entrepreneurs,1000000,2019,Africa,Healthy Entrepreneurs' network of community health workers selling essential medicines in rural Africa.
One-time donation,Hivos,1000000,2019,Global,"Hivos' programmes for women, LGBTI rights and freedom of expression."
One-time donation,ICCO en Solidaridad,1000000,2019,Global,"""PlusPlus"", new crowdfunding platform helping agri-entrepreneurs in developing countries (with Lendahand and Truvalu)."
One-time donation,Oceana,1000000,2019,The Netherlands (North Sea),Oceana's North Sea protection campaigns.
One-time donation,Oxfam Novib,1000000,2019,"Nigeria, Lebanon, Vietnam","Oxfam Novib's programmes in Nigeria, Lebanon and Vietnam."
One-time donation,Plastic Soup Foundation,1000000,2019,Global,"Tackling plastic pollution at source, including microplastics and clothing-fibre pollution."
One-time donation,Rewilding Europe,1000000,2019,Europe,Rewilding Europe's flagship rewilding landscapes across Europe.
One-time donation,SoortenNL,1000000,2019,The Netherlands,SoortenNL's biodiversity-protection programmes across Dutch flora and fauna species.
One-time donation,SPARK,1000000,2019,"Jordan, Lebanon, Turkey","Higher education and entrepreneurship for Syrian refugees in Jordan, Lebanon and Turkey."
One-time donation,Stichting leerKRACHT,1000000,2019,The Netherlands,Scaling leerKRACHT's continuous-improvement methodology in Dutch schools.
One-time donation,Trees for All,1000000,2019,"The Netherlands, Europe",Tree planting and forest restoration in the Netherlands and Europe.
One-time donation,Vogelbescherming Nederland,1000000,2019,The Netherlands,"""Schone Rivieren"" partnership cleaning plastic from Dutch rivers (with Stichting De Noordzee/IVN)."
One-time donation,100WEEKS,500000,2019,"Rwanda, Ghana, Uganda, Ivory Coast","100WEEKS' 100-week cash-transfer programme empowering women in Rwanda, Ghana, Uganda and Ivory Coast."
One-time donation,Sea Ranger Service,500000,2019,The Netherlands (North Sea),Launching the Sea Ranger Service training young people to monitor and protect Dutch North Sea marine areas.
One-time donation,Space Buzz Foundation,500000,2019,The Netherlands,"The Space Buzz mobile VR rocket touring Dutch schools teaching children the ""Overview Effect"" and Earth-stewardship."
One-time donation,Stichting Elisabeth Samson Huis,500000,2019,The Netherlands,The Elisabeth Samson Huis programmes empowering women of colour in the Netherlands.
One-time donation,Resto VanHarte,300000,2019,The Netherlands,Resto VanHarte's community dinners against loneliness and social exclusion.
Extra contribution to multi-year partners,The Sentry,6300000,2019,Africa,Co-financed with Postcode Loterij partners to expand The Sentry's financial-crime investigations against war profiteers in Africa.
Extra contribution to multi-year partners,IUCN NL,2825000,2019,The Netherlands,"""Onder het Maaiveld"", large-scale Dutch soil-biodiversity project with NIOO-KNAW, De Vlinderstichting and IVN."
Extra contribution to multi-year partners,Krajicek Foundation,2500000,2019,The Netherlands,New Krajicek Playgrounds in disadvantaged Dutch neighbourhoods.
Extra contribution to multi-year partners,YY Foundation,2490000,2019,Africa,The Yunus & You Foundation's youth-unemployment programmes in Uganda and Kenya.
Extra contribution to multi-year partners,LandschappenNL,2462500,2019,The Netherlands,"""Het Groene Strand"", restoring nature on Dutch beaches (with Duinbehoud, IVN and Anemoon)."
Extra contribution to multi-year partners,De Natuur en Milieufederaties,2250000,2019,The Netherlands,"""Plan Boom"", planting 10 million extra trees in the Netherlands."
Extra contribution to multi-year partners,Kinderfonds MAMAS,2200000,2019,South Africa,Kinderfonds MAMAS' township programmes supporting South African mothers and children.
Extra contribution to multi-year partners,Aidsfonds,2050000,2019,Russia,Aidsfonds' work with key populations in Russia.
Extra contribution to multi-year partners,Sea Shepherd,1980000,2019,Gabon,Sea Shepherd's anti-poaching operations in Gabonese waters.
Extra contribution to multi-year partners,Het Rode Kruis,1975000,2019,Ivory Coast,Red Cross emergency operations in Ivory Coast.
Extra contribution to multi-year partners,Natuurmonumenten,1796000,2019,The Netherlands,"Developing the Naardermeer wetland for re-establishment of the otter (""Otterparadijs"")."
Extra contribution to multi-year partners,Stichting de Vrolijkheid,1595000,2019,The Netherlands,De Vrolijkheid's creative activities for children in Dutch asylum centres.
Extra contribution to multi-year partners,Edukans,1550000,2019,Africa,Edukans' education programmes in Africa.
Extra contribution to multi-year partners,Free Press Unlimited,1485000,2019,Europe,Developing new projects on journalism innovation in Europe.
Extra contribution to multi-year partners,Johan Cruyff Foundation,1000000,2019,Greece,Cruyff Courts and sports programmes for refugee children in Greece.
Extra contribution to multi-year partners,Voedselbanken Nederland,510000,2019,The Netherlands,Supporting the growing demand at Dutch food banks.
Dream Fund,"Wereld Natuur Fonds, African Parks Network en Peace Parks Foundation",16900000,2019,Global,"Dream Fund project ""Onbegrensd door Afrika"", saving the Kavango Zambezi (KAZA) transfrontier conservation area across five Southern African countries through water-source protection and corridor connectivity."
Dream Fund,Amref Flying Doctors en PharmAccess,1750000,2019,Africa,Top-up to the 2015 Dream Fund project bringing health insurance and digital health services to rural African communities.
One-time donation,Het Rode Kruis,4893000,2020,"The Netherlands, Caribbean",COVID-19 emergency response by the Red Cross in the Netherlands and the Caribbean.
One-time donation,Artsen zonder Grenzen,4000000,2020,Global,MSF's global COVID-19 pandemic response.
One-time donation,Hivos,4000000,2020,Global,"Hivos' global programmes on open society, women's rights and climate justice."
One-time donation,SamenSpeelFonds,2000000,2020,The Netherlands,Launching the SamenSpeelFonds making Dutch playgrounds accessible for children with and without disabilities.
One-time donation,Fauna & Flora International,1500000,2020,South Sudan,FFI's conservation of the Sudd wetlands in South Sudan.
One-time donation,One Acre Fund,1500000,2020,"Malawi, Rwanda, Ethiopia","One Acre Fund's smallholder-farmer services in Malawi, Rwanda and Ethiopia."
One-time donation,RNW Media,1500000,2020,Global,RNW Media's digital platforms for youth voice in restricted-media countries.
One-time donation,Wetlands International,1500000,2020,"Asia, Africa, Latin America","Wetlands International's wetland-restoration programmes in Asia, Africa and Latin America."
One-time donation,"Theirworld, UNHCR & UNICEF",1350000,2020,Greece,Education and protection of refugee children on the Greek islands following the Moria fire.
One-time donation,Bellingcat,1000000,2020,Global,Expanding Bellingcat's open-source investigative work on war crimes and human-rights abuses.
One-time donation,Girls First Fund,1000000,2020,Global,The Girls First Fund's grassroots organisations ending child marriage.
One-time donation,Impunity Watch,1000000,2020,"Burundi, Syria, Guatemala","Impunity Watch's transitional-justice work in Burundi, Syria and Guatemala."
One-time donation,Landelijk Samenwerkingsverband Actieve Bewoners & Social Enterprise NL,1000000,2020,The Netherlands,Supporting community-led enterprises and active residents in Dutch neighbourhoods.
One-time donation,Nadia's Initiative,1000000,2020,Iraq,Nadia Murad's initiative for sustainable rebuilding of Yezidi homeland in Iraq and for survivors of sexual violence.
One-time donation,Schone Kleren Campagne,1000000,2020,Worldwide (40 countries),The Clean Clothes Campaign's worker-rights work in 40 garment-producing countries.
One-time donation,Stichting DierenLot,1000000,2020,The Netherlands,Animal ambulances and local animal-welfare shelters in the Netherlands.
One-time donation,Tropenbos International,1000000,2020,"Asia, Africa, Latin America","Tropenbos' research and policy work on tropical forests in Asia, Africa and Latin America."
One-time donation,Lighthouse Reports,500000,2020,Global,"Launching Lighthouse Reports' collaborative investigative journalism on migration, climate and accountability."
One-time donation,Stichting Het Vergeten Kind,500000,2020,The Netherlands,Het Vergeten Kind's programmes for Dutch children growing up in unsafe situations.
One-time donation,Voedselbanken Nederland,500000,2020,The Netherlands,Supporting food banks during COVID-19 demand surge.
One-time donation,Women Engage for a Common Future,500000,2020,Global,WECF's gender-just climate action with grassroots women worldwide.
One-time donation,World Fish Migration Foundation,500000,2020,Europe,Fish-migration river restoration projects across Europe.
One-time donation,Dokters van de Wereld,430000,2020,The Netherlands,Healthcare for uninsured and undocumented people in the Netherlands.
Extra contribution to multi-year partners,Amnesty International,2583000,2020,Global,Amnesty's global human-rights work including digital-rights and accountability programmes.
Extra contribution to multi-year partners,Stichting Kinderpostzegels Nederland,2195000,2020,The Netherlands,Kinderpostzegels' programmes for vulnerable children.
Extra contribution to multi-year partners,ARK Natuurontwikkeling,2185000,2020,The Netherlands,ARK's natural-process rewilding projects across the Netherlands.
Extra contribution to multi-year partners,Aflatoun International,1950000,2020,Global,Aflatoun's social and financial education for children worldwide.
Extra contribution to multi-year partners,Wildlife Justice Commission,1943000,2020,Global,Expanding WJC's transnational wildlife-crime investigations.
Extra contribution to multi-year partners,"Waddenvereniging, Stichting De Noordzee & De Natuur en Milieufederaties",1922000,2020,The Netherlands,"""Clean Up XL"", recovering 800 tons of remaining cargo waste from the MSC Zoe container disaster on the Wadden Sea."
Extra contribution to multi-year partners,Centrum tegen Kinderhandel en Mensenhandel,1195000,2020,The Netherlands,CKM's victim-support work and second-location operations in Rotterdam.
Dream Fund,KNCV Tuberculosefonds,11100000,2020,"The Netherlands, Tanzania, Vietnam, Kyrgyzstan","Dream Fund project ""Nooit meer een pandemie"", global rollout of an all-in-one portable diagnostic test for infectious diseases and resistances, starting in the Netherlands, Tanzania, Vietnam and Kyrgyzstan."
Dream Fund,Natuurmonumenten,5000000,2020,The Netherlands,"Dream Fund top-up launching the project ""Rotterdam de boer op!"", shortening the food chain in the Rotterdam region toward nature-inclusive agriculture."
One-time donation,International Fund for Animal Welfare (IFAW),1500000,2021,Global,IFAW's global animal-welfare and anti-poaching programmes.
One-time donation,Media Development Investment Fund (MDIF),1500000,2021,Global,MDIF's financing of independent media in restricted environments worldwide.
One-time donation,National Geographic Society,1500000,2021,Global,"The National Geographic Explorers programme funding scientists, educators and storytellers."
One-time donation,Triggerise,1500000,2021,Global,Triggerise's platform connecting young people to sexual- and reproductive-health services.
One-time donation,Bijzondere uitkeringen,1340744,2021,The Netherlands,Aggregate of smaller special distributions to various Dutch initiatives.
One-time donation,100WEEKS,1000000,2021,The Netherlands,"Expanding 100WEEKS' cash-transfer programme, including to Dutch single mothers in poverty."
One-time donation,ActionAid Nederland,1000000,2021,Global,ActionAid's women-led emergency response and climate-justice work.
One-time donation,Justdiggit,1000000,2021,Africa,"Justdiggit's landscape-cooling techniques (bunds, kisiki hai) regreening dry African landscapes."
One-time donation,Organized Crime and Corruption Reporting Project (OCCRP),1000000,2021,Global,OCCRP's cross-border investigative journalism on organised crime and corruption.
One-time donation,The Fund for Global Human Rights,1000000,2021,Global,FGHR's grassroots human-rights defender support.
One-time donation,ParkinsonNL,900000,2021,The Netherlands,ParkinsonNL's research and patient-support programmes.
One-time donation,Stichting ALS Nederland,900000,2021,The Netherlands,ALS Nederland's research into ALS treatments.
One-time donation,Stichting IPSO,800000,2021,The Netherlands,IPSO's network of psychosocial-care centres for people with cancer.
One-time donation,Stichting Refugee Company,750000,2021,The Netherlands,Refugee Company's work-integration programmes for refugees in the Netherlands.
One-time donation,Stichting De Schoolschrijver,650000,2021,The Netherlands,De Schoolschrijver's writers-in-residence programme in primary schools.
One-time donation,Jeugdeducatiefonds,588000,2021,The Netherlands,The Jeugdeducatiefonds' direct support to children in poverty via Dutch primary schools.
One-time donation,Break Free from Plastic (BFFP),500000,2021,Global,The global Break Free From Plastic movement against plastic pollution.
One-time donation,De Buzinezzclub,500000,2021,The Netherlands,The Buzinezzclub's training of young entrepreneurs from disadvantaged neighbourhoods.
One-time donation,Dona Daria,500000,2021,The Netherlands,Dona Daria's emancipation programmes for women in Rotterdam.
One-time donation,Global Fishing Watch,500000,2021,Global,Expanding Global Fishing Watch's satellite-based ocean transparency platform.
One-time donation,Kinderziekenhuizen van Oranje,500000,2021,The Netherlands,Supporting the seven Dutch children's hospitals' patient-experience improvements.
One-time donation,Movement on the Ground,500000,2021,Global,Movement on the Ground's reception-camp improvements for refugees in Greece.
One-time donation,Red Umbrella Fund,500000,2021,Global,The Red Umbrella Fund's support of sex-worker-led organisations worldwide.
One-time donation,Stichting Mainline,500000,2021,Global,Mainline's harm-reduction work with drug users.
One-time donation,Stichting Move,500000,2021,The Netherlands,Move's student-driven projects in disadvantaged Dutch neighbourhoods.
One-time donation,Stichting Thuisgekookt,500000,2021,The Netherlands,Thuisgekookt's volunteer home-cooking network for people unable to cook for themselves.
One-time donation,Wemos,500000,2021,Global,Wemos' advocacy on global access to medicines and health workforce.
One-time donation,Young Impact,500000,2021,The Netherlands,Young Impact's youth-led social-impact campaigns in Dutch schools.
One-time donation,Stichting Gilat,400000,2021,The Netherlands,Stichting Gilat's programmes supporting Jewish-community welfare.
Extra contribution to multi-year partners,Rode Kruis,3100000,2021,Global,Red Cross emergency response (COVID-19 follow-up and global crises).
Extra contribution to multi-year partners,UNICEF,2334000,2021,Global,UNICEF's COVID-19 child-protection and vaccination response.
Extra contribution to multi-year partners,Wilde Ganzen,2200000,2021,Global,Wilde Ganzen's matching-grant programme co-financing Dutch private development initiatives.
Extra contribution to multi-year partners,Wereld Natuur Fonds,2000000,2021,Global,Nature-based flood-protection in the Geul and Gulp valleys (Limburg) after the 2021 floods.
Extra contribution to multi-year partners,Cordaid,1800000,2021,Global,Cordaid's programmes in fragile states.
Extra contribution to multi-year partners,IVN Natuureducatie,1800000,2021,The Netherlands,IVN's nature-education programmes.
Extra contribution to multi-year partners,Vogelbescherming Nederland,1700000,2021,The Netherlands,"""PolderPracht Terschelling"", turning 40% of the Terschelling polder into meadow-bird-rich nature."
Extra contribution to multi-year partners,Both ENDS,1380000,2021,Global,Both ENDS' work with environmental groups in the Global South.
Extra contribution to multi-year partners,Johan Cruyff Foundation,1000000,2021,The Netherlands,Cruyff Courts and inclusive sports in the Netherlands.
Extra contribution to multi-year partners,KWF Kankerbestrijding,1000000,2021,The Netherlands,KWF's cancer research and patient support.
Extra contribution to multi-year partners,AAP,750000,2021,Global,AAP's primate and exotic-animal rescue.
Extra contribution to multi-year partners,Stichting MS Research,660000,2021,The Netherlands,MS Research's multiple-sclerosis research.
Extra contribution to multi-year partners,Dr. Denis Mukwege Foundation,500000,2021,The Netherlands,The Mukwege Foundation's work with survivors of conflict-related sexual violence.
Extra contribution to multi-year partners,Free Press Unlimited,500000,2021,Global,Press-freedom and journalist-safety programmes.
Extra contribution to multi-year partners,Maag Lever Darm Stichting,500000,2021,The Netherlands,The Dutch Gastrointestinal Foundation's patient programmes.
Extra contribution to multi-year partners,HandicapNL,483000,2021,The Netherlands,HandicapNL's programmes supporting people with disabilities.
Extra contribution to multi-year partners,Stichting Lezen en Schrijven,375000,2021,The Netherlands,Lezen en Schrijven's adult-literacy programmes.
Extra contribution to multi-year partners,EpilepsieNL,235000,2021,The Netherlands,EpilepsieNL's patient programmes and research.
Dream Fund,Solidaridad - Van Klimaatslachtoffers naar Klimaathelden,12731322,2021,"Uganda, Kenya, Colombia, Nicaragua","Dream Fund project enabling 100,000 small-scale farmers in Uganda, Kenya, Colombia and Nicaragua to adopt climate-smart agriculture and access carbon-credit income (2060% income increase) via the Acorn platform, with Fairfood and Cool Farm Alliance."
One-time donation,Bureau Burgerberaad,500000,2022,The Netherlands,Setting up Bureau Burgerberaad promoting citizens' assemblies on major societal issues in the Netherlands.
One-time donation,CNV Internationaal,1000000,2022,Global,CNV Internationaal's worker-rights and living-wage programmes in global supply chains.
One-time donation,Drugs for Neglected Diseases Initiative,1000000,2022,Global,DNDi's R&D for neglected tropical diseases.
One-time donation,Everyday Heroes,400000,2022,The Netherlands,Everyday Heroes' job-matching for people far from the Dutch labour market.
One-time donation,Freedom House,1000000,2022,Global,Freedom House's defence of democracy and human rights worldwide.
One-time donation,Healthy Entrepreneurs,1000000,2022,Global,Expanding the Healthy Entrepreneurs community-health network in rural Africa.
One-time donation,IDFA Bertha Fonds,500000,2022,The Netherlands,The IDFA Bertha Fund supporting documentary filmmakers from the Global South.
One-time donation,Internews,500000,2022,Global,Internews' support of local independent media worldwide.
One-time donation,Maggies Centers Nederland,1000000,2022,The Netherlands,Establishing the first Maggie's Centres in the Netherlands providing free psychosocial cancer support.
One-time donation,Nederlandse Helsinki Comité,500000,2022,Global,Rule-of-law and human-rights work in Central/Eastern Europe.
One-time donation,ProVeg Nederland,500000,2022,The Netherlands,ProVeg Nederland's plant-based food transition campaigns.
One-time donation,Ronald McDonald Kinderfonds,1000000,2022,The Netherlands,Ronald McDonald Houses near Dutch children's hospitals.
One-time donation,Room to Read,500000,2022,Indonesia,Room to Read's girls' education programme in Indonesia.
One-time donation,SoortenNL,800000,2022,The Netherlands,SoortenNL's biodiversity-protection work.
One-time donation,Space Buzz Foundation,500000,2022,The Netherlands,Continuing the Space Buzz VR rocket experience in Dutch schools.
One-time donation,Stichting ease,400000,2022,The Netherlands,ease's mental-health support for young people in the Netherlands.
One-time donation,Stichting Join Us,500000,2022,The Netherlands,Expanding Join Us's programmes against loneliness among Dutch young people.
One-time donation,Stichting KiKiD,400000,2022,The Netherlands,KiKiD's interactive sexuality education in Dutch secondary schools.
One-time donation,Stichting Onderzoek Multinationale Ondernemingen,1000000,2022,Global,SOMO's research into multinationals' impact on people and environment.
One-time donation,Trees for All,1000000,2022,The Netherlands,Tree planting and forest restoration in the Netherlands.
One-time donation,What Design Can Do,500000,2022,The Netherlands,What Design Can Do's design-led challenges on social issues.
Extra contribution to multi-year partners,Rutgers,4530000,2022,Global,Rutgers' sexual-and-reproductive-health programmes (continuation of Dream Fund work).
Extra contribution to multi-year partners,Oxfam Novib,4200000,2022,Global,Emergency aid for the Ukraine war response.
Extra contribution to multi-year partners,Free Press Unlimited,4000000,2022,Global,Press freedom and protection of journalists in conflict zones (Ukraine focus).
Extra contribution to multi-year partners,Wereld Natuur Fonds en Rode Kruis,3000000,2022,Global,Joint emergency relief and ecosystem recovery in the Ukraine war and other crises.
Extra contribution to multi-year partners,Amref Flying Doctors,2000000,2022,Ethiopia,Community-health response to drought in Ethiopia.
Extra contribution to multi-year partners,De Natuur en Milieufederaties,2000000,2022,The Netherlands,"""Burger-boercoalities"", accelerating the transition from intensive to nature-inclusive agriculture across the Netherlands."
Extra contribution to multi-year partners,VluchtelingenWerk Nederland,2000000,2022,The Netherlands,Additional support to refugees from Ukraine arriving in the Netherlands.
Extra contribution to multi-year partners,IUCN NL,1800000,2022,Global,IUCN NL's global biodiversity and land-rights work.
Extra contribution to multi-year partners,Longfonds,1500000,2022,The Netherlands,"PostCovid NL, supporting hundreds of thousands of Dutch people with long COVID."
Extra contribution to multi-year partners,LandschappenNL,1505000,2022,The Netherlands,Landscape-management projects across the 12 Dutch provincial landscape organisations.
Extra contribution to multi-year partners,Stichting het Gehandicapte Kind,1200000,2022,The Netherlands,"""Samen naar School"" inclusive-classroom programme for children with disabilities."
Extra contribution to multi-year partners,Cordaid,1400000,2022,Global,Cordaid's response in fragile states including Ukraine.
Extra contribution to multi-year partners,WOMEN Inc.,800000,2022,The Netherlands,WOMEN Inc.'s gender-equality programmes in the Netherlands.
Extra contribution to multi-year partners,LINDA.foundation,660000,2022,The Netherlands,LINDA.foundation's direct support of Dutch single-parent families in poverty.
Extra contribution to multi-year partners,World Food Programme,600000,2022,Global,"WFP's ""Ripple Effect"" project helping South Sudanese communities turn water hyacinth into fuel briquettes after flooding."
Extra contribution to multi-year partners,Vier het Leven,550000,2022,The Netherlands,Vier het Leven and Oud Geleerd Jong Gedaan reducing loneliness among older people through senior colleges.
Extra contribution to multi-year partners,Dokters van de Wereld,500000,2022,Global,Doctors of the World's care for uninsured people.
Extra contribution to multi-year partners,Hivos,500000,2022,Global,Hivos' programmes.
Extra contribution to multi-year partners,Jeugdfonds Sport & Cultuur,500000,2022,The Netherlands,Enabling more Dutch children in poverty to participate in sport and culture.
Extra contribution to multi-year partners,Leergeld Nederland,500000,2022,The Netherlands,"Leergeld's support of children from low-income Dutch families with school supplies, sports and culture."
Extra contribution to multi-year partners,PAX,500000,2022,Global,"PAX's peace work, including Ukraine."
Extra contribution to multi-year partners,Roger Federer Foundation,500000,2022,Global,The Roger Federer Foundation's early childhood education in southern Africa.
Extra contribution to multi-year partners,Save the Children,500000,2022,Global,Save the Children's life-saving humanitarian work in Yemen.
Extra contribution to multi-year partners,Bas van de Goor Foundation,370000,2022,The Netherlands,Bas van de Goor Foundation's sports activities for people with diabetes.
Extra contribution to multi-year partners,Krajicek Foundation,250000,2022,The Netherlands,New Krajicek Playgrounds.
Dream Fund,Commonland - Het Groene Goud,12000000,2022,Global,Dream Fund project funding a global Landscape Leadership Academy training regional teams in 100 landscapes to restore 10 million hectares using the 4 Returns model.
One-time donation,Sam voor alle kinderen,5000000,2023,The Netherlands,"The Sam& alliance (Leergeld, Jeugdfonds Sport & Cultuur, Stichting Jarige Job, Nationaal Fonds Kinderhulp) meeting rising demand from Dutch children in poverty."
One-time donation,Stichting Kansengelijkheid Burgerschapsonderwijs,3000000,2023,The Netherlands,Equal-opportunity citizenship education for Dutch students.
One-time donation,Leger des Heils,2500000,2023,The Netherlands,Salvation Army's shelter and outreach for homeless people and vulnerable Dutch citizens.
One-time donation,Wetlands International,1500000,2023,Global,Global wetland-restoration work.
One-time donation,Land Life Company/Borneo Orangutang Survival Fund,1100000,2023,Global,Large-scale reforestation in Borneo restoring orangutan habitat.
One-time donation,Front Line Defenders,1000000,2023,Global,Front Line Defenders' protection of human-rights defenders at risk worldwide.
One-time donation,International Budget Partnership,1000000,2023,Global,IBP's work on government budget transparency and citizen participation.
One-time donation,Lighthouse Reports,1000000,2023,The Netherlands,"Expanding Lighthouse Reports' collaborative investigations on migration, climate and human rights."
One-time donation,RNW Media,1000000,2023,Global,RNW Media's digital youth platforms in restricted-media countries.
One-time donation,Vereniging SchuldHulpMaatje Nederland,1000000,2023,The Netherlands,SchuldHulpMaatje's volunteer debt-coaching network in Dutch municipalities.
One-time donation,WeForest,1000000,2023,Global,WeForest's tropical-forest restoration projects.
One-time donation,Women Win,920000,2023,Global,Women Win's sport-based programmes for girls and young women worldwide.
One-time donation,Girls First Fund,910000,2023,Global,Girls First Fund's grassroots organisations ending child marriage.
One-time donation,Young Africa,807000,2023,Global,Young Africa's vocational-skills training for African youth.
One-time donation,Stichting Met je hart,800000,2023,The Netherlands,Met je hart's volunteer programmes for lonely Dutch elderly.
One-time donation,Crisis Action,750000,2023,Global,Crisis Action's coordination of NGO advocacy to prevent armed conflict.
One-time donation,Land van Ons,750000,2023,The Netherlands,Land van Ons' cooperative farmland purchases for biodiversity-friendly agriculture in the Netherlands.
One-time donation,MIND Us,750000,2023,The Netherlands,MIND Us' mental-health programmes for Dutch young people.
One-time donation,World Animal Protection,750000,2023,Global,World Animal Protection's campaigns against wildlife exploitation and farm-animal cruelty.
One-time donation,Forbidden Stories,600000,2023,Global,Forbidden Stories' continuation of murdered or threatened journalists' investigations.
One-time donation,Stichting Hartekind,510000,2023,The Netherlands,Hartekind's research and support for children with congenital heart defects.
One-time donation,Enviu,500000,2023,Global,"Enviu's creation of social enterprises in food, plastics, textiles and mobility."
One-time donation,FairWork,500000,2023,The Netherlands,FairWork's work against modern slavery and labour exploitation in the Netherlands.
One-time donation,Truth Tellers Summit,500000,2023,UK,The Truth Tellers Summit gathering investigative journalists and human-rights defenders (UK).
One-time donation,Stichting Artsen voor Kinderen,450000,2023,The Netherlands,Artsen voor Kinderen's support of chronically ill Dutch children.
One-time donation,Heifer Nederland,400000,2023,Global,Heifer's livestock and livelihood programmes for smallholder farmers.
One-time donation,KLABU,400000,2023,Global,KLABU's sports clubs in refugee camps and host communities.
One-time donation,Young Perspectives,400000,2023,The Netherlands and Europe,Young Perspectives' youth-leadership programmes in the Netherlands and Europe.
One-time donation,Trombosestichting Nederland,303000,2023,The Netherlands,Trombosestichting's research and patient support.
One-time donation,Nice Place Foundation,250000,2023,Kenya,The Nice Place Foundation's community projects in Kenya.
One-time donation,Dirk Kuyt Foundation,200000,2023,The Netherlands,The Dirk Kuyt Foundation's sports activities for Dutch children with disabilities.
Extra contribution to multi-year partners,ARK Rewilding Nederland,2100000,2023,The Netherlands and North Sea,"ARK's rewilding of Dutch nature areas (dunes, heath, agricultural areas) and North Sea biodiversity restoration."
Extra contribution to multi-year partners,Greenpeace,2233000,2023,Global,Greenpeace's global climate and biodiversity campaigns.
Extra contribution to multi-year partners,Postcode Loterij Buurtfonds,2481727,2023,The Netherlands,"The Buurtfonds' small-scale neighbourhood initiatives across the Netherlands (nearly 1,900 funded in 3 years)."
Extra contribution to multi-year partners,Rewilding Europe,2200000,2023,Global,Rewilding Europe's flagship rewilding landscapes.
Extra contribution to multi-year partners,Artsen zonder Grenzen,1908000,2023,Global,"MSF's emergency response (Turkey/Syria earthquakes, ongoing crises)."
Extra contribution to multi-year partners,UNHCR,1760000,2023,Global,UNHCR's refugee protection and education programmes.
Extra contribution to multi-year partners,IVN Natuureducatie,1990000,2023,The Netherlands,IVN's nature-education programmes including Tiny Forests.
Extra contribution to multi-year partners,Edukans,1990000,2023,Global,Edukans' education programmes for children in Africa.
Extra contribution to multi-year partners,Jantje Beton,1541000,2023,The Netherlands,Jantje Beton's outdoor play opportunities for Dutch children.
Extra contribution to multi-year partners,Simavi,1450000,2023,Global,"Simavi's water, sanitation and menstrual-health programmes."
Extra contribution to multi-year partners,Liliane Fonds,1279000,2023,Global,Liliane Fonds' support of children with disabilities in the Global South.
Extra contribution to multi-year partners,Metakids,1200000,2023,The Netherlands,Metakids' research into metabolic diseases in children.
Extra contribution to multi-year partners,The Sentry,1194000,2023,Global,The Sentry's investigations into war profiteers in African conflicts.
Extra contribution to multi-year partners,War Child,1000000,2023,Global,War Child's psychosocial support to children in conflict areas.
Extra contribution to multi-year partners,Aidsfonds,895000,2023,Global,Aidsfonds' global HIV programmes.
Extra contribution to multi-year partners,CARE Nederland,800000,2023,Global,CARE's humanitarian response (Turkey/Syria earthquake response).
Extra contribution to multi-year partners,Save the Children Nederland,800000,2023,Global,Save the Children's humanitarian work in Yemen.
Extra contribution to multi-year partners,De Vrolijkheid,630000,2023,The Netherlands,De Vrolijkheid's creative activities for children in Dutch asylum centres.
Extra contribution to multi-year partners,Vfonds,500000,2023,The Netherlands,vfonds' peace and freedom projects.
Extra contribution to multi-year partners,Het Vergeten Kind,450000,2023,The Netherlands,Het Vergeten Kind's programmes for Dutch children growing up in unsafe conditions.
Extra contribution to multi-year partners,Stichting Lezen en Schrijven,477000,2023,The Netherlands,Lezen en Schrijven's adult-literacy programmes.
Extra contribution to multi-year partners,HandicapNL,1603000,2023,The Netherlands,"HandicapNL's projects against loneliness among children with disabilities (preceding ""Iedereen een Maatje"")."
Extra contribution to multi-year partners,Dr. Denis Mukwege Foundation,400000,2023,Global,The Mukwege Foundation's support of survivors of conflict-related sexual violence.
Extra contribution to multi-year partners,Pink Ribbon,287000,2023,The Netherlands,Pink Ribbon's breast-cancer research and patient support.
Dream Fund,Natuurmonumenten - Rotterdam de Boer op!,10000000,2023,"The Netherlands, region around Rotterdam","Dream Fund top-up (8.8M to continue the 23-partner Rotterdam-region project for nature-inclusive agriculture and shorter food chains, 1.2M to apply lessons elsewhere in the Netherlands)."
Dream Fund,Natuur & Milieu en Stichting De Noordzee - De Rijke Noordzee,2600000,2023,The Netherlands (North Sea),Dream Fund top-up scaling the living-reefs-in-wind-parks project to new North Sea wind farms and securing the approach for future offshore wind expansion.
One-time donation,Ashoka,1500000,2024,The Netherlands,"Ashoka's network of social entrepreneurs (""Ashoka Fellows"") in the Netherlands."
One-time donation,ASKV Steunpunt Vluchtelingen,500000,2024,The Netherlands,ASKV's support for undocumented refugees in the Netherlands.
One-time donation,Buzz Women,600000,2024,The Netherlands,Buzz Women's training of grassroots women leaders.
One-time donation,Clooney Foundation for Justice,500000,2024,Global,The Clooney Foundation's TrialWatch monitoring of unfair trials worldwide.
One-time donation,Forward Inc,600000,2024,The Netherlands,Forward Inc's tech-talent training for refugees in the Netherlands.
One-time donation,Justice & Peace,1000000,2024,The Netherlands and other regions,Justice & Peace's Shelter City programme and human-rights defender protection.
One-time donation,Koninklijke Nederlandse Reddingsmaatschappij,1000000,2024,The Netherlands,KNRM's sea-rescue volunteers and equipment along the Dutch coast.
One-time donation,Landelijk Samenwerkingsverband Actieve bewoners (LSA),500000,2024,The Netherlands,LSA's support of resident-led neighbourhood initiatives.
One-time donation,Mondiaal FNV,960000,2024,Global,Mondiaal FNV's worker-rights and living-wage work in global supply chains.
One-time donation,National Geographic Society,1610000,2024,Global,"The National Geographic Explorers programme of scientists, educators and storytellers."
One-time donation,Progreso,530000,2024,Latin America and other regions,Progreso's financing of coffee and cocoa cooperatives in Latin America.
One-time donation,Stichting 3X3 Unites,500000,2024,The Netherlands,3X3 Unites' use of 3x3 basketball to empower youth in disadvantaged Dutch neighbourhoods.
One-time donation,Stichting Anne-Bo,400000,2024,The Netherlands,Anne-Bo's support of families with sick children.
One-time donation,Stichting Cliniclowns Nederland,1000000,2024,The Netherlands,CliniClowns' bedside visits to sick children and elderly with dementia.
One-time donation,Stichting Leeuw,600000,2024,The Netherlands and South Africa,Stichting Leeuw's rescue and rehabilitation of big cats in the Netherlands and South Africa.
One-time donation,Stichting Sheltersuit,450000,2024,The Netherlands and Europe,Sheltersuit's wearable-shelter coats for homeless people in the Netherlands and Europe.
One-time donation,Stichting Voedselbosbouw Nederland,450000,2024,The Netherlands,Voedselbosbouw Nederland's food-forest projects.
One-time donation,Wij.Land,500000,2024,The Netherlands,Wij.Land's nature-inclusive agriculture in Dutch peat-meadow areas.
One-time donation,Women Engage for a Common Future,500000,2024,Global,WECF's gender-just climate action with grassroots women.
Extra contribution to multi-year partners,De Natuur en Milieufederaties,2360000,2024,The Netherlands,"""Licht Uit, Meer Zien!"", reducing light pollution in the Veluwe, the Wadden area and National Park Nieuw Land by 50%, training 250 ""Nachtwachters""."
Extra contribution to multi-year partners,Dierenbescherming Nederland,2500000,2024,The Netherlands,Construction of a new modern animal-shelter centre in Tuitjenhorn replacing the outdated Alkmaar and IJmuiden facilities.
Extra contribution to multi-year partners,Dutch Caribbean Nature Alliance,1725000,2024,Dutch Caribbean,"A three-year programme (with WWF-NL) restoring mangroves, coral reefs, seagrass and coastal forests on the six Dutch Caribbean islands."
Extra contribution to multi-year partners,EpilepsieNL,770000,2024,The Netherlands,"Better detection of dangerous nighttime epileptic seizures for the 40,000 Dutch patients for whom medication is insufficient."
Extra contribution to multi-year partners,Fonds Slachtofferhulp,675000,2024,The Netherlands,Supporting victims of environmental crime with health problems from pollution and harmful substances.
Extra contribution to multi-year partners,Hulphond Nederland,935000,2024,The Netherlands,"""De Sociale Hulphond"", deploying specially trained dogs in hospitals and care homes to reduce anxiety and loneliness in sick children and elderly."
Extra contribution to multi-year partners,IMC Weekendschool,500000,2024,The Netherlands,"""Wijs in Media!"" reintroducing a documentary-making subject in ten Weekendscholen and ten primary schools to improve media literacy."
Extra contribution to multi-year partners,IUCN NL,4690000,2024,Global,"""Samen voor een Bloeiend Nederland"", a three-year coalition of 11 nature organisations (Groene 11) to implement the EU Nature Restoration Law in the Netherlands."
Extra contribution to multi-year partners,Kinderfonds MAMAS,1250000,2024,South Africa and other regions,"""Boys Matter"", five-year mentoring programme by ""PAPAS"" father figures for South African boys growing up without fathers."
Extra contribution to multi-year partners,LandschappenNL,1775000,2024,The Netherlands,"""Omhoog met het Veen"", restoring peat-moss cushions in Dutch low-lying peatlands to reduce CO2 emissions and restore biodiversity."
Extra contribution to multi-year partners,Leprastichting,1250000,2024,South and Southeast Asia,"Finalising and publishing the ""Stop leprabesmetting!"" Dream Fund project (Brazil, India, Indonesia, Nepal, Bangladesh) for global scale-up of preventive treatment."
Extra contribution to multi-year partners,Mama Cash,1500000,2024,Global,"Global support to feminist organisations fighting for the equal rights of women, girls and gender-diverse people."
Extra contribution to multi-year partners,Natuur & Milieu,1960000,2024,The Netherlands,"""Watergemeenschappen"", setting up local water communities to improve quality of Dutch rivers, ditches and lakes (currently only 1% meets EU standards)."
Extra contribution to multi-year partners,Prins Claus Fonds,1500000,2024,Global,"Establishing an Artist Emergency Fund for endangered artists worldwide with financial, legal, psychological and evacuation support."
Extra contribution to multi-year partners,Prinses Beatrix Spierfonds,1665000,2024,The Netherlands,"Making CAR-T cell therapy available to 10,000 Dutch patients with rare auto-immune diseases."
Extra contribution to multi-year partners,ReumaNederland,1537000,2024,The Netherlands,"Targeting juvenile rheumatism (affecting 1 in 1,000 children) to fight pain, fatigue and lasting damage."
Extra contribution to multi-year partners,Rutgers,750000,2024,Global,"Improving comprehensive sexuality education and online platforms for 200,000+ Dutch youth aged 1218 (with Aidsfonds and Soa Aids Nederland)."
Extra contribution to multi-year partners,Solidaridad,2167000,2024,Global,Development of a deforestation-mapping system enabling small-scale Global South farmers to comply with the 2026 EU deforestation-free import rules.
Extra contribution to multi-year partners,The Hunger Project,1600000,2024,Global,"""Water Winnen"", building 12 sand dams in Burkina Faso, Benin, Mozambique and Malawi to give 12,000 households direct access to clean water."
Extra contribution to multi-year partners,Vereniging Nederlands Cultuurlandschap,1150000,2024,The Netherlands,"Reversing the decline of toads, frogs and newts in the Netherlands, including in cities."
Extra contribution to multi-year partners,Vfonds,985000,2024,The Netherlands,"The new ""Vrijheidsmaaltijden"" national tradition on 5 May, marking 80 years of freedom (20242025)."
Extra contribution to multi-year partners,War Child,1895000,2024,Global,"Rollout of War Child's ""BeThere"" group programme for Syrian refugee parents in Lebanon and Jordan."
Dream Fund,Longfonds & MIND - Project Bruis,13000000,2024,The Netherlands,"Dream Fund project, 10-year community-health programme in Den Haag Zuidwest targeting 22,000 children and youth via 10 mobile ""BRUIS Pop-ups"" (green outdoor spaces) and online hub ""BRUIS Verder""."
Dream Fund,Nierstichting - Samen voor de nieuwe generatie nieren,10000000,2024,The Netherlands and France,"Dream Fund project funding the Kidnie research team's development of a gene therapy for cystinose, a severe paediatric kidney disease, within ten years."
One-time donation,Stichting Ambulance Wens,450000,2025,The Netherlands,Enabling Ambulance Wens to fulfil last wishes of terminally ill Dutch patients no longer able to travel themselves.
One-time donation,Stichting Armoedefonds,1000000,2025,The Netherlands,"Armoedefonds' direct material support (menstrual products, school supplies) to Dutch people in poverty."
One-time donation,COC Nederland,600000,2025,The Netherlands,"COC Nederland's safety and equal-rights work for LGBTI+ people, with extra focus on youth."
One-time donation,Cultural Emergency Response,750000,2025,Global,Cultural Emergency Response's rescue of cultural heritage in disasters and conflicts.
One-time donation,DollyWood Foundation,350000,2025,Global,Dolly Parton's Imagination Library distributing free books to children.
One-time donation,Emma at Work,600000,2025,The Netherlands,Emma at Work's job-matching for young people with chronic illness or disability.
One-time donation,European AI & Society Fund,1000000,2025,Europe,The European AI & Society Fund's grants to civil-society organisations working on AI accountability.
One-time donation,Front Line Defenders,1000000,2025,Global,Front Line Defenders' protection of human-rights defenders at risk worldwide.
One-time donation,Impact Hub Association,500000,2025,Global,The Impact Hub global network of social entrepreneurs.
One-time donation,International Fund for Animal Welfare,1000000,2025,Global,IFAW's global animal-welfare and habitat-protection work.
One-time donation,Stichting De Kindertelefoon,1500000,2025,The Netherlands,"De Kindertelefoon's ""In je bol"" campaign supporting Dutch children with worries and questions."
One-time donation,KLABU,600000,2025,The Netherlands,Expanding KLABU's sport clubs for displaced and refugee youth.
One-time donation,Stichting Long COVID,1000000,2025,The Netherlands,Stichting Long COVID's patient support and research into post-COVID symptoms.
One-time donation,Mensen met een Missie,1200000,2025,Global,"Mensen met een Missie's dialogue projects against exclusion, discrimination and violence worldwide and in the Netherlands."
One-time donation,NewBees,420000,2025,The Netherlands,"NewBees' guidance of newcomers in the Netherlands to work, study or volunteering."
One-time donation,Organized Crime and Corruption Reporting Project,600000,2025,Global,OCCRP's cross-border investigative journalism on organised crime and corruption.
One-time donation,Paris Peace Forum,300000,2025,Global,Supporting the Paris Peace Forum's annual multilateral governance gathering.
One-time donation,Prinses Máxima Centrum Foundation,1500000,2025,The Netherlands,The Prinses Máxima Centrum Foundation funding paediatric oncology at the Utrecht children's cancer centre.
One-time donation,Quiet Nederland,500000,2025,The Netherlands,Quiet Nederland's projects helping people in poverty participate in society.
One-time donation,Rainforest Foundation,775000,2025,Global (tropical forests),Supporting indigenous and local communities to protect their rainforest territories.
One-time donation,Re:wild,1000000,2025,,Re:wild's tropical-forest and biodiversity-protection programmes.
One-time donation,Refugee Company,750000,2025,The Netherlands,Refugee Company's work-integration programmes for refugees in the Netherlands.
One-time donation,Rewilding Argentina,1000000,2025,Argentina,"Rewilding Argentina's reintroduction of jaguars, giant otters and other keystone species in Iberá."
One-time donation,Sovon Vogelonderzoek Nederland,600000,2025,The Netherlands,Sovon's monitoring of bird populations in the Netherlands.
Extra contribution to multi-year partners,ARK Rewilding Nederland,2800000,2025,The Netherlands,"ARK's ongoing rewilding projects restoring natural processes across Dutch landscapes, including river deltas, coastal dunes and agricultural areas, with additional North Sea biodiversity work."
Extra contribution to multi-year partners,CARE Nederland,1200000,2025,Global,CARE's humanitarian and development programmes for women and girls in fragile and conflict-affected contexts.
Extra contribution to multi-year partners,Cordaid,1700000,2025,Global,"Cordaid's programmes in fragile states, focused on health, livelihoods and emergency response for the most vulnerable."
Extra contribution to multi-year partners,Dokters van de Wereld,750000,2025,Global,"Medical and social care for uninsured, undocumented and otherwise excluded people in the Netherlands."
Extra contribution to multi-year partners,Esther Vergeer Foundation,600000,2025,The Netherlands,"Programmes enabling young people with a disability to discover and develop their sporting talent through coaching, clinics and competitions."
Extra contribution to multi-year partners,Fonds Gehandicaptensport,500000,2025,The Netherlands,"Expanding sport access for people with disabilities in the Netherlands, including Special Olympics activities and inclusive sport programmes via Uniek Sporten."
Extra contribution to multi-year partners,Global Witness,1200000,2025,Global,"Investigations and campaigns exposing the links between natural resource exploitation, corruption and human rights abuses worldwide."
Extra contribution to multi-year partners,Hartstichting en Diabetes Fonds,4000000,2025,The Netherlands,"""CHECK+"" pop-up neighbourhood health check-points (blood pressure, cholesterol, glucose, BMI, waist) with referral to lifestyle support, focused on at-risk Dutch districts."
Extra contribution to multi-year partners,Hivos,1000000,2025,Global (Global South),"Hivos' programmes on open society, digital rights, women's empowerment and sustainable food systems in the Global South."
Extra contribution to multi-year partners,Human Right Watch,1700000,2025,Global,"""Eerlijke ketens, eerlijke kansen"", exposing harsh and unsafe labour conditions in Asian production chains supplying the European market."
Extra contribution to multi-year partners,IUCN NL,2000000,2025,Global (with focus on Global South),Global support of local conservation defenders protecting nature and endangered species in the Global South.
Extra contribution to multi-year partners,Jeugdeducatiefonds,1000000,2025,The Netherlands,"""Springplank naar succes"", direct help to children in poverty via Dutch primary schools (e.g. a bed, glasses, class outings)."
Extra contribution to multi-year partners,Johan Cruyff Foundation en Kraijeck Foundation,400000,2025,The Netherlands,Joint sports-and-play programmes of both foundations for children in disadvantaged Dutch neighbourhoods.
Extra contribution to multi-year partners,Kansfonds en Humanitas,1100000,2025,The Netherlands,"""Op tijd perspectief bieden"" -- early outreach to people with small debts before they become unmanageable."
Extra contribution to multi-year partners,Kinderpostzegels,2850000,2025,The Netherlands and Global South,"Programmes tackling child poverty, loneliness and unsafe home situations for children in the Netherlands, alongside support for children in the Global South."
Extra contribution to multi-year partners,KNCV Tuberculosefonds,2200000,2025,Global (high-burden TB countries),"Global tuberculosis control programmes, including diagnostics, treatment adherence and prevention in high-burden countries."
Extra contribution to multi-year partners,Liliane Fonds,1700000,2025,Global (Global South),"Support for children with disabilities and their families in the Global South, enabling participation in education and community life."
Extra contribution to multi-year partners,Nationaal Ouderenfonds,1000000,2025,The Netherlands,Combating loneliness among older people in the Netherlands through community connection and volunteer support programmes.
Extra contribution to multi-year partners,Nederlandse Vereniging voor Autisme,500000,2025,The Netherlands,"Advocacy, information and support for people with autism and their families across all life stages in the Netherlands."
Extra contribution to multi-year partners,Stichting De Noordzee,500000,2025,The Netherlands (North Sea),"North Sea protection campaigns, including sustainable fisheries, clean beaches and expanding marine reserves."
Extra contribution to multi-year partners,Oogfonds,1500000,2025,The Netherlands,Funding of patient-oriented and innovative scientific research into eye diseases to prevent blindness and severe visual impairment in the Netherlands.
Extra contribution to multi-year partners,Oxfam Novib,2500000,2025,Global,"Oxfam Novib's global programmes on inequality, women's rights and emergency response."
Extra contribution to multi-year partners,Oranje Fonds,1000000,2025,The Netherlands,Strengthening social cohesion in Dutch communities by funding volunteer-driven local initiatives that bring people together.
Extra contribution to multi-year partners,Peace Parks Foundation,1000000,2025,Southern Africa,"Transfrontier conservation across Southern Africa, including the KAZA and Greater Limpopo areas."
Extra contribution to multi-year partners,PharmAccess,650000,2025,Sub-Saharan Africa,Expanding access to quality healthcare for low-income populations in Sub-Saharan Africa through digital health tools and health insurance.
Extra contribution to multi-year partners,Plan International,2500000,2025,Global (Global South),"Programmes for girls' rights, education and protection from gender-based violence in the Global South."
Extra contribution to multi-year partners,WaterAid Nederland,1900000,2025,"Global (water, sanitation in Global South)","Clean water, sanitation and hygiene programmes for communities without access in the Global South."
Extra contribution to multi-year partners,Yvonne van Gennip Talent Fonds,500000,2025,The Netherlands,Financial support enabling Dutch children from low-income families with sports talent to continue developing and competing at a higher level.
Extra contribution to multi-year partners,Het Vergeten Kind,620000,2025,The Netherlands,Programmes for Dutch children growing up in unsafe or highly vulnerable home situations.
Extra contribution to multi-year partners,VluchtelingenWerk Nederland,3850000,2025,The Netherlands,"Legal aid, counselling and integration support for asylum seekers and refugees throughout the Dutch asylum process."
Extra contribution to multi-year partners,Wilde Ganzen,1500000,2025,Global (Global South),Matching-grant co-financing of Dutch private development initiatives and local partner organisations in the Global South.
Extra contribution to multi-year partners,Wildlife Justice Commission,1300000,2025,Global,"Transnational investigations into organised wildlife crime networks, pushing governments to prosecute."
Dream Fund,HandicapNL - MBO op maat,3500000,2025,The Netherlands,"Dream Fund project ""MBO op Maat"", developing new vocational-education learning tracks for young people with a mild intellectual disability, with schools, care organisations and employers."
Dream Fund,World Food Programme - Fortifying the Future,8250000,2025,Global (sorghum and maize-consuming countries),"Dream Fund project tackling ""hidden hunger"" by pioneering new fortification solutions for sorghum and wholegrain maize, staple foods for over one billion people worldwide."
`;


const PROJECT_COUNTRY_CSV = `Categorie,Organisatie,Bedrag,Jaar,Project Location
Eenmalige schenking,Stichting voor Vluchteling-Studenten UAF,4000000,2016,The Netherlands
Eenmalige schenking,Wildlife Justice Commission,2500000,2016,Global
Eenmalige schenking,Oceana,2250000,2016,The Netherlands (North Sea)
Eenmalige schenking,Circle Economy,1000000,2016,The Netherlands
Eenmalige schenking,Free a Girl,1000000,2016,"India, Nepal, Bangladesh, Thailand, Netherlands, Brazil"
Eenmalige schenking,HealthNet,1000000,2016,Global
Eenmalige schenking,KidsRights,1000000,2016,Global
Eenmalige schenking,Urgenda,1000000,2016,The Netherlands
Eenmalige schenking,VluchtelingenWerk Nederland,950000,2016,The Netherlands
Eenmalige schenking,Plastic Soup Foundation,600000,2016,Global
Eenmalige schenking,Stichting De Noordzee,500000,2016,The Netherlands (North Sea)
Eenmalige schenking,Stichting DierenLot,500000,2016,The Netherlands
Eenmalige schenking,Stichting MAX Maakt Mogelijk,500000,2016,Moldova
Eenmalige schenking,Instituut Clingendael,400000,2016,Middle East
SUBTOTAAL Eenmalige schenking,14 organisaties,17200000,2016,
Extra bijdrage aan meerjarige partners,Natuurmonumenten,7770000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,Stichting DOEN,5000000,2016,"Central & Eastern Europe, Latin America"
Extra bijdrage aan meerjarige partners,War Child,2500000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,UNHCR,2384000,2016,Cameroon
Extra bijdrage aan meerjarige partners,ICCO,2120000,2016,Bangladesh
Extra bijdrage aan meerjarige partners,PAX,2040000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,Stichting Kinderpostzegels Nederland,1990000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,Liliane Fonds,1800000,2016,Tanzania
Extra bijdrage aan meerjarige partners,LandschappenNL,1755000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,Marine Stewardship Council,1755000,2016,Global (developing countries)
Extra bijdrage aan meerjarige partners,Vogelbescherming Nederland,1700000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,vfonds,1500000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,Right To Play,1475000,2016,"Rwanda, Netherlands"
Extra bijdrage aan meerjarige partners,Natuur Milieu,1446000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,Krajicek Foundation,1355000,2016,The Netherlands
Extra bijdrage aan meerjarige partners,Stichting AAP,1335000,2016,Morocco
Extra bijdrage aan meerjarige partners,Not On Our Watch,900000,2016,Central & East Africa
Extra bijdrage aan meerjarige partners,LINDA.foundation,426000,2016,The Netherlands
SUBTOTAAL Extra bijdrage,18 organisaties,39251000,2016,
,,,,
Droomfonds,Hivos & Greenpeace  Alle ogen op de Amazone,14825000,2016,"Brazil, Ecuador, Peru"
Droomfonds,Leprastichting  Stop leprabesmetting!,9375000,2016,"India, Indonesia, Brazil"
SUBTOTAAL Droomfonds,2 organisaties,24200000,2016,
TOTAAL 2016,133 entries,323389617,2016,
Eenmalige schenking,Artsen zonder Grenzen,4300000,2017,Global
Eenmalige schenking,Het Nederlandse Rode Kruis,4300000,2017,Global
Eenmalige schenking,Stichting Vluchteling,4300000,2017,Global
Eenmalige schenking,APOPO,1500000,2017,Global
Eenmalige schenking,BRAC International,1500000,2017,Liberia
Eenmalige schenking,350.org / Fossielvrij NL,1000000,2017,Global
Eenmalige schenking,Habitat for Humanity Nederland,1000000,2017,"Cambodja, Uganda"
Eenmalige schenking,Institute for War & Peace Reporting (IWPR),1000000,2017,Global
Eenmalige schenking,Missing Chapter Foundation,1000000,2017,The Netherlands
Eenmalige schenking,RNW Media,1000000,2017,Global
Eenmalige schenking,SPARK,1000000,2017,"Turkey, Jordan, Lebanon "
Eenmalige schenking,Wetlands International,1000000,2017,Global
SUBTOTAAL Eenmalige schenking,12 organisaties,22900000,2017,
Extra bijdrage aan meerjarige partners,Waddenvereniging,5114000,2017,The Netherlands
Extra bijdrage aan meerjarige partners,African Parks Network,2997000,2017,Tsjaad
Extra bijdrage aan meerjarige partners,ICCO,2834000,2017,Bangladesh
Extra bijdrage aan meerjarige partners,Oxfam Novib,2500000,2017,Zimbabwe
Extra bijdrage aan meerjarige partners,Greenpeace,2409000,2017,Russia
Extra bijdrage aan meerjarige partners,Save the Children Nederland,2400000,2017,India
Extra bijdrage aan meerjarige partners,SOS Kinderdorpen,2356000,2017,Global
Extra bijdrage aan meerjarige partners,Amnesty International,2318000,2017,Global
Extra bijdrage aan meerjarige partners,ARK,2163000,2017,The Netherlands
Extra bijdrage aan meerjarige partners,Girls Not Brides,2000000,2017,Global
Extra bijdrage aan meerjarige partners,Amref Flying Doctors,1995000,2017,Kenya
Extra bijdrage aan meerjarige partners,YY Foundation,1860000,2017,Colombia
Extra bijdrage aan meerjarige partners,IVN Natuureducatie,1850000,2017,The Netherlands
Extra bijdrage aan meerjarige partners,Scouting Nederland,1650000,2017,The Netherlands
Extra bijdrage aan meerjarige partners,vfonds,1650000,2017,The Netherlands
Extra bijdrage aan meerjarige partners,Defence for Children  ECPAT Nederland,1640000,2017,Global
Extra bijdrage aan meerjarige partners,UNICEF,1469000,2017,"Bangui, Central African Republic"
Extra bijdrage aan meerjarige partners,Commonland,1394000,2017,"Baviaanskloof, South Africa"
Extra bijdrage aan meerjarige partners,Wakker Dier,1375000,2017,The Netherlands
Extra bijdrage aan meerjarige partners,Mama Cash,1253000,2017,Global
Extra bijdrage aan meerjarige partners,Aidsfonds,1051000,2017,Swaziland
Extra bijdrage aan meerjarige partners,Centrum tegen Kinderhandel en Mensenhandel,1000000,2017,The Netherlands
Extra bijdrage aan meerjarige partners,Dr. Denis Mukwege Foundation,965000,2017,Congo
Extra bijdrage aan meerjarige partners,Dokters van de Wereld,554000,2017,The Netherlands
SUBTOTAAL Extra bijdrage,24 organisaties,46797000,2017,
Droomfonds,Rutgers  Een veilige keuze voor vrouwen,11900000,2017,"Kenya, Ethiopia, West Africa"
SUBTOTAAL Droomfonds,1 organisatie,11900000,2017,
TOTAAL 2017,140 entries,329850890,2017,
Eenmalige schenking,Theirworld - Education in Emergencies,3150000,2018,Global
Eenmalige schenking,War Child,2500000,2018,"Sudan, Uganda, Lebanon, Jordan"
Eenmalige schenking,Greenpeace,2000000,2018,Brazil
Eenmalige schenking,RAVON en Good Fish Foundation,2000000,2018,The Netherlands
Eenmalige schenking,Wereld Natuur Fonds,2000000,2018,Brazil
Eenmalige schenking,Amref Flying Doctors,1000000,2018,Africa
Eenmalige schenking,Forest Stewardship Council (FSC),1000000,2018,Global
Eenmalige schenking,The Hague Institute for Innovation of Law (HiiL),1000000,2018,Global
Eenmalige schenking,HIER klimaatbureau,1000000,2018,The Netherlands
Eenmalige schenking,International Consortium of Investigative Journalists (ICIJ),1000000,2018,Global
Eenmalige schenking,Justice and Peace - Shelter City Initiative,1000000,2018,Global
Eenmalige schenking,Netherlands Helsinki Committee,1000000,2018,"Poland, Russia, Turkey, Hungary"
Eenmalige schenking,Rare,1000000,2018,Indonesia
Eenmalige schenking,Young Africa,1000000,2018,Southern Africa
Eenmalige schenking,Bellingcat,500000,2018,Global
SUBTOTAAL Eenmalige schenking,15 organisaties,20150000,2018,
Extra bijdrage aan meerjarige partners,Free Press Unlimited,3500000,2018,Global
Extra bijdrage aan meerjarige partners,Peace Parks Foundation,3000000,2018,"Angola, Botswana, Namibia, Zambia, Zimbabwe"
Extra bijdrage aan meerjarige partners,Terre des Hommes,2970000,2018,Global
Extra bijdrage aan meerjarige partners,Rocky Mountain Institute,2800000,2018,Nigeria and Ethiopia
Extra bijdrage aan meerjarige partners,IUCN NL,2400000,2018,South America
Extra bijdrage aan meerjarige partners,Stichting Vluchteling,2400000,2018,The Netherlands
Extra bijdrage aan meerjarige partners,Plan International Nederland,2160000,2018,Jordan
Extra bijdrage aan meerjarige partners,European Climate Foundation,2000000,2018,The Netherlands
Extra bijdrage aan meerjarige partners,IVN Natuureducatie,1950000,2018,The Netherlands
Extra bijdrage aan meerjarige partners,Clinton Foundation and Rocky Mountain Institute,1850000,2018,Curaçao
Extra bijdrage aan meerjarige partners,De Natuur en Milieufederaties,1650000,2018,The Netherlands
Extra bijdrage aan meerjarige partners,Urgenda,1605000,2018,Global
Extra bijdrage aan meerjarige partners,PAX,1569000,2018,Colombia
Extra bijdrage aan meerjarige partners,CARE Nederland,1500000,2018,Jordan
Extra bijdrage aan meerjarige partners,Prins Claus Fonds,1305000,2018,Global
Extra bijdrage aan meerjarige partners,World Press Photo,1190000,2018,The Netherlands
Extra bijdrage aan meerjarige partners,JINC,850000,2018,The Netherlands
Extra bijdrage aan meerjarige partners,Rafa Nadal Foundation,500000,2018,Spain
SUBTOTAAL Extra bijdrage,18 projecten,35199000,2018,
Droomfonds,Vogelbescherming Nederland,15000000,2018,The Netherlands
Droomfonds,Natuur Milieu,8500000,2018,The Netherlands
SUBTOTAAL Droomfonds,2 projecten,23500000,2018,
TOTAAL 2018,142 entries,344569159,2018,
Eenmalige schenking,Stichting DOEN - DOEN Participaties,4500000,2019,The Netherlands
Eenmalige schenking,Deltaplan Biodiversiteitsherstel,1500000,2019,The Netherlands
Eenmalige schenking,KidsRights,1500000,2019,Global
Eenmalige schenking,Leger des Heils,1500000,2019,The Netherlands
Eenmalige schenking,Thorn,1500000,2019,Global
Eenmalige schenking,Amazon Frontlines,1000000,2019,Ecuador
Eenmalige schenking,Amref Flying Doctors,1000000,2019,"Africa, Kenya"
Eenmalige schenking,Cordaid,1000000,2019,Global
Eenmalige schenking,Fonds Slachtofferhulp en Centrum Seksueel Geweld,1000000,2019,The Netherlands
Eenmalige schenking,Free a Girl,1000000,2019,"Nepal, Brazil, India"
Eenmalige schenking,Healthy Entrepreneurs,1000000,2019,Africa
Eenmalige schenking,Hivos,1000000,2019,Global
Eenmalige schenking,ICCO en Solidaridad,1000000,2019,Global
Eenmalige schenking,Oceana,1000000,2019,The Netherlands (North Sea)
Eenmalige schenking,Oxfam Novib,1000000,2019,"Nigeria, Lebanon, Vietnam"
Eenmalige schenking,Plastic Soup Foundation,1000000,2019,Global
Eenmalige schenking,Rewilding Europe,1000000,2019,Europe
Eenmalige schenking,SoortenNL,1000000,2019,The Netherlands
Eenmalige schenking,SPARK,1000000,2019,"Jordan, Lebanon, Turkey"
Eenmalige schenking,Stichting leerKRACHT,1000000,2019,The Netherlands
Eenmalige schenking,Trees for All,1000000,2019,"The Netherlands, Europe"
Eenmalige schenking,Vogelbescherming Nederland,1000000,2019,The Netherlands
Eenmalige schenking,100WEEKS,500000,2019,"Rwanda, Ghana, Uganda, Ivory Coast"
Eenmalige schenking,Sea Ranger Service,500000,2019,The Netherlands (North Sea)
Eenmalige schenking,Space Buzz Foundation,500000,2019,The Netherlands
Eenmalige schenking,Stichting Elisabeth Samson Huis,500000,2019,The Netherlands
Eenmalige schenking,Resto VanHarte,300000,2019,The Netherlands
SUBTOTAAL Eenmalige schenking,27 organisaties,29800000,2019,
Extra bijdrage aan meerjarige partners,The Sentry,6300000,2019,Africa
Extra bijdrage aan meerjarige partners,IUCN NL,2825000,2019,The Netherlands
Extra bijdrage aan meerjarige partners,Krajicek Foundation,2500000,2019,The Netherlands
Extra bijdrage aan meerjarige partners,YY Foundation,2490000,2019,Africa
Extra bijdrage aan meerjarige partners,LandschappenNL,2462500,2019,The Netherlands
Extra bijdrage aan meerjarige partners,De Natuur en Milieufederaties,2250000,2019,The Netherlands
Extra bijdrage aan meerjarige partners,Kinderfonds MAMAS,2200000,2019,South Africa
Extra bijdrage aan meerjarige partners,Aidsfonds,2050000,2019,Russia
Extra bijdrage aan meerjarige partners,Sea Shepherd,1980000,2019,Gabon
Extra bijdrage aan meerjarige partners,Het Rode Kruis,1975000,2019,Ivory Coast
Extra bijdrage aan meerjarige partners,Natuurmonumenten,1796000,2019,The Netherlands
Extra bijdrage aan meerjarige partners,Stichting de Vrolijkheid,1595000,2019,The Netherlands
Extra bijdrage aan meerjarige partners,Edukans,1550000,2019,Africa
Extra bijdrage aan meerjarige partners,Free Press Unlimited,1485000,2019,Europe
Extra bijdrage aan meerjarige partners,Johan Cruyff Foundation,1000000,2019,Greece
Extra bijdrage aan meerjarige partners,Voedselbanken Nederland,510000,2019,The Netherlands
SUBTOTAAL Extra bijdrage,16 projecten,34968500,2019,
Droomfonds,"Wereld Natuur Fonds, African Parks Network en Peace Parks Foundation",16900000,2019,Global
Droomfonds,Amref Flying Doctors en PharmAccess (extra bijdrage Droomfonds 2015),1750000,2019,Africa
SUBTOTAAL Droomfonds,2 projecten,18650000,2019,
TOTAAL 2019,150 entries,335169176,2019,
Eenmalige schenking,Het Rode Kruis,4893000,2020,"The Netherlands, Caribbean"
Eenmalige schenking,Artsen zonder Grenzen,4000000,2020,Global
Eenmalige schenking,Hivos,4000000,2020,Global
Eenmalige schenking,SamenSpeelFonds,2000000,2020,The Netherlands
Eenmalige schenking,Fauna & Flora International,1500000,2020,South Sudan
Eenmalige schenking,One Acre Fund,1500000,2020,"Malawi, Rwanda, Ethiopia"
Eenmalige schenking,RNW Media,1500000,2020,Global
Eenmalige schenking,Wetlands International,1500000,2020,"Asia, Africa, Latin America"
Eenmalige schenking,"Theirworld, UNHCR & UNICEF",1350000,2020,Greece
Eenmalige schenking,Bellingcat,1000000,2020,Global
Eenmalige schenking,Girls First Fund,1000000,2020,Global
Eenmalige schenking,Impunity Watch,1000000,2020,"Burundi, Syria, Guatemala"
Eenmalige schenking,Landelijk Samenwerkingsverband Actieve Bewoners & Social Enterprise NL,1000000,2020,The Netherlands
Eenmalige schenking,Nadia's Initiative,1000000,2020,Iraq
Eenmalige schenking,Schone Kleren Campagne,1000000,2020,Worldwide (40 countries)
Eenmalige schenking,Stichting DierenLot,1000000,2020,The Netherlands
Eenmalige schenking,Tropenbos International,1000000,2020,"Asia, Africa, Latin America"
Eenmalige schenking,Lighthouse Reports,500000,2020,Global
Eenmalige schenking,Stichting Het Vergeten Kind,500000,2020,The Netherlands
Eenmalige schenking,Voedselbanken Nederland,500000,2020,The Netherlands
Eenmalige schenking,Women Engage for a Common Future,500000,2020,Global
Eenmalige schenking,World Fish Migration Foundation,500000,2020,Europe
Eenmalige schenking,Dokters van de Wereld,430000,2020,The Netherlands
SUBTOTAAL Eenmalige schenking,23 organisaties,32173000,2020,
Extra bijdrage aan meerjarige partners,Amnesty International,2583000,2020,Global
Extra bijdrage aan meerjarige partners,Stichting Kinderpostzegels Nederland,2195000,2020,The Netherlands
Extra bijdrage aan meerjarige partners,ARK Natuurontwikkeling,2185000,2020,The Netherlands
Extra bijdrage aan meerjarige partners,Aflatoun International,1950000,2020,Global
Extra bijdrage aan meerjarige partners,Wildlife Justice Commission,1943000,2020,Global
Extra bijdrage aan meerjarige partners,"Waddenvereniging, Stichting De Noordzee & De Natuur en Milieufederaties",1922000,2020,The Netherlands
Extra bijdrage aan meerjarige partners,Centrum tegen Kinderhandel en Mensenhandel,1195000,2020,The Netherlands
SUBTOTAAL Extra bijdrage,7 projecten,13973000,2020,
Droomfonds,KNCV Tuberculosefonds,11100000,2020,"The Netherlands, Tanzania, Vietnam, Kyrgyzstan"
Droomfonds,Natuurmonumenten,5000000,2020,The Netherlands
SUBTOTAAL Droomfonds,2 projecten,16100000,2020,
TOTAAL 2020,137 entries,313996330,2020,
Eenmalige schenking,International Fund for Animal Welfare (IFAW),1500000,2021,Global
Eenmalige schenking,Media Development Investment Fund (MDIF),1500000,2021,Global
Eenmalige schenking,National Geographic Society,1500000,2021,Global
Eenmalige schenking,Triggerise,1500000,2021,Global
Eenmalige schenking,Bijzondere uitkeringen,1340744,2021,The Netherlands
Eenmalige schenking,100WEEKS,1000000,2021,The Netherlands
Eenmalige schenking,ActionAid Nederland,1000000,2021,Global
Eenmalige schenking,Justdiggit,1000000,2021,Africa
Eenmalige schenking,Organized Crime and Corruption Reporting Project (OCCRP),1000000,2021,Global
Eenmalige schenking,The Fund for Global Human Rights,1000000,2021,Global
Eenmalige schenking,ParkinsonNL,900000,2021,The Netherlands
Eenmalige schenking,Stichting ALS Nederland,900000,2021,The Netherlands
Eenmalige schenking,Stichting IPSO,800000,2021,The Netherlands
Eenmalige schenking,Stichting Refugee Company,750000,2021,The Netherlands
Eenmalige schenking,Stichting De Schoolschrijver,650000,2021,The Netherlands
Eenmalige schenking,Jeugdeducatiefonds,588000,2021,The Netherlands
Eenmalige schenking,Break Free from Plastic (BFFP),500000,2021,Global
Eenmalige schenking,De Buzinezzclub,500000,2021,The Netherlands
Eenmalige schenking,Dona Daria,500000,2021,The Netherlands
Eenmalige schenking,Global Fishing Watch,500000,2021,Global
Eenmalige schenking,Kinderziekenhuizen van Oranje,500000,2021,The Netherlands
Eenmalige schenking,Movement on the Ground,500000,2021,Global
Eenmalige schenking,Red Umbrella Fund,500000,2021,Global
Eenmalige schenking,Stichting Mainline,500000,2021,Global
Eenmalige schenking,Stichting Move,500000,2021,The Netherlands
Eenmalige schenking,Stichting Thuisgekookt,500000,2021,The Netherlands
Eenmalige schenking,Wemos,500000,2021,Global
Eenmalige schenking,Young Impact,500000,2021,The Netherlands
Eenmalige schenking,Stichting Gilat,400000,2021,The Netherlands
SUBTOTAAL Eenmalige schenking,29 organisaties,23328744,2021,
Extra bijdrage aan meerjarige partners,Rode Kruis,3100000,2021,Global
Extra bijdrage aan meerjarige partners,UNICEF,2334000,2021,Global
Extra bijdrage aan meerjarige partners,Wilde Ganzen,2200000,2021,Global
Extra bijdrage aan meerjarige partners,Wereld Natuur Fonds,2000000,2021,Global
Extra bijdrage aan meerjarige partners,Cordaid,1800000,2021,Global
Extra bijdrage aan meerjarige partners,IVN Natuureducatie,1800000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,Vogelbescherming Nederland,1700000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,Both ENDS,1380000,2021,Global
Extra bijdrage aan meerjarige partners,Johan Cruyff Foundation,1000000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,KWF Kankerbestrijding,1000000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,AAP,750000,2021,Global
Extra bijdrage aan meerjarige partners,Stichting MS Research,660000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,Dr. Denis Mukwege Foundation,500000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,Free Press Unlimited,500000,2021,Global
Extra bijdrage aan meerjarige partners,Maag Lever Darm Stichting,500000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,HandicapNL,483000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,Stichting Lezen en Schrijven,375000,2021,The Netherlands
Extra bijdrage aan meerjarige partners,EpilepsieNL,235000,2021,The Netherlands
SUBTOTAAL Extra bijdrage,18 projecten,22317000,2021,
Droomfonds,Solidaridad - Van Klimaatslachtoffers naar Klimaathelden,12731322,2021,"Uganda, Kenya, Colombia, Nicaragua"
SUBTOTAAL Droomfonds,1 project,12731322,2021,
TOTAAL 2021,196 entries,318352079,2021,
Eenmalige schenking,Bureau Burgerberaad,500000,2022,The Netherlands
Eenmalige schenking,CNV Internationaal,1000000,2022,Global
Eenmalige schenking,Drugs for Neglected Diseases Initiative,1000000,2022,Global
Eenmalige schenking,Everyday Heroes,400000,2022,The Netherlands
Eenmalige schenking,Freedom House,1000000,2022,Global
Eenmalige schenking,Healthy Entrepreneurs,1000000,2022,Global
Eenmalige schenking,IDFA Bertha Fonds,500000,2022,The Netherlands
Eenmalige schenking,Internews,500000,2022,Global
Eenmalige schenking,Maggies Centers Nederland,1000000,2022,The Netherlands
Eenmalige schenking,Nederlandse Helsinki Comité,500000,2022,Global
Eenmalige schenking,ProVeg Nederland,500000,2022,The Netherlands
Eenmalige schenking,Ronald McDonald Kinderfonds,1000000,2022,The Netherlands
Eenmalige schenking,Room to Read,500000,2022,Indonesia
Eenmalige schenking,SoortenNL,800000,2022,The Netherlands
Eenmalige schenking,Space Buzz Foundation,500000,2022,The Netherlands
Eenmalige schenking,Stichting ease,400000,2022,The Netherlands
Eenmalige schenking,Stichting Join Us,500000,2022,The Netherlands
Eenmalige schenking,Stichting KiKiD,400000,2022,The Netherlands
Eenmalige schenking,Stichting Onderzoek Multinationale Ondernemingen,1000000,2022,Global
Eenmalige schenking,Trees for All,1000000,2022,The Netherlands
Eenmalige schenking,What Design Can Do,500000,2022,The Netherlands
SUBTOTAAL Eenmalige schenking,21 organisaties,14500000,2022,
Extra bijdrage aan meerjarige partners,Rutgers,4530000,2022,Global
Extra bijdrage aan meerjarige partners,Oxfam Novib,4200000,2022,Global
Extra bijdrage aan meerjarige partners,Free Press Unlimited,4000000,2022,Global
Extra bijdrage aan meerjarige partners,Wereld Natuur Fonds en Rode Kruis,3000000,2022,Global
Extra bijdrage aan meerjarige partners,Amref Flying Doctors,2000000,2022,Ethiopia
Extra bijdrage aan meerjarige partners,De Natuur en Milieufederaties,2000000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,VluchtelingenWerk Nederland,2000000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,IUCN NL,1800000,2022,Global
Extra bijdrage aan meerjarige partners,Longfonds,1500000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,LandschappenNL,1505000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,Stichting het Gehandicapte Kind,1200000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,Cordaid,1400000,2022,Global
Extra bijdrage aan meerjarige partners,WOMEN Inc.,800000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,LINDA.foundation,660000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,World Food Programme,600000,2022,Global
Extra bijdrage aan meerjarige partners,Vier het Leven,550000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,Dokters van de Wereld,500000,2022,Global
Extra bijdrage aan meerjarige partners,Hivos,500000,2022,Global
Extra bijdrage aan meerjarige partners,Jeugdfonds Sport & Cultuur,500000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,Leergeld Nederland,500000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,PAX,500000,2022,Global
Extra bijdrage aan meerjarige partners,Roger Federer Foundation,500000,2022,Global
Extra bijdrage aan meerjarige partners,Save the Children,500000,2022,Global
Extra bijdrage aan meerjarige partners,Bas van de Goor Foundation,370000,2022,The Netherlands
Extra bijdrage aan meerjarige partners,Krajicek Foundation,250000,2022,The Netherlands
SUBTOTAAL Extra bijdrage,25 projecten,35865000,2022,
Droomfonds,Commonland - Het Groene Goud,12000000,2022,Global
SUBTOTAAL Droomfonds,1 project,12000000,2022,
TOTAAL 2022,193 entries,337890099,2022,
Eenmalige schenking,Sam voor alle kinderen,5000000,2023,The Netherlands
Eenmalige schenking,Stichting Kansengelijkheid Burgerschapsonderwijs,3000000,2023,The Netherlands
Eenmalige schenking,Leger des Heils,2500000,2023,The Netherlands
Eenmalige schenking,Wetlands International,1500000,2023,Global
Eenmalige schenking,Land Life Company/Borneo Orangutang Survival Fund,1100000,2023,Global
Eenmalige schenking,Front Line Defenders,1000000,2023,Global
Eenmalige schenking,International Budget Partnership,1000000,2023,Global
Eenmalige schenking,Lighthouse Reports,1000000,2023,The Netherlands
Eenmalige schenking,RNW Media,1000000,2023,Global
Eenmalige schenking,Vereniging SchuldHulpMaatje Nederland,1000000,2023,The Netherlands
Eenmalige schenking,WeForest,1000000,2023,Global
Eenmalige schenking,Women Win,920000,2023,Global
Eenmalige schenking,Girls First Fund,910000,2023,Global
Eenmalige schenking,Young Africa,807000,2023,Global
Eenmalige schenking,Stichting Met je hart,800000,2023,The Netherlands
Eenmalige schenking,Crisis Action,750000,2023,Global
Eenmalige schenking,Land van Ons,750000,2023,The Netherlands
Eenmalige schenking,MIND Us,750000,2023,The Netherlands
Eenmalige schenking,World Animal Protection,750000,2023,Global
Eenmalige schenking,Forbidden Stories,600000,2023,Global
Eenmalige schenking,Stichting Hartekind,510000,2023,The Netherlands
Eenmalige schenking,Enviu,500000,2023,Global
Eenmalige schenking,FairWork,500000,2023,The Netherlands
Eenmalige schenking,Truth Tellers Summit,500000,2023,UK
Eenmalige schenking,Stichting Artsen voor Kinderen,450000,2023,The Netherlands
Eenmalige schenking,Heifer Nederland,400000,2023,Global
Eenmalige schenking,KLABU,400000,2023,Global
Eenmalige schenking,Young Perspectives,400000,2023,The Netherlands and Europe
Eenmalige schenking,Trombosestichting Nederland,303000,2023,The Netherlands
Eenmalige schenking,Nice Place Foundation,250000,2023,Kenya
Eenmalige schenking,Dirk Kuyt Foundation,200000,2023,The Netherlands
SUBTOTAAL Eenmalige schenking,31 organisaties,31620000,2023,
Extra bijdrage aan meerjarige partners,ARK Rewilding Nederland,2100000,2023,The Netherlands and North Sea
Extra bijdrage aan meerjarige partners,Greenpeace,2233000,2023,Global
Extra bijdrage aan meerjarige partners,Postcode Loterij Buurtfonds,2481727,2023,The Netherlands
Extra bijdrage aan meerjarige partners,Rewilding Europe,2200000,2023,Global
Extra bijdrage aan meerjarige partners,Artsen zonder Grenzen,1908000,2023,Global
Extra bijdrage aan meerjarige partners,UNHCR,1760000,2023,Global
Extra bijdrage aan meerjarige partners,IVN Natuureducatie,1990000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,Edukans,1990000,2023,Global
Extra bijdrage aan meerjarige partners,Jantje Beton,1541000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,Simavi,1450000,2023,Global
Extra bijdrage aan meerjarige partners,Liliane Fonds,1279000,2023,Global
Extra bijdrage aan meerjarige partners,Metakids,1200000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,The Sentry,1194000,2023,Global
Extra bijdrage aan meerjarige partners,War Child,1000000,2023,Global
Extra bijdrage aan meerjarige partners,Aidsfonds,895000,2023,Global
Extra bijdrage aan meerjarige partners,CARE Nederland,800000,2023,Global
Extra bijdrage aan meerjarige partners,Save the Children Nederland,800000,2023,Global
Extra bijdrage aan meerjarige partners,De Vrolijkheid,630000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,Vfonds,500000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,Het Vergeten Kind,450000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,Stichting Lezen en Schrijven,477000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,HandicapNL,1603000,2023,The Netherlands
Extra bijdrage aan meerjarige partners,Dr. Denis Mukwege Foundation,400000,2023,Global
Extra bijdrage aan meerjarige partners,Pink Ribbon,287000,2023,The Netherlands
SUBTOTAAL Extra bijdrage,24 projecten,33697727,2023,
Droomfonds,Natuurmonumenten - Rotterdam de Boer op!,10000000,2023,"The Netherlands, region around Rotterdam"
Droomfonds,Natuur & Milieu en Stichting De Noordzee - De Rijke Noordzee,2600000,2023,The Netherlands (North Sea)
SUBTOTAAL Droomfonds,2 projecten,12600000,2023,
TOTAAL 2023,204 entries,349231938,2023,
SUBTOTAAL,Meerjarige partner 147 organisaties,290156299,2024,
Eenmalige schenking,Ashoka,1500000,2024,The Netherlands
Eenmalige schenking,ASKV Steunpunt Vluchtelingen,500000,2024,The Netherlands
Eenmalige schenking,Buzz Women,600000,2024,The Netherlands
Eenmalige schenking,Clooney Foundation for Justice,500000,2024,Global
Eenmalige schenking,Forward Inc,600000,2024,The Netherlands
Eenmalige schenking,Justice & Peace,1000000,2024,The Netherlands and other regions
Eenmalige schenking,Koninklijke Nederlandse Reddingsmaatschappij,1000000,2024,The Netherlands
Eenmalige schenking,Landelijk Samenwerkingsverband Actieve bewoners (LSA),500000,2024,The Netherlands
Eenmalige schenking,Mondiaal FNV,960000,2024,Global
Eenmalige schenking,National Geographic Society,1610000,2024,Global
Eenmalige schenking,Progreso,530000,2024,Latin America and other regions
Eenmalige schenking,Stichting 3X3 Unites,500000,2024,The Netherlands
Eenmalige schenking,Stichting Anne-Bo,400000,2024,The Netherlands
Eenmalige schenking,Stichting Cliniclowns Nederland,1000000,2024,The Netherlands
Eenmalige schenking,Stichting Leeuw,600000,2024,The Netherlands and South Africa
Eenmalige schenking,Stichting Sheltersuit,450000,2024,The Netherlands and Europe
Eenmalige schenking,Stichting Voedselbosbouw Nederland,450000,2024,The Netherlands
Eenmalige schenking,Wij.Land,500000,2024,The Netherlands
Eenmalige schenking,Women Engage for a Common Future,500000,2024,Global
SUBTOTAAL,Eenmalige schenking 19 organisaties,13700000,2024,
Extra bijdrage aan meerjarige partners,De Natuur en Milieufederaties,2360000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Dierenbescherming Nederland,2500000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Dutch Caribbean Nature Alliance,1725000,2024,Dutch Caribbean
Extra bijdrage aan meerjarige partners,EpilepsieNL,770000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Fonds Slachtofferhulp,675000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Hulphond Nederland,935000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,IMC Weekendschool,500000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,IUCN NL,4690000,2024,Global
Extra bijdrage aan meerjarige partners,Kinderfonds MAMAS,1250000,2024,South Africa and other regions
Extra bijdrage aan meerjarige partners,LandschappenNL,1775000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Leprastichting,1250000,2024,South and Southeast Asia
Extra bijdrage aan meerjarige partners,Mama Cash,1500000,2024,Global
Extra bijdrage aan meerjarige partners,Natuur & Milieu,1960000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Prins Claus Fonds,1500000,2024,Global
Extra bijdrage aan meerjarige partners,Prinses Beatrix Spierfonds,1665000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,ReumaNederland,1537000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Rutgers,750000,2024,Global
Extra bijdrage aan meerjarige partners,Solidaridad,2167000,2024,Global
Extra bijdrage aan meerjarige partners,The Hunger Project,1600000,2024,Global
Extra bijdrage aan meerjarige partners,Vereniging Nederlands Cultuurlandschap,1150000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,Vfonds,985000,2024,The Netherlands
Extra bijdrage aan meerjarige partners,War Child,1895000,2024,Global
SUBTOTAAL,Extra bijdrage 22 projecten,35139000,2024,
Droomfonds,Longfonds & MIND - Project Bruis,13000000,2024,The Netherlands
Droomfonds,Nierstichting - Samen voor de nieuwe generatie nieren,10000000,2024,The Netherlands and France
SUBTOTAAL,Droomfonds 2 projecten,23000000,2024,
TOTAAL 2024,190 entries (berekend),361995299,2024,
`;


// --- CSV parser (handles quoted fields with commas) ---
function parseCSV(text) {
  const rows = [];
  let row = [], field = '', inQuotes = false;
  for (let i = 0; i < text.length; i++) {
    const c = text[i];
    if (inQuotes) {
      if (c === '"') {
        if (text[i+1] === '"') { field += '"'; i++; }
        else { inQuotes = false; }
      } else field += c;
    } else {
      if (c === '"') inQuotes = true;
      else if (c === ',') { row.push(field); field = ''; }
      else if (c === '\n') { row.push(field); rows.push(row); row = []; field = ''; }
      else if (c === '\r') { /* skip */ }
      else field += c;
    }
  }
  if (field.length || row.length) { row.push(field); rows.push(row); }
  return rows;
}

// --- Category translation ---
const CAT_MAP = {
  'Meerjarige partner': 'Multi-year partner',
  'Eenmalige schenking': 'One-time donation',
  'Extra bijdrage aan meerjarige partners': 'Extra contribution to multi-year partners',
  'Droomfonds': 'Dream Fund',
  'Multi-year partner': 'Multi-year partner',
  'One-time donation': 'One-time donation',
  'Extra contribution to multi-year partners': 'Extra contribution to multi-year partners',
  'Dream Fund': 'Dream Fund'
};
const CAT_SHORT = {
  'Multi-year partner': 'Multi-year partner',
  'One-time donation': 'One-time donation',
  'Extra contribution to multi-year partners': 'Extra contribution',
  'Dream Fund': 'Dream Fund'
};
const CAT_ORDER = ['Multi-year partner','One-time donation','Extra contribution to multi-year partners','Dream Fund'];

// --- Parse rows ---
const rawRows = parseCSV(CSV_DATA);
const dataRows = [];          // actual donation entries
const subtotals = {};         // { year: { category: amount } }
const totals = {};            // { year: amount }
const anomalies = [];

for (let i = 0; i < rawRows.length; i++) {
  const r = rawRows[i];
  if (!r || r.length < 4) continue;
  const [cat, org, amt, yr] = [r[0] || '', r[1] || '', r[2] || '', r[3] || ''];
  const catT = cat.trim(), orgT = org.trim(), amtT = amt.trim(), yrT = yr.trim();

  // header
  if (catT === 'Categorie') continue;
  // blank / spacer rows
  if (!catT && !orgT && !amtT && !yrT) continue;
  if (!catT.replace(/\s/g,'') && !orgT.replace(/\s/g,'')) continue;

  // TOTAAL rows
  if (/^TOTAAL/i.test(catT)) {
    const y = parseInt(yrT, 10);
    const n = parseInt(amtT, 10);
    if (!isNaN(y) && !isNaN(n)) totals[y] = n;
    continue;
  }
  // SUBTOTAAL rows (2016-2023 layout)
  if (/^SUBTOTAAL\s+/i.test(catT)) {
    const y = parseInt(yrT, 10);
    const n = parseInt(amtT, 10);
    let which = null;
    if (/Meerjarige|Multi-year/i.test(catT)) which = 'Multi-year partner';
    else if (/Eenmalige|One-time/i.test(catT)) which = 'One-time donation';
    else if (/Extra/i.test(catT)) which = 'Extra contribution to multi-year partners';
    else if (/Droomfonds|Dream/i.test(catT)) which = 'Dream Fund';
    if (which && !isNaN(y) && !isNaN(n)) {
      subtotals[y] = subtotals[y] || {};
      subtotals[y][which] = n;
    }
    continue;
  }
  // SUBTOTAAL rows (2024 layout: "SUBTOTAAL","Meerjarige partner 147 organisaties",amount,2024)
  if (catT === 'SUBTOTAAL') {
    const y = parseInt(yrT, 10);
    const n = parseInt(amtT, 10);
    let which = null;
    if (/Meerjarige|Multi-year/i.test(orgT)) which = 'Multi-year partner';
    else if (/Eenmalige|One-time/i.test(orgT)) which = 'One-time donation';
    else if (/Extra/i.test(orgT)) which = 'Extra contribution to multi-year partners';
    else if (/Droomfonds|Dream/i.test(orgT)) which = 'Dream Fund';
    if (which && !isNaN(y) && !isNaN(n)) {
      subtotals[y] = subtotals[y] || {};
      subtotals[y][which] = n;
    }
    continue;
  }

  // Regular donation row
  const mapped = CAT_MAP[catT];
  if (!mapped) {
    anomalies.push(`Row ${i+1}: unknown category "${catT}" — skipped.`);
    continue;
  }
  const amount = parseInt(amtT, 10);
  const year = parseInt(yrT, 10);
  if (isNaN(amount)) {
    anomalies.push(`Row ${i+1}: missing/invalid amount for "${orgT}" — skipped.`);
    continue;
  }
  if (isNaN(year)) {
    anomalies.push(`Row ${i+1}: missing/invalid year for "${orgT}" — skipped.`);
    continue;
  }
  if (!orgT) {
    anomalies.push(`Row ${i+1}: missing organisation name — skipped.`);
    continue;
  }
  dataRows.push({ organisation: orgT, category: mapped, amount, year });
}

// --- Flag multi-org bundles (contains comma/& between names) ---
const bundlePattern = /[,&]| en /;
const bundles = dataRows.filter(d => bundlePattern.test(d.organisation));
if (bundles.length) {
  anomalies.push(`${bundles.length} entries list multiple organisations bundled together (e.g. "Org A, Org B & Org C"). They are kept as single entries with the full bundle name.`);
}

// --- Duplicates (same org+category+year) ---
const seen = {};
dataRows.forEach(d => {
  const k = d.organisation + '||' + d.category + '||' + d.year;
  seen[k] = (seen[k] || 0) + 1;
});
const dupKeys = Object.keys(seen).filter(k => seen[k] > 1);
if (dupKeys.length) {
  anomalies.push(`${dupKeys.length} duplicate entries found (same organisation, category and year appearing more than once): ${dupKeys.slice(0,5).map(k=>k.replace(/\|\|/g,' / ')).join('; ')}${dupKeys.length>5?'…':''}`);
}

// --- Verification: compare computed subtotals to CSV subtotals ---
const computedByCatYear = {};
dataRows.forEach(d => {
  computedByCatYear[d.year] = computedByCatYear[d.year] || {};
  computedByCatYear[d.year][d.category] = (computedByCatYear[d.year][d.category] || 0) + d.amount;
});
const discrepancies = [];
Object.keys(subtotals).forEach(y => {
  Object.keys(subtotals[y]).forEach(cat => {
    const reported = subtotals[y][cat];
    const computed = (computedByCatYear[y] && computedByCatYear[y][cat]) || 0;
    if (reported !== computed) {
      discrepancies.push({year:y, category:cat, reported, computed, diff: computed - reported});
    }
  });
});

// --- Grand total ---
const grandTotal = dataRows.reduce((s,d) => s+d.amount, 0);
const reportedGrand = Object.values(totals).reduce((s,v) => s+v, 0);

// --- Theme classification from org names ---
const THEMES = [
  ['Nature & Environment', [
    /natuur/i, /milieu/i, /wwf/i, /wereld natuur/i, /world wildlife/i, /vogel/i, /bird/i,
    /greenpeace/i, /rewilding/i, /\bpark(s)?\b/i, /wadden/i, /noordzee/i, /landschap/i,
    /IUCN/i, /climate/i, /klimaat/i, /sea shepherd/i, /ocean/i, /zee/i, /bos\b/i, /forest/i,
    /green challenge/i, /aarde/i, /earth/i, /\bivn\b/i, /urgenda/i, /plastic soup/i,
    /soil/i, /bodem/i, /rainforest/i, /regenwoud/i, /conservation/i, /wetland/i,
    /botanisch/i, /tuinen/i, /bee foundation/i, /bijen/i, /whale/i, /walvis/i
  ]],
  ['Animal Welfare', [
    /dierenbescherming/i, /wakker dier/i, /\baap\b/i, /animal/i, /dieren/i, /stray/i, /donkey/i, /ezel/i
  ]],
  ['Health & Medical', [
    /artsen zonder grenzen/i, /doctors without borders/i, /msf/i, /amref/i, /health/i,
    /gezond/i, /kanker/i, /cancer/i, /aidsfonds/i, /\baids\b/i, /hiv/i, /lepra/i, /leprosy/i,
    /hart/i, /heart/i, /long/i, /nier/i, /kidney/i, /diabetes/i, /alzheimer/i, /parkinson/i,
    /hersen/i, /brain/i, /\bms\b/i, /multiple sclerose/i, /\bals\b/i, /reuma/i, /rheum/i,
    /autisme/i, /autism/i, /blind/i, /doof/i, /deaf/i, /\bcbm\b/i, /\bpharm/i, /medic/i,
    /malaria/i, /tuberc/i, /polio/i, /mental/i, /psychi/i, /maag lever darm/i, /epilep/i,
    /huidfonds/i, /oogfonds/i, /fonds gehandicapten/i, /gehandicapt/i, /prinses beatrix/i,
    /michael j fox/i, /ronald mcdonald/i, /kwf/i, /hartstichting/i, /nierstichting/i,
    /longfonds/i, /diabetes fonds/i, /alzheimer nederland/i, /parkinson/i, /hersenstichting/i,
    /reumafonds/i, /reumanederland/i, /maag lever/i, /huid/i, /oog/i
  ]],
  ['International Aid & Human Rights', [
    /oxfam/i, /unicef/i, /unhcr/i, /vluchteling/i, /refugee/i, /war child/i, /rode kruis/i,
    /red cross/i, /amnesty/i, /human rights/i, /\bplan\b/i, /save the children/i, /\bcare\b/i,
    /terre des hommes/i, /peace/i, /sos kinder/i, /liliane/i, /cordaid/i, /hivos/i, /\bicco\b/i,
    /world food/i, /free press/i, /press unlimited/i, /journalism/i, /simavi/i, /dorcas/i,
    /tear/i, /zoa/i, /healthnet/i, /mama cash/i, /girls not brides/i, /child helpline/i,
    /malala/i, /aflatoun/i, /solidaridad/i, /fair/i, /justdiggit/i, /both ends/i, /wemos/i,
    /clinton/i, /carter/i, /africa/i, /afrik/i, /palestin/i, /myanmar/i, /ukrain/i, /oekra/i,
    /orphan/i, /weeshuis/i, /microcredit/i, /micro-credit/i, /akzion/i, /action aid/i,
    /bill & melinda/i, /wetlands international/i, /\bvfonds\b/i, /war trauma/i, /hcr/i,
    /trocaire/i, /pax/i, /\bicco\b/i, /kerk in actie/i, /edukans/i, /wilde ganzen/i,
    /red een kind/i, /reach now/i, /freedom/i, /vrijheid/i
  ]],
  ['Social Welfare (Netherlands)', [
    /oranje fonds/i, /kansfonds/i, /humanitas/i, /leger des heils/i, /salvation army/i,
    /voedselbank/i, /food bank/i, /jeugdfonds/i, /jantje beton/i, /resto van harte/i,
    /stichting doen/i, /armoede/i, /poverty/i, /dak- en thuisloos/i, /homeless/i,
    /reclassering/i, /slachtofferhulp/i, /kinderhulp/i, /national ouderenfonds/i, /ouderen/i,
    /elderly/i, /alleenstaand/i, /eenzaamheid/i, /loneliness/i, /villa pardoes/i,
    /make a wish/i, /opkikker/i, /kika/i
  ]],
  ['Culture, Education & Sport', [
    /museum/i, /cultuur/i, /cultur/i, /kunst/i, /\bart\b/i, /theater/i, /theatre/i, /film/i,
    /orkest/i, /orchestra/i, /muziek/i, /music/i, /onderwijs/i, /education/i, /school/i,
    /cruyff/i, /sport/i, /olympi/i, /\bngo\b/i, /rijks/i, /anne frank/i, /verzetsmuseum/i,
    /bibliothe/i, /library/i, /lezen/i, /reading/i, /stichting lezen/i, /taalhelden/i,
    /letteren/i, /poezie/i, /poetry/i, /erfgoed/i, /heritage/i, /monument/i, /oorlog/i,
    /verzet/i, /vrede/i
  ]]
];
const THEME_OVERRIDES = {
  // International Aid & Human Rights
  "100WEEKS": "International Aid & Human Rights",
  "ActionAid Nederland": "International Aid & Human Rights",
  "Amazon Frontlines": "International Aid & Human Rights",
  "APOPO": "International Aid & Human Rights",
  "BiD Network": "International Aid & Human Rights",
  "BRAC International": "International Aid & Human Rights",
  "Centrum tegen Kinderhandel en Mensenhandel": "International Aid & Human Rights",
  "Clooney Foundation for Justice": "International Aid & Human Rights",
  "Crisis Action": "International Aid & Human Rights",
  "Dance4Life": "International Aid & Human Rights",
  "Defence for Children": "International Aid & Human Rights",
  "Dokters van de Wereld": "International Aid & Human Rights",
  "Dr. Denis Mukwege Foundation": "International Aid & Human Rights",
  "The Elders": "International Aid & Human Rights",
  "Forbidden Stories": "International Aid & Human Rights",
  "Forward Inc": "International Aid & Human Rights",
  "Free a Girl": "International Aid & Human Rights",
  "Front Line Defenders": "International Aid & Human Rights",
  "Girls First Fund": "International Aid & Human Rights",
  "Global Witness": "International Aid & Human Rights",
  "The Hague Institute for Innovation of Law (HiiL)": "International Aid & Human Rights",
  "Habitat for Humanity Nederland": "International Aid & Human Rights",
  "Heifer Nederland": "International Aid & Human Rights",
  "The Hunger Project": "International Aid & Human Rights",
  "Impunity Watch": "International Aid & Human Rights",
  "Instituut Clingendael": "International Aid & Human Rights",
  "International Budget Partnership": "International Aid & Human Rights",
  "International Consortium of Investigative Journalists (ICIJ)": "International Aid & Human Rights",
  "Kinderfonds MAMAS": "International Aid & Human Rights",
  "KidsRights": "International Aid & Human Rights",
  "KLABU": "International Aid & Human Rights",
  "Lighthouse Reports": "International Aid & Human Rights",
  "Media Development Investment Fund (MDIF)": "International Aid & Human Rights",
  "Missing Chapter Foundation": "International Aid & Human Rights",
  "Mondiaal FNV": "International Aid & Human Rights",
  "Movement on the Ground": "International Aid & Human Rights",
  "Nadia's Initiative": "International Aid & Human Rights",
  "Nederlandse Helsinki Comité": "International Aid & Human Rights",
  "Not On Our Watch": "International Aid & Human Rights",
  "Obama Foundation": "International Aid & Human Rights",
  "CNV Internationaal": "International Aid & Human Rights",
  "One Acre Fund": "International Aid & Human Rights",
  "Organized Crime and Corruption Reporting Project (OCCRP)": "International Aid & Human Rights",
  "Progreso": "International Aid & Human Rights",
  "Red Umbrella Fund": "International Aid & Human Rights",
  "RNW Media": "International Aid & Human Rights",
  "Rutgers": "International Aid & Human Rights",
  "Schone Kleren Campagne": "International Aid & Human Rights",
  "The Sentry": "International Aid & Human Rights",
  "SPARK": "International Aid & Human Rights",
  "Stichting Artsen voor Kinderen": "International Aid & Human Rights",
  "Stichting Kinderpostzegels Nederland": "International Aid & Human Rights",
  "Stichting Onderzoek Multinationale Ondernemingen": "International Aid & Human Rights",
  "Theirworld": "International Aid & Human Rights",
  "Thorn": "International Aid & Human Rights",
  "Triggerise": "International Aid & Human Rights",
  "Truth Tellers Summit": "International Aid & Human Rights",
  "Women Engage for a Common Future": "International Aid & Human Rights",
  "Women Win": "International Aid & Human Rights",
  "YY Foundation": "International Aid & Human Rights",
  "Rare": "Nature & Environment",
  "Bellingcat": "International Aid & Human Rights",
  "Internews": "International Aid & Human Rights",

  // Nature & Environment
  "350.org / Fossielvrij NL": "Nature & Environment",
  "Break Free from Plastic (BFFP)": "Nature & Environment",
  "Carbon War Room": "Nature & Environment",
  "Circle Economy": "Nature & Environment",
  "Commonland": "Nature & Environment",
  "Commonland - Het Groene Goud": "Nature & Environment",
  "Justdiggit": "Nature & Environment",
  "Hivos": "International Aid & Human Rights",
  "Resto VanHarte": "Social Welfare (Netherlands)",
  "Deltaplan Biodiversiteitsherstel": "Nature & Environment",
  "Dutch Caribbean Nature Alliance": "Nature & Environment",
  "Enviu": "Nature & Environment",
  "Fauna & Flora International": "Nature & Environment",
  "Global Fishing Watch": "Nature & Environment",
  "Land Life Company/Borneo Orangutang Survival Fund": "Nature & Environment",
  "Land van Ons": "Nature & Environment",
  "Leonardo DiCaprio Foundation": "Nature & Environment",
  "Marine Stewardship Council": "Nature & Environment",
  "National Geographic Society": "Nature & Environment",
  "RAVON en Good Fish Foundation": "Nature & Environment",
  "Rocky Mountain Institute": "Nature & Environment",
  "Sea Ranger Service": "Nature & Environment",
  "SoortenNL": "Nature & Environment",
  "Stichting Voedselbosbouw Nederland": "Nature & Environment",
  "Trees for All": "Nature & Environment",
  "Wij.Land": "Nature & Environment",
  "Wildlife Justice Commission": "Nature & Environment",
  "World Fish Migration Foundation": "Nature & Environment",

  // Social Welfare (Netherlands)
  "Bijzondere uitkeringen": "Social Welfare (Netherlands)",
  "Bureau Burgerberaad": "Social Welfare (Netherlands)",
  "Buzz Women": "Social Welfare (Netherlands)",
  "De Buzinezzclub": "Social Welfare (Netherlands)",
  "De Vrolijkheid": "Social Welfare (Netherlands)",
  "Dona Daria": "Social Welfare (Netherlands)",
  "Everyday Heroes": "Social Welfare (Netherlands)",
  "Het Vergeten Kind": "Social Welfare (Netherlands)",
  "Jeugdeducatiefonds": "Social Welfare (Netherlands)",
  "Koninklijke Nederlandse Reddingsmaatschappij": "Social Welfare (Netherlands)",
  "Landelijk Samenwerkingsverband Actieve Bewoners & Social Enterprise NL": "Social Welfare (Netherlands)",
  "Landelijk Samenwerkingsverband Actieve bewoners (LSA)": "Social Welfare (Netherlands)",
  "Leergeld Nederland": "Social Welfare (Netherlands)",
  "LINDA.foundation": "Social Welfare (Netherlands)",
  "Lokale Fondsen Nederland": "Social Welfare (Netherlands)",
  "Make-A-Wish Nederland": "Social Welfare (Netherlands)",
  "Nationale Vereniging de Zonnebloem": "Social Welfare (Netherlands)",
  "Nice Place Foundation": "Social Welfare (Netherlands)",
  "Postcode Loterij Buurtfonds": "Social Welfare (Netherlands)",
  "Sam voor alle kinderen": "Social Welfare (Netherlands)",
  "SamenSpeelFonds": "Social Welfare (Netherlands)",
  "Stichting De Buurt": "Social Welfare (Netherlands)",
  "Stichting Elisabeth Samson Huis": "Social Welfare (Netherlands)",
  "Stichting Gilat": "Social Welfare (Netherlands)",
  "Stichting IPSO": "Social Welfare (Netherlands)",
  "Stichting Jarige Job": "Social Welfare (Netherlands)",
  "Stichting Join Us": "Social Welfare (Netherlands)",
  "Stichting KiKiD": "Social Welfare (Netherlands)",
  "Stichting Leeuw": "Social Welfare (Netherlands)",
  "Stichting Life Goals Nederland": "Social Welfare (Netherlands)",
  "Stichting Mainline": "Social Welfare (Netherlands)",
  "Stichting MAX Maakt Mogelijk": "Social Welfare (Netherlands)",
  "Stichting Move": "Social Welfare (Netherlands)",
  "Stichting Sheltersuit": "Social Welfare (Netherlands)",
  "Stichting Thuisgekookt": "Social Welfare (Netherlands)",
  "Vereniging SchuldHulpMaatje Nederland": "Social Welfare (Netherlands)",
  "Vier het Leven": "Social Welfare (Netherlands)",
  "WOMEN Inc.": "Social Welfare (Netherlands)",
  "Young Impact": "Social Welfare (Netherlands)",

  // Health & Medical
  "Bas van de Goor Foundation": "Health & Medical",
  "Drugs for Neglected Diseases Initiative": "Health & Medical",
  "Edwin van der Sar Foundation": "Health & Medical",
  "HandicapNL": "Health & Medical",
  "Kinderziekenhuizen van Oranje": "Health & Medical",
  "Maggies Centers Nederland": "Health & Medical",
  "MDL Fonds": "Health & Medical",
  "Metakids": "Health & Medical",
  "MIND": "Health & Medical",
  "MIND Us": "Health & Medical",
  "Nederlandse Brandwonden Stichting": "Health & Medical",
  "Pink Ribbon": "Health & Medical",
  "Spieren voor Spieren": "Health & Medical",
  "Stichting Anne-Bo": "Health & Medical",
  "Stichting Cliniclowns Nederland": "Health & Medical",
  "Stichting ease": "Health & Medical",
  "Trombosestichting Nederland": "Health & Medical",

  // Animal Welfare
  "Hulphond Nederland": "Animal Welfare",
  "ProVeg Nederland": "Animal Welfare",

  // Culture, Education & Sport (culture)
  "IDFA Bertha Fonds": "Culture, Education & Sport",
  "Movies that Matter": "Culture, Education & Sport",
  "Prins Claus Fonds": "Culture, Education & Sport",
  "Stichting Herman van Veen Arts Center Fonds": "Culture, Education & Sport",
  "What Design Can Do": "Culture, Education & Sport",
  "World Press Photo": "Culture, Education & Sport",

  // Culture, Education & Sport (education & sport)
  "Ashoka": "Culture, Education & Sport",
  "Dirk Kuyt Foundation": "Culture, Education & Sport",
  "Esther Vergeer Foundation": "Culture, Education & Sport",
  "Giovanni van Bronckhorst Foundation": "Culture, Education & Sport",
  "JINC": "Culture, Education & Sport",
  "Krajicek Foundation": "Culture, Education & Sport",
  "Rafa Nadal Foundation": "Culture, Education & Sport",
  "Right To Play": "Culture, Education & Sport",
  "Roger Federer Foundation": "Culture, Education & Sport",
  "Room to Read": "Culture, Education & Sport",
  "Scouting Nederland": "Culture, Education & Sport",
  "Space Buzz Foundation": "Culture, Education & Sport",
  "Stichting 3X3 Unites": "Culture, Education & Sport",
  "Stichting leerKRACHT": "Culture, Education & Sport",
  "Young Perspectives": "Culture, Education & Sport",
  "Yvonne van Gennip Talent Fonds": "Culture, Education & Sport",

  // New orgs appearing in 2025 data
  "Amref Health Africa en PharmAccess (extra bijdrage Dream Fund 2015)": "Health & Medical",
  "COC Nederland": "Social Welfare (Netherlands)",
  "Cultural Emergency Response": "Culture, Education & Sport",
  "De Buurt": "Social Welfare (Netherlands)",
  "DollyWood Foundation": "Culture, Education & Sport",
  "Emma at Work": "Social Welfare (Netherlands)",
  "European AI & Society Fund": "International Aid & Human Rights",
  "HandicapNL - MBO op maat": "Health & Medical",
  "Hartstichting en Diabetes Fonds": "Health & Medical",
  "Human Right Watch": "International Aid & Human Rights",
  "Impact Hub Association": "International Aid & Human Rights",
  "International Fund for Animal Welfare": "Animal Welfare",
  "Johan Cruyff Foundation en Kraijeck Foundation": "Culture, Education & Sport",
  "Join Us": "Social Welfare (Netherlands)",
  "Kansfonds en Humanitas": "Social Welfare (Netherlands)",
  "Kinderpostzegels": "Social Welfare (Netherlands)",
  "Mensen met een Missie": "International Aid & Human Rights",
  "Nationaal Fonds Kinderhulp": "Social Welfare (Netherlands)",
  "NewBees": "Social Welfare (Netherlands)",
  "Organized Crime and Corruption Reporting Project": "International Aid & Human Rights",
  "Paris Peace Forum": "International Aid & Human Rights",
  "ParkinsonNederland": "Health & Medical",
  "Plan International Nederland": "International Aid & Human Rights",
  "Prinses M\u00e1xima Centrum Foundation": "Health & Medical",
  "Quiet Nederland": "Social Welfare (Netherlands)",
  "Rainforest Foundation": "Nature & Environment",
  "Re:wild": "Nature & Environment",
  "Refugee Company": "Social Welfare (Netherlands)",
  "Rewilding Argentina": "Nature & Environment",
  "Rode Kruis": "International Aid & Human Rights",
  "Sovon Vogelonderzoek Nederland": "Nature & Environment",
  "Stichting Ambulance Wens": "Health & Medical",
  "Stichting Armoedefonds": "Social Welfare (Netherlands)",
  "Stichting De Kindertelefoon": "Social Welfare (Netherlands)",
  "Stichting Dierenlot": "Animal Welfare",
  "Stichting Long COVID": "Health & Medical",
  "WaterAid": "International Aid & Human Rights",
  "WaterAid Nederland": "International Aid & Human Rights",
  "World Food Programme - Fortifying the Future": "International Aid & Human Rights"
};
function themeOf(name) {
  if (THEME_OVERRIDES[name]) return THEME_OVERRIDES[name];
  for (const [theme, patterns] of THEMES) {
    for (const p of patterns) if (p.test(name)) return theme;
  }
  return 'Uncategorised';
}
dataRows.forEach(d => { d.theme = themeOf(d.organisation); });

// --- Dutch/International classification ---
const DUTCH_MAP = {};
const DUTCH_MAP_NORM = {}; // whitespace-normalized fallback
const normName = s => s.replace(/\s+/g, ' ').trim().toLowerCase();
{
  const lines = parseCSV(CLASSIFICATION_CSV);
  if (lines.length) {
    const header = lines[0].map(h => (h||'').trim().toLowerCase());
    const nameIdx = header.indexOf('organisation_name');
    const dutchIdx = header.indexOf('is_dutch');
    for (let i = 1; i < lines.length; i++) {
      const r = lines[i];
      if (!r || r.length <= Math.max(nameIdx, dutchIdx)) continue;
      const name = (r[nameIdx] || '').trim();
      if (!name) continue;
      const isDutch = (r[dutchIdx] || '').trim().toUpperCase() === 'TRUE';
      DUTCH_MAP[name] = isDutch;
      DUTCH_MAP_NORM[normName(name)] = isDutch;
    }
  }
}
// Classification overrides for orgs not in the classification CSV
const DUTCH_OVERRIDES = {
  "Amref Health Africa en PharmAccess (extra bijdrage Dream Fund 2015)": true,
  "COC Nederland": true, "Cultural Emergency Response": true, "De Buurt": true,
  "DollyWood Foundation": false, "Emma at Work": true, "European AI & Society Fund": false,
  "HandicapNL - MBO op maat": true, "Hartstichting en Diabetes Fonds": true,
  "Human Right Watch": false, "Impact Hub Association": false,
  "International Fund for Animal Welfare": false,
  "Johan Cruyff Foundation en Kraijeck Foundation": true, "Join Us": true,
  "Kansfonds en Humanitas": true, "Kinderpostzegels": true,
  "Mensen met een Missie": true, "Nationaal Fonds Kinderhulp": true,
  "NewBees": true, "Organized Crime and Corruption Reporting Project": false,
  "Paris Peace Forum": false, "ParkinsonNederland": true,
  "Plan International Nederland": true, "Prinses M\u00e1xima Centrum Foundation": true,
  "Quiet Nederland": true, "Rainforest Foundation": false, "Re:wild": false,
  "Refugee Company": true, "Rewilding Argentina": false, "Rode Kruis": true,
  "Sovon Vogelonderzoek Nederland": true, "Stichting Ambulance Wens": true,
  "Stichting Armoedefonds": true, "Stichting De Kindertelefoon": true,
  "Stichting Dierenlot": true, "Stichting Long COVID": true,
  "WaterAid": false, "WaterAid Nederland": true,
  "World Food Programme - Fortifying the Future": false,
  "Amazon Frontlines": false, "Nederlandse Helsinki Comit\u00e9": true
};
Object.entries(DUTCH_OVERRIDES).forEach(([k, v]) => {
  if (!(k in DUTCH_MAP)) { DUTCH_MAP[k] = v; DUTCH_MAP_NORM[normName(k)] = v; }
});
dataRows.forEach(d => {
  if (d.organisation in DUTCH_MAP) {
    d.isDutch = DUTCH_MAP[d.organisation];
  } else {
    const n = normName(d.organisation);
    d.isDutch = (n in DUTCH_MAP_NORM) ? DUTCH_MAP_NORM[n] : null;
  }
  d.origin = d.isDutch === true ? 'Dutch' : d.isDutch === false ? 'International' : 'Unknown';
});

// --- Organisation metadata from Organisations_overview CSV ---
const ORG_META = {};
const JOINT_GRANT_ORGS = new Set();
const JOINT_GRANT_CONSTITUENT_MAP = {}; // bundled name -> [constituent org names]
{
  const lines = parseCSV(ORG_OVERVIEW_CSV);
  if (lines.length) {
    const hdr = lines[0].map(h => (h||'').trim().toLowerCase());
    const nameIdx = hdr.indexOf('organisations');
    const dutchIdx = hdr.indexOf('is_dutch');
    const countryIdx = hdr.indexOf('country');
    const themeIdx = hdr.indexOf('theme');
    const descIdx = hdr.indexOf('description');
    const jgIdx = hdr.indexOf('joint grant');
    for (let i = 1; i < lines.length; i++) {
      const r = lines[i];
      if (!r || r.length <= nameIdx) continue;
      const name = (r[nameIdx] || '').trim();
      if (!name) continue;
      const meta = {
        isDutch: (r[dutchIdx] || '').trim().toUpperCase() === 'TRUE',
        country: (r[countryIdx] || '').trim(),
        theme: (r[themeIdx] || '').trim(),
        description: (r[descIdx] || '').trim(),
        jointGrant: (r[jgIdx] || '').trim().toUpperCase() === 'TRUE'
      };
      ORG_META[name] = meta;
      if (meta.jointGrant) JOINT_GRANT_ORGS.add(name);
    }
  }
}
// Map compound joint-grant names to their constituent orgs
const compoundJG = [
  ["Hivos & Greenpeace - Alle ogen op de Amazone", ["Hivos", "Greenpeace"]],
  ["Amref Health Africa en PharmAccess (extra bijdrage Dream Fund 2015)", ["Amref Health Africa", "PharmAccess"]],
  ["Amref Health Africa en PharmAccess (extra bijdrage Droomfonds 2015)", ["Amref Health Africa", "PharmAccess"]]
];
compoundJG.forEach(([bundled, parts]) => { JOINT_GRANT_CONSTITUENT_MAP[bundled] = parts; });

// Override dataRow metadata from ORG_META (CSV is source of truth)
dataRows.forEach(d => {
  const m = ORG_META[d.organisation];
  if (m) {
    if (m.theme) d.theme = m.theme;
    d.isDutch = m.isDutch;
    d.origin = d.isDutch === true ? 'Dutch' : d.isDutch === false ? 'International' : 'Unknown';
  }
  d.isJointGrant = JOINT_GRANT_ORGS.has(d.organisation);
});

// --- Project Location from CSV ---
const PROJECT_LOC_MAP = {}; // key: "category||org||year" -> project location
{
  const CAT_MAP_NL = {
    'Meerjarige partner': 'Multi-year partner',
    'Eenmalige schenking': 'One-time donation',
    'Extra bijdrage aan meerjarige partners': 'Extra contribution to multi-year partners',
    'Droomfonds': 'Dream Fund'
  };
  const lines = parseCSV(PROJECT_COUNTRY_CSV);
  if (lines.length) {
    const header = lines[0].map(h => (h||'').trim().toLowerCase());
    const catIdx = header.indexOf('categorie');
    const orgIdx = header.indexOf('organisatie');
    const yearIdx = header.indexOf('jaar');
    const pcIdx = header.indexOf('project location');
    if (orgIdx >= 0 && pcIdx >= 0 && catIdx >= 0) {
      for (let i = 1; i < lines.length; i++) {
        const r = lines[i];
        if (!r || r.length <= Math.max(orgIdx, pcIdx, catIdx)) continue;
        const catNL = (r[catIdx] || '').trim();
        const catEN = CAT_MAP_NL[catNL] || '';
        const org = (r[orgIdx] || '').trim();
        const yr = (r[yearIdx] || '').trim();
        const pc = (r[pcIdx] || '').trim();
        if (!catEN || !org || !pc) continue;
        const key = catEN + '||' + org + '||' + yr;
        PROJECT_LOC_MAP[key] = pc;
      }
    }
  }
}
// Manual overrides for entries where org names differ between the two CSVs
const LOC_OVERRIDES = {
  "One-time donation||Nederlandse Helsinki Comit\u00e9||2018": "Poland, Russia, Turkey, Hungary",
  "One-time donation||Amref Health Africa||2019": "Africa, Kenya",
  "One-time donation||Het Vergeten Kind||2020": "The Netherlands",
  "Extra contribution to multi-year partners||Vfonds||2016": "The Netherlands",
  "Extra contribution to multi-year partners||Natuur & Milieu||2016": "The Netherlands",
  "Extra contribution to multi-year partners||AAP||2016": "Morocco",
  "Extra contribution to multi-year partners||ARK Rewilding Nederland||2017": "The Netherlands",
  "Extra contribution to multi-year partners||Amref Health Africa||2017": "Kenya",
  "Extra contribution to multi-year partners||Defence for Children||2017": "Global",
  "Extra contribution to multi-year partners||Plan International||2018": "Jordan",
  "Extra contribution to multi-year partners||Clinton Foundation||2018": "Cura\u00e7ao",
  "Extra contribution to multi-year partners||Het Nederlandse Rode Kruis||2019": "Ivory Coast",
  "Extra contribution to multi-year partners||De Vrolijkheid||2019": "The Netherlands",
  "Extra contribution to multi-year partners||ARK Rewilding Nederland||2020": "The Netherlands",
  "Extra contribution to multi-year partners||Het Nederlandse Rode Kruis||2021": "Global",
  "Extra contribution to multi-year partners||MDL Fonds||2021": "The Netherlands",
  "Extra contribution to multi-year partners||Wereld Natuur Fonds en Het Rode Kruis||2022": "Global",
  "Extra contribution to multi-year partners||Amref Health Africa||2022": "Ethiopia",
  "Extra contribution to multi-year partners||Save the Children Nederland||2017": "Global",
  "Extra contribution to multi-year partners||Save the Children Nederland||2022": "Global",
  "Extra contribution to multi-year partners||Save the Children Nederland||2023": "Global",
  "Extra contribution to multi-year partners||Dierenbescherming||2024": "The Netherlands",
  "Dream Fund||Leprastichting||2016": "India, Indonesia, Brazil",
  "Dream Fund||Rutgers||2017": "Kenya, Ethiopia, West Africa",
  "Dream Fund||Natuur & Milieu||2018": "The Netherlands",
  "Dream Fund||Amref Health Africa en PharmAccess (extra bijdrage Droomfonds 2015)||2019": "Africa",
  "Dream Fund||Hivos & Greenpeace - Alle ogen op de Amazone||2016": "Brazil, Ecuador, Peru",
  "Extra contribution to multi-year partners||Vfonds||2017": "The Netherlands",
  "One-time donation||Amref Health Africa||2018": "Africa",
  "One-time donation||Stichting DOEN||2019": "The Netherlands",
  "One-time donation||Het Nederlandse Rode Kruis||2020": "The Netherlands, Caribbean"
};
Object.entries(LOC_OVERRIDES).forEach(([k, v]) => {
  if (!PROJECT_LOC_MAP[k]) PROJECT_LOC_MAP[k] = v;
});

// --- Project Descriptions & Updated Locations from PROJ_DESC_CSV ---
const PROJ_DESC_MAP = {}; // key: "category||org||year" -> {location, description}
{
  const PROJ_ALIAS = {
    "vfonds": "Vfonds",
    "Stichting AAP": "AAP",
    "Natuur Milieu": "Natuur & Milieu",
    "ARK": "ARK Rewilding Nederland",
    "ARK Natuurontwikkeling": "ARK Rewilding Nederland",
    "Amref Flying Doctors": "Amref Health Africa",
    "Clinton Foundation and Rocky Mountain Institute": "Clinton Foundation",
    "Plan International Nederland": "Plan International",
    "Het Rode Kruis": "Het Nederlandse Rode Kruis",
    "Rode Kruis": "Het Nederlandse Rode Kruis",
    "Stichting de Vrolijkheid": "De Vrolijkheid",
    "Wereld Natuur Fonds en Rode Kruis": "Wereld Natuur Fonds en Het Rode Kruis",
    "Save the Children": "Save the Children Nederland",
    "Maag Lever Darm Stichting": "MDL Fonds",
    "Dierenbescherming Nederland": "Dierenbescherming",
    "Leprastichting: Stop leprabesmetting!": "Leprastichting",
    "Amref Flying Doctors en PharmAccess": "Amref Health Africa en PharmAccess (extra bijdrage Dream Fund 2015)",
    "Netherlands Helsinki Committee": "Nederlandse Helsinki Comit\u00e9",
    "Stichting DOEN - DOEN Participaties": "Stichting DOEN",
    "Stichting Het Vergeten Kind": "Het Vergeten Kind",
    "Hivos & Greenpeace: Alle ogen op de Amazone": "Hivos & Greenpeace - Alle ogen op de Amazone",
    "Rutgers, Een veilige keuze voor vrouwen": "Rutgers",
    "Defence for Children \u0096 ECPAT Nederland": "Defence for Children",
    "Defence for Children \u2013 ECPAT Nederland": "Defence for Children",
    "Defence for Children  ECPAT Nederland": "Defence for Children"
  };
  const lines = parseCSV(PROJ_DESC_CSV);
  if (lines.length) {
    const hdr = lines[0].map(h => (h||'').trim().toLowerCase());
    const catIdx = hdr.findIndex(h => h.startsWith('category'));
    const orgIdx = hdr.indexOf('organisation');
    const yrIdx = hdr.indexOf('year');
    const locIdx = hdr.indexOf('project location');
    const descIdx = hdr.indexOf('project description');
    if (catIdx >= 0 && orgIdx >= 0) {
      for (let i = 1; i < lines.length; i++) {
        const r = lines[i];
        if (!r || r.length <= Math.max(catIdx, orgIdx)) continue;
        const cat = (r[catIdx] || '').trim();
        let org = (r[orgIdx] || '').trim();
        const yr = (r[yrIdx] || '').trim();
        const loc = locIdx >= 0 ? (r[locIdx] || '').trim() : '';
        const desc = descIdx >= 0 ? (r[descIdx] || '').trim() : '';
        // Resolve org name aliases
        if (PROJ_ALIAS[org]) org = PROJ_ALIAS[org];
        // Also try resolving names with special chars (en-dash etc)
        if (!PROJ_ALIAS[org]) {
          const cleaned = org.replace(/[\x96\u2013\u2014]/g, ' ').replace(/\s+/g, ' ').trim();
          for (const [from, to] of Object.entries(PROJ_ALIAS)) {
            if (cleaned === from.replace(/[\x96\u2013\u2014]/g, ' ').replace(/\s+/g, ' ').trim()) { org = to; break; }
          }
        }
        // Also handle Dream Fund name variants (colon vs dash)
        const orgNorm = org.replace(/:\s*/g, ' - ').replace(/,\s*/g, ' ').trim();
        if (!cat || !org) continue;
        const key = cat + '||' + org + '||' + yr;
        PROJ_DESC_MAP[key] = { location: loc, description: desc };
        // Also store normalized variant
        if (orgNorm !== org) {
          PROJ_DESC_MAP[cat + '||' + orgNorm + '||' + yr] = { location: loc, description: desc };
        }
      }
    }
  }
}

dataRows.forEach(d => {
  const key = d.category + '||' + d.organisation + '||' + d.year;
  const rawLoc = PROJECT_LOC_MAP[key] || '';
  // Multi-year partners have no project location data; show descriptive label
  if (!rawLoc && d.category === 'Multi-year partner') {
    d.projectLocation = 'Core Funding (Long-Term Partnership)';
  } else {
    d.projectLocation = rawLoc;
  }
  // Override location and add description from PROJ_DESC_CSV (source of truth)
  const pd = PROJ_DESC_MAP[key];
  if (pd) {
    if (pd.location) d.projectLocation = pd.location;
    d.projectDescription = pd.description || '';
  } else {
    d.projectDescription = '';
  }
  // Location-based filter flags for the All Donations toggle
  // Parse comma-separated locations and check for Netherlands vs international
  const loc = d.projectLocation.toLowerCase();
  const hasNL = /\bthe netherlands\b|^core funding/i.test(d.projectLocation);
  const parts = d.projectLocation.split(/,/).map(s => s.trim().toLowerCase());
  const hasNonNL = parts.some(p => p && !/the netherlands/i.test(p) && !/^core funding/i.test(p));
  // "Global" counts as international
  const hasGlobal = /\bglobal\b/i.test(d.projectLocation);
  d.locIsNL = hasNL;
  d.locIsIntl = hasNonNL || hasGlobal;
});

// ===== RENDERING =====
const fmt = n => '€' + n.toLocaleString('en-US');
const fmtShort = n => {
  if (n >= 1e9) return '€' + (n/1e9).toFixed(2) + 'B';
  if (n >= 1e6) return '€' + (n/1e6).toFixed(1) + 'M';
  if (n >= 1e3) return '€' + (n/1e3).toFixed(1) + 'K';
  return '€' + n;
};

const years = [...new Set(dataRows.map(d=>d.year))].sort();
const uniqueOrgs = new Set(dataRows.map(d=>d.organisation)).size;

// Category breakdown table
const catTotals = {};
CAT_ORDER.forEach(c => { catTotals[c] = { total: 0, count: 0, orgs: new Set() }; });
dataRows.forEach(d => {
  catTotals[d.category].total += d.amount;
  catTotals[d.category].count += 1;
  catTotals[d.category].orgs.add(d.organisation);
});
const catTbody = document.querySelector('#category-table tbody');
let catRowsHTML = '';
CAT_ORDER.forEach(c => {
  const t = catTotals[c];
  const pct = grandTotal ? (t.total / grandTotal * 100) : 0;
  catRowsHTML += `<tr><td>${c}</td><td class="num">${t.orgs.size} (${t.count} entries)</td><td class="num">${fmt(t.total)}</td><td class="num">${pct.toFixed(1)}%</td></tr>`;
});
catRowsHTML += `<tr style="font-weight:700; background:#f9fafb"><td>Total</td><td class="num">${uniqueOrgs} (${dataRows.length} entries)</td><td class="num">${fmt(grandTotal)}</td><td class="num">100.0%</td></tr>`;
catTbody.innerHTML = catRowsHTML;

// Category pie chart
new Chart(document.getElementById('categoryChart'), {
  type: 'doughnut',
  data: {
    labels: CAT_ORDER,
    datasets: [{
      data: CAT_ORDER.map(c => catTotals[c].total),
      backgroundColor: ['#00ACD7','#F18A6F','#2E5A6B','#E8B647'],
      borderWidth: 2, borderColor: '#fff'
    }]
  },
  options: {
    responsive: true,
    plugins: {
      legend: { position: 'bottom', labels: { boxWidth: 14, font: {size: 11} } },
      tooltip: { callbacks: { label: ctx => `${ctx.label}: ${fmt(ctx.parsed)} (${(ctx.parsed/grandTotal*100).toFixed(1)}%)` } }
    }
  }
});

// Theme breakdown — filterable
const ALL_THEME_KEYS = (() => {
  const s = new Set();
  dataRows.forEach(d => s.add(d.theme));
  return [...s];
})();

let themeChart = null;
function computeThemeTotals(rows) {
  const totals = {};
  ALL_THEME_KEYS.forEach(t => {
    totals[t] = { total: 0, byCat: Object.fromEntries(CAT_ORDER.map(c=>[c,0])), orgs: new Set() };
  });
  rows.forEach(d => {
    if (!totals[d.theme]) {
      totals[d.theme] = { total: 0, byCat: Object.fromEntries(CAT_ORDER.map(c=>[c,0])), orgs: new Set() };
    }
    totals[d.theme].total += d.amount;
    totals[d.theme].byCat[d.category] += d.amount;
    totals[d.theme].orgs.add(d.organisation);
  });
  return totals;
}

function renderThemes() {
  const dutchMode = document.querySelector('#dutchToggle .toggle-btn.active').dataset.dutch;
  const yr = document.getElementById('themeYearFilter').value;

  const filtered = dataRows.filter(d => {
    if (yr && String(d.year) !== yr) return false;
    if (dutchMode === 'dutch' && d.isDutch !== true) return false;
    if (dutchMode === 'international' && d.isDutch !== false) return false;
    return true;
  });

  const totals = computeThemeTotals(filtered);
  const keys = Object.keys(totals)
    .filter(k => totals[k].total > 0)
    .sort((a,b) => totals[b].total - totals[a].total);
  const filteredTotal = filtered.reduce((s,d)=>s+d.amount, 0);
  const catSums = Object.fromEntries(CAT_ORDER.map(c=>[c,0]));
  filtered.forEach(d => { catSums[d.category] += d.amount; });

  // Table
  const tbody = document.querySelector('#theme-table tbody');
  if (keys.length === 0) {
    tbody.innerHTML = `<tr><td colspan="7" style="text-align:center; color:var(--muted); padding:1rem;">No data for the selected filters.</td></tr>`;
  } else {
    tbody.innerHTML = keys.map(t => {
      const r = totals[t];
      const pct = filteredTotal ? (r.total/filteredTotal*100).toFixed(1) : '0.0';
      return `<tr><td>${t}</td>` +
        CAT_ORDER.map(c => `<td class="num">${fmtShort(r.byCat[c])}</td>`).join('') +
        `<td class="num"><strong>${fmt(r.total)}</strong></td><td class="num">${pct}%</td></tr>`;
    }).join('') + `<tr style="font-weight:700; background:#f9fafb"><td>Total</td>` +
      CAT_ORDER.map(c => `<td class="num">${fmtShort(catSums[c])}</td>`).join('') +
      `<td class="num">${fmt(filteredTotal)}</td><td class="num">${filteredTotal?'100.0':'0.0'}%</td></tr>`;
  }

  // Chart
  const chartLabels = keys.length ? keys : ['(no data)'];
  const chartData = {
    labels: chartLabels,
    datasets: CAT_ORDER.map((c,i) => ({
      label: CAT_SHORT[c],
      data: keys.length ? keys.map(t => totals[t].byCat[c]) : [0],
      backgroundColor: ['#00ACD7','#F18A6F','#2E5A6B','#E8B647'][i]
    }))
  };
  if (themeChart) {
    themeChart.data = chartData;
    themeChart.update();
  } else {
    themeChart = new Chart(document.getElementById('themeChart'), {
      type: 'bar',
      data: chartData,
      options: {
        responsive: true, maintainAspectRatio: false,
        scales: {
          x: { stacked: true, ticks: { font: {size: 10} } },
          y: { stacked: true, ticks: { callback: v => fmtShort(v) } }
        },
        plugins: {
          legend: { position: 'bottom' },
          tooltip: { callbacks: { label: ctx => `${ctx.dataset.label}: ${fmt(ctx.parsed.y)}` } }
        }
      }
    });
  }
}

// Theme -> orgs listing (unfiltered reference)
const allThemeTotals = computeThemeTotals(dataRows);
const themeOrgsDiv = document.getElementById('theme-orgs');
themeOrgsDiv.innerHTML = Object.keys(allThemeTotals)
  .filter(k => allThemeTotals[k].total > 0)
  .sort((a,b) => allThemeTotals[b].total - allThemeTotals[a].total)
  .map(t => {
    const orgs = [...allThemeTotals[t].orgs].sort();
    return `<p><strong>${t}</strong> (${orgs.length} orgs): ${orgs.join(', ')}</p>`;
  }).join('');

// Wire up theme filters
document.querySelectorAll('#dutchToggle .toggle-btn').forEach(btn => {
  btn.addEventListener('click', () => {
    document.querySelectorAll('#dutchToggle .toggle-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    renderThemes();
  });
});
const themeYearSel = document.getElementById('themeYearFilter');
years.forEach(y => { const o=document.createElement('option'); o.value=y; o.textContent=y; themeYearSel.appendChild(o); });
themeYearSel.addEventListener('change', renderThemes);

renderThemes();

// ===== Organisations (aggregated) =====
const orgAgg = {};
const orgJointGrants = {}; // orgName -> [{title, amount, year, category}]

function ensureOrgAgg(name, theme, isDutch) {
  if (!orgAgg[name]) {
    orgAgg[name] = {
      organisation: name,
      theme: theme || 'Uncategorised',
      isDutch: isDutch,
      total: 0,
      count: 0,
      years: new Set(),
      byCat: Object.fromEntries(CAT_ORDER.map(c => [c, { total: 0, years: new Set() }]))
    };
  }
}

dataRows.forEach(d => {
  if (d.isJointGrant) {
    // Compound joint grants: attribute to constituent orgs for display (not totals)
    const parts = JOINT_GRANT_CONSTITUENT_MAP[d.organisation];
    if (parts) {
      parts.forEach(partName => {
        // Ensure the constituent org exists in aggregation
        const pm = ORG_META[partName];
        ensureOrgAgg(partName, pm ? pm.theme : d.theme, pm ? pm.isDutch : d.isDutch);
        if (!orgJointGrants[partName]) orgJointGrants[partName] = [];
        orgJointGrants[partName].push({
          title: d.organisation, amount: d.amount, year: d.year, category: d.category
        });
      });
    }
    // Single-name joint grants: just skip from org list (still in All Donations)
    return;
  }
  // Normal donation row
  ensureOrgAgg(d.organisation, d.theme, d.isDutch);
  const a = orgAgg[d.organisation];
  a.total += d.amount;
  a.count += 1;
  a.years.add(d.year);
  a.byCat[d.category].total += d.amount;
  a.byCat[d.category].years.add(d.year);
});

const orgList = Object.values(orgAgg)
  .filter(a => !JOINT_GRANT_ORGS.has(a.organisation)) // hide joint-grant-only orgs
  .map(a => {
    const m = ORG_META[a.organisation];
    return {
      ...a,
      origin: a.isDutch === true ? 'Dutch' : a.isDutch === false ? 'International' : 'Unknown',
      description: m ? m.description : '',
      jointGrants: orgJointGrants[a.organisation] || [],
      yearsCount: a.years.size,
      yearsList: [...a.years].sort()
    };
  });

const orgTbody = document.querySelector('#org-table tbody');
let orgSort = { key: 'total', dir: 'desc' };
const expandedOrgs = new Set();

function originPill(o) {
  if (o === 'Dutch') return '<span class="origin-pill dutch">The Netherlands</span>';
  if (o === 'International') return '<span class="origin-pill intl">International</span>';
  return '<span class="origin-pill">Unknown</span>';
}

function renderOrgDetail(org) {
  const cats = CAT_ORDER.filter(c => org.byCat[c].total > 0);
  const cards = cats.map(c => {
    const b = org.byCat[c];
    const ys = [...b.years].sort();
    return `<div class="detail-card">
      <div class="cat">${CAT_SHORT[c]}</div>
      <div class="amt">${fmt(b.total)}</div>
      <div class="yrs">Years: ${ys.join(', ')}</div>
    </div>`;
  }).join('');
  // Joint grant cards
  let jgHTML = '';
  if (org.jointGrants && org.jointGrants.length) {
    const jgCards = org.jointGrants.map(jg =>
      `<div class="detail-card" style="border-left-color:var(--accent-2);">
        <div class="cat">Joint Grant: ${jg.title}</div>
        <div class="amt">${fmt(jg.amount)}</div>
        <div class="yrs">${CAT_SHORT[jg.category] || jg.category} &middot; ${jg.year}</div>
      </div>`
    ).join('');
    jgHTML = `<div style="font-size:.78rem; color:var(--muted); margin:.75rem 0 .35rem; font-weight:600;">Joint Grants (not included in total above)</div>
      <div class="detail-grid">${jgCards}</div>`;
  }
  return `<tr class="detail-row"><td colspan="6">
    ${org.description ? `<div class="org-desc" style="margin-bottom:.6rem;">${org.description.replace(/\.$/, '')}</div>` : ''}
    <div style="font-size:.82rem; color:var(--muted); margin-bottom:.5rem;">
      Breakdown for <strong style="color:var(--ink-strong)">${org.organisation}</strong>
      &middot; ${org.count} donations across ${org.yearsCount} year${org.yearsCount===1?'':'s'}
      &middot; Total: <strong style="color:var(--ink-strong)">${fmt(org.total)}</strong>
    </div>
    <div class="detail-grid">${cards}</div>
    ${jgHTML}
  </td></tr>`;
}

function renderOrgs() {
  const q = document.getElementById('orgSearchInput').value.toLowerCase();
  const dutchMode = document.querySelector('#orgDutchToggle .toggle-btn.active').dataset.dutch;
  const themeSel = document.getElementById('orgThemeFilter').value;
  let v = orgList.filter(a => {
    if (q && !a.organisation.toLowerCase().includes(q)) return false;
    if (dutchMode === 'dutch' && a.isDutch !== true) return false;
    if (dutchMode === 'international' && a.isDutch !== false) return false;
    if (themeSel && a.theme !== themeSel) return false;
    return true;
  });
  const { key, dir } = orgSort;
  v.sort((a, b) => {
    let x, y;
    if (key === 'years') { x = a.yearsCount; y = b.yearsCount; }
    else { x = a[key]; y = b[key]; }
    if (typeof x === 'string') { x = x.toLowerCase(); y = y.toLowerCase(); }
    return (x < y ? -1 : x > y ? 1 : 0) * (dir === 'asc' ? 1 : -1);
  });
  const totalSum = v.reduce((s, a) => s + a.total, 0);
  document.getElementById('orgRowCount').textContent = `${v.length} organisations · ${fmt(totalSum)}`;

  let html = '';
  v.forEach(org => {
    const isOpen = expandedOrgs.has(org.organisation);
    html += `<tr class="org-row${isOpen ? ' expanded' : ''}" data-org="${org.organisation.replace(/"/g, '&quot;')}">` +
      `<td><span class="chev">▸</span> ${org.organisation}</td>` +
      `<td>${org.theme}</td>` +
      `<td>${originPill(org.origin)}</td>` +
      `<td class="num">${fmt(org.total)}</td>` +
      `<td class="num">${org.count}</td>` +
      `<td class="num">${org.yearsCount}</td></tr>`;
    if (isOpen) html += renderOrgDetail(org);
  });
  orgTbody.innerHTML = html || `<tr><td colspan="6" style="text-align:center; color:var(--muted); padding:1rem;">No organisations match the current filters.</td></tr>`;
}

// Click to expand
orgTbody.addEventListener('click', e => {
  const tr = e.target.closest('tr.org-row');
  if (!tr) return;
  const name = tr.dataset.org;
  if (expandedOrgs.has(name)) expandedOrgs.delete(name);
  else expandedOrgs.add(name);
  renderOrgs();
});

// Sort handlers
document.querySelectorAll('#org-table th[data-sort]').forEach(th => {
  th.addEventListener('click', () => {
    const k = th.dataset.sort;
    if (orgSort.key === k) orgSort.dir = orgSort.dir === 'asc' ? 'desc' : 'asc';
    else orgSort = { key: k, dir: (k === 'total' || k === 'count' || k === 'years') ? 'desc' : 'asc' };
    renderOrgs();
  });
});

// Dutch toggle + search
document.querySelectorAll('#orgDutchToggle .toggle-btn').forEach(btn => {
  btn.addEventListener('click', () => {
    document.querySelectorAll('#orgDutchToggle .toggle-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    renderOrgs();
  });
});
document.getElementById('orgSearchInput').addEventListener('input', renderOrgs);

// Populate theme filter (from orgList, sorted by total donated)
const orgThemeSel = document.getElementById('orgThemeFilter');
const orgThemeTotals = {};
orgList.forEach(a => { orgThemeTotals[a.theme] = (orgThemeTotals[a.theme] || 0) + a.total; });
Object.keys(orgThemeTotals)
  .sort((a,b) => orgThemeTotals[b] - orgThemeTotals[a])
  .forEach(t => { const o = document.createElement('option'); o.value = t; o.textContent = t; orgThemeSel.appendChild(o); });
orgThemeSel.addEventListener('change', renderOrgs);

renderOrgs();

// Main donations table
const catFilter = document.getElementById('categoryFilter');
const CAT_FILTER_ORDER = ['Dream Fund','One-time donation','Extra contribution to multi-year partners','Multi-year partner'];
CAT_FILTER_ORDER.forEach(c => { const o=document.createElement('option'); o.value=c; o.textContent=c; if(c==='Dream Fund') o.selected=true; catFilter.appendChild(o); });
{ const o=document.createElement('option'); o.value=''; o.textContent='All categories'; catFilter.appendChild(o); }
const yearFilter = document.getElementById('yearFilter');
years.forEach(y => { const o=document.createElement('option'); o.value=y; o.textContent=y; yearFilter.appendChild(o); });
const themeFilter = document.getElementById('themeFilter');
const mainThemeKeys = ALL_THEME_KEYS.filter(k => allThemeTotals[k] && allThemeTotals[k].total > 0)
  .sort((a,b) => allThemeTotals[b].total - allThemeTotals[a].total);
mainThemeKeys.forEach(t => { const o=document.createElement('option'); o.value=t; o.textContent=t; themeFilter.appendChild(o); });

const mainTbody = document.querySelector('#main-table tbody');
let currentSort = { key: 'amount', dir: 'desc' };
let viewData = dataRows.slice();
const expandedDonations = new Set();
function donKey(d) { return d.category + '||' + d.organisation + '||' + d.year; }

function pillFor(cat) {
  const i = CAT_ORDER.indexOf(cat) + 1;
  return `<span class="pill c${i}">${CAT_SHORT[cat]}</span>`;
}
function render() {
  const q = document.getElementById('searchInput').value.toLowerCase();
  const cf = catFilter.value, yf = yearFilter.value, tf = themeFilter.value;
  const dutchMode = document.querySelector('#mainDutchToggle .toggle-btn.active').dataset.dutch;
  let v = dataRows.filter(d => {
    if (q && !d.organisation.toLowerCase().includes(q)) return false;
    if (cf && d.category !== cf) return false;
    if (yf && String(d.year) !== yf) return false;
    if (tf && d.theme !== tf) return false;
    if (dutchMode === 'dutch' && !d.locIsNL) return false;
    if (dutchMode === 'international' && !d.locIsIntl) return false;
    return true;
  });
  const {key, dir} = currentSort;
  v.sort((a,b) => {
    let x = a[key], y = b[key];
    if (typeof x === 'string') { x = x.toLowerCase(); y = y.toLowerCase(); }
    return (x<y?-1:x>y?1:0) * (dir==='asc'?1:-1);
  });
  viewData = v;
  const sumVisible = v.reduce((s,d)=>s+d.amount,0);
  document.getElementById('rowCount').textContent = `${v.length} rows · ${fmt(sumVisible)}`;
  mainTbody.innerHTML = v.map(d =>
    `<tr class="don-row${d.projectDescription ? ' has-desc' : ''}${expandedDonations.has(donKey(d)) ? ' expanded' : ''}" data-donkey="${donKey(d).replace(/"/g, '&quot;')}"><td>${d.projectDescription ? '<span class="chev">▸</span> ' : ''}${d.organisation}</td><td>${pillFor(d.category)}</td><td>${d.theme}</td><td>${originPill(d.origin)}</td><td>${d.projectLocation}</td><td class="num">${d.year}</td><td class="num">${fmt(d.amount)}</td></tr>${expandedDonations.has(donKey(d)) && d.projectDescription ? `<tr class="detail-row"><td colspan="7"><div class="org-desc">${d.projectDescription.replace(/\.$/, '')}</div></td></tr>` : ''}`
  ).join('');
}
document.querySelectorAll('#main-table th[data-sort]').forEach(th => {
  th.addEventListener('click', () => {
    const k = th.dataset.sort;
    if (currentSort.key === k) currentSort.dir = currentSort.dir === 'asc' ? 'desc' : 'asc';
    else currentSort = { key: k, dir: (k==='amount'||k==='year') ? 'desc' : 'asc' };
    render();
  });
});
document.querySelectorAll('#mainDutchToggle .toggle-btn').forEach(btn => {
  btn.addEventListener('click', () => {
    document.querySelectorAll('#mainDutchToggle .toggle-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');
    render();
  });
});
['searchInput','categoryFilter','yearFilter','themeFilter'].forEach(id =>
  document.getElementById(id).addEventListener('input', render)
);
// Click to expand donation description
mainTbody.addEventListener('click', e => {
  const tr = e.target.closest('tr.don-row.has-desc');
  if (!tr) return;
  const key = tr.dataset.donkey;
  if (expandedDonations.has(key)) expandedDonations.delete(key);
  else expandedDonations.add(key);
  render();
});
render();
</script>
<footer>
  <div class="footer-inner">
    <div>
      <img src="data:image/webp;base64,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" alt="HVFC" class="footer-logo-img">
      <div class="f-legal" style="margin-top:.75rem;">
        HVFC International B.V. | KvK 75716674 | The Hague, NL<br>
        HVFC USA Inc. | TAX-ID 84-4737319 | New York, USA<br>
        Han Valk Consultancy B.V. | KvK 75716534 | Eursinge, NL
      </div>
    </div>
    <div>
      <div class="f-title">Connect</div>
      <div class="f-links">
        <a href="https://hvfc-international.com" target="_blank" rel="noopener">
          <svg width="14" height="14" fill="currentColor" viewBox="0 0 16 16"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm7.5-6.923c-.67.204-1.335.82-1.887 1.855A7.97 7.97 0 0 0 5.145 4H7.5V1.077zM4.09 4a9.267 9.267 0 0 1 .64-1.539 6.7 6.7 0 0 1 .597-.933A7.025 7.025 0 0 0 2.255 4H4.09zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a6.958 6.958 0 0 0-.656 2.5h2.49zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5H4.847zM8.5 5v2.5h2.99a12.495 12.495 0 0 0-.337-2.5H8.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5H4.51zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5H8.5zM5.145 12c.138.386.295.744.468 1.068.552 1.035 1.218 1.65 1.887 1.855V12H5.145zm.182 2.472a6.696 6.696 0 0 1-.597-.933A9.268 9.268 0 0 1 4.09 12H2.255a7.024 7.024 0 0 0 3.072 2.472zM3.82 11a13.652 13.652 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5H3.82zm6.853 3.472A7.024 7.024 0 0 0 13.745 12H11.91a9.27 9.27 0 0 1-.64 1.539 6.688 6.688 0 0 1-.597.933zM8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855.173-.324.33-.682.468-1.068H8.5zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.65 13.65 0 0 1-.312 2.5zm2.802-3.5a6.959 6.959 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5h2.49zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7.024 7.024 0 0 0-3.072-2.472c.218.284.418.598.597.933zM10.855 4a7.966 7.966 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4h2.355z"/></svg>
          hvfc-international.com
        </a><br>
        <a href="mailto:info@hvfc-international.com">
          <svg width="14" height="14" fill="currentColor" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757ZM16 11.801V4.697l-5.803 3.546L16 11.801Z"/></svg>
          info@hvfc-international.com
        </a><br>
        <a href="https://www.linkedin.com/company/hvfcinternational/" target="_blank" rel="noopener">
          <svg width="14" height="14" fill="currentColor" viewBox="0 0 16 16"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/></svg>
          LinkedIn
        </a>
      </div>
    </div>
    <div>
      <div class="f-title">Stay informed</div>
      <p style="margin:0 0 .5rem">Fundraising news, vacancies and upcoming webinars, straight to your inbox.</p>
      <a class="f-newsletter" href="https://tinyurl.com/HVFCmail" target="_blank" rel="noopener">Subscribe to newsletter &rarr;</a>
    </div>
  </div>
  <hr class="f-divider">
  <div class="f-bottom">
    &copy; 2026 HVFC International B.V. Data sourced from the publicly available Dutch Postcode Lottery Annual Reports.
  </div>
</footer>
</body>
</html>
