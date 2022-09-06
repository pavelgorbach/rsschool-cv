# Pavel Gorbach

**Frontend developer**

Email: polgorbach@gmail.com\
Discord: Pavel(@pavelgorbach)

***

I am a Frontend developer with a focus on high performance Web apps. I love solving problems, making things simple, fixing things that could be improved, and making the user experience simple but efficient. I like to drive projects and make sure that they are appropriately designed. Passionate about code quality, unit testing, functional programming.

## Technical expertise
**Programming languages**:\
JavaScript, HTML, CSS

**Frameworks, libraries, services**:\
React, Redux, JQuery\
SASS, Less, CSS Modules, Bootstrap\
ESlint, Prettier, Jest

**Development environments (IDE/Tools)**:\
iTerm2, zsh, Vim, VSCode, GitHub, Jira, Figma, Discord

## Code example

**Roman Numeral Converter**
```
const hash = {
  1: 'I',
  4: 'IV',
  5: 'V',
  9: 'IX',
  10: 'X',
  40: 'XL',
  50: 'L',
  90: 'XC',
  100: 'C',
  400: 'CD',
  500: 'D',
  900: 'CM',
  1000: 'M'
}

const convertToRoman = (num) => {
  const result = []

  Object.keys(hash).reverse().forEach((n) => {
    while (n <= num) {
      result.push(hash[n])
      num -= n
    }
  })
  
  return result.join('')
}
```

## Experience/Projects
1. [Rick and Morty Widget](https://rknmorty.web.app/)
2. [Quote Machine](https://qt-machine.web.app/)
3. [Markdown](https://mrkdwn-previewer.web.app/)
4. [JS Calculator](https://clclator.firebaseapp.com/)
5. [Drum Machine](https://drmmachine.web.app/)
6. [Clock 25](https://clock25.web.app/)

## Education/Certificates

**freeCodeCamp** — [Back End Development and APIs](https://www.freecodecamp.org/certification/fcc59ca2997-2d59-4c7a-b63e-f734c43412bd/back-end-development-and-apis)\
*Aug 2022 - Sep 2022*.

**freeCodeCamp** — [Front End Development Libraries](https://www.freecodecamp.org/certification/fcc59ca2997-2d59-4c7a-b63e-f734c43412bd/front-end-development-libraries)\
*Jul 2022 - Aug 2022*.

**freeCodeCamp** — [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/certification/fcc59ca2997-2d59-4c7a-b63e-f734c43412bd/javascript-algorithms-and-data-structures)\
*Sep 2021 - Feb 2022*.

Belarusian State University of Culture and Arts — Bachelor’s Degree\
*Sep 2010 - ...*.

## Languages

English - B2(Upper Intermediate)

Belorussian, Russian - Native or bilingual proficiency
