---
layout: post
title: "미니PC 두 대로 시작한 나만의 쿠버네티스 실습 클러스터"
date: 2025-04-01
categories: [DevOps, Kubernetes]
tags: [Kubernetes, GitLab, Jenkins, DevOps, 금융권]
---

## 왜 이걸 시작했나

나는 프레임워크 개발자로 한국 금융권에서 7년간 프리랜서로 일해왔다.  
뱅크웨어글로벌이라는 업체와 주로 일했고, 대부분의 프로젝트는 **망분리** 환경이었다.

이런 환경에선 외부 기술 테스트나 자동화 실습이 거의 불가능하다.  
그래서 나는 개인적으로 **미니PC 2대를 활용해 쿠버네티스 실습 환경**을 직접 만들기로 했다.

---

## 실습 환경 구성

- **미니PC 2대**
  - Master Node 1대, Worker Node 1대
- **CI/CD 구성**
  - GitLab + Jenkins + Harbor

---

## 앞으로 다룰 내용

1. kubeadm으로 쿠버네티스 클러스터 구성하기
2. GitLab 설치 및 Runner 등록
3. Jenkins와 연동한 배포 자동화
4. Google Play 앱 자동 배포

---

## 마무리

실습 환경을 구성하면서 겪는 모든 과정과 문제 해결법을  
이 블로그에 시리즈로 남길 예정이다. 기술적인 성장과 동시에  
거래처 확장을 위한 포트폴리오가 되길 기대하며.