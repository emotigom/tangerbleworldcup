# Grid Field Editor

그리드 기반 활동의 맵 설계와 동선 점검을 위한 브라우저 도구.

## 기능

- 16 × 12 그리드 맵 편집
- 시작점·도착점·마커·장애물 배치
- 방향 전환과 한 칸 이동 점검
- JSON 저장·불러오기
- 서버 전송·외부 의존성 없음

## 실행

`index.html`을 브라우저에서 열거나 로컬 서버를 사용한다.

```bash
python3 -m http.server 8000
```

`http://localhost:8000`

## 조작

| 동작 | 입력 |
| --- | --- |
| 배치·삭제 | 도구 선택 후 그리드 클릭 |
| 장애물 연속 배치·삭제 | 그리드 드래그 |
| 왼쪽·오른쪽 회전 | `←`·`→` 또는 `A`·`D` |
| 한 칸 전진 | `↑` 또는 `W` |

## 저작 및 라이선스

원본 소스 코드와 문서: © 2025–2026 Ahn Sangkyoon

해당 범위는 [MIT License](LICENSE)에 따라 사용할 수 있다. 제3자 권리는 라이선스 범위에 포함되지 않는다.

## 제3자 권리

이 도구는 Tangible Coding World Cup 참가 과정의 현장 필요를 위해 시작한 비공식 독립 보조도구이며, Tangible Africa 또는 Leva Foundation과 제휴·승인 관계가 없다.

Tangible Africa, Leva Foundation, Tangible Coding, Tangible World Cup 관련 명칭·상표·앱·교육 콘텐츠·상용 키트·그래픽 자산의 권리는 각 권리자에게 있다. 현재 `main`에는 해당 이미지나 제품 자산을 포함하지 않는다.

[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)
