---
id: info
title: info
sidebar_position: 3
---

# info

제목, 제작자, 버튼개수, 체인개수 등 팩에 대한 기본 정보를 정의합니다.

---

## info의 구조

| 명령어 | 형식 | 내용 |
|---|---|---|
| title | 문자열 | 팩의 제목 |
| producerName | 문자열 | 팩의 제작자 |
| buttonX | 자연수 | 세로 버튼 개수 |
| buttonY | 자연수 | 가로 버튼 개수 |
| chain | 자연수 | 체인 개수 |
| squareButton | 불린 | 버튼의 유형 |
| websiteURL | 문자열 | 웹사이트 URL |

## 예시

```
title=Alan Walker - Faded
producerName=Abc, Bcd
buttonX=8
buttonY=8
chain=5
squareButton=true
websiteUrl=https://unipad.kr
```

:::info
이전 형식에 있었던 **landscape** 명령어는 제거되었습니다.
:::
