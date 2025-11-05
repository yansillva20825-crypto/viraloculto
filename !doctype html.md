<!doctype html>  
<html lang="pt-BR">  
<head>  
  <meta charset="utf-8" />  
  <meta name="viewport" content="width=device-width,initial-scale=1" />  
  <title>ViralOculto — Faça vídeos virais sem mostrar o rosto</title>  
  <meta name="description" content="ViralOculto: rota rápida para vídeos virais e blogs anônimos. Templates, roteiros, automações e hooks prontos para TikTok, Reels e YouTube Shorts." />  
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">  
  <style>  
    :root{  
      --red:#e31b23;  
      --dark:#0f1720;  
      --muted:#7b8794;  
      --glass: rgba(255,255,255,0.05);  
      --card:#0b1116;  
    }  
    *{box-sizing:border-box}  
    body{  
      margin:0;  
      font-family:Inter,system-ui,Arial;  
      background:linear-gradient(180deg,#05060a 0%, #07111a 100%);  
      color:#e6eef6;  
      -webkit-font-smoothing:antialiased;  
      -moz-osx-font-smoothing:grayscale;  
      line-height:1.45;  
    }  
    .container{max-width:1100px;margin:0 auto;padding:28px}  
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 0}  
    .brand{display:flex;align-items:center;gap:14px}  
    .logo{  
      width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--red),#ff6b6b);  
      display:flex;align-items:center;justify-content:center;font-weight:800;color:white;font-size:20px;  
      box-shadow:0 8px 30px rgba(227,27,35,0.18)  
    }  
    nav a{color: #cfe8ff;text-decoration:none;margin-left:18px;font-weight:600}  
    nav a.cta{background:var(--red);color:white;padding:10px 14px;border-radius:8px}  
    .hero{display:flex;gap:30px;align-items:center;padding:36px 0}  
    .hero-left{flex:1}  
    h1{font-size:36px;margin:0 0 12px 0;line-height:1.02}  
    p.lead{color:var(--muted);font-size:16px;margin:0 0 20px}  
    .badges{display:flex;gap:10px;margin-bottom:18px}  
    .badge{background:var(--card);padding:8px 10px;border-radius:999px;color:#cfe8ff;font-weight:700;font-size:13px}  
    .cta-row{display:flex;gap:12px;flex-wrap:wrap}  
    .btn{background:var(--red);color:white;padding:14px 18px;border-radius:12px;border:none;font-weight:700;cursor:pointer}  
    .btn.ghost{background:transparent;border:2px solid rgba(255,255,255,0.06);color:#fff;padding:12px 16px}  
    .hero-right{flex:1;display:flex;justify-content:center}  
    .card-video{width:100%;max-width:480px;border-radius:18px;overflow:hidden;background:linear-gradient(180deg,#071219,#0b1320);box-shadow:0 20px 60px rgba(3,8,14,0.8);border:1px solid rgba(255,255,255,0.03)}  
    .card-video img{width:100%;display:block}  
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:30px}  
    .feature{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}  
    .feature h3{margin:0 0 8px;font-size:16px;color:#fff}  
    .feature p{color:var(--muted);margin:0;font-size:14px}  
    .pricing{margin-top:36px;display:flex;gap:18px;align-items:stretch}  
    .price-card{background:linear-gradient(180deg,#07111a,#08161d);padding:22px;border-radius:12px;flex:1;border:1px solid rgba(255,255,255,0.03)}  
    .price-card.best{box-shadow:0 18px 50px rgba(227,27,35,0.12);border:1px solid rgba(227,27,35,0.25)}  
    .price{font-size:28px;font-weight:800;color:var(--red);margin:6px 0}  
    .list{margin:12px 0;color:var(--muted);font-size:14px}  
    footer{margin-top:48px;padding:18px 0;color:var(--muted);border-top:1px solid rgba(255,255,255,0.02)}  
    .flex-row{display:flex;gap:12px;align-items:center}  
    .testimonial{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:14px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}  
    .faq{margin-top:28px}  
    .faq h4{margin:6px 0;color:#fff}  
    @media (max-width:900px){  
      .hero{flex-direction:column}  
      .features{grid-template-columns:repeat(2,1fr)}  
      .pricing{flex-direction:column}  
    }  
    @media (max-width:520px){  
      .features{grid-template-columns:1fr}  
    }  
  </style>  
</head>  
<body>  
  <div class="container">  
    <header>  
      <div class="brand">  
        <div class="logo">VO</div>  
        <div>  
          <div style="font-weight:800">ViralOculto</div>  
          <div style="font-size:13px;color:var(--muted)">Viralize sem aparecer • Templates & automações</div>  
        </div>  
      </div>  
      <nav>  
        <a href="#features">Recursos</a>  
        <a href="#pricing">Preços</a>  
        <a href="#testimonials">Provas</a>  
        <a class="cta" href="#signup">Comece AGORA</a>  
      </nav>  
    </header>  
  
    <main>  
      <section class="hero">  
        <div class="hero-left">  
          <div class="badges">  
            <div class="badge">Roteiros que viralizam</div>  
            <div class="badge">Templates prontos</div>  
            <div class="badge">Sem rosto, sem complicação</div>  
          </div>  
  
          <h1>Viralize vídeos e seja blogueiro sem mostrar o rosto</h1>  
          <p class="lead">Receba roteiros, templates de edição, hooks virais e automações para TikTok, Reels e Shorts. Suba conteúdo anônimo que bomba — mesmo se você não souber editar.</p>  
  
          <div class="cta-row">  
            <button class="btn" onclick="document.getElementById('signup').scrollIntoView({behavior:'smooth'})">Quero Viralizar (GRÁTIS)</button>  
            <button class="btn ghost" onclick="document.getElementById('pricing').scrollIntoView({behavior:'smooth'})">Ver Planos</button>  
          </div>  
  
          <div style="margin-top:18px;color:var(--muted);font-size:13px">  
            +60.000 hooks testados • 1 mês de estratégias entregues por e-mail  
          </div>  
  
          <div id="features" class="features" style="margin-top:24px">  
            <div class="feature">  
              <h3>Roteiros prontos & adaptáveis</h3>  
              <p>Cópia e roteiro para 100+ formatos: narração, texto dinâmico, montagem. Só copiar e colar.</p>  
            </div>  
            <div class="feature">  
              <h3>Templates de edição</h3>  
              <p>Projetos .premiere / .capcut / .vn / .canva com animações que prendem atenção.</p>  
            </div>  
            <div class="feature">  
              <h3>Automação & agendamento</h3>  
              <p>Fluxo recomendado para publicar no melhor horário com descrições e hashtags prontas.</p>  
            </div>  
          </div>  
        </div>  
  
        <div class="hero-right">  
          <div class="card-video">  
            <img src="https://via.placeholder.com/900x500/111827/ffffff?text=Vídeo+Demonstração" alt="demonstração">  
          </div>  
        </div>  
      </section>  
  
      <section style="margin-top:30px">  
        <div style="display:flex;gap:16px;flex-wrap:wrap;align-items:center;justify-content:space-between">  
          <div style="max-width:640px">  
            <h2 style="margin:0 0 8px 0">O que você recebe</h2>  
            <p style="color:var(--muted);margin:0">Tudo pronto para você criar conteúdo que viraliza — mesmo sem mostrar rosto, voz ou identidade.</p>  
          </div>  
          <div style="display:flex;gap:10px;align-items:center">  
            <div class="testimonial">  
              <strong>+10k</strong> seguidores médios em 30 dias  
            </div>  
            <div class="testimonial">  
              <strong>85%</strong> dos roteiros testados viralizaram  
            </div>  
          </div>  
        </div>  
  
        <div class="pricing" id="pricing">  
          <div class="price-card">  
            <div style="font-weight:800">Starter</div>  
            <div class="price">R$27/mês</div>  
            <div class="list">• 20 roteiros mensais<br>• 15 templates de edição<br>• Checklist de SEO para Reels</div>  
            <div style="margin-top:12px"><button class="btn" onclick="alert('Iniciar Starter')">Assinar Starter</button></div>  
          </div>  
  
          <div class="price-card best">  
            <div style="font-weight:800">Pro (Recomendado)</div>  
            <div class="price">R$67/mês</div>  
            <div class="list">• 60+ roteiros mensais<br>• Projetos editáveis + pack de sons<br>• Automação + descrição/hashtags testadas</div>  
            <div style="margin-top:12px"><button class="btn" onclick="alert('Iniciar Pro')">Assinar Pro</button></div>  
          </div>  
  
          <div class="price-card">  
            <div style="font-weight:800">Agency</div>  
            <div class="price">R$197/mês</div>  
            <div class="list">• Tudo do Pro<br>• Scripts exclusivos por nicho<br>• Consultoria 1x mês</div>  
            <div style="margin-top:12px"><button class="btn" onclick="alert('Iniciar Agency')">Assinar Agency</button></div>  
          </div>  
        </div>  
      </section>  
  
      <section style="margin-top:36px" id="testimonials">  
        <h2 style="margin-bottom:8px">Depoimentos reais</h2>  
        <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:12px">  
          <blockquote class="testimonial">  
            <strong>@anon_creator</strong>  
            <p style="color:var(--muted);margin:6px 0 0">Passei de 0 a 12k com 7 vídeos em 10 dias — tudo sem mostrar o rosto.</p>  
          </blockquote>  
          <blockquote class="testimonial">  
            <strong>Juliana (nicho recipes)</strong>  
            <p style="color:var(--muted);margin:6px 0 0">Os templates aceleraram minha edição. Viral direto.</p>  
          </blockquote>  
          <blockquote class="testimonial">  
            <strong>Lucas M.</strong>  
            <p style="color:var(--muted);margin:6px 0 0">O pack de hooks é ouro — cada roteiro tem CTA embutido que funciona.</p>  
          </blockquote>  
        </div>  
      </section>  
  
      <section class="faq">  
        <h3>Perguntas frequentes</h3>  
        <div style="margin-top:12px">  
          <h4>Preciso aparecer ou usar minha voz?</h4>  
          <p style="color:var(--muted);margin:6px 0">Não. Oferecemos roteiros e formatos 100% text-to-video, narração por TTS e ideias de b-roll para ocultar identidade.</p>  
  
          <h4>Os roteiros funcionam em qualquer nicho?</h4>  
          <p style="color:var(--muted);margin:6px 0">Sim — há pacotes por nicho (entretenimento, culinária, curiosidades, finanças, mods, etc.).</p>  
  
          <h4>Tem garantia?</h4>  
          <p style="color:var(--muted);margin:6px 0">30 dias de garantia: se não ficar satisfeito, devolvemos.</p>  
        </div>  
      </section>  
  
      <section id="signup" style="margin-top:34px;padding:20px;border-radius:12px;background:linear-gradient(180deg, rgba(227,27,35,0.06), rgba(255,255,255,0.01));display:flex;gap:18px;align-items:center;justify-content:space-between">  
        <div>  
          <h3 style="margin:0">Comece grátis — receba 7 roteiros que viralizam</h3>  
          <p style="color:var(--muted);margin:6px 0 0">Insira seu e-mail e receba imediatamente o pack de boas-vindas.</p>  
        </div>  
        <form onsubmit="event.preventDefault();alert('E-mail recebido! Checar inbox.');" style="display:flex;gap:8px;align-items:center">  
          <input required type="email" placeholder="seu@email.com" style="padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:#fff"/>  
          <button class="btn" type="submit">Quero os Roteiros</button>  
        </form>  
