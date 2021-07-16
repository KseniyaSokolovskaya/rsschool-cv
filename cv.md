# CV

<br/>

## Summary

**First Name:** Kseniya

**Last Name:** Sokolovskaya

**Primary skills:** HTML, CSS, JS(React)

**English:** B1

<br/>

## Contact Information

**Cell:** +375296201325

**Email:** deff.1990@gmail.com

**Skype:** kseniyasokolovskaya

<br/>

## About me

A dedicated web-designer with a hands-on experience in creating adaptive and crossbrowser templates, single page application and perfect-pixel PSD-to-HTML coding too.

I am familiar with float and grid techniques, however I prefer to use flexbox.

I have a professional expertise in native JS, React; moreover I have an experience of working with SCSS, JQuery, Gulp, Webpack, React and Redux. I use GIT for version control.

My short-term goal is to learn JS pattern and get hands-on experience React.

I’m focused, self-driven person who constantly striving for self-development and vocational trainings. I am looking for a company with a friendly team and interesting projects where I can get new experience and learn new tricks and techniques.

<br/>

## Work Experience

**HiQo-solutions (Aug-2019 - Sep-2020)::**

***(Feb-2020 - Present) HiQo Coins Application***

**Job-Position:** Front-end developer

**Customer:** HiQo solutions

**Team size:** Project Lead, 2 Back-end Developer, Front-end developer

**Project Role:** Front-end developer

**Technologies:** Webpack, React/React-router/Redux, Material UI, ESLint, SCSS Tools: VSCode, git, GitHub

**Task Performed:** investigate project, improve React/Redux knowledge

***(Aug-2019 -Dec-2019)***

- AshtonWoods https://www.ashtonwoods.com/

- Belgard https://www.belgard.com/

- CarterCenter https://forum.cartercenter.org/

- Starlighthomes

**Job-Position:** Junior Front-end developer

**Customer:** Definition6 https://www.definition6.com/

**Team size:** Project Lead, Back-end Developer, Front-end developer

**Project Role:** Front-end developer

**Technologies:** JS, JQuery, Gulp, SCSS, ESLint, AJAX, Google Maps Api Tools: VSCode, git, GitHub

**Task Performed:** development; analyzing, estimate and fixing bugs and performance issues; refactoring; implementing

<br/>

## Skills

| Professional skills              | Level    | Years of use |
| -------------------------------- | -------- | ------------ |
| JS                           |
| Core js                          | Advanced | 1            |
| React                            | Novice   | 1            |
| Redux                            | Novice   | 1            |
| User experience design (UXD) |
| HTML                             | Advanced | 1            |
| CSS3                             | Advanced | 1            |
| SASS/SCSS                        | Advanced | 1            |
| Material UI                      | Advanced | 1            |
| Version control system       |
| Git                              | Novice   | 1            |
| Graphic editor               |
| Adobe Photoshop                  | Advanced | 1            |

<br/>

## Code example
    import { useState } from 'react';
    import PropTypes from 'prop-types';


    const useLightBox = (isOpen) => {
      const [modalOpen, setModalOpen] = useState(isOpen);
      const toggle = () => setModalOpen(!modalOpen);
      return [modalOpen, setModalOpen, toggle];
    };

    useLightBox.propTypes = {
      isOpen: PropTypes.bool.isRequired,
    };

    export default useLightBox;
