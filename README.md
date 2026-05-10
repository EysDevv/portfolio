[index.html.html](https://github.com/user-attachments/files/27567421/index.html.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio 2025</title>
<link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --blue:#1565C0;--blue-light:#42A5F5;--blue-bg:#1976D2;
  --orange:#FF8C00;--orange-light:#FFB74D;
  --green:#6BC53A;--green-dark:#4A9A1E;
  --pink:#FF6B9D;--pink-light:#FFB3CF;
  --sky:#74C7EC;--yellow:#FFD600;
  --cream:#FFFEF5;--paper:#FFF9E6;
  --dark:#1A1A2E;--text:#2C2C3E;
  --admin-bg:#0F1117;--admin-panel:#1A1D27;--admin-card:#22263A;--admin-border:#2E3350;--admin-accent:#6C63FF;--admin-green:#4ADE80;--admin-red:#F87171;--admin-text:#E2E8F0;--admin-muted:#94A3B8;
}
html{scroll-behavior:smooth}
body{font-family:'Nunito',sans-serif;background:var(--blue-bg);color:var(--text);overflow-x:hidden}
body::before{content:'';position:fixed;inset:0;background-image:radial-gradient(ellipse at 20% 20%,rgba(255,255,255,.07) 0%,transparent 60%),radial-gradient(ellipse at 80% 80%,rgba(255,255,255,.05) 0%,transparent 50%);pointer-events:none;z-index:0}
.bg-shapes{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.bg-shape{position:absolute;border-radius:50%;opacity:.08;background:white;animation:floatShape 8s ease-in-out infinite}
.bg-shape:nth-child(1){width:300px;height:300px;top:-100px;left:-100px}
.bg-shape:nth-child(2){width:200px;height:200px;top:40%;right:-80px;animation-delay:2s}
.bg-shape:nth-child(3){width:150px;height:150px;bottom:10%;left:5%;animation-delay:4s}
@keyframes floatShape{0%,100%{transform:translateY(0) rotate(0)}50%{transform:translateY(-30px) rotate(10deg)}}
nav{position:fixed;top:20px;left:50%;transform:translateX(-50%);z-index:200;background:var(--orange);border-radius:50px;padding:10px 28px;display:flex;gap:24px;align-items:center;box-shadow:0 6px 0 rgba(0,0,0,.25),0 8px 20px rgba(0,0,0,.2);border:3px solid rgba(255,255,255,.3)}
nav a{color:white;text-decoration:none;font-weight:800;font-size:.9rem;letter-spacing:.5px;text-shadow:0 1px 3px rgba(0,0,0,.2);transition:transform .15s;text-transform:uppercase}
nav a:hover{transform:scale(1.1)}
section{position:relative;z-index:1}

/* ── HERO ── */
#hero{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:100px 20px 60px}
.hero-folder{position:relative;max-width:780px;width:100%;animation:popIn .7s cubic-bezier(.34,1.56,.64,1) both}
@keyframes popIn{from{transform:scale(.7) rotate(-3deg);opacity:0}to{transform:scale(1) rotate(0);opacity:1}}
.folder-tabs{display:flex;gap:8px;padding:0 20px}
.ftab{height:36px;width:130px;border-radius:12px 12px 0 0;border:3px solid rgba(0,0,0,.15);border-bottom:none}
.ftab:nth-child(1){background:#e8d5a3}.ftab:nth-child(2){background:var(--orange-light)}
.folder-body{background:var(--orange);border-radius:4px 20px 20px 20px;padding:44px 50px 50px;border:4px solid rgba(0,0,0,.12);box-shadow:0 12px 0 rgba(0,0,0,.2),0 20px 40px rgba(0,0,0,.3);position:relative;overflow:hidden}
.sticker{position:absolute;animation:wobble 3s ease-in-out infinite}
.s1{top:-20px;right:60px;width:90px;height:90px;animation-delay:.5s}
.s2{bottom:30px;left:-20px;width:80px;height:80px;animation-delay:1s}
.s3{top:10px;right:-10px;width:65px;height:65px;animation-delay:1.5s}
@keyframes wobble{0%,100%{transform:rotate(-5deg) scale(1)}50%{transform:rotate(5deg) scale(1.05)}}
.hero-title{font-family:'Fredoka One',cursive;font-size:clamp(72px,14vw,140px);line-height:.9;color:var(--green);text-shadow:-4px -4px 0 white,4px -4px 0 white,-4px 4px 0 white,4px 4px 0 white,0 6px 0 var(--green-dark);letter-spacing:-2px;position:relative;z-index:2}
.hero-tags{display:flex;gap:10px;flex-wrap:wrap;margin-top:24px;position:relative;z-index:2}
.year-badge{background:#E74C3C;color:white;font-family:'Fredoka One',cursive;font-size:1.3rem;padding:4px 16px;border-radius:6px;box-shadow:0 3px 0 #a93226;transform:rotate(-2deg);display:inline-block}
.tag-banner{background:#E74C3C;color:white;font-weight:800;font-size:1rem;padding:6px 20px;border-radius:6px;box-shadow:0 3px 0 #a93226;display:inline-block;text-transform:uppercase;letter-spacing:.5px;position:relative}
.tag-banner::before{content:'';position:absolute;top:50%;left:-13px;transform:translateY(-50%);border:8px solid transparent;border-right-color:#E74C3C}
.tag-banner::after{content:'';position:absolute;top:50%;right:-13px;transform:translateY(-50%);border:8px solid transparent;border-left-color:#E74C3C}
.hero-sub{font-size:1.05rem;color:rgba(255,255,255,.9);font-weight:700;margin-top:18px;text-shadow:0 1px 4px rgba(0,0,0,.3);position:relative;z-index:2}
.hero-cta{display:inline-block;margin-top:28px;background:var(--green);color:white;font-family:'Fredoka One',cursive;font-size:1.2rem;padding:12px 32px;border-radius:50px;text-decoration:none;box-shadow:0 5px 0 var(--green-dark),0 8px 20px rgba(0,0,0,.2);transition:transform .15s,box-shadow .15s;position:relative;z-index:2}
.hero-cta:hover{transform:translateY(-3px);box-shadow:0 8px 0 var(--green-dark)}
.scroll-hint{position:absolute;bottom:30px;left:50%;transform:translateX(-50%);color:rgba(255,255,255,.7);font-size:.85rem;font-weight:800;display:flex;flex-direction:column;align-items:center;gap:6px;animation:bounce 2s ease-in-out infinite}
@keyframes bounce{0%,100%{transform:translateX(-50%) translateY(0)}50%{transform:translateX(-50%) translateY(8px)}}

/* ── ABOUT ── */
#about{padding:80px 20px;display:flex;justify-content:center}
.about-card{background:var(--paper);border-radius:20px;padding:48px;max-width:800px;width:100%;border:4px solid rgba(0,0,0,.1);box-shadow:8px 8px 0 rgba(0,0,0,.15),0 20px 50px rgba(0,0,0,.2);position:relative;transform:rotate(-.5deg)}
.about-card::before{content:'';position:absolute;top:0;left:0;right:0;bottom:0;border-radius:16px;background:repeating-linear-gradient(transparent,transparent 27px,rgba(120,170,255,.15) 27px,rgba(120,170,255,.15) 28px);pointer-events:none}
.slabel{font-family:'Fredoka One',cursive;font-size:2.4rem;color:var(--blue);margin-bottom:20px;display:flex;align-items:center;gap:12px}
.dot{width:14px;height:14px;border-radius:50%;background:var(--pink);display:inline-block;box-shadow:0 0 0 3px var(--pink-light);flex-shrink:0}
.about-card p{font-size:1.05rem;line-height:1.8;color:#444;font-weight:600}
.about-tags{display:flex;flex-wrap:wrap;gap:10px;margin-top:24px}
.chip{padding:6px 18px;border-radius:50px;font-weight:800;font-size:.9rem;border:2.5px solid rgba(0,0,0,.12);box-shadow:0 3px 0 rgba(0,0,0,.12)}
.cg{background:#DCFFB0;color:#2E6B00}.cb{background:#B8E0FF;color:#00428C}.cp{background:#FFD6E8;color:#8C0038}.co{background:#FFE8C0;color:#8C4500}.cs{background:#CCF4FF;color:#005F7A}

/* ── PROJECTS ── */
#projects{padding:60px 20px 80px}
.sec-title{text-align:center;margin-bottom:48px}
.pgrid{display:grid;grid-template-columns:repeat(auto-fill,minmax(290px,1fr));gap:28px;max-width:1100px;margin:0 auto}
.pcard{background:var(--cream);border-radius:20px;overflow:hidden;border:3px solid rgba(0,0,0,.1);box-shadow:6px 6px 0 rgba(0,0,0,.15),0 12px 30px rgba(0,0,0,.15);transition:transform .2s,box-shadow .2s;position:relative;cursor:pointer}
.pcard:hover{transform:translateY(-6px) scale(1.02);box-shadow:8px 12px 0 rgba(0,0,0,.2)}
.pcard:nth-child(even){transform:rotate(-.5deg)}
.pcard:nth-child(even):hover{transform:translateY(-6px) rotate(-.5deg) scale(1.02)}
.pthumb{height:200px;display:flex;align-items:center;justify-content:center;font-size:80px;position:relative;overflow:hidden}
.pthumb-bg{position:absolute;inset:0;opacity:.15;background:repeating-linear-gradient(45deg,transparent,transparent 10px,rgba(0,0,0,.1) 10px,rgba(0,0,0,.1) 11px)}
.pthumb img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;z-index:1}
.pemoji{position:relative;z-index:2;filter:drop-shadow(0 4px 8px rgba(0,0,0,.2))}
.tb{background:linear-gradient(135deg,#1565C0,#42A5F5)}.tg{background:linear-gradient(135deg,#2E7D32,#66BB6A)}.tp{background:linear-gradient(135deg,#6A1B9A,#AB47BC)}.to{background:linear-gradient(135deg,#E65100,#FFA726)}.tt{background:linear-gradient(135deg,#00695C,#26C6DA)}.tr{background:linear-gradient(135deg,#B71C1C,#EF5350)}
.pcontent{padding:24px}
.pname{font-family:'Fredoka One',cursive;font-size:1.5rem;color:var(--dark);margin-bottom:8px}
.pdesc{font-size:.92rem;color:#555;font-weight:600;line-height:1.6;margin-bottom:16px}
.ptags{display:flex;flex-wrap:wrap;gap:6px}
.ptag{font-size:.78rem;font-weight:800;padding:3px 10px;border-radius:50px;background:var(--green);color:white;text-transform:uppercase;letter-spacing:.5px}
.ptag.blue{background:var(--blue)}.ptag.pink{background:var(--pink)}.ptag.orange{background:var(--orange)}.ptag.sky{background:#0288D1}.ptag.purple{background:#7B1FA2}
.view-hint{position:absolute;top:12px;right:12px;background:rgba(0,0,0,.55);color:white;font-size:.75rem;font-weight:800;padding:4px 10px;border-radius:50px;opacity:0;transition:opacity .2s;z-index:5}
.pcard:hover .view-hint{opacity:1}

/* ── SKILLS ── */
#skills{padding:60px 20px;display:flex;justify-content:center}
.skills-card{background:var(--paper);border-radius:20px;padding:48px;max-width:900px;width:100%;border:4px solid rgba(0,0,0,.1);box-shadow:8px 8px 0 rgba(0,0,0,.15);transform:rotate(.4deg)}
.sgrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:20px;margin-top:28px}
.sbox{background:white;border-radius:16px;padding:20px;border:3px solid rgba(0,0,0,.1);box-shadow:4px 4px 0 rgba(0,0,0,.1);text-align:center}
.sico{font-size:2.5rem;margin-bottom:10px;display:block}
.sname{font-family:'Fredoka One',cursive;font-size:1.1rem;color:var(--dark);margin-bottom:8px}
.bwrap{height:10px;background:#E0E0E0;border-radius:10px;overflow:hidden;margin-top:8px}
.bar{height:100%;border-radius:10px;background:var(--green);transition:width 1.2s ease}
.bblue{background:var(--blue-light)}.bpink{background:var(--pink)}.borange{background:var(--orange)}

/* ── CONTACT ── */
#contact{padding:60px 20px 120px;display:flex;justify-content:center}
.contact-card{background:var(--orange);border-radius:24px;padding:48px;max-width:700px;width:100%;border:4px solid rgba(0,0,0,.12);box-shadow:8px 8px 0 rgba(0,0,0,.2),0 20px 50px rgba(0,0,0,.25);text-align:center;transform:rotate(-.5deg)}
.contact-card .slabel{color:white;justify-content:center}
.cdesc{color:rgba(255,255,255,.92);font-size:1.05rem;font-weight:700;margin-bottom:32px;line-height:1.7}
.clinks{display:flex;flex-wrap:wrap;gap:14px;justify-content:center}
.cbtn{display:inline-flex;align-items:center;gap:8px;background:white;color:var(--dark);text-decoration:none;font-weight:800;font-size:1rem;padding:12px 26px;border-radius:50px;box-shadow:0 4px 0 rgba(0,0,0,.2);transition:transform .15s,box-shadow .15s}
.cbtn:hover{transform:translateY(-3px);box-shadow:0 7px 0 rgba(0,0,0,.2)}
footer{text-align:center;padding:20px;color:rgba(255,255,255,.5);font-size:.85rem;font-weight:700;position:relative;z-index:1}

/* ── LIGHTBOX ── */
.overlay{position:fixed;inset:0;background:rgba(10,10,20,.92);z-index:1000;display:none;align-items:center;justify-content:center;padding:20px}
.overlay.open{display:flex;animation:fi .25s ease}
@keyframes fi{from{opacity:0}to{opacity:1}}
.lb-box{background:var(--paper);border-radius:24px;width:100%;max-width:960px;max-height:90vh;overflow-y:auto;border:4px solid rgba(0,0,0,.12);box-shadow:0 30px 80px rgba(0,0,0,.5);position:relative;animation:su .3s cubic-bezier(.34,1.3,.64,1)}
@keyframes su{from{transform:translateY(40px);opacity:0}to{transform:translateY(0);opacity:1}}
.xbtn{position:absolute;top:16px;right:20px;font-size:1.4rem;background:rgba(0,0,0,.08);border:none;cursor:pointer;color:#777;width:36px;height:36px;display:flex;align-items:center;justify-content:center;border-radius:50%;font-weight:800;z-index:10}
.xbtn:hover{background:rgba(0,0,0,.16)}
.lbh{padding:32px 32px 0}
.lbtitle{font-family:'Fredoka One',cursive;font-size:2rem;color:var(--dark);margin-bottom:8px}
.lbdesc{font-size:1rem;color:#555;font-weight:600;line-height:1.7;margin-bottom:16px}
.lbtags{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:24px}
.lbg{padding:0 32px 32px}
.lbgl{font-family:'Fredoka One',cursive;font-size:1.3rem;color:var(--blue);margin-bottom:14px}
.lbimgs{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:12px}
.imgw{border-radius:14px;overflow:hidden;border:3px solid rgba(0,0,0,.1);aspect-ratio:16/9;cursor:zoom-in;background:#e0e0e0;display:flex;align-items:center;justify-content:center;position:relative}
.imgw img{width:100%;height:100%;object-fit:cover;display:block;transition:transform .2s}
.imgw:hover img{transform:scale(1.05)}
.no-imgs{color:#aaa;font-style:italic;font-size:.95rem;padding:8px 0}
.zoom-ov{position:fixed;inset:0;background:rgba(0,0,0,.95);z-index:2000;display:none;align-items:center;justify-content:center}
.zoom-ov.open{display:flex}
.zoom-ov img{max-width:95vw;max-height:92vh;object-fit:contain;border-radius:8px}
.zxbtn{position:absolute;top:16px;right:20px;color:white;cursor:pointer;background:rgba(255,255,255,.15);border:none;width:44px;height:44px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:800;font-size:1.4rem}
.zxbtn:hover{background:rgba(255,255,255,.3)}

/* ══════════════════════════════════════
   ADMIN — LOGIN SCREEN
══════════════════════════════════════ */
.admin-gate{position:fixed;inset:0;background:var(--admin-bg);z-index:9000;display:none;align-items:center;justify-content:center;animation:fi .2s ease}
.admin-gate.open{display:flex}
.login-card{background:var(--admin-panel);border:1px solid var(--admin-border);border-radius:20px;padding:48px 40px;width:100%;max-width:400px;text-align:center;box-shadow:0 30px 80px rgba(0,0,0,.6)}
.login-logo{font-family:'Fredoka One',cursive;font-size:2.2rem;color:var(--admin-accent);margin-bottom:6px}
.login-sub{color:var(--admin-muted);font-size:.9rem;font-weight:600;margin-bottom:32px}
.login-input{width:100%;background:#0F1117;border:1.5px solid var(--admin-border);border-radius:10px;padding:13px 16px;color:var(--admin-text);font-family:'Nunito',sans-serif;font-size:1rem;font-weight:600;outline:none;margin-bottom:14px;transition:border-color .2s;text-align:center;letter-spacing:4px}
.login-input::placeholder{letter-spacing:0;color:#4A5568}
.login-input:focus{border-color:var(--admin-accent)}
.login-btn{width:100%;background:var(--admin-accent);color:white;border:none;border-radius:10px;padding:13px;font-family:'Fredoka One',cursive;font-size:1.1rem;cursor:pointer;transition:opacity .2s,transform .15s;box-shadow:0 4px 20px rgba(108,99,255,.4)}
.login-btn:hover{opacity:.9;transform:translateY(-2px)}
.login-err{color:var(--admin-red);font-size:.88rem;font-weight:700;margin-top:10px;min-height:20px}
.login-hint{color:#4A5568;font-size:.78rem;margin-top:20px;font-weight:600}

/* ══════════════════════════════════════
   ADMIN — PANEL
══════════════════════════════════════ */
.admin-panel{position:fixed;inset:0;background:var(--admin-bg);z-index:8999;display:none;flex-direction:column;overflow:hidden}
.admin-panel.open{display:flex}
.ap-topbar{background:var(--admin-panel);border-bottom:1px solid var(--admin-border);padding:0 24px;height:56px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0}
.ap-logo{font-family:'Fredoka One',cursive;font-size:1.3rem;color:var(--admin-accent);display:flex;align-items:center;gap:10px}
.ap-logo span{font-size:.75rem;background:rgba(108,99,255,.2);color:var(--admin-accent);padding:2px 10px;border-radius:50px;font-family:'Nunito',sans-serif;font-weight:800;letter-spacing:.5px}
.ap-topbar-right{display:flex;gap:10px;align-items:center}
.ap-preview-btn{background:rgba(74,222,128,.15);color:var(--admin-green);border:1px solid rgba(74,222,128,.3);border-radius:8px;padding:7px 16px;font-weight:800;font-size:.85rem;cursor:pointer;font-family:'Nunito',sans-serif;transition:background .15s}
.ap-preview-btn:hover{background:rgba(74,222,128,.25)}
.ap-logout{background:rgba(248,113,113,.12);color:var(--admin-red);border:1px solid rgba(248,113,113,.25);border-radius:8px;padding:7px 14px;font-weight:800;font-size:.85rem;cursor:pointer;font-family:'Nunito',sans-serif;transition:background .15s}
.ap-logout:hover{background:rgba(248,113,113,.22)}
.ap-body{display:flex;flex:1;overflow:hidden}
.ap-sidebar{width:210px;background:var(--admin-panel);border-right:1px solid var(--admin-border);padding:16px 12px;display:flex;flex-direction:column;gap:4px;flex-shrink:0;overflow-y:auto}
.ap-nav-item{display:flex;align-items:center;gap:10px;padding:10px 14px;border-radius:10px;cursor:pointer;color:var(--admin-muted);font-weight:700;font-size:.9rem;transition:background .15s,color .15s;border:none;background:none;width:100%;text-align:left;font-family:'Nunito',sans-serif}
.ap-nav-item:hover{background:rgba(255,255,255,.05);color:var(--admin-text)}
.ap-nav-item.active{background:rgba(108,99,255,.18);color:var(--admin-accent)}
.ap-nav-ico{font-size:1.1rem;width:20px;text-align:center}
.ap-content{flex:1;overflow-y:auto;padding:28px}
.ap-section{display:none}
.ap-section.active{display:block}
.ap-section-title{font-family:'Fredoka One',cursive;font-size:1.6rem;color:var(--admin-text);margin-bottom:4px}
.ap-section-sub{color:var(--admin-muted);font-size:.88rem;font-weight:600;margin-bottom:24px}
.ap-card{background:var(--admin-card);border:1px solid var(--admin-border);border-radius:14px;padding:24px;margin-bottom:18px}
.ap-card-title{color:var(--admin-accent);font-weight:800;font-size:.82rem;text-transform:uppercase;letter-spacing:.8px;margin-bottom:14px;padding-bottom:10px;border-bottom:1px solid var(--admin-border)}
.fg{margin-bottom:16px}
.fg label{display:block;color:var(--admin-muted);font-size:.82rem;font-weight:800;text-transform:uppercase;letter-spacing:.5px;margin-bottom:6px}
.fg input,.fg textarea,.fg select{width:100%;background:#0F1117;border:1.5px solid var(--admin-border);border-radius:8px;padding:10px 13px;color:var(--admin-text);font-family:'Nunito',sans-serif;font-size:.95rem;font-weight:600;outline:none;transition:border-color .2s}
.fg input:focus,.fg textarea:focus{border-color:var(--admin-accent)}
.fg textarea{min-height:80px;resize:vertical}
.fg select{cursor:pointer}
.fg select option{background:var(--admin-card)}
.ap-row{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.ap-save-btn{background:var(--admin-accent);color:white;border:none;border-radius:10px;padding:11px 28px;font-family:'Fredoka One',cursive;font-size:1rem;cursor:pointer;transition:opacity .2s,transform .15s;box-shadow:0 3px 14px rgba(108,99,255,.4)}
.ap-save-btn:hover{opacity:.9;transform:translateY(-1px)}
.save-confirm{display:inline-block;color:var(--admin-green);font-weight:800;font-size:.9rem;margin-left:12px;opacity:0;transition:opacity .3s}
.save-confirm.show{opacity:1}

/* Skills editor */
.skill-row{display:grid;grid-template-columns:40px 1fr 80px 100px auto;gap:10px;align-items:center;padding:10px 0;border-bottom:1px solid var(--admin-border)}
.skill-row:last-child{border:none}
.skill-row input{background:#0F1117;border:1.5px solid var(--admin-border);border-radius:7px;padding:7px 10px;color:var(--admin-text);font-family:'Nunito',sans-serif;font-size:.88rem;font-weight:600;outline:none;width:100%}
.skill-row input:focus{border-color:var(--admin-accent)}
.skill-row input[type=range]{padding:0;cursor:pointer;accent-color:var(--admin-accent)}
.skill-row select{background:#0F1117;border:1.5px solid var(--admin-border);border-radius:7px;padding:7px 8px;color:var(--admin-text);font-family:'Nunito',sans-serif;font-size:.8rem;outline:none}
.skill-row .pct{color:var(--admin-muted);font-size:.85rem;font-weight:700;text-align:center}
.add-row-btn{background:rgba(108,99,255,.15);color:var(--admin-accent);border:1px dashed rgba(108,99,255,.4);border-radius:8px;padding:8px 16px;font-weight:800;font-size:.85rem;cursor:pointer;font-family:'Nunito',sans-serif;margin-top:12px;transition:background .15s}
.add-row-btn:hover{background:rgba(108,99,255,.25)}
.del-row-btn{background:rgba(248,113,113,.12);color:var(--admin-red);border:1px solid rgba(248,113,113,.2);border-radius:7px;padding:6px 10px;cursor:pointer;font-size:.85rem;font-weight:800;font-family:'Nunito',sans-serif}
.del-row-btn:hover{background:rgba(248,113,113,.22)}

/* Projects editor list */
.proj-row{display:flex;align-items:center;gap:14px;padding:12px 16px;background:#0F1117;border:1px solid var(--admin-border);border-radius:10px;margin-bottom:10px;cursor:pointer;transition:border-color .15s}
.proj-row:hover{border-color:var(--admin-accent)}
.proj-row-emoji{font-size:1.8rem;flex-shrink:0}
.proj-row-info{flex:1}
.proj-row-name{color:var(--admin-text);font-weight:800;font-size:.95rem}
.proj-row-tags{color:var(--admin-muted);font-size:.8rem;margin-top:2px}
.proj-row-edit{background:rgba(108,99,255,.15);color:var(--admin-accent);border:1px solid rgba(108,99,255,.3);border-radius:8px;padding:6px 14px;font-weight:800;font-size:.8rem;cursor:pointer;font-family:'Nunito',sans-serif;flex-shrink:0}
.proj-row-edit:hover{background:rgba(108,99,255,.25)}
.new-proj-btn{width:100%;background:rgba(74,222,128,.1);color:var(--admin-green);border:1.5px dashed rgba(74,222,128,.4);border-radius:10px;padding:12px;font-family:'Fredoka One',cursive;font-size:1rem;cursor:pointer;margin-top:4px;transition:background .15s}
.new-proj-btn:hover{background:rgba(74,222,128,.18)}

/* Proj edit form inside admin */
.proj-edit-form{display:none;background:#0F1117;border:1px solid var(--admin-border);border-radius:12px;padding:20px;margin-top:14px}
.proj-edit-form.open{display:block}
.iurow{display:flex;gap:8px;align-items:center;margin-bottom:8px}
.iurow input{flex:1;background:#1A1D27;border:1.5px solid var(--admin-border);border-radius:7px;padding:8px 12px;color:var(--admin-text);font-family:'Nunito',sans-serif;font-size:.88rem;font-weight:600;outline:none}
.iurow input:focus{border-color:var(--admin-accent)}
.rm-btn{background:rgba(248,113,113,.12);border:1px solid rgba(248,113,113,.2);border-radius:7px;padding:7px 11px;cursor:pointer;font-size:.9rem;color:var(--admin-red)}
.rm-btn:hover{background:rgba(248,113,113,.22)}
.ai-btn{background:rgba(116,199,236,.12);color:var(--sky);border:1px solid rgba(116,199,236,.25);border-radius:7px;padding:7px 14px;font-weight:800;font-size:.82rem;cursor:pointer;font-family:'Nunito',sans-serif}
.proj-form-footer{display:flex;gap:10px;margin-top:16px;flex-wrap:wrap}
.pf-save{background:var(--admin-accent);color:white;border:none;border-radius:9px;padding:9px 22px;font-weight:800;font-size:.88rem;cursor:pointer;font-family:'Nunito',sans-serif}
.pf-cancel{background:rgba(255,255,255,.05);color:var(--admin-muted);border:1px solid var(--admin-border);border-radius:9px;padding:9px 18px;font-weight:800;font-size:.88rem;cursor:pointer;font-family:'Nunito',sans-serif}
.pf-del{background:rgba(248,113,113,.12);color:var(--admin-red);border:1px solid rgba(248,113,113,.25);border-radius:9px;padding:9px 18px;font-weight:800;font-size:.88rem;cursor:pointer;font-family:'Nunito',sans-serif;margin-left:auto}
.pf-del:hover{background:rgba(248,113,113,.22)}

/* Contact links editor */
.link-row{display:grid;grid-template-columns:36px 1fr 1fr auto;gap:10px;align-items:center;padding:10px 0;border-bottom:1px solid var(--admin-border)}
.link-row:last-child{border:none}
.link-row input{background:#0F1117;border:1.5px solid var(--admin-border);border-radius:7px;padding:7px 10px;color:var(--admin-text);font-family:'Nunito',sans-serif;font-size:.88rem;font-weight:600;outline:none;width:100%}
.link-row input:focus{border-color:var(--admin-accent)}
.link-emoji-in{text-align:center;font-size:1.2rem}

/* Password change */
.pw-row{display:flex;gap:10px;align-items:center}
.pw-row input{flex:1;background:#0F1117;border:1.5px solid var(--admin-border);border-radius:8px;padding:10px 13px;color:var(--admin-text);font-family:'Nunito',sans-serif;font-size:.95rem;font-weight:600;outline:none}
.pw-row input:focus{border-color:var(--admin-accent)}

/* Admin trigger (secret) */
.admin-trigger{position:fixed;bottom:28px;right:28px;z-index:500;background:rgba(0,0,0,.0);border:none;width:44px;height:44px;cursor:pointer;border-radius:50%}

@media(max-width:768px){
  .ap-body{flex-direction:column}
  .ap-sidebar{width:100%;flex-direction:row;overflow-x:auto;padding:10px;gap:6px}
  .ap-nav-item{flex-shrink:0;padding:8px 12px}
  .ap-row{grid-template-columns:1fr}
  .skill-row{grid-template-columns:30px 1fr auto;flex-wrap:wrap}
  .link-row{grid-template-columns:30px 1fr auto}
}
@media(max-width:600px){
  .folder-body{padding:32px 24px 36px}
  .hero-title{font-size:clamp(60px,18vw,100px)}
  .about-card,.skills-card,.contact-card{padding:28px}
  nav{gap:12px;padding:10px 18px}
  nav a{font-size:.78rem}
}
</style>
</head>
<body>
<div class="bg-shapes"><div class="bg-shape"></div><div class="bg-shape"></div><div class="bg-shape"></div></div>

<nav>
  <a href="#hero">Home</a><a href="#about">About</a><a href="#projects">Maps</a><a href="#skills">Skills</a><a href="#contact">Contact</a>
</nav>

<!-- ═══ HERO ═══ -->
<section id="hero">
  <div class="hero-folder">
    <div class="folder-tabs"><div class="ftab"></div><div class="ftab"></div></div>
    <div class="folder-body">
      <svg style="position:absolute;top:-38px;left:22px;width:52px;height:90px;z-index:10" viewBox="0 0 52 90" fill="none">
        <path d="M34 8C34 4 30 1 26 1 22 1 18 4 18 8L18 62C18 70 24 76 32 76 40 76 46 70 46 62L46 18C46 12 42 8 36 8 30 8 26 12 26 18L26 60C26 64 29 67 32 67 35 67 38 64 38 60L38 20" stroke="#CCC" stroke-width="5.5" stroke-linecap="round"/>
      </svg>
      <svg class="sticker s1" viewBox="0 0 100 100"><polygon points="50,5 61,35 95,35 68,57 79,91 50,70 21,91 32,57 5,35 39,35" fill="#FF6B9D" stroke="white" stroke-width="5" stroke-linejoin="round"/></svg>
      <svg class="sticker s2" viewBox="0 0 100 100"><polygon points="50,5 61,35 95,35 68,57 79,91 50,70 21,91 32,57 5,35 39,35" fill="#74C7EC" stroke="white" stroke-width="5" stroke-linejoin="round"/></svg>
      <svg class="sticker s3" viewBox="0 0 80 80"><g transform="translate(40,40)"><line x1="0" y1="-30" x2="0" y2="30" stroke="#FFD600" stroke-width="10" stroke-linecap="round"/><line x1="-26" y1="-15" x2="26" y2="15" stroke="#FFD600" stroke-width="10" stroke-linecap="round"/><line x1="-26" y1="15" x2="26" y2="-15" stroke="#FFD600" stroke-width="10" stroke-linecap="round"/><circle cx="0" cy="0" r="6" fill="white"/></g><circle cx="40" cy="40" r="36" fill="none" stroke="white" stroke-width="4"/></svg>
      <div class="hero-title" id="heroTitle">Port<br>folio</div>
      <div class="hero-tags">
        <span class="year-badge" id="heroYear">2025</span>
        <span class="tag-banner" id="heroTag1">Level Design</span>
        <span class="tag-banner" id="heroTag2">3D Modeling</span>
      </div>
      <p class="hero-sub" id="heroSub">Building worlds, one map at a time ✦ Level Designer & Map Builder</p>
      <a href="#projects" class="hero-cta" id="heroCtaEl">Explore My Maps →</a>
    </div>
  </div>
  <div class="scroll-hint"><span>Scroll</span><span style="font-size:1.4rem">↓</span></div>
</section>

<!-- ═══ ABOUT ═══ -->
<section id="about">
  <div class="about-card">
    <div class="slabel"><span class="dot"></span><span id="aboutTitle">About Me</span></div>
    <p id="aboutP1">Hey! I'm a passionate <strong>Level Designer, Map Builder & 3D Modeler</strong> who loves crafting immersive game environments and gameplay spaces. From dense urban dungeons to sprawling open worlds, I design levels that feel alive — where every corner tells a story and every path rewards exploration.</p>
    <p id="aboutP2" style="margin-top:14px">I focus on player experience first: flow, pacing, verticality, and environmental storytelling. Whether it's a tight combat arena or a vast terrain, I make sure every map plays as good as it looks.</p>
    <div class="about-tags" id="aboutTags"></div>
  </div>
</section>

<!-- ═══ PROJECTS ═══ -->
<section id="projects">
  <div class="sec-title">
    <div class="slabel" style="justify-content:center;font-size:3rem;color:white;text-shadow:3px 3px 0 rgba(0,0,0,.2)">
      <span class="dot" style="background:var(--yellow);box-shadow:0 0 0 3px rgba(255,214,0,.3)"></span>
      <span id="projectsTitle">My Maps</span>
    </div>
  </div>
  <div class="pgrid" id="pgrid"></div>
</section>

<!-- ═══ SKILLS ═══ -->
<section id="skills">
  <div class="skills-card">
    <div class="slabel"><span class="dot" style="background:var(--orange);box-shadow:0 0 0 3px rgba(255,140,0,.3)"></span><span id="skillsTitle">Toolbox</span></div>
    <div class="sgrid" id="sgrid"></div>
  </div>
</section>

<!-- ═══ CONTACT ═══ -->
<section id="contact">
  <div class="contact-card">
    <div class="slabel" style="color:white;justify-content:center"><span id="contactTitle">Let's Build!</span></div>
    <p class="cdesc" id="contactDesc">Got a project, a mod, or a world that needs a skilled level designer? I'd love to be part of it. Drop me a message!</p>
    <div class="clinks" id="clinks"></div>
  </div>
</section>
<footer id="footerEl">Made with ♥ · Level Design & 3D Modeling Portfolio 2025</footer>

<!-- Secret admin trigger — invisible button bottom-right -->
<button class="admin-trigger" id="adminTrigger" title=""></button>

<!-- ═══ LIGHTBOX ═══ -->
<div class="overlay" id="lb" onclick="closeLbBg(event)">
  <div class="lb-box">
    <button class="xbtn" onclick="closeLb()">✕</button>
    <div class="lbh">
      <div class="lbtitle" id="lbTitle"></div>
      <div class="lbdesc" id="lbDesc"></div>
      <div class="lbtags" id="lbTags"></div>
    </div>
    <div class="lbg">
      <div class="lbgl">📸 Reference Images</div>
      <div class="lbimgs" id="lbImgs"></div>
    </div>
  </div>
</div>
<div class="zoom-ov" id="zoom" onclick="closeZoom()">
  <button class="zxbtn" onclick="closeZoom()">✕</button>
  <img id="zoomImg" src="" alt="">
</div>

<!-- ═══ ADMIN LOGIN ═══ -->
<div class="admin-gate" id="adminGate">
  <div class="login-card">
    <div class="login-logo">⚙️ Admin</div>
    <div class="login-sub">Portfolio Control Panel</div>
    <input class="login-input" type="password" id="loginPw" placeholder="Enter password" autocomplete="off">
    <button class="login-btn" onclick="tryLogin()">Unlock Panel</button>
    <div class="login-err" id="loginErr"></div>
    <div class="login-hint">Press Esc to close</div>
  </div>
</div>

<!-- ═══ ADMIN PANEL ═══ -->
<div class="admin-panel" id="adminPanel">
  <div class="ap-topbar">
    <div class="ap-logo">⚙️ Admin Panel <span>EDITOR</span></div>
    <div class="ap-topbar-right">
      <button class="ap-preview-btn" onclick="closeAdmin()">👁 Preview Site</button>
      <button class="ap-logout" onclick="logout()">Logout</button>
    </div>
  </div>
  <div class="ap-body">
    <!-- SIDEBAR -->
    <div class="ap-sidebar">
      <button class="ap-nav-item active" onclick="showTab('hero',this)"><span class="ap-nav-ico">🏠</span>Hero</button>
      <button class="ap-nav-item" onclick="showTab('about',this)"><span class="ap-nav-ico">👤</span>About</button>
      <button class="ap-nav-item" onclick="showTab('projects',this)"><span class="ap-nav-ico">🗺️</span>Projects</button>
      <button class="ap-nav-item" onclick="showTab('skills',this)"><span class="ap-nav-ico">🎮</span>Skills</button>
      <button class="ap-nav-item" onclick="showTab('contact',this)"><span class="ap-nav-ico">✉️</span>Contact</button>
      <button class="ap-nav-item" onclick="showTab('settings',this)"><span class="ap-nav-ico">🔑</span>Settings</button>
    </div>

    <!-- CONTENT -->
    <div class="ap-content">

      <!-- HERO TAB -->
      <div class="ap-section active" id="tab-hero">
        <div class="ap-section-title">Hero Section</div>
        <div class="ap-section-sub">Edit your main headline, tags, subtitle and call-to-action</div>
        <div class="ap-card">
          <div class="ap-card-title">Headlines</div>
          <div class="fg"><label>Year Badge</label><input type="text" id="f-heroYear" placeholder="2025"></div>
          <div class="ap-row">
            <div class="fg"><label>Tag 1</label><input type="text" id="f-heroTag1" placeholder="Level Design"></div>
            <div class="fg"><label>Tag 2</label><input type="text" id="f-heroTag2" placeholder="3D Modeling"></div>
          </div>
          <div class="fg"><label>Subtitle / Tagline</label><input type="text" id="f-heroSub" placeholder="Building worlds, one map at a time..."></div>
          <div class="fg"><label>CTA Button Text</label><input type="text" id="f-heroCta" placeholder="Explore My Maps →"></div>
        </div>
        <button class="ap-save-btn" onclick="saveHero()">Save Hero</button>
        <span class="save-confirm" id="sc-hero">✓ Saved!</span>
      </div>

      <!-- ABOUT TAB -->
      <div class="ap-section" id="tab-about">
        <div class="ap-section-title">About Section</div>
        <div class="ap-section-sub">Edit your bio and skill tags shown on the about card</div>
        <div class="ap-card">
          <div class="ap-card-title">Bio Text</div>
          <div class="fg"><label>Section Title</label><input type="text" id="f-aboutTitle" placeholder="About Me"></div>
          <div class="fg"><label>Paragraph 1</label><textarea id="f-aboutP1"></textarea></div>
          <div class="fg"><label>Paragraph 2</label><textarea id="f-aboutP2"></textarea></div>
        </div>
        <div class="ap-card">
          <div class="ap-card-title">Skill Chips (comma separated)</div>
          <div class="fg"><label>Chips — separate with commas</label><input type="text" id="f-aboutChips" placeholder="Level Design, 3D Modeling, Map Building"></div>
        </div>
        <button class="ap-save-btn" onclick="saveAbout()">Save About</button>
        <span class="save-confirm" id="sc-about">✓ Saved!</span>
      </div>

      <!-- PROJECTS TAB -->
      <div class="ap-section" id="tab-projects">
        <div class="ap-section-title">Projects</div>
        <div class="ap-section-sub">Click a project to edit it, or add a new one</div>
        <div class="ap-card">
          <div class="ap-card-title">Section Title</div>
          <div class="fg"><label>Section Heading</label><input type="text" id="f-projectsTitle" placeholder="My Maps" oninput="applyProjectsTitle()"></div>
        </div>
        <div class="ap-card">
          <div class="ap-card-title">Projects List</div>
          <div id="projList"></div>
          <button class="new-proj-btn" onclick="openProjForm(-1)">＋ Add New Project</button>
        </div>
        <div class="proj-edit-form" id="projForm">
          <div style="font-family:'Fredoka One',cursive;font-size:1.1rem;color:var(--admin-accent);margin-bottom:16px" id="projFormTitle">New Project</div>
          <div class="ap-row">
            <div class="fg"><label>Name</label><input type="text" id="pf-name" placeholder="Project name"></div>
            <div class="fg"><label>Emoji</label><input type="text" id="pf-emoji" placeholder="🏰" maxlength="4"></div>
          </div>
          <div class="fg"><label>Description</label><textarea id="pf-desc" placeholder="Describe your project..."></textarea></div>
          <div class="ap-row">
            <div class="fg"><label>Color Theme</label>
              <select id="pf-color">
                <option value="tb">🔵 Blue</option><option value="tg">🟢 Green</option><option value="tp">🟣 Purple</option><option value="to">🟠 Orange</option><option value="tt">🩵 Teal</option><option value="tr">🔴 Red</option>
              </select>
            </div>
            <div class="fg"><label>Tags (comma separated)</label><input type="text" id="pf-tags" placeholder="Unreal Engine, PvP, 3D Modeled"></div>
          </div>
          <div class="fg">
            <label>Reference Image URLs</label>
            <p style="font-size:.78rem;color:var(--admin-muted);margin-bottom:8px;font-weight:600">First image = cover photo. Use Imgur, ArtStation, or ImgBB links.</p>
            <div id="pf-imgList"></div>
            <button class="ai-btn" onclick="addImgRow()">+ Add Image URL</button>
          </div>
          <div class="proj-form-footer">
            <button class="pf-del" id="pf-delBtn" onclick="deleteProj()" style="display:none">🗑 Delete</button>
            <button class="pf-cancel" onclick="closeProjForm()">Cancel</button>
            <button class="pf-save" onclick="saveProj()">Save Project ✓</button>
          </div>
        </div>
      </div>

      <!-- SKILLS TAB -->
      <div class="ap-section" id="tab-skills">
        <div class="ap-section-title">Skills / Toolbox</div>
        <div class="ap-section-sub">Edit each skill, its icon, level and bar colour</div>
        <div class="ap-card">
          <div class="ap-card-title">Section Title</div>
          <div class="fg"><label>Section Heading</label><input type="text" id="f-skillsTitle" placeholder="Toolbox" oninput="applySkillsTitle()"></div>
        </div>
        <div class="ap-card">
          <div class="ap-card-title" style="display:grid;grid-template-columns:40px 1fr 80px 100px auto;gap:10px;font-size:.75rem">
            <span>Icon</span><span>Skill Name</span><span>Level %</span><span>Bar Color</span><span></span>
          </div>
          <div id="skillRows"></div>
          <button class="add-row-btn" onclick="addSkillRow()">+ Add Skill</button>
        </div>
        <button class="ap-save-btn" onclick="saveSkills()">Save Skills</button>
        <span class="save-confirm" id="sc-skills">✓ Saved!</span>
      </div>

      <!-- CONTACT TAB -->
      <div class="ap-section" id="tab-contact">
        <div class="ap-section-title">Contact Section</div>
        <div class="ap-section-sub">Edit your contact heading, description and links</div>
        <div class="ap-card">
          <div class="ap-card-title">Text</div>
          <div class="fg"><label>Section Title</label><input type="text" id="f-contactTitle" placeholder="Let's Build!"></div>
          <div class="fg"><label>Description</label><textarea id="f-contactDesc"></textarea></div>
          <div class="fg"><label>Footer Text</label><input type="text" id="f-footer" placeholder="Made with ♥ · Portfolio 2025"></div>
        </div>
        <div class="ap-card">
          <div class="ap-card-title" style="display:grid;grid-template-columns:36px 1fr 1fr auto;gap:10px;font-size:.75rem"><span>Icon</span><span>Label</span><span>URL / href</span><span></span></div>
          <div id="linkRows"></div>
          <button class="add-row-btn" onclick="addLinkRow()">+ Add Link</button>
        </div>
        <button class="ap-save-btn" onclick="saveContact()">Save Contact</button>
        <span class="save-confirm" id="sc-contact">✓ Saved!</span>
      </div>

      <!-- SETTINGS TAB -->
      <div class="ap-section" id="tab-settings">
        <div class="ap-section-title">Settings</div>
        <div class="ap-section-sub">Change your admin password</div>
        <div class="ap-card">
          <div class="ap-card-title">Change Password</div>
          <div class="fg"><label>Current Password</label><div class="pw-row"><input type="password" id="s-curPw" placeholder="Current password"></div></div>
          <div class="fg"><label>New Password</label><div class="pw-row"><input type="password" id="s-newPw" placeholder="New password"></div></div>
          <div class="fg"><label>Confirm New Password</label><div class="pw-row"><input type="password" id="s-confPw" placeholder="Confirm new password"></div></div>
          <div class="login-err" id="pw-err"></div>
        </div>
        <button class="ap-save-btn" onclick="changePassword()">Update Password</button>
        <span class="save-confirm" id="sc-pw">✓ Password updated!</span>
        <div class="ap-card" style="margin-top:24px">
          <div class="ap-card-title">Reset All Data</div>
          <p style="color:var(--admin-muted);font-size:.88rem;font-weight:600;margin-bottom:14px">This will reset ALL site content back to defaults. Cannot be undone.</p>
          <button class="ap-logout" onclick="resetAll()" style="font-family:'Nunito',sans-serif">⚠️ Reset Everything</button>
        </div>
      </div>

    </div><!-- /ap-content -->
  </div><!-- /ap-body -->
</div><!-- /admin-panel -->

<script>
// ═══════════════════════════════════════════
// DEFAULT DATA
// ═══════════════════════════════════════════
const TC=['blue','pink','orange','sky','purple',''];
const CHIP_CLASSES=['cg','cb','cp','co','cs','cg','cb'];

const DEFAULTS={
  password:'admin1234',
  hero:{year:'2025',tag1:'Level Design',tag2:'3D Modeling',sub:'Building worlds, one map at a time ✦ Level Designer & Map Builder',cta:'Explore My Maps →'},
  about:{title:'About Me',p1:"Hey! I'm a passionate Level Designer, Map Builder & 3D Modeler who loves crafting immersive game environments and gameplay spaces. From dense urban dungeons to sprawling open worlds, I design levels that feel alive — where every corner tells a story and every path rewards exploration.",p2:"I focus on player experience first: flow, pacing, verticality, and environmental storytelling. Whether it's a tight combat arena or a vast terrain, I make sure every map plays as good as it looks.",chips:'Level Design,3D Modeling,Map Building,Terrain Sculpting,Environmental Art,Gameplay Flow,World Building'},
  projectsTitle:'My Maps',
  projects:[
    {name:'Duskhold Fortress',desc:'A multi-tiered castle siege map with dynamic choke points, flanking routes, and a destructible gatehouse mechanic.',emoji:'🏰',color:'tb',tags:['Unreal Engine','PvP','3D Modeled'],images:[]},
    {name:'Verdant Hollow',desc:'An open-world exploration zone featuring dense forest canopies, hidden ruins, and layered verticality across 2km² of terrain.',emoji:'🌿',color:'tg',tags:['Unity','Terrain','Open World'],images:[]},
    {name:'Void Station Alpha',desc:'Sci-fi space station with modular corridor design, zero-gravity zones, and branching narrative paths across 3 floors.',emoji:'🌌',color:'tp',tags:['Unreal Engine','Sci-Fi','Modular'],images:[]},
    {name:'Ashpeak Canyon',desc:'A desert canyon racing map with cliff-side shortcuts, massive jump ramps, and hand-sculpted rock formations.',emoji:'🏜️',color:'to',tags:['Racing','Blender','Sculpted'],images:[]},
    {name:'Sunken Archive',desc:'Underwater dungeon crawler with flooded libraries, air-pocket puzzles, and bioluminescent prop models built from scratch.',emoji:'🌊',color:'tt',tags:['Dungeon','3D Props','Blender'],images:[]},
    {name:'Ember Caldera',desc:'High-intensity PvP arena built around an active volcano, with rising lava mechanics and asymmetric team bases.',emoji:'🌋',color:'tr',tags:['Unreal Engine','Arena','PvP'],images:[]}
  ],
  skillsTitle:'Toolbox',
  skills:[
    {icon:'🎮',name:'Unreal Engine',pct:90,color:'bblue'},
    {icon:'🕹️',name:'Unity',pct:75,color:'bblue'},
    {icon:'🧊',name:'Blender',pct:85,color:'borange'},
    {icon:'🗺️',name:'Map Building',pct:95,color:''},
    {icon:'⛰️',name:'Terrain Sculpt',pct:80,color:'bpink'},
    {icon:'🎨',name:'Texturing',pct:70,color:'borange'}
  ],
  contact:{title:"Let's Build!",desc:"Got a project, a mod, or a world that needs a skilled level designer? I'd love to be part of it. Drop me a message!",footer:'Made with ♥ · Level Design & 3D Modeling Portfolio 2025'},
  links:[
    {icon:'✉️',label:'Email Me',href:'mailto:hello@yourportfolio.com'},
    {icon:'💼',label:'ArtStation',href:'#'},
    {icon:'🎮',label:'Discord',href:'#'},
    {icon:'🐙',label:'GitHub',href:'#'}
  ]
};

// ═══════════════════════════════════════════
// STATE
// ═══════════════════════════════════════════
function load(key,def){try{const v=localStorage.getItem('pf_'+key);return v?JSON.parse(v):def}catch(e){return def}}
function persist(key,val){localStorage.setItem('pf_'+key,JSON.stringify(val))}

let pw=load('password',DEFAULTS.password);
let hero=load('hero',DEFAULTS.hero);
let about=load('about',DEFAULTS.about);
let projectsTitle=load('projectsTitle',DEFAULTS.projectsTitle);
let projects=load('projects',DEFAULTS.projects);
let skillsTitle=load('skillsTitle',DEFAULTS.skillsTitle);
let skills=load('skills',DEFAULTS.skills);
let contact=load('contact',DEFAULTS.contact);
let links=load('links',DEFAULTS.links);
let isLoggedIn=false;
let editProjIdx=-1;

// ═══════════════════════════════════════════
// RENDER SITE
// ═══════════════════════════════════════════
function renderSite(){
  // Hero
  document.getElementById('heroYear').textContent=hero.year;
  document.getElementById('heroTag1').textContent=hero.tag1;
  document.getElementById('heroTag2').textContent=hero.tag2;
  document.getElementById('heroSub').textContent=hero.sub;
  document.getElementById('heroCtaEl').textContent=hero.cta;
  // About
  document.getElementById('aboutTitle').textContent=about.title;
  document.getElementById('aboutP1').textContent=about.p1;
  document.getElementById('aboutP2').textContent=about.p2;
  const chips=about.chips.split(',').map(s=>s.trim()).filter(Boolean);
  document.getElementById('aboutTags').innerHTML=chips.map((c,i)=>`<span class="chip ${CHIP_CLASSES[i%CHIP_CLASSES.length]}">${c}</span>`).join('');
  // Projects section title
  document.getElementById('projectsTitle').textContent=projectsTitle;
  // Projects grid
  const g=document.getElementById('pgrid');g.innerHTML='';
  projects.forEach((p,i)=>{
    const c=document.createElement('div');c.className='pcard';
    c.innerHTML=`<div class="view-hint">👁 View Project</div>
      <div class="pthumb ${p.color}"><div class="pthumb-bg"></div>
        ${p.images&&p.images[0]?`<img src="${p.images[0]}" alt="" onerror="this.style.display='none'">`:''}
        <span class="pemoji">${p.emoji||'🎮'}</span></div>
      <div class="pcontent">
        <div class="pname">${p.name}</div>
        <div class="pdesc">${p.desc}</div>
        <div class="ptags">${p.tags.map((t,ti)=>`<span class="ptag ${TC[ti%TC.length]}">${t}</span>`).join('')}</div>
      </div>`;
    c.addEventListener('click',()=>openLb(i));
    g.appendChild(c);
  });
  // Skills
  document.getElementById('skillsTitle').textContent=skillsTitle;
  document.getElementById('sgrid').innerHTML=skills.map(s=>`
    <div class="sbox"><span class="sico">${s.icon}</span><div class="sname">${s.name}</div>
    <div class="bwrap"><div class="bar ${s.color}" data-w="${s.pct}%" style="width:0"></div></div></div>`).join('');
  // Animate bars next tick
  setTimeout(()=>{
    document.querySelectorAll('[data-w]').forEach(b=>b.style.width=b.dataset.w);
  },50);
  // Contact
  document.getElementById('contactTitle').textContent=contact.title;
  document.getElementById('contactDesc').textContent=contact.desc;
  document.getElementById('footerEl').textContent=contact.footer;
  document.getElementById('clinks').innerHTML=links.map(l=>`<a href="${l.href}" class="cbtn">${l.icon} ${l.label}</a>`).join('');
}

// ═══════════════════════════════════════════
// LIGHTBOX
// ═══════════════════════════════════════════
function openLb(i){
  const p=projects[i];
  document.getElementById('lbTitle').textContent=p.name;
  document.getElementById('lbDesc').textContent=p.desc;
  document.getElementById('lbTags').innerHTML=p.tags.map((t,ti)=>`<span class="ptag ${TC[ti%TC.length]}">${t}</span>`).join('');
  const el=document.getElementById('lbImgs');
  el.innerHTML=(!p.images||!p.images.length)
    ?'<p class="no-imgs">No reference images yet.</p>'
    :p.images.map(u=>`<div class="imgw" onclick="zoomImg('${u}')"><img src="${u}" alt="" onerror="this.parentElement.innerHTML='🖼️'" loading="lazy"></div>`).join('');
  document.getElementById('lb').classList.add('open');
  document.body.style.overflow='hidden';
}
function closeLb(){document.getElementById('lb').classList.remove('open');document.body.style.overflow=''}
function closeLbBg(e){if(e.target===document.getElementById('lb'))closeLb()}
function zoomImg(u){document.getElementById('zoomImg').src=u;document.getElementById('zoom').classList.add('open')}
function closeZoom(){document.getElementById('zoom').classList.remove('open')}

// ═══════════════════════════════════════════
// ADMIN AUTH
// ═══════════════════════════════════════════
// Secret trigger: click admin trigger button
let clickCount=0,clickTimer=null;
document.getElementById('adminTrigger').addEventListener('click',()=>{
  clickCount++;
  clearTimeout(clickTimer);
  clickTimer=setTimeout(()=>clickCount=0,2000);
  if(clickCount>=3){
    clickCount=0;
    if(isLoggedIn)openAdmin();else openGate();
  }
});

// Also: Konami-style — type "admin" anywhere (not in an input) to open gate
let keyBuf='';
document.addEventListener('keydown',e=>{
  if(e.target.tagName==='INPUT'||e.target.tagName==='TEXTAREA')return;
  keyBuf+=e.key.toLowerCase();
  if(keyBuf.length>5)keyBuf=keyBuf.slice(-5);
  if(keyBuf==='admin'){keyBuf='';if(isLoggedIn)openAdmin();else openGate();}
  if(e.key==='Escape'){closeGate();closeAdmin();closeLb();closeZoom();}
});
document.getElementById('loginPw').addEventListener('keydown',e=>{if(e.key==='Enter')tryLogin()});

function openGate(){document.getElementById('adminGate').classList.add('open');document.getElementById('loginPw').value='';document.getElementById('loginErr').textContent='';setTimeout(()=>document.getElementById('loginPw').focus(),100)}
function closeGate(){document.getElementById('adminGate').classList.remove('open')}
function tryLogin(){
  const v=document.getElementById('loginPw').value;
  if(v===pw){isLoggedIn=true;closeGate();openAdmin();}
  else{document.getElementById('loginErr').textContent='Wrong password. Try again.';document.getElementById('loginPw').value='';}
}
function logout(){isLoggedIn=false;closeAdmin()}
function openAdmin(){
  populateAdminForms();
  document.getElementById('adminPanel').classList.add('open');
  document.body.style.overflow='hidden';
}
function closeAdmin(){document.getElementById('adminPanel').classList.remove('open');document.body.style.overflow=''}

// ═══════════════════════════════════════════
// POPULATE ADMIN FORMS
// ═══════════════════════════════════════════
function populateAdminForms(){
  // Hero
  document.getElementById('f-heroYear').value=hero.year;
  document.getElementById('f-heroTag1').value=hero.tag1;
  document.getElementById('f-heroTag2').value=hero.tag2;
  document.getElementById('f-heroSub').value=hero.sub;
  document.getElementById('f-heroCta').value=hero.cta;
  // About
  document.getElementById('f-aboutTitle').value=about.title;
  document.getElementById('f-aboutP1').value=about.p1;
  document.getElementById('f-aboutP2').value=about.p2;
  document.getElementById('f-aboutChips').value=about.chips;
  // Projects
  document.getElementById('f-projectsTitle').value=projectsTitle;
  renderProjList();
  // Skills
  document.getElementById('f-skillsTitle').value=skillsTitle;
  renderSkillRows();
  // Contact
  document.getElementById('f-contactTitle').value=contact.title;
  document.getElementById('f-contactDesc').value=contact.desc;
  document.getElementById('f-footer').value=contact.footer;
  renderLinkRows();
}

// ═══════════════════════════════════════════
// SAVE FUNCTIONS
// ═══════════════════════════════════════════
function flash(id){const el=document.getElementById(id);el.classList.add('show');setTimeout(()=>el.classList.remove('show'),2200)}

function saveHero(){
  hero={year:v('f-heroYear'),tag1:v('f-heroTag1'),tag2:v('f-heroTag2'),sub:v('f-heroSub'),cta:v('f-heroCta')};
  persist('hero',hero);renderSite();flash('sc-hero');
}
function saveAbout(){
  about={title:v('f-aboutTitle'),p1:v('f-aboutP1'),p2:v('f-aboutP2'),chips:v('f-aboutChips')};
  persist('about',about);renderSite();flash('sc-about');
}
function applyProjectsTitle(){projectsTitle=v('f-projectsTitle');persist('projectsTitle',projectsTitle);document.getElementById('projectsTitle').textContent=projectsTitle;}
function applySkillsTitle(){skillsTitle=v('f-skillsTitle');persist('skillsTitle',skillsTitle);document.getElementById('skillsTitle').textContent=skillsTitle;}
function saveSkills(){
  skills=Array.from(document.querySelectorAll('.skill-row')).map(r=>{
    const ins=r.querySelectorAll('input');const sel=r.querySelector('select');
    return{icon:ins[0].value,name:ins[1].value,pct:parseInt(ins[2].value),color:sel.value};
  });
  persist('skills',skills);renderSite();flash('sc-skills');
}
function saveContact(){
  contact={title:v('f-contactTitle'),desc:v('f-contactDesc'),footer:v('f-footer')};
  persist('contact',contact);
  links=Array.from(document.querySelectorAll('.link-row')).map(r=>{
    const ins=r.querySelectorAll('input');return{icon:ins[0].value,label:ins[1].value,href:ins[2].value};
  });
  persist('links',links);renderSite();flash('sc-contact');
}
function v(id){return document.getElementById(id).value.trim()}

// ═══════════════════════════════════════════
// SKILL ROWS
// ═══════════════════════════════════════════
function renderSkillRows(){
  document.getElementById('skillRows').innerHTML=skills.map((s,i)=>skillRowHTML(s,i)).join('');
}
function skillRowHTML(s){
  return`<div class="skill-row">
    <input type="text" value="${s.icon}" placeholder="🎮" style="text-align:center;font-size:1.2rem">
    <input type="text" value="${s.name}" placeholder="Skill name">
    <div style="display:flex;flex-direction:column;align-items:center;gap:3px">
      <input type="range" min="0" max="100" value="${s.pct}" oninput="this.nextElementSibling.textContent=this.value+'%'" style="width:100%">
      <span class="pct">${s.pct}%</span>
    </div>
    <select>
      <option value="" ${s.color===''?'selected':''}>🟢 Green</option>
      <option value="bblue" ${s.color==='bblue'?'selected':''}>🔵 Blue</option>
      <option value="bpink" ${s.color==='bpink'?'selected':''}>🩷 Pink</option>
      <option value="borange" ${s.color==='borange'?'selected':''}>🟠 Orange</option>
    </select>
    <button class="del-row-btn" onclick="this.closest('.skill-row').remove()">✕</button>
  </div>`;
}
function addSkillRow(){
  const div=document.createElement('div');div.innerHTML=skillRowHTML({icon:'🎯',name:'',pct:50,color:''});
  document.getElementById('skillRows').appendChild(div.firstChild);
}

// ═══════════════════════════════════════════
// LINK ROWS
// ═══════════════════════════════════════════
function renderLinkRows(){
  document.getElementById('linkRows').innerHTML=links.map(l=>linkRowHTML(l)).join('');
}
function linkRowHTML(l){
  return`<div class="link-row">
    <input class="link-emoji-in" type="text" value="${l.icon}" placeholder="✉️" maxlength="4">
    <input type="text" value="${l.label}" placeholder="Label">
    <input type="text" value="${l.href}" placeholder="https://... or mailto:...">
    <button class="del-row-btn" onclick="this.closest('.link-row').remove()">✕</button>
  </div>`;
}
function addLinkRow(){
  const div=document.createElement('div');div.innerHTML=linkRowHTML({icon:'🔗',label:'',href:'#'});
  document.getElementById('linkRows').appendChild(div.firstChild);
}

// ═══════════════════════════════════════════
// PROJECT EDITOR
// ═══════════════════════════════════════════
function renderProjList(){
  document.getElementById('projList').innerHTML=projects.map((p,i)=>`
    <div class="proj-row" onclick="openProjForm(${i})">
      <span class="proj-row-emoji">${p.emoji||'🎮'}</span>
      <div class="proj-row-info">
        <div class="proj-row-name">${p.name}</div>
        <div class="proj-row-tags">${p.tags.join(' · ')}</div>
      </div>
      <button class="proj-row-edit" onclick="openProjForm(${i})">Edit</button>
    </div>`).join('');
}
function openProjForm(i){
  editProjIdx=i;
  const isNew=i===-1;
  document.getElementById('projFormTitle').textContent=isNew?'New Project':'Edit Project';
  document.getElementById('pf-delBtn').style.display=isNew?'none':'block';
  const p=isNew?{name:'',desc:'',emoji:'🎮',color:'tb',tags:[],images:[]}:projects[i];
  document.getElementById('pf-name').value=p.name;
  document.getElementById('pf-emoji').value=p.emoji||'';
  document.getElementById('pf-desc').value=p.desc;
  document.getElementById('pf-color').value=p.color||'tb';
  document.getElementById('pf-tags').value=(p.tags||[]).join(', ');
  document.getElementById('pf-imgList').innerHTML='';
  (p.images||[]).forEach(u=>addImgRow(u));
  if(!(p.images||[]).length)addImgRow();
  document.getElementById('projForm').classList.add('open');
  document.getElementById('projForm').scrollIntoView({behavior:'smooth',block:'nearest'});
}
function closeProjForm(){document.getElementById('projForm').classList.remove('open')}
function addImgRow(val=''){
  const r=document.createElement('div');r.className='iurow';
  r.innerHTML=`<input type="url" placeholder="https://i.imgur.com/example.jpg" value="${val}"><button class="rm-btn" onclick="this.parentElement.remove()">✕</button>`;
  document.getElementById('pf-imgList').appendChild(r);
}
function saveProj(){
  const name=document.getElementById('pf-name').value.trim();
  if(!name){alert('Please enter a project name!');return}
  const imgs=Array.from(document.querySelectorAll('#pf-imgList input')).map(i=>i.value.trim()).filter(Boolean);
  const p={name,desc:document.getElementById('pf-desc').value.trim(),emoji:document.getElementById('pf-emoji').value.trim()||'🎮',color:document.getElementById('pf-color').value,tags:document.getElementById('pf-tags').value.split(',').map(t=>t.trim()).filter(Boolean),images:imgs};
  if(editProjIdx===-1)projects.push(p);else projects[editProjIdx]=p;
  persist('projects',projects);closeProjForm();renderProjList();renderSite();
}
function deleteProj(){
  if(!confirm('Delete this project?'))return;
  projects.splice(editProjIdx,1);persist('projects',projects);closeProjForm();renderProjList();renderSite();
}

// ═══════════════════════════════════════════
// ADMIN TABS
// ═══════════════════════════════════════════
function showTab(name,btn){
  document.querySelectorAll('.ap-section').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.ap-nav-item').forEach(b=>b.classList.remove('active'));
  document.getElementById('tab-'+name).classList.add('active');
  btn.classList.add('active');
}

// ═══════════════════════════════════════════
// PASSWORD CHANGE
// ═══════════════════════════════════════════
function changePassword(){
  const cur=document.getElementById('s-curPw').value;
  const nw=document.getElementById('s-newPw').value;
  const cf=document.getElementById('s-confPw').value;
  const err=document.getElementById('pw-err');
  if(cur!==pw){err.textContent='Current password is wrong.';return}
  if(nw.length<6){err.textContent='New password must be at least 6 characters.';return}
  if(nw!==cf){err.textContent='Passwords do not match.';return}
  pw=nw;persist('password',pw);err.textContent='';
  document.getElementById('s-curPw').value='';document.getElementById('s-newPw').value='';document.getElementById('s-confPw').value='';
  flash('sc-pw');
}

// ═══════════════════════════════════════════
// RESET
// ═══════════════════════════════════════════
function resetAll(){
  if(!confirm('Reset ALL site content to defaults? This cannot be undone.'))return;
  ['password','hero','about','projectsTitle','projects','skillsTitle','skills','contact','links'].forEach(k=>localStorage.removeItem('pf_'+k));
  location.reload();
}

// ═══════════════════════════════════════════
// SKILL BAR OBSERVER
// ═══════════════════════════════════════════
const sObs=new IntersectionObserver(en=>{
  en.forEach(e=>{if(e.isIntersecting){document.querySelectorAll('[data-w]').forEach((b,i)=>setTimeout(()=>b.style.width=b.dataset.w,i*100));sObs.disconnect();}});
},{threshold:.3});
sObs.observe(document.getElementById('skills'));

// ═══════════════════════════════════════════
// INIT
// ═══════════════════════════════════════════
renderSite();
</script>
</body>
</html>
