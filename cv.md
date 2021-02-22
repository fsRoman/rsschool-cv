# Roman Khoroshaylo

## **contacts**

| ![phone](https://www.itgemini.net/images/head_ipone.png) +380713007403 | ![mail](https://www.jasshermagicshop.com/catalog/view/cfp/image/email-blue.png) horoshailo.r@gmail.com | [![telegram](https://telegram.org/favicon.ico)](https://t.me/jl1220) [![VK](https://obruchcdis.ru/assets/images/socl/VK.png)](https://vk.com/id312857266) [![facebook](https://static.xx.fbcdn.net/rsrc.php/yD/r/d4ZIVX-5C-b.ico)](https://www.facebook.com/profile.php?id=100000027149156) [![LinkedIn](https://www.robertamckinney.com/wp-content/uploads/2019/03/linkedin.png)](https://www.linkedin.com/in/roman-khoroshailo-078249173) |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |

## **about me**

I am currently working in a non-programming position. But I often write Powershell and VBA scripts for MS Access to automate and streamline workflows. I want to change specialization and become a **_Front-end_** or **_FullStack_ web developer**. I am interested in exploring this way and hope to learn the full development cycle.

## **my skills**

-   HTML + CSS
-   JavaScript (ES6)
-   Figma
-   git + GitHub
-   Node.js + Express.js
-   SQL

## **code example**

```javascript
function timeCorrect(timestring) {
    if (timestring === "") {
        return "";
    }

    const regexp = new RegExp(/\d\d:\d\d:\d\d/);

    if (!regexp.test(timestring)) {
        return null;
    } else {
        const timeArr = timestring.split(":").map((i) => parseInt(i));

        timeArr[1] += Math.floor(timeArr[2] / 60);
        timeArr[0] += Math.floor(timeArr[1] / 60);

        timeArr[2] = timeArr[2] % 60;
        timeArr[1] = timeArr[1] % 60;
        timeArr[0] = timeArr[0] % 24;

        return timeArr.map((i) => (i < 10 ? `0${i}` : i)).join(":");
    }
}

timeCorrect(null); //> null
timeCorrect(""); //> ""
timeCorrect("001122"); //> null
timeCorrect("00;11;22"); //> null
timeCorrect("0a:1c:22"); //> null
timeCorrect("09:10:01"); //> "09:10:01"
timeCorrect("11:70:10"); //> "12:10:10"
timeCorrect("19:99:09"); //> "20:39:09"
timeCorrect("19:99:99"); //> "20:40:39"
timeCorrect("24:01:01"); //> "00:01:01"
timeCorrect("52:01:01"); //> "04:01:01"
```

## **experience**

took courses on a **FreeCodeCamp**

-   Basic JS
-   Basic HTML and CSS
-   Applied Visual Design
-   Responsive Web Design Principles
-   CSS Flexbox

## **education**

-   from 20.02.2021 to the present time apprentice [**RS School**](https://rs.school/js/)

## **languages**

-   Russian (native)
-   Ukrainian
-   English A1 - A2 (I can read and write, but sometimes I need a translator)
