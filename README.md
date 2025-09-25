<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>장혜린 | 말로 연결하고, 진심으로 전하다</title>
  <meta name="description" content="밝은 에너지와 진정성으로 마음을 움직이는 커뮤니케이터, 장혜린 포트폴리오" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Pretendard:wght@400;600;700;800&display=swap" rel="stylesheet">


  <style>
   /* ==== MOBILE-FIRST COMPACT PATCH (revised) ==== */

/* iOS가 글자 임의 확대하는 것 방지 */
html { -webkit-text-size-adjust: 100%; }

/* 1) 전체 폭: 데스크탑은 살짝 좁게, 모바일은 화면에 딱 맞게 */
:root{ --maxw: 880px; } /* 필요하면 820~920 사이로 조절해도 OK */
.container{
  width: min(100%, var(--maxw));
  margin: 0 auto;
  padding: clamp(12px, 4vw, 22px);
  box-sizing: border-box;
}

/* 2) 제목/본문 크기 & 간격 한 단계 더 다운 */
.brandline{
  font-size: clamp(20px, 5.4vw, 30px);
  line-height: 1.18;
  letter-spacing: -0.3px;
  margin: clamp(6px, 2.2vw, 10px) 0 clamp(6px, 2vw, 10px);
}
.subtitle{
  font-size: clamp(12px, 3.2vw, 14px);
  line-height: 1.5;
  max-width: 28ch;  /* 문장 폭 줄여 더 안정감 있게 */
  margin: 0 auto;
  color: var(--muted);
}
.section-title{ font-size: clamp(16px, 3.8vw, 20px); }
.card blockquote{ font-size: clamp(13px, 3.6vw, 16px); }
.mini{ font-size: clamp(11px, 3.2vw, 13px); }

/* 3) 배너/칩/SNS 버튼 컴팩트 */
.banner-inner{ padding: clamp(14px, 4.2vw, 18px); }
.chips{ gap: 6px; margin-top: 8px; justify-content: center; }
.chip{
  padding: 4px 8px;
  font-size: clamp(10px, 2.8vw, 11px);
  border-radius: 999px;
}
.sns{ gap: 8px; margin-top: 12px; justify-content: center; }
.sns .btn{
  font-size: clamp(12px, 3.1vw, 13px);
  padding: 8px 12px;
  border-width: 2px;
  border-radius: 14px;
  box-shadow: 0 4px 12px rgba(2,6,23,.05);
}

/* 4) 섹션 간격/카드 패딩 축소 */
section{ margin-top: clamp(14px, 4.6vw, 24px); }
.card{ padding: clamp(12px, 3.6vw, 18px); }

/* 5) 상단 슬라이더: 3:4 유지 + 화면 높이/폭 안 넘게 */
.photo-viewport{
  aspect-ratio: 3 / 4;
  width: min(100%, 92vw);
  max-height: min(65vh, 90svh);
  margin: 0 auto;
}
.photo-track{ height: 100%; }
#photos .photo-dots{ margin-top: 6px; }
#photos{ margin-bottom: 0; }

/* 6) 프로젝트 카드/썸네일 소형화 */
.project{ padding: clamp(10px, 2.4vw, 14px); gap: clamp(8px, 2.2vw, 12px); }
.thumb{ width: clamp(60px, 18vw, 74px); height: clamp(60px, 18vw, 74px); }

/* 7) 갤러리: 폰 2열, 태블릿 3열, 데스크탑 자동 */
.gallery{ grid-template-columns: repeat(auto-fill, minmax(160px, 1fr)); gap: clamp(10px, 3vw, 14px); }
.gallery img{ aspect-ratio: 3 / 4; }

/* 8) 모바일 강화 */
@media (max-width: 768px){
  .grid.cols-2, .grid.cols-3{ grid-template-columns: 1fr; }
  .section-title:after{ height: 3px; width: 54px; }
  footer{ font-size: 12px; margin: 32px 0 16px; }
}

/* 9) 초소형 기기(<= 390px) */
@media (max-width: 390px){
  :root{ --maxw: 100%; }
  .chips{ display: none; } /* 필요 없으면 주석 해제해서 숨김 */
}


    :root{
      --bg:#ffffff; --text:#0f172a; --muted:#64748b; --card:#f8fafc; --border:#e5e7eb;
      --vitamin:#2563eb; --mint:#22c55e; --yt:#ff0033; --ig:#d62976; --blog:#111827; --mail:#2563eb; --tel:#10b981;
      --radius:18px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:'Pretendard',system-ui,-apple-system,Segoe UI,Roboto,Noto Sans KR,sans-serif}
    a{color:var(--vitamin);text-decoration:none}
    a:hover{text-decoration:underline}
    .container{max-width:1080px;margin:0 auto;padding:24px}

    /* ======= TOP (제목 > SNS) ======= */
    .banner{position:relative;border-radius:28px;overflow:hidden;background:linear-gradient(135deg,#eaf7ff 0%, #eaf0ff 35%, #fff 100%);border:1px solid var(--border);}
    .banner-inner{padding:28px 22px;text-align:center}
    .brandline{font-size:40px;line-height:1.15;margin:10px 0 10px;font-weight:800;letter-spacing:-0.3px}
    .subtitle{margin:0;color:var(--muted);font-size:18px}
    .chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px;justify-content:center}
    .chip{padding:7px 12px;border-radius:999px;border:1px solid rgba(0,0,0,.06);background:#fff;font-size:12px;color:#334155}

    /* SNS pill style (compact) */
    .sns{display:flex;gap:10px;flex-wrap:wrap;align-items:center;justify-content:center;margin-top:18px}
    .sns .btn{
      display:inline-flex;align-items:center;justify-content:center;
      padding:8px 14px;border-radius:9999px;font-weight:600;font-size:14px;background:#fff;
      transition:.15s ease;border:2px solid currentColor;text-decoration:none;
    }
    .btn.youtube{color:var(--yt)} .btn.youtube:hover{background:rgba(255,0,51,.06)}
    .btn.insta{color:var(--ig)} .btn.insta:hover{background:rgba(214,41,118,.08)}
    .btn.blog{color:var(--blog)} .btn.blog:hover{background:rgba(17,24,39,.06)}
    .btn.mail{color:var(--mail)} .btn.mail:hover{background:rgba(37,99,235,.08)}
    .btn.tel{color:var(--tel)} .btn.tel:hover{background:rgba(16,185,129,.10)}
    @media(max-width:720px){
      .brandline{font-size:28px}
      .subtitle{font-size:15px}
      .sns .btn{font-size:13px;padding:8px 12px}
    }

    /* 공통 섹션 */
    section{margin-top:28px}
    .section-title{font-size:22px;margin:0 0 12px;text-align:center;position:relative}
    .section-title small{display:block;color:var(--muted);font-size:12px;margin-top:6px}
    .section-title:after{content:"";display:block;width:68px;height:4px;background:linear-gradient(90deg,#2563eb,#22c55e);border-radius:999px;margin:10px auto 0}
    .card{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);padding:20px;box-shadow:0 6px 20px rgba(2,6,23,.04)}

    /* ====== Photo slider (3:4) ====== */
    .photo-slider{position:relative}
    .photo-viewport{position:relative;border:1px solid var(--border);border-radius:22px;overflow:hidden;background:#fff;aspect-ratio:3/4}
    .photo-track{display:flex;transition:transform .5s ease}
    .photo-track img{flex:0 0 100%;width:100%;height:100%;object-fit:cover;display:block}
    .photo-dots{display:flex;gap:6px;justify-content:center;margin-top:10px}
    .photo-dot{width:8px;height:8px;border-radius:999px;background:#cbd5e1;opacity:.7}
    .photo-dot.active{opacity:1;background:#2563eb}
    .photo-nav{position:absolute;top:50%;transform:translateY(-50%);background:rgba(255,255,255,.92);border:1px solid var(--border);width:40px;height:40px;border-radius:999px;display:grid;place-items:center;cursor:pointer}
    .photo-nav:hover{background:#fff}
    .photo-prev{left:8px}.photo-next{right:8px}

    /* ====== Experience & Activities (mint gradient, very light) ====== */
    .acc-wrap{padding:0;border-radius:var(--radius);border:1px solid var(--border);overflow:hidden}
    details.acc{border-top:1px solid var(--border);background:linear-gradient(180deg,#ffffff, #f7fef9)}
    details.acc:first-of-type{border-top:none}
    details.acc>summary{list-style:none;cursor:pointer;padding:16px 20px;font-weight:700;display:flex;gap:10px;align-items:center}
    details.acc>summary::-webkit-details-marker{display:none}
    .acc-body{padding:10px 20px 18px 20px;border-top:1px solid var(--border)}
    .acc-body ul{margin:8px 0 0 18px;color:var(--text)}
    .acc-body li{margin:6px 0}

    /* Certificates grid (in Experience) */
    .cert-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px;padding:18px}
    .cert{border-radius:12px;padding:14px;border:1px solid var(--border);background:linear-gradient(180deg,#ffffff,#f8fafc)}
    .cert h4{margin:0;font-size:16px;font-weight:700}
    .cert p{margin:4px 0 0;font-size:14px;color:var(--muted)}
    @media(max-width:720px){.cert-grid{grid-template-columns:1fr}}

    /* ====== Activities & Awards (very light gray) ====== */
    details.acc2{border-top:1px solid var(--border);background:linear-gradient(180deg,#ffffff,#f9fbfd)}
    details.acc2:first-of-type{border-top:none}
    details.acc2>summary{list-style:none;cursor:pointer;padding:16px 20px;font-weight:700;display:flex;gap:10px;align-items:center}
    details.acc2>summary::-webkit-details-marker{display:none}
    .acc2-body{padding:10px 20px 18px 20px;border-top:1px solid var(--border)}
    .acc2-body ul{margin:8px 0 0 18px}
    .acc2-body li{margin:6px 0}

    /* ====== Works/Collab/Gallery components ====== */
    .grid{display:grid;gap:16px}
    .grid.cols-2{grid-template-columns:repeat(2,minmax(0,1fr))}
    .grid.cols-3{grid-template-columns:repeat(3,minmax(0,1fr))}
    @media(max-width:900px){.grid.cols-2,.grid.cols-3{grid-template-columns:1fr}}
    .project{border:1px solid var(--border);border-radius:14px;padding:14px;display:flex;gap:12px;align-items:center;background:#fff}
    .thumb{width:80px;height:80px;border:1px solid var(--border);border-radius:12px;background:#f0f0f0}
    .mini{font-size:14px;color:var(--muted);margin:4px 0}
    .gallery{display:grid;grid-template-columns:repeat(auto-fill,minmax(180px,1fr));gap:14px}
    .gallery img{width:100%;aspect-ratio:3/4;object-fit:cover;border-radius:14px;border:1px solid var(--border)}

    footer{margin:48px 0 24px;color:var(--muted);font-size:13px;text-align:center}
    <img src="./paris.png" alt="Paris trip">
<img src="./singapore.png" alt="Singapore trip">
<img src="./hostshow.png" alt="Hosting show">
/* ===== Responsive scale tuning (drop-in patch) ===== */
/* ==== MOBILE-FIRST COMPACT PATCH ==== */

/* ===== Force mobile-friendly scale (drop-in) ===== */

/* ===== Hero (배너) Beauty Pass – mobile 우선 균형 잡기 ===== */

/* 배너 전체 여백/반경 살짝 축소 */
.banner{ border-radius: 22px; }
.banner-inner{
  padding: clamp(14px,4.6vw,18px) clamp(14px,5vw,20px);
}

/* 메인 타이틀: 더 작게, 줄간격 촘촘, 자간 살짝 줄임 */
.brandline{
  font-size: clamp(20px, 5.8vw, 30px); /* 기존보다 한 단계 다운 */
  line-height: 1.12;
  letter-spacing: -0.4px;
  margin: clamp(6px,2vw,10px) 0 clamp(4px,1.8vw,8px);
  font-weight: 800;
}

/* 서브 타이틀: 폭 제한 + 크기 축소 */
.subtitle{
  font-size: clamp(12px, 3.4vw, 14px);
  line-height: 1.5;
  max-width: 28ch;        /* 문장 폭을 줄여 균형 */
  margin: 0 auto;         /* 가운데 정렬 */
}

/* 칩(해시태그) 더 작고 촘촘하게 */
.chips{ gap: 6px; margin-top: 8px; justify-content: center; }
.chip{
  font-size: clamp(10px, 2.8vw, 11px);
  padding: 4px 8px;
  border-radius: 999px;
}

/* SNS 버튼: 높이/글자 축소, 테두리 얇게 */
.sns{ gap: 8px; margin-top: 12px; justify-content: center; }
.sns .btn{
  font-size: clamp(12px, 3.2vw, 13px);
  padding: 8px 12px;      /* 높이 낮추기 */
  border-width: 2px;
  border-radius: 14px;
  box-shadow: 0 4px 12px rgba(2,6,23,.05);
}

/* 섹션 제목도 한 치수 줄이기 */
.section-title{
  font-size: clamp(16px, 4vw, 20px);
  margin: 0 0 8px;
}
.section-title:after{ width: 54px; height: 3px; }

/* 컨테이너 폭 살짝 더 좁게 (데스크탑에서도 과하게 커지지 않도록) */
:root{ --maxw: 900px; }
.container{ max-width: var(--maxw); }

/* 초소형 화면(<=360px)에서 더 콤팩트 */
@media (max-width: 360px){
  .brandline{ font-size: 19px; letter-spacing: -0.2px; }
  .subtitle{ font-size: 12px; }
  .sns .btn{ padding: 7px 10px; }
}


  </style>
</head>
<body>
  <div class="container">

    <!-- TOP -->
    <section class="banner">
      <div class="banner-inner">
        <h1 class="brandline">말로 연결하고, 진심으로 전하다</h1>
        <p class="subtitle">밝은 에너지와 신뢰로 사람들과 소통하는 다재다능한 크리에이터</p>
        <div class="chips">
          <span class="chip">#밝은에너지</span>
          <span class="chip">#명료한전달</span>
          <span class="chip">#신뢰감</span>
          <span class="chip">#발성·발음코칭</span>
        </div>
        <div class="sns">
          <a class="btn mail" href="mailto:dotorin33@gmail.com">Email</a>
          <a class="btn youtube" href="https://www.youtube.com/@DoTorin" target="_blank" rel="noopener">YouTube</a>
          <a class="btn insta" href="https://instagram.com/livelyrin" target="_blank" rel="noopener">Instagram</a>
          <a class="btn blog" href="#" target="_blank" rel="noopener">Blog</a>
          <a class="btn tel" href="tel:010-0000-0000">Call</a>
        </div>
      </div>
    </section>

    <!-- Photo slider (3:4) -->
    <section id="photos">
      <h2 class="section-title">Photo Highlights <small>사진 하이라이트</small></h2>
      <div class="photo-slider">
        <div class="photo-viewport">
          <div class="photo-track" id="pTrack">
            <img src="./ar01.jpeg?v=1" alt="slide 1">
<img src="./ar02.jpeg?v=1" alt="slide 2">
<img src="./ar03.jpeg?v=1" alt="slide 3">
<img src="./ar04.jpeg?v=1" alt="slide 4">
<img src="./ar05.jpeg?v=1" alt="slide 5">
<img src="./ar06.jpeg?v=1" alt="slide 6">
<img src="./ar07.jpeg?v=1" alt="slide 7">
<img src="./ar08.jpeg?v=1" alt="slide 8">
<img src="./ar09.jpeg?v=1" alt="slide 9">
<img src="./ar10.jpeg?v=1" alt="slide 10">
          </div>
          <div class="photo-nav photo-prev" id="pPrev">❮</div>
          <div class="photo-nav photo-next" id="pNext">❯</div>
        </div>
        <div class="photo-dots" id="pDots"></div>
      </div>
    </section>

    <!-- About -->
    <section id="about">
      <h2 class="section-title">About Me <small>소개</small></h2>
      <div class="card">
        <blockquote style="margin:0;font-size:18px;line-height:1.6">
          <strong>백문이 불여일견(百聞不如一見).</strong>   저는 직접 부딪히며 배우고, 그 경험을 말과 콘텐츠로 전하는 사람입니다.
        </blockquote>
      </div>
    </section>

    <!-- Experience & Activities -->
    <section id="experience">
      <h2 class="section-title">Experience & Activities <small>경험 및 활동</small></h2>
      <div class="acc-wrap">
        <details class="acc" open>
          <summary>🎤 Voice Training / 발성·발음 교육</summary>
          <div class="acc-body">
            <ul>
              <li>1:1 발성·호흡·딕션 코칭</li>
              <li>발음·억양 교정 및 전달력 향상</li>
              <li>직장인 스피치 대비 실전 피드백</li>
            </ul>
          </div>
        </details>
        <details class="acc">
          <summary>🌏 Korean Education / 한국어 교육</summary>
          <div class="acc-body">
            <ul>
              <li>1:1 튜터링, 회화·여행 한국어 수업</li>
              <li>발음·억양 교정 지도, 듣기·말하기 집중</li>
              <li>상황극 Role-play 기반 학습</li>
            </ul>
          </div>
        </details>
        <details class="acc">
          <summary>🎬 Content & Collaboration / 콘텐츠 & 협업</summary>
          <div class="acc-body">
            <ul>
              <li>브랜드 체험 리뷰, 광고·협찬 영상 제작</li>
              <li>유튜브·릴스 대본/자막 제작</li>
              <li>촬영·나레이션·편집까지 End-to-End 진행</li>
            </ul>
          </div>
        </details>
        <details class="acc">
          <summary>📜 Certificates & Licenses / 자격증</summary>
          <div class="cert-grid">
            <div class="cert"><h4>롯데 손해보험 설계사 </h4><p>자동차·화재·질병·상해보험 상품 설계, 상담 및 판매 자격</p></div>
            <div class="cert"><h4>SMAT 서비스 경영자격 1급</h4><p>서비스 마인드, 응대·마케팅 등 고객 중심 커뮤니케이션</p></div>
            <div class="cert"><h4>CS Leaders 관리사</h4><p>고객 응대·감정 조절·갈등 해결 등 실전 CS 역량</p></div>
            <div class="cert"><h4>컴퓨터 활용능력 2급</h4><p>엑셀·워드 등 문서 작업, 데이터 정리, 기획서 작성</p></div>
            <div class="cert"><h4>OA 마스터</h4><p>엑셀·파워포인트·워드 등 오피스 통합 활용 능력</p></div>
          </div>
        </details>
      </div>
    </section>

    <!-- Activities & Awards -->
    <section id="activities">
      <h2 class="section-title">Activities & Awards <small>활동 & 수상</small></h2>
      <div class="acc-wrap">
        <details class="acc2" open>
          <summary>Awards & Startup / 수상 & 창업</summary>
          <div class="acc2-body">
            <ul>
              <li>네이버 스마트스토어 인테리어 소품 쇼핑몰 운영</li>
              <li>청년 도박문제 예방 공청회 최우수상</li>
              <li>경기청년사다리 NUS 연수 우수참가자 / 경기도지사 표창</li>
              <li>교내 창업아이디어 경진대회 장려상</li>
            </ul>
          </div>
        </details>
        <details class="acc2">
          <summary>Youth Programs & Leadership 
          / 청년 프로그램 & 리더십</summary>
          <div class="acc2-body">
            <ul>
              <li>경기청년사다리 (싱가포르 국립대학교 학교 대표)</li>
              <li>경기도 일자리재단 잡아바크루 1기</li>
              <li>청년의 날 홍보대사단 부단장</li>
              <li>청년의 날 해외청년 퀴즈대회 사회자</li>
            </ul>
          </div>
        </details>
        <details class="acc2">
          <summary>Broadcast & Promotion / 방송·홍보 & 단체</summary>
          <div class="acc2-body">
            <ul>
              <li>대학교 교육방송국 JEBS 아나운서 부장</li>
              <li>오산시 소상공인 연합회 SNS 홍보단</li>
              <li>화성시 청소년수련관 대학생 서포터즈</li>
              <li>유권자정치 페스티벌 사회자</li>
            </ul>
          </div>
        </details>
        <details class="acc2">
          <summary>Youth Policy & Legislation / 청년정책 & 의정</summary>
          <div class="acc2-body">
            <ul>
              <li>청년 도박문제 예방 정책 개발 특별위원회</li>
              <li>대학생국회 산업통상자원중소벤처기업 위원회 위원 </li>
              <li>제3대 대학생국회 외교통일국방 제3위원회 법안공청회 사회자 </li>
            </ul>
          </div>
        </details>
      </div>
    </section>

    <!-- Featured Works -->
    <section id="works">
      <h2 class="section-title">Featured Works <small>대표 작업</small></h2>
      <div class="grid cols-2">
        <div class="project">
          <div class="thumb" style="background-image:url('./thumb1.jpg');background-size:cover;background-position:center"></div>
          <div>
            <div style="font-weight:700">Vision Talk </div>
            <p class="mini">경기청년 사다리 발대식ㅣ내가 꿈꾸는 말하기 방식 </p>
            <a href="#" target="_blank">영상 보기</a>
          </div>
        </div>
        <div class="project">
          <div class="thumb" style="background-image:url('./thumb2.jpg');background-size:cover;background-position:center"></div>
          <div>
            <div style="font-weight:700">My Picks</div>
            <p class="mini">내돈내산 리얼 리뷰</p>
            <a href="#" target="_blank">영상 보기</a>
          </div>
        </div>
      </div>
    </section>

    <!-- Collaboration & Contents -->
    <section id="collab">
      <h2 class="section-title">Collaboration & Contents <small>협업 & 콘텐츠</small></h2>
      <div class="grid cols-3">
        <div class="project">
          <div class="thumb" style="background-image:url('./collab1.jpg');background-size:cover;background-position:center"></div>
          <div>
            <div style="font-weight:700">브랜드 협업 콘텐츠</div>
            <p class="mini">제품/숙소 체험 기반 리뷰 · 광고/협찬 제작</p>
            <a href="#" target="_blank" rel="noopener">링크 보기</a>
          </div>
        </div>
        <div class="project">
          <div class="thumb" style="background-image:url('./collab2.jpg');background-size:cover;background-position:center"></div>
          <div>
            <div style="font-weight:700">Travel Vlogs</div>
            <p class="mini">상과 연결되는 나의 여정</p>
            <a href="#" target="_blank" rel="noopener">영상 보기</a>
          </div>
        </div>
        <div class="project">
          <div class="thumb" style="background-image:url('./collab3.jpg');background-size:cover;background-position:center"></div>
          <div>
            <div style="font-weight:700">SNS/블로그 협업</div>
            <p class="mini"> 블로그 콘텐츠 모음</p>
            <a href="#" target="_blank" rel="noopener">모아보기</a>
          </div>
        </div>
      </div>
    </section>

    <!-- My Daily Life -->
    <section id="gallery">
      <h2 class="section-title">My Daily Life <small>일상 갤러리</small></h2>
      <div class="gallery">
        <img src="./daily01.jpg" alt="일상사진1">
        <img src="./daily02.jpg" alt="일상사진2">
        <img src="./daily03.jpg" alt="일상사진3">
        <img src="./daily04.jpg" alt="일상사진4">
        <img src="./daily05.jpg" alt="일상사진5">
        <img src="./daily06.jpg" alt="일상사진6">
      </div>
      <div style="text-align:center;margin-top:10px">
        <a class="btn" style="border:1px solid var(--border);padding:10px 14px;border-radius:12px" href="#top">맨 위로</a>
      </div>
    </section>

    <footer>© <span id="year"></span> 장혜린</footer>
  </div>

  <script>
    // Year
    document.getElementById('year').textContent=new Date().getFullYear();

    // Photo slider (3:4, 3.5s autoplay)
    const pTrack=document.getElementById('pTrack');
    const pPrev=document.getElementById('pPrev');
    const pNext=document.getElementById('pNext');
    const pDots=document.getElementById('pDots');
    const pSlides=[...pTrack.children];
    let pi=0, pn=pSlides.length;
    function pGo(idx){
      pi=(idx+pn)%pn;
      pTrack.style.transform=`translateX(-${pi*100}%)`;
      pUpdateDots();
    }
    function pUpdateDots(){
      pDots.innerHTML='';
      for(let k=0;k<pn;k++){
        const d=document.createElement('div');
        d.className='photo-dot'+(k===pi?' active':'');
        d.onclick=()=>pGo(k);
        pDots.appendChild(d);
      }
    }
    pPrev?.addEventListener('click',()=>pGo(pi-1));
    pNext?.addEventListener('click',()=>pGo(pi+1));
    pUpdateDots();
    let pTimer=setInterval(()=>pGo(pi+1), 3500);
    pTrack.addEventListener('pointerdown', ()=>clearInterval(pTimer));
  </script>
</body>
</html>
