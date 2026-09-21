# vision-AI

2026 국립공원 위성 모니터링 AI 챌린지 주제 3(국립공원 내 시설물 변화 탐지) 실험 저장소입니다.

## 현재 최고 버전

`experiments/exp01_nodata_mask`

- 공식 UNet-ResNet18 6채널 베이스라인 사용
- `pre` 또는 `post` 영상이 완전히 검정인 화소를 배경으로 강제 변환
- 기본 공개점수: `0.2744792354`
- 무영상 마스킹 디버그 공개점수: `0.2990630154`
- 절대 상승폭: `+0.0245837800`

## 다른 PC에서 이어하기

1. 이 저장소를 clone합니다.
2. [AIFactory 공식 베이스라인](https://aifactory.space/ko/task/9306/baseline)을 다운로드합니다.
3. `unet_r18_cd.pt`를 `experiments/exp01_nodata_mask/assets/model/`에 복사합니다.
4. `predict.ipynb`의 `<참여키>`를 로컬에서만 바꾸어 제출합니다. 참여키를 저장한 상태로 commit하지 마세요.

가중치 SHA-256:

```text
1BE127BD2F70C8E3B0EFDC48C6D3EFFC29F30F090746A91C87E6C23E9B3E878B
```

대회 제공 가중치는 재배포하지 않고 Git에서 제외합니다.
