---
title: "강화학습 기반 월면 로버 탑재 Pick-and-Place 조작 정책의 에너지·안전 지표 평가"
collection: publications
category: domestic conference
permalink: /publication/ksas-2026-spring-conference
excerpt: "본 논문은 월면 로버 탑재 pick-and-place 조작을 대상으로, 강화학습 기반 정책의 성능을 에너지·안전 지표와 함께 평가하는 방법을 제안한다. 저중력 월면 환경을 모사한 Isaac Sim 기반 시뮬레이션에서 PPO 정책을 학습하고, 외부 토크 외란 조건에서 성공률, 기계적 에너지 지표, 안전 사고율을 함께 분석함으로써 월면 조작 정책의 성능–효율–안전 특성을 정량적으로 비교한다."
date: 2026-04-01
venue: "KSAS"
slidesurl: "https://academicpages.github.io/files/slides1.pdf"
paperurl: "https://academicpages.github.io/files/paper1.pdf"
bibtexurl: "https://academicpages.github.io/files/bibtex1.bib"
citation: "강현준, 최재용 &quot;강화학습 기반 월면 로버 탑재 Pick-and-Place 조작 정책의 에너지·안전 지표 평가&quot;, 한국항공우주학회 춘계학술대회, 신화월드, 제주도, 3월 31일-4월 3일, 2026."
---

![KSAS 2026 Spring Conference Architecture Overview](/images/publications/KSAS-Spring_fig01_architecture_overview_v1.png)

_그림 1. 월면 로버 탑재 pick-and-place 조작 정책의 강화학습 기반 학습·평가 아키텍처. Isaac Sim/Isaac Lab 기반 저중력 시뮬레이션 환경에서 로버 탑재 Franka Panda 조작기를 대상으로 MDP를 구성하고, PPO 기반 actor–critic 정책과 단계형 보상 설계를 통해 학습을 수행한다. 또한 GPU 병렬 롤아웃과 엔드이펙터 외부 토크 외란 주입을 통해 다양한 운용 조건을 모사하며, 성공률(SR), 기계적 에너지 지표 E_{\mathrm{mech}}, 접촉 영향률(CIR)을 이용하여 정책의 성능–효율–안전 특성을 평가한다.\_
