#Curriculum vitae

1. Dmitrii Chernyshev

2. +7951 641 98 38, Telegramm

3. I want to learn new things and I want to take part in interesting projects that improve the world

4. HTML/CSS,JavaScript, BEM, Git

5. class CardList {
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
6.
7. Yandex.Praktikum, FreeCodeCamp, EF eglish school
8. B1