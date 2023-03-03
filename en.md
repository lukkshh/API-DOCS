

# Random Quotes Generator Api

***MADE WITH ❤ BY LUKKSHH***

## Introducion

Lukkshh Quotes is a free, open source quotations API. I Built It For Fun While Learning Php. (●'◡'●)


## Features

- English Quotes
- Georgian Quotes

## Get Quote 

```http
GET https://lukkshh.ga/quotes/api/?API_KEY=KEY&LANG=LANG
```

- Lang Need To Be **GEO** or **ENG**

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `API_KEY` | `string` | **Required**. Your API key |

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `LANG` | `string` | **Required**. GEO or ENG |

### Code Example 

```javascript
const API_KEY = 'API';
const LANG = 'ENG';
```

```javascript
fetch(`https://lukkshh.ga/quotes/api/?API_KEY=${API_KEY}&LANG=${LANG}`)
  .then((response) => response.json())
  .then((data) => console.log(data));
```

### In Case Of Questions Feel Free To Contact Me 

- Mail **luka@lukkshh.ga**
- Discord **lukkshh#3849**


