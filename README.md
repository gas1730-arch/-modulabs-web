[terms-quote.html](https://github.com/user-attachments/files/30372711/terms-quote.html)
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>모두의견적서 이용약관 | ModooLabs</title>
  <meta name="description" content="모두의 견적서 앱의 이용약관 — 시행 2026년 7월 25일" />
  <meta name="robots" content="index, follow" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Noto+Sans+KR:wght@300;400;500;700;900&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet" />

  <script>
    (function() {
      try {
        var saved = localStorage.getItem('modoolabs-theme');
        if (saved && ['dark', 'mid', 'light'].indexOf(saved) !== -1) {
          document.documentElement.setAttribute('data-theme', saved);
        }
      } catch (e) {}
    })();
  </script>

  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root, html[data-theme="mid"] {
      --bg: #252530;
      --bg-2: #2E2E3D;
      --surface: #383848;
      --border: rgba(255, 255, 255, 0.08);
      --border-strong: rgba(255, 255, 255, 0.14);
      --text: #E8E8ED;
      --text-2: #A5A5B5;
      --muted: #7A7A88;
      --cyan: #22D4C4;
      --violet: #8067FF;
      --lime: #C0EB60;
      --nav-bg: rgba(37, 37, 48, 0.75);
      --mark-bg: #252530;
      --hover-3: rgba(255, 255, 255, 0.03);
      --callout-tint: rgba(128, 103, 255, 0.12);
      --font-display: 'Space Grotesk', system-ui, sans-serif;
      --font-body: 'Noto Sans KR', system-ui, sans-serif;
      --font-mono: 'JetBrains Mono', ui-monospace, monospace;
      --ease: cubic-bezier(0.22, 1, 0.36, 1);
    }

    html[data-theme="dark"] {
      --bg: #0A0A15;
      --bg-2: #12121F;
      --surface: #191927;
      --border: rgba(255, 255, 255, 0.08);
      --border-strong: rgba(255, 255, 255, 0.16);
      --text: #F5F5F7;
      --text-2: #B8B8C8;
      --muted: #6E6E82;
      --cyan: #06E3D4;
      --violet: #7C5CFF;
      --lime: #C7F868;
      --nav-bg: rgba(10, 10, 21, 0.75);
      --mark-bg: #0A0A15;
      --hover-3: rgba(255, 255, 255, 0.02);
      --callout-tint: rgba(124, 92, 255, 0.08);
    }

    html[data-theme="light"] {
      --bg: #FAFAF7;
      --bg-2: #F2F2EC;
      --surface: #E8E8E1;
      --border: rgba(10, 10, 21, 0.08);
      --border-strong: rgba(10, 10, 21, 0.16);
      --text: #0A0A15;
      --text-2: #4A4A5C;
      --muted: #8B8B9F;
      --cyan: #06B8AB;
      --violet: #6B4CE6;
      --lime: #7EB026;
      --nav-bg: rgba(250, 250, 247, 0.75);
      --mark-bg: #FAFAF7;
      --hover-3: rgba(10, 10, 21, 0.03);
      --callout-tint: rgba(107, 76, 230, 0.10);
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: var(--font-body);
      font-weight: 400;
      line-height: 1.7;
      -webkit-font-smoothing: antialiased;
    }

    /* Ambient grain */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      pointer-events: none;
      z-index: 1;
      opacity: 0.28;
      mix-blend-mode: overlay;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' /%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.4'/%3E%3C/svg%3E");
    }

    /* NAV */
    nav {
      position: sticky;
      top: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px 48px;
      background: var(--nav-bg);
      backdrop-filter: blur(24px);
      -webkit-backdrop-filter: blur(24px);
      border-bottom: 1px solid var(--border);
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
      text-decoration: none;
      color: var(--text);
    }

    .brand-mark {
      width: 28px;
      height: 28px;
      border-radius: 8px;
      background:
        radial-gradient(circle at 30% 30%, var(--cyan) 0%, transparent 55%),
        radial-gradient(circle at 70% 70%, var(--violet) 0%, transparent 55%),
        radial-gradient(circle at 50% 90%, var(--lime) 0%, transparent 60%),
        var(--mark-bg);
      box-shadow: 0 0 24px rgba(128, 103, 255, 0.3);
    }

    .brand-name {
      font-family: var(--font-display);
      font-size: 16px;
      font-weight: 600;
      letter-spacing: -0.01em;
    }

    .nav-back {
      font-family: var(--font-display);
      font-size: 14px;
      font-weight: 500;
      color: var(--text-2);
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      gap: 6px;
      transition: color 0.2s var(--ease);
    }

    .nav-back:hover { color: var(--text); }

    /* Nav right — theme switcher + back link */
    .nav-right {
      display: flex;
      align-items: center;
      gap: 14px;
    }

    .theme-switcher {
      display: flex;
      gap: 6px;
      align-items: center;
      padding: 4px 6px;
      background: var(--hover-3);
      border-radius: 999px;
      border: 1px solid var(--border);
    }

    .theme-switcher button {
      width: 20px;
      height: 20px;
      border-radius: 50%;
      border: 1.5px solid transparent;
      cursor: pointer;
      padding: 0;
      transition: border-color 0.2s var(--ease), transform 0.2s var(--ease);
    }

    .theme-switcher button[data-set-theme="dark"] { background: #0A0A15; }
    .theme-switcher button[data-set-theme="mid"] { background: #252530; }
    .theme-switcher button[data-set-theme="light"] {
      background: #FAFAF7;
      border-color: rgba(0, 0, 0, 0.1);
    }

    .theme-switcher button:hover { transform: scale(1.15); }

    html[data-theme="dark"] .theme-switcher button[data-set-theme="dark"],
    html[data-theme="mid"] .theme-switcher button[data-set-theme="mid"],
    html:not([data-theme]) .theme-switcher button[data-set-theme="mid"],
    html[data-theme="light"] .theme-switcher button[data-set-theme="light"] {
      border-color: var(--text);
      transform: scale(1.1);
    }

    /* MAIN LAYOUT */
    main {
      position: relative;
      z-index: 2;
      max-width: 820px;
      margin: 0 auto;
      padding: 80px 48px 120px;
    }

    /* HEADER */
    .doc-eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-family: var(--font-mono);
      font-size: 12px;
      color: var(--text-2);
      padding: 6px 14px;
      border: 1px solid var(--border-strong);
      border-radius: 999px;
      margin-bottom: 32px;
      background: var(--hover-3);
    }

    .doc-eyebrow::before {
      content: '';
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: var(--lime);
      box-shadow: 0 0 8px var(--lime);
    }

    h1 {
      font-family: var(--font-display);
      font-size: clamp(36px, 5vw, 56px);
      font-weight: 500;
      line-height: 1.05;
      letter-spacing: -0.03em;
      margin-bottom: 20px;
    }

    h1 .accent {
      background: linear-gradient(120deg, var(--cyan) 0%, var(--violet) 55%, var(--lime) 100%);
      -webkit-background-clip: text;
      background-clip: text;
      -webkit-text-fill-color: transparent;
      font-style: italic;
      font-weight: 400;
    }

    .doc-lead {
      color: var(--text-2);
      font-size: 16px;
      margin-bottom: 40px;
    }

    /* META BOX */
    .meta-box {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
      padding: 24px;
      background: var(--bg-2);
      border: 1px solid var(--border);
      border-radius: 16px;
      margin-bottom: 60px;
    }

    .meta-item {
      font-family: var(--font-mono);
      font-size: 12px;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 0.06em;
    }

    .meta-item b {
      display: block;
      font-family: var(--font-body);
      color: var(--text);
      font-size: 15px;
      font-weight: 500;
      margin-top: 6px;
      text-transform: none;
      letter-spacing: 0;
    }

    /* SECTIONS */
    h2 {
      font-family: var(--font-display);
      font-size: 26px;
      font-weight: 600;
      letter-spacing: -0.02em;
      margin-top: 60px;
      margin-bottom: 20px;
      padding-top: 32px;
      border-top: 1px solid var(--border);
      line-height: 1.3;
    }

    h2 .num {
      font-family: var(--font-mono);
      font-size: 13px;
      color: var(--text-2);
      font-weight: 400;
      display: block;
      margin-bottom: 8px;
      letter-spacing: 0.05em;
    }

    h3 {
      font-family: var(--font-display);
      font-size: 17px;
      font-weight: 600;
      color: var(--text);
      margin-top: 28px;
      margin-bottom: 12px;
      letter-spacing: -0.01em;
    }

    p {
      color: var(--text-2);
      font-size: 15px;
      margin-bottom: 16px;
    }

    ul, ol {
      color: var(--text-2);
      font-size: 15px;
      margin-bottom: 20px;
      padding-left: 22px;
    }

    li {
      margin-bottom: 8px;
      line-height: 1.7;
    }

    li::marker {
      color: var(--muted);
    }

    strong {
      color: var(--text);
      font-weight: 600;
    }

    /* NOTE / CALLOUT */
    .callout {
      padding: 20px 24px;
      background:
        radial-gradient(circle at 20% 30%, var(--callout-tint), transparent 60%),
        var(--bg-2);
      border: 1px solid var(--border);
      border-left: 3px solid var(--violet);
      border-radius: 12px;
      margin: 24px 0;
      font-size: 14px;
      color: var(--text-2);
    }

    /* CONTACT TABLE */
    .contact-table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
      background: var(--bg-2);
      border: 1px solid var(--border);
      border-radius: 12px;
      overflow: hidden;
      font-size: 14px;
    }

    .contact-table th,
    .contact-table td {
      padding: 14px 20px;
      text-align: left;
      border-bottom: 1px solid var(--border);
    }

    .contact-table th {
      font-family: var(--font-display);
      font-size: 13px;
      font-weight: 500;
      color: var(--text-2);
      background: var(--hover-3);
      width: 30%;
    }

    .contact-table td {
      color: var(--text);
    }

    .contact-table tr:last-child th,
    .contact-table tr:last-child td {
      border-bottom: none;
    }

    .contact-table a {
      color: var(--cyan);
      text-decoration: none;
      transition: opacity 0.2s var(--ease);
    }

    .contact-table a:hover { opacity: 0.8; }

    /* FOOTER */
    footer {
      padding: 40px 48px;
      border-top: 1px solid var(--border);
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-family: var(--font-mono);
      font-size: 12px;
      color: var(--muted);
      position: relative;
      z-index: 2;
      max-width: 820px;
      margin: 0 auto;
    }

    footer .brand {
      opacity: 0.7;
    }

    footer a {
      color: var(--muted);
      text-decoration: none;
      transition: color 0.2s var(--ease);
    }

    footer a:hover { color: var(--text); }

    /* RESPONSIVE */
    @media (max-width: 700px) {
      nav { padding: 16px 24px; }
      main { padding: 48px 24px 80px; }
      footer {
        padding: 32px 24px;
        flex-direction: column;
        gap: 16px;
        text-align: center;
      }
      h2 { font-size: 22px; }
      .contact-table th { width: 35%; }
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav>
    <a href="/" class="brand">
      <div class="brand-mark"></div>
      <span class="brand-name">ModooLabs</span>
    </a>
    <div class="nav-right">
      <div class="theme-switcher" role="group" aria-label="테마 선택">
        <button type="button" data-set-theme="dark" aria-label="다크 테마" title="다크"></button>
        <button type="button" data-set-theme="mid" aria-label="미드 테마" title="미드"></button>
        <button type="button" data-set-theme="light" aria-label="라이트 테마" title="라이트"></button>
      </div>
      <a href="/" class="nav-back">← 홈으로</a>
    </div>
  </nav>

  <main>
    <div class="doc-eyebrow">Legal · Terms of Service</div>

    <h1>
      모두의 견적서<br>
      <span class="accent">이용약관</span>
    </h1>

    <p class="doc-lead">
      모두의 견적서 앱의 이용에 관한 이용자와 서비스 제공자의 권리·의무·책임사항을 안내드립니다.
    </p>

    <div class="meta-box">
      <div class="meta-item">앱명<b>모두의 견적서</b></div>
      <div class="meta-item">서비스 제공자<b>김진춘</b></div>
      <div class="meta-item">시행일<b>2026년 7월 25일</b></div>
      <div class="meta-item">문의<b>gas1730@gmail.com</b></div>
    </div>

    <!-- 1 -->
    <h2><span class="num">01</span>목적</h2>
    <p>
      본 약관은 모두의 견적서(Everyone's Quote, 이하 "서비스")를 운영하는 서비스 제공자(이하 "회사")가 제공하는 모바일 애플리케이션 및 관련 서비스의 이용과 관련하여
      회사와 이용자 사이의 권리, 의무, 책임사항 및 기타 필요한 사항을 정하는 것을 목적으로 합니다.
    </p>

    <!-- 2 -->
    <h2><span class="num">02</span>용어의 정의</h2>
    <p>① 본 약관에서 사용하는 용어의 뜻은 다음과 같습니다.</p>
    <ul>
      <li><strong>"회사"</strong>란 본 서비스를 운영하는 서비스 제공자(개발자 김진춘, 연락처 <a href="mailto:gas1730@gmail.com" style="color: var(--cyan); text-decoration: none;">gas1730@gmail.com</a>)를 말합니다.</li>
      <li><strong>"서비스"</strong>란 회사가 제공하는 모두의 견적서 모바일 애플리케이션 및 이에 부수되는 견적서 작성, 방문예약, 고객 관리, 일정 관리, 문서 저장 및 공유 등의 기능을 말합니다.</li>
      <li><strong>"이용자"</strong>란 본 약관에 동의하고 회원가입을 완료하여 서비스를 이용하는 자를 말합니다.</li>
      <li><strong>"무료체험"</strong>이란 회원가입 후 견적서와 방문예약의 신규 작성 건수를 합산하여 최초 10건까지 제공되는 1회성 무료 이용 혜택을 말합니다. 무료체험에는 별도의 기간 제한이 없으며, 해당 10건을 모두 사용할 때까지 프리미엄과 동일한 범위의 기능을 이용할 수 있습니다.</li>
      <li><strong>"프리미엄" 또는 "유료 서비스"</strong>란 이용자가 Google Play 인앱 정기결제를 통하여 월 이용료를 결제하고 서비스의 유료 기능을 제한 없이 이용할 수 있는 구독 상품을 말합니다.</li>
      <li><strong>"포인트"</strong>란 무료체험 10건을 모두 사용한 이용자에게 리워드 광고 시청 등의 조건에 따라 회사가 무상으로 지급하는 서비스 이용 수단을 말합니다.</li>
      <li>포인트 1개는 견적서 또는 방문예약 1건을 추가로 작성할 수 있는 서비스상 이용 권한을 의미하며, 현금이나 전자화폐 등의 금전적 가치를 가지는 지급수단이 아닙니다.</li>
      <li><strong>"리워드 광고"</strong>란 광고를 정상적으로 시청한 이용자에게 회사가 정한 기준에 따라 포인트 등의 혜택을 제공하는 광고를 말합니다.</li>
    </ul>
    <p>② 본 조에서 정하지 않은 용어의 의미는 관계 법령, Google Play의 관련 정책 및 서비스 내 안내에서 정하는 바에 따릅니다.</p>

    <!-- 3 -->
    <h2><span class="num">03</span>약관의 효력 및 변경</h2>
    <p>① 본 약관은 서비스 화면 또는 이에 연결된 화면에 게시하거나 기타 적절한 방법으로 이용자에게 알림으로써 효력이 발생합니다.</p>
    <p>② 회사는 관련 법령을 위반하지 않는 범위에서 본 약관을 변경할 수 있습니다.</p>
    <p>③ 회사가 약관을 변경하는 경우 변경 내용과 시행일을 서비스 내 공지 등의 방법으로 시행일 전에 안내합니다.</p>
    <p>④ 이용자에게 불리하거나 권리 및 의무에 중대한 영향을 미치는 변경사항은 특별한 사정이 없는 한 시행일 30일 전부터 안내하며, 관계 법령에서 별도의 고지 또는 동의를 요구하는 경우에는 해당 법령에 따릅니다.</p>
    <p>⑤ 변경된 약관의 내용이 이용자에게 불리하거나 중요한 사항에 해당하는 경우 회사는 서비스 화면, 알림 등 이용자가 쉽게 확인할 수 있는 방법으로 이를 안내합니다.</p>
    <p>⑥ 변경된 약관에 동의하지 않는 이용자는 서비스 이용계약을 해지하거나 회원탈퇴를 할 수 있습니다.</p>
    <p>⑦ 본 약관의 내용과 관계 법령의 강행규정이 충돌하는 경우 관계 법령이 우선 적용됩니다.</p>

    <!-- 4 -->
    <h2><span class="num">04</span>서비스의 내용</h2>

    <h3>1) 서비스의 기본 기능</h3>
    <p>① 회사는 이용자에게 다음과 같은 기능을 제공할 수 있습니다.</p>
    <ul>
      <li>견적서 작성 및 관리</li>
      <li>방문예약 작성 및 관리</li>
      <li>고객 정보 관리</li>
      <li>일정 관리</li>
      <li>견적서, 세금계산서, 간이영수증, 거래명세서 등 문서 작성 및 PDF 저장 또는 공유</li>
      <li>작업 내용의 직원 공유</li>
      <li>문자 안내 및 문자 문구 템플릿 기능</li>
      <li>리워드 광고 시청 및 포인트 지급</li>
      <li>기타 회사가 추가로 제공하는 기능</li>
    </ul>
    <p>② 서비스의 세부 기능 및 화면 구성은 서비스 개선, 운영상 필요 또는 관계 법령과 플랫폼 정책의 변경 등에 따라 변경될 수 있습니다.</p>

    <h3>2) 무료체험</h3>
    <p>③ 회원가입 후 이용자는 견적서와 방문예약의 신규 작성 건수를 합산하여 최초 10건까지 무료체험 혜택을 받을 수 있습니다.</p>
    <p>④ 무료체험은 기간 제한 없이 평생 1회 제공되는 혜택이며, 무료체험 이용 가능 건수가 남아 있는 동안에는 프리미엄 이용자와 동일한 범위의 기능을 이용할 수 있습니다.</p>
    <p>⑤ 무료체험은 이용자 1인을 기준으로 제공되며, 무료체험 혜택을 반복적으로 받기 위한 회원가입, 탈퇴, 계정 생성 또는 기타 비정상적인 방법의 이용은 제한될 수 있습니다.</p>

    <h3>3) 무료체험 소진 후 무료 이용</h3>
    <p>⑥ 최초 10건의 무료체험을 모두 사용한 이후에도 이용자는 회사가 무료로 제공하는 기능을 계속 이용할 수 있습니다.</p>
    <p>⑦ 이용자는 리워드 광고를 시청하여 포인트를 획득할 수 있으며, 포인트 1개를 사용하여 견적서 또는 방문예약 1건을 추가 작성할 수 있습니다.</p>
    <p>⑧ 리워드 광고 시청을 통한 포인트 획득 기회는 하루 최대 10회까지 제공됩니다. 광고 제공사의 광고 재고 부족, 네트워크 상태 또는 기타 기술적인 사유로 실제 시청 가능한 광고 수가 하루 최대 횟수보다 적을 수 있습니다.</p>
    <p>⑨ 무료체험 소진 후 다음 기능은 무료 이용자의 경우 각각 하루 1회로 이용이 제한될 수 있습니다.</p>
    <ul>
      <li>세금계산서 PDF 저장 및 공유</li>
      <li>간이영수증 PDF 저장 및 공유</li>
      <li>거래명세서 PDF 저장 및 공유</li>
      <li>직원에게 작업 내용 공유하기</li>
    </ul>
    <p>⑩ 다음 기능은 무료체험 소진 여부와 관계없이 무료로 제공됩니다.</p>
    <ul>
      <li>견적서 PDF 저장 및 공유</li>
      <li>이용자가 직접 문자를 작성하여 발송하는 기능</li>
    </ul>
    <p>단, 문자 발송 과정에서 이동통신사 또는 외부 서비스에 의해 발생하는 문자 발송료, 데이터 이용료 등은 이용자가 부담할 수 있습니다.</p>
    <p>⑪ 문자 안내 문구를 자동으로 제공하거나 완성하는 문자 템플릿 기능은 무료체험 소진 후 프리미엄 이용자에게만 제공될 수 있습니다.</p>

    <h3>4) 프리미엄 이용</h3>
    <p>⑫ 프리미엄 이용자는 구독이 정상적으로 유지되는 기간 동안 무료 이용자에게 적용되는 작성 건수, 문서 저장 및 공유 횟수, 직원 공유 횟수, 문자 템플릿 등의 제한 없이 회사가 정한 프리미엄 기능을 이용할 수 있습니다.</p>
    <p>⑬ 서비스에서 작성되는 세금계산서, 영수증, 거래명세서 등의 문서 기능은 이용자의 업무 편의를 위한 문서 작성 지원 기능입니다. 관계 법령상 별도의 발행, 신고, 보관 또는 전송 절차가 요구되는 경우 이용자는 해당 법령에 따른 의무를 직접 확인하고 이행하여야 합니다.</p>

    <!-- 5 -->
    <h2><span class="num">05</span>무상 포인트의 지급 및 소멸</h2>
    <p>① 포인트는 회사가 이용자에게 무상으로 제공하는 서비스 이용 혜택으로, 이용자가 금전을 지급하여 구매하는 상품이 아닙니다.</p>
    <p>② 무료체험을 모두 사용한 이용자는 회사가 제공하는 리워드 광고를 정상적으로 시청한 경우 회사가 정한 기준에 따라 포인트를 지급받을 수 있습니다.</p>
    <p>③ 리워드 광고를 통해 포인트를 받을 수 있는 횟수는 하루 최대 10회입니다.</p>
    <p>④ 포인트 1개를 사용하면 견적서 또는 방문예약 1건을 추가 작성할 수 있습니다.</p>

    <div class="callout">
      <strong>포인트 유효기간 안내</strong><br>
      리워드 광고를 통해 지급된 포인트의 유효기간은 지급 당일에 한정됩니다. 지급된 포인트를 당일 사용하지 않은 경우 대한민국 표준시(KST) 기준으로 해당 날짜가 종료되고 다음 날이 시작되는 시점에 자동으로 소멸합니다.
    </div>

    <p>⑦ 소멸된 포인트는 원칙적으로 복구되지 않습니다. 다만, 회사의 명백한 시스템 오류 등 회사의 귀책사유로 포인트를 정상적으로 사용할 수 없었던 경우 회사가 별도의 보상 또는 복구 조치를 할 수 있습니다.</p>
    <p>⑧ 포인트는 현금으로 환전, 환불하거나 다른 이용자에게 양도할 수 없으며, 서비스 외의 용도로 사용할 수 없습니다.</p>
    <p>⑨ 회사는 서비스 운영, 광고 정책 변경, 광고 제공업체의 정책 변경, 관계 법령 변경 등의 사유가 있는 경우 다음 사항을 변경할 수 있습니다.</p>
    <ul>
      <li>광고 시청 가능 횟수</li>
      <li>광고 1회당 지급되는 포인트 수</li>
      <li>포인트 사용 조건</li>
      <li>포인트 유효기간</li>
      <li>기타 포인트 운영에 관한 사항</li>
    </ul>
    <p>⑩ 회사가 이용자에게 불리하게 포인트 정책을 변경하는 경우 시행 전에 서비스 내 공지 등의 방법으로 변경 내용을 안내합니다. 이용자의 권리에 중대한 영향을 미치는 변경은 특별한 사정이 없는 한 시행일 30일 전에 안내합니다.</p>
    <p>⑪ 포인트는 무상으로 제공되는 혜택이라는 이유만으로 회사가 이미 이용자에게 제공된 권리를 자의적으로 박탈하지 않으며, 관계 법령에서 이용자의 권리를 보호하도록 정한 경우에는 해당 법령이 우선 적용됩니다.</p>

    <!-- 6 -->
    <h2><span class="num">06</span>유료 서비스 이용 및 결제</h2>
    <p>① 프리미엄 구독의 이용요금은 <strong>월 6,900원</strong>입니다.</p>
    <p>② 프리미엄은 Google Play 인앱 정기결제 시스템을 통하여 결제됩니다.</p>
    <p>③ 실제 결제금액, 결제일, 세금 포함 여부 및 결제수단에 관한 세부사항은 결제 당시 Google Play 화면에 표시되는 내용을 따릅니다.</p>
    <p>④ 프리미엄 구독은 월 단위 정기결제 상품으로, 이용자가 구독을 취소하지 않는 경우 Google Play의 정기결제 정책에 따라 다음 결제 기간의 이용요금이 자동으로 결제될 수 있습니다.</p>
    <p>⑤ 이용자는 Google Play의 정기결제 관리 화면에서 언제든지 구독의 자동갱신을 취소할 수 있습니다.</p>

    <div class="callout">
      <strong>중요 — 앱 삭제와 구독 취소는 다릅니다</strong><br>
      앱을 삭제하는 것만으로는 Google Play 정기결제가 자동으로 취소되지 않습니다. 이용자는 Google Play 정기결제 관리 화면에서 구독 상태 및 취소 여부를 직접 확인하여야 합니다.
    </div>

    <p>⑦ 구독을 취소한 경우 특별한 사정이 없는 한 이미 결제가 완료된 구독 기간이 종료될 때까지 프리미엄 기능을 이용할 수 있으며, 이후 자동갱신이 중단됩니다. 단, 환불 또는 구독 종료 처리 방식은 Google Play 정책 및 관계 법령에 따라 달라질 수 있습니다.</p>
    <p>⑧ 회사가 프리미엄 이용요금을 변경하는 경우 관계 법령 및 Google Play 정책에서 요구하는 방법과 절차에 따라 이용자에게 안내하며, 이용자의 별도 동의가 필요한 경우 해당 동의를 받습니다.</p>
    <p>⑨ 결제수단 오류, Google Play 계정 문제, 결제 승인 실패 등 회사가 직접 통제하기 어려운 사유로 결제가 완료되지 않는 경우 프리미엄 이용이 제한되거나 종료될 수 있습니다.</p>

    <!-- 7 -->
    <h2><span class="num">07</span>환불 정책</h2>
    <p>① 프리미엄 구독의 결제 취소, 환불 및 관련 절차는 원칙적으로 Google Play의 환불 정책과 결제 시스템을 따릅니다.</p>
    <p>② 이용자는 Google Play에서 제공하는 환불 신청 절차를 통하여 환불을 요청할 수 있습니다.</p>
    <p>③ Google Play 정책상 회사에 직접 문의하도록 되어 있는 경우 이용자는 회사에 환불 관련 문의를 할 수 있으며, 회사는 Google Play 정책 및 관계 법령에 따라 이를 처리합니다.</p>
    <p>④ 구독을 취소하는 것과 이미 결제된 금액을 환불받는 것은 서로 다른 절차일 수 있습니다. 구독 취소만으로 이미 결제된 이용요금이 자동으로 환불되는 것은 아닙니다.</p>
    <p>⑤ 이용자의 단순 변심, 사용 여부, 결제 후 경과 기간 등에 따른 구체적인 환불 가능 여부는 Google Play 환불 정책 및 관계 법령에 따라 판단됩니다.</p>
    <p>⑥ 서비스 장애, 결제 오류, 중복 결제 또는 회사의 귀책사유 등으로 관계 법령상 환불, 계약 해제 또는 손해배상 등의 권리가 인정되는 경우 본 약관은 이용자의 해당 권리를 제한하지 않습니다.</p>
    <p>⑦ 본 조의 내용과 「전자상거래 등에서의 소비자보호에 관한 법률」 등 관계 법령의 강행규정이 충돌하는 경우 관계 법령이 우선 적용됩니다.</p>

    <!-- 8 -->
    <h2><span class="num">08</span>회사의 의무</h2>
    <p>① 회사는 관계 법령과 본 약관을 준수하며 안정적으로 서비스를 제공하기 위하여 합리적인 노력을 합니다.</p>
    <p>② 회사는 이용자의 개인정보를 관계 법령 및 별도로 공개하는 <a href="/privacy-quote.html" style="color: var(--cyan); text-decoration: none;">개인정보처리방침</a>에 따라 보호합니다.</p>
    <p>③ 회사는 이용자로부터 서비스 장애, 결제 오류 또는 기타 정당한 의견이나 불만이 접수된 경우 합리적인 범위에서 이를 확인하고 처리하도록 노력합니다.</p>
    <p>④ 회사는 유료 서비스의 이용요금, 자동갱신 여부, 무료 및 유료 기능의 차이 등 이용자의 계약 여부 판단에 중요한 사항을 이용자가 쉽게 확인할 수 있도록 안내합니다.</p>
    <p>⑤ 회사는 서비스 장애 또는 운영상 중요한 변경이 발생하는 경우 합리적으로 가능한 범위에서 이용자에게 관련 내용을 안내합니다.</p>

    <!-- 9 -->
    <h2><span class="num">09</span>이용자의 의무</h2>
    <p>① 이용자는 서비스 이용 시 관계 법령, 본 약관 및 서비스 내 안내사항을 준수하여야 합니다.</p>
    <p>② 이용자는 회원가입 및 서비스 이용 과정에서 사실에 부합하는 정보를 제공하여야 하며, 자신의 계정과 인증정보를 안전하게 관리할 책임이 있습니다.</p>
    <p>③ 이용자는 다음 행위를 하여서는 안 됩니다.</p>
    <ul>
      <li>타인의 계정 또는 개인정보를 무단으로 사용하는 행위</li>
      <li>무료체험 혜택을 반복하여 받기 위한 목적으로 다수의 계정을 생성하거나 탈퇴 및 재가입을 반복하는 행위</li>
      <li>앱 또는 단말기 정보를 조작하여 무료체험 이용 건수나 포인트를 부정하게 취득하는 행위</li>
      <li>자동화 프로그램, 매크로, 비정상적인 기기 조작 등을 이용하여 광고를 반복 시청하거나 포인트를 부정 취득하는 행위</li>
      <li>광고 시청, 노출, 클릭 등의 실적을 인위적으로 증가시키는 행위</li>
      <li>본인 또는 제3자에게 광고 클릭을 유도하거나 광고 시스템을 어뷰징하는 행위</li>
      <li>서비스의 정상적인 운영을 방해하거나 서버, 네트워크 또는 보안시스템에 부당하게 접근하는 행위</li>
      <li>앱을 변조하거나 회사의 기술적 보호조치를 우회하는 행위</li>
      <li>회사 또는 제3자의 저작권, 상표권, 개인정보 기타 권리를 침해하는 행위</li>
      <li>불법적인 목적으로 서비스를 사용하는 행위</li>
      <li>그 밖에 관계 법령 또는 사회질서에 위반되는 행위</li>
    </ul>
    <p>④ 이용자가 고객, 직원 또는 제3자의 이름, 전화번호, 주소 등 개인정보를 서비스에 입력하는 경우 해당 정보를 적법하게 수집하고 이용할 수 있는 권한 또는 법적 근거를 갖추어야 합니다.</p>
    <p>⑤ 이용자는 서비스를 이용하여 작성한 견적서, 거래명세서, 세금 관련 문서 등에 입력되는 사업자정보, 금액, 세율, 고객정보 및 기타 내용의 정확성을 확인할 책임이 있습니다.</p>

    <!-- 10 -->
    <h2><span class="num">10</span>서비스 이용제한 및 계약해지</h2>
    <p>① 이용자는 언제든지 회사가 제공하는 방법을 통하여 서비스 이용계약을 해지하거나 회원탈퇴를 할 수 있습니다.</p>
    <p>② 회사는 이용자가 다음 각 호에 해당하는 경우 서비스 이용을 일시적으로 제한하거나 이용계약을 해지할 수 있습니다.</p>
    <ul>
      <li>본 약관 또는 관계 법령을 위반한 경우</li>
      <li>무료체험 또는 포인트를 부정한 방법으로 획득하거나 사용한 경우</li>
      <li>광고 시스템을 조작하거나 어뷰징한 경우</li>
      <li>다른 이용자의 서비스 이용을 방해한 경우</li>
      <li>회사의 시스템 또는 서비스 운영에 중대한 피해를 발생시킨 경우</li>
      <li>기타 서비스 이용을 계속 허용하기 어려운 중대한 사유가 있는 경우</li>
    </ul>
    <p>③ 회사는 이용제한 또는 계약해지 전에 가능한 경우 그 사유와 내용을 이용자에게 안내하고 소명할 기회를 제공합니다. 다만, 긴급한 보안 문제, 시스템 공격, 명백한 불법행위 등 즉시 조치가 필요한 경우에는 먼저 이용을 제한한 후 그 사유를 안내할 수 있습니다.</p>
    <p>④ 이용자는 회사의 이용제한 조치에 대하여 고객지원 등을 통해 이의를 제기할 수 있습니다.</p>
    <p>⑤ 회원탈퇴 또는 서비스 이용계약 해지와 Google Play의 프리미엄 정기결제 취소는 별개의 절차일 수 있습니다. 프리미엄 이용자는 회원탈퇴 시 Google Play 정기결제 관리 화면에서 구독 상태를 반드시 확인하는 것이 필요합니다.</p>

    <!-- 11 -->
    <h2><span class="num">11</span>면책조항</h2>
    <p>① 회사는 천재지변, 전쟁, 정전, 통신망 장애, 클라우드 또는 외부 서비스 장애, Google Play 장애, 광고 제공업체의 장애 등 회사가 합리적으로 통제하기 어려운 사유로 서비스를 제공할 수 없는 경우 그 책임이 제한될 수 있습니다.</p>
    <p>② 서비스의 점검, 업데이트, 서버 장애, 네트워크 상태 또는 기술적인 문제로 일부 기능이 일시적으로 제한될 수 있습니다.</p>
    <p>③ 리워드 광고의 제공 여부와 광고 재고는 광고 제공업체의 사정에 영향을 받을 수 있으므로 회사는 모든 이용자에게 매일 최대 광고 시청 횟수만큼 광고가 반드시 제공되는 것을 보장하지 않습니다.</p>
    <p>④ 광고 시청으로 제공되는 포인트는 이용자가 금전을 지급하여 구매한 것이 아닌 무상 혜택입니다. 광고 재고 부족, 광고 제공업체 정책 변경 등 회사가 통제하기 어려운 사유로 포인트 획득 기회가 제한되는 경우 회사는 해당 포인트에 상응하는 현금 지급 의무를 부담하지 않습니다.</p>
    <p>⑤ 다만, 회사의 고의 또는 중대한 과실로 이용자에게 손해가 발생하거나 관계 법령에 따라 회사가 책임을 부담하여야 하는 경우에는 본 조를 이유로 해당 책임을 배제하지 않습니다.</p>
    <p>⑥ 회사는 이용자가 서비스에 입력한 견적 내용, 고객정보, 일정, 금액, 세율 기타 정보의 사실 여부 또는 정확성을 보증하지 않습니다.</p>
    <p>⑦ 서비스가 제공하는 견적서, 세금계산서, 간이영수증, 거래명세서 등의 문서 작성 기능은 이용자의 업무 편의를 지원하기 위한 기능입니다. 회사가 별도로 명시하지 않는 한 회계, 세무, 법률 신고 또는 세법상 적법한 문서 발행 절차를 대행하거나 그 적법성을 보증하는 서비스를 의미하지 않습니다.</p>
    <p>⑧ 이용자는 작성된 문서를 실제 거래, 세무처리 또는 신고 등에 사용하기 전에 관련 내용과 관계 법령상 요건을 직접 확인하여야 합니다.</p>
    <p>⑨ 회사는 이용자와 이용자의 고객, 직원 또는 제3자 사이에서 발생한 거래, 계약, 공사, 대금 지급, 작업 내용 등에 직접 당사자로 참여하지 않으며, 회사의 귀책사유가 없는 한 그 분쟁에 대하여 책임을 부담하지 않습니다.</p>
    <p>⑩ 본 조는 관계 법령에 따라 이용자에게 인정되는 손해배상, 계약 해제, 환불 기타 권리를 제한하는 것으로 해석되지 않습니다.</p>

    <!-- 12 -->
    <h2><span class="num">12</span>분쟁해결 및 준거법</h2>
    <p>① 회사와 이용자 사이에 서비스 이용과 관련하여 분쟁이 발생한 경우 회사와 이용자는 원만한 해결을 위해 상호 협의하도록 노력합니다.</p>
    <p>② 이용자는 서비스 이용과 관련한 불만 또는 피해구제 요청을 회사의 고객지원 창구를 통하여 제기할 수 있습니다.</p>
    <p>③ 당사자 사이의 협의로 분쟁이 해결되지 않는 경우 관계 법령에 따라 소비자분쟁조정기관 또는 관할 법원 등을 통한 분쟁해결 절차를 이용할 수 있습니다.</p>
    <p>④ 본 약관 및 서비스 이용계약에는 대한민국 법령을 적용합니다.</p>
    <p>⑤ 소송이 필요한 경우 관할 법원은 「민사소송법」 등 대한민국 관계 법령이 정하는 바에 따릅니다.</p>

    <!-- 13 -->
    <h2><span class="num">13</span>문의처</h2>
    <table class="contact-table">
      <tr>
        <th>서비스 제공자</th>
        <td>김진춘</td>
      </tr>
      <tr>
        <th>이메일</th>
        <td><a href="mailto:gas1730@gmail.com">gas1730@gmail.com</a></td>
      </tr>
      <tr>
        <th>관련 문서</th>
        <td><a href="/privacy-quote.html">개인정보처리방침</a></td>
      </tr>
    </table>
    <p>본 약관과 관련한 문의사항, 서비스 장애 신고, 환불 요청 등은 위 이메일로 접수해 주시기 바랍니다.</p>

    <!-- 부칙 -->
    <h2><span class="num">부칙</span>시행일 및 경과조치</h2>
    <h3>1) 시행일</h3>
    <p>본 약관은 <strong>2026년 7월 25일</strong>부터 시행합니다.</p>

    <h3>2) 기존 이용자에 대한 적용</h3>
    <p>본 약관 시행 전에 가입한 이용자에 대해서도 시행일 이후의 서비스 이용에 본 약관이 적용됩니다. 다만, 이용자에게 이미 발생한 권리 또는 관계 법령상 보호되는 권리를 소급하여 부당하게 제한하지 않습니다.</p>

  </main>

  <!-- FOOTER -->
  <footer>
    <div class="brand">
      <div class="brand-mark"></div>
      <span class="brand-name">ModooLabs</span>
    </div>
    <div>© 2026 ModooLabs · <a href="/">modooscoin.com</a></div>
  </footer>

  <!-- Theme Switcher Script -->
  <script>
    (function() {
      var buttons = document.querySelectorAll('.theme-switcher button[data-set-theme]');
      buttons.forEach(function(btn) {
        btn.addEventListener('click', function() {
          var theme = btn.getAttribute('data-set-theme');
          document.documentElement.setAttribute('data-theme', theme);
          try {
            localStorage.setItem('modoolabs-theme', theme);
          } catch (e) {}
        });
      });
    })();
  </script>

</body>
</html>
