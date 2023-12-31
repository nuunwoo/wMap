## UPDATE

> **_2023-05-31_**
>
> - 그린 사각 도형 그리기 (투 그린 대응)
> - 그린 사각 도형 컨트롤러 추가 (투 그린 대응)
> - 그린 사각 도형 스케일 변경 추가 (투 그린 대응)
> - 그린 사각 도형 각도 변경 추가 (투 그린 대응)

> **_2023-05-22_**
>
> - 사각 도형 스케일 변경 버그 수정
> - 도형 그리기 및 수정 비율 고정 추가 및 방향성 중앙 컨트롤러 삭제

> **_2023-05-22_**
>
> - 사각 도형 상하 좌우 방향 레이아웃 삭제(추후 수정)
> - 사각 도형 스케일 변경 추가
> - 사각 좌표 지도 이미지 추가

> **_2023-05-22_**
>
> - 사각 도형 상하 좌우 레이아웃 추가
> - 사각 도형 각도 변경 추가

> **_2023-05-19_**
>
> - ~~섹션코드 필터링 버그~~
> - ~~섹션 영역에서 포인트 삭제 후 취소 시 버그~~
> - ~~홀 인식 영역, 섹션 영역 수정 시 초기화 후 다시 그려짐~~
> - 섹션코드 텍스트 레이아웃 추가
> - function -> arrow function / useCallback
> - build 오류 수정

> **_2023-05-17_**
>
> - 파일 다운로드
>
>   > - ~~좌표 없는 데이터 0.0으로 나옴~~
>   > - ~~홀인식 영역, 섹션 영역 없음~~
>   > - infoImage에 대한 정의 필요
>
> - 파일 다운로드 수정
>   > - 좌표0.0데이터가 있을 시 해당 파일 다운로드 불가능
>   > - 홀인식 영역, 섹션영역 다운로드 추가

> **_2023-05-15_**
>
> - 업장 생성 및 수정
> - 홀 인식 영역 데이터 없을 때 그리기 추가
> - 섹션 영역 데이터 없을 때 그리기 추가
> - 그리드 고도 데이터 추출

> **_2023-05-10_**
>
> - 사각영역 그리기, 수정 및 저장 추가
> - 티(X, Y, Z), 홀 중앙(X, Y, Z), 그린 엣지(X, Y), 그린 중앙(X, Y, Z) 그리기, 수정 및 저장 추가
> - 홀 인식 영역 데이터 있을 때 수정 및 저장 추가
> - 섹션 영역 데이터 있을 때 수정 추가

## 프로젝트 시작

> #### 배포방법

> 1. $ yarn build
> 2. $ yarn start

> #### 개발모드

> $ yarn dev
