# 최신 자연어처리 모델 소개

2018년 BERT의 등장 이후로 사전훈련 모델들이 딥러닝 자연어처리의 표준으로 자리잡았습니다. 2020년에는 GPT-3가 공개되면서 초거대모델로 다시 흐름이 바뀌고 있습니다. 지금까지 수많은 자연어처리 모델들이 공개되었지만, 한눈에 볼 수 있는 자료가 많지 않았습니다. 그래서 최신 자연어처리 모델들을 정리한 문서를 작성해보았습니다.

각 모델마다 간략한 특징만 나와있는데, 보다 자세한 내용은 링크된 문서를 확인하시면 됩니다. Github에서 바로 pdf를 열면 링크가 작동하지 않는 문제가 있습니다. 되도록 다운로드 후 읽어보시길 추천드립니다. 혹시 잘못된 정보가 있거나 추가하고 싶은 모델이 있으면 이슈에 올려주시면 고맙겠습니다. 앞으로 계속 새로운 모델을 업데이트할 예정입니다.


## 모델 목록
- 2018/11
  - **BERT** (구글)
    - 설명
      - Transformer의 Encoder로 만든 사전훈련 모델
    - 모델크기
      - Base 110M / Large 340M
    - 관련문서
      - The Illustrated BERT, ELMo, and co. [[Link]]
      [Link]: https://nlpinkorean.github.io/illustrated-bert
- 2019/02
  - **GPT-2** (OpenAI)
    - Transformer의 Decoder로 만든 사전훈련 모델
- 2019/07
  - **RoBERTa** (메타)
    - BERT를 개선한 모델
- 2019/10
  - **BART** (메타)
    - Seq2Seq 구조로 손상된 텍스트를 복구하는 사전훈련 방법 사용
  - **KoBERT** (SKT)
    - 한국어 BERT
- 2019/12
  - **ALBERT** (구글)
    - BERT 경량화
- 2020/01
  - **Meena** (구글)
    - 일상대화 모델
- 2020/03
  - **ELECTRA** (구글)
    - RTD(Replaced Token Detection) 방식으로 사전훈련
- 2020/04
  - **KoELECTRA** (박장원)
    - 한국어 ELECTRA
  - **KoGPT-2** (SKT)
    - 한국어 GPT-2
- 2020/05
  - **GPT-3** (OpenAI)
    - GPT-2의 100배 크기를 가진 초거대모델
  - **BlenderBot** (메타)
    - 일상대화 모델
- 2020/07
  - **KcBERT** (이준범)
    - 구어체에 특화된 한국어 BERT
- 2020/12
  - **KoBART** (SKT)
    - 한국어 BART
- 2021/01
  - **DALL·E** (OpenAI)
    - Text-to-Image 모델
  - **CLIP** (OpenAI)
    - 이미지와 텍스트 임베딩이 유사하도록 만드는 모델
- 2021/04
  - **KoELECTRA** (이준범)
    - 구어체에 특화된 한국어 ELECTRA
- 2021/05
  - **LaMDA** (구글)
    - 대화 전용 초거대모델
  - **하이퍼클로바** (네이버)
    - 한국어 초거대모델
- 2021/07
  - **BlenderBot 2.0** (메타)
    - 검색 및 기억 능력이 추가된 일상대화 모델
- 2021/09
  - **TUNiB-Electra** (튜닙)
    - 한국어 ELECTRA
- 2021/10
  - **KLUE-BERT** (KLUE)
    - 한국어 BERT
  - **KLUE-RoBERTa** (KLUE)
    - 한국어 RoBERTa
- 2021/11
  - **KoGPT** (카카오)
    - 6B의 한국어 GPT
- 2021/12
  - **minDALL-E** (카카오)
    - Text-to-Image 모델
  - **엑사원** (LG)
    - 텍스트와 이미지를 동시에 처리하는 한국어 초거대모델
  - **Gopher** (딥마인드)
    - 280B의 초거대모델
  - **RETRO** (딥마인드)
    - 7.5B이지만 외부 검색으로 성능을 높인 모델
- 2022/01
  - **InstructGPT** (OpenAI)
    - GPT-3의 업그레이드 버전
- 2022/02
  - **AlphaCode** (딥마인드)
    - 설명이 주어지면 코드를 작성하는 모델
- 2022/04
  - **DALL·E 2** (OpenAI)
    - CLIP과 Diffusion을 사용한 Text-to-Image 모델
  - **Chinchilla** (딥마인드)
    - 70B으로 280B의 Gopher보다 뛰어난 성능을 보임
  - **Flamingo** (딥마인드)
    - 텍스트, 이미지, 영상을 처리할 수 있는 멀티모달 모델
  - **PaLM** (구글)
    - GPT-3의 3배인 540B의 초거대모델
- 2022/05
  - **Imagen** (구글)
    - Diffusion을 사용한 Text-to-Image 모델
  - **Gato** (딥마인드)
    - 텍스트, 이미지, 영상, 게임, 로봇 등 다양한 작업을 하나의 모델로 수행
  - **Parti** (구글)
    - Encoder-Decoder 구조의 Text-to-Image 모델
  - **에이닷** (SKT)
    - 일상대화가 가능한 개인비서 앱
  - **CogVideo** (칭화대)
    - 4초 32프레임의 영상을 만드는 Text-to-Video 모델


## 참고 자료
- 한국어 사전학습 모델
  - https://github.com/sooftware/Korean-PLM
