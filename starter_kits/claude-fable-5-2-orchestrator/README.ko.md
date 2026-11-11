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
git clone https://github.com/eroica-ai/ai-tech-brief.git
cd starter_kits/claude-fable-5-2-orchestrator
pip install -r requirements.txt
cp .env.example .env
# .env 파일에 ANTHROPIC_API_KEY 입력 (미입력 시 --dry-run 시뮬레이션 모드 지원)
```

### 2. 오케스트레이터 실행
```bash
# 기본 실행 (WebSocket 클라이언트 작업)
python fable_orchestrator.py

# 커스텀 작업 지정 및 결과 파일 생성
python fable_orchestrator.py --task "JWT 인증 및 Redis 토큰 블랙리스트 핸들러" --out auth_service.py

# API 키 없이 파이프라인 시뮬레이션 및 비용 분석
python fable_orchestrator.py --dry-run
```

---



---
⭐ 도움이 되셨다면 상단의 **Star** 버튼을 눌러주세요!
