<!--서비스 이미지-->
<p align="center">
  <img width="1727" alt="PolarStar" src="https://github.com/KDT-AiVENGERS/.github/assets/110510080/690629c2-5cfa-4814-ad8c-39dde7ecf33c">

</p>

<!--서비스 설명-->
<p align="center">
  흔히 자신에게 맞는 직무를 선정하고, 공부의 방향성을 정하기 위해서는<br>
  “채용 공고의 Job Description을 읽어보는 것이 정답” 이라고 얘기합니다.<br>
  그러나 하나하나 채용 공고를 읽는 대신, 개인에게 맞는 공고와 강의를 추천받는다면<br> 
  많은 시간과 노력을 절약할 수 있지 않을까요?<br>
</p>
<p align="center">
  AI 북극성은 취업을 준비하는 예비 개발자들을 위해 만들어진 서비스로,<br>
  아래 2가지 기능으로 길잡이별의 역할을 하는 북극성과 같은 역할을 하고자 합니다.<br>
</p>
<br>

<!--서비스 개요-->
<h1>
  북극성 서비스란?📌
</h1>
<ul>
  <li>언어 모델을 통해 유저 정보에 기반한 채용 공고 매칭</li>
  <ul type="circle">
    <li>유저들은 개인의 역량과  관심사를 반영한 채용 공고를 빠르게 추천받아 개별 공고를 살펴보는 데 드는 번거로움을 덜고, 자신에게 가장 알맞은 기회에 집중할 수 있습니다.</li>
  </ul>
  <br>
  <li>매칭된 공고의 기술 스택을 기준으로 강의 목록 추천</li>
  <ul type="circle">
    <li>매칭된 채용 공고의 기술 요구사항을 분석하여 필요한 기술을 학습하기 위한 강의를 추천받음으로써 필요 역량을 빠르게 획득하고, 경쟁력 있는 개발자로 성장할 수 있습니다.</li>
  </ul>
</ul>
<br><br>

<!--서비스 기능 소개 및 설명-->
<h1>
 서비스 기능 소개 및 설명 📌
</h1>

<h3>
 💡 1. 랜딩 페이지
</h3>
<p align="center">
  <img width="1727" alt="PolarStar_LandingPage" src="https://github.com/KDT-AiVENGERS/.github/assets/110510080/edffed0d-2dd7-4f08-b7c8-c11095f35ce6">
</p>
<br>

<h3>
 💡 2. 유저 Q&A
</h3>
<p align="center">
  <img width="1727" alt="PolarStar_Q&A" src="https://github.com/KDT-AiVENGERS/.github/assets/110510080/9c50dfc8-1e76-4862-bc04-12574a045e5b">
</p>
<br>

<h3>
 💡 3. 채용공고 추천
</h3>
<p align="center">
  <img width="1727" alt="PolarStar_JDRec" src="https://github.com/KDT-AiVENGERS/.github/assets/110510080/db012b20-3dec-492b-a8e4-55d5e1579a34">
</p>
<br>

<h3>
 💡 4. 강의 추천
</h3>
<p align="center">
  <img width="1727" alt="PolarStar_LECRec" src="https://github.com/KDT-AiVENGERS/.github/assets/110510080/c4ec9a0b-3167-437c-9fd7-6003e8aa7d30">
</p>
<br>
<!--테이블: repo-->
<h1>
  Repository 📌
</h1>
<table>
  <tr>
    <th scope="col">Repo</td>
    <th scope="col">설명</td>
  </tr>
  <tr>
    <td><a href="https://github.com/KDT-AiVENGERS/PolarStar_AIModel">PolarStar_AIModel     </a></td>
    <td>모델 서빙</td>
  </tr>
  <tr>
    <td><a href="https://github.com/KDT-AiVENGERS/PolarStar_AIInfra">PolarStar_AIInfra     </a></td>
    <td>모델 훈련, 테스트 코드</td>
  </tr>
  <tr>
    <td><a href="https://github.com/KDT-AiVENGERS/PolarStar_Data">PolarStar_Data     </a></td>
    <td>데이터 수집 및 가공</td>
  </tr>
  <tr>
    <td><a href="https://github.com/KDT-AiVENGERS/PolarStar_FrontEnd">PolarStar_FrontEnd     </a></td>
    <td>프론트엔드</td>
  </tr>
</table>
<br><br>

<!--개발 환경-->
<h1>
  개발 환경 📌
</h1>
<table>
  <tr>
    <th scope="col">Model & Infra</td>
    <th scope="col">FrontEnd</td>
    <th scope="col">FrontEnd</td>
  </tr>
  <tr>
    <td>Python 3.10.12</td>
    <td>Next.js 13.4.2</td>
    <td>FastAPI</td>
  </tr>
  <tr>
    <td>Pytorch Lightning</td>
    <td></td>
    <td>TorchServe</td>
  </tr>
  <tr>
    <td>Hydra</td>
    <td></td>
    <td>AWS EC2</td>
  </tr>
  <tr>
    <td>WandB</td>
    <td></td>
    <td></td>
  </tr>
</table>
<br><br>

<!--팀 구성 및 역할-->
<h1>
  팀 구성 및 역할 📌
</h1>
<table>
  <tr>
    <th scope="col">팀원</td>
    <th scope="col">역할</td>
  </tr>
  <tr>
    <td><a href="https://github.com/SuwonPabby">SuwonPabby</a></td>
    <td>프로젝트 관리<br>인프라 및 프론트엔드 작업</td>
  </tr>
  <tr>
    <td><a href="https://github.com/dkqp">dkqp</a></td>
    <td>모델 학습 및 추론 알고리즘 작성<br>모델 서버 및 요청 처리 알고리즘 작성</td>
  </tr>
  <tr>
    <td><a href="https://github.com/LoraBaek">LoraBaek</a></td>
    <td>데이터 수집 및 처리<br>가상 JD 생성 및 유사도 계산 알고리즘 작성</td>
  </tr>
  <tr>
    <td><a href="https://github.com/kwakchanhyuk">kwakchanhyuk</a></td>
    <td>데이터 수집 및 처리<br>가상 JD 생성 및 유사도 계산 알고리즘 작성</td>
  </tr>
  <tr>
    <td><a href="https://github.com/eno3940">eno3940</a></td>
    <td>데이터 수집 및 처리<br>모델 선정 및 실험, 강의 추천 알고리즘 작성</td>
  </tr>
  <tr>
    <td><a href="https://github.com/kimjaehyeonC">kimjaehyeonC</a></td>
    <td>데이터 수집 및 처리<br>모델 선정 및 실험, 강의 추천 알고리즘 작성</td>
  </tr>
</table>
<br><br>

<!--프로젝트 타임라인-->
<h1>
  프로젝트 타임라인 📌
</h1>
<table>
  <tr>
    <th scope="col">23.06.07 - 06.21<br>사전 기획</td>
    <th scope="col">23.06.19 - 07.29<br>데이터 수집 및 전처리</td>
    <th scope="col">23.07.17 - 08.04<br>모델링</td>
    <th scope="col">23.07.31 - 08.06<br>웹 개발 및 서비스 배포</td>
  </tr>
  <tr>
    <td>프로젝트 주제 선정 및 기획 회의</td>
    <td>필요 데이터 및 수집 절차 정의, 수집 대상 탐색</td>
    <td>모델 실험을 위한 infra 환경 구축</td>
    <td>엔드포인트 및 데이터 설정</td>
  </tr>
  <tr>
    <td>User Story 및 기능명세서 작성</td>
    <td>크롤링 코드 작성 및 데이터 수집</td>
    <td>BERT 계열 한국어 언어모델 서칭 (Kobert, Kcbert, Klue, etc.)</td>
    <td>프론트엔드 서버 제작</td>
  </tr>
  <tr>
    <td>관련 선행연구 사례 및 모델 서칭</td>
    <td>필요 컬럼 정의 및 중복값 처리</td>
    <td>모델 학습 및 추론</td>
    <td>백엔드 모델 서버 제작</td>
  </tr>
  <tr>
    <td>Notion page 생성 및 git convention 정의</td>
    <td>데이터 Wrangling</td>
    <td>모델 성능 실험 및 선정</td>
    <td>최적화 및 오류 수정</td>
  </tr>
</table>
<br><br>

<!--최종 프로젝트 발표회-->
<h1>
  최종 프로젝트 발표회 유튜브 영상📌
</h1>

  [![최종 프로젝트 발표회 유튜브](https://img.youtube.com/vi/eP0XIFfD51Y/0.jpg)](https://www.youtube.com/watch?v=eP0XIFfD51Y)
