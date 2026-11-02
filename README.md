<!doctype html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Business English Idioms 2 — Lesson &amp; Practice</title>
<style>
  :root {
    font-family: Georgia, 'Times New Roman', serif;
    color: #1f2937;
    background: #0f172a;
  }
  * { box-sizing: border-box; }
  body { margin: 0; min-height: 100vh; display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 24px; }
  .deck {
    width: 100%;
    max-width: 900px;
    background: #ffffff;
    border-radius: 16px;
    box-shadow: 0 20px 60px rgba(0,0,0,.45);
    overflow: hidden;
  }
  .progress-bar { height: 6px; background: #e2e8f0; }
  .progress-fill { height: 100%; background: linear-gradient(90deg, #059669, #0d9488); transition: width .3s ease; }
  .slide {
    display: none;
    padding: 40px 48px 32px;
    min-height: 520px;
    max-height: 640px;
    overflow-y: auto;
    flex-direction: column;
  }
  .slide.active { display: flex; }
  h1 { font-size: 34px; margin: 0 0 6px; color: #0f172a; }
  h2 { font-size: 26px; margin: 0 0 18px; color: #047857; border-bottom: 3px solid #d1fae5; padding-bottom: 8px; }
  h3 { font-size: 19px; margin: 18px 0 8px; color: #374151; }
  p, li { font-size: 17px; line-height: 1.55; }
  .kicker { text-transform: uppercase; letter-spacing: 2px; font-size: 12px; color: #6b7280; margin-bottom: 10px; font-family: Verdana, sans-serif; }
  .idiom-card {
    background: #f0fdf4;
    border-left: 5px solid #059669;
    border-radius: 8px;
    padding: 12px 16px;
    margin: 8px 0;
  }
  .idiom-card b { color: #047857; font-size: 18px; }
  .example { font-style: italic; color: #475569; margin-top: 4px; }
  .example u { text-decoration: none; background: #fef08a; padding: 0 3px; border-radius: 3px; }
  .navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 20px;
    background: #0f172a;
    color: #e2e8f0;
    font-family: Verdana, sans-serif;
    font-size: 14px;
  }
  .navbar button {
    background: #059669;
    color: #fff;
    border: none;
    border-radius: 8px;
    padding: 10px 22px;
    font-size: 15px;
    cursor: pointer;
    transition: background .2s;
  }
  .navbar button:hover:not(:disabled) { background: #047857; }
  .navbar button:disabled { background: #334155; color: #64748b; cursor: default; }
  .match-item { display: flex; align-items: center; gap: 12px; margin: 10px 0; }
  .match-item select { font-size: 16px; padding: 6px 10px; border-radius: 6px; border: 1px solid #cbd5e1; font-family: inherit; flex: 1; }
  .feedback { font-weight: bold; white-space: nowrap; }
  .ok { color: #16a34a; }
  .no { color: #dc2626; }
  .answer-hidden { display: none; margin-top: 12px; background: #ecfdf5; border-left: 5px solid #16a34a; padding: 12px 16px; border-radius: 8px; }
  .btn-show {
    margin-top: 14px;
    background: #0d9488;
    color: #fff;
    border: none;
    border-radius: 8px;
    padding: 9px 18px;
    font-size: 15px;
    cursor: pointer;
  }
  .btn-show:hover { background: #0f766e; }
  .gap { border-bottom: 2px solid #9ca3af; display: inline-block; min-width: 160px; text-align: center; color: #059669; font-weight: bold; cursor: pointer; }
  .bank {
    background: #f0fdf4;
    border: 1px dashed #059669;
    border-radius: 8px;
    padding: 10px 16px;
    margin: 10px 0 18px;
    font-style: italic;
    color: #065f46;
  }
  textarea {
    width: 100%;
    min-height: 90px;
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    padding: 10px;
    font-family: inherit;
    font-size: 16px;
    resize: vertical;
  }
  .sent { margin: 0 0 14px; line-height: 2; font-size: 17px; }
  .blank {
    border: none;
    border-bottom: 2px solid #94a3b8;
    background: #f8fafc;
    border-radius: 4px 4px 0 0;
    padding: 4px 8px;
    font-family: inherit;
    font-size: 16px;
    width: 190px;
    text-align: center;
    color: #047857;
    font-weight: bold;
  }
  .blank:focus { outline: none; border-bottom-color: #059669; background: #f0fdf4; }
  .blank.correct { background: #dcfce7; border-bottom-color: #16a34a; }
  .blank.incorrect { background: #fee2e2; border-bottom-color: #dc2626; }
  .btn-row { display: flex; gap: 10px; flex-wrap: wrap; }
  .hint { font-size: 14px; color: #6b7280; }
  ol li { margin-bottom: 10px; }
</style>
</head>
<body>
<div class="deck">
  <div class="progress-bar"><div class="progress-fill" id="progress"></div></div>

  <!-- SLIDE 1: PRESENTATION -->
  <section class="slide active" id="s0">
    <div class="kicker">Vocabulary · Business English · Part 2</div>
    <h1>Nine Idioms for Business English</h1>
    <p>Here is a second set of common business sayings. Study the meaning and example for each one — you will practise them all in the next slides!</p>

    <div class="idiom-card"><b>1. Raise the bar</b><br>
      <span><i>Meaning:</i> to set a higher standard of quality or performance.</span>
      <div class="example">Their last product was so good that it <u>raised the bar</u> for every competitor.</div>
    </div>
    <div class="idiom-card"><b>2. It's not rocket science</b><br>
      <span><i>Meaning:</i> it's not as complicated as it seems.</span>
      <div class="example">Don't worry about the new software — using it is <u>not rocket science</u>.</div>
    </div>
    <div class="idiom-card"><b>3. Call it a day</b><br>
      <span><i>Meaning:</i> to stop working, for now or for today.</span>
      <div class="example">We've been at this since 8 a.m. — let's <u>call it a day</u> and continue tomorrow.</div>
    </div>
    <div class="idiom-card"><b>4. On the same page</b><br>
      <span><i>Meaning:</i> to share the same understanding or opinion.</span>
      <div class="example">Before the launch, let's make sure the whole team is <u>on the same page</u>.</div>
    </div>
    <div class="idiom-card"><b>5. Learn the ropes</b><br>
      <span><i>Meaning:</i> to learn how a job or task is done.</span>
      <div class="example">She joined last month and has already <u>learned the ropes</u> of the sales process.</div>
    </div>
    <div class="idiom-card"><b>6. Go the extra mile</b><br>
      <span><i>Meaning:</i> to make more effort than what is expected.</span>
      <div class="example">Our support team always <u>goes the extra mile</u> to keep customers happy.</div>
    </div>
    <div class="idiom-card"><b>7. In the pipeline</b><br>
      <span><i>Meaning:</i> being planned or developed, not yet ready.</span>
      <div class="example">We have two new features <u>in the pipeline</u> for next quarter.</div>
    </div>
    <div class="idiom-card"><b>8. Cut corners</b><br>
      <span><i>Meaning:</i> to do something cheaply or carelessly to save time or money.</span>
      <div class="example">The builder <u>cut corners</u> on materials, and the wall cracked after a month.</div>
    </div>
    <div class="idiom-card"><b>9. Ahead of the curve</b><br>
      <span><i>Meaning:</i> more advanced or innovative than others, especially competitors.</span>
      <div class="example">Investing in AI early kept the company <u>ahead of the curve</u>.</div>
    </div>
  </section>

  <!-- SLIDE 2: MATCHING -->
  <section class="slide" id="s1">
    <div class="kicker">Exercise 1 · Recognition</div>
    <h2>Match the idiom to its meaning</h2>
    <p>Choose the correct meaning for each idiom, then check your answers.</p>
    <div class="match-item" data-a="raise the bar">
      <b>a) Raise the bar</b>
      <select>
        <option value="">— choose —</option>
        <option value="raise the bar">to set a higher standard</option>
        <option value="learn the ropes">to learn how a job is done</option>
        <option value="cut corners">to do something carelessly to save money</option>
        <option value="in the pipeline">being planned or developed</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="it's not rocket science">
      <b>b) It's not rocket science</b>
      <select>
        <option value="">— choose —</option>
        <option value="ahead of the curve">more advanced than competitors</option>
        <option value="it's not rocket science">it's not as complicated as it seems</option>
        <option value="call it a day">to stop working for the day</option>
        <option value="on the same page">to share the same understanding</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="call it a day">
      <b>c) Call it a day</b>
      <select>
        <option value="">— choose —</option>
        <option value="in the pipeline">being planned or developed</option>
        <option value="go the extra mile">to make more effort than expected</option>
        <option value="call it a day">to stop working for now</option>
        <option value="raise the bar">to set a higher standard</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="on the same page">
      <b>d) On the same page</b>
      <select>
        <option value="">— choose —</option>
        <option value="on the same page">to share the same understanding</option>
        <option value="learn the ropes">to learn how a job is done</option>
        <option value="cut corners">to do something carelessly to save money</option>
        <option value="it's not rocket science">it's not as complicated as it seems</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="learn the ropes">
      <b>e) Learn the ropes</b>
      <select>
        <option value="">— choose —</option>
        <option value="ahead of the curve">more advanced than competitors</option>
        <option value="call it a day">to stop working for now</option>
        <option value="raise the bar">to set a higher standard</option>
        <option value="learn the ropes">to learn how a job is done</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="go the extra mile">
      <b>f) Go the extra mile</b>
      <select>
        <option value="">— choose —</option>
        <option value="go the extra mile">to make more effort than expected</option>
        <option value="in the pipeline">being planned or developed</option>
        <option value="on the same page">to share the same understanding</option>
        <option value="cut corners">to do something carelessly to save money</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="in the pipeline">
      <b>g) In the pipeline</b>
      <select>
        <option value="">— choose —</option>
        <option value="it's not rocket science">it's not as complicated as it seems</option>
        <option value="in the pipeline">being planned or developed</option>
        <option value="go the extra mile">to make more effort than expected</option>
        <option value="ahead of the curve">more advanced than competitors</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="cut corners">
      <b>h) Cut corners</b>
      <select>
        <option value="">— choose —</option>
        <option value="cut corners">to do something carelessly to save money or time</option>
        <option value="learn the ropes">to learn how a job is done</option>
        <option value="on the same page">to share the same understanding</option>
        <option value="call it a day">to stop working for now</option>
      </select>
      <span class="feedback"></span>
    </div>
    <div class="match-item" data-a="ahead of the curve">
      <b>i) Ahead of the curve</b>
      <select>
        <option value="">— choose —</option>
        <option value="raise the bar">to set a higher standard</option>
        <option value="in the pipeline">being planned or developed</option>
        <option value="ahead of the curve">more advanced than competitors</option>
        <option value="go the extra mile">to make more effort than expected</option>
      </select>
      <span class="feedback"></span>
    </div>
    <button class="btn-show" onclick="checkMatch()">Check answers</button>
  </section>

  <!-- SLIDE 3: FILL IN THE BLANKS (PART 1) -->
  <section class="slide" id="s2">
    <div class="kicker">Exercise 2 · Controlled practice · Part 1</div>
    <h2>Complete the sentences (1–9)</h2>
    <p>Type the correct idiom in each gap — think about meaning <b>and</b> grammar (you may need to change the verb form). Then press <b>Check my answers</b>.</p>
    <div class="bank">Word bank: <b>raise the bar · it's not rocket science · call it a day · on the same page · learn the ropes · go the extra mile · in the pipeline · cut corners · ahead of the curve</b></div>
    <div class="sent">1. It's almost 9 p.m. and we're exhausted — let's <input class="blank" data-a="call it a day"> and finish the rest tomorrow.</div>
    <div class="sent">2. Our intern is smart; it took her only a week to <input class="blank" data-a="learn the ropes"> of the invoicing system.</div>
    <div class="sent">3. The update is still <input class="blank" data-a="in the pipeline"> — it will be ready for customers sometime next quarter.</div>
    <div class="sent">4. Before we present to the board, the directors need to be <input class="blank" data-a="on the same page"> about the new strategy.</div>
    <div class="sent">5. Most employees do the minimum, but Marta always <input class="blank" data-a="goes the extra mile|go the extra mile"> for her clients.</div>
    <div class="sent">6. That startup's design is so impressive — they've really <input class="blank" data-a="raised the bar|raise the bar"> for the whole industry.</div>
    <div class="sent">7. The bridge was unsafe because the construction company <input class="blank" data-a="cut corners"> on the steel.</div>
    <div class="sent">8. By adopting e-commerce in 2010, the shop stayed <input class="blank" data-a="ahead of the curve"> while its rivals struggled.</div>
    <div class="sent">9. Relax — setting up the meeting room is <input class="blank" data-a="not rocket science|it's not rocket science">; you'll manage it in five minutes.</div>
    <div class="btn-row">
      <button class="btn-show" onclick="checkBlanks()">Check my answers</button>
      <button class="btn-show" onclick="showBlanks()">Show answers</button>
    </div>
  </section>

  <!-- SLIDE 4: FILL IN THE BLANKS (PART 2) -->
  <section class="slide" id="s2b">
    <div class="kicker">Exercise 2 · Controlled practice · Part 2</div>
    <h2>Complete the sentences (10–18)</h2>
    <p>Same idioms, new sentences — a second round to make them stick!</p>
    <div class="bank">Word bank: <b>raise the bar · it's not rocket science · call it a day · on the same page · learn the ropes · go the extra mile · in the pipeline · cut corners · ahead of the curve</b></div>
    <div class="sent">10. Our marketing has become sloppy — this campaign really needs to <input class="blank" data-a="raise the bar">.</div>
    <div class="sent">11. Don't worry about your first week — everyone needs time to <input class="blank" data-a="learn the ropes"> in a new company.</div>
    <div class="sent">12. Both managers read the contract carefully so they would be <input class="blank" data-a="on the same page"> before signing.</div>
    <div class="sent">13. Stop overthinking it — refilling the printer <input class="blank" data-a="is not rocket science|not rocket science|it's not rocket science">; just follow the instructions on the screen.</div>
    <div class="sent">14. We've just fixed the last bug of the day, so let's <input class="blank" data-a="call it a day"> a bit earlier tonight.</div>
    <div class="sent">15. The chef refused to <input class="blank" data-a="cut corners"> even though cheaper ingredients would save him hundreds of euros a month.</div>
    <div class="sent">16. By switching to solar power years before its competitors, the factory stayed <input class="blank" data-a="ahead of the curve">.</div>
    <div class="sent">17. Marco was still at his desk at 11 p.m. — he really <input class="blank" data-a="went the extra mile|goes the extra mile"> for this client.</div>
    <div class="sent">18. The app's voice-assistant feature is still <input class="blank" data-a="in the pipeline">; it won't be released before summer.</div>
    <div class="btn-row">
      <button class="btn-show" onclick="checkBlanks()">Check my answers</button>
      <button class="btn-show" onclick="showBlanks()">Show answers</button>
    </div>
  </section>

  <!-- SLIDE 4: CHOOSE THE RIGHT IDIOM (context) -->
  <section class="slide" id="s3">
    <div class="kicker">Exercise 3 · Understanding in context</div>
    <h2>Which idiom is the speaker using?</h2>
    <p>Read each mini-dialogue and decide which idiom best describes the situation.</p>
    <ol>
      <li><i>"That was a long meeting, but at least we all agree on the new plan now."</i><br>
        → Everyone is <span class="gap" data-a="on the same page" onclick="fill(this)"></span></li>
      <li><i>"I know the courier job is tough — I'll show you how everything works during your first week."</i><br>
        → The new employee has to <span class="gap" data-a="learn the ropes" onclick="fill(this)"></span></li>
      <li><i>"You don't need a degree to use our booking system. It's really quite simple."</i><br>
        → Using the system <span class="gap" data-a="is not rocket science" onclick="fill(this)"></span></li>
      <li><i>"Most shops closed during the crisis, but ours was already selling online — and we survived."</i><br>
        → The shop was <span class="gap" data-a="ahead of the curve" onclick="fill(this)"></span></li>
      <li><i>"No, we can't use cheaper paint on this client's house. Quality comes first."</i><br>
        → The manager refuses to <span class="gap" data-a="cut corners" onclick="fill(this)"></span></li>
      <li><i>"Last year's phones were good, but this new model is exceptional — now everyone else looks average."</i><br>
        → The new model has <span class="gap" data-a="raised the bar" onclick="fill(this)"></span></li>
      <li><i>"The delivery was late, but the driver personally came back to install the part for free."</i><br>
        → The driver <span class="gap" data-a="went the extra mile" onclick="fill(this)"></span></li>
      <li><i>"We're planning a premium version, a mobile app and a partnership with a bank."</i><br>
        → Those projects are <span class="gap" data-a="in the pipeline" onclick="fill(this)"></span></li>
      <li><i>"We've been packing orders since dawn and the van is loaded. That's enough for today."</i><br>
        → It's time to <span class="gap" data-a="call it a day" onclick="fill(this)"></span></li>
    </ol>
    <p class="hint">💡 Click on a gap to reveal the answer.</p>
  </section>

  <!-- SLIDE 5: GUIDED PRODUCTION -->
  <section class="slide" id="s4">
    <div class="kicker">Exercise 4 · Guided production</div>
    <h2>Finish the sentences in your own words</h2>
    <p>Complete each sentence so it makes sense in a real business situation. Say your answers out loud, or write them in the boxes.</p>
    <h3>1. When I start a new job, the fastest way for me to learn the ropes is to…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
    <h3>2. A company should never cut corners on…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
    <h3>3. To stay ahead of the curve in my industry, a company must…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
    <h3>4. A time when I (or someone I know) really went the extra mile was when…</h3>
    <textarea placeholder="Write your sentence here…"></textarea>
  </section>

  <!-- SLIDE 6: OPEN PRODUCTION (role play) -->
  <section class="slide" id="s5">
    <div class="kicker">Exercise 5 · Open practice</div>
    <h2>Role play: the new employee's first week</h2>
    <p><b>Scenario:</b> You are a team leader welcoming a talented new colleague to your company. It's the end of a long first day, and you are giving them advice and encouragement.</p>
    <p>Prepare and perform your welcome talk (1–2 minutes). Your goal is to use <b>at least five</b> of the nine idioms.</p>
    <h3>Guiding questions</h3>
    <ul>
      <li>What will you tell them about the tools they must use — how could you reassure them that it's <b>not rocket science</b>?</li>
      <li>Who will help them <b>learn the ropes</b> in their first weeks?</li>
      <li>What values does the company have — does the team <b>go the extra mile</b> for clients? Does it refuse to <b>cut corners</b>?</li>
      <li>What exciting projects are <b>in the pipeline</b> that they will join?</li>
      <li>Why does the company invest in new technology — does it want to stay <b>ahead of the curve</b> and <b>raise the bar</b>?</li>
      <li>How will you end your talk — will you suggest you both <b>call it a day</b>, after making sure you are <b>on the same page</b> about tomorrow's tasks?</li>
    </ul>
    <textarea placeholder="Write your speech or notes here…"></textarea>
  </section>

  <!-- SLIDE 7: OPEN PRODUCTION (free writing) -->
  <section class="slide" id="s6">
    <div class="kicker">Exercise 6 · Free production</div>
    <h2>Write your own business story</h2>
    <p>Write a short paragraph (6–10 sentences) about a company — real or imaginary — that succeeds thanks to good habits.</p>
    <ul>
      <li>Use <b>as many of the nine idioms as you can</b> (aim for at least six!).</li>
      <li>Give the company a name and describe how it works.</li>
      <li>Finish with a positive result.</li>
    </ul>
    <h3>Example opening</h3>
    <p class="example">"Green Grocers, a tiny organic shop in Milan, learned the ropes of online selling faster than anyone expected…"</p>
    <textarea style="min-height: 160px;" placeholder="Write your story here…"></textarea>
    <h3>Self-check</h3>
    <p class="hint">☐ Did you use the idioms in the correct form? (e.g. "learned the ropes", "raised the bar") ☐ Is each idiom used in a logical situation? ☐ Did you use at least six different idioms?</p>
  </section>

  <div class="navbar">
    <button id="prevBtn" onclick="go(-1)">← Previous</button>
    <span id="counter">Slide 1 / 8</span>
    <button id="nextBtn" onclick="go(1)">Next →</button>
  </div>
</div>

<script>
  const total = 8;
  let idx = 0;

  function render() {
    document.querySelectorAll('.slide').forEach((s, i) => s.classList.toggle('active', i === idx));
    document.getElementById('counter').textContent = 'Slide ' + (idx + 1) + ' / ' + total;
    document.getElementById('progress').style.width = ((idx + 1) / total * 100) + '%';
    document.getElementById('prevBtn').disabled = (idx === 0);
    document.getElementById('nextBtn').disabled = (idx === total - 1);
  }

  function go(d) {
    const n = idx + d;
    if (n < 0 || n >= total) return;
    idx = n;
    render();
  }

  function reveal(id) {
    const el = document.getElementById(id);
    el.style.display = (el.style.display === 'block') ? 'none' : 'block';
  }

  function fill(span) {
    span.textContent = span.dataset.a;
    span.style.background = '#fef08a';
  }

  function checkMatch() {
    document.querySelectorAll('.match-item').forEach(item => {
      const sel = item.querySelector('select');
      const fb = item.querySelector('.feedback');
      if (!sel.value) { fb.textContent = '✗'; fb.className = 'feedback no'; return; }
      const ok = sel.value === item.dataset.a;
      fb.textContent = ok ? '✓ Correct' : '✗ Try again';
      fb.className = 'feedback ' + (ok ? 'ok' : 'no');
    });
  }

  function normalize(s) {
    return s.trim().toLowerCase().replace(/[.,!?;:'’]+$/g, '');
  }

  function checkBlanks() {
    document.querySelectorAll('.slide.active .blank').forEach(inp => {
      const accepted = (inp.dataset.a || '').split('|').map(normalize);
      inp.classList.remove('correct', 'incorrect');
      if (normalize(inp.value) === '') { inp.classList.add('incorrect'); return; }
      inp.classList.add(accepted.includes(normalize(inp.value)) ? 'correct' : 'incorrect');
    });
  }

  function showBlanks() {
    document.querySelectorAll('.slide.active .blank').forEach(inp => {
      inp.value = inp.dataset.a.split('|')[0];
      inp.classList.remove('incorrect');
      inp.classList.add('correct');
    });
  }

  document.addEventListener('keydown', e => {
    if (e.key === 'ArrowRight') go(1);
    if (e.key === 'ArrowLeft') go(-1);
  });

  render();
</script>
</body>
</html>
