<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Forgive Me, Diksha ❤️</title>
  <style>
    :root{--bg1:#ffefe9;--bg2:#ffd9e0;--card:#ffffffcc;--accent:#ff6b81}
    *{box-sizing:border-box;font-family: 'Segoe UI', Roboto, 'Noto Sans', sans-serif}
    body{margin:0;min-height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,var(--bg1),var(--bg2));padding:24px}
    .card{max-width:880px;width:100%;background:var(--card);border-radius:16px;box-shadow:0 10px 30px rgba(0,0,0,0.12);overflow:hidden}
    header{padding:28px 32px;background:linear-gradient(90deg,rgba(255,255,255,0.06),transparent);display:flex;align-items:center;gap:18px}
    .heart{width:72px;height:72px;position:relative;transform:rotate(-45deg)}
    .heart::before,.heart::after{content:'';position:absolute;width:72px;height:72px;border-radius:50%;background:var(--accent)}
    .heart::before{top:-36px;left:0}
    .heart::after{left:36px;top:0}
    h1{margin:0;font-size:28px;color:#7a1622}
    p.lead{margin:6px 0 0;color:#4b232a}
    main{display:grid;grid-template-columns:1fr 360px;gap:20px;padding:28px}
    @media (max-width:880px){main{grid-template-columns:1fr;}}
    .poems{padding:12px}
    .poem{background:rgba(255,255,255,0.6);padding:18px;border-radius:12px;margin-bottom:12px;transition:transform .18s ease}
    .poem:hover{transform:translateY(-4px)}
    .poem p{margin:0 0 8px 0;line-height:1.45;font-size:18px;color:#3b1f24}
    .small{font-size:14px;color:#6a3a41}
    .actions{padding:18px}
    .box{background:rgba(255,255,255,0.85);padding:16px;border-radius:12px}
    label{display:block;font-size:13px;color:#5a2f34;margin-bottom:6px}
    input[type=text]{width:100%;padding:10px;border-radius:8px;border:1px solid #f0c6c9;font-size:15px}
    button{width:100%;margin-top:12px;padding:12px;border-radius:10px;border:0;background:linear-gradient(90deg,var(--accent),#ff9aa2);color:white;font-weight:600;cursor:pointer}
    .muted{background:transparent;color:#7d3a40;border:1px dashed rgba(125,58,64,0.15);}
    .preview{margin-top:12px;padding:12px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.9),rgba(255,255,255,0.7));min-height:120px}
    .preview p{margin:0;font-size:16px;color:#3b1f24}
    footer{padding:16px 24px;background:linear-gradient(0deg,rgba(255,255,255,0.03),transparent);display:flex;justify-content:space-between;align-items:center}
    .note{font-size:13px;color:#6a3a41}
    .modal{position:fixed;inset:0;display:flex;align-items:center;justify-content:center;background:rgba(0,0,0,0.35);opacity:0;pointer-events:none;transition:opacity .16s}
    .modal.show{opacity:1;pointer-events:auto}
    .modal-card{background:white;padding:22px;border-radius:12px;max-width:420px;text-align:center;box-shadow:0 12px 30px rgba(0,0,0,0.2)}
  </style>
</head>
<body>
  <div class="card">
    <header>
      <div class="heart" aria-hidden="true"></div>
      <div>
        <h1>Forgive Me, Diksha ❤️</h1>
        <p class="lead">A short note from the heart — hope it helps mend things.</p>
      </div>
    </header>

    <main>
      <section class="poems">
        <div class="poem">
          <p>Diksha, I made a mistake and I'm truly sorry.<br>Your smile lights up everything; I miss it.</p>
        </div>

        <div class="poem">
          <p>Please forgive my shortcomings — I promise to do better.<br>Can we start fresh and have tea together?</p>
        </div>

        <div class="poem">
          <p style="font-weight:700;">Forgive me, Diksha. You have always been, and will always be, my sister.</p>
        </div>
      </section>

      <aside class="actions">
        <div class="box">
          <label for="fromName">Your name (as it will appear):</label>
          <input id="fromName" type="text" placeholder="Your name" />

          <label style="margin-top:12px">Personal short message (optional):</label>
          <input id="personal" type="text" placeholder="I promise..." value="Forgive me, Diksha. You have always been, and will always be, my sister." />

          <button id="makeBtn">Prepare message & copy</button>
          <button id="printBtn" class="muted">Open print-friendly page</button>

          <div class="preview" id="preview" aria-live="polite"></div>
        </div>
      </aside>
    </main>

    <footer>
      <div class="note">Small effort — big feelings.</div>
      <div style="font-size:13px;color:#7a3a3f">Need help? Tell me what to change.</div>
    </footer>
  </div>

  <div id="modal" class="modal" role="dialog" aria-hidden="true">
    <div class="modal-card">
      <h3 id="modalTitle">Message copied!</h3>
      <p id="modalText">Now you can paste it into Messenger, WhatsApp or Email.</p>
      <div style="margin-top:12px"><button onclick="closeModal()">OK</button></div>
    </div>
  </div>

  <script>
    const poemsText = `Diksha, I made a mistake and I'm truly sorry.\\nYour smile lights up everything; I miss it.\\n\\nPlease forgive my shortcomings — I promise to do better.\\nCan we start fresh and have tea together?\\n\\nForgive me, Diksha. You have always been, and will always be, my sister.\\n\\n--`;

    const preview = document.getElementById('preview');
    const fromName = document.getElementById('fromName');
    const personal = document.getElementById('personal');
    const makeBtn = document.getElementById('makeBtn');
    const printBtn = document.getElementById('printBtn');
    const modal = document.getElementById('modal');

    function buildMessage(){
      const who = fromName.value.trim() || 'Yours';
      const note = personal.value.trim();
      let msg = (note ? note + '\\n\\n' : '') + poemsText + '\\n' + who;
      return msg;
    }

    function updatePreview(){
      const text = buildMessage().replace(/\\n/g,'<br>');
      preview.innerHTML = text;
    }

    makeBtn.addEventListener('click', ()=>{
      const msg = buildMessage();
      if(navigator.clipboard && navigator.clipboard.writeText){
        navigator.clipboard.writeText(msg).then(()=>{
          showModal('Message copied!', 'Now paste it into Messenger/WhatsApp/Email and send it.');
        }).catch(()=>{ prompt('Please copy this message:', msg); });
      } else {
        prompt('Please copy this message:', msg);
      }
    });

    printBtn.addEventListener('click', ()=>{
      const w = window.open('', '_blank');
      const html = `<!doctype html><html><head><meta charset="utf-8"><title>Print - Sorry</title><style>body{font-family:Arial,Helvetica,sans-serif;padding:30px;background:#fff;color:#333}pre{white-space:pre-wrap;font-size:18px}</style></head><body><pre>${buildMessage()}</pre></body></html>`;
      w.document.write(html); w.document.close();
    });

    function showModal(title, text){
      document.getElementById('modalTitle').innerText = title;
      document.getElementById('modalText').innerText = text;
      modal.classList.add('show');
      modal.setAttribute('aria-hidden','false');
    }
    function closeModal(){ modal.classList.remove('show'); modal.setAttribute('aria-hidden','true'); }

    fromName.addEventListener('input', updatePreview);
    personal.addEventListener('input', updatePreview);
    updatePreview();
  </script>
</body>
</html>
