# enpattern-audio

영어패턴 앱의 단어·문장 음성 파일 (mp3, 24 kHz 모노 32 kbps). GitHub Pages로 공개해서 앱이 바로 불러 쓴다.

- 경로: `<목소리>/s/<id>.mp3` (문장), `<목소리>/w/<id>.mp3` (단어)
- 목소리 폴더: `af_sarah`(미국 여), `am_michael`(미국 남), `bf_emma`(영국 여), `bm_lewis`(영국 남)
- 문장: [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) (Apache-2.0)으로 만듦
- 단어: Google Cloud Text-to-Speech로 만듦
- 만드는 도구와 `id` 규칙은 앱 저장소의 `site/enpattern/tools/voice/` 참고. 이 저장소의 파일은 손으로 고치지 않고 도구로 다시 만든다.
