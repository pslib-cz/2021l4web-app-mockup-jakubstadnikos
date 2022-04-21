# Aplikace SwapIT
## O aplikaci
- Aplikace je určená pro matky a otce, kteří mají věci, které jejich děti již nepoužívají a chtěli by je vyměnit za nové.
- V této aplikaci si najdou někoho, kdo vyměnuje věc dle jejich představ a domluví se na výměně.
- Do svého profilu si přidají věci, které chtějí poslat dál. Ty pak vidí ostatní lidé. V aplikaci si mohou dopisovat a domluvit výměnu. 
## Vlastnosti
```css
@import url('https://fonts.googleapis.com/css2?family=Epilogue:wght@100;300;400;600;700;800&display=swap');
/* font-family: 'Epilogue', sans-serif; */
:root{
    --white: #FFFFFF;
    --shadow: #1a17411f;
    --light-gray: #F7F7F7;
    --gray-background: #F2F2F2;
    --black: #1A1741;
    --dark-gray: #484848;
    --purple: #A540E9;
    --pink: #FF1495;
    --blue-text: #5BC2F9;
    --gray-text: #E5E5E5;
}
body{
    background-color: var(--gray-background);
    margin: 0;
    font-family: 'Epilogue', sans-serif; 
}
.title{
    font-size: 30px;
    font-weight: bold;
    line-height: 30px;
    letter-spacing: 1px;
}
.white{
    color: var(--white);
}
.black{
    color: var(--black);
}
p{
    font-size: 16px;
    line-height: 17px;
    letter-spacing: 2px;
}
.shadow{
    box-shadow: var(--shadow) 0 3px 6px;
}
```



## Header
```html
<header class="top-header">
        <div class="header-box">
            <h1 class="header-title">SwapIT</h1>
        </div>
 </header>
```
```css
.header-box{
    width: 100vw;
    background-color: #ffffff50;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 0 0 12px 12px;
    box-shadow: var(--shadow) 0 3px 6px;
}
.header-title{
    color: var(--white);
}
```
## Navigační lišta
```html
    <div class="nav-box">
        <a href="#"><img src="./svg/home.svg" alt=""></a>
        <a href="#"><img src="./svg/heart.svg" alt=""></a>
        <a href="#"><img src="./svg/messages.svg" alt=""></a>
        <a href="#"><img src="./svg/search.svg" alt=""></a>
        <a href="#"><img src="./svg/person.svg" alt=""></a>
    </div>
```

```css
    .nav-box{
    position: fixed;
    bottom: 0;
    width: 100vw;
    background-color: var(--light-gray);
    height: 80px;
    border-radius: 30px 30px 0 0;
    display: flex;
    align-items: center;
    justify-content: center;

}
.nav-box a{
    padding: 10px;
}
```
## Úvodní stránka
- Nacházejí se zde nejnovější objevy, mezi kterými se dá procházet. Pokud posunute obrázek do leva, tak se vám věc nelíbí a pokud posunute do prava, tak o ní máte zájem. 
- Tlačítko Info: vás přesměruje na více informací o produktu. Název souboru: `info-main.svg`
- Tlačítko srdce: znamená, že se vám produkt líbí. Název souboru: ``like-main.svg``
- Tlačítko křížek: produkt se vám nelíbí. Název souboru: `dislike-main.svg`
- Obrázek na pozadí: `background-image: url(../svg/background-diagonal-large.svg);`
![Návrhová plocha 1](https://user-images.githubusercontent.com/79641987/162609725-4e1ebdae-69d5-4007-9a9e-31c17e75ad25.jpg)
- Vyhledávání box: `vyhledávat.svg` ikona: `search.svg`
### Stránka vyhledávat
- Zde se dá vyhledávat konkrétní kategorie, která vás zajímá.
- Obrázek na pozadí: `background-image: url(../svg/background-diagonal-small.svg);`
### Kategorie
- Pod vyhledáváním se nacházejí jednotlivé kategorie s produkty a tlačítkem na přidání do oblíbených.
- Obrázky kategorií: 
```
kategorie-hracka.svg
kategorie-obleceni.svg
kategorie-obuv.svg
kategorie-sport.svg
```
### Možnosti vyhledávání
- Obrázek na pozadí: `moznosti-vyhledávání.svg`
### Design
[Domovská stránka.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534275/Domovska.stranka.pdf)
## Stránka líbí se mi
- Zde se nacházejí jednotlivé produkty s profily, které se vám v minulosti líbily.
- Jednotlivé produkty se dají rozkliknout na stránku s více informacemi o produktu.
- Jednotlivé profily inzertů se dají rozkliknout.
- Tlačítko kontakt vás převede na chat s konkrétní osobou.
- Obrázek na pozadí: `background-image: url(../svg/background-chat.svg);`
### Design
[Líbí se mi.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534273/Libi.se.mi.pdf)
## Stránka chatty
- Nacházejí se zde jendotlivé chatty s inzerty.
- Obrázek na pozadí: `background-image: url(../svg/background-chat.svg);`
### Nové shody
- Zde jsou vypsány nové shody. Tj. profily, se kterými se vám navzájem líbí produkty.
### Líbí se vaše produkty
- Zde jsou vypsány profily, kterým se líbil váš produkt a vy můžete rozkliknout jejich profil, zda se vám nelíbí něco z jejich nabídky. 
### Design
[Chatty.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534265/Chatty.pdf)
### Design chattu
[Chat.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534267/Chat.pdf)
## Stránka vyhledávání
- Zde se nachází vyhledávání různých kategorií, o které byste mohli mít zájem.
- Obrázek na pozadí: `background-image: url(../svg/background-diagonal.svg);`
### Design
[Vyhledávání.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534263/Vyhledavani.pdf)
## Stránka můj osobní profil 
- Zde je váš osobní profil.
- Jméno, fotografie, krátký popisek, tlačítko filtrování, co vás zajímá a vaše inzeráy.
- Obrázek na pozadí: `background-image: url(../svg/background-gradient.svg);`
### Design
[Osobní profil.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534257/Osobni.profil.pdf)
### Filtrovat výběr
- Zde můžete zaškrtnout kategorie, které vás zajímají, například: oblečení, hračky...
- Věkové hranice: 8-12 let, 2-3 roky.
- Stav zboží: Nové, jako nové, použité.
### Moje inzeráty
- Zde jsou vypsaný všechny vaše inzeráty.
- Tlačítko plus –> přidat inzerát.
## Nový inzerát
- Přidání nového inzerátu.
- Popisek, kategorie, fotografie, stav, lokalita.
- Obrázek na pozadí: `background-image: url(../svg/background-gradient.svg);`
### Design
[Nový inzerát.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534231/Novy.inzerat.pdf)
## Inzerát hračky
- zde se nachází detailní popis inzerátů.
- Fotografie s přidáním do oblíbených.
- Název, kategorie, popisek, Jméno a fotografie inzerta s prokliknutím na profil. 
- Tlačítko líbí se mi: přidá inzerát mezi oblíený.
- Tlačítko kontaktovat: přesune na chat s inzertem.
- Obrázek na pozadí: `background-image: url(../svg/background-diagonal.svg);`
### Design
[Hračka.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534249/Hracka.pdf)
## Profil inzerta
- Zde se nachází jméno a fotografie inzerta, s krátkým popiskem.
- Jednotlivé inzeráty, které osoba nabízí.
    - Tlačítko zjistit více –> přesměruje vás na více informací o produktu.
    - Tlačítko kontaktovat –> přesměruje vás na chat s konkrétní osobou.
- Líbí se je místo kde jsou ukázány vaše produkty, které se osobě líbí.
- Obrázek na pozadí: `background-image: url(../svg/background-profil.svg);`
### Design
[Profil inzerta.pdf](https://github.com/pslib-cz/2021l4web-app-mockup-jakubstadnikos/files/8534195/Profil.inzerta.pdf)
