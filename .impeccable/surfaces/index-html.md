---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# 표면: index.html (검수 도구 한 페이지)

모드: Operate. 대상: 카톡 이모티콘 작가(입문 + 숙련). 할 일: PNG를 맡기고, 고칠 칸을 바로 찾고, 실제 크기와 테마에서 확인하기.
사용자 조정: "디자인은 좋은데 너무 딱딱함, 더 한국식으로" → 한국 소비자 서비스처럼 부드럽게 만들어요 (둥근 모서리, Pretendard, 해요체, 친근한 문구).
미정: 서비스 이름(작업용 이름 '이모티콘 사진관'을 제안안으로 씀), 유료화.

## Direction contract
THESIS: 동네 사진관에서 한 장의 사진을 여러 규격으로 나란히 뽑아 주는 출력지. 칸마다 180·40·20px을 한 줄로 펼쳐 검수해요. 업로드 상자에 결과 카드가 이어지는 일반 이미지 도구 배치는 거부해요.
OWN-WORLD: 증명사진 하늘색 배경지(#d9ebf8 계열), 흰 인화지 카드와 점선 재단선, 남색 잉크, '다시 찍기' 빨강은 손볼 칸에만, 통과 초록. Pretendard, 둥근 모서리 16px, 부드러운 그림자. 사진관 접수증처럼 정리된 규격 목록.
STORY: 처음 온 작가는 예시 시트로 바로 둘러보고, 자기 PNG를 맡기면 빨간 표시 칸과 '지금 고칠 것' 한 줄을 보고 원본으로 돌아가요.
FIRST VIEWPORT: 위쪽 바(로고, 이름, 탭 3개, 무료 공개 배지). 비어 있으면 가운데 큰 접수 카드(종류 선택, PNG 맡기기 버튼, 예시로 둘러보기). 결과가 있으면 3단 구성: 왼쪽 접수증(규격 목록), 가운데 칸 그리드(하늘색 위 흰 인화지), 오른쪽 선택한 칸의 출력 시트.
FORM: 자체 후보 7번 '증명사진 출력 시트'. seed:6aba10d015a8b980. 대표 움직임: 결과가 나오면 인화지가 현상되듯 흐릿함에서 선명해지는 한 번의 전환. 다른 카드에서 가져온 규율: 상태가 바뀌어도 그리드는 움직이지 않기(역 안내판), 빨강은 한 의미만(오리엔티어링), 지금 할 일 하나(공항 안내판), 본문은 한 크기(아세테이트 매뉴얼), 바뀐 칸은 확인할 때까지 표시 유지(탑승권).
FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance
