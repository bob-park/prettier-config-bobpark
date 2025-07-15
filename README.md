# prettier-config-bobpark
이것은 'Bob Park' 의 prettier 를 적용한 Shared Configuration Repository 이다.

## 적용된 것
- width: 120px
- semi
- single quote
- tab width: 2
- imports sort
- tailwindcss sort


## custom import orders patterns
- ^react
- ^next
- ^expo
- ^@tanstack
- ^@bob-park
- 내부 @/
- third party modules
- ./ 이하 내부 상대 경로

## 사용 예시
```json
// package.json

{
  ...,
  "prettier": "@bob-park/prettier-config-bobpark"
}

```

