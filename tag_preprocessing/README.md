# kakao_arena_preprocessing

**TaeYun Kim (School of Computer Science & Engineering 🖥️, Chung-Ang Univ.)**


### 데이터셋 구성

  - 플레이리스트 메타데이터
  - 플레이리스트 제목
  - 플레이리스트에 수록된 곡
  - 플레이리스트에 달려있는 태그 목록
  - 플레이리스트 좋아요 수
  - 플레이리스트가 최종 수정된 시각
  - 곡 메타데이터
  - 곡 제목
  - 앨범 제목
  - 아티스트명
  - 장르
  - 발매일
  - 곡에 대한 Mel-spectrogram

Konlp와 pandas를 이용하여 태그를 분해한 다음 빈도수를 측정하여 One-hot Endcoding 해주었습니다.



