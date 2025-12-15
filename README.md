# parousia
star rail
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8" />
<title>파루시아 </title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="css/wiki.css" />
</head>
<body>

  <!-- ===== 헤더 ===== -->
  <header class="wiki-header">
    <h1>파루시아 <span class="en">parousia</span></h1>
    <p class="subtitle">붕괴: 스타레일 플레이어블 캐릭터</p>
  </header>

  <!-- ===== 인포박스 ===== -->
  <aside class="infobox">
    <img src="img/parousia.png" alt="파루시아" />
    <table>
      <tr><th>이름</th><td>파루시아</td></tr>
      <tr><th>본명</th><td>휘포스타시스 파루시아</td></tr>
      <tr><th>성별</th><td>여성</td></tr>
      <tr><th>소속</th><td>차원 방랑자</td></tr>
      <tr><th>속성</th><td>허수</td></tr>
      <tr><th>운명의 길</th><td>지식</td></tr>
      <tr><th>출시일</th><td>2025-11-11</td></tr>
    </table>
  </aside>

  <!-- ===== 본문 ===== -->
  <main class="wiki-content">

    <!-- 개요 -->
    <section id="overview">
      <h2>개요</h2>
      <blockquote>
        <p>「그대의 최초의 교파는 멸망했다」</p>
      </blockquote>
      <p>
        「신이 없으면 신앙심도 무의미 하죠. 이건 당연한 논리입니다.」
        </p>
    </section>

    <!-- 관련 매체 -->
    <section id="media">
      <h2>관련 매체</h2>
      <h3>공식 영상</h3>
      <div class="video">
        <iframe src="" title="Character PV"></iframe>
      </div>
    </section>

    <!-- 인게임 정보 -->
    <section id="ingame">
      <h2>인게임 정보</h2>

      <h3>기본 능력치</h3>
      <table class="wiki-table">
        <tr><th>HP</th><th>공격력</th><th>방어력</th><th>속도</th></tr>
        <tr><td>-</td><td>-</td><td>-</td><td>-</td></tr>
      </table>

      <h3>스킬</h3>

      <div class="skill">
        <h4>일반 공격 : 논증 방법</h4>
        <p>지정된 단일 적에게 파루시아 hp의 n%만큼 허수 속성 피해를 가한다</p>
      </div>

      <div class="skill">
        <h4>전투 스킬 : 진리의 선도자</h4>
        <p>모든 적에게 허수 속성 피해</p>
      </div>

      <div class="skill">
        <h4>필살기 : 가장 고결했던 진리의 잔향</h4>
        <p>에너지 90 소모, 전체 공격</p>
      </div>

      <div class="skill highlight">
        <h4>강화 필살기 : 정원에서 「내」가 수여한 공훈</h4>
        <p>에너지 180 소모, 바운스 추가 피해, 속도가 10% 감소</p>
      </div>
    </section>

    <!-- 성혼 -->
    <section id="eidolon">
      <h2>성혼</h2>
      <ol>
        <li>영원한 진리</li>
        <li>이데아의 현상계</li>
        <li>형상의 구조</li>
        <li>부정과 진리</li>
        <li>성령의 열매</li>
        <li>최초의 「빛」을 안는 법</li>
      </ol>
    </section>

    <!-- 음성 -->
    <section id="voice">
      <h2>음성</h2>
      <button onclick="toggle('voice-interact')">상호작용</button>
      <div id="voice-interact" class="fold">
        <p>첫 만남 / 인사 / 작별 등</p>
      </div>

      <button onclick="toggle('voice-battle')">전투</button>
      <div id="voice-battle" class="fold">
        <p>전투 시작 / 필살기 / 승리</p>
      </div>
    </section>

    <!-- 스토리 -->
    <section id="story">
      <h2>이야기</h2>

      <button onclick="toggle('story1')">캐릭터 스토리 · 1</button>
      <div id="story1" class="fold">
        <p>Lv.20 개방</p>
      </div>

      <button onclick="toggle('story2')">캐릭터 스토리 · 2</button>
      <div id="story2" class="fold">
        <p>Lv.40 개방</p>
      </div>

      <button onclick="toggle('story3')">캐릭터 스토리 · 3</button>
      <div id="story3" class="fold">
        <p>Lv.60 개방</p>
      </div>

      <button onclick="toggle('story4')">캐릭터 스토리 · 4</button>
      <div id="story4" class="fold">
        <p>Lv.80 개방</p>
      </div>
    </section>

  </main>

  <!-- ===== 푸터 ===== -->
  <footer class="wiki-footer">
    <p>Fan-made wiki page · Honkai: Star Rail</p>
  </footer>

  <script src="js/toggle.js"></script>
</body>
</html>
