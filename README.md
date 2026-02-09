# Telomere 자료 업로드 패키지 (OpenNeuro/BIDS wrapper)

이 데이터셋은 BIDS에서 정의한 neuroimaging 원자료가 아니라, 엑셀 형태의 참고/정리 자료입니다.
OpenNeuro 업로드 시 BIDS Validator가 루트에 비표준 파일(.xlsx 등)이 존재하면 오류를 내기 때문에,
원본 파일을 `sourcedata/` 아래로 이동해 보관하도록 구성했습니다.

## 파일 위치
- `dataset_description.json` : BIDS 필수 메타데이터(최소)
- `sourcedata/` : 원본(비표준) 파일 보관 폴더

## 참고
실제 BIDS 호환 신경영상/행동 데이터가 있다면, `sub-*/` 구조 및 `.tsv/.json` 사이드카를 추가해 주세요.
