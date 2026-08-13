<img width="927" height="1302" alt="화면 캡처 2026-08-13 171153" src="https://github.com/user-attachments/assets/0e1fd594-5dc9-4c60-9340-4b0377b84a3d" />
📱 AI 영어 문법 도우미 (English Grammar Assistant)
스마트폰 환경에 최적화된 모바일 중심의 반응형 AI 영어 문법 교정 웹 애플리케이션입니다. Google Gemini API를 활용하여 사용자가 입력한 영문장의 문법적 오류를 유연하고 실시간으로 분석하며, 정확한 수정본과 상세한 해설을 제공합니다.

✨ 주요 기능
🔑 사용자 친화적인 API 키 설정

상단 메뉴의 'API 키 설정' 버튼을 통해 사용자의 Gemini API Key를 직접 입력하고 관리할 수 있습니다.

입력된 키는 브라우저의 localStorage에 안전하게 저장되어 새로고침 후에도 유지됩니다.

🤖 유연한 AI 기반 문법 검사 (Gemini API)

하드코딩된 규칙이나 패턴에 얽매이지 않고, 최신 Gemini AI 모델이 문장의 맥락과 문법적 오류(시제, 수 일치, 전치사, 관사 등)를 스스로 판단합니다.

구조화된 JSON 응답(responseSchema)을 통해 정확하고 신뢰성 있는 교정 데이터를 받아옵니다.

📋 직관적인 결과 리포트 & 복사 기능

정상 문장: 깔끔한 성공 상태 카드 표시

오류 문장: 주의 상태 카드, 추천 수정 문장, 원인에 대한 상세 해설 제공

수정된 문장은 클릭 한 번으로 클립보드에 간편하게 복사할 수 있습니다.

📱 모바일 최적화 UI / UX

Tailwind CSS를 활용한 모던하고 직관적인 인터페이스

엄지손가락 터치에 최적화된 버튼 크기와 여백, 부드러운 애니메이션 효과 적용

🚀 시작하기 (사용 방법)
Gemini API 키 준비

Google AI Studio에서 Gemini API 키를 발급받습니다.

API 키 등록

웹앱 실행 후 상단의 [API 키 설정] 버튼을 클릭하고 발급받은 키를 입력하여 저장합니다.

문장 검사

입력창에 검사하고 싶은 영어 문장을 직접 입력하거나, 하단의 예시 버튼(She don't like apples. 등)을 눌러 테스트해 보세요.

[문법 검사 및 분석하기] 버튼을 누르면 AI가 즉시 분석 결과를 보여줍니다.

🛠 기술 스택
Frontend: HTML5, Tailwind CSS, JavaScript (Vanilla ES6+)

AI Engine: Google Gemini API (gemini-3-flash-preview)

Icons & Fonts: FontAwesome, Google Fonts (Inter)
