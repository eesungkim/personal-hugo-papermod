---
title: "Triton devlog: 첫 삽"
date: 2026-01-16
tags: ["triton", "asr", "serving"]
translationKey: "triton-devlog-001"
draft: false
---

오늘은 Triton Python backend에서 기본 모델 로딩/입출력 경로를 정리했다.

## 체크리스트
- 에러 재현 최소 케이스 만들기
- 배포/서빙 관점에서 병목 위치 분해하기
- 메트릭(p50/p95) 기준으로 목표치 정의하기
