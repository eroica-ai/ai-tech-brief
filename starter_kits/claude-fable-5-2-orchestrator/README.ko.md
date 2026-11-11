# 🚀 Claude Fable 5.2 가성비 오케스트레이터 스타터 키트

앤트로픽의 최상위 프론티어 모델 **Claude Fable 5.2**를 사용하면서 **토큰 비용을 90% 이상 절감**할 수 있는 실전 멀티에이전트 오케스트레이션 코드입니다.

---

## 📌 핵심 원리
- **Fable 5.2 (총사령관/Architect)**: 전체 아키텍처 설계, 버그 근본 원인 분석, 코드 리뷰에만 핀포인트 투입.
- **Sonnet / Haiku (작업자/Worker)**: 단순 파일 작성, 포맷팅, 단위 테스트 실행 등 반복 작업 수행.
- ➔ 전 구간 Fable 5.2 사용 대비 **토큰 비용 \$40/M ➔ \$5/M 이하로 극적 절감**.

---

## 🛠️ 빠른 시작 (Quick Start)

### 1. 환경 설정
```bash
git clone https://github.com/kodwoo1/ai-tech-brief.git
cd starter_kits/claude-fable-5-2-orchestrator
pip install anthropic
cp .env.example .env
# .env 파일에 ANTHROPIC_API_KEY 입력
```

### 2. 오케스트레이터 실행
```bash
python fable_orchestrator.py
```

---

⚡ [영상 속 추천 툴 & 제휴 링크]
• Anthropic Claude Console: https://console.anthropic.com/ (Claude 공식 콘솔 바로가기 (Fable 5.2 지원))
※ 위 링크를 통해 결제 시 영상 제작에 소정의 수수료가 지원될 수 있습니다.

---
⭐ 도움이 되셨다면 상단의 **Star** 버튼을 눌러주세요!
