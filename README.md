# 📊 Google Merchandise Store GA4 분석 프로젝트

> **포괄적인 Ecommerce 데이터 분석을 통한 business insight 도출 및 마케팅 최적화 방안 제시**

## 🎯 프로젝트 개요

### 프로젝트 목적
Google Merchandise Store의 GA4 데이터를 활용하여 **전환율 급감 원인을 파악**하고, **데이터 기반 마케팅 최적화 방안**을 제시하는 것입니다. 단순한 지표 분석을 넘어 **실무에서 활용 가능한 Insight**를 도출하는 것에 중점을 두었습니다.

### Business 문제
- **구매 전환율 27.3% 급감** (전월 대비)
- **장바구니 이탈률 99.2%** (극도로 높음)
- **전체 전환율 0.98%** (업계 평균 대비 매우 낮음)
- **마케팅 채널별 실제 기여도** 불명확

### 분석 접근법
```
문제 정의 → 가설 수립 → 다각도 분석 → 인사이트 도출 → 실행 방안 제시
```

## 🛠️ 사용 도구 및 방법론

### 분석 도구
- **GA4 Reports**: 기본 현황 파악
- **GA4 Explore**: 심화 분석 (Funnel, Path, Segment Overlap)
- **GA4 Advertising**: 심화 분석 (Attribution Paths and Models)
- **Data Analysis**: 통계적 해석 및 비즈니스 인사이트 도출

### 분석 방법론
- **Funnel Exploration**: 사용자 여정 단계별 이탈 지점 파악
- **Path Exploration**: 실제 사용자 행동 패턴 추적
- **Segment Overlap**: 구매 행동별 사용자 특성 분석
- **Attribution Paths and Models**: 마케팅 채널 기여도 정확한 측정

## 📋 분석 구조

### 1단계: 현황 파악 📈
- **기본 지표 분석**: 핵심 성과 지표 현황 파악
- **문제점 식별**: 전환율 급감 원인 가설 수립

### 2단계: 트래픽 분석 🚀
- **User Acquisition**: 유입 채널별 성과 분석
- **Traffic Acquisition**: 채널별 품질 및 참여도 평가
- **Pages & Screens**: 사용자 행동 및 페이지 성과 분석
- **Ecommerce Purchases**: 상품별 성과 및 전환율 분석

### 3단계: 사용자 여정 분석 🛤️
- **Funnel Exploration**: 구매 과정 단계별 이탈률 분석
- **Path Exploration**: 실제 사용자 행동 경로 추적
- **Segment Overlap**: 구매 행동별 사용자 세분화

### 4단계: 마케팅 최적화 🎯
- **Attribution Models**: 채널별 실제 기여도 측정
- **Attribution Paths**: 고객 여정 패턴 분석

## 🔍 주요 발견사항

### 💥 Critical Findings

#### 1. 홈페이지에 8초만 머무르는 시간에 관한 부분
**가설**: "8초는 너무 짧은데 이탈하는 것 아닌가?"
**결과**: 
```
✅ Funnel Exploration: 이탈은 아니였으나, 다른 부분에서 문제가 있는 것을 확인
✅ Path Exploration: Funnel에서 문제가 있는 듯 보였으나, 93.2%가 실제로 페이지 탐색 진행
```
**인사이트**: 8초는 **효율적인 의사결정 시간**이며, 이탈이 아닌 **빠른 목적 달성**을 보여준 것

#### 2. 장바구니 이탈의 심각성
```
장바구니 추가: 3,065명
구매 완료: 24명
전환율: 0.78% (극도로 낮음)
```
**문제**: 구매 의도가 있는 사용자의 **99.2%가 결제 단계에서 포기**

#### 3. 마케팅 채널 기여도 오해
**Data-driven vs Last-click 모델 비교**:
- **Cross-network**: +39.87% (가장 과소평가됨)
- **Organic Social**: +20.92% (숨겨진 가치)
- **Organic Search**: -7.48% (과대평가됨)

### 📊 데이터로 입증된 인사이트

#### 사용자 행동 패턴
- **53.3% 사용자**가 프로모션 확인 (가장 많은 활동)
- **28.8% 사용자**가 활성/참여 사용자로 분류
- **97.1% 구매 고객**이 장바구니 없이 바로 구매

#### 채널별 특성
- **Direct**: 76.3% 점유율, 하지만 참여도 낮음 (봇 트래픽 의심)
- **Email**: 0.19% 점유율이지만 **높은 품질** (참여시간 3분 13초)
- **Referral**: 작은 규모지만 **10.64회 재방문** (높은 충성도)

#### 상품별 성과 패턴
- **관심 vs 구매 괴리**: 최다 조회 상품 전환율 3.1% vs 고수익 상품 전환율 27.3%
- **숨겨진 고수익 상품**: Super G RIPL Rainforest Tote(4위 조회수 → 1위 매출)
- **카테고리별 차이**: 실용적 Accessory > 의류 > Collectible 순 전환율

## 🎯 핵심 전략 제안

### 즉시 실행
1. **장바구니 결제 과정 간소화**
   - 원클릭 결제 도입
   - 게스트 체크아웃 강화
   - 결제 단계 3→1단계로 축소

2. **Cross-network 마케팅 예산 40% 증액**
   - 가장 과소평가된 채널에 집중 투자
   - 디스플레이/동영상 광고 확대

### 단기 실행
1. **프로모션 → 구매 연결 강화**
   - 53.3% 사용자가 확인하는 프로모션을 구매로 전환
   - 개인화된 할인 쿠폰 제공

2. **고효율 소량 채널 확대**
   - Email 마케팅 투자 확대 
   - Referral 파트너십 프로그램 확대

2. **상풍별 맞춤 전략**
   - 고전호나 상품 마케팅 확대
   - 인기 상품 전환 장애물 제거
   - 카테고리별 차별화된 접근

### 중기 실행
1. **개인화 추천 시스템 도입**
   - 28.8% 참여 사용자 대상 맞춤 상품 추천
   - 구매 고객 성공 패턴 복제

2. **Data-driven Attribution 기반 예산 재배분**
   - 과소평가된 채널 (Cross-network, Social) 투자 확대
   - 과대평가된 채널 (Organic Search) 투자 조정

## 📈 예상 비즈니스 개선점

```
장바구니 전환율: 0.78% → 3% 개선
예상 추가 구매자: 60명/월
매출 증가: 약 80% 증가
```

## 📁 프로젝트 구조

```
├── docs/
│   ├── Basic_Analysis_Report.md           
│   ├── Exploration_Analysis_Report.md     
│   ├── Advertising_Analysis_Report.md     
├── imgs/
│   ├── Home_Screen.png
│   ├── User_Acquisition.png
│   ├── Traffic_Acquisition.png                
│   ├── Funnel_Exploration.png            
│   ├── Path_Exploration.png              
│   ├── Pages_and_Screens.png
│   ├── Ecommerce_Purchases.png                  
│   ├── Segment_Overlap.png
│   ├── Attribution_Paths.png                            
│   └── Attribution_Models.png            
└── README.md                             
```

## 🎓 학습 내용

### GA4 전문성 향상
- **여러 GA4 기능 공부**: Funnel, Path, Segment Overlap, Attribution 분석
- **데이터 해석 능력**: 동일 데이터의 다각도 분석
- **비즈니스 연결**: 기술적 분석을 비즈니스 가치로 전환

### 분석 방법론 개발
- **가설 기반 분석**: 문제 정의 → 가설 수립 → 검증 → 인사이트 도출
- **교차 검증**: 여러 도구를 활용한 결과 검증으로 정확도 향상

## 💡 배운 점

### 1. 데이터 분석의 함정
```
❌ 단일 지표만 보면 잘못된 결론 도출 가능
✅ 여러 도구와 관점에서 교차 검증 필요
```

### 2. 가설의 중요성
```
❌ 데이터를 보고 나서 해석하면 편향 발생
✅ 가설을 먼저 세우고 데이터로 검증해야 객관적 분석
```

### 3. 비즈니스 관점의 필수성
```
❌ 기술적으로 완벽한 분석도 비즈니스 가치가 없으면 무의미
✅ 항상 실행 방안까지 제시
```
