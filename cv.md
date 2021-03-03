# Curriculum vitae

## **Personal Information**
 **Name**  

 Dmitrii Chernyshev  

 **Contact**
  * +7951 641 98 38 Telegramm

 **Objective**  

 I want to learn new things and I want to take part in interesting projects that improve the world

 **Skills** 
 * HTML
 * CSS
 * JavaScript
 * BEM
 * Git

 **Code examples** 
 ```
class CardList {
  constructor(container, makeCard, api) {
    this.container = container;
    this.makeCard = makeCard;
    this.api = api;
  }
addCard(card) {
  const cardElem = card.create();
  this.container.appendChild(cardElem);
}

render() {
  this.api.getCards().then((rest) =>{
    rest.forEach(function(data) {
    const card = this.makeCard(data.name, data.link);
    this.addCard(card)}.bind(this))})
    .catch((err) => {
      console.log(err);
     }) 
  }
}
```
 **Work experience**

 **Qualifications**
  * Yandex.Praktikum
  * FreeCodeCamp
  * EF eglish school

 **Level english**  
 
  B1