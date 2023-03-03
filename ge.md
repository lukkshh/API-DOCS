

# Random Quotes Generator Api

***MADE WITH ❤ BY LUKKSHH***

## შესავალი

Lukkshh Quotes არის უფასო, open source ციტატების API. რომელიც Php_ის სწავლის დროს გავაკეთე. (●'◡'●)


## მახასიათებლები

- ინგლისური ციტატები
- ქართული ციტატები

## Get Quote 

```http
GET https://lukkshh.ga/quotes/api/?API_KEY=KEY&LANG=LANG
```

- ენა უნდა იყოს **GEO** ან **ENG**

| პარამეტრი | ტიპი     | აღწერა                     |
| :-------- | :------- | :------------------------- |
| `API_KEY` | `string` | **Required**. შენი API key |

| პარამეტრი | ტიპი     | აღწერა                     |
| :-------- | :------- | :------------------------- |
| `LANG` | `string` | **Required**. GEO ან ENG |

### კოდის მაგალითი 

```javascript
const API_KEY = 'API';
const LANG = 'ENG';
```

```javascript
fetch(`https://lukkshh.ga/quotes/api/?API_KEY=${API_KEY}&LANG=${LANG}`)
  .then((response) => response.json())
  .then((data) => console.log(data));
```

### კითხვების შემთხვევაში დამიკავშირდი

- მეილზე **luka@lukkshh.ga**
- დისქორდი **lukkshh#3849**


