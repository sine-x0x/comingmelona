(영어버전 및 과정은 곧 업데이트하도록 하겠습니다!)

# 데이콘 한국 부동산 데이터 시각화 경진대회
https://dacon.io/competitions/official/235724/codeshare/2737

## 올때메로나 팀 (comingmelona) *팀 구성원 : @yoojin730, @SEONGHYUN-1211*

1. 목적 : local html을 외부로 띄우고 싶을 때 경유 목적의 github.io입니다.

2. 당시 상황 : 반응형 그래프(Pyecharts, plotly.write_html)등 로컬에 html을 저장해 Jupyternotebook, colab에 구현

3. 문제 상황
 - 로컬에서는 IPython.display.HTML 코드로 시각화를 구현할 수 있었지만, 데이콘 코드 공유에서는 결과가 보이지 않는 문제점이 발생.
 - pyecharts와 같은 경우 바이두 제작 패키지라 중국어 유저가 많았고, 버전 충돌이 많은 상황이었습니다. 
 - 데이콘 측과 여러 메일을 주고 받았지만, 해결이 되지 않은 상태였습니다. 
 - 시도했지만 실패한 방법들 : configure, js_host, CURRENTCONFIG 등

4. 해결 방안 : THIS REPOSITORY !

5. 응용 방안
 - 앞으로의 local html files를 특정 사이트에 못 올리는 상태가 발생했을 때 우회하여 적용할 수 있을 것같습니다! 
 - 구글링을 해보았을 때, html이 dacon에 안 올라가 반응형 그래프를 스크린캡쳐로 대체하는 팀들을 볼 수 있었는데, 
 github.io를 활용하신다면 그런 불상사를 방지할 수 있을 듯합니다! 🙂

# 재미있게 보셨다면 하트와 댓글 꾸욱 부탁드립니다 🔥🔥🔥🔥🔥
