<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hunter System</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@400;600;700&family=Share+Tech+Mono&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}

:root{
  --cyan:#00d4ff;
  --orange:#ff6600;
  --blue:#0ea5e9;
  --dark:#020617;
  --card:#0f172a;
  --border:#1e293b;
  --muted:#94a3b8;
  --green:#00ff88;
  --purple:#a855f7;
}

body{
  background:var(--dark);
  color:white;
  font-family:'Rajdhani',sans-serif;
  overflow-x:hidden;
}

/* SCANLINE OVERLAY */
body::before{
  content:'';
  position:fixed;
  inset:0;
  background:repeating-linear-gradient(0deg,transparent,transparent 2px,rgba(0,212,255,0.015) 2px,rgba(0,212,255,0.015) 4px);
  pointer-events:none;
  z-index:9999;
}

.container{
  max-width:480px;
  margin:auto;
  min-height:100vh;
  padding-bottom:50px;
}

/* ANIMATED BACKGROUND */
.bg{
  position:fixed;
  inset:0;
  z-index:-2;
  background:#020617;
}
.bg::before{
  content:'';
  position:fixed;
  inset:0;
  background:
    radial-gradient(ellipse at 80% 10%,rgba(0,212,255,0.15),transparent 50%),
    radial-gradient(ellipse at 10% 90%,rgba(255,102,0,0.12),transparent 50%),
    radial-gradient(ellipse at 50% 50%,rgba(168,85,247,0.05),transparent 60%);
  animation:bgPulse 8s ease-in-out infinite alternate;
}
.bg::after{
  content:'';
  position:fixed;
  inset:0;
  background-image:
    linear-gradient(rgba(0,212,255,0.03) 1px,transparent 1px),
    linear-gradient(90deg,rgba(0,212,255,0.03) 1px,transparent 1px);
  background-size:40px 40px;
}

@keyframes bgPulse{
  0%{opacity:0.6;}
  100%{opacity:1;}
}

/* PARTICLES */
.particles{
  position:fixed;
  inset:0;
  z-index:-1;
  overflow:hidden;
  pointer-events:none;
}
.particle{
  position:absolute;
  width:2px;
  height:2px;
  border-radius:50%;
  background:var(--cyan);
  animation:float linear infinite;
  opacity:0;
}
@keyframes float{
  0%{transform:translateY(100vh) translateX(0);opacity:0;}
  10%{opacity:1;}
  90%{opacity:0.5;}
  100%{transform:translateY(-100px) translateX(var(--dx));opacity:0;}
}

/* ===== SETUP WIZARD ===== */
.setup{
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  min-height:100vh;
  padding:20px;
}

.logo-wrap{
  text-align:center;
  margin-bottom:30px;
  animation:logoIn 1s ease both;
}
@keyframes logoIn{
  from{opacity:0;transform:translateY(-30px);}
  to{opacity:1;transform:translateY(0);}
}

.logo-glyph{
  font-family:'Orbitron',sans-serif;
  font-size:48px;
  font-weight:900;
  background:linear-gradient(135deg,var(--cyan),var(--purple),var(--orange));
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  text-shadow:none;
  letter-spacing:2px;
  line-height:1;
}

.logo-sub{
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  letter-spacing:6px;
  color:var(--orange);
  margin-top:6px;
  text-transform:uppercase;
}

/* STEP CARD */
.step-card{
  width:100%;
  background:rgba(15,23,42,0.95);
  border:1px solid rgba(0,212,255,0.3);
  padding:28px 24px;
  border-radius:20px;
  box-shadow:
    0 0 40px rgba(0,212,255,0.1),
    0 0 80px rgba(0,212,255,0.05),
    inset 0 1px 0 rgba(255,255,255,0.05);
  animation:cardIn 0.5s ease both;
  position:relative;
  overflow:hidden;
}
.step-card::before{
  content:'';
  position:absolute;
  top:0;left:0;right:0;
  height:2px;
  background:linear-gradient(90deg,transparent,var(--cyan),transparent);
  animation:scanline 3s linear infinite;
}
@keyframes scanline{
  0%{transform:translateX(-100%);}
  100%{transform:translateX(100%);}
}
@keyframes cardIn{
  from{opacity:0;transform:translateY(20px) scale(0.97);}
  to{opacity:1;transform:translateY(0) scale(1);}
}

/* STEP INDICATOR */
.step-indicator{
  display:flex;
  justify-content:center;
  gap:8px;
  margin-bottom:24px;
}
.step-dot{
  width:8px;height:8px;
  border-radius:50%;
  background:var(--border);
  border:1px solid #334155;
  transition:all 0.3s;
}
.step-dot.active{
  background:var(--cyan);
  box-shadow:0 0 8px var(--cyan);
}
.step-dot.done{
  background:var(--green);
  box-shadow:0 0 6px var(--green);
}

/* STEP HEADER */
.step-header{
  margin-bottom:20px;
}
.step-num{
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  color:var(--cyan);
  letter-spacing:3px;
  margin-bottom:4px;
}
.step-title{
  font-family:'Orbitron',sans-serif;
  font-size:20px;
  font-weight:700;
  color:white;
}
.step-desc{
  font-size:13px;
  color:var(--muted);
  margin-top:4px;
  font-family:'Share Tech Mono',monospace;
}

/* INPUTS */
.field{
  margin-bottom:16px;
}
.field-label{
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  color:var(--cyan);
  letter-spacing:2px;
  text-transform:uppercase;
  margin-bottom:6px;
  display:block;
}
.inp{
  width:100%;
  padding:14px 16px;
  background:rgba(2,6,23,0.8);
  border:1px solid #334155;
  border-radius:10px;
  color:white;
  font-size:16px;
  font-family:'Rajdhani',sans-serif;
  font-weight:600;
  outline:none;
  transition:all 0.3s;
}
.inp:focus{
  border-color:var(--cyan);
  box-shadow:0 0 12px rgba(0,212,255,0.2);
}
.inp::placeholder{color:#334155;}
select.inp option{background:#0f172a;}

/* OPTION GRID */
.opt-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:8px;
  margin-top:4px;
}
.opt-grid.three{
  grid-template-columns:1fr 1fr 1fr;
}
.opt-btn{
  padding:12px 8px;
  border:1px solid #334155;
  border-radius:10px;
  background:rgba(2,6,23,0.8);
  color:var(--muted);
  font-family:'Rajdhani',sans-serif;
  font-weight:700;
  font-size:14px;
  cursor:pointer;
  transition:all 0.25s;
  text-align:center;
}
.opt-btn:hover{border-color:var(--cyan);color:white;}
.opt-btn.selected{
  border-color:var(--cyan);
  background:rgba(0,212,255,0.1);
  color:var(--cyan);
  box-shadow:0 0 10px rgba(0,212,255,0.15);
}

/* INLINE UNIT FIELD */
.unit-field{
  display:flex;
  gap:8px;
}
.unit-field .inp{flex:1;}
.unit-tag{
  display:flex;
  align-items:center;
  padding:0 14px;
  background:rgba(0,212,255,0.08);
  border:1px solid rgba(0,212,255,0.3);
  border-radius:10px;
  color:var(--cyan);
  font-family:'Share Tech Mono',monospace;
  font-size:13px;
  white-space:nowrap;
}

/* BUTTONS */
.btn-row{
  display:flex;
  gap:10px;
  margin-top:20px;
}
.btn{
  flex:1;
  padding:15px;
  border:none;
  border-radius:12px;
  font-family:'Orbitron',sans-serif;
  font-weight:700;
  font-size:13px;
  cursor:pointer;
  transition:all 0.25s;
  letter-spacing:1px;
}
.btn-primary{
  background:linear-gradient(135deg,var(--cyan),var(--blue));
  color:#020617;
  box-shadow:0 4px 20px rgba(0,212,255,0.3);
}
.btn-primary:hover{
  box-shadow:0 4px 30px rgba(0,212,255,0.5);
  transform:translateY(-1px);
}
.btn-ghost{
  background:transparent;
  border:1px solid #334155;
  color:var(--muted);
}
.btn-ghost:hover{border-color:#475569;color:white;}
.btn-awaken{
  background:linear-gradient(135deg,#ff6600,#ff4400);
  color:white;
  box-shadow:0 4px 20px rgba(255,102,0,0.4);
  font-size:15px;
  letter-spacing:3px;
}
.btn-awaken:hover{
  box-shadow:0 4px 40px rgba(255,102,0,0.6);
  transform:translateY(-2px);
}

/* PROFILE PREVIEW (step final) */
.profile-preview{
  background:rgba(0,212,255,0.04);
  border:1px solid rgba(0,212,255,0.15);
  border-radius:12px;
  padding:16px;
  margin-bottom:16px;
}
.profile-row{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:8px 0;
  border-bottom:1px solid rgba(255,255,255,0.05);
  font-size:14px;
}
.profile-row:last-child{border-bottom:none;}
.profile-key{
  color:var(--muted);
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  letter-spacing:1px;
}
.profile-val{
  color:white;
  font-weight:700;
  color:var(--cyan);
}

/* ===== MAIN APP ===== */
.main{display:none;}

/* HEADER */
.header{
  padding:20px;
  background:rgba(15,23,42,0.95);
  border-bottom:1px solid rgba(0,212,255,0.15);
  position:relative;
  overflow:hidden;
}
.header::after{
  content:'';
  position:absolute;
  bottom:0;left:0;right:0;
  height:1px;
  background:linear-gradient(90deg,transparent,var(--cyan),transparent);
}

.header-top{
  display:flex;
  justify-content:space-between;
  align-items:flex-start;
  margin-bottom:12px;
}

.hunter-name{
  font-family:'Orbitron',sans-serif;
  font-size:22px;
  font-weight:900;
  letter-spacing:1px;
}

.header-stats{
  text-align:right;
}

.rank-badge{
  display:inline-flex;
  align-items:center;
  gap:6px;
  padding:6px 14px;
  border-radius:8px;
  background:linear-gradient(135deg,#ff6600,#ff4400);
  font-weight:700;
  font-size:13px;
  letter-spacing:2px;
  box-shadow:0 0 15px rgba(255,102,0,0.4);
}

.day-text{
  margin-top:6px;
  color:var(--muted);
  font-family:'Share Tech Mono',monospace;
  font-size:12px;
}

/* XP BAR */
.xp-wrap{
  margin-top:12px;
}
.xp-label{
  display:flex;
  justify-content:space-between;
  font-family:'Share Tech Mono',monospace;
  font-size:10px;
  color:var(--muted);
  margin-bottom:4px;
}
.xp-bar{
  width:100%;
  height:6px;
  background:rgba(30,41,59,0.8);
  border-radius:20px;
  overflow:hidden;
}
.xp-fill{
  height:100%;
  width:0%;
  background:linear-gradient(90deg,var(--cyan),var(--purple));
  border-radius:20px;
  transition:width 1s ease;
  box-shadow:0 0 8px var(--cyan);
}

/* HUNTER PROFILE STRIP */
.profile-strip{
  display:flex;
  gap:8px;
  padding:12px 15px;
  overflow-x:auto;
  scrollbar-width:none;
}
.profile-strip::-webkit-scrollbar{display:none;}
.profile-chip{
  flex-shrink:0;
  background:rgba(15,23,42,0.8);
  border:1px solid rgba(0,212,255,0.15);
  border-radius:8px;
  padding:8px 12px;
  text-align:center;
  min-width:70px;
}
.chip-label{
  font-family:'Share Tech Mono',monospace;
  font-size:9px;
  color:var(--muted);
  letter-spacing:1px;
}
.chip-val{
  font-weight:700;
  font-size:15px;
  color:var(--cyan);
  margin-top:2px;
}

/* STATS GRID */
.stats{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:10px;
  padding:15px;
}
.stat{
  background:rgba(15,23,42,0.8);
  padding:16px;
  border-radius:15px;
  border:1px solid var(--border);
  position:relative;
  overflow:hidden;
  transition:border-color 0.3s;
}
.stat:hover{border-color:rgba(0,212,255,0.3);}
.stat::before{
  content:'';
  position:absolute;
  top:0;left:0;right:0;
  height:2px;
  background:linear-gradient(90deg,var(--cyan),var(--purple));
  opacity:0.5;
}
.stat-icon{
  font-size:20px;
  margin-bottom:4px;
}
.stat-title{
  font-family:'Share Tech Mono',monospace;
  font-size:10px;
  color:var(--muted);
  letter-spacing:2px;
}
.stat-value{
  font-family:'Orbitron',sans-serif;
  font-size:26px;
  font-weight:900;
  margin-top:4px;
  background:linear-gradient(135deg,white,var(--cyan));
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
}

/* SECTION TITLE */
.section-title{
  padding:0 15px;
  margin-top:14px;
  font-family:'Orbitron',sans-serif;
  font-size:14px;
  letter-spacing:2px;
  color:var(--cyan);
  display:flex;
  align-items:center;
  gap:10px;
}
.section-title::after{
  content:'';
  flex:1;
  height:1px;
  background:linear-gradient(90deg,rgba(0,212,255,0.3),transparent);
}

/* QUESTS */
.quest-list{padding:15px;}
.quest{
  background:rgba(15,23,42,0.8);
  padding:16px;
  border-radius:15px;
  margin-bottom:12px;
  border:1px solid var(--border);
  transition:all 0.3s;
  position:relative;
  overflow:hidden;
}
.quest.done-quest{
  border-color:rgba(0,255,136,0.3);
  background:rgba(0,255,136,0.03);
}
.quest-header{
  display:flex;
  justify-content:space-between;
  align-items:center;
}
.quest-name{
  font-family:'Orbitron',sans-serif;
  font-size:14px;
  font-weight:700;
  letter-spacing:1px;
}
.quest-badge{
  font-family:'Share Tech Mono',monospace;
  font-size:10px;
  padding:3px 8px;
  border-radius:4px;
  background:rgba(0,212,255,0.1);
  border:1px solid rgba(0,212,255,0.2);
  color:var(--cyan);
}
.quest-progress{
  margin-top:8px;
  font-size:13px;
  color:var(--muted);
  font-family:'Share Tech Mono',monospace;
}
.quest-bar{
  height:6px;
  background:rgba(30,41,59,0.8);
  border-radius:20px;
  overflow:hidden;
  margin-top:8px;
}
.quest-fill{
  height:100%;
  width:0%;
  background:linear-gradient(90deg,var(--cyan),var(--blue));
  border-radius:20px;
  transition:width 0.5s ease;
  box-shadow:0 0 6px var(--cyan);
}
.quest-fill.full{background:linear-gradient(90deg,var(--green),#00cc66);}
.quest-actions{
  display:flex;
  gap:8px;
  margin-top:12px;
}
.quest-btn{
  padding:9px 14px;
  border:none;
  border-radius:8px;
  background:rgba(255,102,0,0.15);
  border:1px solid rgba(255,102,0,0.3);
  color:var(--orange);
  font-family:'Orbitron',sans-serif;
  font-weight:700;
  font-size:11px;
  cursor:pointer;
  transition:all 0.25s;
}
.quest-btn:hover{
  background:rgba(255,102,0,0.25);
  box-shadow:0 0 10px rgba(255,102,0,0.2);
}
.quest-btn.big{
  background:rgba(0,212,255,0.1);
  border-color:rgba(0,212,255,0.3);
  color:var(--cyan);
}

/* COMPLETE BTN */
.complete-btn{
  margin:10px 15px 20px;
  width:calc(100% - 30px);
  padding:18px;
  border:none;
  border-radius:15px;
  background:linear-gradient(135deg,#00ff88,#00cc66);
  font-family:'Orbitron',sans-serif;
  font-size:14px;
  font-weight:900;
  color:#020617;
  cursor:pointer;
  display:none;
  letter-spacing:3px;
  box-shadow:0 4px 30px rgba(0,255,136,0.4);
  animation:pulseGreen 2s ease infinite;
}
@keyframes pulseGreen{
  0%,100%{box-shadow:0 4px 30px rgba(0,255,136,0.4);}
  50%{box-shadow:0 4px 50px rgba(0,255,136,0.7);}
}

/* VIDEO */
.video-box{padding:15px;}
.video-title{
  font-family:'Orbitron',sans-serif;
  font-size:13px;
  letter-spacing:2px;
  color:var(--cyan);
  margin-bottom:10px;
}
iframe{border-radius:15px;border:1px solid var(--border);}

/* POPUP */
.popup{
  position:fixed;inset:0;
  background:rgba(0,0,0,0.85);
  display:none;
  justify-content:center;
  align-items:center;
  padding:20px;
  z-index:999;
  backdrop-filter:blur(4px);
}
.popup-card{
  background:#0f172a;
  padding:32px 28px;
  border-radius:24px;
  text-align:center;
  max-width:340px;
  width:100%;
  border:1px solid rgba(0,255,136,0.3);
  box-shadow:0 0 60px rgba(0,255,136,0.15);
  animation:popIn 0.4s cubic-bezier(0.34,1.56,0.64,1) both;
}
@keyframes popIn{
  from{opacity:0;transform:scale(0.7);}
  to{opacity:1;transform:scale(1);}
}
.popup-icon{font-size:48px;margin-bottom:12px;}
.popup-title{
  font-size:26px;
  font-family:'Orbitron',sans-serif;
  color:var(--green);
  margin-bottom:8px;
  text-shadow:0 0 20px rgba(0,255,136,0.5);
}
.popup-sub{color:var(--muted);font-size:14px;margin-bottom:8px;}
.popup-xp{
  font-family:'Orbitron',sans-serif;
  font-size:32px;
  color:var(--cyan);
  font-weight:900;
  margin:12px 0;
}
.popup-btn{
  margin-top:16px;
  padding:14px 24px;
  width:100%;
  border:none;
  border-radius:12px;
  background:linear-gradient(135deg,var(--cyan),var(--blue));
  color:#020617;
  font-family:'Orbitron',sans-serif;
  font-weight:700;
  font-size:13px;
  cursor:pointer;
  letter-spacing:2px;
}

/* RESET BTN */
.reset-btn{
  display:block;
  margin:0 auto 20px;
  padding:8px 20px;
  border:1px solid #334155;
  border-radius:8px;
  background:transparent;
  color:#475569;
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  cursor:pointer;
  letter-spacing:1px;
}
.reset-btn:hover{border-color:#ef4444;color:#ef4444;}

/* AD POPUP */
.ad-popup{
  position:fixed;inset:0;
  background:rgba(0,0,0,0.92);
  display:none;
  justify-content:center;
  align-items:center;
  padding:20px;
  z-index:9998;
  backdrop-filter:blur(6px);
}
.ad-card{
  background:#0f172a;
  border:1px solid rgba(255,102,0,0.4);
  border-radius:24px;
  padding:28px 24px;
  max-width:340px;
  width:100%;
  text-align:center;
  box-shadow:0 0 60px rgba(255,102,0,0.15);
  animation:popIn 0.4s cubic-bezier(0.34,1.56,0.64,1) both;
}
.ad-top{
  font-family:'Share Tech Mono',monospace;
  font-size:10px;
  color:var(--muted);
  letter-spacing:3px;
  margin-bottom:16px;
  padding:4px 10px;
  border:1px solid #334155;
  border-radius:4px;
  display:inline-block;
}
.ad-box{
  background:rgba(255,102,0,0.05);
  border:2px dashed rgba(255,102,0,0.3);
  border-radius:16px;
  padding:30px 20px;
  margin:16px 0;
  min-height:120px;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  gap:8px;
}
.ad-box-icon{font-size:36px;}
.ad-box-text{
  font-family:'Orbitron',sans-serif;
  font-size:13px;
  color:var(--orange);
  letter-spacing:1px;
}
.ad-box-sub{
  font-family:'Share Tech Mono',monospace;
  font-size:10px;
  color:var(--muted);
}
.ad-timer{
  font-family:'Orbitron',sans-serif;
  font-size:28px;
  font-weight:900;
  color:var(--cyan);
  margin:8px 0;
}
.ad-skip-btn{
  width:100%;
  padding:14px;
  border:none;
  border-radius:12px;
  background:linear-gradient(135deg,var(--orange),#ff4400);
  color:white;
  font-family:'Orbitron',sans-serif;
  font-weight:700;
  font-size:13px;
  cursor:pointer;
  letter-spacing:2px;
  display:none;
  box-shadow:0 4px 20px rgba(255,102,0,0.4);
}

/* THANKS POPUP */
.thanks-popup{
  position:fixed;inset:0;
  background:rgba(0,0,0,0.88);
  display:none;
  justify-content:center;
  align-items:center;
  padding:20px;
  z-index:9999;
  backdrop-filter:blur(6px);
}
.thanks-card{
  background:#0f172a;
  border:1px solid rgba(0,255,136,0.4);
  border-radius:24px;
  padding:32px 24px;
  max-width:320px;
  width:100%;
  text-align:center;
  box-shadow:0 0 60px rgba(0,255,136,0.15);
  animation:popIn 0.4s cubic-bezier(0.34,1.56,0.64,1) both;
}
.thanks-icon{font-size:52px;margin-bottom:12px;}
.thanks-title{
  font-family:'Orbitron',sans-serif;
  font-size:22px;
  font-weight:900;
  color:var(--green);
  margin-bottom:8px;
  text-shadow:0 0 20px rgba(0,255,136,0.4);
}
.thanks-msg{
  font-family:'Share Tech Mono',monospace;
  font-size:12px;
  color:var(--muted);
  line-height:1.6;
  margin-bottom:16px;
}
.thanks-btn{
  width:100%;
  padding:14px;
  border:none;
  border-radius:12px;
  background:linear-gradient(135deg,var(--green),#00cc66);
  color:#020617;
  font-family:'Orbitron',sans-serif;
  font-weight:700;
  font-size:13px;
  cursor:pointer;
  letter-spacing:2px;
}

/* DONATE SECTION */
.donate-box{
  margin:0 15px 20px;
  background:rgba(168,85,247,0.05);
  border:1px solid rgba(168,85,247,0.3);
  border-radius:16px;
  padding:20px;
  text-align:center;
}
.donate-title{
  font-family:'Orbitron',sans-serif;
  font-size:13px;
  color:var(--purple);
  letter-spacing:2px;
  margin-bottom:6px;
}
.donate-sub{
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  color:var(--muted);
  margin-bottom:14px;
  line-height:1.5;
}
.donate-btn{
  display:inline-block;
  padding:12px 24px;
  border:none;
  border-radius:10px;
  background:linear-gradient(135deg,var(--purple),#7c3aed);
  color:white;
  font-family:'Orbitron',sans-serif;
  font-weight:700;
  font-size:12px;
  cursor:pointer;
  letter-spacing:1px;
  text-decoration:none;
  box-shadow:0 4px 20px rgba(168,85,247,0.3);
}
.donate-amounts{
  display:flex;
  gap:8px;
  justify-content:center;
  margin-bottom:12px;
}
.donate-amt{
  padding:8px 14px;
  border:1px solid rgba(168,85,247,0.3);
  border-radius:8px;
  background:transparent;
  color:var(--purple);
  font-family:'Orbitron',sans-serif;
  font-size:12px;
  cursor:pointer;
  transition:all 0.25s;
}
.donate-amt:hover{
  background:rgba(168,85,247,0.15);
  box-shadow:0 0 10px rgba(168,85,247,0.2);
}


/* QR CODE */
.qr-wrap{
  display:flex;
  flex-direction:column;
  align-items:center;
  margin:14px 0;
}
.qr-inner{
  background:white;
  padding:14px;
  border-radius:18px;
  display:inline-block;
  box-shadow:0 0 30px rgba(168,85,247,0.4),0 0 60px rgba(168,85,247,0.1);
  border:3px solid rgba(168,85,247,0.5);
}
.qr-img{
  width:180px;
  height:180px;
  object-fit:contain;
  display:block;
  border-radius:6px;
}
.qr-label{
  margin-top:10px;
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  color:var(--purple);
  letter-spacing:1px;
  text-align:center;
}

/* AD POPUP extras */
.ad-headline{
  font-family:'Orbitron',sans-serif;
  font-size:18px;
  font-weight:700;
  color:white;
  margin-bottom:4px;
}
.ad-tagline{
  font-family:'Share Tech Mono',monospace;
  font-size:11px;
  color:var(--muted);
  margin-bottom:12px;
}
</style>
</head>
<body>

<div class="bg"></div>
<div class="particles" id="particles"></div>
<div class="container">

<!-- ===== SETUP WIZARD ===== -->
<div class="setup" id="setup">

  <div class="logo-wrap">
    <div class="logo-glyph">HUNTER<br>SYSTEM</div>
    <div class="logo-sub">⬡ Hunter Registration System ⬡</div>
  </div>

  <!-- STEP 1: Identity -->
  <div class="step-card" id="step1">
    <div class="step-indicator">
      <div class="step-dot active" id="dot1"></div>
      <div class="step-dot" id="dot2"></div>
      <div class="step-dot" id="dot3"></div>
      <div class="step-dot" id="dot4"></div>
      <div class="step-dot" id="dot5"></div>
    </div>
    <div class="step-header">
      <div class="step-num">STEP 01 / 05</div>
      <div class="step-title">HUNTER IDENTITY</div>
      <div class="step-desc">> Enter your designation, soldier.</div>
    </div>
    <div class="field">
      <label class="field-label">Hunter Name</label>
      <input class="inp" id="inp_name" type="text" placeholder="e.g. Sung Jin-Woo" maxlength="20">
    </div>
    <div class="field">
      <label class="field-label">Age</label>
      <input class="inp" id="inp_age" type="number" placeholder="e.g. 20" min="10" max="99">
    </div>
    <div class="field">
      <label class="field-label">Sex</label>
      <div class="opt-grid three">
        <button class="opt-btn" onclick="selectOpt(this,'sex','Male')">♂ MALE</button>
        <button class="opt-btn" onclick="selectOpt(this,'sex','Female')">♀ FEMALE</button>
        <button class="opt-btn" onclick="selectOpt(this,'sex','Other')">◈ OTHER</button>
      </div>
    </div>
    <div class="btn-row">
      <button class="btn btn-primary" onclick="goStep(2)">NEXT →</button>
    </div>
  </div>

  <!-- STEP 2: Physical Stats -->
  <div class="step-card" id="step2" style="display:none;">
    <div class="step-indicator">
      <div class="step-dot done" id="dot1b"></div>
      <div class="step-dot active" id="dot2b"></div>
      <div class="step-dot" id="dot3b"></div>
      <div class="step-dot" id="dot4b"></div>
      <div class="step-dot" id="dot5b"></div>
    </div>
    <div class="step-header">
      <div class="step-num">STEP 02 / 05</div>
      <div class="step-title">PHYSICAL STATS</div>
      <div class="step-desc">> System scanning your vessel...</div>
    </div>
    <div class="field">
      <label class="field-label">Height</label>
      <div class="unit-field">
        <input class="inp" id="inp_height" type="number" placeholder="175" min="100" max="250">
        <div class="unit-tag">CM</div>
      </div>
    </div>
    <div class="field">
      <label class="field-label">Weight</label>
      <div class="unit-field">
        <input class="inp" id="inp_weight" type="number" placeholder="70" min="30" max="300">
        <div class="unit-tag">KG</div>
      </div>
    </div>
    <div class="field">
      <label class="field-label">Body Type</label>
      <div class="opt-grid">
        <button class="opt-btn" onclick="selectOpt(this,'body','Ectomorph')">🔹 ECTO</button>
        <button class="opt-btn" onclick="selectOpt(this,'body','Mesomorph')">⚡ MESO</button>
        <button class="opt-btn" onclick="selectOpt(this,'body','Endomorph')">🔶 ENDO</button>
        <button class="opt-btn" onclick="selectOpt(this,'body','Athletic')">💠 ATHLETIC</button>
      </div>
    </div>
    <div class="btn-row">
      <button class="btn btn-ghost" onclick="goStep(1)">← BACK</button>
      <button class="btn btn-primary" onclick="goStep(3)">NEXT →</button>
    </div>
  </div>

  <!-- STEP 3: Combat Style -->
  <div class="step-card" id="step3" style="display:none;">
    <div class="step-indicator">
      <div class="step-dot done"></div>
      <div class="step-dot done"></div>
      <div class="step-dot active"></div>
      <div class="step-dot"></div>
      <div class="step-dot"></div>
    </div>
    <div class="step-header">
      <div class="step-num">STEP 03 / 05</div>
      <div class="step-title">CLASS & STYLE</div>
      <div class="step-desc">> Choose your combat specialization.</div>
    </div>
    <div class="field">
      <label class="field-label">Fitness Goal</label>
      <div class="opt-grid">
        <button class="opt-btn" onclick="selectOpt(this,'goal','Muscle Gain')">💪 BUILD</button>
        <button class="opt-btn" onclick="selectOpt(this,'goal','Fat Loss')">🔥 CUT</button>
        <button class="opt-btn" onclick="selectOpt(this,'goal','Endurance')">⚡ ENDURE</button>
        <button class="opt-btn" onclick="selectOpt(this,'goal','Overall')">🌀 ALL</button>
      </div>
    </div>
    <div class="field">
      <label class="field-label">Experience Level</label>
      <div class="opt-grid three">
        <button class="opt-btn" onclick="selectOpt(this,'exp','Beginner')">E-RANK</button>
        <button class="opt-btn" onclick="selectOpt(this,'exp','Intermediate')">C-RANK</button>
        <button class="opt-btn" onclick="selectOpt(this,'exp','Advanced')">S-RANK</button>
      </div>
    </div>
    <div class="field">
      <label class="field-label">Preferred Training</label>
      <div class="opt-grid">
        <button class="opt-btn" onclick="selectOpt(this,'train','Gym')">🏋️ GYM</button>
        <button class="opt-btn" onclick="selectOpt(this,'train','Home')">🏠 HOME</button>
        <button class="opt-btn" onclick="selectOpt(this,'train','Outdoor')">🌿 OUTDOOR</button>
        <button class="opt-btn" onclick="selectOpt(this,'train','Mixed')">⚔️ MIXED</button>
      </div>
    </div>
    <div class="btn-row">
      <button class="btn btn-ghost" onclick="goStep(2)">← BACK</button>
      <button class="btn btn-primary" onclick="goStep(4)">NEXT →</button>
    </div>
  </div>

  <!-- STEP 4: Health & Lifestyle -->
  <div class="step-card" id="step4" style="display:none;">
    <div class="step-indicator">
      <div class="step-dot done"></div>
      <div class="step-dot done"></div>
      <div class="step-dot done"></div>
      <div class="step-dot active"></div>
      <div class="step-dot"></div>
    </div>
    <div class="step-header">
      <div class="step-num">STEP 04 / 05</div>
      <div class="step-title">LIFESTYLE DATA</div>
      <div class="step-desc">> System analyzing your habits...</div>
    </div>
    <div class="field">
      <label class="field-label">Sleep Hours (per night)</label>
      <div class="opt-grid three">
        <button class="opt-btn" onclick="selectOpt(this,'sleep','< 5hrs')">☠️ &lt;5H</button>
        <button class="opt-btn" onclick="selectOpt(this,'sleep','6-7hrs')">😴 6-7H</button>
        <button class="opt-btn" onclick="selectOpt(this,'sleep','8+ hrs')">⚡ 8+H</button>
      </div>
    </div>
    <div class="field">
      <label class="field-label">Diet Type</label>
      <div class="opt-grid">
        <button class="opt-btn" onclick="selectOpt(this,'diet','Standard')">🍖 STANDARD</button>
        <button class="opt-btn" onclick="selectOpt(this,'diet','Vegetarian')">🥦 VEGGIE</button>
        <button class="opt-btn" onclick="selectOpt(this,'diet','Vegan')">🌱 VEGAN</button>
        <button class="opt-btn" onclick="selectOpt(this,'diet','Keto')">🥑 KETO</button>
      </div>
    </div>
    <div class="field">
      <label class="field-label">Daily Activity Level</label>
      <div class="opt-grid three">
        <button class="opt-btn" onclick="selectOpt(this,'activity','Sedentary')">💤 LOW</button>
        <button class="opt-btn" onclick="selectOpt(this,'activity','Moderate')">🚶 MID</button>
        <button class="opt-btn" onclick="selectOpt(this,'activity','Active')">🏃 HIGH</button>
      </div>
    </div>
    <div class="btn-row">
      <button class="btn btn-ghost" onclick="goStep(3)">← BACK</button>
      <button class="btn btn-primary" onclick="goStep(5)">NEXT →</button>
    </div>
  </div>

  <!-- STEP 5: Confirm & Awaken -->
  <div class="step-card" id="step5" style="display:none;">
    <div class="step-indicator">
      <div class="step-dot done"></div>
      <div class="step-dot done"></div>
      <div class="step-dot done"></div>
      <div class="step-dot done"></div>
      <div class="step-dot active"></div>
    </div>
    <div class="step-header">
      <div class="step-num">STEP 05 / 05</div>
      <div class="step-title">HUNTER PROFILE</div>
      <div class="step-desc">> Confirm your data before awakening.</div>
    </div>
    <div class="profile-preview" id="profilePreview"></div>
    <button class="btn btn-awaken" onclick="awaken()" style="width:100%;padding:18px;">
      ⚡ AWAKEN ⚡
    </button>
    <div class="btn-row" style="margin-top:10px;">
      <button class="btn btn-ghost" onclick="goStep(4)">← EDIT</button>
    </div>
  </div>

</div>

<!-- ===== MAIN APP ===== -->
<div class="main" id="main">

  <div class="header">
    <div class="header-top">
      <div>
        <div class="hunter-name" id="hunterName">HUNTER</div>
        <div class="rank-badge" id="rankText">⬡ E-RANK</div>
      </div>
      <div class="header-stats">
        <div class="day-text" id="dayText">DAY 1 / 60</div>
        <div style="margin-top:6px;font-family:'Orbitron',sans-serif;font-size:11px;color:var(--cyan);" id="levelDisp">LVL 1</div>
      </div>
    </div>
    <div class="xp-wrap">
      <div class="xp-label">
        <span>EXP</span>
        <span id="xpText">0 / 100</span>
      </div>
      <div class="xp-bar"><div class="xp-fill" id="xpFill"></div></div>
    </div>
  </div>

  <!-- HUNTER INFO STRIP -->
  <div class="profile-strip" id="profileStrip"></div>

  <!-- STATS -->
  <div class="stats">
    <div class="stat">
      <div class="stat-icon">🥩</div>
      <div class="stat-title">PROTEIN TARGET</div>
      <div class="stat-value" id="proteinStat">140g</div>
    </div>
    <div class="stat">
      <div class="stat-icon">💧</div>
      <div class="stat-title">WATER TARGET</div>
      <div class="stat-value">3L</div>
    </div>
    <div class="stat">
      <div class="stat-icon">🔥</div>
      <div class="stat-title">COMPLETION</div>
      <div class="stat-value" id="completionStat">0%</div>
    </div>
    <div class="stat">
      <div class="stat-icon">⚡</div>
      <div class="stat-title">LEVEL</div>
      <div class="stat-value" id="levelText">1</div>
    </div>
  </div>

  <div class="section-title">DAILY QUESTS</div>
  <div class="quest-list" id="questList"></div>

  <button class="complete-btn" id="completeBtn" onclick="completeDay()">
    ✦ COMPLETE DAY ✦
  </button>

  <div class="video-box">
    <div class="video-title">◈ DAILY MOTIVATION</div>
    <iframe width="100%" height="220"
      src="https://www.youtube.com/embed/RoypGYAxD0c"
      frameborder="0" allowfullscreen></iframe>
  </div>

  <!-- DONATE SECTION -->
  <div class="donate-box">
    <div class="donate-title">💜 SUPPORT THE DEVELOPER</div>
    <div class="donate-sub">This app is free for everyone!<br>A small donation keeps it alive 🙏</div>

    <!-- QR CODE -->
    <div class="qr-wrap">
      <div class="qr-inner">
        <img src="data:image/jpeg;base64,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" class="qr-img" alt="PhonePe QR">
      </div>
      <div class="qr-label">📱 Scan with PhonePe / Any UPI App</div>
    </div>

    <!-- QUICK AMOUNTS -->
    <div class="donate-amounts">
      <button class="donate-amt" onclick="openDonate(10)">₹10</button>
      <button class="donate-amt" onclick="openDonate(20)">₹20</button>
      <button class="donate-amt" onclick="openDonate(50)">₹50</button>
      <button class="donate-amt" onclick="openDonate(100)">₹100</button>
    </div>
    <button class="donate-btn" onclick="openDonate(0)">💜 DONATE VIA UPI</button>
  </div>

  <button class="reset-btn" onclick="resetSystem()">[ RESET HUNTER DATA ]</button>

</div>
</div>

<!-- AD POPUP -->
<div class="ad-popup" id="adPopup">
  <div class="ad-card">
    <div class="ad-top">◈ HUNTER SYSTEM ◈</div>
    <div class="ad-headline">Daily Support</div>
    <div class="ad-tagline">Your 5 seconds keeps this app free!</div>
    <div class="ad-box">
      <div class="ad-box-icon">📺</div>
      <div class="ad-box-text">AD PLAYING</div>
      <div class="ad-timer" id="adTimer">5</div>
      <div class="ad-box-sub">Please wait...</div>
    </div>
    <button class="ad-skip-btn" id="adSkipBtn" onclick="adWatched()">
      ✓ DONE — ENTER SYSTEM
    </button>
  </div>
</div>

<!-- THANKS POPUP -->
<div class="thanks-popup" id="thanksPopup">
  <div class="thanks-card">
    <div class="thanks-icon">⚡🙏⚡</div>
    <div class="thanks-title">THANK YOU!</div>
    <div class="thanks-msg">
      Your support keeps<br>
      <span style="color:var(--cyan);font-weight:700;">Hunter System</span><br>
      free for everyone!<br><br>
      You are a real Hunter! 💪<br>
      <span style="color:var(--orange);">— Developer</span>
    </div>
    <button class="thanks-btn" onclick="closeThanks()">▶ ENTER SYSTEM</button>
  </div>
</div>

<!-- POPUP -->
<div class="popup" id="popup">
  <div class="popup-card">
    <div class="popup-icon">⚡</div>
    <div class="popup-title">QUEST CLEARED</div>
    <div class="popup-sub">Daily mission accomplished, Hunter.</div>
    <div class="popup-xp" id="popupXP">+100 XP</div>
    <div style="color:var(--muted);font-family:'Share Tech Mono',monospace;font-size:11px;" id="popupLevel"></div>
    <button class="popup-btn" onclick="closePopup()">▶ CONTINUE</button>
  </div>
</div>

<script>
// =================== STATE ===================
let profile = {};
let selectedOpts = {};
let currentStep = 1;

let state = {
  day:1, level:1, xp:0,
  quests:{pushups:0,situps:0,squats:0,running:0,plank:0}
};

const targets = {pushups:100,situps:100,squats:100,running:10,plank:3};
const questMeta = {
  pushups:{icon:'💪',unit:'reps',label:'PUSH-UPS'},
  situps:{icon:'🔥',unit:'reps',label:'SIT-UPS'},
  squats:{icon:'🦵',unit:'reps',label:'SQUATS'},
  running:{icon:'🏃',unit:'km',label:'RUNNING'},
  plank:{icon:'⏱',unit:'min',label:'PLANK'}
};

// =================== PARTICLES ===================
(function(){
  const wrap = document.getElementById('particles');
  for(let i=0;i<20;i++){
    const p = document.createElement('div');
    p.className='particle';
    p.style.left = Math.random()*100+'%';
    p.style.animationDuration = (10+Math.random()*20)+'s';
    p.style.animationDelay = (Math.random()*20)+'s';
    p.style.setProperty('--dx',(Math.random()*200-100)+'px');
    p.style.width = p.style.height = (Math.random()<0.5?2:3)+'px';
    if(Math.random()<0.3) p.style.background='#ff6600';
    if(Math.random()<0.2) p.style.background='#a855f7';
    wrap.appendChild(p);
  }
})();

// =================== WIZARD ===================
function selectOpt(el, group, value){
  const parent = el.parentElement;
  parent.querySelectorAll('.opt-btn').forEach(b=>b.classList.remove('selected'));
  el.classList.add('selected');
  selectedOpts[group] = value;
}

function goStep(n){
  // Validate current step
  if(n===2){
    if(!document.getElementById('inp_name').value.trim()){
      shake('inp_name'); return;
    }
    if(!document.getElementById('inp_age').value){
      shake('inp_age'); return;
    }
    if(!selectedOpts.sex){
      alert('Please select your sex'); return;
    }
  }
  if(n===3){
    if(!document.getElementById('inp_height').value){shake('inp_height');return;}
    if(!document.getElementById('inp_weight').value){shake('inp_weight');return;}
    if(!selectedOpts.body){alert('Please select body type');return;}
  }
  if(n===4){
    if(!selectedOpts.goal){alert('Please select a fitness goal');return;}
    if(!selectedOpts.exp){alert('Please select experience level');return;}
    if(!selectedOpts.train){alert('Please select training preference');return;}
  }
  if(n===5){
    buildPreview();
  }

  document.getElementById('step'+currentStep).style.display='none';
  currentStep=n;
  document.getElementById('step'+n).style.display='block';
  document.getElementById('step'+n).style.animation='none';
  void document.getElementById('step'+n).offsetWidth;
  document.getElementById('step'+n).style.animation='cardIn 0.4s ease both';
}

function shake(id){
  const el = document.getElementById(id);
  el.style.borderColor='#ef4444';
  el.style.animation='shake 0.4s ease';
  setTimeout(()=>{el.style.borderColor='';el.style.animation='';},600);
}

function buildPreview(){
  const data = {
    'NAME': document.getElementById('inp_name').value || '—',
    'AGE': document.getElementById('inp_age').value + ' yrs' || '—',
    'SEX': selectedOpts.sex || '—',
    'HEIGHT': document.getElementById('inp_height').value + ' cm' || '—',
    'WEIGHT': document.getElementById('inp_weight').value + ' kg' || '—',
    'BODY TYPE': selectedOpts.body || '—',
    'GOAL': selectedOpts.goal || '—',
    'EXPERIENCE': selectedOpts.exp || '—',
    'TRAINING': selectedOpts.train || '—',
    'SLEEP': selectedOpts.sleep || '—',
    'DIET': selectedOpts.diet || '—',
    'ACTIVITY': selectedOpts.activity || '—',
  };
  let html='';
  for(const [k,v] of Object.entries(data)){
    html += `<div class="profile-row">
      <span class="profile-key">${k}</span>
      <span class="profile-val">${v}</span>
    </div>`;
  }
  document.getElementById('profilePreview').innerHTML=html;
}

function awaken(){
  profile = {
    name: document.getElementById('inp_name').value.trim() || 'HUNTER',
    age: document.getElementById('inp_age').value,
    sex: selectedOpts.sex || '—',
    height: document.getElementById('inp_height').value,
    weight: document.getElementById('inp_weight').value,
    body: selectedOpts.body || '—',
    goal: selectedOpts.goal || '—',
    exp: selectedOpts.exp || '—',
    train: selectedOpts.train || '—',
    sleep: selectedOpts.sleep || '—',
    diet: selectedOpts.diet || '—',
    activity: selectedOpts.activity || '—',
  };
  localStorage.setItem('hunterProfile', JSON.stringify(profile));
  loadData();
  showMain();
}

// =================== MAIN APP ===================
function showMain(){
  document.getElementById('setup').style.display='none';
  document.getElementById('main').style.display='block';
  document.getElementById('hunterName').innerText = profile.name.toUpperCase();
  buildProfileStrip();
  setProteinTarget();
  renderQuests();
  updateUI();
}

function buildProfileStrip(){
  const chips = [
    {label:'AGE', val: profile.age+'yr'},
    {label:'HEIGHT', val: profile.height+'cm'},
    {label:'WEIGHT', val: profile.weight+'kg'},
    {label:'GOAL', val: (profile.goal||'—').split(' ')[0]},
    {label:'TYPE', val: (profile.body||'—').substring(0,4)},
    {label:'DIET', val: (profile.diet||'—').substring(0,3)},
  ];
  let html='';
  chips.forEach(c=>{
    if(c.val && c.val!=='—cm' && c.val!=='—kg' && c.val!=='—yr'){
      html+=`<div class="profile-chip">
        <div class="chip-label">${c.label}</div>
        <div class="chip-val">${c.val}</div>
      </div>`;
    }
  });
  document.getElementById('profileStrip').innerHTML=html;
}

function setProteinTarget(){
  const w = parseFloat(profile.weight) || 70;
  const p = Math.round(w * 2);
  document.getElementById('proteinStat').innerText = p+'g';
}

function renderQuests(){
  const list = document.getElementById('questList');
  list.innerHTML='';
  for(const key in targets){
    const val = state.quests[key];
    const target = targets[key];
    const pct = Math.min((val/target)*100,100);
    const meta = questMeta[key];
    const isDone = val>=target;
    list.innerHTML+=`
    <div class="quest ${isDone?'done-quest':''}">
      <div class="quest-header">
        <div class="quest-name">${meta.icon} ${meta.label}</div>
        <div class="quest-badge">${isDone?'✓ DONE':meta.unit}</div>
      </div>
      <div class="quest-progress">${val} / ${target} ${meta.unit}</div>
      <div class="quest-bar">
        <div class="quest-fill ${isDone?'full':''}" style="width:${pct}%"></div>
      </div>
      ${!isDone?`<div class="quest-actions">
        <button class="quest-btn" onclick="addProgress('${key}',10)">+10</button>
        <button class="quest-btn" onclick="addProgress('${key}',25)">+25</button>
        <button class="quest-btn big" onclick="addProgress('${key}',50)">+50</button>
      </div>`:''}
    </div>`;
  }
  checkComplete();

  // Update completion stat
  let done=0;
  for(const key in targets){
    if(state.quests[key]>=targets[key]) done++;
  }
  const pct = Math.round((done/Object.keys(targets).length)*100);
  document.getElementById('completionStat').innerText = pct+'%';
}

function addProgress(type, amt){
  state.quests[type] = Math.min(state.quests[type]+amt, targets[type]);
  saveData();
  renderQuests();
}

function checkComplete(){
  let done=true;
  for(const key in targets){
    if(state.quests[key]<targets[key]){done=false;}
  }
  document.getElementById('completeBtn').style.display = done?'block':'none';
}

function completeDay(){
  const gainedXP = 100 + (state.level*10);
  state.xp += gainedXP;
  const xpNeeded = state.level * 100;
  let leveledUp = false;
  if(state.xp >= xpNeeded){
    state.xp -= xpNeeded;
    state.level++;
    leveledUp=true;
  }
  state.day++;
  state.quests={pushups:0,situps:0,squats:0,running:0,plank:0};
  saveData();
  updateUI();
  renderQuests();

  document.getElementById('popupXP').innerText = `+${gainedXP} XP`;
  document.getElementById('popupLevel').innerText = leveledUp?`⬆ LEVEL UP → ${state.level}`:`Level ${state.level} • ${state.xp}/${state.level*100} XP`;
  document.getElementById('popup').style.display='flex';
}

function closePopup(){
  document.getElementById('popup').style.display='none';
}

function updateUI(){
  document.getElementById('dayText').innerText = 'DAY '+state.day+' / 60';
  document.getElementById('levelText').innerText = state.level;
  document.getElementById('levelDisp').innerText = 'LVL '+state.level;

  const xpNeeded = state.level*100;
  const xpPct = Math.min((state.xp/xpNeeded)*100,100);
  document.getElementById('xpFill').style.width = xpPct+'%';
  document.getElementById('xpText').innerText = state.xp+' / '+xpNeeded;

  const ranks = [{d:50,r:'⬡ S-RANK'},{d:40,r:'⬡ A-RANK'},{d:30,r:'⬡ B-RANK'},{d:20,r:'⬡ C-RANK'},{d:10,r:'⬡ D-RANK'}];
  let rank='⬡ E-RANK';
  for(const r of ranks){if(state.day>=r.d){rank=r.r;break;}}
  document.getElementById('rankText').innerText = rank;
}

function saveData(){
  localStorage.setItem('hunterSystemData', JSON.stringify(state));
}

function loadData(){
  const d = localStorage.getItem('hunterSystemData');
  if(d) state=JSON.parse(d);
}

function resetSystem(){
  if(confirm('⚠ Reset all hunter data? This cannot be undone.')){
    localStorage.clear();
    location.reload();
  }
}

// =================== AD SYSTEM ===================
let adTimerInterval = null;

function showAdOnOpen(){
  const lastAdDate = localStorage.getItem('lastAdDate');
  const today = new Date().toDateString();
  if(lastAdDate !== today){
    localStorage.setItem('lastAdDate', today);
    setTimeout(()=>startAd(), 800);
  }
}

function startAd(){
  document.getElementById('adPopup').style.display='flex';
  document.getElementById('adSkipBtn').style.display='none';
  let count = 5;
  document.getElementById('adTimer').innerText = count;
  adTimerInterval = setInterval(()=>{
    count--;
    document.getElementById('adTimer').innerText = count;
    if(count <= 0){
      clearInterval(adTimerInterval);
      document.getElementById('adTimer').innerText = '✓';
      document.getElementById('adSkipBtn').style.display='block';
    }
  }, 1000);
}

function adWatched(){
  clearInterval(adTimerInterval);
  document.getElementById('adPopup').style.display='none';
  document.getElementById('thanksPopup').style.display='flex';
}

function closeThanks(){
  document.getElementById('thanksPopup').style.display='none';
}

// =================== DONATE ===================
function openDonate(amount){
  const upiId = '8341830079@ibl';
  const name = 'Hunter System';
  const note = 'Support Hunter System App';
  let url = '';
  if(amount > 0){
    url = `upi://pay?pa=${upiId}&pn=${encodeURIComponent(name)}&am=${amount}&cu=INR&tn=${encodeURIComponent(note)}`;
  } else {
    url = `upi://pay?pa=${upiId}&pn=${encodeURIComponent(name)}&cu=INR&tn=${encodeURIComponent(note)}`;
  }
  window.location.href = url;
}

// =================== INIT ===================
window.onload = ()=>{
  const savedProfile = localStorage.getItem('hunterProfile');
  if(savedProfile){
    profile = JSON.parse(savedProfile);
    loadData();
    showMain();
    showAdOnOpen();
  }
};
</script>

<style>
@keyframes shake{
  0%,100%{transform:translateX(0);}
  20%{transform:translateX(-8px);}
  40%{transform:translateX(8px);}
  60%{transform:translateX(-5px);}
  80%{transform:translateX(5px);}
}
</style>

</body>
</html>
