# visualize
- "Python graph gallery"의 샘플코드를 여러가지 파라미터를 조절하여 터득

## visualize 업데이트 일정
- ~1주차(-23/7/4) : "Distribution" / git-pro 교재로 git-hub 사용법 익히기~  --> 23/7/3 완료
- ~2주차(-23/7/11) : "Correlation"~ --> 23/7/5 완료
- ~3주차(-23/7/18) : "Ranking"~ --> 23/7/14 완료
- ~4주차(-23/7/25) : "Part Of A Whole"~ --> 23/7/17 완료
- ~5주차(-23/8/1) : "Evolution"~ --> 23/7/31 완료
- ~6주차(-23/8/8) : "Map"~ --> 23/8/7 완료
- ~7주차(-23/8/15) : "Flow"~ --> 23/8/9 완료
- ~8주차(-23/8/22) : "General knowledge"~ --> 1-7주차 까지의 내용이 반복되므로 생략
- ~customizing --> 23/10/20 완료~
- 9주차 : "1-4주차" 그래프 bokeh로 구현
- 10주차 : "5-8주차" 그래프 bokeh로 구현

## 구상중
- data set으로 그릴 수 있는 그래프의 목록 출력
  - 독립변수들 간의 모든 조합 고려
  - RDB 스키마의 속성을 따라갈지 고려


## 참고
프로젝트 상황은 밀릴 수 있음

- 해당 사이트에서 제공하는 데이터셋 mtcars의 url은
  - 'https://gist.githubusercontent.com/seankross/a412dfbd88b3db70b74b/raw/5f23f993cd87c283ce766e7ac6b329ee7cc2e1d1/mtcars.csv' 으로 변경해야함
- "Python graph gallery"의 샘플코드 중 Map에 관련된 geoplot은 사용할 수 없는것으로 판단하여 folium, plotly, pydeck으로 대체
- Flow step에서 'chord diagram'은 chord 라이브러리가 유료화가 되어 'pycirclize' 및 'bokeh'를 사용

