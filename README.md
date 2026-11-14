# 📈 US Tech Stock Dashboard (NVIDIA & Tesla)

Apple Design System(라이트 테마) 감성으로 설계된 **엔비디아(NVDA)** 및 **테슬라(TSLA)**의 최근 1개월 주식 분석 대시보드 웹 애플리케이션입니다.  
초보자도 쉽게 이해할 수 있도록 **사실(Fact)**과 **해석(Interpretation)**을 나란히 배치하고, 복합적인 시장 변동 요인을 객관적으로 조망할 수 있도록 설계되었습니다.

---

## 🖥️ 주요 기능

1. **Apple Light Design System UI**
   - 부드러운 오프화이트 캔버스, 섬세한 섀도우, SF Pro / 시스템 한글 폰트 계층 구조.
   - PC 모니터 및 모바일 스마트폰 화면 폭에 맞춘 완전 반응형(Responsive) 카드 레이아웃.
2. **사실과 해석 나란히 보기 (Side-by-Side Comparison)**
   - **사실 (Fact)**: 공시 수치, 과거 24거래일 일일 종가, 지수 편입 일자 등 증명된 데이터.
   - **해석 (Interpretation)**: 독점적 경제적 해자(CUDA, FSD), 거시경제 및 수급 요인 분석.
3. **인터랙티브 종가 차트**
   - Chart.js 기반 일일 종가 라인 차트 (호버 및 모바일 터치 시 정확한 날짜별 종가 툴팁 제공).
4. **최근 1개월 관련 뉴스 5선 및 투명한 검증**
   - 본문 전문 확인 완료 기사(CNBC, 공식 IR)와 언론사 봇 차단 기사(로이터, 포브스)의 접근 상태를 정직하게 분리 표기.
   - 단일 뉴스가 주가 등락의 유일한 원인이라는 인과관계 단정을 철저히 배제.
5. **독립 실행 및 인쇄/PDF 저장 지원**
   - 상단 `[🖨️ 인쇄 / PDF 저장]` 버튼 제공 및 A4 페이지 잘림 방지 스타일(`@media print`) 내장.

---

## 📂 파일 구성 안내

- **`index.html`**: 메인 대시보드 (NVIDIA NVDA 1개월 분석 및 Tesla 전환 탭 포함)
- **`tesla.html`**: 테슬라 대시보드 (Tesla TSLA 1개월 분석 및 NVIDIA 전환 탭 포함)
- **`stock-report.html`**: 완전 독립 실행형 종합 보고서 웹페이지
- **`chart.min.js`**: 오프라인 구동용 Chart.js 로컬 라이브러리
- **`nvda_1month_data.json`**: 앤비디아 일별 종가 정적 데이터 (2024-10-14 ~ 2024-11-14)
- **`tsla_1month_data.json`**: 테슬라 일별 종가 정적 데이터 (2024-10-14 ~ 2024-11-14)

---

## ⚠️ 고지 사항 (Disclaimer)

- 본 대시보드는 **AI 초안**이며, **실시간 시세가 아닙니다**.
- 사전에 공개 수집된 과거 정적 일일 종가 데이터(기준일: 2024-11-14)를 바탕으로 작성되었습니다.
- 본 페이지는 투자 권유 목적이 아니며 학습 및 포트폴리오 프로젝트용입니다.

---

## 📄 License
This project is for educational and portfolio demonstration purposes.
