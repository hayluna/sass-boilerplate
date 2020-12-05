# sass-boilerplate

//live server 익스텐션 설치는 기본! live server와 궁합이 좋은 live sass compiler를 사용한다.

VS CODE에서
1. Live Sass Compiler 설치
2. 설정에서 live sass 검색 후, Live Sass Compile> Settings: Format 항목 -> setting.json에서 편집 클릭
```
"liveSassCompile.settings.formats": [

  {
    "format": "expanded",
    // "extensionName": ".css",
    "savePath": "/css"
  }
]
```
3. Generate Map항목 -setting.json에서 편집 클릭
```
"liveSassCompile.settings.generateMap": false,
````
4. VS CODE 하단의 Watch Sass 클릭
5. 하단 우측의 Go Live 클릭(live server실행)
