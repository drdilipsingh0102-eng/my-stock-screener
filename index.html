<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" />
  <title>Bharat Trade - NSE Stock Screener</title>
  
  <!-- Mobile & PWA Configuration -->
  <meta name="theme-color" content="#ea580c" />
  <meta name="mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
  <meta name="apple-mobile-web-app-title" content="Bharat Trade" />
  <link rel="apple-touch-icon" href="https://img.icons8.com/fluency/192/bullish.png" />

  <!-- Manifest via clean valid Data URI with standard web icons -->
  <link rel="manifest" href="data:application/manifest+json,%7B%22name%22%3A%22Bharat%20Trade%20NSE%20Screener%22%2C%22short_name%22%3A%22BharatTrade%22%2C%22start_url%22%3A%22.%2F%22%2C%22scope%22%3A%22.%2F%22%2C%22display%22%3A%22standalone%22%2C%22background_color%22%3A%22%23020617%22%2C%22theme_color%22%3A%22%23ea580c%22%2C%22icons%22%3A%5B%7B%22src%22%3A%22https%3A%2F%2Fimg.icons8.com%2Ffluency%2F192%2Fbullish.png%22%2C%22sizes%22%3A%22192x192%22%2C%22type%22%3A%22image%2Fpng%22%2C%22purpose%22%3A%22any%20maskable%22%7D%2C%7B%22src%22%3A%22https%3A%2F%2Fimg.icons8.com%2Ffluency%2F512%2Fbullish.png%22%2C%22sizes%22%3A%22512x512%22%2C%22type%22%3A%22image%2Fpng%22%2C%22purpose%22%3A%22any%20maskable%22%7D%5D%7D" />

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      -webkit-tap-highlight-color: transparent;
      user-select: none;
    }
    body {
      background-color: #020617;
      color: #f8fafc;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      overflow-x: hidden;
      min-height: 100vh;
      padding-bottom: env(safe-area-inset-bottom, 20px);
    }
    .mono { font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace; }
    
    .app-container {
      max-width: 480px;
      margin: 0 auto;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      position: relative;
      background: #020617;
      border-left: 1px solid #1e293b;
      border-right: 1px solid #1e293b;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 40;
      background: rgba(15, 23, 42, 0.96);
      backdrop-filter: blur(8px);
      border-bottom: 1px solid #1e293b;
      padding: 10px 14px;
    }
    .top-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .brand {
      display: flex;
      align-items: center;
      gap: 8px;
    }
    .brand-icon {
      width: 32px;
      height: 32px;
      border-radius: 8px;
      background: linear-gradient(135deg, #ea580c, #f59e0b);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      font-weight: 900;
    }
    .brand-title {
      font-size: 15px;
      font-weight: 800;
      letter-spacing: -0.3px;
    }
    .brand-sub {
      font-size: 10px;
      color: #94a3b8;
      display: flex;
      align-items: center;
      gap: 4px;
    }
    .dot-live {
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: #10b981;
      animation: pulse 1.5s infinite;
    }
    @keyframes pulse {
      0%, 100% { opacity: 1; transform: scale(1); }
      50% { opacity: 0.4; transform: scale(0.85); }
    }

    .header-actions {
      display: flex;
      align-items: center;
      gap: 6px;
    }
    .btn-live {
      padding: 5px 9px;
      border-radius: 6px;
      font-size: 11px;
      font-weight: 700;
      border: 1px solid #059669;
      background: rgba(6, 78, 59, 0.6);
      color: #6ee7b7;
      cursor: pointer;
    }
    .btn-paused {
      border-color: #be123c;
      background: rgba(136, 19, 55, 0.6);
      color: #fda4af;
    }
    .btn-install {
      padding: 5px 12px;
      border-radius: 6px;
      font-size: 11px;
      font-weight: 800;
      background: #ea580c;
      border: none;
      color: #fff;
      cursor: pointer;
      display: flex;
      align-items: center;
      gap: 4px;
      box-shadow: 0 0 12px rgba(234, 88, 12, 0.4);
    }

    .search-box {
      margin-top: 8px;
      position: relative;
    }
    .search-box input {
      width: 100%;
      background: #020617;
      border: 1px solid #334155;
      border-radius: 8px;
      padding: 7px 10px 7px 30px;
      font-size: 12px;
      color: #fff;
      outline: none;
    }
    .search-box input:focus { border-color: #ea580c; }
    .search-icon {
      position: absolute;
      left: 10px;
      top: 8px;
      width: 13px;
      height: 13px;
      stroke: #64748b;
    }

    .preset-chips {
      display: flex;
      gap: 6px;
      overflow-x: auto;
      padding: 8px 0 2px 0;
      scrollbar-width: none;
    }
    .preset-chips::-webkit-scrollbar { display: none; }
    .chip {
      padding: 4px 10px;
      border-radius: 20px;
      font-size: 11px;
      white-space: nowrap;
      border: 1px solid #334155;
      background: #090d16;
      color: #94a3b8;
      cursor: pointer;
    }
    .chip.active {
      background: #ea580c;
      color: #fff;
      border-color: #ea580c;
      font-weight: 700;
    }

    .sub-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 6px 14px;
      background: #0b1120;
      border-bottom: 1px solid #1e293b;
      font-size: 11px;
      color: #94a3b8;
    }
    .sub-bar select {
      background: #020617;
      border: 1px solid #334155;
      color: #cbd5e1;
      padding: 2px 6px;
      border-radius: 4px;
      font-size: 11px;
      outline: none;
    }

    .stock-list {
      flex: 1;
      padding: 10px 12px 80px 12px;
      display: flex;
      flex-direction: column;
      gap: 8px;
    }
    .stock-card {
      background: #0b1329;
      border: 1px solid #1e293b;
      border-radius: 12px;
      padding: 12px;
      cursor: pointer;
      transition: transform 0.1s, border-color 0.2s, background-color 0.2s;
    }
    .stock-card:active { transform: scale(0.98); }
    .flash-up { border-color: #10b981 !important; background: #064e3b33 !important; }
    .flash-down { border-color: #f43f5e !important; background: #88133733 !important; }

    .card-top {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
    }
    .stock-info {
      display: flex;
      align-items: center;
      gap: 8px;
    }
    .star-btn {
      background: none;
      border: none;
      font-size: 16px;
      cursor: pointer;
      color: #475569;
      padding: 2px;
    }
    .star-btn.starred { color: #f59e0b; }
    .stock-sym {
      font-size: 14px;
      font-weight: 800;
      color: #fff;
    }
    .stock-sector {
      font-size: 9px;
      background: #1e293b;
      color: #94a3b8;
      padding: 2px 5px;
      border-radius: 4px;
      margin-left: 4px;
    }
    .stock-name {
      font-size: 11px;
      color: #64748b;
      margin-top: 2px;
      max-width: 170px;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }
    .price-col {
      text-align: right;
    }
    .stock-price {
      font-size: 15px;
      font-weight: 800;
      color: #fff;
    }
    .stock-change {
      font-size: 11px;
      font-weight: 700;
      margin-top: 2px;
    }
    .up { color: #10b981; }
    .down { color: #f43f5e; }

    /* ACTIONABLE BUY RANGE AND SL/TARGET STRIP */
    .trade-setup-strip {
      margin-top: 8px;
      padding: 6px 10px;
      background: #020617;
      border: 1px solid #1e293b;
      border-radius: 8px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 11px;
    }
    .buy-range-tag {
      color: #38bdf8;
      font-weight: 800;
    }
    .sl-tgt-tag {
      color: #94a3b8;
      font-size: 10px;
    }
    .sl-tgt-tag strong {
      color: #f8fafc;
    }

    .card-bottom {
      margin-top: 8px;
      padding-top: 8px;
      border-top: 1px solid #1e293b;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 10.5px;
    }
    .card-metrics {
      display: flex;
      gap: 10px;
      color: #64748b;
    }
    .card-metrics span strong { color: #cbd5e1; }

    .badge-signal {
      padding: 2px 7px;
      border-radius: 20px;
      font-size: 9px;
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: 0.3px;
      border: 1px solid transparent;
    }
    .sig-strong-buy { background: #064e3b; color: #6ee7b7; border-color: #059669; }
    .sig-buy { background: #064e3b88; color: #a7f3d0; border-color: #047857; }
    .sig-sell { background: #88133788; color: #fecdd3; border-color: #be123c; }
    .sig-strong-sell { background: #881337; color: #fda4af; border-color: #e11d48; }
    .sig-neutral { background: #1e293b; color: #cbd5e1; border-color: #334155; }

    nav {
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      max-width: 480px;
      margin: 0 auto;
      height: 56px;
      background: rgba(15, 23, 42, 0.98);
      backdrop-filter: blur(10px);
      border-top: 1px solid #1e293b;
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      z-index: 50;
      padding-bottom: env(safe-area-inset-bottom, 0px);
    }
    .nav-btn {
      background: none;
      border: none;
      color: #64748b;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 3px;
      font-size: 10px;
      font-weight: 600;
      cursor: pointer;
    }
    .nav-btn.active { color: #ea580c; font-weight: 800; }
    .nav-btn svg { width: 18px; height: 18px; stroke-width: 2.2; }

    .modal-overlay {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.78);
      backdrop-filter: blur(4px);
      z-index: 60;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
    }
    .modal-sheet {
      background: #0f172a;
      border-top: 1px solid #334155;
      border-radius: 20px 20px 0 0;
      max-height: 85vh;
      overflow-y: auto;
      padding: 16px;
      padding-bottom: calc(env(safe-area-inset-bottom, 16px) + 20px);
    }
    .modal-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #1e293b;
      padding-bottom: 12px;
      margin-bottom: 12px;
    }
    .close-btn {
      background: #1e293b;
      border: none;
      color: #94a3b8;
      width: 28px;
      height: 28px;
      border-radius: 50%;
      cursor: pointer;
      font-weight: 800;
    }
    .chart-container {
      background: #020617;
      border: 1px solid #1e293b;
      border-radius: 12px;
      padding: 12px;
      margin-bottom: 12px;
    }
    .grid-2 {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 8px;
      margin-bottom: 12px;
    }
    .stat-box {
      background: #020617;
      border: 1px solid #1e293b;
      border-radius: 10px;
      padding: 10px;
      font-size: 11px;
    }
    .stat-title { color: #64748b; margin-bottom: 4px; }
    .stat-val { font-size: 13px; font-weight: 800; color: #f8fafc; }

    .alerts-container {
      padding: 14px;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .alert-card {
      background: #0b1329;
      border: 1px solid #1e293b;
      border-radius: 10px;
      padding: 12px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 12px;
    }
    .input-field {
      width: 100%;
      background: #020617;
      border: 1px solid #334155;
      padding: 8px;
      border-radius: 6px;
      color: #fff;
      font-size: 12px;
      margin-bottom: 8px;
      outline: none;
    }
  </style>
</head>
<body>

  <div class="app-container">
    <!-- HEADER -->
    <header>
      <div class="top-bar">
        <div class="brand">
          <div class="brand-icon">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5">
              <polyline points="22 7 13.5 15.5 8.5 10.5 2 17"></polyline>
              <polyline points="16 7 22 7 22 13"></polyline>
            </svg>
          </div>
          <div>
            <div class="brand-title">BHARAT TRADE</div>
            <div class="brand-sub">
              <span class="dot-live"></span>
              <span>NSE Live Feed</span>
              <span>•</span>
              <span id="stock-count-label">41 Stocks</span>
            </div>
          </div>
        </div>

        <div class="header-actions">
          <button id="toggle-stream-btn" class="btn-live">LIVE</button>
          <button id="install-pwa-btn" class="btn-install">
            <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3">
              <path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path>
              <polyline points="7 10 12 15 17 10"></polyline>
              <line x1="12" y1="15" x2="12" y2="3"></line>
            </svg>
            <span>Install</span>
          </button>
        </div>
      </div>

      <!-- SEARCH BOX -->
      <div class="search-box">
        <svg class="search-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <circle cx="11" cy="11" r="8"></circle>
          <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
        </svg>
        <input type="text" id="search-input" placeholder="Search Reliance, Tata, HDFC..." />
      </div>

      <!-- PRESET CHIPS -->
      <div class="preset-chips">
        <button class="chip active" data-preset="All">All Stocks</button>
        <button class="chip" data-preset="Top Gainers">🚀 Top Gainers</button>
        <button class="chip" data-preset="Top Losers">📉 Top Losers</button>
        <button class="chip" data-preset="Above VWAP">⚡ Above VWAP</button>
        <button class="chip" data-preset="Oversold">💎 RSI &lt; 35</button>
        <button class="chip" data-preset="High Delivery">📦 Delivery %</button>
      </div>
    </header>

    <!-- SUB-BAR -->
    <div class="sub-bar">
      <div>
        <span>Index: </span>
        <select id="index-select">
          <option value="All">All Indices</option>
          <option value="Nifty 50">Nifty 50</option>
          <option value="Bank Nifty">Bank Nifty</option>
          <option value="F&O Momentum">F&O Momentum</option>
        </select>
      </div>
      <div class="mono" id="screened-count-text">Screened: 41</div>
    </div>

    <!-- MAIN CONTENT CONTAINER -->
    <main class="stock-list" id="stock-list-container"></main>

    <!-- BOTTOM NAVIGATION -->
    <nav>
      <button class="nav-btn active" data-tab="screener" id="tab-screener">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><rect x="3" y="3" width="7" height="7"></rect><rect x="14" y="3" width="7" height="7"></rect><rect x="14" y="14" width="7" height="7"></rect><rect x="3" y="14" width="7" height="7"></rect></svg>
        <span>Screener</span>
      </button>
      <button class="nav-btn" data-tab="watchlist" id="tab-watchlist">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"></polygon></svg>
        <span id="watchlist-tab-label">Watchlist (4)</span>
      </button>
      <button class="nav-btn" data-tab="alerts" id="tab-alerts">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"></path><path d="M13.73 21a2 2 0 0 1-3.46 0"></path></svg>
        <span>Alerts</span>
      </button>
    </nav>
  </div>

  <!-- INTRADAY BREAKDOWN MODAL -->
  <div id="stock-modal" class="modal-overlay" style="display: none;">
    <div class="modal-sheet">
      <div class="modal-header">
        <div>
          <div style="display:flex; align-items:center; gap:8px;">
            <span id="modal-symbol" style="font-size:16px; font-weight:800; color:#fff;">RELIANCE</span>
            <span id="modal-sector" style="font-size:10px; background:#1e293b; color:#94a3b8; padding:2px 6px; border-radius:4px;">Energy</span>
          </div>
          <div id="modal-name" style="font-size:11px; color:#64748b; margin-top:2px;">Reliance Industries Ltd.</div>
        </div>
        <div style="display:flex; align-items:center; gap:12px;">
          <div style="text-align:right;">
            <div id="modal-price" class="mono" style="font-size:16px; font-weight:800; color:#fff;">₹2,980.50</div>
            <div id="modal-change" class="mono" style="font-size:11px; font-weight:700;">+1.45%</div>
          </div>
          <button class="close-btn" id="modal-close-btn">✕</button>
        </div>
      </div>

      <!-- 15-Min SVG Candlestick -->
      <div class="chart-container">
        <div style="display:flex; justify-content:space-between; font-size:11px; color:#94a3b8; margin-bottom:8px;">
          <strong style="color:#cbd5e1;">15-Min Candlesticks</strong>
          <span id="modal-hl" class="mono">High: ₹0 | Low: ₹0</span>
        </div>
        <svg id="candlestick-svg" width="100%" height="110" viewBox="0 0 400 110" preserveAspectRatio="none"></svg>
      </div>

      <!-- Technical Stats -->
      <div class="grid-2">
        <div class="stat-box">
          <div class="stat-title">Intraday VWAP</div>
          <div id="modal-vwap" class="stat-val mono" style="color:#f59e0b;">₹0.00</div>
        </div>
        <div class="stat-box">
          <div class="stat-title">Supertrend (7, 3)</div>
          <div id="modal-supertrend" class="stat-val">BULLISH</div>
        </div>
        <div class="stat-box">
          <div class="stat-title">Delivery %</div>
          <div id="modal-delivery" class="stat-val mono">54.2%</div>
        </div>
        <div class="stat-box">
          <div class="stat-title">F&O Lot Size</div>
          <div id="modal-lotsize" class="stat-val mono">250 Qty</div>
        </div>
      </div>

      <!-- Trade Setup Box (Buy Range, SL, Target) -->
      <div class="stat-box" style="margin-bottom:12px; border-color:#0284c7; background:#082f4922;">
        <div class="stat-title" style="color:#38bdf8; font-weight:bold; display:flex; justify-content:space-between; align-items:center;">
          <span>🎯 ACTIONABLE TRADE SETUP</span>
          <span id="modal-rr-ratio" style="font-size:10px; color:#a5f3fc; background:#0369a1; padding:2px 6px; border-radius:4px;">R:R 1:2.0</span>
        </div>
        <div style="display:grid; grid-template-columns: 1fr 1fr; gap:8px; margin-top:8px;" class="mono">
          <div style="background:#020617; padding:8px; border-radius:8px; border:1px solid #1e293b;">
            <div style="font-size:10px; color:#94a3b8;">Ideal Buy Range</div>
            <div id="modal-buy-range" style="color:#38bdf8; font-weight:800; font-size:12px; margin-top:2px;">₹0 - ₹0</div>
          </div>
          <div style="background:#020617; padding:8px; border-radius:8px; border:1px solid #1e293b;">
            <div style="font-size:10px; color:#f43f5e;">Stop Loss (SL)</div>
            <div id="modal-sl" style="color:#f43f5e; font-weight:800; font-size:12px; margin-top:2px;">₹0.00</div>
          </div>
          <div style="background:#020617; padding:8px; border-radius:8px; border:1px solid #1e293b;">
            <div style="font-size:10px; color:#10b981;">Target 1 (T1)</div>
            <div id="modal-t1" style="color:#10b981; font-weight:800; font-size:12px; margin-top:2px;">₹0.00</div>
          </div>
          <div style="background:#020617; padding:8px; border-radius:8px; border:1px solid #1e293b;">
            <div style="font-size:10px; color:#34d399;">Target 2 (T2)</div>
            <div id="modal-t2" style="color:#34d399; font-weight:800; font-size:12px; margin-top:2px;">₹0.00</div>
          </div>
        </div>
      </div>

      <!-- Pivot Levels -->
      <div class="stat-box" style="margin-bottom:14px;">
        <div class="stat-title" style="margin-bottom:8px; font-weight:bold; color:#cbd5e1;">Classic Pivot Levels (NSE)</div>
        <div style="display:flex; flex-direction:column; gap:5px; font-size:11px;" class="mono">
          <div style="display:flex; justify-content:space-between; color:#f43f5e;">
            <span>Resistance 1 (R1)</span><strong id="modal-r1">₹0.00</strong>
          </div>
          <div style="display:flex; justify-content:space-between; color:#f59e0b; background:#f59e0b22; padding:3px 6px; border-radius:4px;">
            <span>Pivot Point (PP)</span><strong id="modal-pp">₹0.00</strong>
          </div>
          <div style="display:flex; justify-content:space-between; color:#10b981;">
            <span>Support 1 (S1)</span><strong id="modal-s1">₹0.00</strong>
          </div>
        </div>
      </div>

      <button id="modal-dismiss-btn" style="width:100%; padding:10px; background:#ea580c; border:none; border-radius:10px; color:#fff; font-weight:700; font-size:12px; cursor:pointer;">
        Close Breakdown
      </button>
    </div>
  </div>

  <!-- APPLICATION LOGIC WITH NATIVE SERVICE WORKER -->
  <script>
    // Register separate sw.js file so Chrome validates PWA installability
    if ('serviceWorker' in navigator) {
      window.addEventListener('load', () => {
        navigator.serviceWorker.register('./sw.js')
          .then((reg) => console.log('SW Registered successfully:', reg.scope))
          .catch((err) => console.log('SW registration error:', err));
      });
    }

    // Comprehensive Indian Stock Universe (41 Stocks)
    const STOCKS_DATA = [
      { symbol: 'RELIANCE', name: 'Reliance Industries', sector: 'Energy & Oil', base: 2980.50, index: 'Nifty 50', lotSize: 250, pe: 28.4, deliveryPct: 54.2 },
      { symbol: 'TCS', name: 'Tata Consultancy Services', sector: 'IT Services', base: 4120.00, index: 'Nifty 50', lotSize: 175, pe: 31.8, deliveryPct: 62.1 },
      { symbol: 'HDFCBANK', name: 'HDFC Bank Ltd.', sector: 'Banking', base: 1650.25, index: 'Bank Nifty', lotSize: 550, pe: 19.5, deliveryPct: 58.7 },
      { symbol: 'ICICIBANK', name: 'ICICI Bank Ltd.', sector: 'Banking', base: 1245.80, index: 'Bank Nifty', lotSize: 700, pe: 18.2, deliveryPct: 64.3 },
      { symbol: 'INFY', name: 'Infosys Ltd.', sector: 'IT Services', base: 1880.40, index: 'Nifty 50', lotSize: 400, pe: 27.6, deliveryPct: 60.5 },
      { symbol: 'BHARTIARTL', name: 'Bharti Airtel', sector: 'Telecom', base: 1675.00, index: 'Nifty 50', lotSize: 475, pe: 54.1, deliveryPct: 51.0 },
      { symbol: 'SBIN', name: 'State Bank of India', sector: 'Banking', base: 825.60, index: 'Bank Nifty', lotSize: 1500, pe: 10.8, deliveryPct: 48.2 },
      { symbol: 'ITC', name: 'ITC Ltd.', sector: 'FMCG', base: 512.40, index: 'Nifty 50', lotSize: 1600, pe: 29.3, deliveryPct: 66.8 },
      { symbol: 'LT', name: 'Larsen & Toubro', sector: 'Infrastructure', base: 3620.00, index: 'Nifty 50', lotSize: 175, pe: 34.5, deliveryPct: 49.3 },
      { symbol: 'HINDUNILVR', name: 'Hindustan Unilever', sector: 'FMCG', base: 2680.00, index: 'Nifty 50', lotSize: 300, pe: 58.2, deliveryPct: 65.4 },
      { symbol: 'TATAMOTORS', name: 'Tata Motors', sector: 'Automobile', base: 985.30, index: 'Nifty 50', lotSize: 575, pe: 11.2, deliveryPct: 42.5 },
      { symbol: 'MARUTI', name: 'Maruti Suzuki', sector: 'Automobile', base: 12450.00, index: 'Nifty 50', lotSize: 50, pe: 26.7, deliveryPct: 55.4 },
      { symbol: 'SUNPHARMA', name: 'Sun Pharma', sector: 'Pharma', base: 1860.00, index: 'Nifty 50', lotSize: 350, pe: 36.4, deliveryPct: 58.2 },
      { symbol: 'TATASTEEL', name: 'Tata Steel', sector: 'Metals', base: 156.40, index: 'Nifty 50', lotSize: 5500, pe: 38.1, deliveryPct: 41.6 },
      { symbol: 'KOTAKBANK', name: 'Kotak Mahindra Bank', sector: 'Banking', base: 1795.00, index: 'Bank Nifty', lotSize: 400, pe: 21.0, deliveryPct: 59.0 },
      { symbol: 'AXISBANK', name: 'Axis Bank', sector: 'Banking', base: 1180.00, index: 'Bank Nifty', lotSize: 625, pe: 13.8, deliveryPct: 52.4 },
      { symbol: 'BAJFINANCE', name: 'Bajaj Finance', sector: 'Financials', base: 7320.00, index: 'Nifty 50', lotSize: 125, pe: 32.5, deliveryPct: 47.9 },
      { symbol: 'NTPC', name: 'NTPC Ltd.', sector: 'Power', base: 420.50, index: 'Nifty 50', lotSize: 1500, pe: 17.6, deliveryPct: 56.1 },
      { symbol: 'POWERGRID', name: 'Power Grid Corp', sector: 'Power', base: 345.00, index: 'Nifty 50', lotSize: 1800, pe: 19.8, deliveryPct: 67.2 },
      { symbol: 'TITAN', name: 'Titan Company', sector: 'Retail', base: 3580.00, index: 'Nifty 50', lotSize: 175, pe: 86.4, deliveryPct: 52.8 },
      { symbol: 'ADANIENT', name: 'Adani Enterprises', sector: 'Conglomerate', base: 3050.00, index: 'Nifty 50', lotSize: 300, pe: 98.2, deliveryPct: 34.6 },
      { symbol: 'ADANIPORTS', name: 'Adani Ports', sector: 'Infrastructure', base: 1420.00, index: 'Nifty 50', lotSize: 400, pe: 32.7, deliveryPct: 45.2 },
      { symbol: 'M&M', name: 'Mahindra & Mahindra', sector: 'Automobile', base: 2920.00, index: 'Nifty 50', lotSize: 350, pe: 30.5, deliveryPct: 53.6 },
      { symbol: 'HCLTECH', name: 'HCL Tech', sector: 'IT Services', base: 1820.00, index: 'Nifty 50', lotSize: 350, pe: 26.8, deliveryPct: 63.4 },
      { symbol: 'WIPRO', name: 'Wipro Ltd.', sector: 'IT Services', base: 540.00, index: 'Nifty 50', lotSize: 1500, pe: 23.4, deliveryPct: 59.8 },
      { symbol: 'JSWSTEEL', name: 'JSW Steel', sector: 'Metals', base: 995.00, index: 'Nifty 50', lotSize: 675, pe: 29.8, deliveryPct: 44.5 },
      { symbol: 'HINDALCO', name: 'Hindalco', sector: 'Metals', base: 730.00, index: 'Nifty 50', lotSize: 1400, pe: 16.4, deliveryPct: 43.1 },
      { symbol: 'CIPLA', name: 'Cipla Ltd.', sector: 'Pharma', base: 1610.00, index: 'Nifty 50', lotSize: 650, pe: 28.5, deliveryPct: 58.7 },
      { symbol: 'DRREDDY', name: 'Dr. Reddys Labs', sector: 'Pharma', base: 6650.00, index: 'Nifty 50', lotSize: 125, pe: 20.3, deliveryPct: 55.8 },
      { symbol: 'BPCL', name: 'BPCL', sector: 'Energy & Oil', base: 350.00, index: 'Nifty 50', lotSize: 1800, pe: 8.8, deliveryPct: 47.1 },
      { symbol: 'PNB', name: 'Punjab National Bank', sector: 'Banking', base: 112.50, index: 'Bank Nifty', lotSize: 8000, pe: 9.2, deliveryPct: 41.5 },
      { symbol: 'BANKBARODA', name: 'Bank of Baroda', sector: 'Banking', base: 254.00, index: 'Bank Nifty', lotSize: 2925, pe: 6.8, deliveryPct: 47.2 },
      { symbol: 'AUBANK', name: 'AU Small Finance Bank', sector: 'Banking', base: 645.00, index: 'Bank Nifty', lotSize: 1000, pe: 24.5, deliveryPct: 43.8 },
      { symbol: 'FEDERALBNK', name: 'Federal Bank', sector: 'Banking', base: 198.50, index: 'Bank Nifty', lotSize: 5000, pe: 11.4, deliveryPct: 53.6 },
      { symbol: 'ZOMATO', name: 'Zomato Ltd.', sector: 'Consumer Tech', base: 268.50, index: 'F&O Momentum', lotSize: 2000, pe: 95.0, deliveryPct: 38.4 },
      { symbol: 'HAL', name: 'Hindustan Aeronautics', sector: 'Defense', base: 4560.00, index: 'F&O Momentum', lotSize: 150, pe: 38.8, deliveryPct: 45.1 },
      { symbol: 'BEL', name: 'Bharat Electronics', sector: 'Defense', base: 295.00, index: 'F&O Momentum', lotSize: 2850, pe: 46.5, deliveryPct: 51.4 },
      { symbol: 'DIXON', name: 'Dixon Technologies', sector: 'Electronics', base: 14200.00, index: 'F&O Momentum', lotSize: 50, pe: 88.5, deliveryPct: 35.2 },
      { symbol: 'TRENT', name: 'Trent Ltd.', sector: 'Retail', base: 7850.00, index: 'F&O Momentum', lotSize: 100, pe: 145.0, deliveryPct: 46.3 },
      { symbol: 'BSE', name: 'BSE Ltd.', sector: 'Financials', base: 4650.00, index: 'F&O Momentum', lotSize: 125, pe: 58.0, deliveryPct: 39.8 },
      { symbol: 'POLYCAB', name: 'Polycab India', sector: 'Infrastructure', base: 6720.00, index: 'F&O Momentum', lotSize: 100, pe: 49.2, deliveryPct: 54.7 }
    ];

    function makeCandles(base, count = 18) {
      const arr = [];
      let c = base * 0.99;
      for (let i = 0; i < count; i++) {
        const delta = (Math.random() - 0.48) * (c * 0.004);
        const open = c;
        const close = +(c + delta).toFixed(2);
        const high = +(Math.max(open, close) + Math.random() * (c * 0.002)).toFixed(2);
        const low = +(Math.min(open, close) - Math.random() * (c * 0.002)).toFixed(2);
        c = close;
        arr.push({ open, high, low, close });
      }
      return arr;
    }

    function calcSignal(rsi, price, vwap) {
      let score = 0;
      if (rsi > 60) score += 1;
      if (rsi < 40) score -= 1;
      if (price > vwap) score += 1.5; else score -= 1.5;
      if (score >= 2) return 'Strong Buy';
      if (score >= 0.5) return 'Buy';
      if (score <= -2) return 'Strong Sell';
      if (score <= -0.5) return 'Sell';
      return 'Neutral';
    }

    // Dynamic Calculation of Actionable Buy Range, Stop Loss, and Targets
    function calculateTradeLevels(price, low, high, vwap) {
      const pivot = (high + low + price) / 3;
      const s1 = 2 * pivot - high;
      const atrEstimate = Math.max(price * 0.008, (high - low) * 0.7);
      
      const buyMin = +(Math.min(price * 0.994, Math.max(s1, vwap * 0.998))).toFixed(2);
      const buyMax = +(Math.max(price * 1.002, price)).toFixed(2);
      const stopLoss = +(buyMin - atrEstimate * 0.9).toFixed(2);
      
      const riskPerShare = Math.max(price * 0.006, buyMax - stopLoss);
      const target1 = +(buyMax + riskPerShare * 1.5).toFixed(2);
      const target2 = +(buyMax + riskPerShare * 2.5).toFixed(2);
      
      return { buyMin, buyMax, stopLoss, target1, target2, rrRatio: '1:2.0' };
    }

    let stocks = STOCKS_DATA.map(s => {
      const changePct = +(Math.random() * 3.6 - 1.6).toFixed(2);
      const price = +(s.base * (1 + changePct / 100)).toFixed(2);
      const open = s.base;
      const high = +(Math.max(price, open) + price * 0.008).toFixed(2);
      const low = +(Math.min(price, open) - price * 0.008).toFixed(2);
      const vwap = +(price * (1 + (Math.random() * 0.006 - 0.003))).toFixed(2);
      const rsi = +(40 + Math.random() * 28).toFixed(1);
      const supertrend = price > vwap ? 'BULL' : 'BEAR';
      const tradeLevels = calculateTradeLevels(price, low, high, vwap);
      return {
        ...s,
        price,
        open,
        high,
        low,
        vwap,
        rsi,
        supertrend,
        changePct,
        signal: calcSignal(rsi, price, vwap),
        tradeLevels,
        tickDir: 0,
        candles: makeCandles(price)
      };
    });

    let isLive = true;
    let activeTab = 'screener';
    let currentPreset = 'All';
    let currentIndex = 'All';
    let searchQuery = '';
    let watchlist = ['RELIANCE', 'HDFCBANK', 'TCS', 'TATAMOTORS'];
    let selectedStock = null;
    let deferredPrompt = null;

    const stockContainer = document.getElementById('stock-list-container');
    const screenedCountText = document.getElementById('screened-count-text');
    const toggleStreamBtn = document.getElementById('toggle-stream-btn');
    const installBtn = document.getElementById('install-pwa-btn');
    const searchInput = document.getElementById('search-input');
    const indexSelect = document.getElementById('index-select');
    const presetChips = document.querySelectorAll('.chip');
    const modalEl = document.getElementById('stock-modal');

    function render() {
      if (activeTab === 'alerts') {
        renderAlertsView();
        return;
      }

      const filtered = stocks.filter(s => {
        if (activeTab === 'watchlist' && !watchlist.includes(s.symbol)) return false;
        if (searchQuery && !s.symbol.toLowerCase().includes(searchQuery.toLowerCase()) && !s.name.toLowerCase().includes(searchQuery.toLowerCase())) return false;
        if (currentIndex !== 'All' && s.index !== currentIndex) return false;
        if (currentPreset === 'Top Gainers' && s.changePct <= 0) return false;
        if (currentPreset === 'Top Losers' && s.changePct >= 0) return false;
        if (currentPreset === 'Above VWAP' && s.price <= s.vwap) return false;
        if (currentPreset === 'Oversold' && s.rsi >= 35) return false;
        if (currentPreset === 'High Delivery' && s.deliveryPct < 55) return false;
        return true;
      }).sort((a, b) => {
        if (currentPreset === 'Top Gainers') return b.changePct - a.changePct;
        if (currentPreset === 'Top Losers') return a.changePct - b.changePct;
        if (currentPreset === 'High Delivery') return b.deliveryPct - a.deliveryPct;
        return 0;
      });

      screenedCountText.textContent = `Screened: ${filtered.length}`;

      if (filtered.length === 0) {
        stockContainer.innerHTML = `
          <div style="text-align:center; padding:50px 20px; color:#64748b; font-size:12px;">
            <p>No stocks match your current criteria.</p>
            <button onclick="resetFilters()" style="margin-top:12px; padding:6px 14px; background:#1e293b; border:1px solid #334155; color:#ea580c; border-radius:6px; font-weight:700;">Reset Filters</button>
          </div>`;
        return;
      }

      stockContainer.innerHTML = filtered.map(s => {
        const isPos = s.changePct >= 0;
        const isStarred = watchlist.includes(s.symbol);
        const flashClass = s.tickDir === 1 ? 'flash-up' : s.tickDir === -1 ? 'flash-down' : '';
        const sigSlug = s.signal.toLowerCase().replace(' ', '-');
        const tl = s.tradeLevels;

        return `
          <div class="stock-card ${flashClass}" onclick="openModal('${s.symbol}')">
            <div class="card-top">
              <div class="stock-info">
                <button class="star-btn ${isStarred ? 'starred' : ''}" onclick="toggleWatch('${s.symbol}', event)">★</button>
                <div>
                  <div style="display:flex; align-items:center;">
                    <span class="stock-sym">${s.symbol}</span>
                    <span class="stock-sector">${s.sector.split(' ')[0]}</span>
                  </div>
                  <div class="stock-name">${s.name}</div>
                </div>
              </div>
              <div class="price-col">
                <div class="stock-price mono">₹${s.price.toLocaleString('en-IN', { minimumFractionDigits: 2 })}</div>
                <div class="stock-change mono ${isPos ? 'up' : 'down'}">
                  ${isPos ? '▲ +' : '▼ '}${s.changePct.toFixed(2)}%
                </div>
              </div>
            </div>

            <!-- ACTIONABLE BUY RANGE AND SL/TGT STRIP -->
            <div class="trade-setup-strip mono">
              <span class="buy-range-tag">Buy: ₹${tl.buyMin} - ₹${tl.buyMax}</span>
              <span class="sl-tgt-tag">SL: <strong>₹${tl.stopLoss}</strong> | TGT: <strong>₹${tl.target1}</strong></span>
            </div>

            <div class="card-bottom">
              <div class="card-metrics mono">
                <span>VWAP: <strong style="color:${s.price >= s.vwap ? '#10b981' : '#f43f5e'}">₹${s.vwap}</strong></span>
                <span>RSI: <strong>${s.rsi}</strong></span>
              </div>
              <span class="badge-signal sig-${sigSlug}">${s.signal}</span>
            </div>
          </div>
        `;
      }).join('');
    }

    function renderAlertsView() {
      screenedCountText.textContent = `Alerts: Active`;
      stockContainer.innerHTML = `
        <div class="alerts-container">
          <div style="background:#0b1329; border:1px solid #1e293b; padding:14px; border-radius:12px;">
            <div style="font-size:13px; font-weight:800; color:#fff; margin-bottom:4px;">Stock Price & RSI Triggers</div>
            <div style="font-size:11px; color:#94a3b8; margin-bottom:12px;">Set notification thresholds for intraday swings.</div>
            
            <label style="font-size:11px; color:#cbd5e1; display:block; margin-bottom:4px;">Select Stock:</label>
            <select class="input-field" id="alert-stock-select">
              ${stocks.map(s => `<option value="${s.symbol}">${s.symbol} (₹${s.price})</option>`).join('')}
            </select>

            <label style="font-size:11px; color:#cbd5e1; display:block; margin-bottom:4px;">Trigger Price (₹):</label>
            <input type="number" id="alert-price-input" class="input-field" placeholder="e.g. 3000" />

            <button onclick="saveDemoAlert()" style="width:100%; padding:10px; background:#ea580c; border:none; border-radius:8px; color:#fff; font-weight:700; font-size:12px; cursor:pointer;">
              Add Active Alert
            </button>
          </div>

          <div style="font-size:12px; font-weight:700; color:#cbd5e1; margin-top:8px;">Active Watch Alerts</div>
          <div class="alert-card">
            <div>
              <strong style="color:#fff;">RELIANCE</strong>
              <div style="color:#94a3b8; font-size:10px;">Alert when price crosses &gt; ₹3,020</div>
            </div>
            <span style="color:#10b981; font-weight:700; font-size:11px;">ACTIVE</span>
          </div>
        </div>
      `;
    }

    window.saveDemoAlert = function() {
      const stock = document.getElementById('alert-stock-select').value;
      const pr = document.getElementById('alert-price-input').value;
      if (!pr) return;
      alertNotification(`Alert saved for ${stock} at ₹${pr}!`);
      document.getElementById('alert-price-input').value = '';
    };

    function alertNotification(text) {
      const banner = document.createElement('div');
      banner.textContent = text;
      banner.style.cssText = 'position:fixed; top:70px; left:50%; transform:translateX(-50%); background:#059669; color:#fff; padding:8px 16px; border-radius:20px; font-size:11px; font-weight:700; z-index:99; box-shadow:0 4px 12px rgba(0,0,0,0.5);';
      document.body.appendChild(banner);
      setTimeout(() => banner.remove(), 2500);
    }

    window.resetFilters = function() {
      currentPreset = 'All';
      currentIndex = 'All';
      searchQuery = '';
      searchInput.value = '';
      indexSelect.value = 'All';
      presetChips.forEach(c => c.classList.toggle('active', c.dataset.preset === 'All'));
      render();
    };

    window.toggleWatch = function(sym, e) {
      if (e) e.stopPropagation();
      if (watchlist.includes(sym)) {
        watchlist = watchlist.filter(x => x !== sym);
      } else {
        watchlist.push(sym);
      }
      document.getElementById('watchlist-tab-label').textContent = `Watchlist (${watchlist.length})`;
      render();
    };

    window.openModal = function(sym) {
      selectedStock = stocks.find(s => s.symbol === sym);
      if (!selectedStock) return;

      document.getElementById('modal-symbol').textContent = selectedStock.symbol;
      document.getElementById('modal-sector').textContent = selectedStock.sector;
      document.getElementById('modal-name').textContent = selectedStock.name;
      document.getElementById('modal-price').textContent = '₹' + selectedStock.price.toLocaleString('en-IN', { minimumFractionDigits: 2 });
      
      const changeEl = document.getElementById('modal-change');
      changeEl.textContent = (selectedStock.changePct >= 0 ? '+' : '') + selectedStock.changePct.toFixed(2) + '%';
      changeEl.className = 'mono ' + (selectedStock.changePct >= 0 ? 'up' : 'down');

      document.getElementById('modal-hl').textContent = `High: ₹${selectedStock.high} | Low: ₹${selectedStock.low}`;
      document.getElementById('modal-vwap').textContent = '₹' + selectedStock.vwap;
      
      const stEl = document.getElementById('modal-supertrend');
      stEl.textContent = selectedStock.supertrend === 'BULL' ? 'BULLISH' : 'BEARISH';
      stEl.style.color = selectedStock.supertrend === 'BULL' ? '#10b981' : '#f43f5e';

      document.getElementById('modal-delivery').textContent = selectedStock.deliveryPct + '%';
      document.getElementById('modal-lotsize').textContent = selectedStock.lotSize + ' Qty';

      const tl = selectedStock.tradeLevels;
      document.getElementById('modal-buy-range').textContent = `₹${tl.buyMin} - ₹${tl.buyMax}`;
      document.getElementById('modal-sl').textContent = `₹${tl.stopLoss}`;
      document.getElementById('modal-t1').textContent = `₹${tl.target1}`;
      document.getElementById('modal-t2').textContent = `₹${tl.target2}`;
      document.getElementById('modal-rr-ratio').textContent = `R:R ${tl.rrRatio}`;

      const h = selectedStock.high, l = selectedStock.low, c = selectedStock.price;
      const pp = +((h + l + c) / 3).toFixed(2);
      const r1 = +(2 * pp - l).toFixed(2);
      const s1 = +(2 * pp - h).toFixed(2);
      document.getElementById('modal-pp').textContent = '₹' + pp;
      document.getElementById('modal-r1').textContent = '₹' + r1;
      document.getElementById('modal-s1').textContent = '₹' + s1;

      const svg = document.getElementById('candlestick-svg');
      const candles = selectedStock.candles;
      const minP = Math.min(...candles.map(c => c.low));
      const maxP = Math.max(...candles.map(c => c.high));
      const range = maxP - minP || 1;
      const w = 400 / candles.length;
      
      svg.innerHTML = candles.map((c, i) => {
        const isGreen = c.close >= c.open;
        const x = i * w + w / 2;
        const yH = 100 - ((c.high - minP) / range) * 90;
        const yL = 100 - ((c.low - minP) / range) * 90;
        const yO = 100 - ((c.open - minP) / range) * 90;
        const yC = 100 - ((c.close - minP) / range) * 90;
        const top = Math.min(yO, yC);
        const height = Math.max(2, Math.abs(yC - yO));
        const color = isGreen ? '#10b981' : '#f43f5e';
        return `
          <line x1="${x}" y1="${yH}" x2="${x}" y2="${yL}" stroke="${color}" stroke-width="1.2" />
          <rect x="${x - w * 0.3}" y="${top}" width="${w * 0.6}" height="${height}" fill="${color}" rx="1" />
        `;
      }).join('');

      modalEl.style.display = 'flex';
    };

    function closeModal() {
      modalEl.style.display = 'none';
      selectedStock = null;
    }
    document.getElementById('modal-close-btn').onclick = closeModal;
    document.getElementById('modal-dismiss-btn').onclick = closeModal;
    modalEl.onclick = (e) => { if (e.target === modalEl) closeModal(); };

    presetChips.forEach(chip => {
      chip.addEventListener('click', () => {
        presetChips.forEach(c => c.classList.remove('active'));
        chip.classList.add('active');
        currentPreset = chip.dataset.preset;
        render();
      });
    });

    searchInput.addEventListener('input', (e) => {
      searchQuery = e.target.value;
      render();
    });

    indexSelect.addEventListener('change', (e) => {
      currentIndex = e.target.value;
      render();
    });

    const navButtons = document.querySelectorAll('.nav-btn');
    navButtons.forEach(btn => {
      btn.addEventListener('click', () => {
        navButtons.forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        activeTab = btn.dataset.tab;
        render();
      });
    });

    toggleStreamBtn.onclick = () => {
      isLive = !isLive;
      toggleStreamBtn.textContent = isLive ? 'LIVE' : 'PAUSED';
      toggleStreamBtn.className = isLive ? 'btn-live' : 'btn-live btn-paused';
    };

    // Live Tick Updates
    setInterval(() => {
      if (!isLive) return;
      const count = Math.floor(Math.random() * 3) + 2;
      const chosen = new Set();
      while (chosen.size < count) chosen.add(Math.floor(Math.random() * stocks.length));

      stocks = stocks.map((s, idx) => {
        if (!chosen.has(idx)) return { ...s, tickDir: 0 };
        const tickPct = (Math.random() * 0.003 - 0.0014);
        const delta = +(s.price * tickPct).toFixed(2);
        const newPrice = +(s.price + delta).toFixed(2);
        const newHigh = Math.max(s.high, newPrice);
        const newLow = Math.min(s.low, newPrice);
        const newChangePct = +(((newPrice - s.open) / s.open) * 100).toFixed(2);
        const newRsi = +Math.max(15, Math.min(85, s.rsi + (Math.random() * 0.6 - 0.28))).toFixed(1);
        const newVwap = +((s.vwap * 0.998) + (newPrice * 0.002)).toFixed(2);
        const newTradeLevels = calculateTradeLevels(newPrice, newLow, newHigh, newVwap);

        return {
          ...s,
          price: newPrice,
          high: newHigh,
          low: newLow,
          changePct: newChangePct,
          rsi: newRsi,
          vwap: newVwap,
          supertrend: newPrice > newVwap ? 'BULL' : 'BEAR',
          signal: calcSignal(newRsi, newPrice, newVwap),
          tradeLevels: newTradeLevels,
          tickDir: delta > 0 ? 1 : delta < 0 ? -1 : 0
        };
      });

      if (activeTab !== 'alerts') {
        render();
      }

      if (selectedStock) {
        const updated = stocks.find(s => s.symbol === selectedStock.symbol);
        if (updated) {
          document.getElementById('modal-price').textContent = '₹' + updated.price.toLocaleString('en-IN', { minimumFractionDigits: 2 });
          document.getElementById('modal-vwap').textContent = '₹' + updated.vwap;
          const utl = updated.tradeLevels;
          document.getElementById('modal-buy-range').textContent = `₹${utl.buyMin} - ₹${utl.buyMax}`;
          document.getElementById('modal-sl').textContent = `₹${utl.stopLoss}`;
          document.getElementById('modal-t1').textContent = `₹${utl.target1}`;
          document.getElementById('modal-t2').textContent = `₹${utl.target2}`;
        }
      }
    }, 1200);

    // Chrome PWA Install Prompt Handler
    window.addEventListener('beforeinstallprompt', (e) => {
      e.preventDefault();
      deferredPrompt = e;
      installBtn.style.display = 'flex';
    });

    installBtn.onclick = () => {
      if (deferredPrompt) {
        deferredPrompt.prompt();
        deferredPrompt.userChoice.then((choice) => {
          if (choice.outcome === 'accepted') {
            console.log('Bharat Trade PWA installed');
          }
          deferredPrompt = null;
        });
      } else {
        alertNotification('Tap 3 dots (⋮) in Chrome > "Add to Home screen"');
      }
    };

    render();
  </script>
</body>
</html>
