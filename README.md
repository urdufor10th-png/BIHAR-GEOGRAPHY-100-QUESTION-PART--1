# BIHAR-GEOGRAPHY-100-QUESTION-PART--1
For Any Competitive Exams 
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BPSC Bihar Geography 100 Standard MCQs - 20 Minutes</title>

  <!-- EmailJS Library for direct lead routing -->
  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: "Times New Roman", Times, serif !important;
    }
    body {
      background-color: #000000;
      color: #ffffff;
      padding: 16px;
    }
    .wrapper {
      max-width: 1100px;
      margin: 0 auto;
    }

    /* Top Banner */
    .top-header {
      background: #0d0d0d;
      border: 2px solid #262626;
      border-radius: 16px;
      padding: 24px 20px;
      text-align: center;
      margin-bottom: 24px;
    }
    .badge {
      display: inline-block;
      background: #1e3a8a;
      border: 1px solid #3b82f6;
      color: #93c5fd;
      font-size: 22px;
      font-weight: 700;
      padding: 6px 18px;
      border-radius: 50px;
      margin-bottom: 12px;
    }
    .title {
      font-size: 40px;
      line-height: 1.35;
      font-weight: 800;
      margin-bottom: 10px;
      color: #ffffff;
    }
    .title span { color: #38bdf8; }
    .desc {
      font-size: 24px;
      line-height: 1.5;
      color: #cbd5e1;
      max-width: 860px;
      margin: 0 auto 16px;
    }
    .features {
      display: flex;
      justify-content: center;
      gap: 24px;
      margin-top: 14px;
      font-size: 22px;
      color: #94a3b8;
      flex-wrap: wrap;
    }

    /* Registration Gate Card */
    .gate-card {
      background: #0f0f0f;
      padding: 36px;
      border-radius: 16px;
      border: 2px solid #2a2a2a;
      max-width: 680px;
      margin: 0 auto;
    }
    .gate-card h2 { color: #ef4444; font-size: 38px; margin-bottom: 10px; text-align: center; font-weight: 800; }
    .gate-card p { font-size: 24px; color: #a1a1aa; margin-bottom: 24px; text-align: center; }

    .form-group { margin-bottom: 20px; }
    .form-group label { display: block; font-size: 26px; font-weight: 700; margin-bottom: 8px; color: #f4f4f5; }
    .form-group input {
      width: 100%; padding: 14px 18px; background: #1c1c1c; border: 2px solid #3f3f46;
      border-radius: 8px; font-size: 24px; color: #ffffff; outline: none;
    }
    .form-group input:focus { border-color: #ef4444; }

    .otp-inline { display: flex; gap: 12px; }
    .btn-send-otp {
      padding: 0 22px; background: #0284c7; color: white; border: none; border-radius: 8px;
      font-size: 22px; font-weight: 700; cursor: pointer; white-space: nowrap;
    }
    .btn-submit {
      width: 100%; padding: 16px; background: #16a34a; color: white; border: none;
      border-radius: 10px; font-size: 30px; font-weight: 800; cursor: pointer; margin-top: 12px;
    }
    .btn-submit:disabled, .btn-send-otp:disabled { background: #52525b; cursor: not-allowed; }

    /* Test View Section */
    #test-view { display: none; }
    header {
      background: #0f0f0f; border: 2px solid #27272a; color: white; padding: 18px 20px;
      border-radius: 14px; margin-bottom: 20px; display: flex; flex-wrap: wrap;
      justify-content: space-between; align-items: center; gap: 16px;
    }
    .timer-box {
      font-size: 32px; font-weight: 800; color: #facc15; background: #27272a;
      padding: 6px 18px; border-radius: 8px; border: 2px solid #eab308;
    }
    .stats { display: flex; gap: 12px; font-size: 24px; }
    .badge-stat { padding: 6px 16px; border-radius: 8px; font-weight: 700; }
    .badge-tot { background: #1e40af; }
    .badge-cor { background: #15803d; }
    .badge-wro { background: #b91c1c; }

    /* Question Palette */
    .palette-toggle {
      background: #18181b; color: #ffffff; border: 2px solid #3f3f46; padding: 12px 18px;
      border-radius: 10px; cursor: pointer; font-weight: 700; margin-bottom: 16px; width: 100%;
      text-align: left; font-size: 24px;
    }
    .palette-grid {
      display: none; background: #09090b; padding: 16px; border-radius: 12px; margin-bottom: 20px;
      max-height: 250px; overflow-y: auto; border: 2px solid #27272a;
      grid-template-columns: repeat(auto-fill, minmax(56px, 1fr)); gap: 8px;
    }
    .palette-grid.active { display: grid; }
    .pal-btn {
      height: 48px; border: 2px solid #3f3f46; background: #1c1c1c; color: #ffffff; border-radius: 8px;
      cursor: pointer; font-weight: 700; font-size: 20px;
    }
    .pal-btn.current { border: 3px solid #ef4444; }
    .pal-btn.correct { background: #15803d; border-color: #22c55e; }
    .pal-btn.wrong { background: #b91c1c; border-color: #ef4444; }

    /* Question Card - Strict Red & 36px Font */
    .card {
      background: #0d0d0d; padding: 32px; border-radius: 16px; border: 2px solid #262626;
      margin-bottom: 24px;
    }
    .q-head {
      font-weight: 800;
      color: #f87171 !important;
      margin-bottom: 16px;
      font-size: 32px;
    }
    .q-txt {
      font-size: 36px !important;
      line-height: 1.5;
      margin-bottom: 28px;
      white-space: pre-line;
      color: #ef4444 !important;
      font-weight: 800;
    }
    .options { display: flex; flex-direction: column; gap: 18px; }
    .opt-btn {
      text-align: left;
      padding: 20px 24px;
      border: 2px solid #3f3f46;
      background: #171717;
      border-radius: 12px;
      cursor: pointer;
      font-size: 36px !important;
      line-height: 1.4;
      color: #ffffff;
      transition: background-color 0.15s ease;
    }
    .opt-btn:hover:not(:disabled) { background: #262626; border-color: #71717a; }
    .opt-btn.correct { background: #14532d !important; border-color: #22c55e !important; color: #ffffff !important; font-weight: 800; }
    .opt-btn.wrong { background: #7f1d1d !important; border-color: #ef4444 !important; color: #ffffff !important; font-weight: 800; }

    /* Detailed Explanation Box */
    .explanation-card {
      display: none;
      margin-top: 28px;
      padding: 24px;
      border-radius: 12px;
      background: #020617;
      border-left: 10px solid #ef4444;
      line-height: 1.6;
    }
    .explanation-card.show { display: block; }
    .exp-title {
      font-weight: 800;
      color: #f87171;
      margin-bottom: 12px;
      font-size: 36px !important;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .exp-text {
      color: #e2e8f0;
      font-size: 36px !important;
      line-height: 1.5;
    }

    .nav-btns { display: flex; justify-content: space-between; margin-top: 26px; }
    .nav-btn {
      padding: 16px 36px; border-radius: 10px; border: 2px solid #ef4444; background: #b91c1c;
      color: white; font-weight: 800; font-size: 28px; cursor: pointer;
    }
    .nav-btn:disabled { background: #27272a; border-color: #18181b; color: #71717a; cursor: not-allowed; }
  </style>
</head>
<body>

<div class="wrapper">

  <!-- ================= TOP BANNER ================= -->
  <div class="top-header">
    <div class="badge">BPSC Special Geography Series</div>
    <h1 class="title">
      Bihar Geography 100 Standard MCQs <br>
      <span>BPSC Level Online Mock Test</span>
    </h1>
    <p class="desc">
      BPSC ke kade manakon par aadharit 100 alag-alag prashn (Geological Structure, Soil, River Basin, Climate, Forests, Minerals) 20 minute live timer aur vistrit samadhan ke sath.
    </p>
    <div class="features">
      <span>⏱ 20 Minutes Countdown</span>
      <span>🔴 Red Color Question (36px)</span>
      <span>💡 100 Unique Standard Explanations</span>
    </div>
  </div>

  <!-- ================= 1. REGISTRATION GATE ================= -->
  <div id="gate-view" class="gate-card">
    <h2>Aspirant Verification</h2>
    <p>Test prarambh karne ke liye apna vivaran darj karein</p>

    <div class="form-group">
      <label>Pura Naam (Full Name)</label>
      <input type="text" id="u_name" placeholder="Apna naam darj karein" required>
    </div>

    <div class="form-group">
      <label>Mobile Number</label>
      <div class="otp-inline">
        <input type="tel" id="u_phone" maxlength="10" placeholder="10 ankon ka mobile number">
        <button class="btn-send-otp" id="btn-otp" onclick="handleSendOTP()">OTP Bhejein</button>
      </div>
    </div>

    <div class="form-group" id="otp-field" style="display: none;">
      <label>Darj Karein OTP</label>
      <input type="text" id="u_otp" maxlength="4" placeholder="4 ankon ka OTP">
      <small id="otp-hint" style="color: #ef4444; display: block; margin-top: 8px; font-size: 22px;"></small>
    </div>

    <div class="form-group">
      <label>Rajya (State)</label>
      <input type="text" id="u_state" placeholder="Jaise: Bihar">
    </div>

    <div class="form-group">
      <label>Zila (District)</label>
      <input type="text" id="u_district" placeholder="Jaise: Patna, Gaya, Samastipur">
    </div>

    <button class="btn-submit" id="btn-start" onclick="handleVerifyAndStart()">Verify & Start 20-Min Test</button>
    <div id="status-msg" style="text-align:center; font-size:24px; margin-top:14px; font-weight:700;"></div>
  </div>

  <!-- ================= 2. MOCK TEST VIEW ================= -->
  <div id="test-view">
    <header>
      <div>
        <h1 style="font-size:30px; color: #ef4444;">BPSC Bihar Geography (100 MCQs)</h1>
        <small id="user-display" style="opacity: 0.9; font-size: 22px; color: #f87171;"></small>
      </div>
      <div class="timer-box" id="timer-display">⏱ 20:00</div>
      <div class="stats">
        <span class="badge-stat badge-tot" id="stat-q">Q: 1/100</span>
        <span class="badge-stat badge-cor" id="stat-cor">Correct: 0</span>
        <span class="badge-stat badge-wro" id="stat-wro">Wrong: 0</span>
      </div>
    </header>

    <button class="palette-toggle" onclick="togglePalette()">📋 Question Palette (1-100) Dekhein / Chhupayein</button>
    <div class="palette-grid" id="palette"></div>

    <div class="card">
      <div class="q-head" id="q-head">Question 1</div>
      <div class="q-txt" id="q-txt">Question loading...</div>
      <div class="options" id="opt-container"></div>
      
      <!-- Detailed Explanation Box -->
      <div class="explanation-card" id="exp-box">
        <div class="exp-title">💡 Vistrit Vishleshan (Detailed Explanation):</div>
        <div class="exp-text" id="exp-text"></div>
      </div>
    </div>

    <div class="nav-btns">
      <button class="nav-btn" id="btn-prev" onclick="prevQ()">Previous</button>
      <button class="nav-btn" id="btn-next" onclick="nextQ()">Next</button>
    </div>
  </div>

</div>

<script>
/* ================= EMAILJS CONFIGURATION ================= */
const EMAILJS_PUBLIC_KEY = "YOUR_PUBLIC_KEY";      
const EMAILJS_SERVICE_ID = "YOUR_SERVICE_ID";      
const EMAILJS_TEMPLATE_ID = "YOUR_TEMPLATE_ID";    

(function() {
  if (typeof emailjs !== 'undefined' && EMAILJS_PUBLIC_KEY !== "YOUR_PUBLIC_KEY") {
    emailjs.init(EMAILJS_PUBLIC_KEY);
  }
})();

/* ================= OTP VERIFICATION ================= */
let generatedOTP = null;

function handleSendOTP() {
  const phone = document.getElementById("u_phone").value.trim();
  if (!/^\d{10}$/.test(phone)) {
    alert("Kripya sahi 10 ankon ka mobile number dalein.");
    return;
  }
  generatedOTP = Math.floor(1000 + Math.random() * 9000).toString();
  document.getElementById("otp-field").style.display = "block";
  document.getElementById("otp-hint").innerText = `(Testing ke liye OTP: ${generatedOTP})`;
  alert(`Aapka OTP hai: ${generatedOTP}`);
  document.getElementById("btn-otp").innerText = "Resend OTP";
}

function handleVerifyAndStart() {
  const name = document.getElementById("u_name").value.trim();
  const phone = document.getElementById("u_phone").value.trim();
  const otpEntered = document.getElementById("u_otp").value.trim();
  const state = document.getElementById("u_state").value.trim();
  const district = document.getElementById("u_district").value.trim();
  const statusMsg = document.getElementById("status-msg");

  if (!name || !phone || !state || !district) {
    alert("Kripya sabhi columns bharein.");
    return;
  }
  if (!generatedOTP || otpEntered !== generatedOTP) {
    alert("Galat OTP! Kripya sahi OTP enter karein.");
    return;
  }

  statusMsg.style.color = "#ef4444";
  statusMsg.innerText = "Data email par bheja ja raha hai...";
  document.getElementById("btn-start").disabled = true;

  const templateParams = {
    student_name: name,
    student_phone: phone,
    student_state: state,
    student_district: district,
    submission_time: new Date().toLocaleString()
  };

  if (typeof emailjs !== 'undefined' && EMAILJS_PUBLIC_KEY !== "YOUR_PUBLIC_KEY") {
    emailjs.send(EMAILJS_SERVICE_ID, EMAILJS_TEMPLATE_ID, templateParams)
      .then(() => startTest(name))
      .catch(() => startTest(name));
  } else {
    startTest(name);
  }
}

/* ================= 20-MINUTE TIMER ================= */
let timerInterval = null;
let timeLeft = 20 * 60;

function startTimer() {
  const display = document.getElementById("timer-display");
  timerInterval = setInterval(() => {
    timeLeft--;
    const minutes = Math.floor(timeLeft / 60);
    const seconds = timeLeft % 60;
    display.innerText = `⏱ ${minutes < 10 ? "0" + minutes : minutes}:${seconds < 10 ? "0" + seconds : seconds}`;

    if (timeLeft <= 300) {
      display.style.color = "#ef4444";
      display.style.borderColor = "#ef4444";
    }

    if (timeLeft <= 0) {
      clearInterval(timerInterval);
      alert("Samay samapt! Aapka test auto-submit kiya ja raha hai.");
      showFinalResult();
    }
  }, 1000);
}

function startTest(studentName) {
  document.getElementById("gate-view").style.display = "none";
  document.getElementById("test-view").style.display = "block";
  document.getElementById("user-display").innerText = `Candidate: ${studentName}`;
  initPalette();
  loadQuestion();
  startTimer();
}

/* ================= 100 DISTINCT BPSC LEVEL QUESTIONS ================= */
const rawData = [
  // 1-10: Geological Structure & Boundaries
  ["बिहार के भूगर्भीय संरचना में प्राचीनतम शैल समूह निम्नलिखित में से कौन सा है?", "विंध्यन शैल समूह", "धारवाड़ शैल समूह", "टर्शियरी शैल समूह", "क्वार्टनरी शैल समूह", "b", "बिहार के दक्षिण-पूर्व (मुंगेर, जमुई, नवादा) में स्थित धारवाड़ शैल समूह प्री-कैम्ब्रियन काल की सबसे प्राचीन संरचना है, जबकि विंध्यन शैल दक्षिण-पश्चिम (कैमूर, रोहतास) में पाए जाते हैं।"],
  ["बिहार के किस भू-आकृतिक प्रदेश में कैमूर का पठार विस्तृत है?", "धारवाड़ क्रम", "विंध्यन क्रम", "गोंडवाना क्रम", "टर्शियरी क्रम", "b", "कैमूर और रोहतास जिले में विंध्यन क्रम के चूना पत्थर, बलुआ पत्थर और शेल पाए जाते हैं, जो भवन निर्माण सामग्री के मुख्य स्रोत हैं।"],
  ["बिहार के उत्तरी-पश्चिमी भाग में स्थित 'सोमेश्वर श्रेणी' का निर्माण किस भूवैज्ञानिक काल में हुआ था?", "कार्बोनिफेरस युग", "प्लायस्टोसीन (टर्शियरी) काल", "जुरासिक काल", "क्रिटेशियस काल", "b", "पश्चिम चंपारण की सोमेश्वर और दून श्रेणी नवीन वलित शिवालिक पर्वत का विस्तार हैं, जिसका निर्माण तृतीयक (टर्शियरी/प्लायस्टोसीन) काल में हुआ था।"],
  ["बिहार का मैदानी भाग (गंगा का मैदान) भू-वैज्ञानिक दृष्टि से किस श्रेणी में आता है?", "प्रायद्वीपीय शील्ड", "अग्रगर्त (Foredeep / क्वार्टनरी निक्षेप)", "गोंडवाना भ्रंश", "रिफ्ट घाटी", "b", "गंगा का मैदान वास्तव में हिमालय के निर्माण के दौरान बने एक विशाल गर्त (Geosyncline) में नदियों द्वारा लाए गए अवसादों के जमाव से बना है।"],
  ["बिहार का अक्षांशीय विस्तार (Latitudinal Span) निम्नलिखित में से कितना है?", "24°20'10\" N से 27°31'15\" N", "21°58'10\" N से 25°12'15\" N", "23°25'00\" N से 28°10'15\" N", "22°15'10\" N से 26°30'15\" N", "a", "बिहार राज्य 24°20'10\" उत्तरी अक्षांश से 27°31'15\" उत्तरी अक्षांश के मध्य स्थित है, जिसका कुल अक्षांशीय फैलाव लगभग 3°11'05\" है।"],
  ["बिहार का कुल देशांतरीय विस्तार (Longitudinal Span) कितना है?", "80°10'50\" E से 85°12'40\" E", "83°19'50\" E से 88°17'40\" E", "82°30'00\" E से 89°15'00\" E", "84°10'20\" E से 90°12'10\" E", "b", "बिहार 83°19'50\" पूर्वी देशांतर (कैमूर) से 88°17'40\" पूर्वी देशांतर (किशनगंज) तक विस्तृत है, जिसका कुल देशांतरीय अंतर लगभग 4°57'50\" है।"],
  ["बिहार की औसत समुद्र तल से ऊंचाई (Mean Sea Level Height) लगभग कितनी है?", "150 फीट", "173 फीट (लगभग 53 मीटर)", "225 फीट", "260 फीट", "b", "सर्वे ऑफ इंडिया के अनुसार बिहार के मैदानी भाग की समुद्र तल से औसत ऊंचाई लगभग 53 मीटर यानी 173 फीट है।"],
  ["गंगा नदी बिहार राज्य को लगभग कितने प्रतिशत क्षेत्र में विभाजित करती है?", "उत्तरी मैदान (लगभग 62%) तथा दक्षिणी मैदान (लगभग 38%)", "उत्तरी मैदान (50%) तथा दक्षिणी मैदान (50%)", "उत्तरी मैदान (40%) तथा दक्षिणी मैदान (60%)", "उत्तरी मैदान (75%) तथा दक्षिणी मैदान (25%)", "a", "बिहार के कुल 94,163 वर्ग किमी क्षेत्रफल में उत्तरी मैदान लगभग 56,980 वर्ग किमी (62%) और दक्षिणी मैदान लगभग 33,670 वर्ग किमी में विस्तृत है।"],
  ["नेपाल के साथ बिहार की अंतरराष्ट्रीय सीमा की कुल लंबाई लगभग कितनी है?", "601 किमी", "729 किमी", "812 किमी", "650 किमी", "b", "बिहार की नेपाल से लगी अंतरराष्ट्रीय सीमा रेखा लगभग 726 से 729 किमी लंबी है, जिसे 'ओपन बॉर्डर' कहा जाता है।"],
  ["बिहार का वह एकमात्र जिला कौन सा है जिसकी सीमा नेपाल और उत्तर प्रदेश दोनों से स्पर्श करती है?", "गोपालगंज", "पश्चिम चंपारण", "सीतामढ़ी", "पूर्वी चंपारण", "b", "पश्चिम चंपारण उत्तर में नेपाल से तथा पश्चिम में उत्तर प्रदेश के कुशीनगर और महाराजगंज से सीमा बनाता है।"],

  // 11-20: Drainage System (Rivers)
  ["गंगा नदी बिहार के कुल 12 जिलों से प्रवाहित होती है। इसकी बिहार में कुल लंबाई कितनी है?", "345 किमी", "445 किमी", "512 किमी", "483 किमी", "b", "गंगा नदी की कुल लंबाई 2525 किमी है, जिसमें से बिहार राज्य में इसकी कुल प्रवाह लंबाई 445 किमी है।"],
  ["बिहार में गंगा नदी के प्रवाह क्षेत्र में किस जिले में इसकी लंबाई सर्वाधिक है?", "भागलपुर", "पटना (लगभग 99 किमी)", "कटिहार", "बेगूसराय", "b", "गंगा नदी पटना जिले में सर्वाधिक 99 किमी की दूरी तय करती है, इसके बाद दूसरा स्थान भागलपुर (लगभग 97 किमी) का है।"],
  ["घाघरा (सरयू) नदी बिहार में गंगा नदी से किस स्थान के निकट मिलती है?", "हाजीपुर", "मांझी (छपरा)", "दानापुर", "सोनपुर", "b", "घाघरा नदी उत्तर प्रदेश से प्रवाहित होकर सारण (छपरा) जिले के 'मांझी' नामक स्थान पर गंगा नदी में मिल जाती है।"],
  ["गंडक नदी का उद्गम नेपाल हिमालय में होता है, जहाँ इसे किस नाम से जाना जाता है?", "नारायणी और सालिग्रामी", "करनाली", "अरुण", "काली गंडकी मात्र", "a", "गंडक नदी को नेपाल के पर्वतीय भागों में सालिग्रामी (शालिग्राम पत्थरों के कारण) तथा तराई मैदान में नारायणी कहा जाता है।"],
  ["बूढ़ी गंडक (Budhi Gandak) नदी का उद्गम स्थल निम्नलिखित में से कौन सा है?", "अन्नपूर्णा श्रेणी", "चौतरवा चौर (सोमेश्वर पहाड़ी का पश्चिमी ढलान)", "महाभारत श्रेणी", "गोसाईंथान", "b", "बूढ़ी गंडक किसी विदेशी ग्लेशियर से नहीं बल्कि बिहार के पश्चिम चंपारण जिले में सोमेश्वर श्रेणी के 'चौतरवा चौर' विशंभरपुर से निकलती है।"],
  ["बिहार में सबसे तीव्र गति से जलप्रवाह करने वाली और सर्वाधिक मार्ग बदलने वाली नदी कौन सी है?", "कमला", "कोसी", "बागमती", "महानंदा", "b", "कोसी नदी नेपाल के गोसाईंथान से निकलती है और भारी गाद लाने के कारण अपना मार्ग बदलने के लिए कुख्यात है, जिससे इसे 'बिहार का शोक' कहा जाता है।"],
  ["बागमती नदी बिहार में प्रवेश करने के उपरांत अंततः किस नदी में समाहित हो जाती है?", "गंगा नदी", "कोसी नदी (अथवा बूढ़ी गंडक की शाखा)", "कमला नदी", "महानंदा", "b", "बागमती नदी सीतामढ़ी के शोरवटिया से प्रवेश करती है और आगे चलकर कमला तथा कोसी नदी प्रणाली में मिल जाती है।"],
  ["महानंदा नदी बिहार के किस जिले में सर्वप्रथम प्रवेश करती है?", "अररिया", "किशनगंज", "कटिहार", "पूर्णिया", "b", "दार्जिलिंग की महालधिराम पहाड़ियों से निकलकर महानंदा नदी बिहार के किशनगंज जिले में प्रवेश करती है और कटिहार के पास गंगा में मिलती है।"],
  ["सोन नदी बिहार के किस जिले में सर्वप्रथम प्रवेश करती है?", "बक्सर", "रोहतास", "औरंगाबाद", "भोजपुर", "b", "अमरकंटक से निकलने वाली सोन नदी बिहार के रोहतास जिले में प्रवेश करती है तथा रोहतास और औरंगाबाद के बीच प्राकृतिक सीमा बनाती है।"],
  ["पुनपुन नदी का उद्गम स्थल किस क्षेत्र में स्थित है?", "छोटा नागपुर पठार (पलामू जिला)", "विंध्याचल पर्वत", "हजारीबाग पठार", "अमरकंटक", "a", "पुनपुन नदी झारखंड के पलामू के चौराहा पहाड़ी क्षेत्र से निकलती है और फतुहा (पटना) में गंगा में मिलती है।"],

  // 21-30: Rivers, Lakes & Waterfalls
 
