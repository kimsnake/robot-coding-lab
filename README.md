# 🤖 Robot Coding Lab

초등학생을 위한 로봇·코딩 교육 자료와 인터랙티브 시뮬레이션 모음입니다.

## 시뮬레이션

1. [바퀴 회전 실험](simulations/wheel-rotation/) — 좌우 바퀴의 회전량을 조절하고 로봇의 이동 경로를 관찰합니다.
2. [같은 각도, 다른 거리](simulations/turning-radius/) — 90° 회전할 때 중심에서 멀수록 이동 거리가 길어지는 원리를 관찰합니다.

## GitHub Pages 공개 방법

1. 저장소에 이 폴더의 **내용물**(`index.html`, `simulations/`, `README.md`)을 업로드합니다.
2. GitHub 저장소의 **Settings → Pages**로 이동합니다.
3. **Build and deployment → Deploy from a branch**를 선택합니다.
4. Branch를 **main**, Folder를 **/(root)**로 설정하고 저장합니다.
5. 공개 주소: `https://<GitHub-사용자이름>.github.io/<저장소이름>/`

별도 서버나 빌드 도구 없이 HTML, CSS, JavaScript만으로 작동합니다.

## 교육용 참고

- 바퀴 회전 실험은 바퀴 둘레 17.5cm, 바퀴 사이 거리 12cm를 가정합니다. 실제 교구와 다를 수 있습니다.
- 시뮬레이션은 마찰과 미끄러짐을 생략한 단순 모델입니다.
- 곡선 주행의 안쪽·바깥쪽 바퀴 거리 차이는 제자리 회전과 구별해서 설명합니다.
