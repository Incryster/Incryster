<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ABHILASH T.A ⚡ Cloud Engineer · AWS · DevOps</title>
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%23060a14'/%3E%3Ctext x='32' y='42' font-size='34' text-anchor='middle'%3E%E2%9A%A1%3C/text%3E%3C/svg%3E">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/orbitron@5/700.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/orbitron@5/900.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/rajdhani@5/600.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/rajdhani@5/700.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/space-grotesk@5/400.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/space-grotesk@5/500.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/space-grotesk@5/700.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/jetbrains-mono@5/400.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fontsource/jetbrains-mono@5/700.css">
<style>
:root{
  --bg0:#04060e; --bg1:#070c19; --surface:rgba(11,18,36,.72); --surface2:rgba(15,24,46,.85);
  --cyan:#00F5FF; --violet:#7B2FF7; --magenta:#FF00E5; --lime:#39FF14;
  --amber:#FFB020; --red:#FF3B5C; --info:#4DA6FF;
  --text:#E8F4FF; --muted:#8FA3C8; --line:rgba(0,245,255,.16);
  --font-display:'Orbitron',sans-serif; --font-hud:'Rajdhani',sans-serif;
  --font-body:'Space Grotesk',sans-serif; --font-mono:'JetBrains Mono',monospace;
  --nav-h:72px;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
html,body{overflow-x:hidden}
body{background:var(--bg0);color:var(--text);font-family:var(--font-body);font-size:16px;line-height:1.6;-webkit-font-smoothing:antialiased}
::selection{background:var(--cyan);color:#041018}
::-webkit-scrollbar{width:10px;height:8px}
::-webkit-scrollbar-track{background:#060a14}
::-webkit-scrollbar-thumb{background:linear-gradient(180deg,var(--cyan),var(--violet));border-radius:6px;border:2px solid #060a14}
::-webkit-scrollbar-thumb:hover{background:linear-gradient(180deg,#7ffbff,var(--magenta))}
*{scrollbar-width:thin;scrollbar-color:#00b8c4 #060a14}
a{color:var(--cyan);text-decoration:none}
button{font-family:inherit;cursor:pointer}
img{max-width:100%}
:focus-visible{outline:2px solid var(--cyan);outline-offset:3px;border-radius:4px}
.skip-link{position:fixed;top:-60px;left:16px;z-index:2000;background:var(--cyan);color:#041018;padding:10px 16px;font-weight:700;border-radius:6px;transition:top .2s}
.skip-link:focus{top:12px}

/* ---------- ATMOSPHERE ---------- */
.aurora{position:fixed;inset:0;z-index:-2;overflow:hidden;pointer-events:none}
.aurora i{position:absolute;border-radius:50%;filter:blur(90px);opacity:.5;will-change:transform}
.aurora i:nth-child(1){width:52vw;height:52vw;left:-14vw;top:-18vw;background:radial-gradient(circle,rgba(0,245,255,.22),transparent 65%);animation:drift1 26s ease-in-out infinite alternate}
.aurora i:nth-child(2){width:46vw;height:46vw;right:-12vw;top:16vh;background:radial-gradient(circle,rgba(123,47,247,.26),transparent 65%);animation:drift2 31s ease-in-out infinite alternate}
.aurora i:nth-child(3){width:40vw;height:40vw;left:22vw;bottom:-20vh;background:radial-gradient(circle,rgba(255,0,229,.14),transparent 65%);animation:drift3 37s ease-in-out infinite alternate}
@keyframes drift1{to{transform:translate(10vw,10vh) scale(1.15)}}
@keyframes drift2{to{transform:translate(-9vw,-8vh) scale(1.2) rotate(20deg)}}
@keyframes drift3{to{transform:translate(-12vw,-10vh) scale(1.1)}}
.grain{position:fixed;inset:-50%;z-index:1200;pointer-events:none;opacity:.05;mix-blend-mode:overlay;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='160' height='160'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2'/%3E%3C/filter%3E%3Crect width='160' height='160' filter='url(%23n)' opacity='0.6'/%3E%3C/svg%3E");animation:grainShift 1.2s steps(4) infinite}
@keyframes grainShift{0%{transform:translate(0,0)}25%{transform:translate(-2%,1%)}50%{transform:translate(1%,-2%)}75%{transform:translate(-1%,2%)}100%{transform:translate(0,0)}}
#cursorGlow{position:fixed;left:0;top:0;width:340px;height:340px;margin:-170px 0 0 -170px;border-radius:50%;pointer-events:none;z-index:1;background:radial-gradient(circle,rgba(0,245,255,.09),rgba(123,47,247,.05) 45%,transparent 70%);mix-blend-mode:screen;display:none}
#progressBar{position:fixed;top:0;left:0;height:3px;width:0;z-index:1500;background:linear-gradient(90deg,var(--cyan),var(--violet),var(--magenta));box-shadow:0 0 12px rgba(0,245,255,.7)}

/* ---------- BOOT ---------- */
#bootOverlay{position:fixed;inset:0;z-index:3000;background:var(--bg0);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:22px;cursor:pointer;transition:opacity .55s ease,visibility .55s}
#bootOverlay.done{opacity:0;visibility:hidden}
.boot-logo{font-family:var(--font-display);font-weight:900;font-size:clamp(26px,5vw,44px);letter-spacing:.14em;background:linear-gradient(90deg,var(--cyan),var(--violet),var(--magenta));-webkit-background-clip:text;background-clip:text;color:transparent}
.boot-bar{width:min(340px,72vw);height:4px;background:#0c1428;border-radius:4px;overflow:hidden;border:1px solid var(--line)}
.boot-bar i{display:block;height:100%;width:0;background:linear-gradient(90deg,var(--cyan),var(--magenta));animation:bootFill 1.55s cubic-bezier(.3,.8,.4,1) forwards;box-shadow:0 0 14px var(--cyan)}
@keyframes bootFill{to{width:100%}}
#bootLine{font-family:var(--font-mono);font-size:12px;color:var(--muted);letter-spacing:.08em;min-height:18px}
.boot-skip{font-family:var(--font-hud);font-size:11px;letter-spacing:.3em;color:#3d557e}

/* ---------- NAV ---------- */
#navbar{position:fixed;top:0;left:0;right:0;height:var(--nav-h);z-index:1400;display:flex;align-items:center;transition:background .3s,border-color .3s,backdrop-filter .3s;border-bottom:1px solid transparent}
#navbar.scrolled{background:rgba(4,7,15,.82);backdrop-filter:blur(14px);border-bottom-color:var(--line)}
.nav-inner{width:min(1220px,100% - 40px);margin:0 auto;display:flex;align-items:center;gap:20px}
.nav-logo{font-family:var(--font-display);font-weight:700;font-size:15px;letter-spacing:.1em;color:var(--text);display:flex;align-items:center;gap:10px;white-space:nowrap}
.nav-logo b{color:var(--cyan);text-shadow:0 0 12px rgba(0,245,255,.8)}
.nav-logo .logo-glyph{width:30px;height:30px;display:grid;place-items:center;border:1px solid var(--line);border-radius:8px;background:linear-gradient(135deg,rgba(0,245,255,.14),rgba(123,47,247,.14));font-size:15px}
.nav-links{display:flex;gap:4px;margin-left:auto}
.nav-link{font-family:var(--font-hud);font-weight:700;font-size:13px;letter-spacing:.18em;color:var(--muted);padding:9px 12px;border-radius:8px;position:relative;transition:color .2s,background .2s}
.nav-link:hover{color:var(--text);background:rgba(0,245,255,.06)}
.nav-link.active{color:var(--cyan)}
.nav-link.active::after{content:'';position:absolute;left:12px;right:12px;bottom:3px;height:2px;background:linear-gradient(90deg,var(--cyan),var(--violet));box-shadow:0 0 8px var(--cyan);border-radius:2px}
.nav-actions{display:flex;align-items:center;gap:10px}
#soundBtn{display:flex;align-items:center;gap:7px;background:rgba(0,245,255,.06);border:1px solid var(--line);color:var(--cyan);font-family:var(--font-hud);font-weight:700;font-size:11px;letter-spacing:.16em;padding:8px 12px;border-radius:8px;transition:.2s}
#soundBtn:hover{background:rgba(0,245,255,.14);box-shadow:0 0 14px rgba(0,245,255,.25)}
#soundBtn.muted{color:var(--muted);border-color:rgba(143,163,200,.25)}
#navMenuBtn{display:none;background:none;border:1px solid var(--line);border-radius:8px;width:40px;height:40px;color:var(--cyan);font-size:18px}
#mobileMenu{position:fixed;top:var(--nav-h);left:0;right:0;z-index:1390;background:rgba(4,7,15,.96);backdrop-filter:blur(16px);border-bottom:1px solid var(--line);padding:14px 20px 22px;display:none;flex-direction:column;gap:4px;transform:translateY(-8px);opacity:0;transition:.25s}
#mobileMenu.open{display:flex;transform:none;opacity:1}
#mobileMenu .nav-link{font-size:15px;padding:12px}

/* ---------- BUTTONS / SHARED ---------- */
.btn{display:inline-flex;align-items:center;gap:9px;font-family:var(--font-hud);font-weight:700;letter-spacing:.14em;font-size:14px;padding:13px 22px;border-radius:10px;border:1px solid transparent;transition:transform .18s,box-shadow .25s,background .25s,color .2s;position:relative;white-space:nowrap}
.btn:active{transform:scale(.96)}
.btn-primary{background:linear-gradient(100deg,var(--cyan),#4dc3ff 55%,var(--violet));color:#041018;box-shadow:0 0 22px rgba(0,245,255,.35),0 6px 22px rgba(123,47,247,.25)}
.btn-primary:hover{transform:translateY(-2px);box-shadow:0 0 34px rgba(0,245,255,.55),0 10px 30px rgba(123,47,247,.4)}
.btn-ghost{background:rgba(0,245,255,.05);border-color:rgba(0,245,255,.4);color:var(--cyan)}
.btn-ghost:hover{background:rgba(0,245,255,.13);box-shadow:0 0 18px rgba(0,245,255,.3);transform:translateY(-2px)}
.btn-magenta{background:rgba(255,0,229,.07);border-color:rgba(255,0,229,.45);color:#ff7bf2}
.btn-magenta:hover{background:rgba(255,0,229,.16);box-shadow:0 0 18px rgba(255,0,229,.35);transform:translateY(-2px)}
.btn-sm{padding:9px 16px;font-size:12px}
.btn[disabled]{opacity:.55;cursor:wait;transform:none!important}
.container{width:min(1220px,100% - 40px);margin:0 auto}
section{padding:110px 0;scroll-margin-top:calc(var(--nav-h) + 16px);position:relative}
.sec-head{margin-bottom:52px}
.sec-index{font-family:var(--font-mono);font-size:12px;letter-spacing:.3em;color:var(--magenta);display:flex;align-items:center;gap:14px;margin-bottom:14px}
.sec-index::after{content:'';flex:0 0 90px;height:1px;background:linear-gradient(90deg,var(--magenta),transparent)}
.sec-title{font-family:var(--font-display);font-weight:900;font-size:clamp(26px,4.2vw,42px);letter-spacing:.05em;line-height:1.15}
.sec-title .grad{background:linear-gradient(92deg,var(--cyan) 10%,var(--violet) 55%,var(--magenta));-webkit-background-clip:text;background-clip:text;color:transparent}
.sec-sub{color:var(--muted);margin-top:12px;max-width:640px;font-size:15.5px}
.panel{background:var(--surface);border:1px solid var(--line);border-radius:14px;position:relative;backdrop-filter:blur(8px)}
.panel::before,.panel::after{content:'';position:absolute;width:14px;height:14px;pointer-events:none}
.panel::before{top:-1px;left:-1px;border-top:2px solid var(--cyan);border-left:2px solid var(--cyan);border-top-left-radius:14px}
.panel::after{bottom:-1px;right:-1px;border-bottom:2px solid var(--violet);border-right:2px solid var(--violet);border-bottom-right-radius:14px}
.reveal{opacity:0;transform:translateY(30px);transition:opacity .8s cubic-bezier(.2,.7,.2,1),transform .8s cubic-bezier(.2,.7,.2,1)}
.reveal.in{opacity:1;transform:none}
.led{width:8px;height:8px;border-radius:50%;background:var(--lime);box-shadow:0 0 10px var(--lime);display:inline-block;animation:ledPulse 1.8s ease-in-out infinite}
@keyframes ledPulse{50%{opacity:.35;box-shadow:0 0 3px var(--lime)}}
.chip{display:inline-flex;align-items:center;gap:6px;font-family:var(--font-mono);font-size:11px;padding:5px 10px;border-radius:6px;border:1px solid;letter-spacing:.04em}

/* ---------- HERO ---------- */
.hero{min-height:100vh;display:flex;align-items:center;padding:calc(var(--nav-h) + 60px) 0 90px;position:relative;overflow:hidden}
#heroCanvas{position:absolute;inset:0;z-index:0;pointer-events:none}
.hero::before{content:'';position:absolute;left:-20%;right:-20%;bottom:-6%;height:52%;z-index:0;background-image:linear-gradient(rgba(0,245,255,.14) 1px,transparent 1px),linear-gradient(90deg,rgba(0,245,255,.14) 1px,transparent 1px);background-size:46px 46px;transform:perspective(620px) rotateX(63deg);transform-origin:bottom;-webkit-mask-image:linear-gradient(to top,#000 20%,transparent 85%);mask-image:linear-gradient(to top,#000 20%,transparent 85%);animation:gridScroll 12s linear infinite;opacity:.5;pointer-events:none}
@keyframes gridScroll{to{background-position-y:46px}}
.hero-grid{position:relative;z-index:2;display:grid;grid-template-columns:1.08fr .92fr;gap:56px;align-items:center;width:100%}
.hero [data-stage]{opacity:0;transform:translateY(26px);transition:opacity .9s cubic-bezier(.2,.7,.2,1),transform .9s cubic-bezier(.2,.7,.2,1);transition-delay:var(--d,0s)}
body.ready .hero [data-stage]{opacity:1;transform:none}
.status-chip{display:inline-flex;align-items:center;gap:9px;font-family:var(--font-hud);font-weight:700;font-size:12px;letter-spacing:.26em;color:var(--lime);border:1px solid rgba(57,255,20,.4);background:rgba(57,255,20,.06);padding:8px 16px;border-radius:100px;margin-bottom:24px}
.hero-kicker{font-family:var(--font-mono);color:var(--muted);font-size:13px;letter-spacing:.14em;margin-bottom:10px}
.hero-kicker b{color:var(--cyan)}
.hero-name{font-family:var(--font-display);font-weight:900;font-size:clamp(38px,6.4vw,74px);letter-spacing:.03em;line-height:1.04;position:relative;background:linear-gradient(92deg,#fff 15%,var(--cyan) 55%,var(--violet) 90%);-webkit-background-clip:text;background-clip:text;color:transparent;filter:drop-shadow(0 0 26px rgba(0,245,255,.25))}
.glitch{position:relative;display:inline-block}
.glitch::before,.glitch::after{content:attr(data-text);position:absolute;inset:0;background:none;-webkit-text-fill-color:initial;color:var(--cyan);opacity:0;pointer-events:none;mix-blend-mode:screen}
.glitch::after{color:var(--magenta)}
body.ready .glitch::before{animation:glitchA 5s steps(1) 2.2s infinite}
body.ready .glitch::after{animation:glitchB 5s steps(1) 2.2s infinite}
@keyframes glitchA{0%,93%{opacity:0}94%{opacity:.8;transform:translate(-4px,2px);clip-path:inset(10% 0 55% 0)}96%{opacity:.8;transform:translate(3px,-2px);clip-path:inset(60% 0 8% 0)}98%,100%{opacity:0}}
@keyframes glitchB{0%,94%{opacity:0}95%{opacity:.8;transform:translate(4px,-1px);clip-path:inset(40% 0 30% 0)}97%{opacity:.8;transform:translate(-3px,2px);clip-path:inset(5% 0 78% 0)}99%,100%{opacity:0}}
.hero-role{font-family:var(--font-hud);font-weight:700;font-size:clamp(15px,2vw,20px);letter-spacing:.34em;color:var(--text);margin:16px 0 20px;display:flex;align-items:center;gap:14px;flex-wrap:wrap}
.hero-role .sep{color:var(--magenta)}
.type-wrap{font-family:var(--font-mono);font-size:clamp(13px,1.6vw,16px);color:var(--cyan);min-height:28px;margin-bottom:26px}
.type-wrap .prompt-sym{color:var(--magenta);margin-right:8px}
.caret{display:inline-block;width:9px;height:1.05em;background:var(--cyan);vertical-align:text-bottom;margin-left:3px;box-shadow:0 0 8px var(--cyan);animation:caretBlink 1s steps(1) infinite}
@keyframes caretBlink{50%{opacity:0}}
.hero-badges{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:30px}
.badge{font-family:var(--font-hud);font-weight:700;font-size:11.5px;letter-spacing:.14em;padding:8px 14px;border-radius:8px;border:1px solid;display:inline-flex;align-items:center;gap:8px;background:rgba(6,10,20,.6)}
.badge.b-cyan{color:var(--cyan);border-color:rgba(0,245,255,.4)}
.badge.b-violet{color:#b78bff;border-color:rgba(123,47,247,.5)}
.badge.b-magenta{color:#ff7bf2;border-color:rgba(255,0,229,.4)}
.hero-ctas{display:flex;flex-wrap:wrap;gap:14px;margin-bottom:38px}
.hero-stats{display:grid;grid-template-columns:repeat(4,auto);gap:0;border:1px solid var(--line);border-radius:12px;overflow:hidden;background:rgba(6,10,20,.55);width:fit-content}
.stat{padding:14px 22px;border-right:1px solid var(--line)}
.stat:last-child{border-right:0}
.stat b{display:block;font-family:var(--font-display);font-weight:700;font-size:21px;color:var(--cyan);text-shadow:0 0 14px rgba(0,245,255,.5)}
.stat span{font-family:var(--font-hud);font-weight:600;font-size:10px;letter-spacing:.2em;color:var(--muted)}
.scroll-cue{position:absolute;bottom:26px;left:50%;transform:translateX(-50%);z-index:2;font-family:var(--font-hud);font-weight:600;font-size:10px;letter-spacing:.4em;color:var(--muted);display:flex;flex-direction:column;align-items:center;gap:8px}
.scroll-cue i{width:1px;height:34px;background:linear-gradient(180deg,var(--cyan),transparent);animation:cueDrop 1.8s ease-in-out infinite}
@keyframes cueDrop{0%{transform:scaleY(0);transform-origin:top}45%{transform:scaleY(1);transform-origin:top}55%{transform:scaleY(1);transform-origin:bottom}100%{transform:scaleY(0);transform-origin:bottom}}

/* hologram console */
.console{padding:22px 22px 18px;overflow:hidden}
.console-head{display:flex;align-items:center;gap:10px;font-family:var(--font-hud);font-weight:700;font-size:11px;letter-spacing:.24em;color:var(--muted);padding-bottom:14px;border-bottom:1px solid var(--line)}
.console-head .region{margin-left:auto;color:var(--cyan);font-family:var(--font-mono);font-size:11px;letter-spacing:.05em}
.holo{position:relative;height:300px;display:grid;place-items:center;perspective:800px;margin:8px 0}
.holo-core{width:118px;height:118px;border-radius:50%;display:grid;place-items:center;background:radial-gradient(circle at 34% 30%,rgba(0,245,255,.5),rgba(123,47,247,.32) 55%,rgba(4,6,14,.9) 78%);box-shadow:0 0 44px rgba(0,245,255,.4),inset 0 0 30px rgba(0,245,255,.3);border:1px solid rgba(0,245,255,.55);animation:corePulse 3.4s ease-in-out infinite;position:relative;z-index:3}
@keyframes corePulse{50%{box-shadow:0 0 70px rgba(123,47,247,.55),inset 0 0 40px rgba(0,245,255,.45)}}
.holo-core .mono{font-family:var(--font-display);font-weight:900;font-size:32px;color:#fff;text-shadow:0 0 18px var(--cyan)}
.holo-core small{position:absolute;bottom:20px;font-family:var(--font-hud);font-weight:600;font-size:8px;letter-spacing:.3em;color:var(--cyan)}
.ring{position:absolute;border-radius:50%;border:1px solid rgba(0,245,255,.3);pointer-events:none}
.ring.r1{width:190px;height:190px;border-color:rgba(0,245,255,.4);border-style:dashed;animation:spinZ 22s linear infinite}
.ring.r2{width:252px;height:252px;border-color:rgba(123,47,247,.45);transform:rotateX(64deg);animation:spinX 14s linear infinite}
.ring.r3{width:284px;height:284px;border-color:rgba(255,0,229,.28);transform:rotateX(64deg) rotateY(18deg);animation:spinX2 20s linear infinite reverse}
@keyframes spinZ{to{transform:rotate(360deg)}}
@keyframes spinX{from{transform:rotateX(64deg) rotateZ(0)}to{transform:rotateX(64deg) rotateZ(360deg)}}
@keyframes spinX2{from{transform:rotateX(64deg) rotateY(18deg) rotateZ(0)}to{transform:rotateX(64deg) rotateY(18deg) rotateZ(360deg)}}
.orbit{position:absolute;width:0;height:0;animation:spinZ 20s linear infinite}
.orbit.rev{animation:spinZrev 28s linear infinite}
@keyframes spinZrev{to{transform:rotate(-360deg)}}
.orbit .sat{position:absolute;transform:translate(-50%,-50%)}
.orbit .sat span{display:inline-block;font-family:var(--font-mono);font-size:10px;padding:4px 9px;border-radius:6px;background:rgba(6,12,26,.9);border:1px solid rgba(0,245,255,.4);color:var(--cyan);box-shadow:0 0 10px rgba(0,245,255,.2);animation:spinZrev 20s linear infinite;white-space:nowrap}
.orbit.rev .sat span{animation:spinZ 28s linear infinite;border-color:rgba(255,0,229,.4);color:#ff8df3;box-shadow:0 0 10px rgba(255,0,229,.2)}
.telemetry{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:6px}
.tele{border:1px solid var(--line);border-radius:10px;padding:10px 12px;background:rgba(6,10,20,.5)}
.tele span{display:block;font-family:var(--font-hud);font-weight:600;font-size:9px;letter-spacing:.24em;color:var(--muted)}
.tele b{font-family:var(--font-mono);font-size:14px;color:var(--text)}
.tele b.ok{color:var(--lime)}
.equalizer{display:flex;align-items:flex-end;gap:4px;height:26px;margin-top:14px;padding:0 2px}
.equalizer i{flex:1;background:linear-gradient(180deg,var(--cyan),var(--violet));border-radius:2px;animation:eq 1s ease-in-out infinite alternate;opacity:.8}
@keyframes eq{from{height:18%}to{height:100%}}

/* ---------- MARQUEE ---------- */
.marquee{border-top:1px solid var(--line);border-bottom:1px solid var(--line);background:rgba(6,10,20,.6);overflow:hidden;padding:15px 0;position:relative}
.marquee-track{display:flex;gap:0;width:max-content;animation:marquee 30s linear infinite}
.marquee:hover .marquee-track{animation-play-state:paused}
@keyframes marquee{to{transform:translateX(-50%)}}
.marquee-set{display:flex;align-items:center;flex-shrink:0}
.marquee-set span{font-family:var(--font-display);font-weight:700;font-size:13px;letter-spacing:.24em;color:var(--muted);padding:0 22px;white-space:nowrap}
.marquee-set i{color:var(--magenta);font-style:normal;text-shadow:0 0 8px var(--magenta)}
.marquee-set span:nth-child(4n+1){color:var(--cyan)}
.marquee-set span:nth-child(4n+3){color:#b78bff}

/* ---------- TERMINAL ---------- */
.terminal{overflow:hidden;background:#050910!important}
.term-head{display:flex;align-items:center;gap:8px;padding:13px 18px;border-bottom:1px solid var(--line);background:rgba(10,17,32,.9)}
.term-dot{width:11px;height:11px;border-radius:50%}
.term-dot.r{background:var(--red)}.term-dot.a{background:var(--amber)}.term-dot.g{background:var(--lime)}
.term-title{font-family:var(--font-mono);font-size:12px;color:var(--muted);margin-left:10px}
#termClock{margin-left:auto;font-family:var(--font-mono);font-size:11px;color:var(--cyan)}
.term-screen{position:relative;padding:20px 20px 16px;font-family:var(--font-mono);font-size:13.5px;line-height:1.75}
.term-screen::after{content:'';position:absolute;inset:0;pointer-events:none;background:repeating-linear-gradient(0deg,rgba(0,245,255,.022) 0 1px,transparent 1px 3px);border-radius:0 0 14px 14px}
#termBody{max-height:360px;overflow-y:auto;padding-right:8px}
#termBody::-webkit-scrollbar{width:6px}
.t-line{white-space:pre-wrap;word-break:break-word;color:#c9dcf5}
.t-prompt{color:var(--lime);font-weight:700}
.t-cmd{color:#fff}
.t-out{color:#c9dcf5}
.t-accent{color:var(--cyan)}
.t-ok{color:var(--lime)}
.t-err{color:var(--red)}
.t-dim{color:#5f7396}
.t-magenta{color:#ff8df3}
.t-line a{color:var(--cyan);text-decoration:underline;text-underline-offset:3px}
.term-input-row{display:flex;align-items:center;gap:8px;margin-top:6px}
#termInput{flex:1;background:none;border:none;outline:none;color:#fff;font-family:var(--font-mono);font-size:13.5px;caret-color:var(--cyan)}
.term-hint{font-family:var(--font-hud);font-weight:600;font-size:11px;letter-spacing:.2em;color:#44608f;padding:10px 20px 16px;border-top:1px dashed rgba(0,245,255,.1)}
.term-hint b{color:var(--cyan)}

/* ---------- STACK ---------- */
.stack-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(104px,1fr));gap:14px;margin-bottom:60px}
.t-tile{position:relative;border:1px solid var(--line);border-radius:12px;background:var(--surface);padding:18px 8px 13px;display:flex;flex-direction:column;align-items:center;gap:9px;transition:transform .25s,border-color .25s,box-shadow .25s;overflow:hidden}
.t-tile::before{content:'';position:absolute;inset:0;background:radial-gradient(120px at 50% 0%,var(--tile-c,rgba(0,245,255,.16)),transparent 70%);opacity:0;transition:opacity .3s}
.t-tile:hover{transform:translateY(-6px);border-color:var(--tile-b,rgba(0,245,255,.5));box-shadow:0 12px 30px rgba(0,0,0,.5),0 0 20px var(--tile-g,rgba(0,245,255,.18))}
.t-tile:hover::before{opacity:1}
.t-icon{position:relative;width:46px;height:46px;display:grid;place-items:center}
.t-icon img{width:44px;height:44px;object-fit:contain;position:relative;z-index:1;filter:drop-shadow(0 4px 10px rgba(0,0,0,.5))}
.t-icon img.inv{filter:invert(1) brightness(1.7) drop-shadow(0 0 8px rgba(0,245,255,.3))}
.t-fallback{position:absolute;inset:0;display:grid;place-items:center;font-family:var(--font-display);font-weight:700;font-size:13px;color:var(--cyan)}
.t-name{font-family:var(--font-hud);font-weight:700;font-size:12px;letter-spacing:.1em;color:var(--text)}
.t-cat{font-family:var(--font-mono);font-size:8.5px;letter-spacing:.18em;color:var(--muted)}
.domain-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:16px}
.domain{padding:22px;border-radius:14px;border:1px solid var(--line);background:var(--surface);transition:transform .25s,border-color .25s,box-shadow .25s;position:relative;overflow:hidden}
.domain:hover{transform:translateY(-4px);border-color:var(--dc);box-shadow:0 0 24px color-mix(in srgb,var(--dc) 22%,transparent)}
.domain::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,var(--dc),transparent)}
.domain-head{display:flex;align-items:center;gap:12px;margin-bottom:14px}
.domain-ico{width:38px;height:38px;border-radius:9px;display:grid;place-items:center;font-size:18px;background:color-mix(in srgb,var(--dc) 12%,transparent);border:1px solid color-mix(in srgb,var(--dc) 45%,transparent)}
.domain-head h3{font-family:var(--font-display);font-weight:700;font-size:14px;letter-spacing:.1em;color:var(--text)}
.domain-count{margin-left:auto;font-family:var(--font-mono);font-size:10px;color:var(--dc);border:1px solid color-mix(in srgb,var(--dc) 45%,transparent);padding:3px 8px;border-radius:20px}
.domain-chips{display:flex;flex-wrap:wrap;gap:7px}
.domain-chips .chip{color:#cfe2ff;border-color:rgba(143,163,200,.25);background:rgba(6,10,20,.5);transition:.2s}
.domain:hover .domain-chips .chip{border-color:color-mix(in srgb,var(--dc) 40%,transparent)}
.domain-chips .chip:hover{color:var(--dc);border-color:var(--dc);box-shadow:0 0 10px color-mix(in srgb,var(--dc) 30%,transparent)}

/* ---------- ARCHITECTURE ---------- */
.arch-layout{display:grid;grid-template-columns:1fr 330px;gap:20px;align-items:start}
.diagram-panel{padding:18px}
.diagram-toolbar{display:flex;flex-wrap:wrap;gap:9px;align-items:center;margin-bottom:14px}
.chip-toggle{position:relative;cursor:pointer}
.chip-toggle input{position:absolute;opacity:0;inset:0;cursor:pointer}
.chip-ui{display:inline-flex;align-items:center;gap:8px;font-family:var(--font-hud);font-weight:700;font-size:11px;letter-spacing:.16em;padding:8px 13px;border-radius:100px;border:1px solid var(--c);color:var(--c);background:color-mix(in srgb,var(--c) 8%,transparent);transition:.2s;user-select:none}
.chip-ui .dot{width:7px;height:7px;border-radius:50%;background:var(--c);box-shadow:0 0 8px var(--c)}
.chip-toggle input:not(:checked)+.chip-ui{opacity:.4;border-style:dashed;background:transparent}
.chip-toggle input:not(:checked)+.chip-ui .dot{box-shadow:none;opacity:.5}
.chip-toggle input:focus-visible+.chip-ui{outline:2px solid var(--cyan);outline-offset:2px}
.chip-toggle:hover .chip-ui{box-shadow:0 0 14px color-mix(in srgb,var(--c) 35%,transparent)}
#traceBtn{margin-left:auto}
.diagram-scroll{overflow-x:auto;border-radius:10px}
.diagram-scroll::-webkit-scrollbar{height:7px}
#vpcSvg{width:100%;min-width:660px;height:auto;display:block}
.flow path{fill:none;stroke-width:2}
#flow-in path{stroke:var(--cyan)}
#flow-ssh path{stroke:var(--magenta)}
#flow-up path{stroke:var(--lime);stroke-dasharray:7 7;animation:dashMove 1.1s linear infinite}
#flow-out path{stroke:var(--amber)}
@keyframes dashMove{to{stroke-dashoffset:-14}}
.flow-label{font-family:var(--font-mono);font-size:10px;letter-spacing:.08em}
.node{cursor:pointer}
.node .n-box{fill:rgba(10,19,38,.92);stroke:rgba(0,245,255,.4);stroke-width:1.4;transition:.25s;rx:10}
.node:hover .n-box,.node.active .n-box{stroke:var(--cyan);filter:drop-shadow(0 0 8px rgba(0,245,255,.7))}
.node.trace .n-box{stroke:#fff;stroke-width:2.4;filter:drop-shadow(0 0 14px rgba(0,245,255,1))}
.node text{pointer-events:none}
.n-title{font-family:var(--font-hud);font-weight:700;font-size:14px;fill:#EAF6FF;letter-spacing:.06em}
.n-sub{font-family:var(--font-mono);font-size:9.5px;fill:#8FA3C8}
.zone{fill:rgba(0,245,255,.03);stroke:rgba(0,245,255,.25);stroke-dasharray:5 5}
.zone-label{font-family:var(--font-hud);font-weight:700;font-size:12px;letter-spacing:.22em;fill:var(--cyan)}
.zone-label.violet{fill:#b78bff}
.trace-packet{fill:#fff;filter:drop-shadow(0 0 8px var(--cyan))}
.arch-side{display:flex;flex-direction:column;gap:16px}
.info-panel{padding:20px}
.info-tag{font-family:var(--font-mono);font-size:10px;letter-spacing:.24em;color:var(--magenta);margin-bottom:8px}
#infoTitle{font-family:var(--font-display);font-weight:700;font-size:16px;letter-spacing:.06em;color:var(--cyan);margin-bottom:10px}
#infoBody{font-size:13.5px;color:#c4d6f2;line-height:1.65}
.info-hint{margin-top:14px;padding-top:12px;border-top:1px dashed rgba(0,245,255,.12);font-family:var(--font-hud);font-weight:600;font-size:10px;letter-spacing:.2em;color:#44608f}
.log-panel{padding:16px 18px}
.log-head{font-family:var(--font-hud);font-weight:700;font-size:11px;letter-spacing:.24em;color:var(--muted);margin-bottom:10px;display:flex;align-items:center;gap:8px}
#traceLog{font-family:var(--font-mono);font-size:11.5px;line-height:1.8;max-height:150px;overflow-y:auto;color:#9fe8ff}
#traceLog::-webkit-scrollbar{width:5px}
#traceLog .tl-ok{color:var(--lime)}
#traceLog .tl-dim{color:#44608f}

/* ---------- PROJECTS ---------- */
.proj-grid{display:grid;grid-template-columns:repeat(6,1fr);gap:18px}
.proj-card{grid-column:span 3;padding:26px;cursor:pointer;transition:border-color .3s,box-shadow .3s;transform-style:preserve-3d;will-change:transform;position:relative;overflow:hidden}
.proj-card.wide{grid-column:span 6}
.proj-card::after{content:'';position:absolute;inset:0;background:radial-gradient(280px at var(--mx,50%) var(--my,50%),color-mix(in srgb,var(--pc) 13%,transparent),transparent 65%);opacity:0;transition:opacity .3s;pointer-events:none}
.proj-card:hover::after{opacity:1}
.proj-card:hover{border-color:color-mix(in srgb,var(--pc) 55%,transparent);box-shadow:0 18px 44px rgba(0,0,0,.55),0 0 26px color-mix(in srgb,var(--pc) 20%,transparent)}
.proj-top{display:flex;align-items:center;gap:12px;margin-bottom:16px}
.proj-index{font-family:var(--font-mono);font-size:11px;color:var(--muted);letter-spacing:.2em}
.proj-status{margin-left:auto;display:inline-flex;align-items:center;gap:7px;font-family:var(--font-hud);font-weight:700;font-size:10px;letter-spacing:.22em;color:var(--pc)}
.proj-status i{width:7px;height:7px;border-radius:50%;background:var(--pc);box-shadow:0 0 9px var(--pc);animation:ledPulse 2s infinite}
.proj-ico{width:46px;height:46px;border-radius:11px;display:grid;place-items:center;font-size:22px;background:color-mix(in srgb,var(--pc) 12%,transparent);border:1px solid color-mix(in srgb,var(--pc) 45%,transparent);box-shadow:0 0 16px color-mix(in srgb,var(--pc) 18%,transparent)}
.proj-card h3{font-family:var(--font-display);font-weight:700;font-size:17px;letter-spacing:.04em;margin-bottom:10px;color:var(--text)}
.proj-card p{font-size:14px;color:var(--muted);margin-bottom:18px;line-height:1.65}
.proj-tags{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:18px}
.proj-tags .chip{color:var(--pc);border-color:color-mix(in srgb,var(--pc) 40%,transparent);background:color-mix(in srgb,var(--pc) 6%,transparent)}
.proj-open{font-family:var(--font-hud);font-weight:700;font-size:12px;letter-spacing:.2em;color:var(--pc);background:none;border:none;display:inline-flex;align-items:center;gap:8px;padding:0;transition:gap .2s}
.proj-card:hover .proj-open{gap:14px}
.proj-card.wide .wide-inner{display:grid;grid-template-columns:auto 1fr auto;gap:24px;align-items:center}
.proj-card.wide p{margin-bottom:0}
.proj-card.wide .proj-tags{margin:12px 0 0}

/* modal */
#modalOverlay{position:fixed;inset:0;z-index:2000;background:rgba(2,4,10,.8);backdrop-filter:blur(8px);display:grid;place-items:center;padding:20px;opacity:0;visibility:hidden;transition:.3s}
#modalOverlay.open{opacity:1;visibility:visible}
#modalCard{width:min(680px,100%);max-height:86vh;overflow-y:auto;padding:32px;transform:translateY(24px) scale(.97);transition:.35s cubic-bezier(.2,.8,.25,1);background:var(--surface2)!important}
#modalOverlay.open #modalCard{transform:none}
#modalCard::-webkit-scrollbar{width:7px}
.modal-top{display:flex;align-items:flex-start;gap:14px;margin-bottom:6px}
#modalIndex{font-family:var(--font-mono);font-size:11px;letter-spacing:.24em;color:var(--muted)}
#modalClose{margin-left:auto;background:rgba(255,59,92,.08);border:1px solid rgba(255,59,92,.4);color:var(--red);width:36px;height:36px;border-radius:9px;font-size:15px;transition:.2s;flex-shrink:0}
#modalClose:hover{background:rgba(255,59,92,.2);box-shadow:0 0 14px rgba(255,59,92,.4)}
#modalTitle{font-family:var(--font-display);font-weight:900;font-size:clamp(19px,3vw,25px);letter-spacing:.03em;margin:8px 0 4px;background:linear-gradient(90deg,#fff,var(--mc,var(--cyan)));-webkit-background-clip:text;background-clip:text;color:transparent}
#modalStatus{font-family:var(--font-hud);font-weight:700;font-size:11px;letter-spacing:.24em;color:var(--mc,var(--cyan));display:inline-flex;align-items:center;gap:8px;margin-bottom:16px}
#modalDesc{color:#c4d6f2;font-size:14.5px;margin-bottom:20px}
.modal-sec{font-family:var(--font-hud);font-weight:700;font-size:11px;letter-spacing:.28em;color:var(--muted);margin:20px 0 10px}
#modalList{list-style:none}
#modalList li{padding:7px 0 7px 24px;position:relative;font-size:13.5px;color:#c4d6f2;border-bottom:1px dashed rgba(0,245,255,.08)}
#modalList li::before{content:'▸';position:absolute;left:4px;color:var(--mc,var(--cyan))}
#modalChips{display:flex;flex-wrap:wrap;gap:8px}
#modalChips .chip{color:var(--mc,var(--cyan));border-color:color-mix(in srgb,var(--mc,var(--cyan)) 45%,transparent)}
#modalLog{font-family:var(--font-mono);font-size:11.5px;line-height:1.8;background:#050910;border:1px solid var(--line);border-radius:10px;padding:16px;color:#9fe8ff;white-space:pre-wrap;overflow-x:auto}
#modalLog::-webkit-scrollbar{height:6px}
.modal-cta{margin-top:24px;display:flex;gap:12px;flex-wrap:wrap}

/* ---------- FOCUS ---------- */
.focus-layout{display:grid;grid-template-columns:340px 1fr;gap:40px;align-items:center}
.radar-wrap{display:flex;flex-direction:column;align-items:center;gap:18px}
.radar{position:relative;width:280px;height:280px;border-radius:50%;border:1px solid rgba(0,245,255,.35);background:radial-gradient(circle,rgba(0,245,255,.05),rgba(4,6,14,.6) 75%),repeating-radial-gradient(circle,transparent 0 45px,rgba(0,245,255,.14) 45px 46px);overflow:hidden;box-shadow:0 0 40px rgba(0,245,255,.12),inset 0 0 40px rgba(0,245,255,.06)}
.radar::before{content:'';position:absolute;inset:0;background:linear-gradient(rgba(0,245,255,.12) 1px,transparent 1px),linear-gradient(90deg,rgba(0,245,255,.12) 1px,transparent 1px);background-size:100% 50%,50% 100%;background-position:center}
.radar-sweep{position:absolute;inset:0;border-radius:50%;background:conic-gradient(from 0deg,rgba(0,245,255,.55),rgba(0,245,255,.08) 70deg,transparent 90deg);animation:spinZ 4.2s linear infinite}
.blip{position:absolute;width:9px;height:9px;border-radius:50%;background:var(--magenta);box-shadow:0 0 12px var(--magenta);animation:blipPing 4.2s ease-out infinite}
.blip.b2{background:var(--lime);box-shadow:0 0 12px var(--lime);animation-delay:1.1s}
.blip.b3{background:var(--amber);box-shadow:0 0 12px var(--amber);animation-delay:2.2s}
.blip.b4{background:var(--cyan);box-shadow:0 0 12px var(--cyan);animation-delay:3.1s}
@keyframes blipPing{0%,15%{transform:scale(1);opacity:1}45%{transform:scale(2.1);opacity:.25}70%,100%{transform:scale(1);opacity:1}}
.radar-label{font-family:var(--font-hud);font-weight:700;font-size:11px;letter-spacing:.34em;color:var(--muted)}
.focus-list{display:flex;flex-direction:column;gap:18px}
.focus-item{padding:20px 22px}
.focus-top{display:flex;align-items:center;gap:13px;margin-bottom:8px}
.focus-ico{font-size:21px}
.focus-item h3{font-family:var(--font-display);font-weight:700;font-size:14.5px;letter-spacing:.06em}
.focus-pct{margin-left:auto;font-family:var(--font-mono);font-size:14px;color:var(--fc,var(--cyan))}
.focus-item p{font-size:13px;color:var(--muted);margin-bottom:13px}
.bar{height:6px;border-radius:6px;background:#0b1428;border:1px solid rgba(0,245,255,.12);overflow:hidden}
.bar i{display:block;height:100%;width:0;border-radius:6px;background:linear-gradient(90deg,var(--fc,var(--cyan)),color-mix(in srgb,var(--fc,var(--cyan)) 40%,var(--violet)));box-shadow:0 0 12px var(--fc,var(--cyan));transition:width 1.4s cubic-bezier(.2,.7,.2,1)}

/* ---------- CONTACT ---------- */
.uplink{padding:clamp(30px,5vw,60px);text-align:center;border:1px solid transparent!important;background:linear-gradient(#0a1122,#0a1122) padding-box,linear-gradient(120deg,var(--cyan),var(--violet),var(--magenta)) border-box!important;border-radius:20px;position:relative;overflow:hidden}
.uplink::before{content:'';position:absolute;inset:-40%;background:conic-gradient(from 0deg,transparent 70%,rgba(0,245,255,.08) 82%,transparent 94%);animation:spinZ 9s linear infinite;pointer-events:none}
.uplink-kicker{font-family:var(--font-mono);font-size:12px;letter-spacing:.3em;color:var(--lime);margin-bottom:18px;position:relative}
.uplink-title{font-family:var(--font-display);font-weight:900;font-size:clamp(22px,4.4vw,42px);letter-spacing:.03em;line-height:1.3;min-height:2.6em;position:relative;background:linear-gradient(92deg,#fff,var(--cyan) 55%,var(--magenta));-webkit-background-clip:text;background-clip:text;color:transparent}
.uplink-title .caret{background:var(--magenta);box-shadow:0 0 8px var(--magenta)}
.uplink-sub{color:var(--muted);max-width:560px;margin:14px auto 30px;font-size:15px;position:relative}
.uplink-ctas{display:flex;justify-content:center;flex-wrap:wrap;gap:14px;margin-bottom:32px;position:relative}
.uplink-meta{display:flex;justify-content:center;flex-wrap:wrap;gap:10px;position:relative}

/* ---------- FOOTER ---------- */
footer{position:relative;margin-top:40px}
.footer-wave{display:block;width:100%;height:110px;overflow:hidden}
.footer-wave svg{width:200%;height:100%;display:block}
.wave-move{animation:waveSlide 13s linear infinite}
.wave-move.slow{animation-duration:21s;animation-direction:reverse;opacity:.45}
@keyframes waveSlide{to{transform:translateX(-1440px)}}
.footer-bar{background:#05080f;border-top:1px solid var(--line);padding:26px 0}
.footer-inner{display:flex;flex-wrap:wrap;align-items:center;gap:16px}
.footer-inner .f-logo{font-family:var(--font-display);font-weight:700;font-size:13px;letter-spacing:.12em}
.footer-inner .f-logo b{color:var(--cyan)}
.footer-sys{font-family:var(--font-mono);font-size:10.5px;color:var(--muted);display:flex;align-items:center;gap:9px;margin-left:auto}
.footer-copy{width:100%;font-family:var(--font-hud);font-weight:600;font-size:11px;letter-spacing:.22em;color:#44608f;text-align:center;margin-top:8px}
#toTop{position:fixed;right:22px;bottom:22px;z-index:1300;width:46px;height:46px;border-radius:12px;border:1px solid rgba(0,245,255,.45);background:rgba(6,12,26,.9);color:var(--cyan);font-size:18px;opacity:0;visibility:hidden;transform:translateY(12px);transition:.3s;box-shadow:0 0 18px rgba(0,245,255,.2)}
#toTop.show{opacity:1;visibility:visible;transform:none}
#toTop:hover{background:rgba(0,245,255,.15);box-shadow:0 0 26px rgba(0,245,255,.5)}

/* ---------- TOAST ---------- */
#toast{position:fixed;left:50%;bottom:30px;transform:translate(-50%,20px);z-index:2500;background:rgba(8,14,28,.95);border:1px solid var(--line);border-radius:12px;padding:13px 22px;font-family:var(--font-hud);font-weight:700;font-size:13px;letter-spacing:.1em;color:var(--text);opacity:0;visibility:hidden;transition:.3s;display:flex;align-items:center;gap:10px;backdrop-filter:blur(10px);max-width:calc(100vw - 40px)}
#toast.show{opacity:1;visibility:visible;transform:translate(-50%,0)}
#toast.ok{border-color:rgba(57,255,20,.5);box-shadow:0 0 24px rgba(57,255,20,.2)}
#toast.ok::before{content:'✓';color:var(--lime)}
#toast.info{border-color:rgba(0,245,255,.5);box-shadow:0 0 24px rgba(0,245,255,.2)}
#toast.info::before{content:'⚡';color:var(--cyan)}
#toast.err{border-color:rgba(255,59,92,.5)}
#toast.err::before{content:'✕';color:var(--red)}

/* ---------- RESPONSIVE ---------- */
@media (max-width:1080px){
  .hero-grid{grid-template-columns:1fr;gap:44px}
  .console{max-width:520px}
  .arch-layout{grid-template-columns:1fr}
  .focus-layout{grid-template-columns:1fr;gap:34px}
  .radar-wrap{order:2}
}
@media (max-width:860px){
  .nav-links{display:none}
  #navMenuBtn{display:grid;place-items:center}
  .nav-actions .btn{display:none}
  .proj-card,.proj-card.wide{grid-column:span 6}
  .proj-card.wide .wide-inner{grid-template-columns:1fr;gap:14px}
  section{padding:80px 0}
  .hero-stats{grid-template-columns:repeat(2,1fr);width:100%}
  .stat:nth-child(2){border-right:0}
  .stat:nth-child(1),.stat:nth-child(2){border-bottom:1px solid var(--line)}
}
@media (max-width:520px){
  .hero{padding-top:calc(var(--nav-h) + 36px)}
  .holo{height:250px;transform:scale(.86)}
  .term-screen{padding:14px;font-size:12px}
  #termInput{font-size:12px}
  .stack-grid{grid-template-columns:repeat(3,1fr)}
  #soundBtn span{display:none}
  .uplink-ctas .btn{width:100%;justify-content:center}
  .hero-ctas .btn{flex:1;justify-content:center}
}
@media (prefers-reduced-motion:reduce){
  *,*::before,*::after{animation-duration:.001s!important;animation-iteration-count:1!important;transition-duration:.001s!important}
  html{scroll-behavior:auto}
  .packet{display:none}
  .marquee-track{animation:none!important}
}
</style>
<noscript><style>#bootOverlay{display:none}.hero [data-stage],.reveal{opacity:1!important;transform:none!important}</style></noscript>
</head>
<body>

<a class="skip-link" href="#terminal">Skip to content</a>

<!-- BOOT -->
<div id="bootOverlay" role="presentation">
  <div class="boot-logo">ABHILASH://CLOUD</div>
  <div class="boot-bar"><i></i></div>
  <div id="bootLine">Initializing cloud console…</div>
  <div class="boot-skip">CLICK TO SKIP</div>
</div>

<div class="aurora" aria-hidden="true"><i></i><i></i><i></i></div>
<div class="grain" aria-hidden="true"></div>
<div id="cursorGlow" aria-hidden="true"></div>
<div id="progressBar" aria-hidden="true"></div>

<!-- NAV -->
<nav id="navbar" aria-label="Primary">
  <div class="nav-inner">
    <a class="nav-logo" href="#top"><span class="logo-glyph">⚡</span>ABHILASH<b>://</b>CLOUD</a>
    <div class="nav-links">
      <a class="nav-link" href="#terminal">SHELL</a>
      <a class="nav-link" href="#stack">ARSENAL</a>
      <a class="nav-link" href="#architecture">BLUEPRINT</a>
      <a class="nav-link" href="#projects">MISSIONS</a>
      <a class="nav-link" href="#focus">FOCUS</a>
      <a class="nav-link" href="#contact">CONTACT</a>
    </div>
    <div class="nav-actions">
      <button id="soundBtn" aria-pressed="true" aria-label="Toggle sound">🔊 <span>SOUND ON</span></button>
      <a class="btn btn-primary btn-sm" href="mailto:Abhilashantony17@gmail.com?subject=Opportunity%20for%20Abhilash%20%E2%80%94%20Cloud%20%2F%20DevOps">HIRE ME ⚡</a>
      <button id="navMenuBtn" aria-expanded="false" aria-label="Open menu">☰</button>
    </div>
  </div>
</nav>
<div id="mobileMenu">
  <a class="nav-link" href="#terminal">SHELL</a>
  <a class="nav-link" href="#stack">ARSENAL</a>
  <a class="nav-link" href="#architecture">BLUEPRINT</a>
  <a class="nav-link" href="#projects">MISSIONS</a>
  <a class="nav-link" href="#focus">FOCUS</a>
  <a class="nav-link" href="#contact">CONTACT</a>
  <a class="btn btn-primary" style="margin-top:10px;justify-content:center" href="mailto:Abhilashantony17@gmail.com?subject=Opportunity%20for%20Abhilash">HIRE ME ⚡</a>
</div>

<!-- HERO -->
<header class="hero" id="top">
  <canvas id="heroCanvas" aria-hidden="true"></canvas>
  <div class="container hero-grid">
    <div>
      <div class="status-chip" data-stage style="--d:.05s"><span class="led"></span>STATUS · OPEN_TO_WORK</div>
      <div class="hero-kicker" data-stage style="--d:.12s">~/identity <b>$</b> cat cloud_engineer.profile</div>
      <h1 class="hero-name" data-stage style="--d:.2s"><span class="glitch" id="typeName" data-text="ABHILASH T.A">ABHILASH T.A</span></h1>
      <div class="hero-role" data-stage style="--d:.3s">CLOUD ENGINEER <span class="sep">◆</span> AWS <span class="sep">◆</span> DEVOPS</div>
      <div class="type-wrap" data-stage style="--d:.38s"><span class="prompt-sym">&gt;</span><span id="typeLine"></span><span class="caret" aria-hidden="true"></span></div>
      <div class="hero-badges" data-stage style="--d:.46s">
        <span class="badge b-cyan">🎓 BCA · CLASS OF 2026</span>
        <span class="badge b-violet">☁ AWS-FOCUSED BUILDER</span>
        <span class="badge b-magenta">📍 MANGALORE · BANGALORE · REMOTE</span>
      </div>
      <div class="hero-ctas" data-stage style="--d:.54s">
        <a class="btn btn-primary" href="mailto:Abhilashantony17@gmail.com?subject=Let%27s%20build%20in%20the%20cloud">📧 EMAIL ME</a>
        <a class="btn btn-ghost" href="https://www.linkedin.com/in/abhilash-t-anthony-74a529260" target="_blank" rel="noopener">in · LINKEDIN</a>
        <button class="btn btn-magenta" data-copy="Abhilashantony17@gmail.com">⧉ COPY EMAIL</button>
      </div>
      <div class="hero-stats" data-stage style="--d:.62s">
        <div class="stat"><b><span data-count="5" data-suffix="+">0+</span></b><span>CLOUD BUILDS</span></div>
        <div class="stat"><b><span data-count="15" data-suffix="+">0+</span></b><span>TOOLS DEPLOYED</span></div>
        <div class="stat"><b><span data-count="7" data-suffix="">0</span></b><span>AWS DOMAINS</span></div>
        <div class="stat"><b>∞</b><span>AUTOMATE-EVERYTHING</span></div>
      </div>
    </div>
    <div class="console panel" data-stage style="--d:.4s">
      <div class="console-head"><span class="led"></span>LIVE CONSOLE<span class="region">ap-south-1 · Mumbai</span></div>
      <div class="holo" aria-hidden="true">
        <div class="ring r1"></div><div class="ring r2"></div><div class="ring r3"></div>
        <div class="orbit">
          <div class="sat" style="left:128px;top:0"><span>EC2</span></div>
          <div class="sat" style="left:-128px;top:0"><span>S3</span></div>
          <div class="sat" style="left:0;top:128px"><span>IAM</span></div>
          <div class="sat" style="left:0;top:-128px"><span>λ LAMBDA</span></div>
        </div>
        <div class="orbit rev">
          <div class="sat" style="left:158px;top:60px"><span>VPC</span></div>
          <div class="sat" style="left:-158px;top:-60px"><span>RDS</span></div>
          <div class="sat" style="left:-60px;top:158px"><span>CF</span></div>
          <div class="sat" style="left:60px;top:-158px"><span>🐳</span></div>
        </div>
        <div class="holo-core"><span class="mono">AT</span><small>CLOUD CORE</small></div>
      </div>
      <div class="telemetry">
        <div class="tele"><span>LATENCY</span><b id="latencyVal">21ms</b></div>
        <div class="tele"><span>UPTIME</span><b id="uptimeVal">00:00:00</b></div>
        <div class="tele"><span>STATE</span><b class="ok">OPERATIONAL</b></div>
      </div>
      <div class="equalizer" aria-hidden="true">
        <i style="animation-delay:0s"></i><i style="animation-delay:.15s"></i><i style="animation-delay:.3s"></i><i style="animation-delay:.45s"></i><i style="animation-delay:.1s"></i><i style="animation-delay:.55s"></i><i style="animation-delay:.25s"></i><i style="animation-delay:.4s"></i><i style="animation-delay:.05s"></i><i style="animation-delay:.6s"></i><i style="animation-delay:.2s"></i><i style="animation-delay:.5s"></i>
      </div>
    </div>
  </div>
  <div class="scroll-cue" aria-hidden="true">SCROLL TO INITIALIZE<i></i></div>
</header>

<!-- MARQUEE -->
<div class="marquee" aria-hidden="true">
  <div class="marquee-track" id="marqueeTrack">
    <div class="marquee-set">
      <span>EC2</span><i>◆</i><span>VPC</span><i>◆</i><span>IAM</span><i>◆</i><span>S3</span><i>◆</i><span>LAMBDA</span><i>◆</i><span>CLOUDFRONT</span><i>◆</i><span>ROUTE 53</span><i>◆</i><span>DYNAMODB</span><i>◆</i><span>RDS</span><i>◆</i><span>TERRAFORM</span><i>◆</i><span>DOCKER</span><i>◆</i><span>GITHUB ACTIONS</span><i>◆</i><span>CLOUDWATCH</span><i>◆</i><span>KMS</span><i>◆</i><span>EVENTBRIDGE</span><i>◆</i><span>SNS · SQS</span><i>◆</i>
    </div>
  </div>
</div>

<!-- TERMINAL -->
<section id="terminal">
  <div class="container">
    <div class="sec-head reveal">
      <div class="sec-index">01 // SYSTEM SHELL</div>
      <h2 class="sec-title"><span data-scramble>INTERACTIVE</span> <span class="grad">TERMINAL</span></h2>
      <p class="sec-sub">A live shell into my profile. It boots itself — then it's yours. Type <b style="color:var(--cyan)">help</b> and explore.</p>
    </div>
    <div class="terminal panel reveal" id="terminalPanel">
      <div class="term-head">
        <span class="term-dot r"></span><span class="term-dot a"></span><span class="term-dot g"></span>
        <span class="term-title">abhilash@cloud: ~/console — bash</span>
        <span id="termClock">00:00:00</span>
      </div>
      <div class="term-screen">
        <div id="termBody" aria-live="polite"></div>
        <div class="term-input-row">
          <span class="t-prompt">abhilash@cloud:~$</span>
          <input id="termInput" type="text" autocomplete="off" spellcheck="false" aria-label="Terminal input" placeholder="">
        </div>
      </div>
      <div class="term-hint">PRO TIP · <b>help</b> lists commands · <b>sudo hire-me</b> unlocks the recruiter fast-track · ↑/↓ history · TAB autocompletes</div>
    </div>
  </div>
</section>

<!-- STACK -->
<section id="stack">
  <div class="container">
    <div class="sec-head reveal">
      <div class="sec-index">02 // TECH ARSENAL</div>
      <h2 class="sec-title"><span data-scramble>WEAPONS</span> <span class="grad">OF CHOICE</span></h2>
      <p class="sec-sub">The tools I reach for when building, securing and automating cloud infrastructure.</p>
    </div>
    <div class="stack-grid reveal" id="stackGrid"></div>
    <div class="sec-head reveal" style="margin-bottom:30px">
      <div class="sec-index" style="color:var(--cyan)">02.1 // CAPABILITY MATRIX</div>
      <h2 class="sec-title" style="font-size:clamp(20px,3vw,28px)">AWS <span class="grad">DOMAIN COVERAGE</span></h2>
    </div>
    <div class="domain-grid reveal" id="domainGrid"></div>
  </div>
</section>

<!-- ARCHITECTURE -->
<section id="architecture">
  <div class="container">
    <div class="sec-head reveal">
      <div class="sec-index">03 // FEATURED BLUEPRINT</div>
      <h2 class="sec-title"><span data-scramble>CUSTOM VPC</span> <span class="grad">ARCHITECTURE</span></h2>
      <p class="sec-sub">Public / private tiers across 2 AZs with a bastion jump host and NAT egress. Toggle traffic layers, hover nodes for intel, or run a live packet trace.</p>
    </div>
    <div class="arch-layout reveal">
      <div class="diagram-panel panel">
        <div class="diagram-toolbar">
          <label class="chip-toggle" style="--c:var(--cyan)"><input type="checkbox" checked data-flow="in"><span class="chip-ui"><i class="dot"></i>INBOUND</span></label>
          <label class="chip-toggle" style="--c:var(--magenta)"><input type="checkbox" checked data-flow="ssh"><span class="chip-ui"><i class="dot"></i>SSH</span></label>
          <label class="chip-toggle" style="--c:var(--lime)"><input type="checkbox" checked data-flow="up"><span class="chip-ui"><i class="dot"></i>UPDATES</span></label>
          <label class="chip-toggle" style="--c:var(--amber)"><input type="checkbox" checked data-flow="out"><span class="chip-ui"><i class="dot"></i>EGRESS</span></label>
          <button class="btn btn-primary btn-sm" id="traceBtn">▶ RUN TRACE</button>
        </div>
        <div class="diagram-scroll">
        <svg id="vpcSvg" viewBox="0 0 1000 620" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" role="img" aria-label="Custom VPC architecture diagram">
          <defs>
            <marker id="arrIn" markerWidth="8" markerHeight="8" refX="8" refY="4" orient="auto"><path d="M0 0 L8 4 L0 8 z" fill="#00F5FF"/></marker>
            <marker id="arrSsh" markerWidth="8" markerHeight="8" refX="8" refY="4" orient="auto"><path d="M0 0 L8 4 L0 8 z" fill="#FF00E5"/></marker>
            <marker id="arrUp" markerWidth="8" markerHeight="8" refX="8" refY="4" orient="auto"><path d="M0 0 L8 4 L0 8 z" fill="#39FF14"/></marker>
            <marker id="arrOut" markerWidth="8" markerHeight="8" refX="8" refY="4" orient="auto"><path d="M0 0 L8 4 L0 8 z" fill="#FFB020"/></marker>
            <filter id="pktGlow" x="-80%" y="-80%" width="260%" height="260%"><feGaussianBlur stdDeviation="2.4" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
          </defs>

          <rect class="zone" x="60" y="210" width="880" height="380" rx="14"/>
          <text class="zone-label" x="100" y="240">☁ CUSTOM VPC · 10.0.0.0/16</text>
          <rect class="zone" x="90" y="252" width="360" height="316" rx="12" style="stroke:rgba(0,245,255,.3)"/>
          <text class="zone-label" x="110" y="280" style="font-size:11px">PUBLIC SUBNETS · WEB TIER ×2 AZ</text>
          <rect class="zone" x="550" y="252" width="360" height="316" rx="12" style="stroke:rgba(123,47,247,.45);fill:rgba(123,47,247,.04)"/>
          <text class="zone-label violet" x="570" y="280" style="font-size:11px">PRIVATE SUBNETS · APP TIER ×2 AZ</text>

          <g id="flow-in" class="flow">
            <path id="p-in" d="M500 92 L500 126" marker-end="url(#arrIn)"/>
            <path id="p-in2" d="M500 188 L500 216 L280 216 L280 294" marker-end="url(#arrIn)"/>
            <g filter="url(#pktGlow)">
              <circle class="packet" r="4" fill="#00F5FF"><animateMotion dur="1.5s" repeatCount="indefinite"><mpath href="#p-in" xlink:href="#p-in"/></animateMotion></circle>
              <circle class="packet" r="4" fill="#00F5FF"><animateMotion dur="2.6s" repeatCount="indefinite"><mpath href="#p-in2" xlink:href="#p-in2"/></animateMotion></circle>
            </g>
          </g>
          <g id="flow-ssh" class="flow">
            <path id="p-ssh1" d="M350 332 L644 332" marker-end="url(#arrSsh)"/>
            <path id="p-ssh2" d="M350 348 C 480 348, 510 502, 644 502" marker-end="url(#arrSsh)"/>
            <text class="flow-label" x="470" y="322" fill="#FF00E5">SSH :22</text>
            <g filter="url(#pktGlow)">
              <circle class="packet" r="4" fill="#FF00E5"><animateMotion dur="2.1s" repeatCount="indefinite"><mpath href="#p-ssh1" xlink:href="#p-ssh1"/></animateMotion></circle>
              <circle class="packet" r="4" fill="#FF00E5"><animateMotion dur="3s" begin="0.7s" repeatCount="indefinite"><mpath href="#p-ssh2" xlink:href="#p-ssh2"/></animateMotion></circle>
            </g>
          </g>
          <g id="flow-up" class="flow">
            <path id="p-up1" d="M650 316 C 520 300, 470 460, 356 486" marker-end="url(#arrUp)"/>
            <path id="p-up2" d="M650 518 L356 518" marker-end="url(#arrUp)"/>
            <text class="flow-label" x="452" y="545" fill="#39FF14">pkg updates</text>
            <g filter="url(#pktGlow)">
              <circle class="packet" r="4" fill="#39FF14"><animateMotion dur="3.4s" repeatCount="indefinite"><mpath href="#p-up1" xlink:href="#p-up1"/></animateMotion></circle>
              <circle class="packet" r="4" fill="#39FF14"><animateMotion dur="2.7s" begin="0.5s" repeatCount="indefinite"><mpath href="#p-up2" xlink:href="#p-up2"/></animateMotion></circle>
            </g>
          </g>
          <g id="flow-out" class="flow">
            <path id="p-nat" d="M210 502 L74 502 L74 160 L414 160" marker-end="url(#arrOut)"/>
            <text class="flow-label" x="84" y="452" fill="#FFB020">egress</text>
            <g filter="url(#pktGlow)">
              <circle class="packet" r="4" fill="#FFB020"><animateMotion dur="4.2s" repeatCount="indefinite"><mpath href="#p-nat" xlink:href="#p-nat"/></animateMotion></circle>
            </g>
          </g>

          <g class="node" data-node="internet" tabindex="0" role="button" aria-label="Internet">
            <circle class="n-box" cx="500" cy="58" r="32"/>
            <text x="500" y="66" text-anchor="middle" font-size="24">🌐</text>
            <text class="n-title" x="500" y="112" text-anchor="middle" style="font-size:12px">INTERNET</text>
          </g>
          <g class="node" data-node="igw" tabindex="0" role="button" aria-label="Internet Gateway">
            <rect class="n-box" x="420" y="132" width="160" height="56" rx="10"/>
            <text class="n-title" x="500" y="156" text-anchor="middle">⇅ IGW</text>
            <text class="n-sub" x="500" y="174" text-anchor="middle">internet gateway</text>
          </g>
          <g class="node" data-node="bastion" tabindex="0" role="button" aria-label="Bastion host">
            <rect class="n-box" x="210" y="300" width="140" height="64" rx="10"/>
            <text class="n-title" x="280" y="326" text-anchor="middle">🛡 BASTION</text>
            <text class="n-sub" x="280" y="346" text-anchor="middle">SSH jump host · AZ-a</text>
          </g>
          <g class="node" data-node="nat" tabindex="0" role="button" aria-label="NAT gateway">
            <rect class="n-box" x="210" y="470" width="140" height="64" rx="10"/>
            <text class="n-title" x="280" y="496" text-anchor="middle">🔀 NAT GW</text>
            <text class="n-sub" x="280" y="516" text-anchor="middle">egress only · AZ-a</text>
          </g>
          <g class="node" data-node="app1" tabindex="0" role="button" aria-label="EC2 app server 1">
            <rect class="n-box" x="650" y="300" width="140" height="64" rx="10"/>
            <text class="n-title" x="720" y="326" text-anchor="middle">⚙ EC2 APP 1</text>
            <text class="n-sub" x="720" y="346" text-anchor="middle">10.0.3.0/24 · AZ-a</text>
          </g>
          <g class="node" data-node="app2" tabindex="0" role="button" aria-label="EC2 app server 2">
            <rect class="n-box" x="650" y="470" width="140" height="64" rx="10"/>
            <text class="n-title" x="720" y="496" text-anchor="middle">⚙ EC2 APP 2</text>
            <text class="n-sub" x="720" y="516" text-anchor="middle">10.0.4.0/24 · AZ-b</text>
          </g>
          <g id="traceOverlay"></g>
        </svg>
        </div>
      </div>
      <div class="arch-side">
        <div class="info-panel panel">
          <div class="info-tag" id="infoTag">NODE INTEL</div>
          <h3 id="infoTitle">CUSTOM VPC</h3>
          <p id="infoBody">2 public + 2 private subnets across ap-south-1a/1b. Defense in depth with NACLs + Security Groups, bastion-only SSH, and NAT-controlled egress. Hover or tap any node.</p>
          <div class="info-hint">HOVER NODES · CLICK TO PIN</div>
        </div>
        <div class="log-panel panel">
          <div class="log-head"><span class="led" style="background:var(--cyan);box-shadow:0 0 10px var(--cyan)"></span>TRACE LOG</div>
          <div id="traceLog"><div class="tl-dim">// awaiting trace — press RUN TRACE</div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="container">
    <div class="sec-head reveal">
      <div class="sec-index">04 // MISSION LOG</div>
      <h2 class="sec-title"><span data-scramble>DEPLOYED</span> <span class="grad">PROJECTS</span></h2>
      <p class="sec-sub">Real AWS builds, shipped in public. Open a mission file for architecture notes and deploy logs.</p>
    </div>
    <div class="proj-grid reveal" id="projGrid"></div>
  </div>
</section>

<!-- FOCUS -->
<section id="focus">
  <div class="container">
    <div class="sec-head reveal">
      <div class="sec-index">05 // ACTIVE OPERATIONS</div>
      <h2 class="sec-title"><span data-scramble>CURRENT</span> <span class="grad">FOCUS</span></h2>
      <p class="sec-sub">What's on the workbench right now — tracked like missions, shipped like products.</p>
    </div>
    <div class="focus-layout reveal">
      <div class="radar-wrap">
        <div class="radar" aria-hidden="true">
          <div class="radar-sweep"></div>
          <span class="blip" style="left:62%;top:30%" title="Terraform IaC"></span>
          <span class="blip b2" style="left:30%;top:58%" title="Docker"></span>
          <span class="blip b3" style="left:70%;top:70%" title="CI/CD"></span>
          <span class="blip b4" style="left:42%;top:24%" title="AWS builds"></span>
        </div>
        <div class="radar-label">SCANNING · 4 ACTIVE TARGETS</div>
      </div>
      <div class="focus-list" id="focusList"></div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="container">
    <div class="sec-head reveal">
      <div class="sec-index">06 // UPLINK</div>
      <h2 class="sec-title"><span data-scramble>OPEN</span> <span class="grad">CHANNEL</span></h2>
    </div>
    <div class="uplink reveal">
      <div class="uplink-kicker">● TRANSMISSION READY — RESPONSE &lt; 24H</div>
      <h2 class="uplink-title" id="contactHead"><span id="contactType"></span><span class="caret" aria-hidden="true"></span></h2>
      <p class="uplink-sub">Seeking Cloud Engineer / Junior DevOps roles. If you're building on AWS — or want to — my inbox is the fastest route to me.</p>
      <div class="uplink-ctas">
        <a class="btn btn-primary" href="mailto:Abhilashantony17@gmail.com?subject=Cloud%20%2F%20DevOps%20opportunity">📧 Abhilashantony17@gmail.com</a>
        <button class="btn btn-ghost" data-copy="Abhilashantony17@gmail.com">⧉ COPY ADDRESS</button>
        <a class="btn btn-magenta" href="https://www.linkedin.com/in/abhilash-t-anthony-74a529260" target="_blank" rel="noopener">in · CONNECT ON LINKEDIN</a>
      </div>
      <div class="uplink-meta">
        <span class="badge b-cyan">📍 MANGALORE</span>
        <span class="badge b-violet">📍 BANGALORE</span>
        <span class="badge b-magenta">🌍 REMOTE</span>
        <span class="badge" style="color:var(--lime);border-color:rgba(57,255,20,.4)"><span class="led"></span>OPEN_TO_WORK</span>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-wave" aria-hidden="true">
    <svg viewBox="0 0 2880 120" preserveAspectRatio="none">
      <defs>
        <linearGradient id="waveGrad" x1="0" y1="0" x2="1" y2="0">
          <stop offset="0" stop-color="#7B2FF7"/><stop offset=".5" stop-color="#00F5FF"/><stop offset="1" stop-color="#7B2FF7"/>
        </linearGradient>
      </defs>
      <g class="wave-move slow">
        <path d="M0 70 C 240 20 480 110 720 70 C 960 30 1200 100 1440 70 C 1680 20 1920 110 2160 70 C 2400 30 2640 100 2880 70 L2880 120 L0 120 Z" fill="url(#waveGrad)"/>
      </g>
      <g class="wave-move">
        <path d="M0 84 C 240 44 480 114 720 84 C 960 54 1200 114 1440 84 C 1680 44 1920 114 2160 84 C 2400 54 2640 114 2880 84 L2880 120 L0 120 Z" fill="url(#waveGrad)" opacity=".85"/>
      </g>
    </svg>
  </div>
  <div class="footer-bar">
    <div class="container footer-inner">
      <div class="f-logo">ABHILASH<b>://</b>CLOUD</div>
      <div class="footer-sys"><span class="led"></span>BUILD v2.0.26 · REGION ap-south-1 · ALL SYSTEMS OPERATIONAL</div>
      <div class="footer-copy">© 2026 ABHILASH T.A — BUILT IN PUBLIC · DEPLOYED WITH ⚡ · LEAST-PRIVILEGE EVERYTHING</div>
    </div>
  </div>
</footer>

<button id="toTop" aria-label="Back to top">↑</button>
<div id="toast" role="status"></div>

<!-- MODAL -->
<div id="modalOverlay" aria-hidden="true">
  <div id="modalCard" class="panel" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
    <div class="modal-top">
      <span id="modalIndex">MISSION FILE</span>
      <button id="modalClose" aria-label="Close mission file">✕</button>
    </div>
    <h3 id="modalTitle"></h3>
    <div id="modalStatus"></div>
    <p id="modalDesc"></p>
    <div class="modal-sec">MISSION HIGHLIGHTS</div>
    <ul id="modalList"></ul>
    <div class="modal-sec">STACK</div>
    <div id="modalChips"></div>
    <div class="modal-sec">DEPLOY LOG</div>
    <pre id="modalLog"></pre>
    <div class="modal-cta">
      <a class="btn btn-primary btn-sm" id="modalLink" href="#">📧 DISCUSS THIS BUILD</a>
      <button class="btn btn-ghost btn-sm" id="modalDismiss">CLOSE FILE</button>
    </div>
  </div>
</div>

<script>
(() => {
'use strict';
const $ = s => document.querySelector(s);
const $$ = s => Array.from(document.querySelectorAll(s));
const reduced = matchMedia('(prefers-reduced-motion: reduce)').matches;
const finePointer = matchMedia('(hover: hover) and (pointer: fine)').matches;
const sleep = ms => new Promise(r => setTimeout(r, ms));
const SVG_NS = 'http://www.w3.org/2000/svg';
const EMAIL = 'Abhilashantony17@gmail.com';
const LINKEDIN = 'https://www.linkedin.com/in/abhilash-t-anthony-74a529260';

/* ============ SOUND ENGINE ============ */
let soundOn = true;
try { soundOn = localStorage.getItem('at-sound') !== 'off'; } catch (e) {}
let actx = null, masterGain = null;
function ensureAudio() {
  if (actx || !soundOn) return;
  try {
    const AC = window.AudioContext || window.webkitAudioContext;
    actx = new AC();
    masterGain = actx.createGain();
    masterGain.gain.value = 0.14;
    masterGain.connect(actx.destination);
  } catch (e) {}
}
function tone(freq, dur = 0.07, type = 'sine', vol = 0.5, delay = 0) {
  if (!soundOn || !actx) return;
  if (actx.state === 'suspended') actx.resume();
  const t = actx.currentTime + delay;
  const osc = actx.createOscillator(), g = actx.createGain();
  osc.type = type; osc.frequency.setValueAtTime(freq, t);
  g.gain.setValueAtTime(0.0001, t);
  g.gain.linearRampToValueAtTime(vol, t + 0.008);
  g.gain.exponentialRampToValueAtTime(0.0001, t + dur);
  osc.connect(g); g.connect(masterGain);
  osc.start(t); osc.stop(t + dur + 0.03);
}
const sfx = {
  hover: () => tone(1650, 0.03, 'sine', 0.1),
  click: () => { tone(520, 0.06, 'triangle', 0.4); tone(1040, 0.05, 'sine', 0.18, 0.03); },
  key: () => tone(880 + Math.random() * 240, 0.02, 'square', 0.05),
  ok: () => { tone(660, 0.09, 'sine', 0.32); tone(990, 0.13, 'sine', 0.28, 0.08); },
  err: () => tone(150, 0.13, 'sawtooth', 0.22),
  trace: () => [440, 660, 880].forEach((f, i) => tone(f, 0.12, 'sine', 0.28, i * 0.09))
};
document.addEventListener('pointerdown', ensureAudio);
document.addEventListener('keydown', ensureAudio);
document.addEventListener('pointerover', e => {
  if (e.target.closest('.btn, .nav-link, .chip-toggle, .t-tile, .node, .proj-card, #soundBtn, #toTop')) sfx.hover();
});
document.addEventListener('click', e => {
  if (e.target.closest('.btn, .nav-link, .proj-open, #toTop')) sfx.click();
});
const soundBtn = $('#soundBtn');
function renderSoundBtn() {
  soundBtn.classList.toggle('muted', !soundOn);
  soundBtn.setAttribute('aria-pressed', String(soundOn));
  soundBtn.innerHTML = soundOn ? '🔊 <span>SOUND ON</span>' : '🔇 <span>MUTED</span>';
}
renderSoundBtn();
soundBtn.addEventListener('click', () => {
  soundOn = !soundOn;
  try { localStorage.setItem('at-sound', soundOn ? 'on' : 'off'); } catch (e) {}
  if (soundOn) { ensureAudio(); sfx.ok(); }
  renderSoundBtn();
  toast(soundOn ? 'Audio systems online' : 'Audio muted', 'info');
});

/* ============ TOAST ============ */
const toastEl = $('#toast');
let toastTimer = null;
function toast(msg, type = 'info') {
  toastEl.textContent = msg;
  toastEl.className = 'show ' + type;
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => toastEl.classList.remove('show'), 2600);
}

/* ============ SCRAMBLE ============ */
function scramble(el, finalText, dur = 900) {
  if (reduced) { el.textContent = finalText; return; }
  const glyphs = '!<>-_\\/[]{}=+*^?#01';
  const t0 = performance.now();
  function frame(now) {
    const p = Math.min(1, (now - t0) / dur);
    const revealCount = Math.floor(p * finalText.length);
    let out = '';
    for (let i = 0; i < finalText.length; i++) {
      const ch = finalText[i];
      out += (ch === ' ' || i < revealCount) ? ch : glyphs[(Math.random() * glyphs.length) | 0];
    }
    el.textContent = out;
    if (p < 1) requestAnimationFrame(frame); else el.textContent = finalText;
  }
  requestAnimationFrame(frame);
}

/* ============ TYPER ============ */
function typer(el, phrases, { type = 46, del = 24, hold = 1750, loop = true } = {}) {
  if (reduced) { el.textContent = phrases[0]; return; }
  let pi = 0, pos = 0, deleting = false;
  (function tick() {
    const cur = phrases[pi];
    if (!deleting) {
      pos++; el.textContent = cur.slice(0, pos);
      if (pos === cur.length) {
        if (!loop && pi === phrases.length - 1) return;
        deleting = true; return setTimeout(tick, hold);
      }
      return setTimeout(tick, type + Math.random() * 38);
    }
    pos--; el.textContent = cur.slice(0, pos);
    if (pos === 0) { deleting = false; pi = (pi + 1) % phrases.length; return setTimeout(tick, 420); }
    setTimeout(tick, del);
  })();
}

/* ============ BOOT ============ */
const bootOverlay = $('#bootOverlay'), bootLine = $('#bootLine');
const bootMsgs = ['Linking ap-south-1…', 'Mounting IAM policies…', 'Establishing VPC peering…', 'Decrypting portfolio (KMS)…', 'Compiling ambition…', 'Console ready ✓'];
let bootIdx = 0;
const bootTicker = setInterval(() => { bootLine.textContent = bootMsgs[bootIdx++ % bootMsgs.length]; }, 250);
let bootEnded = false, bootAutoT = null;
function endBoot() {
  if (bootEnded) return; bootEnded = true;
  clearInterval(bootTicker); clearTimeout(bootAutoT);
  bootOverlay.classList.add('done');
  document.body.classList.add('ready');
  setTimeout(() => bootOverlay.remove(), 700);
  scramble($('#typeName'), 'ABHILASH T.A', 1100);
  typer($('#typeLine'), [
    'Architecting secure AWS infrastructure',
    'Automating everything with Python & Bash',
    'Shipping with Docker + Terraform + CI/CD',
    'Open to Cloud / Junior DevOps roles'
  ]);
}
bootOverlay.addEventListener('click', endBoot);
bootAutoT = setTimeout(endBoot, reduced ? 250 : 1750);
setTimeout(endBoot, 3200);

/* ============ PARTICLES ============ */
const heroCanvas = $('#heroCanvas'), heroEl = $('.hero');
const pctx = heroCanvas.getContext('2d');
const DPR = Math.min(window.devicePixelRatio || 1, 1.75);
let pts = [], cw = 0, chh = 0;
const mouseP = { x: -9999, y: -9999 };
const pColors = ['0,245,255', '123,47,247', '255,0,229'];
function sizeCanvas() {
  cw = heroEl.offsetWidth; chh = heroEl.offsetHeight;
  heroCanvas.width = cw * DPR; heroCanvas.height = chh * DPR;
  heroCanvas.style.width = cw + 'px'; heroCanvas.style.height = chh + 'px';
  pctx.setTransform(DPR, 0, 0, DPR, 0, 0);
  const target = Math.min(90, Math.floor(cw * chh / 16000));
  while (pts.length < target) pts.push({
    x: Math.random() * cw, y: Math.random() * chh,
    vx: (Math.random() - .5) * .45, vy: (Math.random() - .5) * .45,
    r: 1 + Math.random() * 1.8, c: pColors[(Math.random() * 3) | 0], tw: Math.random() * Math.PI * 2
  });
  pts.length = target;
}
function drawParticles(animate) {
  pctx.clearRect(0, 0, cw, chh);
  for (const p of pts) {
    if (animate) {
      p.x += p.vx; p.y += p.vy; p.tw += 0.02;
      const dxm = p.x - mouseP.x, dym = p.y - mouseP.y, dm = Math.hypot(dxm, dym);
      if (dm < 130 && dm > 0.1) { p.x += dxm / dm * 0.5; p.y += dym / dm * 0.5; }
      if (p.x < -10) p.x = cw + 10; if (p.x > cw + 10) p.x = -10;
      if (p.y < -10) p.y = chh + 10; if (p.y > chh + 10) p.y = -10;
    }
    const a = 0.35 + Math.sin(p.tw) * 0.25;
    pctx.beginPath(); pctx.arc(p.x, p.y, p.r, 0, Math.PI * 2);
    pctx.fillStyle = 'rgba(' + p.c + ',' + a.toFixed(2) + ')'; pctx.fill();
  }
  for (let i = 0; i < pts.length; i++) for (let j = i + 1; j < pts.length; j++) {
    const a = pts[i], b = pts[j], dx = a.x - b.x, dy = a.y - b.y, d2 = dx * dx + dy * dy;
    if (d2 < 14400) {
      const alpha = (1 - Math.sqrt(d2) / 120) * 0.32;
      pctx.strokeStyle = 'rgba(0,245,255,' + alpha.toFixed(3) + ')';
      pctx.lineWidth = 0.7;
      pctx.beginPath(); pctx.moveTo(a.x, a.y); pctx.lineTo(b.x, b.y); pctx.stroke();
    }
  }
}
sizeCanvas();
if (reduced) drawParticles(false);
else {
  (function loopP() {
    if (!document.hidden) drawParticles(true);
    requestAnimationFrame(loopP);
  })();
}
heroEl.addEventListener('pointermove', e => {
  const r = heroEl.getBoundingClientRect();
  mouseP.x = e.clientX - r.left; mouseP.y = e.clientY - r.top;
});
heroEl.addEventListener('pointerleave', () => { mouseP.x = -9999; mouseP.y = -9999; });
let resizeT = null;
window.addEventListener('resize', () => { clearTimeout(resizeT); resizeT = setTimeout(() => { sizeCanvas(); if (reduced) drawParticles(false); }, 150); });

/* ============ CURSOR GLOW ============ */
const glowEl = $('#cursorGlow');
if (finePointer && !reduced) {
  glowEl.style.display = 'block';
  let gx = innerWidth / 2, gy = innerHeight / 2, tx = gx, ty = gy;
  document.addEventListener('pointermove', e => { tx = e.clientX; ty = e.clientY; });
  (function loopG() {
    gx += (tx - gx) * 0.14; gy += (ty - gy) * 0.14;
    glowEl.style.transform = 'translate(' + gx + 'px,' + gy + 'px)';
    requestAnimationFrame(loopG);
  })();
}

/* ============ NAV / SCROLL ============ */
const navbar = $('#navbar'), progressBar = $('#progressBar'), toTop = $('#toTop');
let scrollTick = false;
function onScroll() {
  const y = scrollY, max = document.documentElement.scrollHeight - innerHeight;
  navbar.classList.toggle('scrolled', y > 30);
  progressBar.style.width = (max > 0 ? (y / max) * 100 : 0) + '%';
  toTop.classList.toggle('show', y > 700);
  scrollTick = false;
}
window.addEventListener('scroll', () => { if (!scrollTick) { scrollTick = true; requestAnimationFrame(onScroll); } }, { passive: true });
onScroll();
toTop.addEventListener('click', () => window.scrollTo({ top: 0, behavior: reduced ? 'auto' : 'smooth' }));
const menuBtn = $('#navMenuBtn'), mobileMenu = $('#mobileMenu');
function closeMenu() { mobileMenu.classList.remove('open'); menuBtn.setAttribute('aria-expanded', 'false'); menuBtn.textContent = '☰'; }
menuBtn.addEventListener('click', () => {
  const open = mobileMenu.classList.toggle('open');
  menuBtn.setAttribute('aria-expanded', String(open));
  menuBtn.textContent = open ? '✕' : '☰';
});
mobileMenu.querySelectorAll('a').forEach(a => a.addEventListener('click', closeMenu));
const spy = new IntersectionObserver(entries => {
  entries.forEach(en => {
    if (en.isIntersecting) $$('.nav-link').forEach(l => l.classList.toggle('active', l.getAttribute('href') === '#' + en.target.id));
  });
}, { rootMargin: '-40% 0px -55% 0px' });
['terminal', 'stack', 'architecture', 'projects', 'focus', 'contact'].forEach(id => spy.observe(document.getElementById(id)));

/* ============ MARQUEE (duplicate set) ============ */
const mTrack = $('#marqueeTrack');
mTrack.appendChild(mTrack.firstElementChild.cloneNode(true));

/* ============ COUNTERS / BARS ============ */
function countUp(el) {
  if (el.dataset.done) return; el.dataset.done = '1';
  const target = +el.dataset.count, suf = el.dataset.suffix || '';
  if (reduced) { el.textContent = target + suf; return; }
  const t0 = performance.now(), dur = 1100;
  (function fr(now) {
    const p = Math.min(1, (now - t0) / dur), e = 1 - Math.pow(1 - p, 3);
    el.textContent = Math.round(target * e) + suf;
    if (p < 1) requestAnimationFrame(fr);
  })(t0);
}

/* ============ REVEAL ============ */
let contactTyperStarted = false;
const io = new IntersectionObserver(entries => entries.forEach(en => {
  if (!en.isIntersecting) return;
  en.target.classList.add('in');
  io.unobserve(en.target);
  en.target.querySelectorAll('[data-scramble]').forEach(sc => {
    if (!sc.dataset.done) { sc.dataset.done = '1'; scramble(sc, sc.textContent.trim(), 800); }
  });
  en.target.querySelectorAll('[data-count]').forEach(countUp);
  en.target.querySelectorAll('.bar i[data-pct]').forEach(b => { b.style.width = b.dataset.pct + '%'; });
  if (en.target.id === 'terminalPanel') startTermAuto();
  if (!contactTyperStarted && en.target.querySelector('#contactHead')) {
    contactTyperStarted = true;
    typer($('#contactType'), ["Let's build something in the cloud ☁️"], { loop: false, type: 55 });
  }
}), { threshold: 0.16 });
$$('.reveal').forEach(el => io.observe(el));
$$('.hero [data-count]').forEach(el => setTimeout(() => countUp(el), 1900));

/* ============ STACK DATA ============ */
const DEV = 'https://cdn.jsdelivr.net/gh/devicons/devicon@v2.16.0/icons/';
const stackData = [
  ['AWS', 'amazonwebservices/amazonwebservices-original.svg', 'CLOUD', '#FF9900', 'AWS'],
  ['Docker', 'docker/docker-original.svg', 'DEVOPS', '#2496ED', 'DOCK'],
  ['Terraform', 'terraform/terraform-original.svg', 'IaC', '#7B42BC', 'TF'],
  ['GH Actions', 'githubactions/githubactions-original.svg', 'CI/CD', '#2088FF', 'GHA'],
  ['Python', 'python/python-original.svg', 'LANG', '#3776AB', 'PY'],
  ['Bash', 'bash/bash-plain.svg', 'SCRIPT', '#39FF14', 'SH', true],
  ['Linux', 'linux/linux-original.svg', 'OS', '#FCC624', 'LNX'],
  ['Nginx', 'nginx/nginx-original.svg', 'SERVER', '#009639', 'NGX'],
  ['Git', 'git/git-original.svg', 'VCS', '#F05032', 'GIT'],
  ['GitHub', 'github/github-original.svg', 'VCS', '#00F5FF', 'GH', true],
  ['React', 'react/react-original.svg', 'WEB', '#61DAFB', 'RCT'],
  ['Node.js', 'nodejs/nodejs-original.svg', 'RUNTIME', '#339933', 'NODE'],
  ['MongoDB', 'mongodb/mongodb-original.svg', 'DB', '#47A248', 'MDB'],
  ['Firebase', 'firebase/firebase-plain.svg', 'BAAS', '#FFCA28', 'FB'],
  ['Apache', 'apache/apache-original.svg', 'SERVER', '#D22128', 'APC']
];
const stackGrid = $('#stackGrid');
stackData.forEach(([name, path, cat, color, mono, inv]) => {
  const tile = document.createElement('div');
  tile.className = 't-tile';
  tile.style.setProperty('--tile-c', color + '2b');
  tile.style.setProperty('--tile-b', color + '88');
  tile.style.setProperty('--tile-g', color + '30');
  const icon = document.createElement('div'); icon.className = 't-icon';
  const fb = document.createElement('span'); fb.className = 't-fallback'; fb.textContent = mono; fb.style.color = color;
  const img = document.createElement('img');
  img.src = DEV + path; img.alt = name + ' logo'; img.loading = 'lazy';
  if (inv) img.classList.add('inv');
  img.onerror = () => {
    if (name === 'AWS' && !img.dataset.retried) {
      img.dataset.retried = '1';
      img.src = DEV + 'amazonwebservices/amazonwebservices-plain-wordmark.svg';
      img.classList.add('inv');
    } else img.style.display = 'none';
  };
  icon.append(fb, img);
  const nm = document.createElement('div'); nm.className = 't-name'; nm.textContent = name;
  const ct = document.createElement('div'); ct.className = 't-cat'; ct.textContent = cat;
  tile.append(icon, nm, ct);
  stackGrid.appendChild(tile);
});

const domains = [
  ['⚡', 'COMPUTE', 'var(--cyan)', ['EC2', 'Auto Scaling', 'ELB', 'Elastic Beanstalk', 'Lambda']],
  ['📡', 'NETWORKING', 'var(--violet)', ['VPC', 'NAT/IGW', 'NACLs', 'Security Groups', 'Peering', 'Transit Gateway', 'Route 53', 'CloudFront']],
  ['💾', 'STORAGE', 'var(--amber)', ['S3', 'EBS', 'EFS', 'AWS Backup']],
  ['🛡', 'SECURITY', 'var(--magenta)', ['IAM', 'STS', 'KMS', 'ACM', 'GuardDuty', 'Inspector', 'Organizations']],
  ['📈', 'MONITORING', 'var(--lime)', ['CloudWatch', 'CloudTrail', 'Systems Manager']],
  ['🔗', 'INTEGRATION', 'var(--info)', ['EventBridge', 'SNS', 'SQS', 'SES']],
  ['🗄', 'DATABASES', 'var(--red)', ['RDS', 'DynamoDB', 'MongoDB']]
];
const domainGrid = $('#domainGrid');
domains.forEach(([ico, name, color, techs]) => {
  const d = document.createElement('div');
  d.className = 'domain'; d.style.setProperty('--dc', color);
  const head = document.createElement('div'); head.className = 'domain-head';
  head.innerHTML = '<div class="domain-ico">' + ico + '</div><h3>' + name + '</h3><span class="domain-count">' + techs.length + ' SVC</span>';
  const chips = document.createElement('div'); chips.className = 'domain-chips';
  techs.forEach(t => { const c = document.createElement('span'); c.className = 'chip'; c.textContent = t; chips.appendChild(c); });
  d.append(head, chips);
  domainGrid.appendChild(d);
});

/* ============ TERMINAL ============ */
const termBody = $('#termBody'), termInput = $('#termInput'), termPanel = $('#terminalPanel');
const PROMPT = 'abhilash@cloud:~$';
let autoStarted = false, autoDone = false, stepTimer = null, stepIdx = 0;
const steps = [];
const cmdHistory = []; let hIdx = 0;
function tScroll() { termBody.scrollTop = termBody.scrollHeight; }
function tPrint(text, cls) {
  const d = document.createElement('div');
  d.className = 't-line ' + (cls || 't-out');
  d.textContent = text;
  termBody.appendChild(d); tScroll();
  return d;
}
function tCmdEcho(cmd) {
  const d = document.createElement('div'); d.className = 't-line t-cmd';
  const p = document.createElement('span'); p.className = 't-prompt'; p.textContent = PROMPT;
  d.appendChild(p); d.appendChild(document.createTextNode(' ' + cmd));
  termBody.appendChild(d); tScroll();
}
function tLink(label, url) {
  const d = document.createElement('div'); d.className = 't-line t-out';
  const a = document.createElement('a'); a.href = url; a.textContent = label;
  if (url.startsWith('http')) { a.target = '_blank'; a.rel = 'noopener'; }
  d.appendChild(a); termBody.appendChild(d); tScroll();
}
let liveCmdSpan = null;
function autoStartCmd() {
  const d = document.createElement('div'); d.className = 't-line t-cmd';
  const p = document.createElement('span'); p.className = 't-prompt'; p.textContent = PROMPT;
  d.appendChild(p); d.appendChild(document.createTextNode(' '));
  liveCmdSpan = document.createElement('span'); d.appendChild(liveCmdSpan);
  termBody.appendChild(d); tScroll();
}
const autoScript = [
  { cmd: 'whoami', out: [['Cloud Engineer | BCA Graduate (2026) | AWS-focused builder', 't-accent']] },
  { cmd: 'cat skills.conf', out: [
    ['cloud      = ["AWS","VPC","IAM","S3","EC2","Lambda","CloudFront"]', 't-out'],
    ['devops     = ["Docker","Terraform","GitHub Actions","CloudFormation"]', 't-out'],
    ['scripting  = ["Python","Bash","Linux"]', 't-out'],
    ['mindset    = "least-privilege, automate-everything, build-in-public"', 't-magenta']] },
  { cmd: 'cat mission.txt', out: [
    ['Build, secure and automate cloud infrastructure.', 't-out'],
    ['Learn fast. Ship real AWS projects.', 't-out']] },
  { cmd: 'status --now', out: [['[OK] Seeking Cloud Engineer / Junior DevOps opportunities', 't-ok']] }
];
autoScript.forEach(item => {
  steps.push({ fn: autoStartCmd, delay: 340 });
  for (const ch of item.cmd) steps.push({ fn: () => { if (liveCmdSpan) liveCmdSpan.textContent += ch; tScroll(); }, delay: 34 });
  steps.push({ fn: () => { liveCmdSpan = null; }, delay: 160 });
  item.out.forEach(([txt, cls]) => steps.push({ fn: () => tPrint(txt, cls), delay: 70 }));
});
function finishAuto() {
  if (autoDone) return; autoDone = true;
  tPrint("type 'help' to explore — 'sudo hire-me' unlocks the good stuff 😏", 't-dim');
}
function runSteps() {
  if (stepIdx >= steps.length) { finishAuto(); return; }
  const s = steps[stepIdx++];
  s.fn();
  stepTimer = setTimeout(runSteps, s.delay);
}
function skipAuto() {
  if (autoDone || !autoStarted) return;
  clearTimeout(stepTimer);
  while (stepIdx < steps.length) steps[stepIdx++].fn();
  finishAuto();
}
function startTermAuto() {
  if (autoStarted) return; autoStarted = true;
  tPrint('Last login: ' + new Date().toDateString() + ' on ttys001', 't-dim');
  if (reduced) { while (stepIdx < steps.length) steps[stepIdx++].fn(); finishAuto(); }
  else runSteps();
}
termPanel.addEventListener('click', () => { skipAuto(); termInput.focus(); });
termInput.addEventListener('focus', skipAuto);

const CMD_NAMES = ['help', 'whoami', 'skills', 'mission', 'status', 'projects', 'stack', 'contact', 'clear', 'date', 'echo', 'history', 'banner', 'linkedin', 'sudo'];
function exec(raw) {
  const input = raw.trim();
  if (!input) return;
  const parts = input.split(/\s+/);
  const cmd = parts[0].toLowerCase();
  const arg = parts.slice(1).join(' ');
  if (cmd === 'clear') { termBody.innerHTML = ''; return; }
  if (cmd === 'help') {
    tPrint('AVAILABLE COMMANDS', 't-accent');
    [['whoami', 'identity & headline'], ['skills / cat skills.conf', 'full skill config'],
     ['mission / cat mission.txt', 'the mission statement'], ['status', 'current availability'],
     ['projects', 'mission log summary'], ['stack', 'tech arsenal'], ['contact', 'open a channel'],
     ['banner', 'because terminals need banners'], ['history', 'command history'],
     ['date · echo · clear', 'the classics'], ['sudo hire-me', '⭐ recruiter fast-track']
    ].forEach(([c, d]) => tPrint('  ' + c.padEnd(26) + '→ ' + d, 't-dim'));
    return;
  }
  if (cmd === 'whoami') { tPrint('Cloud Engineer | BCA Graduate (2026) | AWS-focused builder', 't-accent'); return; }
  if (cmd === 'skills' || (cmd === 'cat' && arg === 'skills.conf')) {
    tPrint('cloud      = ["AWS","VPC","IAM","S3","EC2","Lambda","CloudFront"]');
    tPrint('devops     = ["Docker","Terraform","GitHub Actions","CloudFormation"]');
    tPrint('scripting  = ["Python","Bash","Linux"]');
    tPrint('mindset    = "least-privilege, automate-everything, build-in-public"', 't-magenta');
    return;
  }
  if (cmd === 'mission' || (cmd === 'cat' && arg === 'mission.txt')) {
    tPrint('Build, secure and automate cloud infrastructure.');
    tPrint('Learn fast. Ship real AWS projects.');
    return;
  }
  if (cmd === 'status') { tPrint('[OK] Seeking Cloud Engineer / Junior DevOps opportunities', 't-ok'); return; }
  if (cmd === 'projects') {
    tPrint('MISSION LOG — 5 entries', 't-accent');
    tPrint('  01  Custom VPC Architecture ........ DEPLOYED', 't-out');
    tPrint('  02  Secure Static Website .......... LIVE', 't-out');
    tPrint('  03  IAM Security Lab ............... HARDENED', 't-out');
    tPrint('  04  Serverless EC2 Scheduler ....... AUTOMATED', 't-out');
    tPrint('  05  Elastic Beanstalk Deployment ... GREEN', 't-out');
    tPrint("scroll to MISSIONS for full files ↑", 't-dim');
    return;
  }
  if (cmd === 'stack') { tPrint('aws docker terraform github-actions python bash linux nginx git github react nodejs mongodb firebase apache', 't-accent'); return; }
  if (cmd === 'contact') {
    tPrint('Opening channels…', 't-dim');
    tLink('📧 ' + EMAIL, 'mailto:' + EMAIL);
    tLink('in linkedin.com/in/abhilash-t-anthony', LINKEDIN);
    tPrint('📍 Mangalore | Bangalore | Remote', 't-out');
    return;
  }
  if (cmd === 'linkedin') { tLink('in ' + LINKEDIN, LINKEDIN); return; }
  if (cmd === 'date') { tPrint(new Date().toString()); return; }
  if (cmd === 'echo') { tPrint(arg || ''); return; }
  if (cmd === 'history') { cmdHistory.forEach((h, i) => tPrint('  ' + (i + 1) + '  ' + h, 't-dim')); return; }
  if (cmd === 'banner') {
    tPrint('  ▄▀█ █▄▄ █░█ █ █░░ ▄▀█ █▀ █░█   ▀█▀ ▄▀█', 't-accent');
    tPrint('  █▀█ █▄█ █▀█ █ █▄▄ █▀█ ▄█ █▀█   ░█░ █▀█', 't-accent');
    tPrint('  cloud engineer · aws · devops', 't-dim');
    return;
  }
  if (cmd === 'sudo') {
    if (arg === 'hire-me' || arg === 'hire') {
      tPrint('[sudo] password for recruiter: ********', 't-dim');
      tPrint('ACCESS GRANTED ✔ — recruiter fast-track unlocked', 't-ok');
      tPrint('Priority channel established. Response time < 24h:', 't-out');
      tLink('→ ' + EMAIL, 'mailto:' + EMAIL + '?subject=Recruiter%20fast-track%20%E2%9A%A1');
      tLink('→ LinkedIn profile', LINKEDIN);
      sfx.ok(); toast('Hire protocol initiated 🚀', 'ok');
    } else tPrint('sudo: ' + (arg || '(none)') + ': command not found', 't-err');
    return;
  }
  if (cmd === 'cat') { tPrint('cat: ' + (arg || '(none)') + ': try skills.conf or mission.txt', 't-err'); return; }
  tPrint('bash: ' + cmd + ": command not found — try 'help'", 't-err');
  sfx.err();
}
let lastKeySfx = 0;
termInput.addEventListener('keydown', e => {
  skipAuto();
  if (e.key === 'Enter') {
    const v = termInput.value; termInput.value = '';
    tCmdEcho(v);
    if (v.trim()) { cmdHistory.push(v); hIdx = cmdHistory.length; }
    exec(v); sfx.key();
  } else if (e.key === 'ArrowUp') {
    e.preventDefault();
    if (hIdx > 0) { hIdx--; termInput.value = cmdHistory[hIdx] || ''; }
  } else if (e.key === 'ArrowDown') {
    e.preventDefault();
    if (hIdx < cmdHistory.length) { hIdx++; termInput.value = cmdHistory[hIdx] || ''; }
  } else if (e.key === 'Tab') {
    e.preventDefault();
    const v = termInput.value.trim().toLowerCase();
    if (v) { const m = CMD_NAMES.find(c => c.startsWith(v)); if (m) { termInput.value = m + (m === 'sudo' ? ' hire-me' : ''); sfx.key(); } }
  } else if (e.key.length === 1) {
    const now = performance.now();
    if (now - lastKeySfx > 45) { sfx.key(); lastKeySfx = now; }
  }
});
setInterval(() => { $('#termClock').textContent = new Date().toLocaleTimeString('en-GB'); }, 1000);

/* ============ ARCHITECTURE ============ */
const nodeInfo = {
  vpc: ['CUSTOM VPC', '10.0.0.0/16 · 2 AZs · 4 subnets. Defense in depth with NACLs + Security Groups, bastion-only SSH, and NAT-controlled egress. Hover or tap any node.'],
  internet: ['INTERNET / EDGE', 'User traffic resolves via Route 53 and enters the VPC through the Internet Gateway. Nothing reaches private tiers directly.'],
  igw: ['INTERNET GATEWAY', 'Horizontally scaled, redundant VPC edge component. The public route table points 0.0.0.0/0 here.'],
  bastion: ['BASTION HOST', 'Hardened SSH jump box in the public subnet. Security Group allows :22 only from a trusted CIDR — the single door into private instances.'],
  nat: ['NAT GATEWAY', 'Lets private instances reach the internet for package updates. Outbound-only: the internet cannot initiate connections back in.'],
  app1: ['EC2 · APP 1', 'Private subnet, AZ-a, no public IP. Reachable only via the bastion; egress flows through the NAT Gateway.'],
  app2: ['EC2 · APP 2', 'Private subnet, AZ-b, no public IP. Multi-AZ placement keeps the app tier resilient to a single-AZ failure.']
};
const infoTitle = $('#infoTitle'), infoBody = $('#infoBody'), infoTag = $('#infoTag');
let pinnedNode = null;
function setInfo(key) {
  const d = nodeInfo[key] || nodeInfo.vpc;
  infoTitle.textContent = d[0]; infoBody.textContent = d[1];
  infoTag.textContent = key === 'vpc' ? 'NODE INTEL' : (pinnedNode === key ? 'PINNED · ' + key.toUpperCase() : 'NODE · ' + key.toUpperCase());
}
$$('.node').forEach(n => {
  const key = n.dataset.node;
  n.addEventListener('mouseenter', () => { setInfo(key); n.classList.add('active'); });
  n.addEventListener('mouseleave', () => { n.classList.remove('active'); setInfo(pinnedNode || 'vpc'); });
  n.addEventListener('focus', () => setInfo(key));
  const pin = () => { pinnedNode = pinnedNode === key ? null : key; setInfo(pinnedNode || key); sfx.click(); };
  n.addEventListener('click', pin);
  n.addEventListener('keydown', e => { if (e.key === 'Enter' || e.key === ' ') { e.preventDefault(); pin(); } });
});
$$('input[data-flow]').forEach(cb => cb.addEventListener('change', () => {
  const g = document.getElementById('flow-' + cb.dataset.flow);
  if (g) g.style.display = cb.checked ? '' : 'none';
  sfx.click();
}));
const traceBtn = $('#traceBtn'), traceLog = $('#traceLog'), traceOverlay = $('#traceOverlay');
let tracing = false;
function logLine(msg, cls) {
  const d = document.createElement('div');
  if (cls) d.className = cls;
  d.textContent = msg;
  traceLog.appendChild(d);
  traceLog.scrollTop = traceLog.scrollHeight;
}
function followPacket(pathEl, dur) {
  return new Promise(res => {
    const c = document.createElementNS(SVG_NS, 'circle');
    c.setAttribute('r', '5'); c.setAttribute('class', 'trace-packet');
    traceOverlay.appendChild(c);
    const L = pathEl.getTotalLength(), t0 = performance.now();
    (function fr(now) {
      const p = Math.min(1, (now - t0) / dur);
      const pt = pathEl.getPointAtLength(L * p);
      c.setAttribute('cx', pt.x); c.setAttribute('cy', pt.y);
      if (p < 1) requestAnimationFrame(fr); else { c.remove(); res(); }
    })(t0);
  });
}
async function runTrace() {
  if (tracing) return;
  tracing = true; traceBtn.disabled = true; traceBtn.textContent = '◉ TRACING…';
  traceLog.innerHTML = '';
  logLine('▸ trace initiated · target: EC2 APP 1', 'tl-dim');
  const seq = [
    ['internet', 'p-in', '[hop 1] request received at edge · TLS ✓'],
    ['igw', 'p-in2', '[hop 2] IGW accept · public route table lookup'],
    ['bastion', 'p-ssh1', '[hop 3] SG :22 ALLOW · SSH session established'],
    ['app1', null, '[hop 4] delivered to private EC2 · 200 OK']
  ];
  const lit = [];
  try {
    for (const [key, pathId, msg] of seq) {
      const node = document.querySelector('.node[data-node="' + key + '"]');
      node.classList.add('trace'); lit.push(node);
      logLine(msg);
      tone(500 + lit.length * 120, 0.08, 'sine', 0.25);
      if (!reduced && pathId) await followPacket(document.getElementById(pathId), 620);
      else await sleep(430);
    }
    await sleep(420);
    const ms = 18 + Math.floor(Math.random() * 14);
    logLine('✔ trace complete · 4 hops · ' + ms + 'ms · 0 drops', 'tl-ok');
    sfx.trace(); toast('Trace complete · 4 hops · ' + ms + 'ms', 'ok');
  } finally {
    lit.forEach(n => n.classList.remove('trace'));
    tracing = false; traceBtn.disabled = false; traceBtn.textContent = '▶ RUN TRACE';
  }
}
traceBtn.addEventListener('click', runTrace);

/* ============ PROJECTS ============ */
const projectsData = {
  vpc: {
    index: 'LOG 001', icon: '🌐', title: 'Custom VPC Architecture', status: 'DEPLOYED', color: 'var(--cyan)',
    desc: '2 public + 2 private subnets across 2 Availability Zones. Bastion host access, NAT Gateway egress, layered NACLs and VPC peering — a production-shaped network built from scratch.',
    tags: ['VPC', 'EC2', 'NAT', 'NACL', 'PEERING'],
    highlights: ['4 subnets across ap-south-1a / 1b with clean CIDR plan', 'Bastion-only SSH into private tier — no public IPs on apps', 'NACLs + Security Groups for defense in depth', 'VPC peering with correctly scoped route tables'],
    log: '$ terraform apply -auto-approve\n…\nApply complete! Resources: 18 added, 0 changed, 0 destroyed.\nOutputs: vpc_id = vpc-0f27a… · subnets = 4 · azs = ap-south-1a/1b'
  },
  static: {
    index: 'LOG 002', icon: '🔐', title: 'Secure Static Website', status: 'LIVE', color: 'var(--violet)',
    desc: 'S3 hosting locked behind a least-privilege bucket policy, fronted by CloudFront with ACM HTTPS and a Route 53 custom domain. Versioning and CORS configured for safe rollbacks.',
    tags: ['S3', 'CLOUDFRONT', 'ACM', 'ROUTE 53'],
    highlights: ['Bucket fully private — CloudFront Origin Access Control only', 'Versioning enabled for instant rollback', 'HTTPS everywhere via ACM certificate + redirect policy', 'Custom domain aliased through Route 53'],
    log: '$ aws s3 sync ./dist s3://at-static-site --delete\nupload: 42 files · 1.8 MB\n$ aws cloudfront create-invalidation --paths "/*"\nInvalidation I3K9… Completed · HTTPS ✓ · OAC ✓'
  },
  iam: {
    index: 'LOG 003', icon: '🛡', title: 'IAM Security Lab', status: 'HARDENED', color: 'var(--magenta)',
    desc: 'A least-privilege playground: scoped policies, root account hardening with MFA, and cross-account access using STS temporary credentials instead of long-lived keys.',
    tags: ['IAM', 'MFA', 'STS'],
    highlights: ['Root account locked down with hardware-grade MFA hygiene', 'Policies written and verified with the IAM policy simulator', 'Cross-account role assumption via STS — credentials expire in 1h', 'Zero wildcard admin policies in the final state'],
    log: '$ aws sts assume-role --role-arn arn:aws:iam::2211…:role/CrossAccountAudit\nCredentials: ASIA… · Expiration: +1h\nAccess Analyzer: 0 unused permissions · MFA: enforced ✓'
  },
  sched: {
    index: 'LOG 004', icon: '⚡', title: 'Serverless EC2 Scheduler', status: 'AUTOMATED', color: 'var(--lime)',
    desc: 'Lambda + EventBridge automatically start and stop EC2 instances on a schedule — cutting off-hours compute cost with a scoped execution role and full CloudWatch observability.',
    tags: ['LAMBDA', 'EVENTBRIDGE', 'CLOUDWATCH'],
    highlights: ['Cron rules for office-hours start / evening stop', 'Execution role scoped to specific instance ARNs only', 'Every run logged and metric-tracked in CloudWatch', 'Zero servers to babysit — fully event-driven'],
    log: '[EventBridge] cron(0 19 * * ? *) → lambda:ec2-scheduler\n[λ] stopped 4 instances · duration 412ms · role: scoped ✓\n[CloudWatch] OffHoursSaved ↑ · alarm state: OK'
  },
  bean: {
    index: 'LOG 005', icon: '📦', title: 'Elastic Beanstalk Deployment', status: 'GREEN', color: 'var(--amber)',
    desc: 'Sample application running on managed Beanstalk environments with auto scaling, load balancing, health monitoring and rolling deployments — platform power without the boilerplate.',
    tags: ['BEANSTALK', 'ELB', 'AUTO SCALING'],
    highlights: ['Managed environment with ALB + Auto Scaling group', 'Rolling deploys with automatic health gating', 'Environment health dashboards and event stream', 'Config-as-code via saved configuration templates'],
    log: '$ eb deploy production-env\nINFO: Environment health has transitioned to Green.\nINFO: Rolling update complete · 2/2 instances InService ✓'
  }
};
const projGrid = $('#projGrid');
Object.entries(projectsData).forEach(([key, p], i) => {
  const card = document.createElement('article');
  card.className = 'proj-card panel' + (key === 'bean' ? ' wide' : '');
  card.style.setProperty('--pc', p.color);
  card.dataset.project = key;
  card.tabIndex = 0; card.setAttribute('role', 'button');
  card.setAttribute('aria-label', 'Open mission file: ' + p.title);
  const tagsHtml = p.tags.map(t => '<span class="chip">' + t + '</span>').join('');
  const core = '<div class="proj-top"><span class="proj-index">' + p.index + '</span><span class="proj-status"><i></i>' + p.status + '</span></div>' +
    '<div class="proj-ico">' + p.icon + '</div>' +
    '<h3 style="margin-top:14px">' + p.title + '</h3><p>' + p.desc + '</p>' +
    '<div class="proj-tags">' + tagsHtml + '</div>' +
    '<button class="proj-open" tabindex="-1">OPEN MISSION FILE <span>→</span></button>';
  if (key === 'bean') {
    card.innerHTML = '<div class="wide-inner"><div class="proj-ico" style="width:64px;height:64px;font-size:30px">' + p.icon + '</div>' +
      '<div><div class="proj-top" style="margin-bottom:8px"><span class="proj-index">' + p.index + '</span><span class="proj-status"><i></i>' + p.status + '</span></div>' +
      '<h3>' + p.title + '</h3><p>' + p.desc + '</p><div class="proj-tags">' + tagsHtml + '</div></div>' +
      '<button class="proj-open" tabindex="-1">OPEN FILE <span>→</span></button></div>';
  } else card.innerHTML = core;
  const open = () => openModal(key, card);
  card.addEventListener('click', open);
  card.addEventListener('keydown', e => { if (e.key === 'Enter' || e.key === ' ') { e.preventDefault(); open(); } });
  projGrid.appendChild(card);
});

/* tilt + spotlight */
if (finePointer && !reduced) {
  $$('.proj-card').forEach(card => {
    card.addEventListener('pointermove', e => {
      const r = card.getBoundingClientRect();
      const px = (e.clientX - r.left) / r.width, py = (e.clientY - r.top) / r.height;
      card.style.setProperty('--mx', (px * 100) + '%');
      card.style.setProperty('--my', (py * 100) + '%');
      card.style.transform = 'perspective(950px) rotateX(' + ((0.5 - py) * 6).toFixed(2) + 'deg) rotateY(' + ((px - 0.5) * 6).toFixed(2) + 'deg) translateY(-4px)';
    });
    card.addEventListener('pointerleave', () => { card.style.transform = ''; });
  });
}

/* modal */
const modalOverlay = $('#modalOverlay'), modalCard = $('#modalCard');
let lastFocusedCard = null;
function openModal(key, card) {
  const p = projectsData[key]; if (!p) return;
  lastFocusedCard = card || null;
  modalCard.style.setProperty('--mc', p.color);
  $('#modalIndex').textContent = 'MISSION FILE · ' + p.index;
  $('#modalTitle').textContent = p.icon + ' ' + p.title;
  $('#modalStatus').innerHTML = '<span class="led" style="background:' + p.color + ';box-shadow:0 0 10px ' + p.color + '"></span>STATUS · ' + p.status;
  $('#modalDesc').textContent = p.desc;
  const list = $('#modalList'); list.innerHTML = '';
  p.highlights.forEach(h => { const li = document.createElement('li'); li.textContent = h; list.appendChild(li); });
  const chips = $('#modalChips'); chips.innerHTML = '';
  p.tags.forEach(t => { const c = document.createElement('span'); c.className = 'chip'; c.textContent = t; chips.appendChild(c); });
  $('#modalLog').textContent = p.log;
  $('#modalLink').href = 'mailto:' + EMAIL + '?subject=' + encodeURIComponent('About your ' + p.title + ' build');
  modalOverlay.classList.add('open');
  modalOverlay.setAttribute('aria-hidden', 'false');
  document.body.style.overflow = 'hidden';
  $('#modalClose').focus();
}
function closeModal() {
  modalOverlay.classList.remove('open');
  modalOverlay.setAttribute('aria-hidden', 'true');
  document.body.style.overflow = '';
  if (lastFocusedCard) lastFocusedCard.focus();
}
$('#modalClose').addEventListener('click', closeModal);
$('#modalDismiss').addEventListener('click', closeModal);
modalOverlay.addEventListener('click', e => { if (e.target === modalOverlay) closeModal(); });
document.addEventListener('keydown', e => {
  if (e.key === 'Escape') {
    if (modalOverlay.classList.contains('open')) closeModal();
    closeMenu();
  }
});

/* ============ FOCUS ============ */
const focusData = [
  ['🏗', 'Terraform IaC', 'Modular VPC + EC2 stacks, remote state, workspaces and clean variable design.', 72, 'var(--cyan)'],
  ['🐳', 'Dockerised Apps', 'Multi-stage builds, compose workflows, slim images and registry pushes.', 65, 'var(--info)'],
  ['🔁', 'GitHub Actions CI/CD', 'Lint → build → push → deploy pipelines with OIDC federation into AWS.', 58, 'var(--magenta)'],
  ['☁', 'Real-World AWS Builds', 'One production-grade architecture shipped every fortnight. Build in public.', 84, 'var(--lime)']
];
const focusList = $('#focusList');
focusData.forEach(([ico, title, desc, pct, color]) => {
  const item = document.createElement('div');
  item.className = 'focus-item panel';
  item.style.setProperty('--fc', color);
  item.innerHTML = '<div class="focus-top"><span class="focus-ico">' + ico + '</span><h3>' + title + '</h3>' +
    '<span class="focus-pct"><span data-count="' + pct + '" data-suffix="%">0%</span></span></div>' +
    '<p>' + desc + '</p><div class="bar"><i data-pct="' + pct + '"></i></div>';
  focusList.appendChild(item);
});

/* ============ COPY ============ */
$$('[data-copy]').forEach(btn => btn.addEventListener('click', async () => {
  const txt = btn.dataset.copy;
  try {
    await navigator.clipboard.writeText(txt);
    toast('Email copied to clipboard', 'ok'); sfx.ok();
  } catch (e) {
    const ta = document.createElement('textarea');
    ta.value = txt; ta.style.position = 'fixed'; ta.style.opacity = '0';
    document.body.appendChild(ta); ta.select();
    try { document.execCommand('copy'); toast('Email copied to clipboard', 'ok'); sfx.ok(); }
    catch (err) { toast('Copy failed — ' + txt, 'err'); }
    ta.remove();
  }
}));

/* ============ TELEMETRY ============ */
const t0 = Date.now();
const pad = n => String(n).padStart(2, '0');
setInterval(() => {
  const s = Math.floor((Date.now() - t0) / 1000);
  $('#uptimeVal').textContent = pad(Math.floor(s / 3600)) + ':' + pad(Math.floor(s / 60) % 60) + ':' + pad(s % 60);
  $('#latencyVal').textContent = (16 + Math.round(Math.random() * 14)) + 'ms';
}, 1200);
})();
</script>
</body>
</html>
