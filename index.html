<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, viewport-fit=cover">
<meta name="screen-orientation" content="portrait">
<meta name="x5-orientation" content="portrait">
<meta name="full-screen" content="yes">
<meta name="browsermode" content="application">
<title>Neon Tetris</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700;900&display=swap" rel="stylesheet">
<style>
  :root { --bg:#000; --text:#fff; --grid:#0a0a0a; --border:#222; --accent:#00ffff; }
  body.light { --bg:#d5d5d5; --text:#0a0a0a; --grid:#bdbdbd; --border:#555; --accent:#0044cc; }
  body.light .menu-title { color: #0044cc; text-shadow: 0 0 12px rgba(0,68,204,0.45), 0 0 24px rgba(0,68,204,0.2); }
  body.light .menu-sub { color: #1a1a1a; opacity: 0.85; }
  body.light .menu-btn { background: rgba(215,215,215,0.9); color: #0a0a0a; border-color: #444; }
  body.light .menu-btn:hover, body.light .menu-btn:active { color: #0044cc; border-color: #0044cc; box-shadow: 0 0 18px rgba(0,68,204,0.35); }
  body.light .menu-btn.start { color: #0044cc; border-color: #0044cc; }
  body.light .menu-btn.continue { color: #006622; border-color: #006622; }
  body.light .menu-btn.best { color: #8a4400; border-color: #8a4400; }
  body.light .menu-btn.reset { color: #aa0022; border-color: #aa0022; }
  body.light .menu-btn small { color: #2a2a2a; }
  body.light .menu-version { color: #1a1a1a; opacity: 0.75; }
  body.light .menu-ach-btn { background: rgba(215,215,215,0.95); color: #0a0a0a; border-color: #444; }
  body.light .menu-ach-btn:active { color: #0044cc; border-color: #0044cc; }
  body.light .menu-ach-btn .mab-count { color: #8a4400; }
  body.light .menu-settings-btn { background: rgba(215,215,215,0.95); color: #0a0a0a; border-color: #444; }
  body.light .menu-settings-btn:active { color: #0044cc; border-color: #0044cc; }
  body.light .panel { background: rgba(235,235,235,0.85); border-color: #555; }
  body.light .panel span { color: #0044cc; }
  body.light .panel.best span { color: #8a4400; }
  body.light .action-btn { background: rgba(215,215,215,0.9); color: #0a0a0a; border-color: #444; }
  body.light .action-btn.pause { color: #8a4400; border-color: #8a4400; }
  body.light .action-btn.save { color: #006622; border-color: #006622; }
  body.light .action-btn.reset { color: #aa0022; border-color: #aa0022; }
  body.light .controls button { background: rgba(215,215,215,0.9); color: #0044cc; border-color: #444; }
  body.light canvas#board { background: var(--bg); box-shadow: 0 0 20px rgba(0,68,204,0.55), 0 0 40px rgba(0,68,204,0.35), 0 0 0 2px #555; border: none; }
  body.light .overlay { background: rgba(220,220,220,0.97); }
  body.light .overlay h2 { color: #0044cc; text-shadow: 0 0 12px rgba(0,68,204,0.35); }
  body.light .overlay h2.record { color: #8a4400; text-shadow: 0 0 12px rgba(138,68,0,0.35); }
  body.light .overlay p { color: #0a0a0a; }
  body.light .overlay button { color: #0a0a0a; border-color: #0044cc; }
  body.light .overlay button:active { background: #0044cc; color: #fff; }
  body.light .overlay button.danger { color: #aa0022; border-color: #aa0022; }
  body.light .overlay button.danger:active { background: #aa0022; color: #fff; }
  body.light .overlay button.success { color: #006622; border-color: #006622; }
  body.light .overlay button.success:active { background: #006622; color: #fff; }
  body.light .overlay button.gold { color: #8a4400; border-color: #8a4400; }
  body.light .overlay button.gold:active { background: #8a4400; color: #fff; }
  body.light .ach-modal, body.light .settings-modal { background: rgba(220,220,220,0.98); }
  body.light .ach-modal-title, body.light .settings-modal-title { color: #0044cc; text-shadow: 0 0 10px rgba(0,68,204,0.3); }
  body.light .ach-modal-count { color: #8a4400; text-shadow: none; }
  body.light .ach-close, body.light .settings-close { color: #0a0a0a; border-color: #444; background: rgba(215,215,215,0.9); }
  body.light .ach-close:active, body.light .settings-close:active { background: #0044cc; color: #fff; border-color: #0044cc; }
  body.light .ach-card, body.light .settings-group-card { background: rgba(235,235,235,0.85); border-color: #888; }
  body.light .ach-card.unlocked { border-color: #0044cc; box-shadow: 0 0 12px rgba(0,68,204,0.3); }
  body.light .ach-card.unlocked.rare { border-color: #8a4400; box-shadow: 0 0 12px rgba(138,68,0,0.3); }
  body.light .ach-card.unlocked.legendary { border-color: #aa0022; box-shadow: 0 0 12px rgba(170,0,34,0.3); }
  body.light .ach-card .ac-name { color: #0a0a0a; }
  body.light .ach-card.unlocked .ac-name { color: #000; }
  body.light .ach-card .ac-desc { color: #2a2a2a; opacity: 0.9; }
  body.light .ach-card .ac-rarity { color: #2a2a2a; border-color: #888; }
  body.light .ach-progress-bar { background: rgba(0,0,0,0.12); border-color: #555; }
  body.light .promo-section { background: rgba(235,235,235,0.9); }
  body.light .promo-title { color: #0044cc; text-shadow: none; }
  body.light .promo-input { background: rgba(255,255,255,0.95); color: #0a0a0a; border-color: #444; }
  body.light .promo-input::placeholder { color: #444; opacity: 0.8; }
  body.light .promo-btn { color: #0044cc; border-color: #0044cc; }
  body.light .promo-btn:active { background: #0044cc; color: #fff; }
  body.light .legendary-hint { color: #8a4400; text-shadow: none; }
  body.light .legendary-theme-btn { color: #8a4400; border-color: #8a4400; background: linear-gradient(135deg, rgba(255,215,0,0.18), rgba(255,140,200,0.12)); box-shadow: 0 0 15px rgba(138,68,0,0.4); text-shadow: none; }
  body.light .legendary-theme-btn:hover, body.light .legendary-theme-btn:active { background: linear-gradient(135deg, #ffd700, #ff66cc); color: #0a0410; }
  body.light .toast { background: #0044cc; color: #fff; }
  body.light .settings-group-label { color: #0044cc; }
  body.light .settings-opt { color: #0a0a0a; border-color: #444; background: rgba(215,215,215,0.9); }
  body.light .settings-opt.active { color: #0044cc; border-color: #0044cc; background: rgba(0,68,204,0.12); box-shadow: 0 0 12px rgba(0,68,204,0.35); }
  body.light .settings-reset-card { background: rgba(235,235,235,0.85); border-color: #aa0022; }
  body.light .settings-reset-btn { color: #aa0022; border-color: #aa0022; }
  body.medium { --bg:#1a1a2e; --text:#e0e0e0; --grid:#1f1f38; --border:#333366; --accent:#ff00ff; }
  body.legendary { --bg:#0a0410; --text:#ffe9a8; --grid:#120820; --border:#8a6b1f; --accent:#ffd700; background: #0a0410; }
  * { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
  html { overflow: hidden; width: 100%; height: 100%; position: fixed; }
  body { background: var(--bg); color: var(--text); font-family: 'Orbitron', monospace;
    display: flex; flex-direction: column; align-items: center; justify-content: center;
    min-height: 100vh; padding: 10px; overflow: hidden; transition: background 0.4s, color 0.4s;
    user-select: none; -webkit-user-select: none; touch-action: manipulation; position: relative; }
  body.legendary::after { content: 'LEGENDARY'; position: fixed; bottom: -14px; left: 50%; transform: translateX(-50%); font-size: 0.6rem; letter-spacing: 4px; font-weight: 900; color: #ffd700; text-shadow: 0 0 10px #ffd700; z-index: 100; pointer-events: none; }
  body.legendary canvas#board { box-shadow: 0 0 24px rgba(255,215,0,0.9), 0 0 48px rgba(255,215,0,0.6), 0 0 90px rgba(255,0,255,0.4); border-color: #ffd700; }
  body.legendary .menu-title { background: linear-gradient(90deg, #ffd700 0%, #ffb347 15%, #ff66cc 35%, #b366ff 55%, #ff66cc 75%, #ffb347 88%, #ffd700 100%); background-size: 200% 100%; -webkit-background-clip: text; background-clip: text; -webkit-text-fill-color: transparent; color: transparent; text-shadow: 0 0 15px rgba(255,215,0,0.4); }
  body.legendary .menu .menu-btn { border-color: #ffd700 !important; color: #ffd700 !important; background: linear-gradient(135deg, rgba(255,215,0,0.1), rgba(255,0,255,0.07)); box-shadow: 0 0 12px rgba(255,215,0,0.4), inset 0 0 12px rgba(255,215,0,0.08); text-shadow: 0 0 6px rgba(255,215,0,0.6); }
  body.legendary .menu .menu-btn:hover, body.legendary .menu .menu-btn:active { background: linear-gradient(135deg, #ffd700, #ff00ff); color: #0a0410 !important; border-color: #ffd700 !important; box-shadow: 0 0 25px #ffd700, 0 0 50px #ff00ff, 0 0 80px rgba(0,255,255,0.5); }
  body.legendary .menu-btn.continue { border-color: #ffd700; color: #ffd700; }
  body.legendary .menu-btn.best { border-color: #ffd700; color: #ffd700; }
  body.legendary .menu-btn.best span, body.legendary .menu-btn.best small { color: #ffd700; }
  body.legendary .menu-btn.reset { border-color: #ff66cc; color: #ff66cc; }
  body.legendary .menu-btn.start { border-color: #ffd700; background: linear-gradient(135deg, rgba(255,215,0,0.15), rgba(255,0,255,0.1)); box-shadow: 0 0 20px rgba(255,215,0,0.5), inset 0 0 15px rgba(255,215,0,0.1); }
  body.legendary .menu-ach-btn { border-color: #ffd700; color: #ffd700; box-shadow: 0 0 15px rgba(255,215,0,0.4); }
  body.legendary .menu-settings-btn { border-color: #ffd700; color: #ffd700; box-shadow: 0 0 15px rgba(255,215,0,0.4); }
  body.legendary .toast { background: linear-gradient(135deg, #ffd700, #ff00ff); color: #0a0410; box-shadow: 0 0 25px #ffd700; }
  body.legendary .settings-modal-title { color: #ffd700; text-shadow: 0 0 15px #ffd700; }
  body.legendary .settings-group-label { color: #ffd700; text-shadow: 0 0 8px rgba(255,215,0,0.5); }
  body.legendary .settings-group-card { border-color: #8a6b1f; background: rgba(255,215,0,0.04); }
  body.legendary .settings-opt { border-color: #8a6b1f; color: #ffe9a8; background: rgba(255,215,0,0.06); }
  body.legendary .settings-opt.active { border-color: #ffd700; color: #0a0410; background: linear-gradient(135deg, #ffd700, #ff66cc); box-shadow: 0 0 16px #ffd700; }
  body.legendary .settings-reset-card { border-color: #ff66cc; background: rgba(255,215,0,0.04); }
  body.legendary .settings-reset-btn { border-color: #ff66cc; color: #ff66cc; }
  body.legendary .settings-close { border-color: #8a6b1f; color: #ffe9a8; background: rgba(255,215,0,0.06); }
  #bg-canvas { position: fixed; inset: 0; width: 100%; height: 100%; z-index: 0; opacity: 0.6; display: none; pointer-events: none; }
  #bg-canvas.show { display: block; opacity: 0.6; }
  #bg-canvas.party { opacity: 1; }

  .game-column { display: flex; flex-direction: column; align-items: stretch; position: relative; z-index: 1; gap: 0; max-width: 100%; padding-top: 62px; }
  @media (max-width: 520px) { .game-column { padding-top: 56px; } }
  @media (max-width: 400px) { .game-column { padding-top: 52px; } }
  @media (max-width: 340px) { .game-column { padding-top: 48px; } }
  .game-wrap { display: flex; gap: 8px; align-items: flex-start; position: relative; }
  .game-wrap.hidden { display: none; }
  .game-column.hidden { display: none; }

  #compressionBar { display: none; width: 100%; padding: 4px; border: 2px solid var(--accent); border-radius: 8px; background: rgba(0,0,0,0.92); box-shadow: 0 0 14px var(--accent), inset 0 0 8px rgba(0,255,255,0.08); font-family: 'Orbitron', monospace; font-weight: 900; letter-spacing: 1px; position: absolute; top: 0; left: 0; right: 0; opacity: 0; overflow: hidden; pointer-events: none; z-index: 5; transition: border-color 0.7s ease, box-shadow 0.7s ease, opacity 0.55s ease; }
  #compressionBar .cb-row { transform-origin: center center; opacity: 0; transform: scaleX(0.9); transition: transform 0.55s cubic-bezier(.2,1.15,.35,1), opacity 0.55s ease; }
  #compressionBar.show .cb-row { opacity: 1; transform: scaleX(1); }
  #compressionBar.show { display: block !important; opacity: 1; pointer-events: auto; }
  #compressionBar.hide { opacity: 0; pointer-events: none; }
  #compressionBar.hide .cb-row { opacity: 0; transform: scaleX(0.9); }
  #compressionBar.warn { border-color: #ff0044; box-shadow: 0 0 20px #ff0044, inset 0 0 10px rgba(255,0,68,0.2); }
  #compressionBar.resetFlash { animation: cbResetFlash 0.7s ease; }
  @keyframes cbResetFlash { 0% { border-color: var(--accent); } 50% { border-color: #00ff88; box-shadow: 0 0 28px #00ff88, inset 0 0 14px rgba(0,255,136,0.3); } 100% { border-color: var(--accent); } }
  #compressionBar.fieldFlash { animation: cbFieldFlash 0.8s ease; }
  @keyframes cbFieldFlash { 0% { border-color: var(--accent); } 50% { border-color: #00ffff; box-shadow: 0 0 28px #00ffff, inset 0 0 14px rgba(0,255,255,0.3); } 100% { border-color: var(--accent); } }

  .cb-row { display: flex; align-items: stretch; justify-content: space-between; gap: 4px; width: 100%; position: relative; z-index: 1; }
  .cb-block { flex: 1 1 0; display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 4px 2px; border-radius: 5px; border: 1px solid var(--border); background: rgba(0,0,0,0.4); min-width: 0; position: relative; overflow: hidden; }
  .cb-label { font-size: 0.4rem; letter-spacing: 0.6px; opacity: 0.85; color: var(--accent); white-space: nowrap; text-align: center; line-height: 1.15; overflow: hidden; text-overflow: ellipsis; max-width: 100%; }
  .cb-value { font-size: 0.95rem; line-height: 1.1; margin-top: 2px; font-weight: 900; white-space: nowrap; font-variant-numeric: tabular-nums; color: var(--accent); text-shadow: 0 0 8px var(--accent); }
  .cb-value.timer { color: #ff6600; text-shadow: 0 0 10px #ff6600; font-size: 1.15rem; }
  .cb-value.timer.danger { color: #ff0044; text-shadow: 0 0 12px #ff0044; }
  .cb-value.reset { color: #00ff88; text-shadow: 0 0 8px #00ff88; }
  .cb-value.save  { color: #ffaa00; text-shadow: 0 0 8px #ffaa00; }
  .cb-value.field { color: #00ffff; text-shadow: 0 0 8px #00ffff; }
  .cb-progress { width: 100%; height: 2px; margin-top: 3px; background: rgba(255,255,255,0.1); border-radius: 1px; overflow: hidden; }
  .cb-progress-fill { height: 100%; width: 0%; border-radius: 1px; transition: width 0.4s ease; }
  .cb-progress-fill.timer { background: #ff6600; box-shadow: 0 0 6px #ff6600; }
  .cb-progress-fill.reset { background: #00ff88; box-shadow: 0 0 6px #00ff88; }
  .cb-progress-fill.save  { background: #ffaa00; box-shadow: 0 0 6px #ffaa00; }
  .cb-sep { width: 1px; background: rgba(255,255,255,0.1); margin: 3px 0; flex-shrink: 0; }
  body.legendary #compressionBar { border-color: #ffd700; box-shadow: 0 0 18px rgba(255,215,0,0.6), inset 0 0 10px rgba(255,215,0,0.1); }
  body.legendary .cb-label { color: #ffe9a8; }
  body.legendary .cb-value { color: #ffd700; text-shadow: 0 0 8px #ffd700; }
  body.legendary .cb-value.timer { color: #ffd700; text-shadow: 0 0 10px #ffd700; }
  body.legendary .cb-value.timer.danger { color: #ff66cc; text-shadow: 0 0 12px #ff66cc; }
  body.legendary .cb-value.reset { color: #00ff88; }
  body.legendary .cb-value.save  { color: #ffb347; }
  body.legendary .cb-value.field { color: #ffd700; }
  body.light #compressionBar { border-color: #8a4400; background: rgba(255,255,255,0.95); box-shadow: 0 0 12px rgba(138,68,0,0.4); }
  body.light .cb-block { background: rgba(255,255,255,0.4); border-color: #888; }
  body.light .cb-label { color: #2a2a2a; }
  body.light .cb-value { color: #8a4400; text-shadow: none; }
  body.light .cb-value.timer { color: #8a4400; text-shadow: none; }
  body.light .cb-value.timer.danger { color: #aa0022; text-shadow: none; }
  body.light .cb-value.reset { color: #006622; text-shadow: none; }
  body.light .cb-value.save  { color: #8a4400; text-shadow: none; }
  body.light .cb-value.field { color: #0044cc; text-shadow: none; }
  @media (max-width: 520px) { #compressionBar { padding: 3px; border-radius: 7px; } .cb-row { gap: 3px; } .cb-block { padding: 3px 1px; } .cb-label { font-size: 0.34rem; letter-spacing: 0.4px; } .cb-value { font-size: 0.8rem; } .cb-value.timer { font-size: 0.95rem; } }
  @media (max-width: 400px) { #compressionBar { padding: 3px; } .cb-row { gap: 2px; } .cb-block { padding: 3px 1px; } .cb-label { font-size: 0.3rem; letter-spacing: 0.2px; } .cb-value { font-size: 0.7rem; } .cb-value.timer { font-size: 0.84rem; } }
  @media (max-width: 340px) { .cb-label { font-size: 0.26rem; letter-spacing: 0px; } .cb-value { font-size: 0.62rem; } .cb-value.timer { font-size: 0.74rem; } }

  .board-slot { height: 55vh; max-height: 480px; display: flex; align-items: flex-start; justify-content: center; overflow: visible; position: relative; flex-shrink: 0; padding: 12px; margin: -12px; }
  canvas#board { border: 2px solid var(--border); box-shadow: 0 0 20px rgba(0,255,255,0.85), 0 0 40px rgba(0,255,255,0.55), 0 0 80px rgba(0,255,255,0.35); background: var(--grid); max-width: 100%; max-height: 100%; width: auto; height: auto; display: block; border-radius: 6px; transition: box-shadow 0.5s ease, height 0.4s ease; touch-action: none; }
  canvas#board.flash { box-shadow: 0 0 25px var(--accent), 0 0 50px var(--accent); }
  canvas#board.totem { box-shadow: 0 0 60px #ffaa00, 0 0 120px #ffaa00; animation: totemShake 0.5s ease; }
  @keyframes totemShake { 0%,100% { transform: translate(0,0); } 25% { transform: translate(-2px,2px); } 50% { transform: translate(2px,-2px); } 75% { transform: translate(-1px,-1px); } }
  .side { display: flex; flex-direction: column; gap: 5px; min-width: 100px; }
  .panel { border: 1px solid var(--border); padding: 3px; text-align: center; font-size: 0.5rem; font-weight: 700; letter-spacing: 1px; border-radius: 5px; }
  .panel span { display: block; font-size: 0.85rem; font-weight: 900; margin-top: 1px; color: var(--accent); }
  .panel.best span { color: #ffaa00; }
  .action-btn { padding: 7px 6px; background: rgba(0,0,0,0.4); color: var(--text); border: 2px solid var(--border); border-radius: 7px; cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.6rem; font-weight: 900; letter-spacing: 1.2px; transition: 0.15s; text-align: center; width: 100%; min-height: 32px; display: flex; align-items: center; justify-content: center; }
  .action-btn:active { transform: scale(0.96); }
  .action-btn.pause { border-color: #ffaa00; color: #ffaa00; box-shadow: 0 0 8px rgba(255,170,0,0.5); }
  .action-btn.pause:active { background: #ffaa00; color: #000; box-shadow: 0 0 20px #ffaa00; }
  .action-btn.save { border-color: #00ff88; color: #00ff88; box-shadow: 0 0 8px rgba(0,255,136,0.5); }
  .action-btn.save:active { background: #00ff88; color: #000; box-shadow: 0 0 20px #00ff88; }
  .action-btn.reset { border-color: #ff0044; color: #ff0044; box-shadow: 0 0 8px rgba(255,0,68,0.5); }
  .action-btn.reset:active { background: #ff0044; color: #fff; box-shadow: 0 0 20px #ff0044; }
  .controls { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-top: 14px; width: 100%; max-width: 340px; position: relative; z-index: 1; }
  .controls.hidden { display: none; }
  .controls button { aspect-ratio: 1/1; display: flex; align-items: center; justify-content: center; background: rgba(255,255,255,0.03); color: var(--accent); border: 1.5px solid var(--border); border-radius: 12px; font-family: 'Orbitron', monospace; font-size: 2rem; font-weight: 900; letter-spacing: 2px; cursor: pointer; transition: all 0.15s ease; transform: scaleX(1.15); user-select: none; -webkit-user-select: none; touch-action: none; }
  .controls button:active { border-color: var(--accent); color: var(--bg); background: var(--accent); box-shadow: 0 0 20px var(--accent); transform: scaleX(1.15) scaleY(0.94); }
  .menu { position: fixed; inset: 0; z-index: 5; display: none; flex-direction: column; align-items: center; justify-content: center; gap: 12px; padding: 20px; text-align: center; }
  .menu.show { display: flex; }
  .menu-title { font-size: 2.4rem; font-weight: 900; letter-spacing: 8px; color: var(--accent); text-shadow: 0 0 15px var(--accent), 0 0 30px var(--accent), 0 0 60px var(--accent); margin-bottom: 8px; position: relative; pointer-events: none; user-select: none; -webkit-user-select: none; -webkit-touch-callout: none; width: 100%; text-align: center; }
  .menu-sub { font-size: 0.7rem; letter-spacing: 4px; opacity: 0.6; margin-bottom: 30px; color: var(--text); pointer-events: none; user-select: none; -webkit-user-select: none; -webkit-touch-callout: none; width: 100%; text-align: center; }
  .menu-btn { min-width: 260px; padding: 16px 24px; background: rgba(0,0,0,0.4); color: var(--text); border: 2px solid var(--border); border-radius: 12px; cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.95rem; font-weight: 700; letter-spacing: 3px; transition: all 0.25s ease; position: relative; overflow: hidden; text-align: center; }
  .menu-btn::before { content: ''; position: absolute; top: 0; left: -100%; width: 100%; height: 100%; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.15), transparent); transition: left 0.5s; }
  .menu-btn:hover::before { left: 100%; }
  .menu-btn:hover, .menu-btn:active { border-color: var(--accent); color: var(--accent); box-shadow: 0 0 20px var(--accent), inset 0 0 20px rgba(0,255,255,0.1); transform: translateY(-2px); }
  .menu-btn.start { border-color: var(--accent); color: var(--accent); }
  .menu-btn.continue { border-color: #00ff88; color: #00ff88; }
  .menu-btn.continue:hover { box-shadow: 0 0 20px #00ff88; border-color: #00ff88; }
  .menu-btn.best { border-color: #ffaa00; color: #ffaa00; cursor: default; pointer-events: none; user-select: none; -webkit-user-select: none; }
  .menu-btn.best::before { display: none; }
  .menu-btn.reset { border-color: #ff0044; color: #ff0044; }
  .menu-btn.reset:hover { box-shadow: 0 0 20px #ff0044; border-color: #ff0044; }
  .menu-btn small { display: block; font-size: 0.55rem; letter-spacing: 2px; opacity: 0.7; margin-top: 4px; font-weight: 400; }
  .menu-version { position: fixed; bottom: 15px; font-size: 0.5rem; letter-spacing: 2px; opacity: 0.4; pointer-events: none; user-select: none; text-align: center; line-height: 1.5; }
  .overlay { position: fixed; inset: 0; background: rgba(0,0,0,0.92); display: none; flex-direction: column; align-items: center; justify-content: center; gap: 14px; z-index: 10; padding: 20px; text-align: center; backdrop-filter: blur(8px); }
  .overlay.show { display: flex; }
  .overlay h2 { font-size: 1.8rem; font-weight: 900; color: var(--accent); text-shadow: 0 0 20px var(--accent); letter-spacing: 4px; }
  .overlay h2.record { color: #ffaa00; text-shadow: 0 0 20px #ffaa00, 0 0 40px #ffaa00; }
  .overlay p { font-size: 0.85rem; font-weight: 700; }
  .overlay button { padding: 12px 28px; background: transparent; color: var(--text); border: 2px solid var(--accent); cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.85rem; font-weight: 700; letter-spacing: 2px; transition: 0.2s; border-radius: 8px; min-width: 220px; position: relative; z-index: 11; }
  .overlay button:active { background: var(--accent); color: var(--bg); }
  .overlay button.secondary { border-color: var(--border); }
  .overlay button.danger { border-color: #ff0044; color: #ff0044; }
  .overlay button.danger:active { background: #ff0044; color: #fff; }
  .overlay button.success { border-color: #00ff88; color: #00ff88; }
  .overlay button.success:active { background: #00ff88; color: #000; }
  .overlay button.gold { border-color: #ffaa00; color: #ffaa00; }
  .overlay button.gold:active { background: #ffaa00; color: #000; }
  .overlay.ach-anim { animation: achOverlayFadeIn 0.55s ease-out forwards; }
  .overlay.ach-anim h2, .overlay.ach-anim p, .overlay.ach-anim button { opacity: 0; transform: translateY(14px) scale(0.94); animation: achContentRise 0.6s cubic-bezier(.2,1.2,.3,1) forwards; }
  .overlay.ach-anim h2 { animation-delay: 0.12s; }
  .overlay.ach-anim p  { animation-delay: 0.24s; }
  .overlay.ach-anim button { animation-delay: 0.38s; }
  .overlay.ach-anim button + button { animation-delay: 0.46s; }
  @keyframes achOverlayFadeIn { 0% { background: rgba(0,0,0,0); backdrop-filter: blur(0px); } 100% { background: rgba(0,0,0,0.92); backdrop-filter: blur(8px); } }
  @keyframes achContentRise { 0% { opacity: 0; transform: translateY(14px) scale(0.94); } 60% { opacity: 1; transform: translateY(-3px) scale(1.02); } 100% { opacity: 1; transform: translateY(0) scale(1); } }
  .toast { position: fixed; bottom: 20px; left: 50%; transform: translateX(-50%); background: var(--accent); color: var(--bg); padding: 10px 20px; border-radius: 8px; font-size: 0.7rem; font-weight: 700; opacity: 0; transition: opacity 0.3s; pointer-events: none; z-index: 20; }
  .toast.show { opacity: 1; }
  .bonus { position: fixed; top: 30%; left: 50%; transform: translate(-50%, -50%) scale(0); font-size: 2rem; font-weight: 900; color: #ffaa00; text-shadow: 0 0 20px #ffaa00, 0 0 40px #ffaa00; letter-spacing: 4px; pointer-events: none; z-index: 30; opacity: 0; }
  .bonus.show { animation: bonusPop 1.8s ease forwards; }
  @keyframes bonusPop { 0% { transform: translate(-50%,-50%) scale(0); opacity: 0; } 30% { transform: translate(-50%,-50%) scale(1.4); opacity: 1; } 60% { transform: translate(-50%,-50%) scale(1); opacity: 1; } 100% { transform: translate(-50%,-120%) scale(1.2); opacity: 0; } }
  .combo { position: fixed; top: 18%; left: 50%; transform: translate(-50%, 0) scale(0); font-size: 1.4rem; font-weight: 900; color: #00ff88; text-shadow: 0 0 15px #00ff88, 0 0 30px #00ff88; letter-spacing: 3px; pointer-events: none; z-index: 29; opacity: 0; }
  .combo.show { animation: comboPop 1.2s ease forwards; }
  @keyframes comboPop { 0% { transform: translate(-50%, 0) scale(0); opacity: 0; } 30% { transform: translate(-50%, 0) scale(1.3); opacity: 1; } 60% { transform: translate(-50%, 0) scale(1); opacity: 1; } 100% { transform: translate(-50%, -30px) scale(1); opacity: 0; } }
  .praise { position: fixed; top: 25%; left: 50%; transform: translate(-50%, -50%) scale(0); font-size: 1.6rem; font-weight: 900; letter-spacing: 6px; pointer-events: none; z-index: 28; opacity: 0; text-align: center; }
  .praise.show { animation: praisePop 1.4s ease forwards; }
  @keyframes praisePop { 0% { transform: translate(-50%,-50%) scale(0) rotate(-8deg); opacity: 0; } 25% { transform: translate(-50%,-50%) scale(1.3) rotate(3deg); opacity: 1; } 55% { transform: translate(-50%,-50%) scale(1) rotate(-2deg); opacity: 1; } 100% { transform: translate(-50%,-100%) scale(1.1) rotate(0deg); opacity: 0; } }
  .totem-overlay { position: fixed; inset: 0; pointer-events: none; z-index: 25; display: none; align-items: center; justify-content: center; }
  .totem-overlay.show { display: flex; }
  .totem-ring { position: absolute; width: 100px; height: 100px; border: 3px solid #ffaa00; border-radius: 50%; box-shadow: 0 0 30px #ffaa00; animation: ringExpand 1s ease-out forwards; }
  @keyframes ringExpand { 0% { transform: scale(0); opacity: 1; border-width: 8px; } 100% { transform: scale(12); opacity: 0; border-width: 1px; } }
  .totem-flash { position: fixed; inset: 0; background: radial-gradient(circle, #ffaa00 0%, #ff6600 30%, transparent 70%); pointer-events: none; z-index: 24; opacity: 0; }
  .totem-flash.show { animation: totemFlash 1s ease-out; }
  @keyframes totemFlash { 0% { opacity: 0.9; } 100% { opacity: 0; } }
  .pause-indicator { position: fixed; inset: 0; display: none; align-items: center; justify-content: center; z-index: 8; pointer-events: none; }
  .pause-indicator.show { display: flex; }
  .pause-icon { font-size: 6rem; font-weight: 900; color: var(--accent); text-shadow: 0 0 30px var(--accent), 0 0 60px var(--accent); letter-spacing: 20px; }
  .ach-toast-wrap { position: fixed; top: 16px; right: 16px; z-index: 50; display: flex; flex-direction: column; gap: 10px; pointer-events: none; max-width: 320px; }
  .ach-toast { display: flex; align-items: center; gap: 12px; padding: 12px 16px; background: linear-gradient(135deg, rgba(20,20,20,0.96), rgba(10,10,10,0.96)); border: 2px solid var(--accent); border-radius: 12px; box-shadow: 0 0 25px var(--accent), 0 0 50px rgba(0,255,255,0.25); transform: translateX(120%); opacity: 0; transition: transform 0.45s cubic-bezier(.2,1.3,.4,1), opacity 0.45s; }
  .ach-toast.show { transform: translateX(0); opacity: 1; }
  .ach-toast .ach-icon { font-size: 1.8rem; line-height: 1; filter: drop-shadow(0 0 8px var(--accent)); flex-shrink: 0; }
  .ach-toast .ach-body { flex: 1; min-width: 0; }
  .ach-toast .ach-label { font-size: 0.5rem; letter-spacing: 3px; font-weight: 700; color: var(--accent); opacity: 0.85; margin-bottom: 3px; }
  .ach-toast .ach-name { font-size: 0.72rem; letter-spacing: 1px; font-weight: 900; color: #fff; text-shadow: 0 0 8px var(--accent); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .ach-toast .ach-desc { font-size: 0.52rem; letter-spacing: 0.5px; opacity: 0.7; margin-top: 3px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .ach-toast .ach-badge { font-size: 0.5rem; font-weight: 900; letter-spacing: 1px; padding: 4px 7px; border-radius: 6px; border: 1px solid #ffaa00; color: #ffaa00; box-shadow: 0 0 10px rgba(255,170,0,0.5); flex-shrink: 0; }
  .ach-toast.rare { border-color: #ffaa00; box-shadow: 0 0 30px #ffaa00, 0 0 60px rgba(255,170,0,0.3); }
  .ach-toast.rare .ach-icon { filter: drop-shadow(0 0 10px #ffaa00); }
  .ach-toast.rare .ach-label { color: #ffaa00; }
  .ach-toast.rare .ach-name { text-shadow: 0 0 10px #ffaa00; }
  .ach-toast.legendary { border-color: #ff0044; box-shadow: 0 0 30px #ff0044, 0 0 60px rgba(255,0,68,0.35); }
  .ach-toast.legendary .ach-icon { filter: drop-shadow(0 0 10px #ff0044); }
  .ach-toast.legendary .ach-label { color: #ff0044; }
  .ach-toast.legendary .ach-name { text-shadow: 0 0 10px #ff0044; }
  .ach-toast.legendary .ach-badge { border-color: #ff0044; color: #ff0044; box-shadow: 0 0 10px rgba(255,0,68,0.5); }
  .ach-toast.rainbow { border-image: linear-gradient(90deg,#ff0044,#ffaa00,#00ff88,#00ffff,#ff00ff) 1; border: 2px solid; box-shadow: 0 0 30px #00ffff, 0 0 60px rgba(0,255,255,0.3); }
  .ach-modal { position: fixed; inset: 0; z-index: 40; background: rgba(0,0,0,0.94); backdrop-filter: blur(8px); display: none; flex-direction: column; align-items: center; padding: 24px 14px; overflow-y: auto; }
  .ach-modal.show { display: flex; }
  .ach-modal-header { display: flex; align-items: center; justify-content: space-between; width: 100%; max-width: 560px; margin-bottom: 18px; flex-shrink: 0; }
  .ach-modal-title { font-size: 1.3rem; font-weight: 900; letter-spacing: 4px; color: var(--accent); text-shadow: 0 0 15px var(--accent); position: relative; display: flex; align-items: center; gap: 10px; }
  .ach-modal-crown { display: inline-block; font-size: 1.9rem; line-height: 1; filter: drop-shadow(0 0 10px #ffd700) drop-shadow(0 0 20px #ff00ff); margin-top: -10px; margin-bottom: -10px; }
  .ach-modal-count { font-size: 0.65rem; font-weight: 900; letter-spacing: 2px; color: #ffaa00; text-shadow: 0 0 10px #ffaa00; }
  .ach-close { padding: 8px 16px; background: transparent; border: 2px solid var(--border); color: var(--text); border-radius: 8px; cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.65rem; font-weight: 700; letter-spacing: 2px; transition: 0.2s; }
  .ach-close:active { background: var(--accent); color: var(--bg); border-color: var(--accent); }
  .ach-progress-bar { width: 100%; max-width: 560px; height: 10px; border-radius: 5px; background: rgba(255,255,255,0.06); border: 1px solid var(--border); margin-bottom: 20px; overflow: hidden; flex-shrink: 0; position: relative; }
  .ach-progress-fill { height: 100%; background: linear-gradient(90deg, var(--accent), #ffaa00); box-shadow: 0 0 12px var(--accent); width: 0%; transition: width 0.6s ease; }
  .ach-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 10px; width: 100%; max-width: 560px; padding-bottom: 20px; }
  .ach-card { position: relative; padding: 12px 10px; background: rgba(0,0,0,0.55); border: 1.5px solid var(--border); border-radius: 10px; text-align: center; transition: 0.25s; opacity: 0.45; filter: grayscale(1); }
  .ach-card.unlocked { opacity: 1; filter: none; border-color: var(--accent); box-shadow: 0 0 16px rgba(0,255,255,0.25); }
  .ach-card.unlocked.rare { border-color: #ffaa00; box-shadow: 0 0 16px rgba(255,170,0,0.3); }
  .ach-card.unlocked.legendary { border-color: #ff0044; box-shadow: 0 0 16px rgba(255,0,68,0.35); }
  .ach-card.unlocked.rainbow { border-image: linear-gradient(90deg,#ff0044,#ffaa00,#00ff88,#00ffff,#ff00ff) 1; border: 1.5px solid; }
  .ach-card .ac-icon { font-size: 1.9rem; line-height: 1; margin-bottom: 6px; }
  .ach-card .ac-name { font-size: 0.58rem; font-weight: 900; letter-spacing: 1px; color: var(--text); margin-bottom: 4px; line-height: 1.3; }
  .ach-card.unlocked .ac-name { color: #fff; }
  .ach-card .ac-desc { font-size: 0.48rem; letter-spacing: 0.3px; opacity: 0.65; line-height: 1.4; }
  .ach-card .ac-rarity { display: inline-block; margin-top: 6px; font-size: 0.42rem; font-weight: 900; letter-spacing: 1px; padding: 2px 6px; border-radius: 4px; border: 1px solid var(--border); opacity: 0.7; }
  .ach-card.unlocked.rare .ac-rarity { border-color: #ffaa00; color: #ffaa00; opacity: 1; }
  .ach-card.unlocked.legendary .ac-rarity { border-color: #ff0044; color: #ff0044; opacity: 1; }
  .ach-card.unlocked.rainbow .ac-rarity { border-color: var(--accent); color: var(--accent); opacity: 1; }
  .ach-card .ac-lock { position: absolute; top: 8px; right: 8px; font-size: 0.6rem; opacity: 0.5; }
  .ach-card.unlocked .ac-lock { display: none; }
  .menu-ach-btn { position: fixed; top: 14px; right: 14px; z-index: 6; padding: 10px 14px; background: rgba(0,0,0,0.5); border: 2px solid var(--border); border-radius: 10px; color: var(--text); font-family: 'Orbitron', monospace; font-size: 0.6rem; font-weight: 900; letter-spacing: 2px; cursor: pointer; display: none; align-items: center; gap: 6px; transition: 0.2s; }
  .menu-ach-btn.show { display: flex; }
  .menu-ach-btn:active { border-color: var(--accent); color: var(--accent); box-shadow: 0 0 15px var(--accent); }
  .menu-ach-btn .mab-count { color: #ffaa00; }
  .menu-ach-btn .mab-crown { display: inline-block; font-size: 1.15rem; line-height: 1; filter: drop-shadow(0 0 8px #ffd700) drop-shadow(0 0 16px #ff00ff); margin-top: -5px; margin-bottom: -5px; }
  .menu-settings-btn { position: fixed; top: 14px; left: 14px; z-index: 6; padding: 10px 12px; background: rgba(0,0,0,0.5); border: 2px solid var(--border); border-radius: 10px; color: var(--text); font-family: 'Orbitron', monospace; font-size: 1rem; font-weight: 900; line-height: 1; cursor: pointer; display: none; align-items: center; justify-content: center; transition: 0.2s; min-width: 38px; min-height: 38px; }
  .menu-settings-btn.show { display: flex; }
  .menu-settings-btn:active { border-color: var(--accent); color: var(--accent); box-shadow: 0 0 15px var(--accent); }
  .legendary-theme-btn { display: none; align-self: center; margin: 22px 0 10px; padding: 16px 44px; background: linear-gradient(135deg, rgba(255,215,0,0.16) 0%, rgba(255,140,200,0.12) 50%, rgba(200,120,255,0.14) 100%); border: 2px solid #ffd700; border-radius: 14px; color: #ffd700; font-family: 'Orbitron', monospace; font-size: 0.95rem; font-weight: 900; letter-spacing: 3px; white-space: nowrap; cursor: pointer; box-shadow: 0 0 22px rgba(255,215,0,0.55), 0 0 45px rgba(255,0,255,0.3), inset 0 0 16px rgba(255,215,0,0.12); text-shadow: 0 0 8px #ffd700, 0 0 16px rgba(255,0,255,0.5); transition: all 0.3s ease; position: relative; align-items: center; justify-content: center; text-align: center; line-height: 1; min-width: 250px; box-sizing: border-box; }
  .legendary-theme-btn.show { display: inline-flex; }
  .legendary-theme-btn::before { content: '👑'; position: absolute; left: -26px; top: 50%; transform: translateY(-50%) rotate(-15deg); font-size: 2.6rem; line-height: 1; filter: drop-shadow(0 0 10px #ffd700) drop-shadow(0 0 22px #ff00ff) drop-shadow(0 0 36px rgba(255,215,0,0.5)); pointer-events: none; z-index: 2; }
  .legendary-theme-btn:hover, .legendary-theme-btn:active { background: linear-gradient(135deg, #ffd700 0%, #ff66cc 50%, #b366ff 100%); color: #0a0410; border-color: #ffe066; box-shadow: 0 0 38px #ffd700, 0 0 75px rgba(255,0,255,0.55), inset 0 0 20px rgba(255,255,255,0.22); transform: translateY(-2px); text-shadow: 0 0 6px rgba(10,4,16,0.6); }
  .legendary-theme-btn.active { background: linear-gradient(135deg, #ffd700 0%, #ff66cc 50%, #b366ff 100%); color: #0a0410; border-color: #ffe066; text-shadow: 0 0 6px rgba(10,4,16,0.6); box-shadow: 0 0 38px #ffd700, 0 0 75px rgba(255,0,255,0.55), inset 0 0 20px rgba(255,255,255,0.22); }
  .legendary-hint { display: none; width: 100%; max-width: 560px; text-align: center; font-size: 0.55rem; letter-spacing: 3px; color: #ffd700; margin-top: 8px; opacity: 0.7; text-shadow: 0 0 10px #ffd700; }
  .legendary-hint.show { display: block; }
  .promo-section { width: 100%; max-width: 560px; margin-top: 28px; display: flex; flex-direction: column; gap: 10px; padding: 16px; background: rgba(0,0,0,0.55); border: 2px solid var(--accent); border-radius: 12px; box-shadow: 0 0 22px rgba(0,255,255,0.25); }
  .promo-title { font-size: 0.7rem; font-weight: 900; letter-spacing: 4px; color: var(--accent); text-shadow: 0 0 10px var(--accent); text-align: center; }
  .promo-row { display: flex; gap: 8px; width: 100%; }
  .promo-input { flex: 1; padding: 12px 14px; background: rgba(0,0,0,0.6); border: 2px solid var(--border); border-radius: 8px; color: var(--text); font-family: 'Orbitron', monospace; font-size: 0.75rem; font-weight: 700; letter-spacing: 2px; outline: none; text-transform: uppercase; transition: 0.2s; min-width: 0; }
  .promo-input:focus { border-color: var(--accent); box-shadow: 0 0 12px var(--accent); }
  .promo-input::placeholder { color: var(--text); opacity: 0.4; }
  .promo-btn { padding: 12px 20px; background: transparent; border: 2px solid var(--accent); color: var(--accent); border-radius: 8px; cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.7rem; font-weight: 900; letter-spacing: 2px; transition: 0.2s; flex-shrink: 0; }
  .promo-btn:active { background: var(--accent); color: var(--bg); box-shadow: 0 0 20px var(--accent); }
  .promo-status { font-size: 0.6rem; letter-spacing: 2px; font-weight: 700; text-align: center; min-height: 14px; opacity: 0; transition: opacity 0.3s; }
  .promo-status.show { opacity: 1; }
  .promo-status.ok  { color: #00ff88; text-shadow: 0 0 8px #00ff88; }
  .promo-status.err { color: #ff0044; text-shadow: 0 0 8px #ff0044; }
  .promo-active-list { display: flex; flex-wrap: wrap; gap: 6px; justify-content: center; }
  .promo-active-tag { padding: 4px 8px; border: 1px solid #ffaa00; color: #ffaa00; border-radius: 6px; font-size: 0.5rem; font-weight: 900; letter-spacing: 1px; box-shadow: 0 0 8px rgba(255,170,0,0.4); }
  .promo-toast { position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%) scale(0); z-index: 60; padding: 24px 32px; background: linear-gradient(135deg, rgba(0,0,0,0.98), rgba(20,20,20,0.98)); border: 3px solid var(--accent); border-radius: 16px; box-shadow: 0 0 40px var(--accent), 0 0 80px rgba(0,255,255,0.4); text-align: center; max-width: 400px; width: 90%; opacity: 0; pointer-events: auto; }
  .promo-toast.show { animation: promoToastIn 0.5s cubic-bezier(.2,1.3,.4,1) forwards; }
  @keyframes promoToastIn { 0% { transform: translate(-50%,-50%) scale(0); opacity: 0; } 100% { transform: translate(-50%,-50%) scale(1); opacity: 1; } }
  .promo-toast.hide { animation: promoToastOut 0.5s ease forwards; }
  @keyframes promoToastOut { 0% { transform: translate(-50%,-50%) scale(1); opacity: 1; } 100% { transform: translate(-50%,-50%) scale(0); opacity: 0; } }
  .promo-toast .pt-icon { font-size: 3rem; display: block; margin-bottom: 10px; filter: drop-shadow(0 0 12px var(--accent)); }
  .promo-toast .pt-name { font-size: 1.1rem; font-weight: 900; letter-spacing: 3px; color: var(--accent); text-shadow: 0 0 12px var(--accent); margin-bottom: 10px; }
  .promo-toast .pt-desc { font-size: 0.75rem; font-weight: 700; letter-spacing: 1px; opacity: 0.9; line-height: 1.5; margin-bottom: 12px; }
  .promo-toast .pt-details { font-size: 0.6rem; font-weight: 700; letter-spacing: 1px; opacity: 0.7; line-height: 1.6; padding-top: 10px; border-top: 1px dashed var(--border); }
  .promo-toast .pt-close { margin-top: 16px; padding: 10px 26px; background: transparent; color: var(--accent); border: 2px solid var(--accent); border-radius: 8px; cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.7rem; font-weight: 900; letter-spacing: 3px; transition: 0.2s; }
  .promo-toast .pt-close:active { background: var(--accent); color: var(--bg); box-shadow: 0 0 20px var(--accent); }
  .pl-card { position: relative; padding: 12px 10px; background: rgba(0,0,0,0.55); border: 1.5px solid var(--accent); border-radius: 10px; text-align: center; box-shadow: 0 0 16px rgba(0,255,255,0.25); }
  .pl-card.used { opacity: 0.5; border-color: var(--border); box-shadow: none; filter: grayscale(0.6); }
  .pl-card .pl-icon { font-size: 1.6rem; line-height: 1; margin-bottom: 6px; }
  .pl-card .pl-code { font-size: 0.7rem; font-weight: 900; letter-spacing: 2px; color: #ffd700; text-shadow: 0 0 8px #ffd700; margin-bottom: 4px; }
  .pl-card .pl-name { font-size: 0.6rem; font-weight: 900; letter-spacing: 1px; color: #fff; margin-bottom: 4px; }
  .pl-card .pl-desc { font-size: 0.5rem; letter-spacing: 0.3px; opacity: 0.8; line-height: 1.4; margin-bottom: 4px; }
  .pl-card .pl-details { font-size: 0.45rem; letter-spacing: 0.3px; opacity: 0.6; line-height: 1.4; }
  .pl-card .pl-status { display: inline-block; margin-top: 6px; font-size: 0.42rem; font-weight: 900; letter-spacing: 1px; padding: 2px 6px; border-radius: 4px; border: 1px solid #00ff88; color: #00ff88; }
  .pl-card.used .pl-status { border-color: #ff0044; color: #ff0044; }
  .settings-modal { position: fixed; inset: 0; z-index: 45; background: rgba(0,0,0,0.94); backdrop-filter: blur(8px); display: none; flex-direction: column; align-items: center; padding: 24px 14px; overflow-y: auto; }
  .settings-modal.show { display: flex; animation: settingsFadeIn 0.45s ease-out; }
  @keyframes settingsFadeIn { 0% { opacity: 0; backdrop-filter: blur(0px); } 100% { opacity: 1; backdrop-filter: blur(8px); } }
  .settings-modal-header { display: flex; align-items: center; justify-content: space-between; width: 100%; max-width: 560px; margin-bottom: 18px; flex-shrink: 0; }
  .settings-modal-title { font-size: 1.3rem; font-weight: 900; letter-spacing: 4px; color: var(--accent); text-shadow: 0 0 15px var(--accent); }
  .settings-close { padding: 8px 16px; background: transparent; border: 2px solid var(--border); color: var(--text); border-radius: 8px; cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.65rem; font-weight: 700; letter-spacing: 2px; transition: 0.2s; }
  .settings-close:active { background: var(--accent); color: var(--bg); border-color: var(--accent); }
  .settings-group-card { width: 100%; max-width: 560px; margin-bottom: 14px; padding: 14px 14px 12px; background: rgba(0,0,0,0.55); border: 1.5px solid var(--border); border-radius: 10px; transition: 0.25s; }
  .settings-group-card:hover { border-color: var(--accent); box-shadow: 0 0 14px rgba(0,255,255,0.15); }
  .settings-group-label { font-size: 0.6rem; font-weight: 900; letter-spacing: 3px; color: var(--accent); opacity: 0.9; margin-bottom: 10px; }
  .settings-options { display: flex; flex-wrap: wrap; gap: 8px; }
  .settings-opt { flex: 1 1 auto; min-width: 84px; padding: 11px 12px; background: rgba(0,0,0,0.5); border: 1.5px solid var(--border); border-radius: 8px; color: var(--text); font-family: 'Orbitron', monospace; font-size: 0.6rem; font-weight: 900; letter-spacing: 2px; cursor: pointer; transition: 0.2s; text-align: center; }
  .settings-opt:active { transform: scale(0.97); }
  .settings-opt.active { border-color: var(--accent); color: var(--accent); background: rgba(0,255,255,0.1); box-shadow: 0 0 14px rgba(0,255,255,0.4); }
  body.legendary .settings-opt.active { background: linear-gradient(135deg, rgba(255,215,0,0.15), rgba(255,0,255,0.1)); }
  .settings-reset-card { width: 100%; max-width: 560px; margin-top: 6px; padding: 14px; background: rgba(0,0,0,0.55); border: 1.5px solid #ff0044; border-radius: 10px; text-align: center; }
  .settings-reset-btn { position: relative; overflow: hidden; width: 100%; padding: 14px; background: transparent; border: 2px solid #ff0044; color: #ff0044; border-radius: 10px; cursor: pointer; font-family: 'Orbitron', monospace; font-size: 0.7rem; font-weight: 900; letter-spacing: 3px; transition: 0.2s; user-select: none; -webkit-user-select: none; touch-action: none; }
  .settings-reset-btn:active { box-shadow: 0 0 20px #ff0044; }
  .settings-reset-fill { position: absolute; top: 0; left: 0; height: 100%; width: 0%; background: linear-gradient(90deg, #ff0044, #ff6600); opacity: 0.35; pointer-events: none; }
  .settings-reset-btn .srb-text { position: relative; z-index: 2; }
  .settings-reset-hint { font-size: 0.55rem; letter-spacing: 2px; color: #ffaa00; text-shadow: 0 0 8px rgba(255,170,0,0.5); margin-top: 8px; min-height: 14px; opacity: 0; transition: opacity 0.3s; }
  .settings-reset-hint.show { opacity: 1; }
</style>
</head>
<body>

<canvas id="bg-canvas"></canvas>

<button class="menu-settings-btn" id="menu-settings-btn" onclick="openSettings()" title="Settings">⚙</button>

<button class="menu-ach-btn" id="menu-ach-btn" onclick="openAchievements()">
  <span class="mab-crown">👑</span> <span>ACHIEVEMENTS</span> <span class="mab-count" id="menu-ach-count">0/0</span>
</button>

<div class="menu show" id="menu">
  <div class="menu-title" id="menu-title">NEON TETRIS</div>
  <div class="menu-sub" id="menu-sub">BLOCK PUZZLE</div>
  <button class="menu-btn continue" id="btn-continue" onclick="continueFromMenu()" style="display:none;">
    CONTINUE
    <small id="continue-info"></small>
  </button>
  <button class="menu-btn start" onclick="startNewGame()">NEW GAME</button>
  <button class="menu-btn best" id="btn-best">
    BEST SCORE
    <small id="best-preview">0</small>
  </button>
  <div class="menu-version">v4.4<br><span style="opacity:0.6; font-size:0.45rem; letter-spacing:1.5px;">by Braenorys</span></div>
</div>

<div class="game-column hidden" id="gameColumn">
  <div id="compressionBar">
    <div class="cb-row">
      <div class="cb-block">
        <div class="cb-label">⚠ SQUEEZE</div>
        <div class="cb-value timer" id="cbTimer">0:30</div>
        <div class="cb-progress"><div class="cb-progress-fill timer" id="cbTimerFill"></div></div>
      </div>
      <div class="cb-sep"></div>
      <div class="cb-block">
        <div class="cb-label">RESET</div>
        <div class="cb-value reset" id="cbReset">0/5</div>
        <div class="cb-progress"><div class="cb-progress-fill reset" id="cbResetFill"></div></div>
      </div>
      <div class="cb-sep"></div>
      <div class="cb-block">
        <div class="cb-label">RESTORE</div>
        <div class="cb-value save" id="cbSave">0/10</div>
        <div class="cb-progress"><div class="cb-progress-fill save" id="cbSaveFill"></div></div>
      </div>
      <div class="cb-sep"></div>
      <div class="cb-block">
        <div class="cb-label">FIELD</div>
        <div class="cb-value field" id="cbField">20/20</div>
      </div>
    </div>
  </div>

  <div class="game-wrap" id="gameWrap">
    <div class="board-slot">
      <canvas id="board" width="240" height="480"></canvas>
    </div>
    <div class="side">
      <div class="panel"><span>SCORE</span><span id="score">0</span></div>
      <div class="panel best"><span>BEST</span><span id="best">0</span></div>
      <div class="panel"><span>LINES</span><span id="lines">0</span></div>
      <div class="panel"><span>LEVEL</span><span id="level">1</span></div>
      <div class="panel" id="xrayPanel" style="display:none;">
        <span>X-RAY</span>
        <span style="font-size:0.55rem; letter-spacing:0.5px;" id="xraySpecials">P:0 B:0 K:0</span>
        <span style="font-size:0.55rem; letter-spacing:0.5px;" id="xrayHexa">H:0 S:0</span>
        <span style="font-size:0.5rem; letter-spacing:0.5px; opacity:0.75; margin-top:2px;">NEXT</span>
        <canvas id="xrayNext" width="60" height="40" style="display:block; margin:2px auto 0; background:transparent;"></canvas>
      </div>
      <button class="action-btn pause" id="btn-pause" onclick="togglePause()">PAUSE</button>
      <button class="action-btn save" onclick="saveProgress()">SAVE</button>
      <button class="action-btn reset" onclick="askReset()">RESET</button>
    </div>
  </div>
</div>

<div class="controls hidden" id="controls">
  <button onclick="move(-1)">←</button>
  <button onclick="rotatePiece()">↻</button>
  <button onclick="move(1)">→</button>
  <button id="btn-hard-drop" onpointerdown="hardDropStart(event)" onpointerup="hardDropEnd(event)" onpointerleave="hardDropEnd(event)" onpointercancel="hardDropEnd(event)">⤓</button>
</div>

<div class="pause-indicator" id="pauseIndicator"><div class="pause-icon">❚❚</div></div>

<div class="overlay" id="overlay">
  <h2 id="overlay-title">GAME</h2>
  <p id="overlay-text"></p>
  <button id="overlay-primary" onclick="overlayAction()">OK</button>
  <button class="secondary" id="overlay-secondary" onclick="overlaySecondary()" style="display:none;">NO</button>
  <button class="secondary" id="overlay-tertiary" onclick="overlayTertiary()" style="display:none;">MENU</button>
</div>

<div class="toast" id="toast"></div>
<div class="bonus" id="bonus">TETRIS!</div>
<div class="combo" id="combo">COMBO x2</div>
<div class="praise" id="praise">PERFECT!</div>
<div class="totem-flash" id="totemFlash"></div>
<div class="totem-overlay" id="totemOverlay"></div>

<div class="promo-toast" id="promoToast"></div>

<div class="ach-toast-wrap" id="achToastWrap"></div>

<div class="ach-modal" id="achModal">
  <div class="ach-modal-header">
    <div class="ach-modal-title"><span class="ach-modal-crown">👑</span> ACHIEVEMENTS</div>
    <div class="ach-modal-count" id="achModalCount">0/0</div>
  </div>
  <div class="ach-progress-bar"><div class="ach-progress-fill" id="achProgressFill"></div></div>
  <div class="ach-grid" id="achGrid"></div>
  <button class="legendary-theme-btn" id="legendaryThemeBtn" onclick="toggleLegendaryTheme()">LEGENDARY THEME</button>
  <div class="legendary-hint show" id="legendaryHint">COLLECT ALL ACHIEVEMENTS TO UNLOCK</div>
  <div class="promo-section" id="promoSection">
    <div class="promo-title">⚡ PROMO CODE ⚡</div>
    <div class="promo-row">
      <input type="text" class="promo-input" id="promoInput" placeholder="ENTER PROMO CODE" maxlength="20" autocomplete="off" autocapitalize="characters" spellcheck="false">
      <button class="promo-btn" onclick="applyPromo()">OK</button>
    </div>
    <div class="promo-status" id="promoStatus"></div>
    <div class="promo-active-list" id="promoActiveList"></div>
  </div>
  <button class="ach-close" onclick="closeAchievements()">CLOSE</button>
</div>

<div class="ach-modal" id="promoListModal">
  <div class="ach-modal-header">
    <div class="ach-modal-title"><span class="ach-modal-crown">🔥</span> ALL PROMO CODES</div>
    <div class="ach-modal-count" id="promoListCount">0/0</div>
  </div>
  <div class="ach-progress-bar"><div class="ach-progress-fill" id="promoListFill"></div></div>
  <div class="ach-grid" id="promoListGrid"></div>
  <button class="ach-close" onclick="closePromoCodeList()">CLOSE</button>
</div>

<div class="settings-modal" id="settingsModal">
  <div class="settings-modal-header">
    <div class="settings-modal-title">SETTINGS</div>
    <button class="settings-close" onclick="closeSettings()">CLOSE</button>
  </div>
  <div class="settings-group-card">
    <div class="settings-group-label">MUSIC</div>
    <div class="settings-options" id="settingsMusic">
      <button class="settings-opt" data-val="on" onclick="setMusicSetting('on')">ON</button>
      <button class="settings-opt" data-val="off" onclick="setMusicSetting('off')">OFF</button>
    </div>
  </div>
  <div class="settings-group-card">
    <div class="settings-group-label">SOUND</div>
    <div class="settings-options" id="settingsSound">
      <button class="settings-opt" data-val="mixed" onclick="setSoundSetting('mixed')">MIXED</button>
      <button class="settings-opt" data-val="unified" onclick="setSoundSetting('unified')">UNIFIED</button>
      <button class="settings-opt" data-val="tetris" onclick="setSoundSetting('tetris')">TETRIS</button>
      <button class="settings-opt" data-val="off" onclick="setSoundSetting('off')">OFF</button>
    </div>
  </div>
  <div class="settings-group-card">
    <div class="settings-group-label">THEME</div>
    <div class="settings-options" id="settingsTheme">
      <button class="settings-opt" data-val="dark" onclick="setTheme('dark')">DARK</button>
      <button class="settings-opt" data-val="medium" onclick="setTheme('medium')">MID</button>
      <button class="settings-opt" data-val="light" onclick="setTheme('light')">LIGHT</button>
    </div>
  </div>
  <div class="settings-reset-card">
    <button class="settings-reset-btn" id="settingsResetBtn">
      <span class="settings-reset-fill" id="settingsResetFill"></span>
      <span class="srb-text">RESET PROGRESS</span>
    </button>
    <div class="settings-reset-hint" id="settingsResetHint">HOLD 1.5s TO RESET</div>
  </div>
</div>

<script>
(function lockOrientation() { try { if (screen && screen.orientation && screen.orientation.lock) { screen.orientation.lock('portrait').catch(function(){}); } } catch(e) {} })();
(function freezeOrientation() {
  const initialW = window.innerWidth;
  const initialH = window.innerHeight;
  const portrait = initialH >= initialW;
  function apply() {
    if (!portrait) return;
    document.documentElement.style.width = initialW + 'px';
    document.documentElement.style.height = initialH + 'px';
    document.body.style.width = initialW + 'px';
    document.body.style.height = initialH + 'px';
  }
  window.addEventListener('orientationchange', function(e) { e.preventDefault && e.preventDefault(); apply(); }, { passive: false });
  window.addEventListener('resize', function() { if (window.innerWidth > window.innerHeight) apply(); });
  apply();
})();
(function forcedResetV11() { try { const FLAG = 'neon_tetris_forced_reset_v11'; if (!localStorage.getItem(FLAG)) { const keysToRemove = []; for (let i = 0; i < localStorage.length; i++) { const k = localStorage.key(i); if (k && k.indexOf('neon_tetris') === 0) keysToRemove.push(k); } keysToRemove.forEach(k => localStorage.removeItem(k)); localStorage.setItem(FLAG, 'done'); } } catch(e) {} })();

const COLS = 10, ROWS = 20, SIZE = 24;
const canvas = document.getElementById('board');
const ctx = canvas.getContext('2d');
const SAVE_KEY = 'neon_tetris_save';
const BEST_KEY = 'neon_tetris_best';
const THEME_KEY = 'neon_tetris_theme';
const ACH_KEY = 'neon_tetris_achievements';
const LEGENDARY_UNLOCKED_KEY = 'neon_tetris_legendary_unlocked';
const LEGENDARY_BONUS_KEY = 'neon_tetris_legendary_bonus_claimed';
const MUSIC_SETTING_KEY = 'neon_tetris_music_setting';
const SOUND_SETTING_KEY = 'neon_tetris_sound_setting';

const PENTA_CHANCE = 0.01, BOMB_CHANCE = 0.04, COLOR_KILLER_CHANCE = 0.04;
const FIRST_BLOCK_SPECIAL_CHANCE = 0.005, FIRST_BLOCK_BONUS = 100;
const ALL_ACH_BONUS = 50000, BOMB_RADIUS = 3;
const COMPRESSION_TIME = 30, COMPRESSION_LINES_TO_RESET = 5, COMPRESSION_LINES_TO_RESTORE = 10;
const LUCKY_RESET_CHANCE = 0.15, LUCKY_RESTORE_CHANCE = 0.05;

const SHAPES = [[[1,1,1,1]], [[1,1],[1,1]], [[0,1,0],[1,1,1]], [[1,0,0],[1,1,1]], [[0,0,1],[1,1,1]], [[0,1,1],[1,1,0]], [[1,1,0],[0,1,1]]];
const PENTA_SHAPE = [[1,1,1,1,1]];
const HEXA_SHAPE = [[1,1,1],[1,1,1]];
const COLORS = ['#00ffff','#ffff00','#ff00ff','#ff8800','#0088ff','#00ff88','#ff0044'];

let audioCtx = null, masterLimiter = null;
let musicSetting = 'on', soundSetting = 'mixed';

function loadSettings() {
  try {
    const m = localStorage.getItem(MUSIC_SETTING_KEY);
    const s = localStorage.getItem(SOUND_SETTING_KEY);
    if (m === 'on' || m === 'off') musicSetting = m;
    if (['mixed','unified','tetris','off'].includes(s)) soundSetting = s;
  } catch(e) {}
}
function saveSettings() { try { localStorage.setItem(MUSIC_SETTING_KEY, musicSetting); localStorage.setItem(SOUND_SETTING_KEY, soundSetting); } catch(e) {} }
function makeTanhCurve(amount) { const n = 8192; const curve = new Float32Array(n); for (let i = 0; i < n; i++) { const x = (i / (n - 1)) * 2 - 1; curve[i] = Math.tanh(x * amount); } return curve; }
function initAudio() {
  try {
    if (!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
    if (!masterLimiter) {
      masterLimiter = audioCtx.createWaveShaper();
      masterLimiter.curve = makeTanhCurve(0.85);
      masterLimiter.oversample = '4x';
      masterLimiter.connect(audioCtx.destination);
    }
    if (audioCtx.state === 'suspended') audioCtx.resume();
  } catch(e) {}
}
function beep(freq, dur=0.08, type='sine', vol=0.45) {
  if (!audioCtx) return;
  try {
    if (soundSetting === 'unified') {
      const o = audioCtx.createOscillator(); const g = audioCtx.createGain(); const lp = audioCtx.createBiquadFilter();
      lp.type = 'lowpass'; lp.frequency.value = 700; lp.Q.value = 0.4;
      o.type = type; o.frequency.value = freq * 0.55;
      const now = audioCtx.currentTime; const stopTime = now + dur + 0.02;
      const v = Math.min(Math.max(vol * 0.55, 0.0001), 0.98);
      g.gain.setValueAtTime(0, now); g.gain.linearRampToValueAtTime(v, now + 0.008); g.gain.exponentialRampToValueAtTime(0.0001, now + dur);
      o.connect(g); g.connect(lp);
      if (masterLimiter) lp.connect(masterLimiter); else lp.connect(audioCtx.destination);
      o.start(now); o.stop(stopTime);
      return;
    }
    const o = audioCtx.createOscillator(); const g = audioCtx.createGain();
    o.type = type; o.frequency.value = freq;
    const now = audioCtx.currentTime; const stopTime = now + dur + 0.02;
    const v = Math.min(Math.max(vol, 0.0001), 0.98);
    g.gain.setValueAtTime(0, now); g.gain.linearRampToValueAtTime(v, now + 0.005); g.gain.exponentialRampToValueAtTime(0.0001, now + dur);
    o.connect(g);
    if (masterLimiter) g.connect(masterLimiter); else g.connect(audioCtx.destination);
    o.start(now); o.stop(stopTime);
  } catch(e) {}
}
function playUISound() {
  initAudio();
  if (!audioCtx) return;
  try {
    const now = audioCtx.currentTime;
    const o1 = audioCtx.createOscillator(); const g = audioCtx.createGain(); const lp = audioCtx.createBiquadFilter();
    lp.type = 'lowpass';
    lp.frequency.setValueAtTime(1400, now); lp.frequency.exponentialRampToValueAtTime(500, now + 0.06); lp.Q.value = 0.4;
    o1.type = 'sine';
    o1.frequency.setValueAtTime(320, now); o1.frequency.exponentialRampToValueAtTime(200, now + 0.055);
    g.gain.setValueAtTime(0, now); g.gain.linearRampToValueAtTime(0.13, now + 0.004); g.gain.exponentialRampToValueAtTime(0.06, now + 0.02); g.gain.exponentialRampToValueAtTime(0.0001, now + 0.075);
    o1.connect(g); g.connect(lp);
    if (masterLimiter) lp.connect(masterLimiter); else lp.connect(audioCtx.destination);
    o1.start(now); o1.stop(now + 0.10);
  } catch(e) {}
}
function sfxUIButton() { if (soundSetting === 'off' || soundSetting === 'tetris') return; playUISound(); }
function sfxBlockBase(freq, dur, type, vol) {
  if (soundSetting === 'off') return;
  initAudio();
  if (soundSetting === 'unified') { playUISound(); return; }
  beep(freq, dur, type, vol);
}
function sfxMove() { sfxBlockBase(220, 0.04, 'square', 0.25); }
function sfxRotate() { sfxBlockBase(440, 0.06, 'triangle', 0.34); }
function sfxDrop() { sfxBlockBase(150, 0.08, 'sawtooth', 0.34); }
function sfxClear(n) { if (soundSetting === 'off') return; initAudio(); for (let i = 0; i < n; i++) setTimeout(() => beep(520 + i*120, 0.12, 'sine', 0.63), i*70); }
function sfxLevel() { if (soundSetting === 'off') return; initAudio(); [523,659,784,1047].forEach((f,i) => setTimeout(() => beep(f, 0.15, 'triangle', 0.63), i*90)); }
function sfxWin() { if (soundSetting === 'off') return; initAudio(); [523,659,784,1047,1319].forEach((f,i) => setTimeout(() => beep(f, 0.25, 'sine', 0.84), i*120)); }
function sfxLose() { if (soundSetting === 'off') return; initAudio(); [400,350,300,250,200].forEach((f,i) => setTimeout(() => beep(f, 0.2, 'sawtooth', 0.63), i*130)); }
function sfxTotem() { if (soundSetting === 'off') return; initAudio(); beep(80, 0.5, 'sawtooth', 0.84); [523,659,784,1047,1319,1568].forEach((f,i) => setTimeout(() => beep(f, 0.3, 'sine', 0.84), i*80)); }
function sfxCombo() { if (soundSetting === 'off') return; initAudio(); [660,880,1100].forEach((f,i) => setTimeout(() => beep(f, 0.1, 'triangle', 0.63), i*60)); }
function sfxPenta() { if (soundSetting === 'off') return; initAudio(); [392, 523, 659, 784, 1047, 1319].forEach((f,i) => setTimeout(() => beep(f, 0.25, 'sine', 0.76), i*70)); }
function sfxBomb() { if (soundSetting === 'off') return; initAudio(); beep(80, 0.6, 'sawtooth', 0.98); beep(40, 0.8, 'square', 0.90); [180, 140, 100, 60].forEach((f,i) => setTimeout(() => beep(f, 0.3, 'sawtooth', 0.84), i*60)); }
function sfxColorKiller() { if (soundSetting === 'off') return; initAudio(); [523, 659, 784, 1047].forEach((f,i) => setTimeout(() => beep(f, 0.15, 'sine', 0.76), i*60)); [1047, 880, 659, 523].forEach((f,i) => setTimeout(() => beep(f, 0.15, 'triangle', 0.67), i*80 + 240)); }
function sfxPraise(level) {
  if (soundSetting === 'off') return;
  initAudio();
  if (level === 1) { beep(880, 0.15, 'sine', 0.63); }
  else if (level === 2) { [880, 1100].forEach((f,i) => setTimeout(() => beep(f, 0.15, 'sine', 0.67), i*80)); }
  else if (level === 3) { [880, 1100, 1319].forEach((f,i) => setTimeout(() => beep(f, 0.18, 'sine', 0.71), i*80)); }
  else if (level === 4) { [880, 1047, 1319, 1568].forEach((f,i) => setTimeout(() => beep(f, 0.2, 'sine', 0.76), i*80)); }
  else { [660, 880, 1100, 1319, 1568, 1976].forEach((f,i) => setTimeout(() => beep(f, 0.25, 'triangle', 0.92), i*90)); }
}
function sfxAch(rarity) {
  if (soundSetting === 'off') return;
  initAudio();
  if (soundSetting === 'unified') {
    const playAch = (freq, delay, dur) => {
      setTimeout(() => {
        if (!audioCtx) return;
        try {
          const now = audioCtx.currentTime;
          const o = audioCtx.createOscillator(); const g = audioCtx.createGain(); const lp = audioCtx.createBiquadFilter();
          lp.type = 'lowpass'; lp.frequency.value = 800; lp.Q.value = 0.4;
          o.type = 'sine'; o.frequency.value = freq * 0.7;
          g.gain.setValueAtTime(0, now);
          g.gain.linearRampToValueAtTime(0.14, now + 0.01);
          g.gain.exponentialRampToValueAtTime(0.0001, now + dur);
          o.connect(g); g.connect(lp);
          if (masterLimiter) lp.connect(masterLimiter); else lp.connect(audioCtx.destination);
          o.start(now); o.stop(now + dur + 0.05);
        } catch(e) {}
      }, delay);
    };
    if (rarity === 'legendary') { [523, 659, 784, 1047, 1319, 1568, 2093].forEach((f,i) => playAch(f, i*95, 0.28)); }
    else if (rarity === 'rare') { [659, 880, 1100, 1319].forEach((f,i) => playAch(f, i*90, 0.20)); }
    else if (rarity === 'rainbow') { [523, 659, 784, 1047, 1319, 1568, 2093, 2637].forEach((f,i) => playAch(f, i*80, 0.30)); }
    else { [784, 1047].forEach((f,i) => playAch(f, i*90, 0.16)); }
    return;
  }
  if (rarity === 'legendary') { [523, 659, 784, 1047, 1319, 1568, 2093].forEach((f,i) => setTimeout(() => beep(f, 0.28, 'triangle', 0.84), i*95)); }
  else if (rarity === 'rare') { [659, 880, 1100, 1319].forEach((f,i) => setTimeout(() => beep(f, 0.2, 'sine', 0.76), i*90)); }
  else if (rarity === 'rainbow') { [523, 659, 784, 1047, 1319, 1568, 2093, 2637].forEach((f,i) => setTimeout(() => beep(f, 0.3, 'sine', 0.84), i*80)); }
  else { [784, 1047].forEach((f,i) => setTimeout(() => beep(f, 0.16, 'sine', 0.67), i*90)); }
}
function sfxLegendaryUnlock() { if (soundSetting === 'off') return; initAudio(); [523, 659, 784, 1047, 1319, 1568, 2093, 2637, 3136].forEach((f,i) => setTimeout(() => beep(f, 0.35, 'triangle', 0.92), i*85)); }
function sfxCompress() { if (soundSetting === 'off') return; initAudio(); beep(120, 0.15, 'sawtooth', 0.55); beep(90, 0.20, 'square', 0.45); [140, 110, 85, 65].forEach((f, i) => setTimeout(() => beep(f, 0.10, 'sawtooth', 0.55), i * 50)); setTimeout(() => beep(55, 0.12, 'square', 0.5), 220); }
function sfxTimerReset() { if (soundSetting === 'off') return; initAudio(); [660, 880, 1100, 1320].forEach((f, i) => setTimeout(() => beep(f, 0.10, 'triangle', 0.7), i * 60)); setTimeout(() => beep(1760, 0.18, 'sine', 0.75), 260); }
function sfxExpand() { if (soundSetting === 'off') return; initAudio(); [110, 165, 220, 330, 440, 550].forEach((f, i) => setTimeout(() => beep(f, 0.10, 'triangle', 0.65), i * 45)); setTimeout(() => beep(880, 0.15, 'sine', 0.6), 300); setTimeout(() => beep(1320, 0.15, 'sine', 0.5), 360); }
function attachUIButtonSounds() {
  document.querySelectorAll('button').forEach(btn => {
    if (btn.closest('.controls')) return;
    if (btn.dataset.uiSound === '1') return;
    btn.dataset.uiSound = '1';
    btn.addEventListener('pointerdown', function() { sfxUIButton(); }, { passive: true });
  });
}

const PROMO_KEY = 'neon_tetris_promos';
const PROMO_BONUS_KEY = 'neon_tetris_promo_bonus';
const PROMO_TIMED_KEY = 'neon_tetris_promo_timed';
const PROMO_ONESHOT_KEY = 'neon_tetris_promo_oneshot';
const PROMO_NOPENTA_KEY = 'neon_tetris_promo_nopenta';
const PROMO_XRAY_KEY = 'neon_tetris_promo_xray';

const PROMOCODES = {
  'LEGENDARY': { icon: '👑', name: 'LEGENDARY THEME', desc: 'Unlocks the legendary theme', details: 'Permanent. Available in theme menu.' },
  'BOOST100': { icon: '💰', name: 'BOOST +100', desc: '+100 points next game', details: 'One-time bonus at new game start.' },
  'BOOST500': { icon: '💰', name: 'BOOST +500', desc: '+500 points next game', details: 'One-time bonus at new game start.' },
  'BOOST1000': { icon: '💰', name: 'BOOST +1000', desc: '+1,000 points next game', details: 'One-time bonus at new game start.' },
  'BOOST5000': { icon: '💰', name: 'BOOST +5000', desc: '+5,000 points next game', details: 'One-time bonus at new game start.' },
  'BOOST10000': { icon: '💰', name: 'BOOST +10000', desc: '+10,000 points next game', details: 'One-time bonus at new game start.' },
  'TETRISLOVE': { icon: '💗', name: 'TETRIS LOVE', desc: '+2,500 points next game', details: 'One-time bonus at new game start.' },
  'NEONDREAM': { icon: '💫', name: 'NEON DREAM', desc: '+3,000 points next game', details: 'One-time bonus at new game start.' },
  'BRAENORYS': { icon: '🎨', name: 'BRAENORYS', desc: '+7,777 points next game', details: 'One-time bonus at new game start.' },
  'SLOWMO': { icon: '🐢', name: 'SLOW MOTION', desc: 'Pieces fall 2× slower', details: 'Active for 5 minutes.' },
  'SPEEDUP': { icon: '🔥', name: 'SPEED UP', desc: 'Pieces fall 1.5× faster', details: 'Active for 5 minutes.' },
  'LUCKY': { icon: '🍀', name: 'LUCKY', desc: 'Penta chance ×5 (5%)', details: 'Active for 5 minutes.' },
  'BOMBARD': { icon: '💣', name: 'BOMBARD', desc: 'Bomb chance ×5 (20%)', details: 'Active for 5 minutes.' },
  'RAINBOW': { icon: '🌈', name: 'RAINBOW', desc: 'Color Killer chance ×5 (20%)', details: 'Active for 5 minutes.' },
  'BIGSCORE': { icon: '⭐', name: 'BIG SCORE', desc: 'Line clear score ×2', details: 'Active for 5 minutes.' },
  'COMBOFEST': { icon: '🎉', name: 'COMBO FEST', desc: 'Combo bonus +200 per clear', details: 'Active for 5 minutes.' },
  'CLEANSLATE': { icon: '🧹', name: 'CLEAN SLATE', desc: 'Clears the entire board', details: 'Triggers at next game start.' },
  'EXTRASTART': { icon: '🚀', name: 'EXTRA START', desc: 'Start at level 5', details: 'Triggers at next game start.' },
  'FULLBOMB': { icon: '💥', name: 'FULL BOMB', desc: 'First block is a guaranteed Bomb', details: 'Triggers at next game start.' },
  'FULLPENTA': { icon: '🌈', name: 'FULL PENTA', desc: 'First block is a guaranteed Penta', details: 'Triggers at next game start.' },
  'FULLCOLOR': { icon: '🎯', name: 'FULL COLOR', desc: 'First block is a guaranteed Killer', details: 'Triggers at next game start.' },
  'NOPENTA': { icon: '🚫', name: 'NO PENTA', desc: 'Disables Penta for the next 5 games', details: 'One-time. Applies to the next 5 games then resets.' },
  'CROWNED': { icon: '👑', name: 'CROWNED', desc: 'Golden crown next to LEGENDARY in menu', details: 'Permanent.' },
  'PARTY': { icon: '🎉', name: 'PARTY MODE', desc: 'Colorful particles in menu', details: 'Active while the page is open. Can be entered multiple times.' },
  'XRAY': { icon: '👁️', name: 'X-RAY', desc: 'See special block counters and next piece', details: 'One-time. First 5 games guaranteed, then 10% chance per game.' },
  'ALWAYSXRAY': { icon: '👁️', name: 'ALWAYS X-RAY', desc: 'X-RAY is always active, forever', details: 'Reusable. Permanent until NO X-RAY or full reset.' },
  'NOXRAY': { icon: '🚫', name: 'NO X-RAY', desc: 'Disables X-RAY completely (both modes)', details: 'Reusable. Turn it back on with ALWAYSXRAY or XRAY.' },
  'PROMETHEUS': { icon: '🔥', name: 'PROMETHEUS', desc: 'Reveals the full list of all promo codes', details: 'Can be entered unlimited times. Shows every code with description.' },
  'X100SPEED': { icon: '⚡', name: 'X100 SPEED', desc: 'Pieces fall 100× faster for one game', details: 'Reusable. Applies to the next game only, then resets.' },
  'BOMBSTART': { icon: '💥', name: 'BOMB START', desc: '10 bottom rows filled, Super Bomb drops after 0.5s', details: 'Reusable. Super Bomb clears the field, then compression mode starts.' },
};

let usedPromos = {}, promoBonus = 0, timedEffects = {}, oneShotEffects = {};
let xrayGamesLeft = 0, nopentaGamesLeft = 0, partyActive = false;
let x100SpeedNextGame = false, bombStartNextGame = false;
let alwaysXrayActive = false, xrayDisabled = false;

function loadPromos() {
  try {
    usedPromos = JSON.parse(localStorage.getItem(PROMO_KEY) || '{}');
    promoBonus = parseInt(localStorage.getItem(PROMO_BONUS_KEY) || '0');
    timedEffects = JSON.parse(localStorage.getItem(PROMO_TIMED_KEY) || '{}');
    oneShotEffects = JSON.parse(localStorage.getItem(PROMO_ONESHOT_KEY) || '{}');
    xrayGamesLeft = parseInt(localStorage.getItem(PROMO_XRAY_KEY) || '0');
    nopentaGamesLeft = parseInt(localStorage.getItem(PROMO_NOPENTA_KEY) || '0');
    alwaysXrayActive = localStorage.getItem('neon_tetris_always_xray') === 'yes';
    xrayDisabled = localStorage.getItem('neon_tetris_xray_disabled') === 'yes';
  } catch(e) {
    usedPromos = {}; promoBonus = 0; timedEffects = {};
    oneShotEffects = {}; xrayGamesLeft = 0; nopentaGamesLeft = 0;
    alwaysXrayActive = false; xrayDisabled = false;
  }
  partyActive = false;
}
function savePromos() {
  try {
    localStorage.setItem(PROMO_KEY, JSON.stringify(usedPromos));
    localStorage.setItem(PROMO_BONUS_KEY, promoBonus.toString());
    localStorage.setItem(PROMO_TIMED_KEY, JSON.stringify(timedEffects));
    localStorage.setItem(PROMO_ONESHOT_KEY, JSON.stringify(oneShotEffects));
    localStorage.setItem(PROMO_XRAY_KEY, xrayGamesLeft.toString());
    localStorage.setItem(PROMO_NOPENTA_KEY, nopentaGamesLeft.toString());
  } catch(e) {}
}
function isTimedActive(key) { const t = timedEffects[key]; if (!t) return false; if (Date.now() > t) { delete timedEffects[key]; savePromos(); return false; } return true; }
function applyPromo() {
  initAudio();
  const input = document.getElementById('promoInput');
  const raw = (input.value || '').trim();
  const code = raw.toUpperCase();
  if (!code) { showPromoStatus('ENTER A CODE', 'err'); return; }
  if (!PROMOCODES[code]) { showPromoStatus('INVALID CODE', 'err'); return; }
  if (code === 'PARTY') { partyActive = true; document.getElementById('bg-canvas').classList.add('party'); showPromoModal(code); showPromoStatus('✓ ACTIVATED', 'ok'); input.value = ''; return; }
  if (code === 'PROMETHEUS') { showPromoCodeList(); showPromoStatus('✓ REVEALED', 'ok'); input.value = ''; return; }
  if (code === 'X100SPEED') { x100SpeedNextGame = true; showPromoModal(code); showPromoStatus('✓ ACTIVATED', 'ok'); input.value = ''; return; }
  if (code === 'BOMBSTART') { bombStartNextGame = true; showPromoModal(code); showPromoStatus('✓ ACTIVATED', 'ok'); input.value = ''; return; }
  if (code === 'ALWAYSXRAY') { alwaysXrayActive = true; xrayDisabled = false; localStorage.setItem('neon_tetris_always_xray', 'yes'); localStorage.setItem('neon_tetris_xray_disabled', 'no'); showPromoModal(code); showPromoStatus('✓ ACTIVATED', 'ok'); input.value = ''; return; }
  if (code === 'NOXRAY') { xrayDisabled = true; alwaysXrayActive = false; localStorage.setItem('neon_tetris_xray_disabled', 'yes'); localStorage.setItem('neon_tetris_always_xray', 'no'); showPromoModal(code); showPromoStatus('✓ ACTIVATED', 'ok'); input.value = ''; return; }
  if (usedPromos[code]) { showPromoStatus('ALREADY USED', 'err'); return; }
  usedPromos[code] = true;
  if (code === 'LEGENDARY') { localStorage.setItem(LEGENDARY_UNLOCKED_KEY, 'yes'); revealLegendaryThemeButton(); }
  else if (code === 'BOOST100') { promoBonus += 100; }
  else if (code === 'BOOST500') { promoBonus += 500; }
  else if (code === 'BOOST1000') { promoBonus += 1000; }
  else if (code === 'BOOST5000') { promoBonus += 5000; }
  else if (code === 'BOOST10000') { promoBonus += 10000; }
  else if (code === 'TETRISLOVE') { promoBonus += 2500; }
  else if (code === 'NEONDREAM') { promoBonus += 3000; }
  else if (code === 'BRAENORYS') { promoBonus += 7777; }
  else if (['SLOWMO','SPEEDUP','LUCKY','BOMBARD','RAINBOW','BIGSCORE','COMBOFEST'].includes(code)) { timedEffects[code] = Date.now() + 5 * 60 * 1000; }
  else if (code === 'CLEANSLATE') { oneShotEffects.CLEANSLATE = true; }
  else if (code === 'EXTRASTART') { oneShotEffects.EXTRASTART = true; }
  else if (code === 'FULLBOMB') { oneShotEffects.FULLBOMB = true; }
  else if (code === 'FULLPENTA') { oneShotEffects.FULLPENTA = true; }
  else if (code === 'FULLCOLOR') { oneShotEffects.FULLCOLOR = true; }
  else if (code === 'NOPENTA') { nopentaGamesLeft = 5; }
  else if (code === 'XRAY') { xrayGamesLeft = 5; }
  else if (code === 'CROWNED') { document.body.classList.add('crowned-promo'); }
  savePromos();
  showPromoModal(code);
  showPromoStatus('✓ ACTIVATED', 'ok');
  input.value = '';
  renderActivePromos();
}
function showPromoStatus(msg, type) { const el = document.getElementById('promoStatus'); el.textContent = msg; el.className = 'promo-status show ' + type; setTimeout(() => { el.classList.remove('show'); }, 2500); }
let promoToastTimer = null;
function showPromoModal(code) {
  const def = PROMOCODES[code];
  if (!def) return;
  const el = document.getElementById('promoToast');
  if (promoToastTimer) { clearTimeout(promoToastTimer); promoToastTimer = null; }
  el.className = 'promo-toast';
  el.innerHTML = `<div class="pt-icon">${def.icon}</div><div class="pt-name">${def.name}</div><div class="pt-desc">${def.desc}</div><div class="pt-details">${def.details}</div><button class="pt-close" onclick="closePromoToast()">CLOSE</button>`;
  void el.offsetWidth;
  el.classList.add('show'); el.classList.remove('hide');
  promoToastTimer = setTimeout(() => { closePromoToast(); }, 10000);
}
function closePromoToast() { initAudio(); if (promoToastTimer) { clearTimeout(promoToastTimer); promoToastTimer = null; } const el = document.getElementById('promoToast'); el.classList.remove('show'); el.classList.add('hide'); setTimeout(() => { el.className = 'promo-toast'; }, 500); }
function showPromoCodeList() {
  initAudio();
  const modal = document.getElementById('promoListModal');
  const grid = document.getElementById('promoListGrid');
  if (!modal || !grid) return;
  grid.innerHTML = '';
  Object.keys(PROMOCODES).forEach(code => {
    const def = PROMOCODES[code];
    const reusable = ['PARTY', 'PROMETHEUS', 'X100SPEED', 'BOMBSTART', 'ALWAYSXRAY', 'NOXRAY'].includes(code);
    const isUsed = usedPromos[code] && !reusable;
    const card = document.createElement('div');
    card.className = 'pl-card' + (isUsed ? ' used' : '');
    card.innerHTML = `<div class="pl-icon">${def.icon}</div><div class="pl-code">${code}</div><div class="pl-name">${def.name}</div><div class="pl-desc">${def.desc}</div><div class="pl-details">${def.details}</div><div class="pl-status">${isUsed ? 'USED' : 'AVAILABLE'}</div>`;
    grid.appendChild(card);
  });
  const total = Object.keys(PROMOCODES).length;
  const usedCount = Object.keys(usedPromos).filter(c => PROMOCODES[c] && usedPromos[c] && !['PARTY', 'PROMETHEUS', 'X100SPEED', 'BOMBSTART', 'ALWAYSXRAY', 'NOXRAY'].includes(c)).length;
  const c1 = document.getElementById('promoListCount'); const f1 = document.getElementById('promoListFill');
  if (c1) c1.textContent = usedCount + '/' + total;
  if (f1) f1.style.width = (usedCount / total * 100) + '%';
  modal.classList.add('show');
}
function closePromoCodeList() { document.getElementById('promoListModal').classList.remove('show'); }
function renderActivePromos() {
  const list = document.getElementById('promoActiveList');
  if (!list) return;
  list.innerHTML = '';
  Object.keys(timedEffects).forEach(key => {
    if (isTimedActive(key)) {
      const left = Math.ceil((timedEffects[key] - Date.now()) / 1000);
      const m = Math.floor(left / 60), s = left % 60;
      const tag = document.createElement('div');
      tag.className = 'promo-active-tag';
      tag.textContent = `${key} ${m}:${s.toString().padStart(2,'0')}`;
      list.appendChild(tag);
    }
  });
  if (nopentaGamesLeft > 0) { const tag = document.createElement('div'); tag.className = 'promo-active-tag'; tag.textContent = `NOPENTA x${nopentaGamesLeft}`; list.appendChild(tag); }
  if (xrayGamesLeft > 0) { const tag = document.createElement('div'); tag.className = 'promo-active-tag'; tag.textContent = `XRAY x${xrayGamesLeft}`; list.appendChild(tag); }
  if (alwaysXrayActive) { const tag = document.createElement('div'); tag.className = 'promo-active-tag'; tag.textContent = `ALWAYS X-RAY`; list.appendChild(tag); }
  if (promoBonus > 0) { const tag = document.createElement('div'); tag.className = 'promo-active-tag'; tag.textContent = `+${promoBonus} POINTS`; list.appendChild(tag); }
}
setInterval(() => { const modal = document.getElementById('achModal'); if (modal && modal.classList.contains('show')) renderActivePromos(); }, 1000);

const ACH_RARITY_ORDER = { common: 0, rare: 1, legendary: 2, rainbow: 3 };
const ACH_SCORES = { common: 100, rare: 500, legendary: 2000, rainbow: 5000 };

const ACHIEVEMENTS = [
  { id: 'first_blood', name: 'FIRST BLOOD', desc: 'Clear your first line', icon: '🎯', rarity: 'common' },
  { id: 'first_steps', name: 'FIRST STEPS', desc: 'Clear 10 lines total', icon: '👣', rarity: 'common' },
  { id: 'combo_2', name: 'DOUBLE TROUBLE', desc: 'Reach a x2 combo', icon: '🔥', rarity: 'common' },
  { id: 'level_5', name: 'GETTING STARTED', desc: 'Reach level 5', icon: '⚡', rarity: 'common' },
  { id: 'score_10k', name: 'SCORE HUNTER', desc: 'Reach 10,000 points', icon: '💰', rarity: 'common' },
  { id: 'lines_50', name: 'LINE COOK', desc: 'Clear 50 lines total', icon: '📏', rarity: 'common' },
  { id: 'survivor', name: 'SURVIVOR', desc: 'Play 10 games', icon: '🛡️', rarity: 'common' },
  { id: 'speed_drop', name: 'SPEED DROPPER', desc: 'Hard drop 50 pieces', icon: '⏬', rarity: 'common' },
  { id: 'quick_thinker', name: 'QUICK THINKER', desc: 'Rotate pieces 100 times', icon: '🔄', rarity: 'common' },
  { id: 'slider', name: 'SLIDER', desc: 'Move pieces sideways 200 times', icon: '↔️', rarity: 'common' },
  { id: 'bomb_seen_1', name: 'BOMB SPOTTED', desc: 'Place 1 bomb in one game', icon: '💣', rarity: 'common' },
  { id: 'killer_seen_1', name: 'KILLER SPOTTED', desc: 'Place 1 color killer in one game', icon: '🎨', rarity: 'common' },
  { id: 'combo_4', name: 'COMBO MASTER', desc: 'Reach a x4 combo', icon: '💥', rarity: 'rare' },
  { id: 'tetris_1', name: 'TETRIS!', desc: 'Clear 4 lines at once', icon: '🧱', rarity: 'rare' },
  { id: 'level_10', name: 'SPEEDRUNNER', desc: 'Reach level 10', icon: '🏎️', rarity: 'rare' },
  { id: 'score_50k', name: 'HIGH ROLLER', desc: 'Reach 50,000 points', icon: '💎', rarity: 'rare' },
  { id: 'lines_200', name: 'LINE LORD', desc: 'Clear 200 lines total', icon: '📐', rarity: 'rare' },
  { id: 'veteran', name: 'VETERAN', desc: 'Play 50 games', icon: '🎖️', rarity: 'rare' },
  { id: 'perfect_clear', name: 'PERFECT CLEAR', desc: 'Clear the entire board', icon: '🧹', rarity: 'rare' },
  { id: 'iron_will', name: 'IRON WILL', desc: 'Play 5 games in a row without pause', icon: '🪨', rarity: 'rare' },
  { id: 'demolition', name: 'DEMOLITION', desc: 'Trigger 10 bomb explosions', icon: '🧨', rarity: 'rare' },
  { id: 'chroma_kill', name: 'CHROMA KILL', desc: 'Use the color killer 10 times', icon: '🌈', rarity: 'rare' },
  { id: 'bomb_seen_5', name: 'BOMB ENTHUSIAST', desc: 'Place 5 bombs in one game', icon: '💥', rarity: 'rare' },
  { id: 'bomb_seen_10', name: 'BOMB COLLECTOR', desc: 'Place 10 bombs in one game', icon: '🧨', rarity: 'rare' },
  { id: 'killer_seen_5', name: 'COLOR ENTHUSIAST', desc: 'Place 5 color killers in one game', icon: '🎭', rarity: 'rare' },
  { id: 'killer_seen_10', name: 'COLOR COLLECTOR', desc: 'Place 10 color killers in one game', icon: '🖌️', rarity: 'rare' },
  { id: 'tetris_5', name: 'TETRIS ADDICT', desc: 'Clear 4 lines at once 5 times', icon: '🏗️', rarity: 'legendary' },
  { id: 'level_15', name: 'UNSTOPPABLE', desc: 'Reach level 15', icon: '🚀', rarity: 'legendary' },
  { id: 'score_100k', name: 'LEGEND', desc: 'Reach 100,000 points', icon: '👑', rarity: 'legendary' },
  { id: 'clean_win', name: 'FLAWLESS', desc: 'Win with no game over', icon: '✨', rarity: 'legendary' },
  { id: 'bomb_seen_100', name: 'BOMB ADDICT', desc: 'Place 100 bombs in one game', icon: '☢️', rarity: 'legendary' },
  { id: 'killer_seen_100', name: 'COLOR ADDICT', desc: 'Place 100 color killers in one game', icon: '🌟', rarity: 'legendary' },
  { id: 'penta_1', name: 'PENTA POWER', desc: 'Place 1 Penta in one game', icon: '🌈', rarity: 'rainbow' },
  { id: 'penta_5', name: 'PENTA x5', desc: 'Place 5 Pentas in one game', icon: '🌠', rarity: 'rainbow' },
  { id: 'penta_10', name: 'PENTA x10', desc: 'Place 10 Pentas in one game', icon: '💫', rarity: 'rainbow' },
  { id: 'the_one', name: 'THE ONE', desc: 'Reach 500,000 points in one game', icon: '🌟', rarity: 'rainbow' },
];

let achievements = {};
function loadAchievements() { try { const raw = localStorage.getItem(ACH_KEY); achievements = raw ? JSON.parse(raw) : {}; } catch(e) { achievements = {}; } ACHIEVEMENTS.forEach(a => { if (!achievements[a.id]) achievements[a.id] = { unlocked: false, progress: 0 }; }); }
function saveAchievements() { try { localStorage.setItem(ACH_KEY, JSON.stringify(achievements)); } catch(e) {} }
function getAchCount() { const total = ACHIEVEMENTS.length; const unlocked = ACHIEVEMENTS.filter(a => achievements[a.id] && achievements[a.id].unlocked).length; return { unlocked, total }; }
function allAchievementsUnlocked() { const c = getAchCount(); return c.unlocked === c.total; }
function setAchProgress(id, val, max) { if (!achievements[id]) achievements[id] = { unlocked: false, progress: 0 }; const a = achievements[id]; if (a.unlocked) return; a.progress = Math.min(val, max); if (a.progress >= max) unlockAchievement(id); else saveAchievements(); }
function unlockAchievement(id) {
  if (!achievements[id]) achievements[id] = { unlocked: false, progress: 0 };
  if (achievements[id].unlocked) return;
  achievements[id].unlocked = true;
  achievements[id].progress = 1;
  saveAchievements();
  const def = ACHIEVEMENTS.find(a => a.id === id);
  if (def) queueAchPopup(def);
  updateAchCounts();
  checkAllAchBonus();
}
function checkAllAchBonus() {
  if (!allAchievementsUnlocked()) return;
  if (localStorage.getItem(LEGENDARY_BONUS_KEY) === 'claimed') return;
  localStorage.setItem(LEGENDARY_BONUS_KEY, 'claimed');
  localStorage.setItem(LEGENDARY_UNLOCKED_KEY, 'yes');
  score += ALL_ACH_BONUS;
  if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); }
  updateUI();
  sfxLegendaryUnlock();
  setTimeout(() => showLegendaryReward(), 0);
  revealLegendaryThemeButton();
}
function showLegendaryReward() { setTimeout(() => showBonus('ALL ACHIEVEMENTS! +' + ALL_ACH_BONUS + ' POINTS'), 300); showToast('LEGENDARY THEME UNLOCKED!'); }
function revealLegendaryThemeButton() {
  const btn = document.getElementById('legendaryThemeBtn');
  const hint = document.getElementById('legendaryHint');
  const unlocked = localStorage.getItem(LEGENDARY_UNLOCKED_KEY) === 'yes';
  if (unlocked) { if (btn) btn.classList.add('show'); if (hint) hint.classList.remove('show'); }
  else { if (btn) btn.classList.remove('show'); if (hint) hint.classList.add('show'); }
  const active = (localStorage.getItem(THEME_KEY) || 'dark') === 'legendary';
  if (btn && unlocked) { if (active) btn.classList.add('active'); else btn.classList.remove('active'); }
}
function toggleLegendaryTheme() {
  initAudio();
  const unlocked = localStorage.getItem(LEGENDARY_UNLOCKED_KEY) === 'yes';
  if (!unlocked) return;
  const current = localStorage.getItem(THEME_KEY) || 'dark';
  if (current === 'legendary') { setTheme('dark'); document.getElementById('legendaryThemeBtn').classList.remove('active'); }
  else { setTheme('legendary'); document.getElementById('legendaryThemeBtn').classList.add('active'); }
}
function checkAchThresholds() {
  if (score >= 10000) setAchProgress('score_10k', score, 10000);
  if (score >= 50000) setAchProgress('score_50k', score, 50000);
  if (score >= 100000) setAchProgress('score_100k', score, 100000);
  if (score >= 500000) setAchProgress('the_one', score, 500000);
  if (lines >= 50) setAchProgress('lines_50', lines, 50);
  if (lines >= 200) setAchProgress('lines_200', lines, 200);
  if (level >= 5) setAchProgress('level_5', level, 5);
  if (level >= 10) setAchProgress('level_10', level, 10);
  if (level >= 15) setAchProgress('level_15', level, 15);
}
function trackGameStart() { let plays = parseInt(localStorage.getItem('neon_tetris_plays') || '0'); plays++; localStorage.setItem('neon_tetris_plays', plays); setAchProgress('survivor', plays, 10); setAchProgress('veteran', plays, 50); }
function trackHardDrop() { let drops = parseInt(localStorage.getItem('neon_tetris_drops') || '0'); drops++; localStorage.setItem('neon_tetris_drops', drops); setAchProgress('speed_drop', drops, 50); }
function trackRotate() { let n = parseInt(localStorage.getItem('neon_tetris_rotates') || '0'); n++; localStorage.setItem('neon_tetris_rotates', n); setAchProgress('quick_thinker', n, 100); }
function trackMove() { let n = parseInt(localStorage.getItem('neon_tetris_moves') || '0'); n++; localStorage.setItem('neon_tetris_moves', n); setAchProgress('slider', n, 200); }
function trackNoPauseGame() { let n = parseInt(localStorage.getItem('neon_tetris_nopause_streak') || '0'); n++; localStorage.setItem('neon_tetris_nopause_streak', n); setAchProgress('iron_will', n, 5); }
function resetNoPauseStreak() { localStorage.setItem('neon_tetris_nopause_streak', '0'); }
function trackTetris() { let t = parseInt(localStorage.getItem('neon_tetris_tetris') || '0'); t++; localStorage.setItem('neon_tetris_tetris', t); setAchProgress('tetris_1', t, 1); setAchProgress('tetris_5', t, 5); }
function trackBomb() { let n = parseInt(localStorage.getItem('neon_tetris_bombs') || '0'); n++; localStorage.setItem('neon_tetris_bombs', n); setAchProgress('demolition', n, 10); }
function trackColorKiller() { let n = parseInt(localStorage.getItem('neon_tetris_killers') || '0'); n++; localStorage.setItem('neon_tetris_killers', n); setAchProgress('chroma_kill', n, 10); }
function trackBombSeen() { bombsThisGame++; setAchProgress('bomb_seen_1', bombsThisGame, 1); setAchProgress('bomb_seen_5', bombsThisGame, 5); setAchProgress('bomb_seen_10', bombsThisGame, 10); setAchProgress('bomb_seen_100', bombsThisGame, 100); }
function trackKillerSeen() { killersThisGame++; setAchProgress('killer_seen_1', killersThisGame, 1); setAchProgress('killer_seen_5', killersThisGame, 5); setAchProgress('killer_seen_10', killersThisGame, 10); setAchProgress('killer_seen_100', killersThisGame, 100); }

let achPopupQueue = [], achPopupActive = false, _showingAch = false;
function queueAchPopup(def) { achPopupQueue.push(def); if (!achPopupActive) processAchPopupQueue(); }
function processAchPopupQueue() {
  if (achPopupQueue.length === 0) { achPopupActive = false; return; }
  if (gameOver || won) { achPopupQueue = []; achPopupActive = false; return; }
  if (_showingAch) return;
  achPopupActive = true;
  const def = achPopupQueue.shift();
  setTimeout(() => { if (gameOver || won) { achPopupQueue = []; achPopupActive = false; _showingAch = false; return; } _showingAch = true; showAchGameOverlay(def); }, 0);
}
function showAchGameOverlay(def) {
  paused = true; pausedEverThisGame = true; updatePauseBtn();
  document.getElementById('pauseIndicator').classList.remove('show');
  const reward = ACH_SCORES[def.rarity] || 100;
  score += reward;
  if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); }
  updateUI(); sfxAch(def.rarity);
  overlayMode = 'ach';
  const ov = document.getElementById('overlay'); const title = document.getElementById('overlay-title'); const text = document.getElementById('overlay-text');
  const primary = document.getElementById('overlay-primary'); const secondary = document.getElementById('overlay-secondary'); const tertiary = document.getElementById('overlay-tertiary');
  ov.classList.remove('ach-anim'); void ov.offsetWidth;
  ov.classList.add('show'); ov.classList.add('ach-anim');
  secondary.style.display = 'none'; tertiary.style.display = 'none';
  primary.className = 'success';
  title.textContent = 'ACHIEVEMENT!'; title.className = 'record';
  text.innerHTML = `<span style="font-size:2rem; display:block; margin-bottom:8px;">${def.icon}</span><b style="font-size:1.1rem; color:var(--accent);">${def.name}</b><br><span style="font-size:0.75rem; opacity:0.8;">${def.desc}</span><br><br><b style="color:#ffaa00; font-size:1rem;">+${reward} POINTS</b><br><span style="font-size:0.55rem; opacity:0.6;">${def.rarity.toUpperCase()}</span>`;
  primary.textContent = 'CONTINUE'; primary.className = 'success';
  secondary.textContent = 'MENU'; secondary.style.display = 'block';
}
function continueFromAchOverlay() {
  hideOverlay(); _showingAch = false;
  if (achPopupQueue.length > 0) { processAchPopupQueue(); return; }
  achPopupActive = false; paused = false; updatePauseBtn();
  if (!current && !gameOver && !won) { current = newPiece(); updateXrayPanel(); if (collide(current)) { gameOver = true; endGame(false); return; } }
  dropCounter = 0; lastTime = 0;
  if (rafId) cancelAnimationFrame(rafId);
  rafId = requestAnimationFrame(loop);
}
function menuFromAchOverlay() {
  hideOverlay(); _showingAch = false; achPopupQueue = []; achPopupActive = false;
  if (!gameOver && !won && current) saveProgress();
  document.getElementById('pauseIndicator').classList.remove('show');
  paused = true;
  if (rafId) { cancelAnimationFrame(rafId); rafId = null; }
  showMenu();
}
let achToastQueue = [], achToastActive = false;
function showAchToast(def) { achToastQueue.push(def); if (!achToastActive) processAchToastQueue(); }
function processAchToastQueue() {
  if (achToastQueue.length === 0) { achToastActive = false; return; }
  achToastActive = true;
  const def = achToastQueue.shift();
  const wrap = document.getElementById('achToastWrap');
  const el = document.createElement('div');
  el.className = 'ach-toast ' + def.rarity;
  el.innerHTML = `<div class="ach-icon">${def.icon}</div><div class="ach-body"><div class="ach-label">ACHIEVEMENT UNLOCKED</div><div class="ach-name">${def.name}</div><div class="ach-desc">${def.desc}</div></div><div class="ach-badge">${def.rarity.toUpperCase()}</div>`;
  wrap.appendChild(el);
  requestAnimationFrame(() => el.classList.add('show'));
  setTimeout(() => { el.classList.remove('show'); setTimeout(() => { el.remove(); processAchToastQueue(); }, 500); }, 3200);
}
function updateAchCounts() {
  const c = getAchCount();
  const el1 = document.getElementById('menu-ach-count');
  const el2 = document.getElementById('achModalCount');
  if (el1) el1.textContent = c.unlocked + '/' + c.total;
  if (el2) el2.textContent = c.unlocked + '/' + c.total;
  const fill = document.getElementById('achProgressFill');
  if (fill) fill.style.width = (c.unlocked / c.total * 100) + '%';
}
function openAchievements() { initAudio(); renderAchievements(); revealLegendaryThemeButton(); renderActivePromos(); document.getElementById('achModal').classList.add('show'); }
function closeAchievements() { document.getElementById('achModal').classList.remove('show'); }
function renderAchievements() {
  const grid = document.getElementById('achGrid');
  grid.innerHTML = '';
  const sorted = [...ACHIEVEMENTS].sort((a, b) => ACH_RARITY_ORDER[a.rarity] - ACH_RARITY_ORDER[b.rarity]);
  sorted.forEach(def => {
    const a = achievements[def.id] || { unlocked: false, progress: 0 };
    const card = document.createElement('div');
    card.className = 'ach-card' + (a.unlocked ? ' unlocked' : '') + (a.unlocked ? ' ' + def.rarity : '');
    card.innerHTML = `<div class="ac-lock">🔒</div><div class="ac-icon">${def.icon}</div><div class="ac-name">${def.name}</div><div class="ac-desc">${def.desc}</div><div class="ac-rarity">${def.rarity.toUpperCase()}</div>`;
    grid.appendChild(card);
  });
  updateAchCounts();
}
function checkAchForWinNoPause() { if (!pausedEverThisGame && score >= 100000) { unlockAchievement('clean_win'); } }

function createGrid() { return Array.from({length: ROWS}, () => Array(COLS).fill(0)); }

let grid, current, score = 0, lines = 0, level = 1;
let dropInterval = 800, dropCounter = 0, lastTime = 0;
let gameOver = false, won = false, paused = true;
let rafId = null;
let bestScore = parseInt(localStorage.getItem(BEST_KEY) || '0');
let particles = [], rings = [], shards = [], shines = [];
let clearingLines = [];
let overlayMode = 'pause';
let droppingPiece = null;
let comboCount = 0;
let extremeMode = false;
let rainbowTime = 0;
let winShown = false;
let hardDropStartTime = 0, hardDropHoldInterval = null, hardDropHolding = false;
let pentaThisGame = 0, bombsThisGame = 0, killersThisGame = 0;
let hexaThisGame = 0, superBombsThisGame = 0;
let firstBlockSpawned = false;
let pausedEverThisGame = false;
let nextPiecesQueue = [];

let compressionActive = false;
let compressionRows = ROWS;
let compressionLinesCleared = 0, compressionSaveLines = 0, compressionTimeLeft = COMPRESSION_TIME;
let compressionInterval = null, compressionHideTimer = null;

const PRAISE_PHRASES = [
  { text: 'NICE!', color: '#00ff88' }, { text: 'GOOD!', color: '#00ffcc' },
  { text: 'GREAT!', color: '#00ffff' }, { text: 'COOL!', color: '#66ff66' },
  { text: 'AWESOME!', color: '#ffcc00' }, { text: 'PERFECT!', color: '#ffaa00' },
  { text: 'BRILLIANT!', color: '#ff66ff' }
];
const LEGENDARY_PHRASE = { text: 'LEGENDARY!', color: '#ff0044' };
const BOMB_PHRASES = [{ text: 'BOOM!', color: '#ff6600' }, { text: 'KA-BOOM!', color: '#ff0044' }, { text: 'EXPLOSION!', color: '#ffaa00' }, { text: 'BLOWN UP!', color: '#ff8800' }];
const KILLER_PHRASES = [{ text: 'COLOR WIPE!', color: '#00ffcc' }, { text: 'PURGE!', color: '#ff00ff' }, { text: 'VANISH!', color: '#00ffff' }, { text: 'ERASED!', color: '#ff66ff' }];

function updateCanvasHeight() { const newHeight = compressionRows * SIZE; if (canvas.height !== newHeight) canvas.height = newHeight; }

function generateNextPieceInfo(isLegendary) {
  const r = Math.random();
  const hexaChance = isLegendary ? 0.005 : 0;
  const superBombChance = isLegendary ? 0.0001 : 0;
  if (isLegendary) {
    if (Math.random() < superBombChance) return { shape: [[1,1],[1,1]], color: '#ffd700', special: 'superbomb' };
    if (Math.random() < hexaChance) return { shape: HEXA_SHAPE.map(rr => [...rr]), color: 'hexa', special: 'hexa' };
  }
  const pentaDisabled = nopentaGamesLeft > 0;
  let pentaChance = pentaDisabled ? 0 : (isTimedActive('LUCKY') ? 0.05 : PENTA_CHANCE);
  let bombChance = isTimedActive('BOMBARD') ? 0.20 : BOMB_CHANCE;
  let killerChance = isTimedActive('RAINBOW') ? 0.20 : COLOR_KILLER_CHANCE;
  if (isLegendary) { pentaChance *= 2; bombChance *= 2; killerChance *= 2; }
  if (r < pentaChance) return { shape: PENTA_SHAPE.map(rr => [...rr]), color: 'rainbow', special: 'penta' };
  if (r < pentaChance + bombChance) { const idx = Math.floor(Math.random() * SHAPES.length); return { shape: SHAPES[idx].map(rr => [...rr]), color: COLORS[idx], special: 'bomb' }; }
  if (r < pentaChance + bombChance + killerChance) { const idx = Math.floor(Math.random() * SHAPES.length); return { shape: SHAPES[idx].map(rr => [...rr]), color: COLORS[idx], special: 'killer' }; }
  const idx = Math.floor(Math.random() * SHAPES.length);
  return { shape: SHAPES[idx].map(rr => [...rr]), color: COLORS[idx], special: null };
}

function newPiece() {
  window._bombHandled = null;
  const isLegendary = document.body.classList.contains('legendary');
  while (nextPiecesQueue.length < 4) nextPiecesQueue.push(generateNextPieceInfo(isLegendary));
  if (!firstBlockSpawned) {
    firstBlockSpawned = true;
    if (oneShotEffects.FULLBOMB) { oneShotEffects.FULLBOMB = false; savePromos(); const idx = Math.floor(Math.random() * SHAPES.length); showToast('FULL BOMB!'); const p = { shape: SHAPES[idx].map(r => [...r]), color: COLORS[idx], x: Math.floor((COLS - SHAPES[idx][0].length) / 2), y: 0, isPenta: false, special: 'bomb' }; updateXrayPanel(); return p; }
    if (oneShotEffects.FULLPENTA) { oneShotEffects.FULLPENTA = false; savePromos(); showToast('FULL PENTA!'); const p = { shape: PENTA_SHAPE.map(r => [...r]), color: 'rainbow', x: Math.floor((COLS - PENTA_SHAPE[0].length) / 2), y: 0, isPenta: true, special: 'penta' }; updateXrayPanel(); return p; }
    if (oneShotEffects.FULLCOLOR) { oneShotEffects.FULLCOLOR = false; savePromos(); const idx = Math.floor(Math.random() * SHAPES.length); showToast('FULL COLOR!'); const p = { shape: SHAPES[idx].map(r => [...r]), color: COLORS[idx], x: Math.floor((COLS - SHAPES[idx][0].length) / 2), y: 0, isPenta: false, special: 'killer' }; updateXrayPanel(); return p; }
    if (Math.random() < FIRST_BLOCK_SPECIAL_CHANCE) { const idx = Math.floor(Math.random() * SHAPES.length); score += FIRST_BLOCK_BONUS; if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); } updateUI(); showToast('LUCKY BOMB! +' + FIRST_BLOCK_BONUS); showPraise('LUCKY BOMB!', '#ff6600', 4); sfxBomb(); const p = { shape: SHAPES[idx].map(r => [...r]), color: COLORS[idx], x: Math.floor((COLS - SHAPES[idx][0].length) / 2), y: 0, isPenta: false, special: 'bomb' }; updateXrayPanel(); return p; }
    if (Math.random() < FIRST_BLOCK_SPECIAL_CHANCE * 2) { const idx = Math.floor(Math.random() * SHAPES.length); score += FIRST_BLOCK_BONUS; if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); } updateUI(); showToast('LUCKY KILLER! +' + FIRST_BLOCK_BONUS); showPraise('LUCKY KILLER!', '#00ffcc', 4); sfxColorKiller(); const p = { shape: SHAPES[idx].map(r => [...r]), color: COLORS[idx], x: Math.floor((COLS - SHAPES[idx][0].length) / 2), y: 0, isPenta: false, special: 'killer' }; updateXrayPanel(); return p; }
  }
  const info = nextPiecesQueue.shift();
  nextPiecesQueue.push(generateNextPieceInfo(isLegendary));
  let result;
  if (info.special === 'penta') { sfxPenta(); showToast('PENTA!'); result = { shape: info.shape.map(r => [...r]), color: 'rainbow', x: Math.floor((COLS - info.shape[0].length) / 2), y: 0, isPenta: true, special: 'penta' }; }
  else if (info.special === 'bomb') { showToast('BOMB!'); result = { shape: info.shape.map(r => [...r]), color: info.color, x: Math.floor((COLS - info.shape[0].length) / 2), y: 0, isPenta: false, special: 'bomb' }; }
  else if (info.special === 'killer') { showToast('COLOR KILLER!'); result = { shape: info.shape.map(r => [...r]), color: info.color, x: Math.floor((COLS - info.shape[0].length) / 2), y: 0, isPenta: false, special: 'killer' }; }
  else if (info.special === 'hexa') { sfxPenta(); showToast('HEXA!'); hexaThisGame++; result = { shape: info.shape.map(r => [...r]), color: 'hexa', x: Math.floor((COLS - info.shape[0].length) / 2), y: 0, isPenta: false, special: 'hexa' }; }
  else if (info.special === 'superbomb') { superBombsThisGame++; result = { shape: info.shape.map(r => [...r]), color: info.color, x: Math.floor((COLS - info.shape[0].length) / 2), y: 0, isPenta: false, special: 'superbomb' }; }
  else { result = { shape: info.shape.map(r => [...r]), color: info.color, x: Math.floor((COLS - info.shape[0].length) / 2), y: 0, isPenta: false, special: null }; }
  updateXrayPanel();
  return result;
}

function collide(piece, ox=0, oy=0, shape=null) {
  if (!piece) return true;
  const s = shape || piece.shape;
  for (let y = 0; y < s.length; y++) for (let x = 0; x < s[y].length; x++) {
    if (!s[y][x]) continue;
    const nx = piece.x + x + ox, ny = piece.y + y + oy;
    if (nx < 0 || nx >= COLS || ny >= compressionRows) return true;
    if (ny >= 0 && grid[ny] && grid[ny][nx]) return true;
  }
  return false;
}
function merge(piece) { piece.shape.forEach((row, y) => row.forEach((v, x) => { if (v) { const cx = piece.x + x, cy = piece.y + y; if (cy >= 0 && cy < compressionRows && cx >= 0 && cx < COLS) grid[cy][cx] = piece.color; } })); }
function rotateShape(shape) { return shape[0].map((_, i) => shape.map(row => row[i]).reverse()); }
function spawnRainbowShards(piece, isHardDrop) {
  const count = isHardDrop ? 5 : 3;
  piece.shape.forEach((row, y) => row.forEach((v, x) => {
    if (v) {
      const px = (piece.x + x) * SIZE + SIZE/2, py = (piece.y + y) * SIZE + SIZE/2;
      for (let i = 0; i < count; i++) { const hue = (rainbowTime * 5 + Math.random() * 360) % 360; shards.push({ x: px + (Math.random()-0.5)*SIZE, y: py + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*8, vy: -Math.random()*5 - 1.5, life: 1, color: `hsl(${hue}, 100%, 60%)`, size: 2 + Math.random()*3.5, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.5 }); }
    }
  }));
}
function spawnShards(piece) { piece.shape.forEach((row, y) => row.forEach((v, x) => { if (v) { const px = (piece.x + x) * SIZE + SIZE/2, py = (piece.y + y) * SIZE + SIZE/2; for (let i = 0; i < 3; i++) shards.push({ x: px + (Math.random()-0.5)*SIZE, y: py + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*4, vy: -Math.random()*3 - 1, life: 1, color: piece.color, size: 1.5 + Math.random()*2.5, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.3 }); } })); }
function spawnShine(piece) { piece.shape.forEach((row, y) => row.forEach((v, x) => { if (v) shines.push({ x: (piece.x + x) * SIZE + SIZE/2, y: (piece.y + y) * SIZE + SIZE/2, life: 1, color: piece.color }); })); }
function checkWinCondition() { if (!winShown && score >= 100000) { winShown = true; extremeMode = true; dropInterval = 40; paused = true; sfxWin(); unlockAchievement('score_100k'); checkAchForWinNoPause(); showOverlay('win-100000'); return true; } return false; }
function triggerBombEffect(centerX, centerY) {
  const removed = [];
  for (let y = 0; y < compressionRows; y++) for (let x = 0; x < COLS; x++) { const dx = x - centerX, dy = y - centerY; if (dx*dx + dy*dy <= BOMB_RADIUS * BOMB_RADIUS) { if (grid[y][x]) { removed.push({ x, y, color: grid[y][x] }); grid[y][x] = 0; } } }
  removed.forEach(cell => { const px = cell.x * SIZE + SIZE/2, py = cell.y * SIZE + SIZE/2; for (let i = 0; i < 6; i++) shards.push({ x: px + (Math.random()-0.5)*SIZE, y: py + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*12, vy: -Math.random()*7 - 2, life: 1, color: Math.random() < 0.5 ? '#ff6600' : '#ffcc00', size: 2.5 + Math.random()*4, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.6 }); });
  for (let i = 0; i < 3; i++) rings.push({ x: centerX * SIZE + SIZE/2, y: centerY * SIZE + SIZE/2, r: 10, maxR: BOMB_RADIUS * SIZE * (1.2 + i*0.15), life: 1, color: i === 0 ? '#ffaa00' : (i === 1 ? '#ff6600' : '#ff0044'), speed: 6 + i*2 });
  for (let i = 0; i < 30; i++) { const angle = Math.random() * Math.PI * 2, speed = 3 + Math.random() * 5; particles.push({ x: centerX * SIZE + SIZE/2, y: centerY * SIZE + SIZE/2, vx: Math.cos(angle) * speed, vy: Math.sin(angle) * speed, size: 2 + Math.random()*3, color: Math.random() < 0.5 ? '#ffaa00' : '#ff0044', life: 1 }); }
  canvas.classList.add('totem');
  setTimeout(() => canvas.classList.remove('totem'), 500);
  const phrase = BOMB_PHRASES[Math.floor(Math.random() * BOMB_PHRASES.length)];
  showPraise(phrase.text, phrase.color, 4);
  sfxBomb();
  trackBomb();
  if (removed.length > 0) { const bonus = removed.length * 20 * level; score += bonus; if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); } updateUI(); checkAchThresholds(); }
  if (window._bombStartPending) { window._bombStartPending = false; setTimeout(() => { if (!gameOver && !won && !compressionActive) { showToast('COMPRESSION MODE!'); startCompressionMode(); } }, 600); }
}
function triggerKillerEffect(killerColor) {
  const removed = [];
  for (let y = 0; y < compressionRows; y++) for (let x = 0; x < COLS; x++) if (grid[y][x] === killerColor) { removed.push({ x, y, color: grid[y][x] }); grid[y][x] = 0; }
  removed.forEach(cell => { const px = cell.x * SIZE + SIZE/2, py = cell.y * SIZE + SIZE/2; for (let i = 0; i < 5; i++) shards.push({ x: px + (Math.random()-0.5)*SIZE, y: py + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*7, vy: -Math.random()*5 - 1.5, life: 1, color: killerColor, size: 2 + Math.random()*3, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.5 }); shines.push({ x: px, y: py, life: 1, color: killerColor }); });
  removed.forEach((cell, i) => { if (i % 2 === 0) rings.push({ x: cell.x * SIZE + SIZE/2, y: cell.y * SIZE + SIZE/2, r: 5, maxR: 80, life: 1, color: killerColor, speed: 4 }); });
  rings.push({ x: canvas.width / 2, y: canvas.height / 2, r: 10, maxR: canvas.width * 1.3, life: 1, color: killerColor, speed: 8 });
  canvas.classList.add('flash');
  setTimeout(() => canvas.classList.remove('flash'), 700);
  const phrase = KILLER_PHRASES[Math.floor(Math.random() * KILLER_PHRASES.length)];
  showPraise(phrase.text, phrase.color, 4);
  sfxColorKiller();
  trackColorKiller();
  if (removed.length > 0) { const bonus = removed.length * 50 * level; score += bonus; if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); } updateUI(); checkAchThresholds(); }
}
function triggerSuperBomb() {
  const removed = [];
  for (let y = 0; y < compressionRows; y++) for (let x = 0; x < COLS; x++) if (grid[y][x]) { removed.push({ x, y, color: grid[y][x] }); grid[y][x] = 0; }
  const centerX = canvas.width / 2, centerY = canvas.height / 2;
  removed.forEach(cell => { const px = cell.x * SIZE + SIZE/2, py = cell.y * SIZE + SIZE/2; for (let i = 0; i < 8; i++) shards.push({ x: px + (Math.random()-0.5)*SIZE, y: py + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*15, vy: -Math.random()*9 - 3, life: 1, color: Math.random() < 0.5 ? '#ff0044' : '#ffaa00', size: 3 + Math.random()*5, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.8 }); });
  for (let i = 0; i < 6; i++) rings.push({ x: centerX, y: centerY, r: 5, maxR: canvas.width * (1.6 + i * 0.25), life: 1, color: i % 2 === 0 ? '#ff0044' : '#ff6600', speed: 8 + i * 3.5 });
  for (let i = 0; i < 40; i++) { const angle = Math.random() * Math.PI * 2, speed = 4 + Math.random() * 8; particles.push({ x: centerX, y: centerY, vx: Math.cos(angle) * speed, vy: Math.sin(angle) * speed, size: 2 + Math.random() * 4, color: Math.random() < 0.6 ? '#ff0044' : '#ffd700', life: 1 }); }
  canvas.classList.add('totem');
  setTimeout(() => canvas.classList.remove('totem'), 800);
  showPraise('BOOM!', '#ff0044', 5);
  showBonus('BOOM!');
  sfxBomb();
  trackBomb();
  if (removed.length > 0) { const bonus = removed.length * 100 * level; score += bonus; if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); } updateUI(); checkAchThresholds(); }
  startCompressionMode();
}
function compressBoard() { if (compressionRows <= 1) { gameOver = true; endGame(false); return; } compressionRows--; grid.pop(); updateCanvasHeight(); sfxCompress(); showToast('FIELD COMPRESSED!'); updateCompressionUI(); }
function expandBoard() { if (compressionRows >= ROWS) return; compressionRows++; grid.push(Array(COLS).fill(0)); updateCanvasHeight(); sfxExpand(); showToast('FIELD RESTORED!'); updateCompressionUI(); }
function startCompressionMode() {
  if (compressionActive) return;
  compressionActive = true;
  compressionRows = ROWS; updateCanvasHeight();
  compressionLinesCleared = 0; compressionSaveLines = 0; compressionTimeLeft = COMPRESSION_TIME;
  if (compressionHideTimer) { clearTimeout(compressionHideTimer); compressionHideTimer = null; }
  const bar = document.getElementById('compressionBar');
  if (bar) { bar.classList.remove('hide'); bar.classList.remove('warn'); bar.classList.remove('resetFlash'); bar.classList.remove('fieldFlash'); bar.classList.add('show'); }
  if (window._xrayOn) { const xp = document.getElementById('xrayPanel'); if (xp) xp.style.display = 'block'; }
  updateCompressionUI();
  if (compressionInterval) clearInterval(compressionInterval);
  compressionInterval = setInterval(() => { if (paused || gameOver || won) return; compressionTimeLeft--; if (compressionTimeLeft <= 0) { compressBoard(); compressionLinesCleared = 0; compressionSaveLines = 0; compressionTimeLeft = COMPRESSION_TIME; updateCompressionUI(); } else updateCompressionUI(); }, 1000);
}
function stopCompressionMode() {
  compressionActive = false;
  if (compressionInterval) { clearInterval(compressionInterval); compressionInterval = null; }
  if (compressionHideTimer) { clearTimeout(compressionHideTimer); compressionHideTimer = null; }
  const bar = document.getElementById('compressionBar');
  if (bar) { bar.classList.remove('warn'); bar.classList.remove('resetFlash'); bar.classList.remove('fieldFlash'); bar.classList.add('hide'); compressionHideTimer = setTimeout(() => { bar.classList.remove('show'); bar.classList.remove('hide'); compressionHideTimer = null; }, 400); }
  compressionRows = ROWS; updateCanvasHeight();
  compressionLinesCleared = 0; compressionSaveLines = 0; compressionTimeLeft = COMPRESSION_TIME;
  while (grid.length < ROWS) grid.push(Array(COLS).fill(0));
  while (grid.length > ROWS) grid.pop();
}
function updateCompressionUI() {
  if (!compressionActive) return;
  const t = document.getElementById('cbTimer'), r = document.getElementById('cbReset'), s = document.getElementById('cbSave'), f = document.getElementById('cbField');
  const tf = document.getElementById('cbTimerFill'), rf = document.getElementById('cbResetFill'), sf = document.getElementById('cbSaveFill');
  const bar = document.getElementById('compressionBar');
  if (t) { const m = Math.floor(compressionTimeLeft / 60), sec = compressionTimeLeft % 60; t.textContent = m + ':' + sec.toString().padStart(2, '0'); if (compressionTimeLeft <= 5) t.classList.add('danger'); else t.classList.remove('danger'); }
  if (tf) tf.style.width = ((COMPRESSION_TIME - compressionTimeLeft) / COMPRESSION_TIME * 100) + '%';
  if (r) r.textContent = compressionLinesCleared + '/' + COMPRESSION_LINES_TO_RESET;
  if (rf) rf.style.width = (compressionLinesCleared / COMPRESSION_LINES_TO_RESET * 100) + '%';
  if (s) s.textContent = compressionSaveLines + '/' + COMPRESSION_LINES_TO_RESTORE;
  if (sf) sf.style.width = (compressionSaveLines / COMPRESSION_LINES_TO_RESTORE * 100) + '%';
  if (f) f.textContent = compressionRows + '/' + ROWS;
  if (bar) { if (compressionTimeLeft <= 5) bar.classList.add('warn'); else bar.classList.remove('warn'); }
}
function trackCompressionLines(cleared) {
  if (!compressionActive) return;
  if (Math.random() < LUCKY_RESET_CHANCE) { compressionTimeLeft = COMPRESSION_TIME; compressionLinesCleared = 0; sfxTimerReset(); showPraise('LUCKY RESET!', '#00ff88', 4); const bar = document.getElementById('compressionBar'); if (bar) { bar.classList.remove('resetFlash'); void bar.offsetWidth; bar.classList.add('resetFlash'); setTimeout(() => bar.classList.remove('resetFlash'), 700); } }
  else { compressionLinesCleared += cleared; if (compressionLinesCleared >= COMPRESSION_LINES_TO_RESET) { compressionTimeLeft = COMPRESSION_TIME; compressionLinesCleared = 0; sfxTimerReset(); showPraise('TIMER RESET!', '#00ffff', 3); const bar = document.getElementById('compressionBar'); if (bar) { bar.classList.remove('resetFlash'); void bar.offsetWidth; bar.classList.add('resetFlash'); setTimeout(() => bar.classList.remove('resetFlash'), 700); } } }
  if (Math.random() < LUCKY_RESTORE_CHANCE) { expandBoard(); compressionSaveLines = 0; compressionLinesCleared = 0; compressionTimeLeft = COMPRESSION_TIME; showPraise('LUCKY RESTORE!', '#ffd700', 5); const bar = document.getElementById('compressionBar'); if (bar) { bar.classList.remove('fieldFlash'); void bar.offsetWidth; bar.classList.add('fieldFlash'); setTimeout(() => bar.classList.remove('fieldFlash'), 800); } }
  else { compressionSaveLines += cleared; if (compressionSaveLines >= COMPRESSION_LINES_TO_RESTORE) { expandBoard(); compressionSaveLines = 0; compressionLinesCleared = 0; compressionTimeLeft = COMPRESSION_TIME; showPraise('ROW RESTORED!', '#ffaa00', 4); const bar = document.getElementById('compressionBar'); if (bar) { bar.classList.remove('fieldFlash'); void bar.offsetWidth; bar.classList.add('fieldFlash'); setTimeout(() => bar.classList.remove('fieldFlash'), 800); } } }
  updateCompressionUI();
}
function clearLines() {
  let clearedRows = [];
  for (let y = compressionRows - 1; y >= 0; y--) if (grid[y].every(v => v)) clearedRows.push(y);
  const cleared = clearedRows.length;
  if (cleared) {
    clearedRows.forEach(row => {
      const cells = [];
      for (let x = 0; x < COLS; x++) { cells.push({ x, color: grid[row][x] }); for (let i = 0; i < 3; i++) { const hue = (rainbowTime * 5 + Math.random() * 360) % 360; shards.push({ x: x*SIZE + SIZE/2 + (Math.random()-0.5)*SIZE, y: row*SIZE + SIZE/2 + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*5, vy: -Math.random()*4 - 1.5, life: 1, color: grid[row][x] === 'rainbow' ? `hsl(${hue}, 100%, 60%)` : grid[row][x], size: 2 + Math.random()*3, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.4 }); } }
      clearingLines.push({ row, life: 1, cells });
    });
    const keptRows = [];
    for (let y = 0; y < compressionRows; y++) if (!clearedRows.includes(y)) keptRows.push(grid[y]);
    while (keptRows.length < compressionRows) keptRows.unshift(Array(COLS).fill(0));
    grid.length = 0;
    keptRows.forEach(row => grid.push(row));
    comboCount++;
    const power = Math.min(comboCount, 6);
    if (comboCount >= 2) { showCombo('COMBO x' + comboCount); sfxCombo(); }
    randomPraise(cleared);
    setAchProgress('first_blood', 1, 1);
    let totalLinesEver = parseInt(localStorage.getItem('neon_tetris_total_lines') || '0');
    totalLinesEver += cleared;
    localStorage.setItem('neon_tetris_total_lines', totalLinesEver);
    setAchProgress('first_steps', totalLinesEver, 10);
    if (comboCount >= 2) setAchProgress('combo_2', comboCount, 2);
    if (comboCount >= 4) setAchProgress('combo_4', comboCount, 4);
    if (cleared >= 4) trackTetris();
    const boardEmpty = grid.every(row => row.every(v => !v));
    if (boardEmpty) setAchProgress('perfect_clear', 1, 1);
    let baseScore;
    if (cleared >= 5) baseScore = 500;
    else { const comboBonus = 100 + (comboCount - 1) * 50; baseScore = cleared * comboBonus; }
    baseScore *= level;
    if (isTimedActive('BIGSCORE')) baseScore *= 2;
    if (isTimedActive('COMBOFEST')) baseScore += 200 * cleared;
    score += Math.round(baseScore);
    const centerY = clearedRows.reduce((a,b) => a+b, 0) / clearedRows.length;
    for (let i = 0; i < 1 + power; i++) rings.push({ x: canvas.width/2, y: centerY * SIZE + SIZE/2, r: 10, maxR: canvas.width * (1.1 + power*0.15), life: 1, color: COLORS[Math.floor(Math.random()*COLORS.length)], speed: 2 + i*0.8 + power*0.2 });
    if (cleared === 4) triggerTotem();
    canvas.classList.add('flash');
    setTimeout(() => canvas.classList.remove('flash'), 900);
    lines += cleared;
    sfxClear(cleared);
    const newLevel = Math.floor(lines / 5) + 1;
    if (newLevel > level) { level = newLevel; sfxLevel(); }
    level = newLevel;
    if (!extremeMode) dropInterval = Math.max(80, 800 - (level - 1) * 80);
    if (score > bestScore) { bestScore = score; localStorage.setItem(BEST_KEY, bestScore); }
    updateUI();
    checkAchThresholds();
    if (compressionActive) trackCompressionLines(cleared);
    if (checkWinCondition()) return;
  } else comboCount = 0;
}
function triggerTotem() {
  canvas.classList.add('totem');
  setTimeout(() => canvas.classList.remove('totem'), 600);
  sfxTotem();
  showBonus('TETRIS BONUS! +500');
  const flash = document.getElementById('totemFlash');
  flash.classList.remove('show'); void flash.offsetWidth; flash.classList.add('show');
  const ov = document.getElementById('totemOverlay');
  ov.innerHTML = '';
  for (let i = 0; i < 5; i++) { const ring = document.createElement('div'); ring.className = 'totem-ring'; ring.style.animationDelay = (i * 0.12) + 's'; ring.style.borderColor = i % 2 === 0 ? '#ffaa00' : '#ff6600'; ov.appendChild(ring); }
  ov.classList.add('show');
  setTimeout(() => { ov.classList.remove('show'); ov.innerHTML = ''; }, 1500);
}
function drop() {
  if (!current) return;
  if (current.special === 'hexa') {
    let targetY = current.y;
    while (true) {
      let canMove = true;
      for (let y = 0; y < current.shape.length; y++) for (let x = 0; x < current.shape[y].length; x++) if (current.shape[y][x] && targetY + y + 1 >= compressionRows) { canMove = false; break; }
      if (!canMove) break;
      for (let x = 0; x < current.shape[0].length; x++) if (current.shape[current.shape.length - 1][x]) { const belowX = current.x + x; for (let cy = targetY + current.shape.length; cy < compressionRows; cy++) if (belowX >= 0 && belowX < COLS && grid[cy] && grid[cy][belowX]) { for (let dy = compressionRows - 2; dy >= cy; dy--) grid[dy + 1][belowX] = grid[dy][belowX]; grid[cy][belowX] = 0; } }
      targetY++;
    }
    current.y = targetY;
    landPiece(current, false);
  } else if (current.special === 'superbomb') {
    for (let step = 0; step < 3; step++) {
      let atBottom = false;
      for (let y = 0; y < current.shape.length; y++) for (let x = 0; x < current.shape[y].length; x++) if (current.shape[y][x] && current.y + y + 1 >= compressionRows) atBottom = true;
      if (atBottom) break;
      for (let x = 0; x < current.shape[0].length; x++) if (current.shape[current.shape.length - 1][x]) { const belowX = current.x + x, belowY = current.y + current.shape.length; if (belowX >= 0 && belowX < COLS && belowY >= 0 && belowY < compressionRows && grid[belowY] && grid[belowY][belowX]) { const shX = belowX * SIZE + SIZE/2, shY = belowY * SIZE + SIZE/2; for (let i = 0; i < 5; i++) shards.push({ x: shX + (Math.random()-0.5)*SIZE, y: shY + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*8, vy: -Math.random()*4 - 1, life: 1, color: Math.random() < 0.5 ? '#ffd700' : '#000000', size: 2 + Math.random()*3, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.6 }); grid[belowY][belowX] = 0; } }
      current.y++;
    }
    let atBottomNow = false;
    for (let y = 0; y < current.shape.length; y++) for (let x = 0; x < current.shape[y].length; x++) if (current.shape[y][x] && current.y + y + 1 >= compressionRows) atBottomNow = true;
    if (atBottomNow) landPiece(current, false);
  } else {
    if (!collide(current, 0, 1)) current.y++;
    else landPiece(current, false);
  }
  dropCounter = 0;
}
function landPiece(piece, withShards = false) {
  const special = piece.special;
  if (window._bombHandled === piece) return;
  window._bombHandled = piece;
  merge(piece);
  if (special === 'penta') { pentaThisGame++; if (pentaThisGame >= 1) setAchProgress('penta_1', pentaThisGame, 1); if (pentaThisGame >= 5) setAchProgress('penta_5', pentaThisGame, 5); if (pentaThisGame >= 10) setAchProgress('penta_10', pentaThisGame, 10); }
  else if (special === 'bomb') trackBombSeen();
  else if (special === 'killer') trackKillerSeen();
  if (special === 'bomb') { let sumX = 0, sumY = 0, count = 0; piece.shape.forEach((row, y) => row.forEach((v, x) => { if (v) { sumX += piece.x + x; sumY += piece.y + y; count++; } })); const cx = Math.round(sumX / count), cy = Math.round(sumY / count); triggerBombEffect(cx, cy); }
  else if (special === 'killer') triggerKillerEffect(piece.color);
  else if (special === 'superbomb') { triggerSuperBomb(); if (paused || gameOver || won) return; }
  if (piece.color === 'rainbow') spawnRainbowShards(piece, withShards);
  else if (piece.color === 'hexa') { piece.shape.forEach((row, y) => row.forEach((v, x) => { if (v) { const px = (piece.x + x) * SIZE + SIZE/2, py = (piece.y + y) * SIZE + SIZE/2; for (let i = 0; i < 4; i++) { const hue = (rainbowTime * 5 + Math.random() * 360) % 360; shards.push({ x: px + (Math.random()-0.5)*SIZE, y: py + (Math.random()-0.5)*SIZE, vx: (Math.random()-0.5)*6, vy: -Math.random()*4 - 1, life: 1, color: `hsl(${hue}, 100%, 60%)`, size: 2 + Math.random()*3, rot: Math.random()*Math.PI, rotSpeed: (Math.random()-0.5)*0.5 }); } } })); }
  else { if (withShards) spawnShards(piece); else spawnShine(piece); }
  sfxDrop();
  clearLines();
  if (gameOver || won || paused) return;
  current = newPiece();
  updateXrayPanel();
  if (collide(current)) { gameOver = true; endGame(false); }
}

let _cachedBg = '#000', _cachedBorder = '#222';
function refreshThemeCache() { const cs = getComputedStyle(document.body); _cachedBg = (cs.getPropertyValue('--bg') || '#000').trim(); _cachedBorder = (cs.getPropertyValue('--border') || '#222').trim(); }
function updateUI() { document.getElementById('score').textContent = score; document.getElementById('best').textContent = bestScore; document.getElementById('lines').textContent = lines; document.getElementById('level').textContent = level; updateXrayPanel(); }
function updateXrayPanel() {
  const panel = document.getElementById('xrayPanel');
  if (!panel) return;
  if (!window._xrayOn) { panel.style.display = 'none'; return; }
  panel.style.display = 'block';
  const s = document.getElementById('xraySpecials'), h = document.getElementById('xrayHexa');
  if (s) s.textContent = `P:${pentaThisGame} B:${bombsThisGame} K:${killersThisGame}`;
  if (h) h.textContent = `H:${hexaThisGame} S:${superBombsThisGame}`;
  drawXrayNext();
}
function drawXrayNext() {
  const c = document.getElementById('xrayNext');
  if (!c || !window._xrayOn) return;
  const cx = c.getContext('2d');
  cx.clearRect(0, 0, c.width, c.height);
  const cell = 10;
  const p = nextPiecesQueue[0];
  if (!p) return;
  const isSpecial = p.special && p.special !== null;
  if (isSpecial) {
    cx.shadowColor = '#ffaa00'; cx.shadowBlur = 6; cx.fillStyle = 'rgba(255, 170, 0, 0.15)'; cx.strokeStyle = '#ffaa00'; cx.lineWidth = 1.5;
    const boxSize = 28, bx = (c.width - boxSize) / 2, by = (c.height - boxSize) / 2;
    cx.fillRect(bx, by, boxSize, boxSize); cx.strokeRect(bx, by, boxSize, boxSize);
    cx.shadowBlur = 0; cx.fillStyle = '#ffaa00'; cx.font = 'bold 18px "Orbitron", monospace'; cx.textAlign = 'center'; cx.textBaseline = 'middle';
    cx.fillText('?', c.width / 2, c.height / 2 + 1);
    return;
  }
  const shape = p.shape, w = shape[0].length, hgt = shape.length;
  const ox = (c.width - w * cell) / 2, oy = (c.height - hgt * cell) / 2;
  let color = p.color;
  if (color === 'rainbow') color = '#ff00ff';
  else if (color === 'hexa') color = '#ffd700';
  cx.shadowColor = color; cx.shadowBlur = 4; cx.strokeStyle = color; cx.lineWidth = 1.2; cx.fillStyle = color + '33';
  for (let y = 0; y < hgt; y++) for (let x = 0; x < w; x++) if (shape[y][x]) { cx.fillRect(ox + x * cell + 1, oy + y * cell + 1, cell - 2, cell - 2); cx.strokeRect(ox + x * cell + 1, oy + y * cell + 1, cell - 2, cell - 2); }
  cx.shadowBlur = 0;
}
function getRainbowColor(offset) { const hue = (rainbowTime * 3 + offset * 30) % 360; return `hsl(${hue}, 100%, 60%)`; }
function getHexaGradientColor(x) {
  const stops = [[255, 215, 0],[255, 140, 200],[179, 102, 255],[255, 140, 200],[255, 215, 0]];
  const t = (x % 3) / 2, seg = t * (stops.length - 1), i = Math.floor(seg), f = seg - i;
  const c1 = stops[i], c2 = stops[Math.min(i + 1, stops.length - 1)];
  const r = Math.round(c1[0] + (c2[0] - c1[0]) * f), g = Math.round(c1[1] + (c2[1] - c1[1]) * f), b = Math.round(c1[2] + (c2[2] - c1[2]) * f);
  return `rgb(${r},${g},${b})`;
}
function drawCell(x, y, color, alpha=1, special=null) {
  const px = x * SIZE, py = y * SIZE, pad = 1.5, r = 4;
  ctx.globalAlpha = alpha;
  const isRainbow = color === 'rainbow', isHexa = color === 'hexa', isLight = document.body.classList.contains('light'), isSuperBomb = special === 'superbomb';
  let actualColor;
  if (isHexa) actualColor = getHexaGradientColor(x);
  else if (isRainbow) actualColor = getRainbowColor(x + y);
  else if (isSuperBomb) actualColor = '#ffd700';
  else if (isLight && color === '#00ffff') actualColor = '#0099bb';
  else actualColor = color;
  ctx.shadowColor = actualColor;
  ctx.shadowBlur = (isRainbow || isHexa) ? 10 : 5;
  let grad;
  if (isHexa) { grad = ctx.createLinearGradient(px, py, px + SIZE, py + SIZE); grad.addColorStop(0, getHexaGradientColor(x)); grad.addColorStop(0.5, getHexaGradientColor(x + 1)); grad.addColorStop(1, getHexaGradientColor(x + 2)); }
  else if (isRainbow) { grad = ctx.createLinearGradient(px, py, px + SIZE, py + SIZE); grad.addColorStop(0, getRainbowColor(x + y)); grad.addColorStop(1, getRainbowColor(x + y + 3)); }
  else { grad = ctx.createLinearGradient(px, py, px + SIZE, py + SIZE); grad.addColorStop(0, lighten(actualColor, 15)); grad.addColorStop(1, actualColor); }
  if (isSuperBomb) {
    ctx.fillStyle = 'rgba(10, 5, 0, 0.9)';
    roundRect(px + pad, py + pad, SIZE - pad*2, SIZE - pad*2, r); ctx.fill();
    ctx.shadowBlur = 0;
    const t = rainbowTime * 0.15, pulse = 0.5 + 0.5 * Math.sin(t), goldShade = 200 + Math.floor(pulse * 55);
    ctx.strokeStyle = `rgba(${goldShade}, ${Math.floor(goldShade * 0.85)}, 0, 1)`; ctx.lineWidth = 1.5;
    roundRect(px + pad + 1, py + pad + 1, SIZE - pad*2 - 2, SIZE - pad*2 - 2, r); ctx.stroke();
  } else if (isLight) {
    ctx.fillStyle = actualColor; ctx.globalAlpha = alpha * 0.2;
    roundRect(px + pad, py + pad, SIZE - pad*2, SIZE - pad*2, r); ctx.fill();
    ctx.globalAlpha = alpha; ctx.strokeStyle = actualColor; ctx.lineWidth = 1.5; ctx.stroke();
  } else {
    ctx.fillStyle = grad; roundRect(px + pad, py + pad, SIZE - pad*2, SIZE - pad*2, r); ctx.fill();
    ctx.shadowBlur = 0;
    ctx.strokeStyle = 'rgba(255,255,255,0.35)'; ctx.lineWidth = 1;
    ctx.beginPath(); ctx.moveTo(px + pad + r, py + pad); ctx.lineTo(px + SIZE - pad - r, py + pad); ctx.moveTo(px + pad, py + pad + r); ctx.lineTo(px + pad, py + SIZE - pad - r); ctx.stroke();
    ctx.strokeStyle = 'rgba(0,0,0,0.35)';
    ctx.beginPath(); ctx.moveTo(px + SIZE - pad - r, py + SIZE - pad); ctx.lineTo(px + pad + r, py + SIZE - pad); ctx.moveTo(px + SIZE - pad, py + SIZE - pad - r); ctx.lineTo(px + SIZE - pad, py + pad + r); ctx.stroke();
  }
  if (special === 'bomb') {
    const pulse = 0.5 + 0.5 * Math.sin(rainbowTime * 0.15);
    ctx.strokeStyle = `rgba(255, 100, 0, ${0.5 + pulse * 0.5})`; ctx.lineWidth = 2; ctx.shadowColor = '#ff6600'; ctx.shadowBlur = 12 + pulse * 10;
    roundRect(px + pad, py + pad, SIZE - pad*2, SIZE - pad*2, r); ctx.stroke();
    ctx.shadowBlur = 8; ctx.fillStyle = `rgba(255, 200, 50, ${0.7 + pulse * 0.3})`;
    ctx.beginPath(); ctx.arc(px + SIZE/2, py + SIZE/2, 2 + pulse * 1.5, 0, Math.PI * 2); ctx.fill();
    const ringR = 6 + pulse * 6;
    ctx.strokeStyle = `rgba(255, 80, 0, ${0.6 - pulse * 0.5})`; ctx.lineWidth = 1.5; ctx.shadowBlur = 8;
    ctx.beginPath(); ctx.arc(px + SIZE/2, py + SIZE/2, ringR, 0, Math.PI * 2); ctx.stroke();
  } else if (special === 'killer') {
    const pulse = 0.5 + 0.5 * Math.sin(rainbowTime * 0.2);
    ctx.strokeStyle = actualColor; ctx.lineWidth = 2; ctx.shadowColor = actualColor; ctx.shadowBlur = 12 + pulse * 12;
    roundRect(px + pad, py + pad, SIZE - pad*2, SIZE - pad*2, r); ctx.stroke();
    const angle = rainbowTime * 0.08, cxp = px + SIZE/2, cyp = py + SIZE/2, orbit = 5 + pulse * 2;
    for (let i = 0; i < 3; i++) { const a = angle + i * Math.PI * 2 / 3, ox = cxp + Math.cos(a) * orbit, oy = cyp + Math.sin(a) * orbit; ctx.fillStyle = actualColor; ctx.shadowColor = actualColor; ctx.shadowBlur = 8; ctx.beginPath(); ctx.arc(ox, oy, 1.6, 0, Math.PI * 2); ctx.fill(); }
    ctx.strokeStyle = `rgba(255,255,255,${0.4 + pulse * 0.4})`; ctx.lineWidth = 1; ctx.shadowBlur = 6;
    ctx.beginPath(); ctx.arc(cxp, cyp, orbit + 3, 0, Math.PI * 2); ctx.stroke();
  }
  ctx.shadowBlur = 0; ctx.globalAlpha = 1;
}
function roundRect(x, y, w, h, r) { ctx.beginPath(); ctx.moveTo(x + r, y); ctx.lineTo(x + w - r, y); ctx.quadraticCurveTo(x + w, y, x + w, y + r); ctx.lineTo(x + w, y + h - r); ctx.quadraticCurveTo(x + w, y + h, x + w - r, y + h); ctx.lineTo(x + r, y + h); ctx.quadraticCurveTo(x, y + h, x, y + h - r); ctx.lineTo(x, y + r); ctx.quadraticCurveTo(x, y, x + r, y); ctx.closePath(); }
function lighten(hex, percent) { if (hex.startsWith('hsl') || hex.startsWith('rgb')) return hex; const num = parseInt(hex.replace('#',''), 16); let r = (num >> 16) + Math.round(255 * percent / 100), g = ((num >> 8) & 0x00FF) + Math.round(255 * percent / 100), b = (num & 0x0000FF) + Math.round(255 * percent / 100); r = Math.min(255, r); g = Math.min(255, g); b = Math.min(255, b); return '#' + ((r << 16) | (g << 8) | b).toString(16).padStart(6, '0'); }
function draw() {
  const isLight = document.body.classList.contains('light');
  if (isLight) {
    ctx.clearRect(0, 0, canvas.width, canvas.height); ctx.fillStyle = _cachedBg; ctx.fillRect(0, 0, canvas.width, canvas.height);
    ctx.strokeStyle = 'rgba(0,0,0,0.13)'; ctx.lineWidth = 0.5; ctx.beginPath();
    for (let i = 0; i <= COLS; i++) { ctx.moveTo(i*SIZE, 0); ctx.lineTo(i*SIZE, canvas.height); }
    for (let i = 0; i <= compressionRows; i++) { ctx.moveTo(0, i*SIZE); ctx.lineTo(canvas.width, i*SIZE); }
    ctx.stroke();
    ctx.strokeStyle = '#555'; ctx.lineWidth = 2; ctx.strokeRect(1, 1, canvas.width - 2, canvas.height - 2);
  } else {
    ctx.clearRect(0, 0, canvas.width, canvas.height); ctx.strokeStyle = _cachedBorder; ctx.lineWidth = 0.5; ctx.beginPath();
    for (let i = 0; i <= COLS; i++) { ctx.moveTo(i*SIZE, 0); ctx.lineTo(i*SIZE, canvas.height); }
    for (let i = 0; i <= compressionRows; i++) { ctx.moveTo(0, i*SIZE); ctx.lineTo(canvas.width, i*SIZE); }
    ctx.stroke();
  }
  if (grid) for (let y = 0; y < compressionRows; y++) { const row = grid[y]; if (!row) continue; for (let x = 0; x < COLS; x++) if (row[x]) drawCell(x, y, row[x]); }
  if (droppingPiece) droppingPiece.shape.forEach((row, y) => row.forEach((v, x) => { if (v) drawCell(droppingPiece.x + x, droppingPiece.y + y, droppingPiece.color, 1, droppingPiece.special); }));
  else if (current && current.shape) current.shape.forEach((row, y) => row.forEach((v, x) => { if (v) drawCell(current.x + x, current.y + y, current.color, 1, current.special); }));
  clearingLines.forEach(c => {
    const life = c.life, progress = 1 - life, py = c.row * SIZE;
    c.cells.forEach((cell, i) => {
      const delay = (i / COLS) * 0.55, localProgress = Math.max(0, Math.min(1, (progress - delay) / 0.45));
      if (localProgress <= 0) return;
      const px = cell.x * SIZE, fadeIn = Math.min(1, localProgress * 2.5), fadeOut = life, cellAlpha = fadeIn * fadeOut;
      ctx.globalAlpha = cellAlpha * 0.55; ctx.fillStyle = '#ffffff'; ctx.shadowColor = '#ffffff'; ctx.shadowBlur = 6;
      ctx.fillRect(px + 2, py + 2, SIZE - 4, SIZE - 4);
      ctx.globalAlpha = cellAlpha * 0.35; ctx.fillStyle = cell.color === 'rainbow' ? getRainbowColor(cell.x) : (cell.color === 'hexa' ? getHexaGradientColor(cell.x) : cell.color);
      ctx.shadowColor = ctx.fillStyle; ctx.shadowBlur = 10; ctx.fillRect(px + 3, py + 3, SIZE - 6, SIZE - 6);
    });
  });
  ctx.shadowBlur = 0; ctx.globalAlpha = 1;
  particles.forEach(p => { ctx.globalAlpha = Math.max(0, p.life); ctx.fillStyle = p.color; if (p.glow !== false) { ctx.shadowColor = p.color; ctx.shadowBlur = 8; } else ctx.shadowBlur = 0; ctx.beginPath(); ctx.arc(p.x, p.y, p.size * p.life, 0, Math.PI*2); ctx.fill(); });
  ctx.shadowBlur = 0; ctx.globalAlpha = 1;
  shards.forEach(s => { ctx.globalAlpha = Math.max(0, s.life); ctx.fillStyle = s.color; ctx.shadowColor = s.color; ctx.shadowBlur = 5; ctx.save(); ctx.translate(s.x, s.y); ctx.rotate(s.rot); ctx.fillRect(-s.size/2, -s.size/2, s.size, s.size); ctx.restore(); });
  ctx.shadowBlur = 0; ctx.globalAlpha = 1;
  shines.forEach(s => { ctx.globalAlpha = s.life * 0.8; ctx.fillStyle = 'rgba(255,255,255,' + (s.life * 0.6) + ')'; ctx.shadowColor = (s.color === 'rainbow' || s.color === 'hexa') ? getRainbowColor(0) : s.color; ctx.shadowBlur = 20; ctx.beginPath(); ctx.arc(s.x, s.y, (1 - s.life) * 18 + 4, 0, Math.PI*2); ctx.fill(); });
  ctx.shadowBlur = 0; ctx.globalAlpha = 1;
  rings.forEach(r => { ctx.globalAlpha = r.life; ctx.strokeStyle = r.color; ctx.shadowColor = r.color; ctx.shadowBlur = 20; ctx.lineWidth = 2 * r.life; ctx.beginPath(); ctx.arc(r.x, r.y, r.r, 0, Math.PI*2); ctx.stroke(); });
  ctx.shadowBlur = 0; ctx.globalAlpha = 1;
}
function updateParticles(dt) {
  rainbowTime += dt / 16;
  for (let i = particles.length - 1; i >= 0; i--) { const p = particles[i]; p.x += p.vx; p.y += p.vy; p.vy += 0.4; p.life -= dt / 700; if (p.life <= 0) { particles[i] = particles[particles.length - 1]; particles.pop(); } }
  for (let i = shards.length - 1; i >= 0; i--) { const s = shards[i]; s.x += s.vx; s.y += s.vy; s.vy += 0.5; s.life -= dt / 900; s.rot += s.rotSpeed; if (s.life <= 0) { shards[i] = shards[shards.length - 1]; shards.pop(); } }
  for (let i = shines.length - 1; i >= 0; i--) { const s = shines[i]; s.life -= dt / 350; if (s.life <= 0) { shines[i] = shines[shines.length - 1]; shines.pop(); } }
  for (let i = rings.length - 1; i >= 0; i--) { const r = rings[i]; r.r += r.speed; r.life -= dt / 600; if (r.life <= 0 || r.r >= r.maxR) { rings[i] = rings[rings.length - 1]; rings.pop(); } }
  for (let i = clearingLines.length - 1; i >= 0; i--) { const c = clearingLines[i]; c.life -= dt / 1100; if (c.life <= 0) { clearingLines[i] = clearingLines[clearingLines.length - 1]; clearingLines.pop(); } }
  if (particles.length > 220) particles.splice(0, particles.length - 220);
  if (shards.length > 220) shards.splice(0, shards.length - 220);
  if (rings.length > 40) rings.splice(0, rings.length - 40);
  if (shines.length > 60) shines.splice(0, shines.length - 60);
}
function loop(time = 0) {
  if (gameOver || won) { draw(); return; }
  let dt = time - lastTime;
  if (dt > 50) dt = 50;
  if (dt < 0) dt = 0;
  lastTime = time;
  if (droppingPiece) {
    const target = droppingPiece.targetY, speed = 1.8;
    if (droppingPiece.y < target) droppingPiece.y = Math.min(target, droppingPiece.y + speed);
    else { const landed = { ...droppingPiece }; droppingPiece = null; current = landed; landPiece(landed, true); }
  } else if (!paused && current) {
    if (current.special === 'superbomb') { dropCounter += dt; if (dropCounter > 16) { drop(); dropCounter = 0; } }
    else {
      let speedMultiplier = hardDropHolding ? 1/3 : 1;
      if (isTimedActive('SLOWMO')) speedMultiplier *= 2;
      if (isTimedActive('SPEEDUP')) speedMultiplier *= 0.67;
      dropCounter += dt;
      if (dropCounter > dropInterval * speedMultiplier) { drop(); dropCounter = 0; }
    }
  }
  updateParticles(dt);
  draw();
  rafId = requestAnimationFrame(loop);
}
function showMenu() {
  initAudio();
  document.getElementById('menu').classList.add('show');
  document.getElementById('gameColumn').classList.add('hidden');
  document.getElementById('controls').classList.add('hidden');
  document.getElementById('bg-canvas').classList.add('show');
  document.getElementById('pauseIndicator').classList.remove('show');
  document.getElementById('menu-ach-btn').classList.add('show');
  document.getElementById('menu-settings-btn').classList.add('show');
  paused = true;
  if (rafId) { cancelAnimationFrame(rafId); rafId = null; }
  if (hasSavedGame()) {
    document.getElementById('btn-continue').style.display = 'block';
    try { const data = JSON.parse(localStorage.getItem(SAVE_KEY)); document.getElementById('continue-info').textContent = `SCORE: ${data.score} · LINES: ${data.lines}`; }
    catch(e) { localStorage.removeItem(SAVE_KEY); document.getElementById('btn-continue').style.display = 'none'; }
  } else document.getElementById('btn-continue').style.display = 'none';
  document.getElementById('best-preview').textContent = bestScore;
  revealLegendaryThemeButton();
  updateAchCounts();
  renderActivePromos();
  const bg = document.getElementById('bg-canvas');
  if (partyActive) bg.classList.add('party'); else bg.classList.remove('party');
  if (!bgRafId) startBgAnimation();
}
function hideMenu() {
  document.getElementById('menu').classList.remove('show');
  document.getElementById('gameColumn').classList.remove('hidden');
  document.getElementById('controls').classList.remove('hidden');
  document.getElementById('bg-canvas').classList.remove('show');
  document.getElementById('menu-ach-btn').classList.remove('show');
  document.getElementById('menu-settings-btn').classList.remove('show');
  document.getElementById('bg-canvas').classList.remove('party');
  stopBgAnimation();
}
function continueFromMenu() { initAudio(); if (loadProgress()) { hideMenu(); paused = false; gameOver = false; won = false; lastTime = 0; dropCounter = 0; updatePauseBtn(); if (rafId) cancelAnimationFrame(rafId); rafId = requestAnimationFrame(loop); } else startNewGame(); }
function askFullReset() { initAudio(); doFullReset(); }
function askReset() { initAudio(); showOverlay('reset'); }
function openSettings() { initAudio(); renderSettingsUI(); document.getElementById('settingsModal').classList.add('show'); }
function closeSettings() { document.getElementById('settingsModal').classList.remove('show'); }
function renderSettingsUI() {
  const mBtns = document.querySelectorAll('#settingsMusic .settings-opt');
  mBtns.forEach(b => b.classList.toggle('active', b.dataset.val === musicSetting));
  const sBtns = document.querySelectorAll('#settingsSound .settings-opt');
  sBtns.forEach(b => b.classList.toggle('active', b.dataset.val === soundSetting));
  const currentTheme = (localStorage.getItem(THEME_KEY) || 'dark');
  const tBtns = document.querySelectorAll('#settingsTheme .settings-opt');
  tBtns.forEach(b => b.classList.toggle('active', b.dataset.val === currentTheme));
}
function setMusicSetting(val) { musicSetting = val; saveSettings(); renderSettingsUI(); if (musicSetting === 'on') { if (window._startMusicNow) window._startMusicNow(); } else { if (window._stopMusicNow) window._stopMusicNow(); } }
function setSoundSetting(val) { soundSetting = val; saveSettings(); renderSettingsUI(); }
(function setupResetButton() {
  const btn = document.getElementById('settingsResetBtn');
  const fill = document.getElementById('settingsResetFill');
  const hint = document.getElementById('settingsResetHint');
  if (!btn) return;
  let holdStart = 0, raf = null, hintTimer = null, resetTriggered = false;
  const HOLD_MS = 1500;
  function tick() { const now = performance.now(); const p = Math.min(1, (now - holdStart) / HOLD_MS); fill.style.width = (p * 100) + '%'; if (p >= 1) { resetTriggered = true; cancelHold(); doFullReset(); return; } raf = requestAnimationFrame(tick); }
  function startHold(e) { if (e) e.preventDefault(); resetTriggered = false; holdStart = performance.now(); fill.style.width = '0%'; cancelAnimationFrame(raf); raf = requestAnimationFrame(tick); }
  function cancelHold() { if (raf) cancelAnimationFrame(raf); raf = null; fill.style.width = '0%'; }
  function showHint() { hint.classList.add('show'); if (hintTimer) clearTimeout(hintTimer); hintTimer = setTimeout(() => { hint.classList.remove('show'); }, 2000); }
  function endHold() { const elapsed = performance.now() - holdStart; cancelHold(); if (!resetTriggered && elapsed < HOLD_MS) { showHint(); } }
  btn.addEventListener('pointerdown', startHold);
  btn.addEventListener('pointerup', endHold);
  btn.addEventListener('pointerleave', function() { if (performance.now() - holdStart < HOLD_MS) cancelHold(); });
  btn.addEventListener('pointercancel', cancelHold);
})();

(function setupSwipeControls() {
  const cvs = document.getElementById('board');
  if (!cvs) return;
  let sx = 0, sy = 0, st = 0, tracking = false, moved = false;
  let holdTimer = null, holding = false;
  const SWIPE_MIN = 25;
  const HOLD_DELAY = 220;
  function onDown(e) {
    if (gameOver || won || paused) return;
    const t = e.touches ? e.touches[0] : e;
    if (!t) return;
    sx = t.clientX; sy = t.clientY; st = Date.now();
    tracking = true; moved = false; holding = false;
    if (holdTimer) clearTimeout(holdTimer);
    holdTimer = setTimeout(function() {
      if (!tracking || moved) return;
      if (gameOver || won || paused || !current || droppingPiece) return;
      if (current.special === 'superbomb') return;
      hardDropHolding = true;
      holding = true;
    }, HOLD_DELAY);
  }
  function onMove(e) {
    if (!tracking) return;
    const t = e.touches ? e.touches[0] : e;
    if (!t) return;
    const dx = t.clientX - sx, dy = t.clientY - sy;
    if (Math.abs(dx) > SWIPE_MIN || Math.abs(dy) > SWIPE_MIN) moved = true;
  }
  function onUp(e) {
    if (!tracking) return;
    tracking = false;
    if (holdTimer) { clearTimeout(holdTimer); holdTimer = null; }
    if (holding) { hardDropHolding = false; holding = false; return; }
    const t = e.changedTouches ? e.changedTouches[0] : e;
    if (!t) return;
    const dx = t.clientX - sx, dy = t.clientY - sy;
    const ax = Math.abs(dx), ay = Math.abs(dy);
    if (gameOver || won || paused || !current || droppingPiece) return;
    if (ax < SWIPE_MIN && ay < SWIPE_MIN) return;
    if (ax > ay) {
      if (dx > 0) move(1); else move(-1);
    } else {
      if (dy < 0) rotatePiece();
      else hardDropInstant();
    }
  }
  cvs.addEventListener('touchstart', onDown, { passive: true });
  cvs.addEventListener('touchmove', onMove, { passive: true });
  cvs.addEventListener('touchend', onUp, { passive: true });
  cvs.addEventListener('touchcancel', function() {
    tracking = false;
    if (holdTimer) { clearTimeout(holdTimer); holdTimer = null; }
    if (holding) { hardDropHolding = false; holding = false; }
  }, { passive: true });
  cvs.addEventListener('mousedown', onDown);
  window.addEventListener('mousemove', onMove);
  window.addEventListener('mouseup', onUp);
})();

const bgCanvas = document.getElementById('bg-canvas');
const bgCtx = bgCanvas.getContext('2d');
let bgParticles = [], bgRafId = null;
function resizeBg() { const oldW = bgCanvas.width || 1, oldH = bgCanvas.height || 1; bgCanvas.width = window.innerWidth; bgCanvas.height = window.innerHeight; const scaleX = bgCanvas.width / oldW, scaleY = bgCanvas.height / oldH; bgParticles.forEach(p => { p.x *= scaleX; p.y *= scaleY; }); }
window.addEventListener('resize', resizeBg);
resizeBg();
function drawBgParticlesNow() {
  if (!bgCtx || !bgCanvas) return;
  bgCtx.clearRect(0, 0, bgCanvas.width, bgCanvas.height);
  for (let i = 0; i < bgParticles.length; i++) { const p = bgParticles[i]; bgCtx.globalAlpha = p.life * 0.6; bgCtx.fillStyle = partyActive ? `hsl(${(rainbowTime * 5 + p.x) % 360}, 100%, 60%)` : p.color; bgCtx.shadowColor = bgCtx.fillStyle; bgCtx.shadowBlur = 12; bgCtx.beginPath(); bgCtx.arc(p.x, p.y, p.size, 0, Math.PI * 2); bgCtx.fill(); }
  bgCtx.shadowBlur = 0; bgCtx.globalAlpha = 1;
}
function startBgAnimation() {
  if (bgRafId) return;
  if (bgCanvas.width !== window.innerWidth || bgCanvas.height !== window.innerHeight) { bgCanvas.width = window.innerWidth; bgCanvas.height = window.innerHeight; }
  if (bgParticles.length === 0) { const w = bgCanvas.width || window.innerWidth, h = bgCanvas.height || window.innerHeight; const isLegendary = document.body.classList.contains('legendary'); for (let i = 0; i < 50; i++) bgParticles.push({ x: Math.random() * w, y: Math.random() * h, vx: (Math.random() - 0.5) * 0.5, vy: (Math.random() - 0.5) * 0.5, size: 1 + Math.random() * 3, color: isLegendary ? (Math.random() < 0.5 ? '#ffd700' : '#ff00ff') : COLORS[Math.floor(Math.random() * COLORS.length)], life: 1 }); }
  else { const w = bgCanvas.width || window.innerWidth, h = bgCanvas.height || window.innerHeight; bgParticles.forEach(p => { if (p.x > w || p.y > h || p.x < 0 || p.y < 0) { p.x = Math.random() * w; p.y = Math.random() * h; } }); }
  drawBgParticlesNow();
  setTimeout(drawBgParticlesNow, 1);
  bgRafId = requestAnimationFrame(bgLoop);
}
function stopBgAnimation() { if (bgRafId) { cancelAnimationFrame(bgRafId); bgRafId = null; } bgCtx.clearRect(0, 0, bgCanvas.width, bgCanvas.height); }
function bgLoop() {
  if (!document.getElementById('menu').classList.contains('show')) { bgRafId = null; return; }
  bgCtx.clearRect(0, 0, bgCanvas.width, bgCanvas.height);
  const len = bgParticles.length;
  for (let i = 0; i < len; i++) { const p = bgParticles[i]; p.x += p.vx; p.y += p.vy; if (p.x < 0) p.x = bgCanvas.width; if (p.x > bgCanvas.width) p.x = 0; if (p.y < 0) p.y = bgCanvas.height; if (p.y > bgCanvas.height) p.y = 0; bgCtx.globalAlpha = p.life * 0.6; bgCtx.fillStyle = partyActive ? `hsl(${(rainbowTime * 5 + p.x) % 360}, 100%, 60%)` : p.color; bgCtx.shadowColor = bgCtx.fillStyle; bgCtx.shadowBlur = 12; bgCtx.beginPath(); bgCtx.arc(p.x, p.y, p.size, 0, Math.PI * 2); bgCtx.fill(); }
  bgCtx.shadowBlur = 0; bgCtx.globalAlpha = 1;
  if (partyActive) rainbowTime += 0.5;
  bgRafId = requestAnimationFrame(bgLoop);
}
function showOverlay(mode) {
  overlayMode = mode;
  const ov = document.getElementById('overlay');
  const title = document.getElementById('overlay-title'), text = document.getElementById('overlay-text');
  const primary = document.getElementById('overlay-primary'), secondary = document.getElementById('overlay-secondary'), tertiary = document.getElementById('overlay-tertiary');
  ov.classList.remove('ach-anim');
  ov.classList.add('show');
  secondary.style.display = 'none'; tertiary.style.display = 'none';
  primary.className = ''; title.className = '';
  if (mode === 'end') { title.textContent = won ? 'YOU WIN!' : 'GAME OVER'; text.textContent = `Points: ${score} · Lines: ${lines}` + (score >= bestScore && score > 0 ? ' · NEW RECORD!' : ''); primary.textContent = 'NEW GAME'; primary.className = 'success'; secondary.textContent = 'MENU'; secondary.style.display = 'block'; }
  else if (mode === 'reset') { title.textContent = 'RESET THIS GAME?'; text.textContent = 'Current game will be lost (best score stays)'; primary.textContent = 'YES'; primary.className = 'danger'; secondary.textContent = 'NO'; secondary.style.display = 'block'; }
  else if (mode === 'pause') { title.textContent = 'PAUSED'; text.textContent = ''; primary.textContent = 'RESUME'; primary.className = 'success'; secondary.textContent = 'MENU'; secondary.style.display = 'block'; }
  else if (mode === 'win-100000') { title.textContent = 'VICTORY!'; title.className = 'record'; text.textContent = `Score: ${score} — You reached 100,000! EXTREME MODE unlocked!`; primary.textContent = 'NEW GAME'; primary.className = 'success'; secondary.textContent = 'CONTINUE'; secondary.className = 'gold'; secondary.style.display = 'block'; tertiary.textContent = 'MENU'; tertiary.style.display = 'block'; }
}
function hideOverlay() { const ov = document.getElementById('overlay'); ov.classList.remove('show'); ov.classList.remove('ach-anim'); }
function overlayAction() { initAudio(); if (overlayMode === 'end') startNewGame(); else if (overlayMode === 'reset') doResetGame(); else if (overlayMode === 'pause') togglePause(); else if (overlayMode === 'win-100000') startNewGame(); else if (overlayMode === 'ach') continueFromAchOverlay(); }
function overlaySecondary() {
  initAudio();
  if (overlayMode === 'reset') hideOverlay();
  else if (overlayMode === 'pause') { hideOverlay(); goToMenuWithSave(); }
  else if (overlayMode === 'end') { hideOverlay(); document.getElementById('pauseIndicator').classList.remove('show'); gameOver = false; won = false; paused = true; if (rafId) { cancelAnimationFrame(rafId); rafId = null; } showMenu(); }
  else if (overlayMode === 'win-100000') { hideOverlay(); paused = false; lastTime = 0; dropCounter = 0; if (rafId) cancelAnimationFrame(rafId); rafId = requestAnimationFrame(loop); }
  else if (overlayMode === 'ach') menuFromAchOverlay();
}
function overlayTertiary() { initAudio(); if (overlayMode === 'win-100000') { hideOverlay(); document.getElementById('pauseIndicator').classList.remove('show'); gameOver = false; won = false; paused = true; if (rafId) { cancelAnimationFrame(rafId); rafId = null; } showMenu(); } }
function endGame(isWin) {
  if (isWin) sfxWin(); else sfxLose();
  if (!pausedEverThisGame) trackNoPauseGame(); else resetNoPauseStreak();
  if (achPopupActive) achPopupActive = false;
  _showingAch = false;
  stopCompressionMode();
  try { localStorage.removeItem(SAVE_KEY); } catch(e) {}
  showOverlay('end');
}
function backToMenuSilent() { if (!gameOver && !won && current) saveProgress(); showMenu(); }
function goToMenuWithSave() { if (!gameOver && !won && current) saveProgress(); document.getElementById('pauseIndicator').classList.remove('show'); paused = true; if (rafId) { cancelAnimationFrame(rafId); rafId = null; } showMenu(); }
function startNewGame() {
  initAudio();
  if (audioCtx && audioCtx.state === 'suspended') audioCtx.resume();
  hideMenu(); hideOverlay();
  trackGameStart();
  pausedEverThisGame = false;
  achPopupQueue = []; achPopupActive = false; _showingAch = false;
  pentaThisGame = 0; bombsThisGame = 0; killersThisGame = 0;
  hexaThisGame = 0; superBombsThisGame = 0;
  nextPiecesQueue = []; firstBlockSpawned = false;
  stopCompressionMode();
  try { localStorage.removeItem(SAVE_KEY); } catch(e) {}
  score = promoBonus; promoBonus = 0; savePromos();
  compressionRows = ROWS; updateCanvasHeight();
  grid = createGrid();
  if (oneShotEffects.CLEANSLATE) { oneShotEffects.CLEANSLATE = false; savePromos(); showToast('CLEAN SLATE!'); }
  let startingLevel = 1;
  if (oneShotEffects.EXTRASTART) { oneShotEffects.EXTRASTART = false; savePromos(); startingLevel = 5; showToast('EXTRA START: LEVEL 5!'); }
  if (bombStartNextGame) {
    bombStartNextGame = false;
    for (let y = ROWS - 10; y < ROWS; y++) for (let x = 0; x < COLS; x++) grid[y][x] = COLORS[Math.floor(Math.random() * COLORS.length)];
    const isLeg = document.body.classList.contains('legendary');
    while (nextPiecesQueue.length < 4) nextPiecesQueue.push(generateNextPieceInfo(isLeg));
    window._bombStartNoScore = true;
    current = null;
    setTimeout(() => { if (gameOver || won) return; current = { shape: [[1,1],[1,1]], color: '#ffd700', x: Math.floor((COLS - 2) / 2), y: 0, isPenta: false, special: 'superbomb' }; superBombsThisGame = 1; updateXrayPanel(); }, 500);
    firstBlockSpawned = true;
  } else { current = newPiece(); updateXrayPanel(); }
  lines = startingLevel > 1 ? (startingLevel - 1) * 5 : 0;
  level = startingLevel;
  if (nopentaGamesLeft > 0) { nopentaGamesLeft--; savePromos(); }
  let xrayOn = false;
  if (xrayDisabled) xrayOn = false;
  else if (alwaysXrayActive) xrayOn = true;
  else if (xrayGamesLeft > 0) { xrayGamesLeft--; savePromos(); xrayOn = true; }
  else xrayOn = Math.random() < 0.1;
  window._xrayOn = xrayOn;
  const xp = document.getElementById('xrayPanel');
  if (xp) { if (xrayOn) xp.style.display = 'block'; else xp.style.display = 'none'; }
  updateXrayPanel();
  dropInterval = 800; dropCounter = 0; lastTime = 0;
  if (x100SpeedNextGame) { dropInterval = 8; x100SpeedNextGame = false; showToast('X100 SPEED ACTIVE!'); }
  gameOver = false; won = false; paused = false;
  particles = []; rings = []; shards = []; shines = []; droppingPiece = null;
  clearingLines = []; comboCount = 0; extremeMode = false; winShown = false;
  document.getElementById('pauseIndicator').classList.remove('show');
  updateUI(); updatePauseBtn();
  if (rafId) cancelAnimationFrame(rafId);
  rafId = requestAnimationFrame(loop);
}
function togglePause() { initAudio(); if (gameOver || won) return; paused = !paused; if (paused) { pausedEverThisGame = true; resetNoPauseStreak(); } updatePauseBtn(); const ind = document.getElementById('pauseIndicator'); if (paused) { ind.classList.add('show'); showOverlay('pause'); } else { ind.classList.remove('show'); hideOverlay(); } }
function updatePauseBtn() { document.getElementById('btn-pause').textContent = paused ? 'RESUME' : 'PAUSE'; }
function hasSavedGame() { const raw = localStorage.getItem(SAVE_KEY); if (!raw) return false; try { const data = JSON.parse(raw); if (data && (data.gameOver === true || data.won === true)) { localStorage.removeItem(SAVE_KEY); return false; } } catch(e) { localStorage.removeItem(SAVE_KEY); return false; } return true; }
function saveProgress() { const data = { grid, score, lines, level, current: current ? { shape: current.shape, color: current.color, x: current.x, y: current.y, isPenta: current.isPenta, special: current.special } : null, extremeMode, compressionActive, compressionRows, compressionLinesCleared, compressionSaveLines, compressionTimeLeft, gameOver: false, won: false }; try { localStorage.setItem(SAVE_KEY, JSON.stringify(data)); showToast('PROGRESS SAVED'); } catch(e) { showToast('SAVE ERROR'); } }
function loadProgress() {
  try {
    const raw = localStorage.getItem(SAVE_KEY);
    if (!raw) return false;
    const data = JSON.parse(raw);
    if (data && (data.gameOver === true || data.won === true)) { localStorage.removeItem(SAVE_KEY); return false; }
    grid = data.grid; score = data.score; lines = data.lines; level = data.level;
    current = data.current; if (!current) current = newPiece();
    extremeMode = data.extremeMode || false;
    dropInterval = extremeMode ? 40 : Math.max(80, 800 - (level - 1) * 80);
    firstBlockSpawned = true;
    if (data.compressionActive) {
      compressionActive = true; compressionRows = data.compressionRows || ROWS; updateCanvasHeight();
      compressionLinesCleared = data.compressionLinesCleared || 0; compressionSaveLines = data.compressionSaveLines || 0; compressionTimeLeft = data.compressionTimeLeft || COMPRESSION_TIME;
      const bar = document.getElementById('compressionBar'); if (bar) { bar.classList.remove('hide'); bar.classList.add('show'); }
      updateCompressionUI();
      if (compressionInterval) clearInterval(compressionInterval);
      compressionInterval = setInterval(() => { if (paused || gameOver || won) return; compressionTimeLeft--; if (compressionTimeLeft <= 0) { compressBoard(); compressionLinesCleared = 0; compressionSaveLines = 0; compressionTimeLeft = COMPRESSION_TIME; updateCompressionUI(); } else updateCompressionUI(); }, 1000);
    } else { compressionRows = ROWS; updateCanvasHeight(); }
    updateUI();
    return true;
  } catch(e) { return false; }
}
function doResetGame() { localStorage.removeItem(SAVE_KEY); showToast('GAME RESET'); hideOverlay(); document.getElementById('pauseIndicator').classList.remove('show'); startNewGame(); }
function doFullReset() {
  localStorage.removeItem(SAVE_KEY); localStorage.removeItem(BEST_KEY);
  localStorage.removeItem(ACH_KEY); localStorage.removeItem(LEGENDARY_UNLOCKED_KEY);
  localStorage.removeItem(LEGENDARY_BONUS_KEY); localStorage.removeItem('neon_tetris_total_lines');
  localStorage.removeItem('neon_tetris_plays'); localStorage.removeItem('neon_tetris_drops');
  localStorage.removeItem('neon_tetris_rotates'); localStorage.removeItem('neon_tetris_moves');
  localStorage.removeItem('neon_tetris_nopause_streak'); localStorage.removeItem('neon_tetris_tetris');
  localStorage.removeItem('neon_tetris_bombs'); localStorage.removeItem('neon_tetris_killers');
  localStorage.removeItem(PROMO_KEY); localStorage.removeItem(PROMO_BONUS_KEY);
  localStorage.removeItem(PROMO_TIMED_KEY); localStorage.removeItem(PROMO_ONESHOT_KEY);
  localStorage.removeItem(PROMO_NOPENTA_KEY); localStorage.removeItem(PROMO_XRAY_KEY);
  localStorage.removeItem('neon_tetris_always_xray'); localStorage.removeItem('neon_tetris_xray_disabled');
  alwaysXrayActive = false; xrayDisabled = false; bestScore = 0;
  document.getElementById('best').textContent = '0';
  document.getElementById('best-preview').textContent = '0';
  loadAchievements(); loadPromos(); revealLegendaryThemeButton();
  const currentTheme = localStorage.getItem(THEME_KEY) || 'dark';
  if (currentTheme === 'legendary' && localStorage.getItem(LEGENDARY_UNLOCKED_KEY) !== 'yes') setTheme('dark');
  else { document.body.className = currentTheme === 'dark' ? '' : currentTheme; }
  renderSettingsUI();
  showToast('FULL RESET DONE'); hideOverlay(); showMenu();
}
function move(dir) { if (gameOver || won || paused || !current || droppingPiece) return; if (current.special === 'hexa') return; if (current.special === 'superbomb') return; if (!collide(current, dir, 0)) { current.x += dir; sfxMove(); trackMove(); } draw(); }
function rotatePiece() { if (gameOver || won || paused || !current || droppingPiece) return; if (current.special === 'hexa') return; if (current.special === 'superbomb') return; const r = rotateShape(current.shape); if (!collide(current, 0, 0, r)) { current.shape = r; sfxRotate(); trackRotate(); } draw(); }
function hardDropInstant() {
  if (gameOver || won || paused || !current || droppingPiece) return;
  if (current.special === 'superbomb') return;
  if (current.special === 'hexa') {
    while (!collide(current, 0, 1)) current.y++;
    for (let x = 0; x < current.shape[0].length; x++) if (current.shape[current.shape.length - 1][x]) { const colX = current.x + x; for (let cy = current.y + current.shape.length; cy < compressionRows; cy++) if (colX >= 0 && colX < COLS && grid[cy] && grid[cy][colX]) { for (let dy = compressionRows - 2; dy >= cy; dy--) grid[dy + 1][colX] = grid[dy][colX]; grid[cy][colX] = 0; } }
    droppingPiece = { shape: current.shape, color: current.color, x: current.x, y: current.y, targetY: current.y, isPenta: current.isPenta, special: current.special };
    current = null; trackHardDrop();
    if (rafId) cancelAnimationFrame(rafId);
    lastTime = 0; rafId = requestAnimationFrame(loop); return;
  }
  let targetY = current.y;
  while (!collide(current, 0, targetY - current.y + 1)) targetY++;
  droppingPiece = { shape: current.shape, color: current.color, x: current.x, y: current.y, targetY, isPenta: current.isPenta, special: current.special };
  current = null; trackHardDrop();
  if (rafId) cancelAnimationFrame(rafId);
  lastTime = 0; rafId = requestAnimationFrame(loop);
}
function hardDropStart(e) { if (e) e.preventDefault(); initAudio(); if (gameOver || won || paused || !current || droppingPiece) return; if (current.special === 'superbomb') return; hardDropHolding = false; hardDropStartTime = Date.now(); hardDropHoldInterval = setTimeout(() => { if (current && !paused && !gameOver && !won) hardDropHolding = true; }, 200); }
function hardDropEnd(e) { if (e) e.preventDefault(); clearTimeout(hardDropHoldInterval); const holdTime = Date.now() - hardDropStartTime; if (!hardDropHolding && holdTime < 200) hardDropInstant(); hardDropHolding = false; }
function hardDrop() { hardDropInstant(); }
document.addEventListener('keydown', e => {
  if (e.key === 'p' || e.key === 'P') { togglePause(); return; }
  if (e.key === 'Escape') { if (document.getElementById('menu').classList.contains('show')) return; backToMenuSilent(); return; }
  if (gameOver || won || paused) return;
  if (e.key === 'ArrowLeft') move(-1);
  else if (e.key === 'ArrowRight') move(1);
  else if (e.key === 'ArrowDown') drop();
  else if (e.key === 'ArrowUp') rotatePiece();
  else if (e.key === ' ') hardDrop();
});
function setTheme(name) {
  initAudio();
  document.body.className = name === 'dark' ? '' : name;
  localStorage.setItem(THEME_KEY, name);
  refreshThemeCache();
  const tBtns = document.querySelectorAll('#settingsTheme .settings-opt');
  tBtns.forEach(b => b.classList.toggle('active', b.dataset.val === name));
  if (canvas && !document.getElementById('gameColumn').classList.contains('hidden')) draw();
}
let toastTimer = null;
function showToast(msg) { const el = document.getElementById('toast'); el.textContent = msg; el.classList.add('show'); clearTimeout(toastTimer); toastTimer = setTimeout(() => el.classList.remove('show'), 1800); }
function showBonus(msg) { const el = document.getElementById('bonus'); el.textContent = msg; el.classList.remove('show'); void el.offsetWidth; el.classList.add('show'); }
function showCombo(msg) { const el = document.getElementById('combo'); el.textContent = msg; el.classList.remove('show'); void el.offsetWidth; el.classList.add('show'); }
function showPraise(text, color, level) { const el = document.getElementById('praise'); el.textContent = text; el.style.color = color; el.style.textShadow = `0 0 15px ${color}, 0 0 30px ${color}`; el.classList.remove('show'); void el.offsetWidth; el.classList.add('show'); sfxPraise(level); }
function randomPraise(cleared) {
  const isLegendary = document.body.classList.contains('legendary');
  const legendaryChance = isLegendary ? 0.3 : 0.15;
  if (cleared >= 5) { showPraise(LEGENDARY_PHRASE.text, LEGENDARY_PHRASE.color, 5); return; }
  if (cleared >= 2 && Math.random() < legendaryChance) { showPraise(LEGENDARY_PHRASE.text, LEGENDARY_PHRASE.color, 5); return; }
  const phrase = PRAISE_PHRASES[Math.floor(Math.random() * PRAISE_PHRASES.length)];
  let level = 1;
  if (cleared === 2) level = 2;
  else if (cleared === 3) level = 3;
  else if (cleared >= 4) level = 4;
  showPraise(phrase.text, phrase.color, level);
}
function tryStartAudio() { initAudio(); }
function tryStartMusic() { initAudio(); if (audioCtx && audioCtx.state === 'suspended') audioCtx.resume(); if (window._startMusicNow && musicSetting === 'on') window._startMusicNow(); }
tryStartAudio();
[100, 400, 1000, 2500].forEach(ms => setTimeout(tryStartAudio, ms));
['click', 'pointerdown', 'mousedown', 'keydown', 'touchstart', 'touchend'].forEach(evt => {
  document.body.addEventListener(evt, function once() { tryStartAudio(); tryStartMusic(); document.body.removeEventListener(evt, once); }, { passive: true });
});
window.addEventListener('load', tryStartAudio);
window.addEventListener('load', function() { setTimeout(tryStartMusic, 100); setTimeout(tryStartMusic, 500); setTimeout(tryStartMusic, 1500); });
loadSettings();
loadAchievements();
loadPromos();
updateAchCounts();
bestScore = parseInt(localStorage.getItem(BEST_KEY) || '0');
document.getElementById('best').textContent = bestScore;
document.getElementById('best-preview').textContent = bestScore;
(function initTheme() {
  let savedTheme = localStorage.getItem(THEME_KEY);
  if (!savedTheme) { savedTheme = 'dark'; localStorage.setItem(THEME_KEY, 'dark'); }
  if (savedTheme === 'legendary' && localStorage.getItem(LEGENDARY_UNLOCKED_KEY) !== 'yes') { savedTheme = 'dark'; localStorage.setItem(THEME_KEY, 'dark'); }
  if (!['dark', 'medium', 'light', 'legendary'].includes(savedTheme)) { savedTheme = 'dark'; localStorage.setItem(THEME_KEY, 'dark'); }
  document.body.className = savedTheme === 'dark' ? '' : savedTheme;
})();
refreshThemeCache();
grid = createGrid();
current = null;
updateUI();
draw();
bgCanvas.width = window.innerWidth;
bgCanvas.height = window.innerHeight;
(function preinitBgParticles() {
  const w = bgCanvas.width || window.innerWidth, h = bgCanvas.height || window.innerHeight;
  const isLegendary = document.body.classList.contains('legendary');
  bgParticles.length = 0;
  for (let i = 0; i < 50; i++) bgParticles.push({ x: Math.random() * w, y: Math.random() * h, vx: (Math.random() - 0.5) * 0.5, vy: (Math.random() - 0.5) * 0.5, size: 1 + Math.random() * 3, color: isLegendary ? (Math.random() < 0.5 ? '#ffd700' : '#ff00ff') : COLORS[Math.floor(Math.random() * COLORS.length)], life: 1 });
  drawBgParticlesNow();
})();
document.getElementById('menu').classList.add('show');
document.getElementById('bg-canvas').classList.add('show');
document.getElementById('menu-ach-btn').classList.add('show');
document.getElementById('menu-settings-btn').classList.add('show');
startBgAnimation();
revealLegendaryThemeButton();
renderActivePromos();
attachUIButtonSounds();
renderSettingsUI();
const _origStartNewGame = startNewGame;
startNewGame = function() { _origStartNewGame(); setTimeout(attachUIButtonSounds, 50); };
const _origShowMenu = showMenu;
showMenu = function() { _origShowMenu(); setTimeout(attachUIButtonSounds, 50); };
(function ambientMusic() {
  let mctx = null, master = null, limiter = null, softClip = null, convolver = null;
  let started = false, scheduledUntil = 0, tickInterval = null;
  const LOOP_LEN = 128, AHEAD = 6;
  const BASS_MELODY = [36, 43, 41, 48, 36, 43, 45, 41];
  const PAD_ROOTS = [48, 55, 53, 60, 48, 55, 57, 53];
  const PAD_INTERVALS = [0, 7, 12, 16];
  const mtof = m => 440 * Math.pow(2, (m - 69) / 12);
  function makeTanhCurveM(amount, n) { n = n || 4096; const curve = new Float32Array(n); for (let i = 0; i < n; i++) { const x = (i / (n - 1)) * 2 - 1; curve[i] = Math.tanh(x * amount); } return curve; }
  function makeReverb(context) { const len = 5.0, rate = context.sampleRate; const buf = context.createBuffer(2, Math.floor(rate * len), rate); for (let c = 0; c < 2; c++) { const d = buf.getChannelData(c); for (let i = 0; i < d.length; i++) { const t = i / d.length; d[i] = (Math.random() * 2 - 1) * Math.pow(1 - t, 1.8) * 0.5; } } const conv = context.createConvolver(); conv.buffer = buf; return conv; }
  function initMusic() {
    if (mctx) return;
    try { mctx = new (window.AudioContext || window.webkitAudioContext)(); } catch(e) { return; }
    master = mctx.createGain();
    const lp2 = mctx.createBiquadFilter(); lp2.type = 'lowpass'; lp2.frequency.value = 1600; lp2.Q.value = 0.15;
    const lp = mctx.createBiquadFilter(); lp.type = 'lowpass'; lp.frequency.value = 1800; lp.Q.value = 0.2;
    const hp = mctx.createBiquadFilter(); hp.type = 'highpass'; hp.frequency.value = 30;
    const finalLP = mctx.createBiquadFilter(); finalLP.type = 'lowpass'; finalLP.frequency.value = 1400; finalLP.Q.value = 0.1;
    convolver = makeReverb(mctx);
    const wet = mctx.createGain(); wet.gain.value = 0.55;
    const dry = mctx.createGain(); dry.gain.value = 0.8;
    lp.connect(lp2); lp2.connect(hp);
    hp.connect(dry); dry.connect(master);
    hp.connect(convolver); convolver.connect(wet); wet.connect(master);
    const comp = mctx.createDynamicsCompressor();
    comp.threshold.value = -22; comp.knee.value = 34; comp.ratio.value = 5; comp.attack.value = 0.008; comp.release.value = 0.4;
    softClip = mctx.createWaveShaper(); softClip.curve = makeTanhCurveM(0.65); softClip.oversample = '4x';
    limiter = mctx.createWaveShaper(); limiter.curve = makeTanhCurveM(0.95); limiter.oversample = '4x';
    const preGain = mctx.createGain(); preGain.gain.value = 1.5;
    master.connect(preGain); preGain.connect(comp); comp.connect(softClip); softClip.connect(limiter); limiter.connect(finalLP); finalLP.connect(mctx.destination);
    master.gain.setValueAtTime(0.98, mctx.currentTime);
  }
  function playBass(freq, start, dur, vol) {
    const o = mctx.createOscillator(); const g = mctx.createGain(); o.type = 'sine'; o.frequency.value = freq;
    const oSub = mctx.createOscillator(); const gSub = mctx.createGain(); oSub.type = 'sine'; oSub.frequency.value = freq * 0.5; gSub.gain.value = 0.7;
    const lp = mctx.createBiquadFilter(); lp.type = 'lowpass'; lp.frequency.value = 300; lp.Q.value = 0.3;
    const atk = Math.min(0.9, dur * 0.22); const rel = dur * 0.7;
    g.gain.setValueAtTime(0.0001, start); g.gain.exponentialRampToValueAtTime(vol, start + atk); g.gain.setValueAtTime(vol, start + dur - rel * 0.4); g.gain.exponentialRampToValueAtTime(0.0001, start + dur + rel * 0.5);
    gSub.gain.setValueAtTime(0.0001, start); gSub.gain.exponentialRampToValueAtTime(vol * 0.85, start + atk * 1.4); gSub.gain.exponentialRampToValueAtTime(0.0001, start + dur + rel * 0.5);
    o.connect(g); oSub.connect(gSub); g.connect(lp); gSub.connect(lp); lp.connect(convolver); lp.connect(master);
    o.start(start); o.stop(start + dur + rel * 0.6 + 0.2); oSub.start(start + 0.02); oSub.stop(start + dur + rel * 0.6 + 0.2);
  }
  function playPad(freq, start, dur, vol) {
    const o = mctx.createOscillator(); const g = mctx.createGain(); o.type = 'sine'; o.frequency.value = freq;
    const lp = mctx.createBiquadFilter(); lp.type = 'lowpass'; lp.frequency.value = 550; lp.Q.value = 0.35;
    const atk = dur * 0.5; const rel = dur * 0.6;
    g.gain.setValueAtTime(0.0001, start); g.gain.exponentialRampToValueAtTime(vol, start + atk); g.gain.setValueAtTime(vol, start + dur - rel * 0.5); g.gain.exponentialRampToValueAtTime(0.0001, start + dur + rel * 0.55);
    o.connect(g); g.connect(lp); lp.connect(convolver); lp.connect(master);
    o.start(start); o.stop(start + dur + rel * 0.65 + 0.2);
  }
  function playLowFlute(freq, start, dur, vol) {
    const o = mctx.createOscillator(); const g = mctx.createGain(); o.type = 'sine'; o.frequency.value = freq;
    const lp = mctx.createBiquadFilter(); lp.type = 'lowpass'; lp.frequency.value = 850; lp.Q.value = 0.4;
    const atk = Math.max(0.5, dur * 0.4); const rel = dur * 0.8;
    g.gain.setValueAtTime(0.0001, start); g.gain.exponentialRampToValueAtTime(vol, start + atk); g.gain.setValueAtTime(vol, start + dur - rel * 0.4); g.gain.exponentialRampToValueAtTime(0.0001, start + dur + rel * 0.55);
    o.connect(g); g.connect(lp); lp.connect(convolver); lp.connect(master);
    o.start(start); o.stop(start + dur + rel * 0.6 + 0.2);
  }
  function scheduleCycle(cycleStart) {
    playBass(mtof(36), cycleStart, LOOP_LEN, 0.13);
    const segCount = 8; const segDur = LOOP_LEN / segCount;
    for (let b = 0; b < segCount; b++) { const t0 = cycleStart + b * segDur; const root = BASS_MELODY[b % BASS_MELODY.length]; playBass(mtof(root), t0, segDur * 0.92, 0.11); playBass(mtof(root + 7), t0 + segDur * 0.45, segDur * 0.45, 0.055); }
    for (let c = 0; c < segCount; c++) { const t0 = cycleStart + c * segDur; const root = PAD_ROOTS[c % PAD_ROOTS.length]; PAD_INTERVALS.forEach((iv, i) => { playPad(mtof(root + iv), t0 + i * 0.5, segDur + 1.0, 0.028 + Math.random() * 0.008); }); }
    let t = cycleStart + 6;
    while (t < cycleStart + LOOP_LEN - 12) { const step = 10 + Math.random() * 12; t += step; if (Math.random() < 0.35) continue; const base = BASS_MELODY[Math.floor(Math.random() * BASS_MELODY.length)]; [0, 4, 7].forEach((off, i) => { playLowFlute(mtof(base + 12 + off), t + i * 1.4, 2.5 + Math.random() * 1.5, 0.05 + Math.random() * 0.015); }); }
  }
  function tick() { if (!mctx) return; if (musicSetting !== 'on') return; const now = mctx.currentTime; while (scheduledUntil < now + AHEAD) { scheduleCycle(scheduledUntil); scheduledUntil += LOOP_LEN; } }
  function startMusic() {
    initMusic(); if (!mctx) return;
    if (started) return;
    started = true;
    scheduledUntil = mctx.currentTime + 0.05;
    if (musicSetting === 'on') { master.gain.cancelScheduledValues(mctx.currentTime); master.gain.setValueAtTime(0.98, mctx.currentTime); }
    tick();
    if (tickInterval) clearInterval(tickInterval);
    tickInterval = setInterval(tick, 2000);
  }
  function tryStart() { initMusic(); if (mctx && mctx.state === 'suspended') mctx.resume(); startMusic(); }
  window._startMusicNow = function() {
    initMusic();
    if (mctx && mctx.state === 'suspended') mctx.resume();
    if (!started) startMusic();
    if (master && mctx && musicSetting === 'on') { master.gain.cancelScheduledValues(mctx.currentTime); master.gain.setValueAtTime(0.98, mctx.currentTime); }
  };
  window._stopMusicNow = function() { if (master && mctx) { master.gain.cancelScheduledValues(mctx.currentTime); master.gain.setValueAtTime(Math.max(0.0001, master.gain.value), mctx.currentTime); master.gain.exponentialRampToValueAtTime(0.0001, mctx.currentTime + 0.4); } };
})();
</script>
</body>
</html>
