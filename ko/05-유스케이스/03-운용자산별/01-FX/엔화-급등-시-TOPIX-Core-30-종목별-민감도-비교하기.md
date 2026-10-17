<!--
id: RX-USECASE-0080
type: use-case
language: ko
locale: ko-KR
author: Reflexivity Research
kb_imported: 2026-10-17
status: draft
translation_status: localized_from_en_canonical
original_language: en
source_type: reflexivity-platform-demo
source_manifest: RX-USECASE-0080
prompt_status: present
prompt_basis: localized_from_en_verbatim
-->

# 엔화 급등 시 TOPIX Core 30 종목별 민감도 비교하기

[← 운용자산별 유스케이스](../README.md) · [전체 유스케이스](../../README.md)

**대상 사용자:** 일본 주식 운용역, 외환 운용역, 리스크 관리 담당자  
**운용자산:** 외환, 일본 주식  
**연구 기준 기간:** 1990~2024년 과거 사례, 2024년 7~8월 엔 캐리 청산 참고

> 시장가격과 계산 결과는 해당 연구 기간의 설명용 예시이며, 현재 수치나 투자 권고가 아닙니다.

**[Reflexivity에서 이 연구 예시 열기 →](https://app.reflexivity.com/alfred?mode=research&conversationId=a1c43683-e81a-46d0-b9a4-0ab6a96d91b7&scrollTo=top)**

## 사용한 프롬프트

> [!IMPORTANT]
> 2024년 7~8월 엔 캐리트레이드 청산 때처럼 USD/JPY가 한 달에 8% 하락하면 TOPIX Core 30 중 어떤 종목이 가장 큰 영향을 받고 가장 덜 영향을 받는지 분석해 주세요. 종목별 엔화 움직임에 대한 과거 민감도를 바탕으로 수출기업과 내수기업도 비교해 주세요.

## 엔화 급등을 개별 주식 투자 질문으로 바꾸기

USD/JPY가 한 달 동안 **8% 하락**하면 수출기업의 해외이익 환산에는 부담이 될 수 있지만, 은행·내수기업에는 다른 경로로 영향을 줄 수 있습니다. 시장 전체가 위험 회피 국면에 들어서는 경우도 있어, 단순히 '엔화 강세는 수출주 악재'로 결론 내리기 어렵습니다.

2024년 7월 3일부터 8월 5일까지 USD/JPY는 약 **161.70에서 144.20**으로 떨어졌습니다. 이 사례는 1990~2024년의 **21거래일 중 환율이 최소 8% 하락한 13개 과거 사건**을 찾아, 뒤따르는 1개월 주가수익률의 중앙값을 비교합니다.

## TOPIX Core 30의 과거 조건부 수익률

![8퍼센트 달러엔 하락 이후 TOPIX Core 30의 과거 1개월 수익률 중앙값](../../../../assets/usecases/reflexivity/deep-research-2026-10/RX-USECASE-0080-yen-shock-topix30.png)

*그림 1. 조건에 맞는 과거 엔화 강세 구간 뒤의 1개월 주가수익률 중앙값입니다. 앞으로 엔화가 8% 강세를 보이면 같은 결과가 나온다는 예측치가 아닙니다.*

| 종목 | 과거 1개월 수익률 중앙값 | 유효 사례 수 |
| --- | ---: | ---: |
| Mitsubishi Corp | −4.90% | 13 |
| Toyota Motor | −4.32% | 13 |
| Sony Group | −3.57% | 13 |
| Honda Motor | −2.84% | 13 |
| Mizuho Financial | +6.68% | 6 |
| Hoya | +7.69% | 13 |
| MUFG | +9.43% | 6 |

보고서에서 수출기업 그룹의 평균은 **−2.74%**, 내수기업 그룹의 평균은 **+4.31%**였습니다. 단, 기업별 유효 사례 수가 크게 다르고 일부는 **2건**에 불과합니다. 또한 이 수치는 순수한 FX 회귀 베타가 아니라 여러 거시경제 충격이 섞인 **과거 조건부 수익률**입니다.

플랫폼에서는 이 화면을 출발점으로 기업의 해외매출 비중, 실제 환헤지 공시, 기간별 환율 회귀와 업종 영향을 추가 검증할 수 있습니다.

## 추가 자료 문의

해당 사례를 다른 연구 환경인 **LSEG Workspace에서 재현한 결과**에 관심이 있으시면, 데이터 접근 권한과 재배포 가능 범위를 확인한 뒤 별도 제공 가능 여부를 안내해 드립니다. **jim@reflexivity.com**으로 문의하면서 문서번호 **RX-USECASE-0080**를 알려주세요.

---

[← 운용자산별 유스케이스](../README.md) · [전체 유스케이스](../../README.md)
