# Yan Logan

## Contacts

* __Telegram__: @yanlogan
* __Email__: [yanlogans@gmail.com](mailto:yanlogans@gmail.com)
* __Skype__: live:yanlogans
* __VK__: [vk.com/yanlogan](https://vk.com/yanlogan)

## About Me

I'm an aspiring self-taught Junior Frontend Developer, who potentially wants to become a Fullstack Developer.

Right now I don't have much of experience in the field, but I've already finished some freelance projects. I didn't get my university degree, but I made the most out of my time spent there. I love to learn, that's why I'm currently studying online to achive my goal of becoming a pro.

## Soft Skills

* effective communitation
* ability to understand specific text (documentation, articles etc.)
* googling and asking the right questions (it's really important)
* problem-solving
* explaing difficult concept to others more simply

## Tech Skills

__General__:
* HTML5
* CSS / Sass / Scss
* Basic JavaScript / JQuery
* Bootstrap 4 / Flexbox
* BEM
* npm
* Git / GitHub
* Gulp 4
* Wordpress

__Some Concepts__:
* OOP (Java / C# / PHP)
* Databases (MySQL)
* Pug
* yarn
* React

## Code Examples

__HTML__

```html
<footer class="footer">
	<div class="container">
		<div class="footer-wrapper">
			<h2 class="section-title">Контакты</h2>
			<section>
				<aside>
					//= ../site-logo/site-logo.html
				</aside>
				<article>
					<div class="footer__title">Sun Petroleum Limited  Partnership (UK)</div>
					<div class="footer__address">
						Pioneer Energy Holdings Pty Ltd. 9<br>
						Ken White Way, Mackay Harbour,<br>
						Queensland, UK
					</div>
					<div class="footer__email">
						//= ../icon-envelope/icon-envelope.html
						splp@sunenergy.com
					</div>
				</article>
				<article>
					<div class="footer__title">Sun Energy FZE (UAE)</div>
					<div class="footer__address">
						Pioneer Energy Holdings Pty Ltd. 9<br>
						Ken White Way, Mackay Harbour,<br>
						Queensland, UK
					</div>
					<div class="footer__email">
						//= ../icon-envelope/icon-envelope.html
						fze@sunenergy.com
					</div>
				</article>
				<div class="footer__copyright">&copy; Sun Energy Group, 2019</div>
			</section>
		</div>
	</div>
</footer>
```

__CSS__

```css
.header-top {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  padding: 0 20px 0 25px;
  color: #fff;
}

.header-top .header-menu {
  width: 612px;
  margin-top: 10px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.header-top .header-menu a {
  font-family: 'Rubik Medium';
  color: #fff;
}

.header-top .header-menu .header-menu__language_active {
  color: #afafaf;
}

.header-top .header-menu__btn .icon-envelope {
  margin-right: 8px;
}

.header-top .header-menu__btn .icon-envelope path {
  fill: white;
}

.header {
  background: #fff url("/img/header-slider/slider-bg.jpg") no-repeat 0 0;
  background-size: cover;
}

.header-bg {
  padding: 23px 0 40px;
  width: 100%;
  min-height: 390px;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(5, 12, 18, 0.6)), to(rgba(5, 12, 18, 0)));
  background-image: linear-gradient(to bottom, rgba(5, 12, 18, 0.6) 0%, rgba(5, 12, 18, 0) 100%);
}

.header-slider {
  margin-top: 500px;
  background-color: rgba(20, 20, 20, 0.8);
}

.header-slider__slide {
  display: none;
}

.header-slider__text {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  -webkit-box-align: end;
      -ms-flex-align: end;
          align-items: flex-end;
  padding: 30px 10px 25px;
  color: #fff;
  font-family: 'Rubik Medium';
  font-size: 24px;
  line-height: 36px;
}

.header-slider__text span {
  max-width: 620px;
}

.header-slider__text a {
  color: #fff;
  font-size: 16px;
  line-height: 22px;
  border-bottom: 2px solid #67bf00;
}

.header-slider .header-slides {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
}

.header-slider .header-slides .header-slider__btn {
  width: 238px;
  height: 4px;
  background-color: #fff;
  opacity: .7;
  cursor: pointer;
}

.header-slider .header-slides .header-slider__btn_active {
  background-color: #67bf00;
}
```

__JavaScript__

```javascript
"use strict";

const isNumber = function (str) {
	if (isNaN(+str) || str === "" || (str !== "0" && +str === 0)) return false;
	else return true;
};

const guessNumber = function () {
	do {
		var guess = prompt("Ваша попытка:");
		if (guess !== null && !isNumber(guess)) alert("Введи число!");
	} while (!isNumber(guess) && guess !== null);

	return guess;
}

const play = function() {
	do {
		var userGuess = guessNumber();
		if (userGuess !== null) {
			if (parseInt(userGuess) > correctNumber) alert("Меньше!");
			else if (parseInt(userGuess) < correctNumber) alert("Больше!");
			else if (parseInt(userGuess) === correctNumber) alert ("Правильно!");
		}
	} while (parseInt(userGuess) !== correctNumber && userGuess !== null);
}

var correctNumber = Math.floor(Math.random() * 1000);
alert("Поиграем? Угадайте число от 0 до 1000!");
console.log(correctNumber);
play();
```

## Experience

I've finished a couple of freelance projects. Latest of them are:
[Zabolotnov.com](http://zabolotnov.com/) and [Sun Petrol](http://demo.sunpetrolgroup.com/). All made as a custom Wordpress Template (from scratch).

## Education

* ITMO University (St. Petersburg, Russia)
* Treehouse - [Full Stack JavaScript](https://teamtreehouse.com/tracks/full-stack-javascript)
* Skillbox - [Web Dev from 0 to PRO](https://course.skillbox.ru/webdev/)
* GloCademy marathones
* [The Rolling Scopes School](https://rs.school/russia/) (currently)
* FreeCodeCamp / HTMLAcademy / Codecademy
* Youtube

## English

Level: B2 / C1 (Upper-Intermediate / Advanced)

I studied at school with advanced english classes, after that I got level-placed at the university. I practice a lot daily by reading and watching content in english. I also used to teach english (for a couple of months).