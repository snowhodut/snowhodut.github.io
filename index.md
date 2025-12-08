---
layout: retro # 이 부분을 'retro'로 변경합니다.
title: 송연우 이력서
---

# 송연우 (Yeonwoo Song)

<div class="profile-container">
  <img src="여기에_실제_이미지_경로를_넣어주세요/_01B07F0A-CCA3-4D10-9F08-B6F4227C0138_-removebg-preview.png" class="profile-img glitch-effect" alt="프로필 사진">
  <div class="profile-info">
    <p class="cyber-text">Security Researcher Interested in System Vulnerability Analysis</p>
    <ul>
      <li>📍 Seoul, South Korea</li>
      <li>🔗 <a href="https://github.com/snowhodut" target="_blank">GitHub: @snowhodut</a></li>
      <li>📧 <a href="mailto:miasong4678@gmail.com">miasong4678@gmail.com</a></li>
    </ul>
  </div>
</div>

<hr class="neon-divider">

## 👩🏻‍💻 ABOUT ME

<div class="terminal-box">
  <p>> 컴퓨터공학과 4학년 학부생입니다.</p>
  <p>> 2024년부터 본격적으로 보안 공부를 시작했으며, 특히 <strong>시스템 취약점 분석</strong>에 깊은 관심을 가지고 탐구하고 있습니다.</p>
  <p>> 실제 공격 흐름을 시뮬레이션하고 방어 기제를 이해하는 과정을 즐깁니다.</p>
</div>

<hr class="neon-divider">

## 🎓 EDUCATION & CERTIFICATIONS

### 학력
- **이화여자대학교** 컴퓨터공학전공 (2021.03 - 현재)
- **용화여자고등학교** (2018.03 - 2021.02)

### 자격증
- <span class="highlight">정보보안기사</span> (한국인터넷진흥원, 2025.12 취득)
- <span class="highlight">정보처리기사</span> (한국산업인력공단, 2025.12 취득)

### 언어
- **English** (업무 가능)

<hr class="neon-divider">

## 🚀 PROJECTS

### **Steam 계정 보안 메커니즘의 진화에 따른 인포스틸러 위협 모델링 및 분석**
<p class="project-meta">📅 2025.05 (개인 프로젝트) | 🔗 <a href="https://github.com/snowhodut/steam-downgrader" target="_blank">GitHub</a> | 🎥 <a href="https://youtu.be/hgRTmFVzz_w" target="_blank">시연 영상</a></p>

> Steam의 인증 구조 진화 과정을 분석하고, 최신 인포스틸러 악성코드가 세션 정보를 탈취하는 방식을 실험적으로 검증한 연구 프로젝트입니다.

<div class="details-box">
  <p><strong>주요 활동 및 성과:</strong></p>
  <ul>
    <li>Steam의 핵심 인증 구성요소(ssfn, loginusers.vdf, steamLoginSecure 쿠키)의 저장 위치와 역할 규명</li>
    <li>Python 기반의 정보 수집 자동화 스크립트(session_probe.py) 구현을 통한 공격 흐름 시뮬레이션</li>
    <li>브라우저 작동 중 쿠키 DB 잠금(PermissionError) 발생 시, 임시 복사본 생성 방식으로 우회하는 트러블슈팅 경험</li>
    <li>Windows 레지스트리를 활용한 지속성(Persistence) 메커니즘 구현 및 분석</li>
  </ul>
  <p class="tech-stack"><strong>🛠 Used Tech:</strong> <span>Python</span> <span>Windows Registry</span> <span>SQLite3</span> <span>VMware</span></p>
</div>

### **PHP 라이브러리 elFinder 기반 WordPress 플러그인 4종 취약점 분석**
<p class="project-meta">📅 2025.03 ~ 2025.05 (팀 프로젝트) | 📄 <a href="/assets/송연우_elfinder_발표.pdf" target="_blank">발표 자료 (PDF)</a></p>

> 파일 관리자 라이브러리인 'elFinder'를 내장한 WordPress 플러그인 4종에서 2024년 발견된 주요 CVE를 심층 분석하고 재현했습니다.

<div class="details-box">
  <p><strong>주요 활동 및 성과:</strong></p>
  <ul>
    <li>Bit File Manager 등 4종 플러그인의 내부 PHP 구조 및 AJAX 진입점 분석</li>
    <li><strong>CVE-2024-7627</strong> (Race Condition 기반 RCE) 등 주요 취약점의 트리거 조건과 동작 흐름을 파악하고 공격 시나리오 재현</li>
    <li>Docker를 활용하여 각 플러그인별 취약 버전 환경 구축 및 Burp Suite를 이용한 자동화 테스트 수행</li>
    <li>(기여 부분) elFinder 명령어 실행 구조와 WP 숏코드/AJAX 연결 고리 분석, 발표 자료 및 시연 시나리오 구성</li>
  </ul>
  <p class="tech-stack"><strong>🛠 Used Tech:</strong> <span>PHP</span> <span>WordPress</span> <span>elFinder</span> <span>Docker</span> <span>Burp Suite</span></p>
</div>

<hr class="neon-divider">

## 🎈 EXPERIENCES

<div class="timeline">
  <div class="timeline-item" data-year="2025">
    <ul>
      <li>KISA 버그헌팅 실습 훈련 교육과정 수료 (25.05)</li>
      <li>Hacktheon Sejong 2025 참여 (팀 사천왕)</li>
      <li>K-Shield Jr. 기초과정 수료 (25.03)</li>
      <li>이화여자대학교 정보보안 동아리 E-COPS (포너블 스터디 참여)</li>
    </ul>
  </div>
  <div class="timeline-item" data-year="2024">
    <ul>
      <li>KISIA 온택트 융합보안 교육 수료 (24.09 ~ 24.10)</li>
      <li>2024 영등포 해커톤 멘토 (24.07.27 ~ 24.07.28)</li>
      <li>Hacktheon Sejong 2024 참여 (팀 디지털닌자스)</li>
    </ul>
  </div>
</div>

<hr class="neon-divider">

## 🖊️ SELF-STUDY NOTES

<p>개인 학습 기록과 워게임 풀이 내용을 정리해둔 공간입니다.</p>

### 🎱 Wargames & CTF Write-ups
<ul>
  <li><a href="https://github.com/snowhodut/wargames" target="_blank">GitHub: Wargames 문제 풀이 저장소</a></li>
  <li><a href="https://github.com/snowhodut/bandit" target="_blank">GitHub: Bandit 풀이 저장소</a></li>
  <li><a href="https://miaami.tistory.com/category/%F0%9F%8E%B1%20Wargames" target="_blank">Tistory Blog: 🎱 Wargames 카테고리</a></li>
</ul>

### 📚 Study & Training Records
<ul>
  <li><strong>Web Hacking:</strong> <a href="/assets/OWASP_JuiceShop_공부.pdf" target="_blank">OWASP JuiceShop 웹 취약점 실습 정리 (PDF)</a></li>
  <li><strong>Pwnable:</strong> <a href="https://miaami.tistory.com/category/E-COPS/%ED%8F%AC%EB%84%88%EB%B8%94%20%EC%8A%A4%ED%84%B0%EB%94%94" target="_blank">Tistory: E-COPS 포너블 스터디 컴퓨터구조 정리</a></li>
  <li><strong>K-Shield Jr:</strong> <a href="https://miaami.tistory.com/category/K-Shield%20Jr" target="_blank">Tistory: 교육과정 실습 내용 정리</a></li>
  <li><strong>Convergence Security:</strong> <a href="/assets/온택트_융합보안_강의_정리.pdf" target="_blank">온택트 융합보안 강의 요약 정리 (PDF)</a></li>
</ul>
