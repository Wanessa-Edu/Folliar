import { useState } from "react";

/* ─────────────────────────────────────────────
   FOLIAR MVP — Interactive Product Document
   Aesthetic: Dark editorial, warm paper tones,
   literary serif + clean sans. Letterboxd-meets-
   Notion with an indie-press soul.
───────────────────────────────────────────── */

const G = `
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,500;0,700;1,500&family=Outfit:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap');

*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}

:root{
  --bg:#0F0D0B;
  --bg2:#161310;
  --bg3:#1E1A16;
  --bg4:#252018;
  --line:#2E2820;
  --line2:#3A3028;
  --muted:#6B5E50;
  --soft:#9B8B7A;
  --text:#E8DDD0;
  --bright:#F5EDE0;
  --sage:#5C8A68;
  --sage2:#7BAF89;
  --sage3:#A8CCB0;
  --sage-glow:rgba(92,138,104,0.15);
  --amber:#B8813A;
  --amber2:#D4A055;
  --amber3:#F0C878;
  --rust:#8B3A28;
  --rust2:#C05030;
  --sky:#3A6B8A;
  --sky2:#5B8FAF;
  --r:8px;--rl:14px;--rxl:20px;
}

body{font-family:'Outfit',sans-serif;background:var(--bg);color:var(--text);line-height:1.6;min-height:100vh}

/* ── LAYOUT ── */
.shell{display:flex;min-height:100vh}
.rail{width:200px;min-height:100vh;background:var(--bg2);border-right:1px solid var(--line);position:fixed;top:0;left:0;display:flex;flex-direction:column;z-index:50}
.rail-logo{padding:22px 20px 18px;border-bottom:1px solid var(--line)}
.logotype{font-family:'Playfair Display',serif;font-size:20px;font-weight:700;color:var(--bright);letter-spacing:-.3px}
.logotype span{color:var(--sage2)}
.logo-tag{font-size:9px;letter-spacing:2.5px;text-transform:uppercase;color:var(--muted);margin-top:2px}
.rail-nav{padding:12px 0;flex:1}
.ni{display:flex;align-items:center;gap:9px;padding:8px 20px;font-size:12px;font-weight:500;color:var(--muted);cursor:pointer;border-left:2px solid transparent;transition:.15s all;letter-spacing:.2px}
.ni:hover{color:var(--text);background:var(--bg3)}
.ni.on{color:var(--sage3);border-left-color:var(--sage);background:var(--sage-glow)}
.ni-ic{font-size:13px;opacity:.7}
.rail-foot{padding:16px 20px;border-top:1px solid var(--line)}
.rail-badge{background:var(--sage-glow);border:1px solid var(--sage);border-radius:6px;padding:8px 10px;font-size:10px;color:var(--sage3);line-height:1.5}

.page{margin-left:200px;padding:48px 52px;max-width:1080px}
@keyframes up{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
.fade{animation:up .3s ease}

/* ── TYPE ── */
.stag{font-size:10px;font-weight:600;letter-spacing:3px;text-transform:uppercase;color:var(--sage2);margin-bottom:8px}
.stitle{font-family:'Playfair Display',serif;font-size:32px;font-weight:700;color:var(--bright);line-height:1.2;letter-spacing:-.4px}
.sdesc{font-size:14px;color:var(--soft);line-height:1.75;margin-top:10px;max-width:640px;margin-bottom:36px}
h3{font-family:'Playfair Display',serif;font-size:17px;font-weight:500;color:var(--bright);margin-bottom:4px}
p.small{font-size:13px;color:var(--soft);line-height:1.7}

/* ── CARDS ── */
.card{background:var(--bg2);border:1px solid var(--line);border-radius:var(--rl);padding:24px 28px;margin-bottom:18px}
.card.glow{border-color:var(--sage);box-shadow:0 0 0 1px var(--sage-glow),0 4px 24px rgba(0,0,0,.4)}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.g3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:14px}

/* ── DIVIDER ── */
hr{border:none;border-top:1px solid var(--line);margin:28px 0}

/* ── PILL ── */
.pill{display:inline-flex;align-items:center;padding:3px 10px;border-radius:99px;font-size:11px;font-weight:500;gap:4px}
.p-sage{background:rgba(92,138,104,.15);color:var(--sage3);border:1px solid rgba(92,138,104,.3)}
.p-amber{background:rgba(184,129,58,.12);color:var(--amber3);border:1px solid rgba(184,129,58,.25)}
.p-rust{background:rgba(139,58,40,.15);color:#F0907A;border:1px solid rgba(139,58,40,.3)}
.p-sky{background:rgba(58,107,138,.15);color:#90C4E0;border:1px solid rgba(58,107,138,.3)}
.p-dim{background:var(--bg3);color:var(--soft);border:1px solid var(--line2)}

/* ── LIST ── */
ul.dot{list-style:none}
ul.dot li{padding:6px 0 6px 16px;position:relative;font-size:13.5px;color:var(--soft);border-bottom:1px solid var(--line);line-height:1.6}
ul.dot li:last-child{border-bottom:none}
ul.dot li::before{content:'';position:absolute;left:0;top:14px;width:5px;height:5px;border-radius:50%;background:var(--sage)}

/* ── TABLE ── */
table.dt{width:100%;border-collapse:collapse;font-size:12.5px}
table.dt th{background:var(--bg3);color:var(--soft);padding:9px 14px;text-align:left;font-weight:500;font-size:11px;letter-spacing:.5px;border-bottom:1px solid var(--line2)}
table.dt td{padding:9px 14px;border-bottom:1px solid var(--line);color:var(--soft);vertical-align:top}
table.dt tr:hover td{background:var(--bg3)}

/* ── CODE ── */
.code{background:var(--bg);border:1px solid var(--line2);border-radius:var(--r);padding:16px 20px;font-family:'JetBrains Mono',monospace;font-size:12px;line-height:1.8;overflow-x:auto;white-space:pre}
.cg{color:#86EFAC}.ca{color:#FCD34D}.cb{color:#93C5FD}.cp{color:#F9A8D4}.cm{color:#6B7280}.cw{color:#F9FAFB}.co{color:#FDBA74}

/* ── ENTITY ── */
.ent{background:var(--bg);border:1px solid var(--line2);border-radius:var(--r);overflow:hidden}
.ent-h{background:var(--bg3);padding:9px 16px;font-family:'JetBrains Mono',monospace;font-size:12.5px;display:flex;align-items:center;gap:8px;border-bottom:1px solid var(--line2)}
.ent-row{display:flex;align-items:center;gap:10px;padding:7px 16px;border-bottom:1px solid var(--line);font-size:12px}
.ent-row:last-child{border-bottom:none}
.ef{font-family:'JetBrains Mono',monospace;color:var(--text);flex:1}
.et{font-family:'JetBrains Mono',monospace;color:var(--amber2);font-size:11px}
.en{color:var(--muted);font-size:11px}
.epk{background:var(--amber);color:#000;font-size:8px;padding:1px 5px;border-radius:3px;font-weight:700}
.efk{background:var(--sky);color:#fff;font-size:8px;padding:1px 5px;border-radius:3px;font-weight:700}

/* ── SPRINT ── */
.sprint{border-left:2px solid var(--sage);padding-left:20px;margin-bottom:26px}
.sp-lbl{font-size:10px;font-weight:600;letter-spacing:2.5px;text-transform:uppercase;color:var(--sage2);margin-bottom:3px}
.sp-title{font-family:'Playfair Display',serif;font-size:15px;color:var(--bright);margin-bottom:10px}
.tk{display:flex;align-items:flex-start;gap:8px;padding:6px 0;font-size:13px;color:var(--soft);border-bottom:1px solid var(--line)}
.tk:last-child{border-bottom:none}
.tk-dot{width:5px;height:5px;border-radius:50%;background:var(--sage);margin-top:8px;flex-shrink:0}

/* ── FEATURE ROW ── */
.fr{display:flex;gap:14px;padding:14px 0;border-bottom:1px solid var(--line);align-items:flex-start}
.fr:last-child{border-bottom:none}
.fic{width:36px;height:36px;border-radius:9px;background:var(--bg3);border:1px solid var(--line2);display:flex;align-items:center;justify-content:center;font-size:16px;flex-shrink:0}
.fn{font-size:13.5px;font-weight:600;color:var(--bright);margin-bottom:3px}
.fd{font-size:12.5px;color:var(--soft);line-height:1.6}

/* ── PROGRESS ── */
.pbar{background:var(--bg3);height:5px;border-radius:99px;overflow:hidden}
.pfill{height:100%;border-radius:99px;background:var(--sage)}

/* ── COMMENT DEMO ── */
.cmmt{display:flex;gap:10px;padding:12px 0;border-bottom:1px solid var(--line)}
.av{width:30px;height:30px;border-radius:50%;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:600;color:#fff}
.cmeta{font-size:11px;color:var(--muted);margin-bottom:3px}
.ctext{font-size:13px;color:var(--soft);line-height:1.6}
.blurred{filter:blur(5px);cursor:pointer;background:var(--bg3);border-radius:4px;padding:0 4px;transition:filter .25s}
.blurred:hover{filter:blur(0)}
.sp-warn{display:inline-flex;align-items:center;gap:4px;background:rgba(139,58,40,.2);border:1px solid rgba(192,80,48,.3);color:#F0907A;border-radius:4px;font-size:10px;font-weight:600;padding:1px 7px;margin-left:6px}

/* ── STACK ITEM ── */
.si{display:flex;align-items:flex-start;gap:12px;padding:14px;background:var(--bg2);border:1px solid var(--line);border-radius:var(--r)}
.sic{width:38px;height:38px;border-radius:9px;background:var(--bg3);display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0}
.sn{font-size:13px;font-weight:600;color:var(--bright)}
.sl{font-size:9.5px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;color:var(--sage2);margin:2px 0}
.sw{font-size:12px;color:var(--muted);line-height:1.5}

/* ── BUTTONS ── */
.btn{display:inline-flex;align-items:center;gap:7px;padding:9px 18px;border-radius:var(--r);font-size:12.5px;font-weight:500;cursor:pointer;border:none;font-family:'Outfit',sans-serif;transition:.15s all}
.b-sage{background:var(--sage);color:#fff}.b-sage:hover{background:var(--sage2)}
.b-out{background:transparent;border:1px solid var(--line2);color:var(--soft)}.b-out:hover{border-color:var(--sage);color:var(--sage3)}
.b-ghost{background:transparent;color:var(--muted);padding:9px 12px}.b-ghost:hover{color:var(--text);background:var(--bg3);border-radius:var(--r)}

/* ── METRIC ── */
.met{text-align:center;padding:22px 14px;background:var(--bg2);border:1px solid var(--line);border-radius:var(--r)}
.mv{font-family:'Playfair Display',serif;font-size:36px;font-weight:700;color:var(--sage3);letter-spacing:-1px}
.ml{font-size:11px;color:var(--muted);margin-top:4px;line-height:1.4}

/* ── INFO ROW ── */
.ir{display:flex;gap:8px;padding:9px 0;border-bottom:1px solid var(--line);font-size:13px}
.ir:last-child{border-bottom:none}
.ik{color:var(--muted);width:180px;flex-shrink:0;font-size:12.5px}
.iv{color:var(--soft)}

/* ── SCREEN TABS ── */
.stabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:22px}
.stab{padding:6px 14px;border-radius:99px;font-size:11.5px;font-weight:500;cursor:pointer;border:1px solid var(--line2);color:var(--muted);transition:.15s all;background:transparent}
.stab:hover{border-color:var(--line2);color:var(--text)}
.stab.on{background:var(--sage-glow);border-color:var(--sage);color:var(--sage3)}

/* ── ROADMAP PHASES ── */
.phase-row{display:flex;border-radius:var(--r);overflow:hidden;border:1px solid var(--line)}
.phase{flex:1;padding:16px 14px}
.ph{font-weight:700;font-size:12px;margin-bottom:5px;color:#fff}
.pd{font-size:11.5px;line-height:1.5;color:rgba(255,255,255,.65)}

/* ── QUOTE ── */
blockquote{border-left:2px solid var(--sage);padding:12px 18px;background:var(--sage-glow);border-radius:0 8px 8px 0;font-family:'Playfair Display',serif;font-size:15px;font-style:italic;color:var(--text);line-height:1.7;margin:14px 0}

/* ── SWATCHES ── */
.sw-wrap{display:flex;gap:12px;flex-wrap:wrap}
.swatch{width:76px}
.sc{height:48px;border-radius:8px;border:1px solid var(--line2);margin-bottom:6px}
.sn2{font-size:10.5px;font-weight:600;color:var(--soft)}
.sh{font-family:'JetBrains Mono',monospace;font-size:9.5px;color:var(--muted)}

/* ── SCREEN WIREFRAME PREVIEW ── */
.wf-shell{background:var(--bg);border:1px solid var(--line2);border-radius:var(--rl);overflow:hidden}
.wf-bar{background:var(--bg3);height:32px;display:flex;align-items:center;padding:0 14px;gap:6px;border-bottom:1px solid var(--line)}
.wf-d{width:8px;height:8px;border-radius:50%;background:var(--line2)}
.wf-url{flex:1;background:var(--line);border-radius:3px;height:16px;margin:0 16px}
.wf-body{padding:18px}

/* ── PITCH HERO ── */
.pitch-hero{background:linear-gradient(135deg,var(--bg2) 0%,var(--bg3) 100%);border:1px solid var(--sage);border-radius:var(--rxl);padding:40px 44px;margin-bottom:20px;position:relative;overflow:hidden}
.pitch-hero::before{content:'';position:absolute;top:-40px;right:-40px;width:200px;height:200px;border-radius:50%;background:var(--sage-glow);filter:blur(40px)}
.pitch-quote{font-family:'Playfair Display',serif;font-size:22px;font-weight:700;color:var(--bright);line-height:1.45;max-width:560px;position:relative}
.pitch-quote em{color:var(--sage3);font-style:italic}
`;

/* ── NAV DATA ── */
const NAV = [
  {id:"brand",    label:"Produto",      ic:"◈"},
  {id:"screens",  label:"Telas",         ic:"⬚"},
  {id:"features", label:"Funcionalidades",ic:"⊕"},
  {id:"tech",     label:"Tecnologias",   ic:"◎"},
  {id:"db",       label:"Banco de Dados",ic:"▣"},
  {id:"roadmap",  label:"Roadmap",       ic:"◷"},
  {id:"pitch",    label:"Pitch Final",   ic:"◆"},
];

/* ── HELPERS ── */
function Pill({ch,t="p-sage"}){return <span className={"pill "+t}>{ch}</span>}
function H({tag,title,desc}){
  return(
    <div>
      <div className="stag">{tag}</div>
      <div className="stitle">{title}</div>
      {desc&&<div className="sdesc">{desc}</div>}
    </div>
  )
}
function Card({title,sub,ch,style,glow}){
  return(
    <div className={"card"+(glow?" glow":"")} style={style}>
      {title&&<h3 style={{marginBottom:sub?4:16}}>{title}</h3>}
      {sub&&<p className="small" style={{marginBottom:16}}>{sub}</p>}
      {ch}
    </div>
  )
}
function UL({items}){
  return(
    <ul className="dot">
      {items.map((it,i)=><li key={i} dangerouslySetInnerHTML={{__html:it}}/>)}
    </ul>
  )
}
function FR({icon,name,desc}){
  return(
    <div className="fr">
      <div className="fic">{icon}</div>
      <div><div className="fn">{name}</div><div className="fd">{desc}</div></div>
    </div>
  )
}

/* ══════════════════════════════════════════
   SECTIONS
══════════════════════════════════════════ */

function Brand(){
  return(
    <div>
      <H tag="01 — Produto" title="Estrutura do Produto" desc="Conceito, proposta de valor e identidade visual que tornam o Foliar reconhecível e memorável."/>

      <div className="g2">
        <Card title="Conceito" ch={
          <>
            <p className="small" style={{marginBottom:14}}>
              O <strong style={{color:"var(--bright)"}}>Foliar</strong> é a plataforma que centraliza toda a experiência de um clube de leitura: do cronograma ao debate, do progresso individual à memória coletiva — tudo em um único lugar, sem spoilers e sem caos.
            </p>
            <div style={{display:"flex",gap:8,flexWrap:"wrap"}}>
              <Pill ch="📖 Leitura coletiva"/>
              <Pill ch="🛡️ Anti-spoiler" t="p-amber"/>
              <Pill ch="💬 Debates organizados" t="p-sky"/>
            </div>
          </>
        }/>
        <Card title="Proposta de Valor" ch={
          <>
            <blockquote style={{marginTop:0,marginBottom:14}}>"Leia junto. Fale na hora certa."</blockquote>
            <UL items={[
              "Fim dos spoilers acidentais no grupo",
              "Cronograma de leitura com marcos claros",
              "Debates organizados por capítulo",
              "Histórico permanente do clube",
              "Tudo em uma plataforma — não dez"
            ]}/>
          </>
        }/>
      </div>

      <Card title="Paleta de Cores" sub="Escura, literária e distinta. Inspirada em tinta, papel envelhecido e folhas de livros antigos." ch={
        <div className="sw-wrap">
          {[
            ["Ink Dark","#0F0D0B"],["Surface","#1E1A16"],["Sage","#5C8A68"],
            ["Sage Light","#7BAF89"],["Amber","#B8813A"],["Amber Light","#D4A055"],
            ["Text","#E8DDD0"],["Muted","#6B5E50"],["Rust","#C05030"]
          ].map(([n,h])=>(
            <div className="swatch" key={n}>
              <div className="sc" style={{background:h}}/>
              <div className="sn2">{n}</div>
              <div className="sh">{h}</div>
            </div>
          ))}
        </div>
      }/>

      <div className="g2">
        <Card title="Tipografia" ch={
          <>
            <div style={{marginBottom:14}}>
              <div style={{fontFamily:"Playfair Display,serif",fontSize:24,fontWeight:700,color:"var(--bright)",marginBottom:3}}>Playfair Display</div>
              <p className="small">Títulos e headings — personalidade literária e autoridade editorial</p>
            </div>
            <div style={{marginBottom:14}}>
              <div style={{fontFamily:"Outfit,sans-serif",fontSize:18,color:"var(--text)",marginBottom:3}}>Outfit</div>
              <p className="small">Interface, botões, corpo — moderno, legível, neutro</p>
            </div>
            <div>
              <div style={{fontFamily:"JetBrains Mono,monospace",fontSize:13,color:"var(--sage3)",marginBottom:3}}>JetBrains Mono</div>
              <p className="small">Dados, badges, código — precisão e clareza técnica</p>
            </div>
          </>
        }/>
        <Card title="Tom de Voz" ch={
          <UL items={[
            "<strong style='color:var(--bright)'>Acolhedor</strong> — como uma livraria independente",
            "<strong style='color:var(--bright)'>Direto</strong> — sem excesso de texto",
            "<strong style='color:var(--bright)'>Inteligente</strong> — sem ser pedante",
            "<strong style='color:var(--bright)'>Empolgante</strong> — celebra a leitura",
            "<strong style='color:var(--bright)'>Inclusivo</strong> — todo tipo de leitor"
          ]}/>
        }/>
      </div>
    </div>
  )
}

/* ── SCREENS ── */
function Screens(){
  const [sc,setSc]=useState("dashboard")
  const LIST=[
    {id:"landing",    label:"Landing Page"},
    {id:"auth",       label:"Login / Cadastro"},
    {id:"dashboard",  label:"Dashboard"},
    {id:"club",       label:"Página do Clube"},
    {id:"book",       label:"Livro Atual"},
    {id:"feed",       label:"Feed de Comentários"},
    {id:"profile",    label:"Perfil"},
  ]
  const DATA={
    landing:{
      goal:"Converter visitantes em usuários. Copy emocional + prova social + CTA claro.",
      components:["Hero: headline + mockup animado","Seção dores → solução","Social proof (clubes ativos)","3 features em destaque","CTA: Criar clube grátis","Rodapé com links"],
      ux:"Above the fold resolve 'o que é isso e por que preciso?'. Scroll revela features progressivamente. CTA verde contrasta com o fundo escuro.",
      microcopy:["\"Seu clube merece mais que um grupo de WhatsApp\"","\"Comece grátis — sem cartão\"","\"1.200+ leitores organizados\""]
    },
    auth:{
      goal:"Cadastro em menos de 60s. Login social como opção principal.",
      components:["OAuth Google (CTA primário)","Form 3 campos (email, nome, senha)","Seletor de interesses literários (opcional)","Link para login se já tem conta"],
      ux:"Mínimo de fricção. Perfil completo é incentivado depois via gamificação, não forçado aqui. Animação suave entre os estados.",
      microcopy:["\"Crie sua conta de leitor\"","\"Que tipos de livro você curte? (pode pular)\"","\"Já tem conta? Entre →\""]
    },
    dashboard:{
      goal:"Hub central: responde 'onde estou?' e 'o que faço agora?'.",
      components:["Saudação personalizada + horário","Cards de clubes ativos (capa, %, membros)","Feed de atividade recente","Próximas datas do cronograma","Streak de leitura","Quick actions"],
      ux:"2 colunas: clubes e agenda à esquerda, feed à direita. Card de clube mostra capa do livro como plano de fundo com overlay.",
      microcopy:["\"Boa tarde, Ana 👋 Você está 3 capítulos atrás\"","\"2 novos comentários no cap. 12 (você já chegou lá!)\""]
    },
    club:{
      goal:"Hub do clube: identidade, membros, livro atual, histórico.",
      components:["Header: nome, cover, descrição","Grid de membros com progress bar","Livro atual em destaque","Timeline de rodadas anteriores","Votação do próximo livro","Botão de convite"],
      ux:"Livro atual domina o topo. Membros com avatares e barras de progresso individuais. Histórico em linha do tempo visual.",
      microcopy:["\"12 de 14 membros estão lendo\"","\"Votação aberta — 4 dias restantes\"","\"Próximo encontro: sexta 19h\""]
    },
    book:{
      goal:"Experiência completa em torno do livro: info + progresso + acesso ao debate.",
      components:["Capa + metadados (Google Books)","Barra de progresso coletiva","Cronograma de capítulos com datas","Feed filtrado por capítulo","Botão 'Registrar progresso'","Citações em destaque"],
      ux:"Visual centrado na capa. Cronograma como eixo da tela — cada marco mostra quantos membros chegaram lá.",
      microcopy:["\"Cap. 15/28 — você está no ritmo!\"","\"7 membros chegaram no cap. 20. Cuidado!\""]
    },
    feed:{
      goal:"Coração da plataforma: debates assíncronos protegidos contra spoilers.",
      components:["Filtro por capítulo","Campo de comentário com âncora","Cards com avatar + reações","Blur automático em spoilers","Botão 'Revelar spoiler'","Thread de 2 níveis"],
      ux:"Comentários além do seu progresso ficam com blur + aviso. Reações temáticas rápidas. Thread colapsável.",
      microcopy:["\"⚠️ Spoiler do Cap. 18 — você ainda não chegou lá. Revelar?\"","\"Ana comentou onde você leu ontem\""]
    },
    profile:{
      goal:"Identidade do leitor: estatísticas, histórico e memória pessoal.",
      components:["Foto + bio","Stats: livros, clubes, capítulos","Citações favoritas","Grid de capas lidas","Badges conquistados","Clubes que participa"],
      ux:"Estética de estante virtual. Grid de capas. Badges sutis. Citações em destaque editorial.",
      microcopy:["\"12 livros lidos com o Foliar\"","\"Membro desde março 2025\""]
    },
  }
  const s=DATA[sc]
  return(
    <div>
      <H tag="02 — Telas" title="Telas Principais" desc="7 telas com objetivo, componentes, UX e microcopys definidos."/>
      <div className="stabs">
        {LIST.map(item=>(
          <button key={item.id} className={"stab"+(sc===item.id?" on":"")} onClick={()=>setSc(item.id)}>{item.label}</button>
        ))}
      </div>
      <Card title={LIST.find(x=>x.id===sc)?.label} ch={
        <div className="g2" style={{gap:24}}>
          <div>
            <div style={{fontSize:10,fontWeight:600,letterSpacing:2.5,textTransform:"uppercase",color:"var(--sage2)",marginBottom:8}}>Objetivo</div>
            <p className="small" style={{marginBottom:20}}>{s.goal}</p>
            <div style={{fontSize:10,fontWeight:600,letterSpacing:2.5,textTransform:"uppercase",color:"var(--sage2)",marginBottom:8}}>Componentes</div>
            <UL items={s.components}/>
          </div>
          <div>
            <div style={{fontSize:10,fontWeight:600,letterSpacing:2.5,textTransform:"uppercase",color:"var(--sage2)",marginBottom:8}}>Decisões de UX</div>
            <p className="small" style={{marginBottom:20}}>{s.ux}</p>
            <div style={{fontSize:10,fontWeight:600,letterSpacing:2.5,textTransform:"uppercase",color:"var(--sage2)",marginBottom:8}}>Microcopys</div>
            <div style={{display:"flex",flexDirection:"column",gap:8}}>
              {s.microcopy.map((m,i)=>(
                <div key={i} style={{background:"var(--bg3)",border:"1px solid var(--line2)",borderRadius:8,padding:"10px 14px",fontSize:12.5,color:"var(--soft)",fontStyle:"italic"}}>{m}</div>
              ))}
            </div>
          </div>
        </div>
      }/>

      {sc==="feed"&&(
        <Card title="Preview: Spoiler-Gate em Ação" sub="Comentários além do seu progresso ficam bloqueados — revelação é sempre consciente e voluntária." ch={
          <div>
            {[
              {n:"Ana Lima",ch:10,t:"A cena da carta me pegou de surpresa. Não esperava!",c:"#5C8A68",i:"AL",bl:false},
              {n:"Bruno M.",ch:12,t:"Quando ela percebe que sempre soube... isso muda tudo.",c:"#B8813A",i:"BM",bl:false},
              {n:"Carla S.",ch:18,t:"O final do capítulo 18 é de partir o coração.",c:"#8B3A28",i:"CS",bl:true},
            ].map((cm,i)=>(
              <div className="cmmt" key={i}>
                <div className="av" style={{background:cm.c}}>{cm.i}</div>
                <div style={{flex:1}}>
                  <div className="cmeta">{cm.n} · Cap. {cm.ch} · há 2h{cm.bl&&<span className="sp-warn">⚠ Spoiler</span>}</div>
                  <div className={"ctext"+(cm.bl?" blurred":"")} title={cm.bl?"Passe o mouse para revelar":""}>{cm.t}</div>
                  {cm.bl&&<div style={{fontSize:11,color:"var(--muted)",marginTop:4}}>Você está no Cap. 15 — passe o mouse para revelar</div>}
                </div>
              </div>
            ))}
          </div>
        }/>
      )}

      {sc==="dashboard"&&(
        <Card title="Preview: Cards de Clube" ch={
          <div style={{display:"grid",gridTemplateColumns:"repeat(3,1fr)",gap:12}}>
            {[["Clube das Quintas","Cem Anos de Solidão",8,67,"#5C8A68"],["Leitoras da Vila","Normal People",5,43,"#B8813A"],["BookNerd Brasil","A Cor Púrpura",14,89,"#8B3A28"]].map(([t,b,m,p,c])=>(
              <div key={t} style={{background:"var(--bg3)",border:"1px solid var(--line2)",borderRadius:12,overflow:"hidden",cursor:"pointer"}}>
                <div style={{height:4,background:c}}/>
                <div style={{padding:14}}>
                  <div style={{fontSize:13,fontWeight:600,color:"var(--bright)",marginBottom:2}}>{t}</div>
                  <div style={{fontSize:11,color:"var(--muted)",marginBottom:12}}>{b}</div>
                  <div className="pbar" style={{marginBottom:7}}><div className="pfill" style={{width:p+"%",background:c}}/></div>
                  <div style={{display:"flex",justifyContent:"space-between",fontSize:10,color:"var(--muted)"}}>
                    <span>👥 {m}</span><span>{p}%</span>
                  </div>
                </div>
              </div>
            ))}
          </div>
        }/>
      )}
    </div>
  )
}

/* ── FEATURES ── */
function Features(){
  const items=[
    ["🏛️","Criação de Clubes","Criação em 3 passos: nome + descrição + convite. Público, privado ou por link. Limite de 20 membros no plano gratuito."],
    ["📅","Rodadas de Leitura","Cada livro é uma rodada com data de início, data-alvo e cronograma de capítulos. Uma rodada ativa por vez no MVP."],
    ["🗳️","Votação do Próximo Livro","Organizador cadastra até 4 opções. Membros votam em 48h. Resultado automático ou escolha direta."],
    ["📊","Progresso por Capítulo","Usuário atualiza o capítulo atual em segundos. Sistema calcula % individual e coletiva. Histórico salvo por data."],
    ["🛡️","Bloqueio Inteligente de Spoilers","Cada comentário tem um campo 'capítulo referência'. Se o leitor não chegou lá, o texto fica com blur + aviso claro."],
    ["💬","Comentários por Trecho","Além do feed geral, o usuário ancora comentários em capítulos específicos. Threads de 2 níveis."],
    ["❤️","Reações Literárias","5 reações temáticas: 📚 favorito, 🤔 pensativo, ❤️ amou, 😮 surpreso, 🔥 intenso."],
    ["📖","Histórico do Clube","Rodadas encerradas viram registros permanentes: debates, citações e avaliações. Exportável como PDF."],
  ]
  return(
    <div>
      <H tag="03 — MVP" title="Funcionalidades do MVP" desc="8 funcionalidades priorizadas. Cada uma resolve uma dor real do usuário."/>
      <Card ch={items.map(([ic,n,d])=><FR key={n} icon={ic} name={n} desc={d}/>)}/>
      <Card title="Lógica do Spoiler-Gate" sub="O diferencial técnico do Foliar em uma única regra de negócio." glow ch={
        <div className="code">
<span className="cm">{"// Back-end: GET /rounds/:id/comments"}</span>
<span className="cp">{"function"}</span>{" "}<span className="cb">{"filterComments"}</span>{"(comments, userProgress) {"}
{"  "}<span className="cp">{"return"}</span>{" comments."}<span className="cb">{"map"}</span>{"(c => {"}
{"    "}<span className="cp">{"const"}</span>{" ok = c.chapter_ref "}<span className="cp">{"<="}</span>{" userProgress.current_chapter;"}
{"    "}<span className="cp">{"return"}</span>{" { ...c,"}
{"      "}<span className="ca">{"text"}</span>{": ok ? c.text : "}<span className="cg">{"null"}</span>{","}
{"      "}<span className="ca">{"is_blocked"}</span>{": !ok,"}
{"      "}<span className="ca">{"spoiler_chapter"}</span>{": !ok ? c.chapter_ref : "}<span className="cg">{"null"}</span>
{"    };"}
{"  });"}
{"}"}
        </div>
      }/>
    </div>
  )
}

/* ── TECH ── */
function Tech(){
  const stack=[
    ["⚛️","React + Vite","Front-end","Componentes reativos, hot reload, Tailwind CSS. Ecossistema amplo, alta demanda no mercado."],
    ["🟩","Node.js + Express","Back-end","JavaScript full-stack reduz curva. REST API simples e escalável para o MVP."],
    ["🐘","PostgreSQL","Banco de Dados","Relações complexas. ACID, full-text search, suporte nativo a JSON."],
    ["🔐","JWT + OAuth Google","Autenticação","Login social elimina fricção. Cookies httpOnly para segurança."],
    ["📚","Google Books API","API Externa","Gratuita até 1000 req/dia. Capa, título, autor, ISBN, páginas."],
    ["🚀","Railway ou Render","Hospedagem","Deploy gratuito com PostgreSQL incluso. CI/CD automático via GitHub."],
  ]
  return(
    <div>
      <H tag="04 — Técnico" title="Estrutura Técnica" desc="Stack moderna, acessível e justificada — escolhida por critérios objetivos, não por modismo."/>
      <div className="g2">
        {stack.map(([ic,n,l,w])=>(
          <div className="si" key={n}>
            <div className="sic">{ic}</div>
            <div><div className="sn">{n}</div><div className="sl">{l}</div><div className="sw">{w}</div></div>
          </div>
        ))}
      </div>
      <Card title="Estrutura de Pastas" sub="Separação clara de responsabilidades." ch={
        <div className="code">
<span className="ca">{"foliar/"}</span>
{"├── "}<span className="cb">{"frontend/"}</span>
{"│   └── src/"}
{"│       ├── components/   "}<span className="cm">{"# Button, Card, Avatar, ProgressBar"}</span>
{"│       ├── pages/        "}<span className="cm">{"# Dashboard, Club, Profile, History"}</span>
{"│       ├── hooks/        "}<span className="cm">{"# useAuth, useProgress, useClub"}</span>
{"│       ├── services/     "}<span className="cm">{"# Axios API calls"}</span>
{"│       └── contexts/     "}<span className="cm">{"# AuthContext, ClubContext"}</span>
{"├── "}<span className="cb">{"backend/"}</span>
{"│   └── src/"}
{"│       ├── routes/       "}<span className="cm">{"# auth, clubs, rounds, comments"}</span>
{"│       ├── controllers/  "}<span className="cm">{"# lógica de negócio"}</span>
{"│       ├── middlewares/  "}<span className="cm">{"# auth, validation, errorHandler"}</span>
{"│       └── models/       "}<span className="cm">{"# Prisma ORM"}</span>
{"└── "}<span className="cb">{"docs/"}</span><span className="cm">{"             # Diagramas, ADRs, API docs"}</span>
        </div>
      }/>
    </div>
  )
}

/* ── DATABASE ── */
function DB(){
  const ents=[
    {name:"users",fields:[["id","UUID","PK",""],["email","VARCHAR","","Unique"],["name","VARCHAR","",""],["avatar_url","TEXT","",""],["created_at","TIMESTAMP","",""]]},
    {name:"clubs",fields:[["id","UUID","PK",""],["name","VARCHAR","",""],["owner_id","UUID","FK","→ users.id"],["is_private","BOOLEAN","","DEFAULT false"],["invite_code","VARCHAR","","Unique"]]},
    {name:"club_members",fields:[["id","UUID","PK",""],["club_id","UUID","FK","→ clubs.id"],["user_id","UUID","FK","→ users.id"],["role","ENUM","","member|organizer"],["joined_at","TIMESTAMP","",""]]},
    {name:"reading_rounds",fields:[["id","UUID","PK",""],["club_id","UUID","FK","→ clubs.id"],["book_google_id","VARCHAR","","Books API"],["book_title","VARCHAR","","Cached"],["total_chapters","INT","",""],["status","ENUM","","active|ended"]]},
    {name:"user_book_progress",fields:[["id","UUID","PK",""],["user_id","UUID","FK","→ users.id"],["round_id","UUID","FK","→ rounds.id"],["current_chapter","INT","","🔑 Spoiler-gate"],["updated_at","TIMESTAMP","",""]]},
    {name:"comments",fields:[["id","UUID","PK",""],["round_id","UUID","FK","→ rounds.id"],["user_id","UUID","FK","→ users.id"],["chapter_ref","INT","","🔑 Spoiler-gate"],["text","TEXT","",""],["parent_id","UUID","FK","Nullable (thread)"]]},
  ]
  return(
    <div>
      <H tag="05 — Dados" title="Banco de Dados" desc="6 entidades relacionais em PostgreSQL. Normalizado, escalável e com a lógica de spoiler-gate embutida nos dados."/>
      <div className="g2">
        {ents.map(e=>(
          <div className="ent" key={e.name}>
            <div className="ent-h">
              <span className="cg">table</span>
              <span className="ca" style={{marginLeft:6}}>{e.name}</span>
            </div>
            {e.fields.map(([n,t,f,note])=>(
              <div className="ent-row" key={n}>
                <span className="ef">{n}</span>
                <span className="et">{t}</span>
                {f==="PK"&&<span className="epk">PK</span>}
                {f==="FK"&&<span className="efk">FK</span>}
                {note&&<span className="en">{note}</span>}
              </div>
            ))}
          </div>
        ))}
      </div>
      <Card title="Query Central: Spoiler-Gate" glow ch={
        <div className="code">
<span className="cm">{"-- Retorna comentários com texto filtrado pelo progresso do usuário"}</span>
<span className="cp">{"SELECT"}</span>{" c.id, c.chapter_ref, c.user_id,"}
{"  "}<span className="cp">{"CASE WHEN"}</span>{" c.chapter_ref "}<span className="cp">{"<="}</span>{" p.current_chapter"}
{"    "}<span className="cp">{"THEN"}</span>{" c.text "}<span className="cp">{"ELSE"}</span>{" "}<span className="cg">{"NULL"}</span>{" "}<span className="cp">{"END"}</span>{" "}<span className="cb">{"AS"}</span>{" safe_text,"}
{"  (c.chapter_ref > p.current_chapter) "}<span className="cb">{"AS"}</span>{" is_blocked"}
<span className="cp">{"FROM"}</span>{" comments c"}
<span className="cp">{"JOIN"}</span>{" user_book_progress p "}<span className="cp">{"ON"}</span>{" p.user_id = "}<span className="co">{"$userId"}</span>{" AND p.round_id = "}<span className="co">{"$roundId"}</span>
<span className="cp">{"WHERE"}</span>{" c.round_id = "}<span className="co">{"$roundId"}</span>{" AND c.parent_id "}<span className="cp">{"IS NULL"}</span>
<span className="cp">{"ORDER BY"}</span>{" c.created_at "}<span className="cp">{"DESC"}</span>{";"}</div>}/>
    </div>
  )
}

/* ── ROADMAP ── */
function Roadmap(){
  const sprints=[
    {c:"var(--sage)",lbl:"Sprint 01 · Semanas 1–2",title:"Fundação",tasks:["Monorepo: Vite + Express + PostgreSQL","Modelagem do banco com Prisma ORM","JWT + OAuth Google funcional","Middleware de autenticação","Design system: tokens, Button, Input, Card","Layout geral: sidebar + main"]},
    {c:"var(--amber)",lbl:"Sprint 02 · Semanas 3–4",title:"Core: Clubes & Rodadas",tasks:["CRUD de clubes com sistema de convites","Papéis: membro / organizador","Integração Google Books API","CRUD de rodadas com cronograma","Registro de progresso","Dashboard com feed de atividade"]},
    {c:"var(--rust2)",lbl:"Sprint 03 · Semanas 5–6",title:"Diferencial: Spoiler-Gate",tasks:["Comentários com campo chapter_ref","Lógica de bloqueio no back-end","Blur + reveal no front-end","Reações literárias","Threads de resposta (2 níveis)","Notificações in-app básicas"]},
    {c:"var(--sky2)",lbl:"Sprint 04 · Semanas 7–8",title:"Acabamento & Deploy",tasks:["Perfil com estatísticas e badges","Histórico de rodadas encerradas","Votação de próximo livro","Painel do organizador","Onboarding (tour 3 passos)","Deploy Railway + domínio custom"]},
  ]
  return(
    <div>
      <H tag="06 — Planejamento" title="Roadmap de Desenvolvimento" desc="4 sprints de 2 semanas. Do zero ao MVP apresentável em 8 semanas."/>
      {sprints.map(sp=>(
        <div className="sprint" key={sp.lbl} style={{borderLeftColor:sp.c}}>
          <div className="sp-lbl" style={{color:sp.c}}>{sp.lbl}</div>
          <div className="sp-title">{sp.title}</div>
          {sp.tasks.map(t=>(
            <div className="tk" key={t}><div className="tk-dot" style={{background:sp.c}}/>{t}</div>
          ))}
        </div>
      ))}
      <div className="g3">
        {[["8","Semanas de dev"],["7","Telas completas"],["6","Entidades no banco"],["4","Sprints"],["8","Funcionalidades"],["1","Diferencial único"]].map(([v,l])=>(
          <div className="met" key={l}><div className="mv">{v}</div><div className="ml">{l}</div></div>
        ))}
      </div>
    </div>
  )
}

/* ── PITCH ── */
function Pitch(){
  return(
    <div>
      <H tag="07 — Apresentação" title="Pitch Final" desc="Tudo que você precisa para convencer professores, investidores ou qualquer banca."/>

      <div className="pitch-hero">
        <div style={{fontSize:11,fontWeight:600,letterSpacing:3,textTransform:"uppercase",color:"var(--sage2)",marginBottom:14}}>Pitch de uma linha</div>
        <div className="pitch-quote">
          "O Foliar transforma grupos de WhatsApp em clubes de leitura <em>organizados</em> — sem spoilers, sem caos, sem perder a magia."
        </div>
      </div>

      <Card title="Descrição do Produto" ch={
        <>
          <blockquote style={{marginTop:0}}>"Foliar é o lar digital do seu clube de leitura."</blockquote>
          <p className="small" style={{marginBottom:14}}>
            Organize cronogramas, registre seu progresso e debata cada capítulo sem medo de spoilers. O Foliar sabe até onde você leu — e protege sua experiência automaticamente.
          </p>
          <div style={{fontSize:13,color:"var(--soft)",lineHeight:2.1}}>
            ✦ Crie ou entre em clubes em segundos<br/>
            ✦ Comentários filtrados pelo seu progresso real<br/>
            ✦ Histórico permanente de todas as leituras<br/>
            ✦ Analytics para organizadores<br/>
            ✦ Memória coletiva do seu grupo literário
          </div>
        </>
      }/>

      <Card title="Argumentos para a Banca" ch={
        <div>
          {[
            ["01","Problema Real e Verificável","Qualquer leitor de clube conhece spoilers no WhatsApp. A dor é documentável, a solução é tangível e testável."],
            ["02","Diferencial Técnico Genuíno","O spoiler-gate baseado em progresso individual não existe em nenhuma plataforma atual — Skoob, Goodreads ou Discord."],
            ["03","Arquitetura Justificada","Stack escolhida por critérios objetivos: PostgreSQL para relações complexas, JWT por statelessness, React por produtividade."],
            ["04","UX Centrada no Usuário","Cada decisão tem métricas: progresso em < 10s, comentar em < 3 cliques, zero spoilers não solicitados."],
            ["05","Escalabilidade Demonstrada","Modelagem normalizada, separação de camadas e estrutura de pastas mostram que o sistema pode crescer além do MVP."],
            ["06","Potencial de Mercado Real","3.000+ clubes no Brasil, R$ 2,97 bi no mercado editorial, 7 milhões de usuários no Skoob. Números verificáveis."],
          ].map(([n,t,d])=>(
            <div key={n} style={{display:"flex",gap:16,padding:"15px 0",borderBottom:"1px solid var(--line)"}}>
              <div style={{fontFamily:"Playfair Display,serif",fontSize:24,fontWeight:700,color:"var(--bg4)",flexShrink:0,width:34,lineHeight:1}}>{n}</div>
              <div>
                <div style={{fontSize:13.5,fontWeight:600,color:"var(--bright)",marginBottom:4}}>{t}</div>
                <div style={{fontSize:12.5,color:"var(--muted)",lineHeight:1.7}}>{d}</div>
              </div>
            </div>
          ))}
        </div>
      }/>

      <div className="g2">
        <Card title="Mercado" ch={
          <div>
            {[["Clubes de leitura no Brasil","3.000+"],["Mercado editorial BR (2023)","R$ 2,97 bi"],["Usuários Skoob","7 milhões"],["Crescimento pós-pandemia","+340%"]].map(([k,v])=>(
              <div className="ir" key={k}><span className="ik">{k}</span><span style={{fontWeight:600,color:"var(--sage3)"}}>{v}</span></div>
            ))}
          </div>
        }/>
        <Card title="Monetização Futura" ch={
          <UL items={[
            "<strong style='color:var(--bright)'>Free:</strong> 1 clube, 20 membros",
            "<strong style='color:var(--bright)'>Pro R$12/mês:</strong> ilimitado + analytics",
            "<strong style='color:var(--bright)'>B2B Editoras:</strong> dados de engajamento",
            "<strong style='color:var(--bright)'>B2B Escolas:</strong> turmas + relatórios",
          ]}/>
        }/>
      </div>
    </div>
  )
}

/* ══════════════════════════════════════════
   APP SHELL
══════════════════════════════════════════ */
const VIEWS={brand:Brand,screens:Screens,features:Features,tech:Tech,db:DB,roadmap:Roadmap,pitch:Pitch}

export default function App(){
  const [active,setActive]=useState("brand")
  const Active=VIEWS[active]
  return(
    <>
      <style>{G}</style>
      <div className="shell">
        <nav className="rail">
          <div className="rail-logo">
            <div className="logotype">Foli<span>ar</span></div>
            <div className="logo-tag">MVP Docs</div>
          </div>
          <div className="rail-nav">
            {NAV.map(n=>(
              <div key={n.id} className={"ni"+(active===n.id?" on":"")} onClick={()=>setActive(n.id)}>
                <span className="ni-ic">{n.ic}</span>{n.label}
              </div>
            ))}
          </div>
          <div className="rail-foot">
            <div className="rail-badge">MVP · ADS<br/>8 semanas · v1.0</div>
          </div>
        </nav>
        <main className="page">
          <div className="fade" key={active}>
            <Active/>
          </div>
        </main>
      </div>
    </>
  )
}
