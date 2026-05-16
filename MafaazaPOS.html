<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mafaaza Chicken POS</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@2.44.0/tabler-icons.min.css">
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --red:#B8272B;--gold:#FFD700;--gold-dark:#7a2000;
  --bg:#f5f5f0;--bg2:#fff;--bg3:#f0ede6;
  --text:#1a1a1a;--text2:#666;--text3:#999;
  --border:rgba(0,0,0,0.12);--border2:rgba(0,0,0,0.22);
  --success-bg:#f0fdf4;--success-text:#166534;
  --danger-bg:#fef2f2;--danger-text:#991b1b;
  --warning-bg:#fffbeb;--warning-text:#92400e;
  --info-bg:#eff6ff;--info-text:#1e40af;
  --radius:8px;--radius-lg:12px;
}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:var(--bg);color:var(--text);min-height:100vh}
.app{display:flex;flex-direction:column;height:100vh;overflow:hidden}
/* TOPBAR */
.topbar{background:var(--red);display:flex;align-items:center;justify-content:space-between;padding:0 16px;height:50px;flex-shrink:0;box-shadow:0 2px 8px rgba(0,0,0,.2)}
.brand{display:flex;align-items:center;gap:8px;color:#fff;font-weight:600;font-size:14px}
.bdot{width:8px;height:8px;background:var(--gold);border-radius:50%}
.nav{display:flex;gap:3px}
.ntab{padding:6px 12px;border-radius:5px;border:none;font-size:12px;cursor:pointer;background:rgba(255,255,255,.12);color:#fff;font-family:inherit;transition:background .15s;display:flex;align-items:center;gap:5px}
.ntab.active{background:var(--gold);color:var(--gold-dark);font-weight:600}
.ntab:hover:not(.active){background:rgba(255,255,255,.22)}
.tright{display:flex;align-items:center;gap:10px;font-size:12px;color:rgba(255,255,255,.85)}
.clk{color:var(--gold);font-weight:600;font-size:13px}
/* SCREENS */
.screen{flex:1;display:none;overflow:hidden}
.screen.active{display:flex;flex-direction:column}
/* LOGIN */
.login-wrap{display:flex;align-items:center;justify-content:center;height:100%;background:linear-gradient(135deg,#fff5f5 0%,#fafaf8 100%)}
.lcard{background:#fff;border:1px solid var(--border);border-radius:var(--radius-lg);padding:32px 28px;width:340px;text-align:center;box-shadow:0 4px 24px rgba(0,0,0,.08)}
.llogo{font-size:40px;margin-bottom:10px}
.ltitle{font-size:18px;font-weight:700;color:var(--text);margin-bottom:4px}
.lsub{font-size:12px;color:var(--text3);margin-bottom:20px}
.ugrid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:12px;max-height:200px;overflow-y:auto}
.ubtn{padding:10px 8px;border-radius:var(--radius);border:1px solid var(--border);background:#fafaf8;cursor:pointer;font-size:12px;font-family:inherit;color:var(--text);transition:all .15s}
.ubtn:hover{border-color:var(--red);color:var(--red)}
.ubtn.sel{border-color:var(--red);color:var(--red);background:#fff5f5;font-weight:600}
.osel,.rsel,.sel-input{height:36px;border:1px solid var(--border);border-radius:var(--radius);padding:0 10px;font-size:13px;background:#fafaf8;color:var(--text);font-family:inherit;width:100%}
.osel{margin-bottom:12px}
.lbtn{width:100%;padding:12px;background:var(--red);color:#fff;border:none;border-radius:var(--radius);font-size:14px;font-weight:600;cursor:pointer;font-family:inherit;transition:background .15s}
.lbtn:hover{background:#9e1f22}
/* POS */
.pos-body{flex:1;display:grid;grid-template-columns:1fr 320px;overflow:hidden}
.lcol{display:flex;flex-direction:column;overflow:hidden;background:var(--bg)}
.sbar{padding:10px 14px;background:#fff;border-bottom:1px solid var(--border);display:flex;gap:8px;align-items:center}
.srch{flex:1;height:34px;padding:0 12px;border:1px solid var(--border);border-radius:var(--radius);font-size:13px;background:var(--bg3);color:var(--text);font-family:inherit}
.srch:focus{outline:none;border-color:var(--red)}
.catsrow{display:flex;gap:6px;overflow-x:auto;padding:10px 14px;background:#fff;border-bottom:1px solid var(--border);scrollbar-width:none}
.catsrow::-webkit-scrollbar{display:none}
.cpill{padding:5px 12px;border-radius:20px;border:1px solid var(--border);font-size:12px;cursor:pointer;white-space:nowrap;background:#fff;color:var(--text2);font-family:inherit;transition:all .15s}
.cpill.active{background:var(--red);color:#fff;border-color:var(--red);font-weight:600}
.cpill:hover:not(.active){border-color:var(--red);color:var(--red)}
.mgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(130px,1fr));gap:8px;padding:12px 14px;overflow-y:auto;flex:1}
.mcard{background:#fff;border-radius:var(--radius);border:1px solid var(--border);padding:12px;cursor:pointer;transition:all .15s;position:relative}
.mcard:hover{border-color:var(--red);box-shadow:0 2px 8px rgba(184,39,43,.1)}
.mcard:active{transform:scale(.97)}
.mcard.oos{opacity:.45;cursor:not-allowed;pointer-events:none}
.mico{font-size:28px;text-align:center;margin-bottom:6px}
.mname{font-size:12px;font-weight:600;color:var(--text);line-height:1.3}
.mprice{font-size:13px;color:var(--red);font-weight:700;margin-top:4px}
.mstk{font-size:10px;color:var(--text3);margin-top:2px}
.mbadge{position:absolute;top:6px;right:6px;background:var(--gold);color:var(--gold-dark);font-size:9px;font-weight:700;padding:2px 5px;border-radius:4px}
.oobadge{position:absolute;top:6px;right:6px;background:var(--danger-bg);color:var(--danger-text);font-size:9px;font-weight:600;padding:2px 5px;border-radius:4px}
.inctag{position:absolute;top:6px;left:6px;background:var(--red);color:#fff;font-size:9px;font-weight:700;padding:2px 5px;border-radius:4px}
/* CART */
.rcol{background:#fff;border-left:1px solid var(--border);display:flex;flex-direction:column}
.chdr{padding:12px 16px;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between}
.cordn{font-size:13px;font-weight:700;color:var(--text)}
.cmeta{font-size:11px;color:var(--text3);margin-top:2px}
.tgrp{display:flex;gap:4px}
.tbtn{padding:4px 8px;border-radius:5px;border:1px solid var(--border);font-size:11px;cursor:pointer;background:#fafaf8;color:var(--text2);font-family:inherit;transition:all .15s}
.tbtn.active{background:var(--red);color:#fff;border-color:var(--red)}
.clist{flex:1;overflow-y:auto;padding:6px 0}
.cempty{display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;color:var(--text3);font-size:13px;gap:8px}
.citem{padding:10px 16px;border-bottom:1px solid var(--border)}
.citem-top{display:flex;justify-content:space-between;align-items:flex-start;gap:6px}
.ciname{font-size:12px;font-weight:600;color:var(--text);flex:1}
.cisub{font-size:12px;color:var(--red);font-weight:700;white-space:nowrap}
.cictrl{display:flex;align-items:center;gap:8px;margin-top:6px}
.qbtn{width:24px;height:24px;border-radius:50%;border:1px solid var(--border);background:#fafaf8;cursor:pointer;font-size:14px;display:flex;align-items:center;justify-content:center;color:var(--text);font-family:inherit;transition:background .15s}
.qbtn:hover{background:var(--bg3)}
.qnum{font-size:13px;font-weight:700;min-width:20px;text-align:center;color:var(--text)}
.notein{font-size:11px;border:none;background:var(--bg3);color:var(--text2);border-radius:4px;padding:3px 8px;width:100%;font-family:inherit;margin-top:5px}
.cfoot{padding:12px 16px;border-top:1px solid var(--border);background:#fafaf8}
.srow{display:flex;justify-content:space-between;font-size:12px;margin-bottom:4px;color:var(--text2)}
.stotal{display:flex;justify-content:space-between;font-size:15px;font-weight:700;color:var(--text);margin-bottom:12px;padding-top:8px;border-top:1px solid var(--border)}
.dinrow{display:flex;gap:6px;margin-bottom:8px}
.dinp{flex:1;height:32px;padding:0 10px;border:1px solid var(--border);border-radius:var(--radius);font-size:12px;font-family:inherit;background:#fff;color:var(--text)}
.dapl{padding:0 12px;height:32px;border-radius:var(--radius);border:1px solid var(--border);background:#fff;font-size:12px;cursor:pointer;font-family:inherit;color:var(--text)}
.paybtn{width:100%;padding:12px;background:var(--red);color:#fff;border:none;border-radius:var(--radius);font-size:14px;font-weight:700;cursor:pointer;font-family:inherit;transition:background .15s}
.paybtn:hover:not(:disabled){background:#9e1f22}
.paybtn:disabled{background:#ccc;cursor:not-allowed}
/* OVERLAY / MODAL */
.overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);align-items:center;justify-content:center;z-index:200}
.overlay.open{display:flex}
.modal{background:#fff;border-radius:var(--radius-lg);padding:24px;border:1px solid var(--border);box-shadow:0 8px 40px rgba(0,0,0,.15);width:300px}
.modal-lg{width:380px}
.mtitle{font-size:15px;font-weight:700;margin-bottom:14px;color:var(--text)}
.mtotal{font-size:32px;font-weight:700;color:var(--red);text-align:center;margin-bottom:16px}
.pmgrid{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:14px}
.pmbtn{padding:12px 8px;border-radius:var(--radius);border:1px solid var(--border);background:#fafaf8;cursor:pointer;font-size:12px;font-family:inherit;color:var(--text);transition:all .15s;display:flex;flex-direction:column;align-items:center;gap:4px;font-weight:500}
.pmbtn.sel{border-color:var(--red);background:#fff5f5;color:var(--red);font-weight:700}
.cin{width:100%;height:40px;padding:0 12px;border:1px solid var(--border);border-radius:var(--radius);font-size:16px;font-weight:600;font-family:inherit;color:var(--text);background:#fff;margin-bottom:10px}
.cin:focus{outline:none;border-color:var(--red)}
.kemrow{background:var(--success-bg);border-radius:var(--radius);padding:10px 14px;display:flex;justify-content:space-between;margin-bottom:12px}
.macts{display:flex;gap:8px}
.cbtn2{flex:1;padding:10px;border-radius:var(--radius);border:1px solid var(--border);background:#fafaf8;cursor:pointer;font-size:13px;font-family:inherit;color:var(--text)}
.okbtn{flex:2;padding:10px;border-radius:var(--radius);border:none;background:var(--red);color:#fff;cursor:pointer;font-size:13px;font-weight:700;font-family:inherit}
/* RECEIPT */
.rcpt-paper{background:#fff;border:1px dashed #bbb;border-radius:6px;padding:16px 18px;margin-bottom:14px;font-family:'Courier New',monospace;font-size:12px;color:#111;max-height:320px;overflow-y:auto}
.rpc{text-align:center;margin-bottom:3px}
.rpsep{border-top:1px dashed #bbb;margin:6px 0}
.rprow{display:flex;justify-content:space-between;margin:2px 0}
.rpsm{font-size:10px;color:#555}
.print-acts{display:flex;gap:8px;margin-bottom:10px}
.act-btn{flex:1;padding:9px;border-radius:var(--radius);border:none;font-size:12px;font-weight:600;cursor:pointer;font-family:inherit;display:flex;align-items:center;justify-content:center;gap:5px}
.print-btn{background:var(--red);color:#fff}
.wa-btn{background:#25D366;color:#fff}
.sheets-btn{background:#0F9D58;color:#fff}
/* LAPORAN */
.rscreen{flex:1;overflow-y:auto;padding:16px}
.rhdr{display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;flex-wrap:wrap;gap:8px}
.rtitle{font-size:16px;font-weight:700;color:var(--text)}
.rcontrols{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
.rsel{height:32px;border:1px solid var(--border);border-radius:var(--radius);padding:0 8px;font-size:12px;background:#fff;color:var(--text);font-family:inherit;width:auto}
.mgcards{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:16px}
.mcard2{background:#fff;border:1px solid var(--border);border-radius:var(--radius);padding:14px}
.mlbl{font-size:11px;color:var(--text2);margin-bottom:4px}
.mval{font-size:20px;font-weight:700;color:var(--text)}
.msub{font-size:11px;color:var(--text3);margin-top:2px}
.sec{font-size:13px;font-weight:700;color:var(--text);margin-bottom:8px;margin-top:4px}
.chart-wrap{background:#fff;border:1px solid var(--border);border-radius:var(--radius);padding:14px;margin-bottom:16px}
.tmlist{display:flex;flex-direction:column;gap:5px;margin-bottom:16px}
.tmitem{display:flex;align-items:center;gap:8px;padding:8px 12px;background:#fff;border:1px solid var(--border);border-radius:var(--radius)}
.tmbar-wrap{background:var(--bg3);border-radius:4px;height:6px;flex:1;overflow:hidden}
.tmbar{height:6px;background:var(--red);border-radius:4px}
.txntbl{width:100%;border-collapse:collapse;font-size:12px;background:#fff;border-radius:var(--radius);overflow:hidden;border:1px solid var(--border)}
.txntbl th{text-align:left;padding:10px 12px;color:var(--text2);background:var(--bg3);border-bottom:1px solid var(--border);font-weight:600;font-size:11px}
.txntbl td{padding:9px 12px;border-bottom:1px solid var(--border);color:var(--text)}
.txntbl tr:hover td{background:var(--bg3)}
.sbadge{padding:3px 8px;border-radius:12px;font-size:10px;font-weight:700}
.sdone{background:var(--success-bg);color:var(--success-text)}
.svoid{background:var(--danger-bg);color:var(--danger-text)}
.void-act{padding:3px 10px;border-radius:4px;border:1px solid #fca5a5;background:var(--danger-bg);font-size:11px;cursor:pointer;font-family:inherit;color:var(--danger-text);font-weight:600}
/* STOK */
.stscreen{flex:1;overflow-y:auto;padding:16px}
.sttbl{width:100%;border-collapse:collapse;font-size:12px;background:#fff;border-radius:var(--radius);overflow:hidden;border:1px solid var(--border)}
.sttbl th{text-align:left;padding:10px 12px;color:var(--text2);background:var(--bg3);border-bottom:1px solid var(--border);font-weight:600;font-size:11px}
.sttbl td{padding:8px 12px;border-bottom:1px solid var(--border);color:var(--text)}
.stkbar-w{background:var(--bg3);border-radius:4px;height:6px;flex:1;overflow:hidden}
.stkbar{height:6px;border-radius:4px}
.stkin{width:60px;height:28px;border:1px solid var(--border);border-radius:var(--radius);text-align:center;font-size:12px;font-family:inherit;background:#fafaf8;color:var(--text);padding:0 4px}
.adjbtn{padding:4px 10px;border-radius:var(--radius);border:1px solid var(--border);background:#fafaf8;font-size:11px;cursor:pointer;font-family:inherit;color:var(--text);font-weight:600;transition:background .15s}
.adjbtn:hover{background:var(--bg3)}
/* EDITOR */
.escreen{flex:1;overflow-y:auto;padding:16px}
.etabs{display:flex;gap:5px;margin-bottom:16px;border-bottom:1px solid var(--border);padding-bottom:10px;flex-wrap:wrap}
.etab{padding:7px 16px;border-radius:var(--radius);border:1px solid var(--border);font-size:12px;cursor:pointer;font-family:inherit;color:var(--text2);background:#fafaf8;transition:all .15s;font-weight:500}
.etab.active{background:var(--red);color:#fff;border-color:var(--red);font-weight:700}
.etbl{width:100%;border-collapse:collapse;font-size:12px;background:#fff;border-radius:var(--radius);overflow:hidden;border:1px solid var(--border)}
.etbl th{text-align:left;padding:10px 12px;color:var(--text2);background:var(--bg3);border-bottom:1px solid var(--border);font-weight:600;font-size:11px}
.etbl td{padding:8px 12px;border-bottom:1px solid var(--border);color:var(--text)}
.ein{width:100%;height:28px;border:1px solid var(--border);border-radius:4px;padding:0 6px;font-size:12px;font-family:inherit;background:#fafaf8;color:var(--text)}
.ein:focus{outline:none;border-color:var(--red)}
.delbtn{padding:4px 10px;border-radius:4px;border:1px solid #fca5a5;background:var(--danger-bg);font-size:11px;cursor:pointer;font-family:inherit;color:var(--danger-text);font-weight:600}
.savbtn{padding:4px 10px;border-radius:4px;border:none;background:var(--red);color:#fff;font-size:11px;cursor:pointer;font-family:inherit;font-weight:600}
.addbtn{padding:8px 16px;border-radius:var(--radius);border:none;background:var(--red);color:#fff;font-size:12px;cursor:pointer;font-family:inherit;font-weight:700;display:flex;align-items:center;gap:5px}
.epanel{display:none}.epanel.active{display:block}
/* GDS */
.gds-step{background:var(--bg3);border-radius:var(--radius);padding:14px;margin-bottom:12px;border:1px solid var(--border)}
.gds-step-title{font-size:13px;font-weight:700;color:var(--text);margin-bottom:8px}
.gds-inp{width:100%;height:34px;border:1px solid var(--border);border-radius:var(--radius);padding:0 10px;font-size:12px;font-family:inherit;background:#fff;color:var(--text);margin-bottom:8px}
.gds-code{background:#fff;border-radius:4px;padding:10px;font-family:'Courier New',monospace;font-size:10px;color:var(--text2);margin-bottom:8px;word-break:break-all;border:1px solid var(--border);white-space:pre-wrap;line-height:1.5}
.gds-status{font-size:12px;padding:8px 12px;border-radius:var(--radius);text-align:center;margin-top:8px;font-weight:500}
/* NOTIF */
.notif{position:fixed;bottom:16px;left:50%;transform:translateX(-50%);background:#1a1a1a;color:#fff;font-size:12px;padding:8px 18px;border-radius:24px;z-index:999;opacity:0;transition:opacity .2s;pointer-events:none;white-space:nowrap;box-shadow:0 4px 12px rgba(0,0,0,.2)}
.notif.show{opacity:1}
@media print{
  .topbar,.nav,.tright{display:none!important}
  body{background:#fff}
  .app{display:block;height:auto}
}
</style>
</head>
<body>
<div class="app" id="app">
<div class="topbar">
  <div class="brand"><div class="bdot"></div>🍗 Mafaaza Chicken POS</div>
  <div class="nav">
    <button class="ntab active" onclick="goS('pos')"><i class="ti ti-cash-register"></i> Kasir</button>
    <button class="ntab" onclick="goS('stok')"><i class="ti ti-box"></i> Stok</button>
    <button class="ntab" onclick="goS('laporan')"><i class="ti ti-chart-bar"></i> Laporan</button>
    <button class="ntab" onclick="goS('editor')"><i class="ti ti-settings"></i> Editor</button>
    <button class="ntab" onclick="logout()" title="Logout"><i class="ti ti-logout"></i></button>
  </div>
  <div class="tright">
    <span id="tCashier">-</span>
    <span style="opacity:.4">|</span>
    <span id="tOutlet" style="color:var(--gold);font-weight:700">-</span>
    <span class="clk" id="clk">--:--</span>
  </div>
</div>

<!-- LOGIN -->
<div class="screen active" id="loginScreen">
  <div class="login-wrap">
    <div class="lcard">
      <div class="llogo">🍗</div>
      <div class="ltitle">Mafaaza Chicken POS</div>
      <div class="lsub">Pilih kasir dan outlet untuk memulai</div>
      <div class="ugrid" id="ugrid"></div>
      <select class="osel" id="osel"><option value="">-- Pilih Outlet --</option></select>
      <button class="lbtn" onclick="doLogin()"><i class="ti ti-login"></i> Masuk ke Sesi</button>
    </div>
  </div>
</div>

<!-- POS -->
<div class="screen" id="posScreen">
  <div class="pos-body">
    <div class="lcol">
      <div class="sbar">
        <i class="ti ti-search" style="color:var(--text3)"></i>
        <input class="srch" id="srchIn" placeholder="Cari menu..." oninput="renderMenu()">
        <span id="stokAlert" style="font-size:11px;color:var(--danger-text)"></span>
      </div>
      <div class="catsrow" id="catsRow"></div>
      <div class="mgrid" id="menuGrid"></div>
    </div>
    <div class="rcol">
      <div class="chdr">
        <div>
          <div class="cordn" id="ordNum">Order #MC-001</div>
          <div class="cmeta" id="cartMeta">-</div>
        </div>
        <div class="tgrp">
          <button class="tbtn active" onclick="setType(this,'Dine In')">Dine In</button>
          <button class="tbtn" onclick="setType(this,'Take Away')">Take Away</button>
          <button class="tbtn" onclick="setType(this,'Online')">Online</button>
        </div>
      </div>
      <div class="clist" id="cartList">
        <div class="cempty" id="cempty"><i class="ti ti-shopping-bag" style="font-size:36px;opacity:.3"></i><span>Pilih menu untuk memulai</span></div>
      </div>
      <div class="cfoot">
        <div class="dinrow">
          <input class="dinp" id="discIn" placeholder="Kode promo / diskon %">
          <button class="dapl" onclick="applyDisc()">Terapkan</button>
        </div>
        <div class="srow"><span>Subtotal</span><span id="stEl">Rp 0</span></div>
        <div class="srow"><span>Diskon</span><span id="dsEl" style="color:var(--success-text)">-Rp 0</span></div>
        <div class="stotal"><span>Total</span><span id="ttEl">Rp 0</span></div>
        <button class="paybtn" id="payBtn" disabled onclick="openPay()"><i class="ti ti-credit-card"></i> Bayar Sekarang</button>
      </div>
    </div>
  </div>
</div>

<!-- STOK -->
<div class="screen" id="stokScreen">
  <div class="stscreen">
    <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:16px">
      <div style="font-size:16px;font-weight:700"><i class="ti ti-box"></i> Manajemen Stok</div>
      <select class="rsel" id="stokOSel" onchange="renderStok()" style="width:160px"></select>
    </div>
    <table class="sttbl">
      <thead><tr><th style="width:28%">Menu</th><th style="width:12%">Kategori</th><th style="width:20%">Level Stok</th><th style="width:8%">Qty</th><th style="width:10%">Min</th><th style="width:12%">Status</th><th style="width:10%">Aksi</th></tr></thead>
      <tbody id="stokBody"></tbody>
    </table>
  </div>
</div>

<!-- LAPORAN -->
<div class="screen" id="laporanScreen">
  <div class="rscreen">
    <div class="rhdr">
      <div class="rtitle"><i class="ti ti-chart-bar"></i> Laporan Penjualan</div>
      <div class="rcontrols">
        <select class="rsel" id="rPeriod" onchange="renderReport()">
          <option value="today">Hari Ini</option>
          <option value="week">7 Hari Terakhir</option>
          <option value="month">Bulan Ini</option>
        </select>
        <select class="rsel" id="rOutlet" onchange="renderReport()"><option value="all">Semua Outlet</option></select>
        <button class="adjbtn" onclick="exportCSV()"><i class="ti ti-download"></i> Export CSV</button>
      </div>
    </div>
    <div class="mgcards" id="mgcards"></div>
    <div class="sec">Tren Omzet</div>
    <div class="chart-wrap"><canvas id="trendChart" height="100"></canvas></div>
    <div class="sec">Top Menu Terlaris</div>
    <div class="tmlist" id="tmlist"></div>
    <div class="sec">Riwayat Transaksi</div>
    <table class="txntbl">
      <thead><tr><th>Order</th><th>Waktu</th><th>Outlet</th><th>Kasir</th><th>Tipe</th><th>Total</th><th>Metode</th><th>Status</th><th>Aksi</th></tr></thead>
      <tbody id="txnBody"></tbody>
    </table>
  </div>
</div>

<!-- EDITOR -->
<div class="screen" id="editorScreen">
  <div class="escreen">
    <div class="etabs">
      <button class="etab active" onclick="switchETab(this,'emenu')"><i class="ti ti-tools-kitchen"></i> Menu</button>
      <button class="etab" onclick="switchETab(this,'ekasir')"><i class="ti ti-users"></i> Kasir</button>
      <button class="etab" onclick="switchETab(this,'eoutlet')"><i class="ti ti-map-pin"></i> Outlet</button>
      <button class="etab" onclick="switchETab(this,'egds')"><i class="ti ti-brand-google"></i> Google Sheets</button>
    </div>
    <div class="epanel active" id="emenu">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
        <span style="font-size:12px;color:var(--text2)" id="menuCount"></span>
        <button class="addbtn" onclick="addMenuItem()"><i class="ti ti-plus"></i> Tambah Menu</button>
      </div>
      <table class="etbl"><thead><tr><th style="width:8%">Ikon</th><th style="width:28%">Nama Menu</th><th style="width:16%">Kategori</th><th style="width:14%">Harga</th><th style="width:12%">Min Stok</th><th style="width:22%">Aksi</th></tr></thead><tbody id="menuEditorBody"></tbody></table>
    </div>
    <div class="epanel" id="ekasir">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
        <span style="font-size:12px;color:var(--text2)" id="kasirCount"></span>
        <button class="addbtn" onclick="addKasir()"><i class="ti ti-plus"></i> Tambah Kasir</button>
      </div>
      <table class="etbl"><thead><tr><th style="width:40%">Nama Kasir</th><th style="width:30%">Role</th><th style="width:30%">Aksi</th></tr></thead><tbody id="kasirBody"></tbody></table>
    </div>
    <div class="epanel" id="eoutlet">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
        <span style="font-size:12px;color:var(--text2)" id="outletCount"></span>
        <button class="addbtn" onclick="addOutlet()"><i class="ti ti-plus"></i> Tambah Outlet</button>
      </div>
      <table class="etbl"><thead><tr><th style="width:35%">Nama Outlet</th><th style="width:28%">Kota / Area</th><th style="width:18%">Status</th><th style="width:19%">Aksi</th></tr></thead><tbody id="outletBody"></tbody></table>
    </div>
    <div class="epanel" id="egds">
      <div class="gds-step">
        <div class="gds-step-title"><i class="ti ti-number-1"></i> Buat Google Apps Script</div>
        <p style="font-size:12px;color:var(--text2);margin-bottom:10px">Buka Google Sheets baru → <b>Extensions → Apps Script</b> → paste kode berikut, ganti <code>SHEET_ID</code>, lalu <b>Deploy → Web App → Anyone</b>:</p>
        <div class="gds-code">function doPost(e) {
  var ss = SpreadsheetApp.openById('SHEET_ID');
  var sh = ss.getSheetByName('Transaksi') || ss.insertSheet('Transaksi');
  var d = JSON.parse(e.postData.contents);
  sh.appendRow([d.id, d.time, d.outlet, d.cashier, d.type, d.total, d.method, new Date()]);
  return ContentService.createTextOutput('ok');
}</div>
      </div>
      <div class="gds-step">
        <div class="gds-step-title"><i class="ti ti-number-2"></i> Masukkan URL Web App</div>
        <input class="gds-inp" id="gdsUrl" placeholder="https://script.google.com/macros/s/...">
        <button class="savbtn" style="width:100%;padding:8px;font-size:13px" onclick="testGDS()"><i class="ti ti-plug"></i> Test & Simpan Koneksi</button>
        <div id="gdsStatus"></div>
      </div>
      <div class="gds-step">
        <div class="gds-step-title"><i class="ti ti-number-3"></i> Status Sinkronisasi</div>
        <div style="display:flex;justify-content:space-between;font-size:12px;margin-bottom:6px"><span style="color:var(--text2)">Status Koneksi</span><span id="gdsConn" style="color:var(--danger-text);font-weight:600">Belum dikonfigurasi</span></div>
        <div style="display:flex;justify-content:space-between;font-size:12px;margin-bottom:6px"><span style="color:var(--text2)">Transaksi tersync</span><span id="gdsSyncCount" style="font-weight:600">0</span></div>
        <div style="display:flex;justify-content:space-between;font-size:12px"><span style="color:var(--text2)">Terakhir sync</span><span id="gdsLastSync" style="color:var(--text3)">-</span></div>
        <button class="savbtn" style="width:100%;padding:8px;font-size:13px;margin-top:10px" onclick="syncAllGDS()"><i class="ti ti-refresh"></i> Sync Semua Transaksi Sekarang</button>
      </div>
    </div>
  </div>
</div>

<!-- PAY MODAL -->
<div class="overlay" id="payModal">
  <div class="modal">
    <div class="mtitle">Metode Pembayaran</div>
    <div class="mtotal" id="mTotal">Rp 0</div>
    <div class="pmgrid">
      <button class="pmbtn sel" onclick="selPay(this,'Tunai')"><i class="ti ti-cash" style="font-size:24px"></i>Tunai</button>
      <button class="pmbtn" onclick="selPay(this,'QRIS')"><i class="ti ti-qrcode" style="font-size:24px"></i>QRIS</button>
      <button class="pmbtn" onclick="selPay(this,'Transfer')"><i class="ti ti-building-bank" style="font-size:24px"></i>Transfer</button>
      <button class="pmbtn" onclick="selPay(this,'EDC')"><i class="ti ti-device-tablet" style="font-size:24px"></i>EDC / Card</button>
    </div>
    <div id="cashSec">
      <label style="font-size:12px;color:var(--text2);display:block;margin-bottom:5px">Uang diterima dari pelanggan</label>
      <input class="cin" type="number" id="cashIn" placeholder="0" oninput="calcKem()">
      <div class="kemrow" id="kemRow" style="display:none">
        <span style="font-size:12px;color:var(--success-text)">Kembalian</span>
        <span style="font-size:14px;font-weight:700;color:var(--success-text)" id="kemVal">Rp 0</span>
      </div>
    </div>
    <div class="macts">
      <button class="cbtn2" onclick="closePay()">Batal</button>
      <button class="okbtn" onclick="confirmPay()"><i class="ti ti-check"></i> Konfirmasi Bayar</button>
    </div>
  </div>
</div>

<!-- RECEIPT MODAL -->
<div class="overlay" id="rcptModal">
  <div class="modal modal-lg">
    <div class="mtitle">🧾 Struk Transaksi</div>
    <div class="rcpt-paper" id="rcptPaper"></div>
    <div class="print-acts">
      <button class="act-btn wa-btn" onclick="sendWA()"><i class="ti ti-brand-whatsapp"></i> WA</button>
      <button class="act-btn sheets-btn" onclick="syncTxnGDS()"><i class="ti ti-brand-google"></i> Sheets</button>
      <button class="act-btn print-btn" onclick="doPrint()"><i class="ti ti-printer"></i> Cetak</button>
    </div>
    <button class="cbtn2" style="width:100%" onclick="closeReceipt()"><i class="ti ti-plus"></i> Selesai &amp; Transaksi Baru</button>
  </div>
</div>

<!-- VOID MODAL -->
<div class="overlay" id="voidModal">
  <div class="modal">
    <div class="mtitle">⚠️ Void / Refund Transaksi</div>
    <div id="voidInfo" style="background:var(--danger-bg);border-radius:var(--radius);padding:12px;margin-bottom:12px;font-size:13px;border:1px solid #fca5a5"></div>
    <label style="font-size:12px;color:var(--text2);display:block;margin-bottom:6px">Alasan void:</label>
    <select class="osel" id="voidReason" style="margin-bottom:14px">
      <option>Salah order</option><option>Pelanggan batal</option><option>Kesalahan harga</option><option>Lainnya</option>
    </select>
    <div class="macts">
      <button class="cbtn2" onclick="closeVoid()">Batal</button>
      <button class="okbtn" style="background:#dc2626" onclick="confirmVoid()"><i class="ti ti-x"></i> Konfirmasi Void</button>
    </div>
  </div>
</div>

<div class="notif" id="notif"></div>

<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
<script>
let MENU=[
  {id:1,name:'Ayam Geprek Gemoy',price:15000,cat:'Geprek',icon:'🍗',badge:'Best Seller',minStok:10},
  {id:2,name:'Ayam Geprek Crispy',price:14000,cat:'Geprek',icon:'🍗',minStok:10},
  {id:3,name:'Geprek Double',price:22000,cat:'Geprek',icon:'🍗',badge:'Hemat',minStok:5},
  {id:4,name:'Ayam Original 1pc',price:10000,cat:'Ayam Goreng',icon:'🍖',minStok:15},
  {id:5,name:'Ayam Original 2pc',price:18000,cat:'Ayam Goreng',icon:'🍖',badge:'Hemat',minStok:8},
  {id:6,name:'Ayam Spicy 1pc',price:11000,cat:'Ayam Goreng',icon:'🌶️',minStok:10},
  {id:7,name:'Nasi Putih',price:4000,cat:'Nasi & Extras',icon:'🍚',minStok:30},
  {id:8,name:'Nasi Uduk',price:5000,cat:'Nasi & Extras',icon:'🍚',minStok:20},
  {id:9,name:'Tahu Goreng',price:3000,cat:'Nasi & Extras',icon:'🟡',minStok:20},
  {id:10,name:'Tempe Goreng',price:3000,cat:'Nasi & Extras',icon:'🟤',minStok:20},
  {id:11,name:'Es Teh Manis',price:5000,cat:'Minuman',icon:'🧋',minStok:50},
  {id:12,name:'Es Jeruk',price:6000,cat:'Minuman',icon:'🍊',minStok:30},
  {id:13,name:'Air Mineral',price:3000,cat:'Minuman',icon:'💧',minStok:50},
  {id:14,name:'Sambal Extra',price:2000,cat:'Tambahan',icon:'🌶️',minStok:30},
  {id:15,name:'Kerupuk',price:2000,cat:'Tambahan',icon:'🍘',minStok:30},
];
let KASIRS=['Andi','Budi','Citra','Dewi'];
let OUTLETS_LIST=['Cibinong','Bogor Kota','Depok','Bekasi'];
let OUTLET_META={Cibinong:{kota:'Bogor',aktif:true},'Bogor Kota':{kota:'Bogor',aktif:true},Depok:{kota:'Depok',aktif:true},Bekasi:{kota:'Bekasi',aktif:true}};
let stok={};
OUTLETS_LIST.forEach(o=>{stok[o]={};MENU.forEach(m=>{stok[o][m.id]=Math.floor(Math.random()*40)+10});stok[o][3]=2;stok[o][6]=0});
let orderCounters={};OUTLETS_LIST.forEach(o=>orderCounters[o]=1);
const DEMO=[
  {id:'MC-001',time:'08:14',outlet:'Cibinong',cashier:'Andi',type:'Dine In',total:37000,sub:37000,disc:0,method:'Tunai',status:'done',dayOffset:0,items:[{name:'Ayam Geprek Gemoy',qty:2,price:15000},{name:'Es Teh Manis',qty:1,price:5000},{name:'Nasi Putih',qty:1,price:4000}]},
  {id:'MC-002',time:'09:02',outlet:'Cibinong',cashier:'Budi',type:'Take Away',total:29000,sub:29000,disc:0,method:'QRIS',status:'done',dayOffset:0,items:[{name:'Ayam Original 2pc',qty:1,price:18000},{name:'Nasi Putih',qty:2,price:4000}]},
  {id:'MC-001',time:'08:45',outlet:'Bogor Kota',cashier:'Citra',type:'Dine In',total:44000,sub:44000,disc:0,method:'EDC',status:'done',dayOffset:0,items:[{name:'Geprek Double',qty:1,price:22000},{name:'Es Jeruk',qty:2,price:6000},{name:'Nasi Uduk',qty:2,price:5000}]},
  {id:'MC-002',time:'09:33',outlet:'Depok',cashier:'Dewi',type:'Take Away',total:25000,sub:25000,disc:0,method:'Tunai',status:'done',dayOffset:0,items:[{name:'Ayam Geprek Crispy',qty:1,price:14000},{name:'Nasi Putih',qty:1,price:4000},{name:'Air Mineral',qty:2,price:3000}]},
  {id:'MC-003',time:'10:22',outlet:'Cibinong',cashier:'Andi',type:'Online',total:52000,sub:52000,disc:0,method:'Transfer',status:'done',dayOffset:0,items:[{name:'Ayam Original 2pc',qty:2,price:18000},{name:'Es Teh Manis',qty:2,price:5000},{name:'Kerupuk',qty:3,price:2000}]},
  {id:'MC-001',time:'14:05',outlet:'Bekasi',cashier:'Andi',type:'Take Away',total:33000,sub:33000,disc:0,method:'Tunai',status:'done',dayOffset:-1,items:[{name:'Geprek Double',qty:1,price:22000},{name:'Es Jeruk',qty:1,price:6000},{name:'Nasi Putih',qty:1,price:4000}]},
  {id:'MC-002',time:'16:30',outlet:'Bogor Kota',cashier:'Citra',type:'Dine In',total:58000,sub:60000,disc:2000,method:'Transfer',status:'done',dayOffset:-2,items:[{name:'Ayam Geprek Gemoy',qty:2,price:15000},{name:'Geprek Double',qty:1,price:22000},{name:'Es Teh Manis',qty:2,price:5000}]},
  {id:'MC-003',time:'11:20',outlet:'Cibinong',cashier:'Andi',type:'Online',total:19000,sub:19000,disc:0,method:'QRIS',status:'done',dayOffset:-3,items:[{name:'Ayam Original 1pc',qty:1,price:10000},{name:'Nasi Uduk',qty:1,price:5000},{name:'Air Mineral',qty:2,price:3000}]},
  {id:'MC-004',time:'13:45',outlet:'Depok',cashier:'Dewi',type:'Dine In',total:47000,sub:47000,disc:0,method:'EDC',status:'done',dayOffset:-4,items:[{name:'Ayam Geprek Crispy',qty:2,price:14000},{name:'Es Jeruk',qty:1,price:6000},{name:'Nasi Uduk',qty:2,price:5000}]},
  {id:'MC-005',time:'09:50',outlet:'Bekasi',cashier:'Andi',type:'Take Away',total:28000,sub:28000,disc:0,method:'Tunai',status:'done',dayOffset:-5,items:[{name:'Ayam Original 2pc',qty:1,price:18000},{name:'Nasi Putih',qty:2,price:4000}]},
  {id:'MC-006',time:'15:15',outlet:'Cibinong',cashier:'Citra',type:'Dine In',total:39000,sub:39000,disc:0,method:'QRIS',status:'done',dayOffset:-6,items:[{name:'Ayam Geprek Gemoy',qty:1,price:15000},{name:'Ayam Spicy 1pc',qty:2,price:11000},{name:'Nasi Putih',qty:1,price:4000}]},
];
let transactions=[...DEMO];
let cart=[],currentOutlet='',currentCashier='',orderType='Dine In',discPct=0,payMethod='Tunai',currentCat='Semua',lastTxn=null,voidTargetId=null;
let gdsUrl='',gdsSyncCount=0,trendChartInst=null;
const fmt=n=>'Rp '+Math.round(n).toLocaleString('id-ID');
function notif(msg){const n=document.getElementById('notif');n.textContent=msg;n.classList.add('show');setTimeout(()=>n.classList.remove('show'),2200)}
function updateClock(){document.getElementById('clk').textContent=new Date().toLocaleTimeString('id-ID',{hour:'2-digit',minute:'2-digit'})}
function buildLoginUI(){
  document.getElementById('ugrid').innerHTML=KASIRS.map(k=>`<button class="ubtn" onclick="selUser(this,'${k}')">👤 ${k}</button>`).join('');
  document.getElementById('osel').innerHTML='<option value="">-- Pilih Outlet --</option>'+OUTLETS_LIST.filter(o=>OUTLET_META[o]?.aktif!==false).map(o=>`<option>${o}</option>`).join('');
}
function selUser(btn,n){document.querySelectorAll('.ubtn').forEach(b=>b.classList.remove('sel'));btn.classList.add('sel');currentCashier=n}
function doLogin(){const o=document.getElementById('osel').value;if(!currentCashier){notif('Pilih kasir terlebih dahulu');return}if(!o){notif('Pilih outlet terlebih dahulu');return}currentOutlet=o;document.getElementById('tCashier').textContent=currentCashier;document.getElementById('tOutlet').textContent=o;goS('pos')}
function logout(){currentCashier='';currentOutlet='';cart=[];discPct=0;buildLoginUI();document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));document.getElementById('loginScreen').classList.add('active');document.querySelectorAll('.ntab').forEach((b,i)=>b.classList.toggle('active',i===0));document.getElementById('tCashier').textContent='-';document.getElementById('tOutlet').textContent='-';notif('Logout berhasil')}
function goS(name){if(!currentCashier){notif('Silakan login terlebih dahulu');return}document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));document.querySelectorAll('.ntab').forEach(b=>b.classList.remove('active'));const sm={pos:'posScreen',stok:'stokScreen',laporan:'laporanScreen',editor:'editorScreen'};const ti={pos:0,stok:1,laporan:2,editor:3};document.getElementById(sm[name]).classList.add('active');document.querySelectorAll('.ntab')[ti[name]].classList.add('active');if(name==='pos'){buildCats();renderMenu();updOrdNum()}if(name==='stok'){populateStokSel();renderStok()}if(name==='laporan'){populateRptSel();renderReport()}if(name==='editor'){renderEditorMenu();renderKasirEditor();renderOutletEditor();document.getElementById('menuCount').textContent=MENU.length+' item menu aktif'}}
function buildCats(){const cats=['Semua',...new Set(MENU.map(m=>m.cat))];document.getElementById('catsRow').innerHTML=cats.map(c=>`<button class="cpill${c===currentCat?' active':''}" onclick="filterCat('${c}')">${c}</button>`).join('')}
function filterCat(c){currentCat=c;buildCats();renderMenu()}
function renderMenu(){if(!currentOutlet)return;const q=document.getElementById('srchIn').value.toLowerCase();const filtered=MENU.filter(m=>(currentCat==='Semua'||m.cat===currentCat)&&(!q||m.name.toLowerCase().includes(q)));const low=MENU.filter(m=>stok[currentOutlet]&&stok[currentOutlet][m.id]>0&&stok[currentOutlet][m.id]<=m.minStok);document.getElementById('stokAlert').textContent=low.length?`⚠ ${low.length} item hampir habis`:'';document.getElementById('menuGrid').innerHTML=filtered.map(m=>{const s=(stok[currentOutlet]||{})[m.id]??99;const oos=s<=0;const ic=cart.find(c=>c.id===m.id);return`<div class="mcard${oos?' oos':''}" onclick="addCart(${m.id})">${ic?`<div class="inctag">×${ic.qty}</div>`:''}${m.badge&&!oos?`<div class="mbadge">${m.badge}</div>`:''}${oos?`<div class="oobadge">Habis</div>`:''}<div class="mico">${m.icon}</div><div class="mname">${m.name}</div><div class="mprice">${fmt(m.price)}</div><div class="mstk">Stok: ${s}</div></div>`}).join('')}
function addCart(id){const m=MENU.find(x=>x.id===id);const s=(stok[currentOutlet]||{})[id]??99;if(s<=0){notif('Stok habis!');return}const ex=cart.find(c=>c.id===id);if(ex&&ex.qty>=s){notif('Stok tidak mencukupi');return}ex?ex.qty++:cart.push({...m,qty:1,note:''});renderMenu();renderCart();notif(m.name+' +')}
function renderCart(){const el=document.getElementById('cartList');const em=document.getElementById('cempty');document.getElementById('cartMeta').textContent=currentCashier+' · '+currentOutlet;if(!cart.length){em.style.display='flex';el.innerHTML='';el.appendChild(em);document.getElementById('payBtn').disabled=true;calcTotal();return}em.style.display='none';document.getElementById('payBtn').disabled=false;el.innerHTML=cart.map((it,i)=>`<div class="citem"><div class="citem-top"><div class="ciname">${it.name}</div><div class="cisub">${fmt(it.price*it.qty)}</div></div><div class="cictrl"><button class="qbtn" onclick="chgQ(${i},-1)">−</button><span class="qnum">${it.qty}</span><button class="qbtn" onclick="chgQ(${i},1)">+</button><span style="font-size:10px;color:var(--text3);margin-left:4px">${fmt(it.price)}/pcs</span></div><input class="notein" placeholder="Catatan pesanan..." value="${it.note}" oninput="setNote(${i},this.value)"></div>`).join('');calcTotal()}
function chgQ(i,d){cart[i].qty+=d;if(cart[i].qty<=0)cart.splice(i,1);renderCart();renderMenu()}
function setNote(i,v){cart[i].note=v}
function calcTotal(){const sub=cart.reduce((s,c)=>s+c.price*c.qty,0);const disc=Math.round(sub*discPct/100);const tot=sub-disc;document.getElementById('stEl').textContent=fmt(sub);document.getElementById('dsEl').textContent='-'+fmt(disc);document.getElementById('ttEl').textContent=fmt(tot);return{sub,disc,tot}}
function applyDisc(){const v=document.getElementById('discIn').value;if(!v){discPct=0;notif('Diskon dihapus');calcTotal();return}const p=parseFloat(v);if(!isNaN(p)&&p>=0&&p<=100){discPct=p;notif(`Diskon ${p}% aktif`)}else notif('Input tidak valid');calcTotal()}
function setType(btn,t){orderType=t;document.querySelectorAll('.tbtn').forEach(b=>b.classList.remove('active'));btn.classList.add('active')}
function updOrdNum(){const n=String(orderCounters[currentOutlet]||1).padStart(3,'0');document.getElementById('ordNum').textContent=`Order #MC-${n}`}
function openPay(){if(!cart.length)return;const{tot}=calcTotal();document.getElementById('mTotal').textContent=fmt(tot);document.getElementById('cashIn').value='';document.getElementById('kemRow').style.display='none';document.getElementById('cashSec').style.display='block';payMethod='Tunai';document.querySelectorAll('.pmbtn').forEach((b,i)=>b.classList.toggle('sel',i===0));document.getElementById('payModal').classList.add('open')}
function closePay(){document.getElementById('payModal').classList.remove('open')}
function selPay(btn,m){payMethod=m;document.querySelectorAll('.pmbtn').forEach(b=>b.classList.remove('sel'));btn.classList.add('sel');document.getElementById('cashSec').style.display=m==='Tunai'?'block':'none';if(m!=='Tunai')document.getElementById('kemRow').style.display='none'}
function calcKem(){const{tot}=calcTotal();const cash=parseFloat(document.getElementById('cashIn').value)||0;if(cash>0){document.getElementById('kemRow').style.display='flex';const k=cash-tot;document.getElementById('kemVal').textContent=k>=0?fmt(k):'Kurang '+fmt(-k);document.getElementById('kemVal').style.color=k>=0?'var(--success-text)':'var(--danger-text)'}else document.getElementById('kemRow').style.display='none'}
function confirmPay(){const{sub,disc,tot}=calcTotal();cart.forEach(it=>{if(stok[currentOutlet]&&stok[currentOutlet][it.id]!==undefined)stok[currentOutlet][it.id]=Math.max(0,stok[currentOutlet][it.id]-it.qty)});const d=new Date();const n=String(orderCounters[currentOutlet]).padStart(3,'0');lastTxn={id:`MC-${n}`,time:d.toLocaleTimeString('id-ID',{hour:'2-digit',minute:'2-digit'}),date:d.toLocaleDateString('id-ID',{day:'2-digit',month:'short',year:'numeric'}),outlet:currentOutlet,cashier:currentCashier,type:orderType,total:tot,sub,disc,method:payMethod,status:'done',dayOffset:0,items:cart.map(c=>({name:c.name,qty:c.qty,price:c.price,note:c.note})),cash:payMethod==='Tunai'?(parseFloat(document.getElementById('cashIn').value)||tot):null};transactions.unshift(lastTxn);orderCounters[currentOutlet]++;closePay();buildReceipt();document.getElementById('rcptModal').classList.add('open')}
function buildReceipt(){const t=lastTxn;let h=`<div class="rpc" style="font-weight:bold;font-size:14px">🍗 MAFAAZA CHICKEN</div><div class="rpc rpsm">Outlet ${t.outlet}</div><div class="rpc rpsm">Kasir: ${t.cashier} · ${t.type}</div><div class="rpsep"></div><div class="rprow rpsm"><span>No. Order</span><span>${t.id}</span></div><div class="rprow rpsm"><span>Tanggal</span><span>${t.date} ${t.time}</span></div><div class="rpsep"></div>`;t.items.forEach(i=>{h+=`<div class="rprow"><span>${i.name}</span></div><div class="rprow rpsm"><span>&nbsp;&nbsp;${i.qty} × ${fmt(i.price)}</span><span>${fmt(i.qty*i.price)}</span></div>${i.note?`<div class="rpsm" style="padding-left:12px;color:#777">📝 ${i.note}</div>`:''}`});h+=`<div class="rpsep"></div>`;if(t.disc>0)h+=`<div class="rprow"><span>Subtotal</span><span>${fmt(t.sub)}</span></div><div class="rprow"><span>Diskon</span><span>-${fmt(t.disc)}</span></div>`;h+=`<div class="rprow" style="font-weight:bold;font-size:13px"><span>TOTAL</span><span>${fmt(t.total)}</span></div>`;if(t.method==='Tunai'&&t.cash)h+=`<div class="rprow rpsm"><span>Tunai</span><span>${fmt(t.cash)}</span></div><div class="rprow rpsm"><span>Kembalian</span><span>${fmt(t.cash-t.total)}</span></div>`;h+=`<div class="rpsep"></div><div class="rpc rpsm">${t.method}</div><div class="rpc rpsm" style="margin-top:8px">Terima kasih sudah mampir! 🙏</div><div class="rpc rpsm">Mafaaza Chicken — Enak & Terjangkau</div>`;document.getElementById('rcptPaper').innerHTML=h}
function doPrint(){const c=document.getElementById('rcptPaper').innerHTML;const w=window.open('','_blank','width=420,height=680');if(!w){notif('Aktifkan pop-up di browser');return}w.document.write(`<!DOCTYPE html><html><head><title>Struk - Mafaaza Chicken</title><style>*{margin:0;padding:0;box-sizing:border-box}body{font-family:'Courier New',monospace;font-size:12px;padding:16px;max-width:300px;margin:auto;color:#111}.rpc{text-align:center;margin-bottom:3px}.rpsep{border-top:1px dashed #bbb;margin:6px 0}.rprow{display:flex;justify-content:space-between;margin:2px 0}.rpsm{font-size:10px;color:#555}@media print{@page{margin:4mm}}</style></head><body>${c}<script>window.onload=function(){window.print();setTimeout(()=>window.close(),1000)}<\/script></body></html>`);w.document.close();notif('Dialog cetak dibuka...')}
function sendWA(){const t=lastTxn;let msg=`*STRUK MAFAAZA CHICKEN*\nOutlet: ${t.outlet} | Order: ${t.id}\n${t.date} ${t.time}\n\n`;t.items.forEach(i=>{msg+=`${i.name} ×${i.qty} = ${fmt(i.qty*i.price)}\n`});if(t.disc>0)msg+=`Diskon: -${fmt(t.disc)}\n`;msg+=`\n*Total: ${fmt(t.total)}* (${t.method})\nKasir: ${t.cashier}\n\nTerima kasih! 🙏 Mafaaza Chicken`;window.open('https://wa.me/?text='+encodeURIComponent(msg),'_blank');notif('Membuka WhatsApp...')}
function syncTxnGDS(){if(!gdsUrl){notif('Konfigurasi Google Sheets dulu di Editor');return}const t=lastTxn;fetch(gdsUrl,{method:'POST',body:JSON.stringify(t),mode:'no-cors'}).then(()=>{gdsSyncCount++;document.getElementById('gdsSyncCount').textContent=gdsSyncCount;document.getElementById('gdsLastSync').textContent=new Date().toLocaleTimeString('id-ID');notif('Sync ke Google Sheets berhasil')}).catch(()=>notif('Gagal sync - cek koneksi'))}
function closeReceipt(){document.getElementById('rcptModal').classList.remove('open');cart=[];discPct=0;document.getElementById('discIn').value='';updOrdNum();renderCart();renderMenu()}
function populateStokSel(){const s=document.getElementById('stokOSel');s.innerHTML=OUTLETS_LIST.map(o=>`<option>${o}</option>`).join('');if(currentOutlet)s.value=currentOutlet}
function renderStok(){const outlet=document.getElementById('stokOSel').value||currentOutlet||OUTLETS_LIST[0];if(!stok[outlet])stok[outlet]={};document.getElementById('stokBody').innerHTML=MENU.map(m=>{const s=stok[outlet][m.id]??0;const pct=Math.min(100,Math.round(s/(m.minStok*2+1)*100));const col=s<=0?'#dc2626':s<=m.minStok?'#d97706':'#16a34a';const stxt=s<=0?'Habis':s<=m.minStok?'Menipis':'Aman';return`<tr><td><b>${m.name}</b></td><td style="color:var(--text2);font-size:11px">${m.cat}</td><td><div style="display:flex;align-items:center;gap:6px"><div class="stkbar-w"><div class="stkbar" style="width:${pct}%;background:${col}"></div></div></div></td><td style="font-weight:700">${s}</td><td style="color:var(--text3)">${m.minStok}</td><td><span class="sbadge ${s<=0?'svoid':s<=m.minStok?'':'sdone'}" style="${s>0&&s<=m.minStok?'background:var(--warning-bg);color:var(--warning-text)':''}">${stxt}</span></td><td><div style="display:flex;gap:5px;align-items:center"><input class="stkin" type="number" id="st_${m.id}" value="${s}" min="0"><button class="adjbtn" onclick="adjStok('${outlet}',${m.id})">Set</button></div></td></tr>`}).join('')}
function adjStok(o,id){const v=parseInt(document.getElementById('st_'+id).value);if(isNaN(v)||v<0){notif('Input tidak valid');return}stok[o][id]=v;notif('Stok diperbarui');renderStok();renderMenu()}
function populateRptSel(){const s=document.getElementById('rOutlet');s.innerHTML='<option value="all">Semua Outlet</option>'+OUTLETS_LIST.map(o=>`<option>${o}</option>`).join('')}
function renderReport(){const period=document.getElementById('rPeriod').value;const oFilter=document.getElementById('rOutlet').value;let maxOffset=period==='today'?0:period==='week'?6:30;const filtered=transactions.filter(t=>Math.abs(t.dayOffset||0)<=maxOffset&&(oFilter==='all'||t.outlet===oFilter)&&t.status==='done');const omzet=filtered.reduce((s,t)=>s+t.total,0);const txnCnt=filtered.length;const avg=txnCnt?Math.round(omzet/txnCnt):0;const nonTunai=filtered.filter(t=>t.method!=='Tunai').length;document.getElementById('mgcards').innerHTML=`<div class="mcard2"><div class="mlbl">Total Omzet</div><div class="mval" style="color:var(--red)">${fmt(omzet)}</div><div class="msub">${txnCnt} transaksi</div></div><div class="mcard2"><div class="mlbl">Avg. Order</div><div class="mval">${fmt(avg)}</div><div class="msub">Per transaksi</div></div><div class="mcard2"><div class="mlbl">Non-Tunai</div><div class="mval">${Math.round(txnCnt?nonTunai/txnCnt*100:0)}%</div><div class="msub">QRIS/Transfer/EDC</div></div><div class="mcard2"><div class="mlbl">Outlet</div><div class="mval">${OUTLETS_LIST.length}</div><div class="msub">Kasir: ${KASIRS.length}</div></div>`;
buildTrendChart(period,oFilter);
const mc={};filtered.forEach(t=>t.items.forEach(i=>{if(!mc[i.name])mc[i.name]={qty:0,rev:0};mc[i.name].qty+=i.qty;mc[i.name].rev+=i.qty*i.price}));const sorted=Object.entries(mc).sort((a,b)=>b[1].qty-a[1].qty).slice(0,6);const mx=sorted[0]?sorted[0][1].qty:1;document.getElementById('tmlist').innerHTML=sorted.map(([nm,d])=>`<div class="tmitem"><span style="font-size:12px;font-weight:600;width:140px;flex-shrink:0">${nm}</span><div class="tmbar-wrap"><div class="tmbar" style="width:${Math.round(d.qty/mx*100)}%"></div></div><span style="font-size:12px;font-weight:700;color:var(--red);width:50px;text-align:right">${d.qty} pcs</span><span style="font-size:11px;color:var(--text2);width:80px;text-align:right">${fmt(d.rev)}</span></div>`).join('');
const all=oFilter==='all'?transactions:transactions.filter(t=>t.outlet===oFilter);document.getElementById('txnBody').innerHTML=all.filter(t=>Math.abs(t.dayOffset||0)<=maxOffset).map(t=>`<tr><td><b>${t.id}</b></td><td>${t.time}</td><td>${t.outlet}</td><td>${t.cashier}</td><td>${t.type}</td><td style="font-weight:700;color:var(--red)">${fmt(t.total)}</td><td>${t.method}</td><td><span class="sbadge ${t.status==='done'?'sdone':'svoid'}">${t.status==='done'?'Lunas':'Void'}</span></td><td>${t.status==='done'?`<button class="void-act" onclick="openVoid('${t.id}','${t.outlet}')">Void</button>`:'-'}</td></tr>`).join('')}
function buildTrendChart(period,oFilter){const days=period==='today'?1:period==='week'?7:30;const labels=[];const vals=[];for(let i=days-1;i>=0;i--){const d=new Date();d.setDate(d.getDate()-i);labels.push(days<=7?d.toLocaleDateString('id-ID',{weekday:'short',day:'2-digit'}):d.toLocaleDateString('id-ID',{day:'2-digit',month:'short'}));const dayTxn=transactions.filter(t=>(t.dayOffset||0)===-i&&(oFilter==='all'||t.outlet===oFilter)&&t.status==='done');vals.push(dayTxn.reduce((s,t)=>s+t.total,0))}const ctx=document.getElementById('trendChart').getContext('2d');if(trendChartInst)trendChartInst.destroy();trendChartInst=new Chart(ctx,{type:'bar',data:{labels,datasets:[{label:'Omzet',data:vals,backgroundColor:'rgba(184,39,43,.75)',borderRadius:4,borderSkipped:false}]},options:{responsive:true,maintainAspectRatio:true,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>fmt(c.raw)}}},scales:{y:{ticks:{callback:v=>fmt(v),font:{size:10}},grid:{color:'rgba(0,0,0,.06)'}},x:{ticks:{font:{size:10}},grid:{display:false}}}}})}
function openVoid(id,outlet){voidTargetId={id,outlet};const t=transactions.find(x=>x.id===id&&x.outlet===outlet&&x.status==='done');if(!t)return;document.getElementById('voidInfo').innerHTML=`<div style="display:flex;justify-content:space-between;margin-bottom:6px"><span style="color:var(--text2)">Order</span><b>${t.id} · ${t.outlet}</b></div><div style="display:flex;justify-content:space-between;margin-bottom:6px"><span style="color:var(--text2)">Total</span><b style="color:var(--red)">${fmt(t.total)}</b></div><div style="display:flex;justify-content:space-between"><span style="color:var(--text2)">Kasir</span><b>${t.cashier}</b></div>`;document.getElementById('voidModal').classList.add('open')}
function closeVoid(){document.getElementById('voidModal').classList.remove('open');voidTargetId=null}
function confirmVoid(){if(!voidTargetId)return;const t=transactions.find(x=>x.id===voidTargetId.id&&x.outlet===voidTargetId.outlet&&x.status==='done');if(t){t.status='void';t.items.forEach(i=>{if(stok[t.outlet]&&stok[t.outlet][i.id]!==undefined)stok[t.outlet][i.id]+=i.qty})}closeVoid();renderReport();notif('Transaksi di-void, stok dikembalikan')}
function exportCSV(){const period=document.getElementById('rPeriod').value;const oFilter=document.getElementById('rOutlet').value;let maxOffset=period==='today'?0:period==='week'?6:30;const rows=[['No Order','Waktu','Outlet','Kasir','Tipe','Total','Metode','Status'],...transactions.filter(t=>(oFilter==='all'||t.outlet===oFilter)&&Math.abs(t.dayOffset||0)<=maxOffset).map(t=>[t.id,t.time,t.outlet,t.cashier,t.type,t.total,t.method,t.status])];const csv=rows.map(r=>r.join(',')).join('\n');const a=document.createElement('a');a.href='data:text/csv;charset=utf-8,\uFEFF'+encodeURIComponent(csv);a.download='laporan_mafaaza.csv';a.click();notif('CSV berhasil diexport')}
function switchETab(btn,panel){document.querySelectorAll('.etab').forEach(b=>b.classList.remove('active'));document.querySelectorAll('.epanel').forEach(p=>p.classList.remove('active'));btn.classList.add('active');document.getElementById(panel).classList.add('active')}
function renderEditorMenu(){document.getElementById('menuCount').textContent=MENU.length+' item menu aktif';document.getElementById('menuEditorBody').innerHTML=MENU.map((m,i)=>`<tr><td><input class="ein" value="${m.icon}" style="width:50px;text-align:center" oninput="MENU[${i}].icon=this.value"></td><td><input class="ein" value="${m.name}" oninput="MENU[${i}].name=this.value"></td><td><input class="ein" value="${m.cat}" oninput="MENU[${i}].cat=this.value"></td><td><input class="ein" type="number" value="${m.price}" oninput="MENU[${i}].price=parseInt(this.value)||0"></td><td><input class="ein" type="number" value="${m.minStok}" oninput="MENU[${i}].minStok=parseInt(this.value)||0"></td><td><div style="display:flex;gap:5px"><button class="savbtn" onclick="saveMenuItem(${i})">Simpan</button><button class="delbtn" onclick="delMenuItem(${i})"><i class="ti ti-trash"></i></button></div></td></tr>`).join('')}
function saveMenuItem(i){notif(MENU[i].name+' disimpan');renderEditorMenu()}
function delMenuItem(i){if(MENU.length<=1){notif('Minimal 1 menu');return}MENU.splice(i,1);renderEditorMenu();notif('Menu dihapus')}
function addMenuItem(){const newId=Math.max(...MENU.map(m=>m.id))+1;MENU.push({id:newId,name:'Menu Baru',price:10000,cat:'Lainnya',icon:'🍽️',minStok:10});OUTLETS_LIST.forEach(o=>{if(!stok[o])stok[o]={};stok[o][newId]=20});renderEditorMenu();notif('Menu baru ditambahkan')}
function renderKasirEditor(){document.getElementById('kasirCount').textContent=KASIRS.length+' kasir terdaftar';document.getElementById('kasirBody').innerHTML=KASIRS.map((k,i)=>`<tr><td><input class="ein" value="${k}" oninput="KASIRS[${i}]=this.value"></td><td><select class="ein" style="height:28px"><option>Kasir</option><option>Supervisor</option><option>Manager</option></select></td><td><div style="display:flex;gap:5px"><button class="savbtn" onclick="saveKasir(${i})">Simpan</button><button class="delbtn" onclick="delKasir(${i})"><i class="ti ti-trash"></i></button></div></td></tr>`).join('')}
function saveKasir(i){notif(KASIRS[i]+' disimpan');buildLoginUI()}
function delKasir(i){if(KASIRS.length<=1){notif('Minimal 1 kasir');return}KASIRS.splice(i,1);renderKasirEditor();buildLoginUI();notif('Kasir dihapus')}
function addKasir(){KASIRS.push('Kasir Baru');renderKasirEditor();buildLoginUI();notif('Kasir baru ditambahkan')}
function renderOutletEditor(){document.getElementById('outletCount').textContent=OUTLETS_LIST.length+' outlet terdaftar';document.getElementById('outletBody').innerHTML=OUTLETS_LIST.map((o,i)=>{const meta=OUTLET_META[o]||{kota:'',aktif:true};return`<tr><td><input class="ein" value="${o}" onchange="renameOutlet(${i},this.value)"></td><td><input class="ein" value="${meta.kota}" onchange="OUTLET_META['${o}'].kota=this.value"></td><td><select class="ein" style="height:28px" onchange="OUTLET_META['${o}'].aktif=this.value==='Aktif'"><option ${meta.aktif!==false?'selected':''}>Aktif</option><option ${meta.aktif===false?'selected':''}>Nonaktif</option></select></td><td><div style="display:flex;gap:5px"><button class="savbtn" onclick="saveOutlet(${i})">Simpan</button><button class="delbtn" onclick="delOutlet(${i})"><i class="ti ti-trash"></i></button></div></td></tr>`}).join('')}
function renameOutlet(i,newName){const old=OUTLETS_LIST[i];if(stok[old])stok[newName]={...stok[old]};if(OUTLET_META[old])OUTLET_META[newName]={...OUTLET_META[old]};OUTLETS_LIST[i]=newName;buildLoginUI()}
function saveOutlet(i){notif(OUTLETS_LIST[i]+' disimpan');buildLoginUI();renderOutletEditor()}
function delOutlet(i){if(OUTLETS_LIST.length<=1){notif('Minimal 1 outlet');return}OUTLETS_LIST.splice(i,1);renderOutletEditor();buildLoginUI();notif('Outlet dihapus')}
function addOutlet(){const name='Outlet Baru';OUTLETS_LIST.push(name);OUTLET_META[name]={kota:'',aktif:true};stok[name]={};MENU.forEach(m=>stok[name][m.id]=0);orderCounters[name]=1;renderOutletEditor();buildLoginUI();notif('Outlet baru ditambahkan')}
function testGDS(){const url=document.getElementById('gdsUrl').value.trim();if(!url){notif('Masukkan URL terlebih dahulu');return}gdsUrl=url;document.getElementById('gdsStatus').innerHTML='<div class="gds-status" style="background:var(--info-bg);color:var(--info-text)">Mengirim test request...</div>';fetch(url,{method:'POST',body:JSON.stringify({id:'TEST',time:'--',outlet:'System',cashier:'Test',type:'Test',total:0,method:'Test'}),mode:'no-cors'}).then(()=>{document.getElementById('gdsConn').textContent='Terhubung ✓';document.getElementById('gdsConn').style.color='var(--success-text)';document.getElementById('gdsStatus').innerHTML='<div class="gds-status" style="background:var(--success-bg);color:var(--success-text)">Koneksi berhasil! Transaksi akan auto-sync.</div>';notif('Google Sheets terhubung!')}).catch(()=>{document.getElementById('gdsStatus').innerHTML='<div class="gds-status" style="background:var(--danger-bg);color:var(--danger-text)">Gagal konek. Cek URL dan pastikan deploy sebagai Anyone.</div>'})}
function syncAllGDS(){if(!gdsUrl){notif('Konfigurasi Google Sheets dulu');return}const done=transactions.filter(t=>t.status==='done');done.forEach(t=>{fetch(gdsUrl,{method:'POST',body:JSON.stringify(t),mode:'no-cors'}).then(()=>{gdsSyncCount++;document.getElementById('gdsSyncCount').textContent=gdsSyncCount;document.getElementById('gdsLastSync').textContent=new Date().toLocaleTimeString('id-ID')}).catch(()=>{})});notif('Sync '+done.length+' transaksi ke Google Sheets')}
buildLoginUI();updateClock();setInterval(updateClock,30000);
</script>
</body>
</html>
