# Aplikace SwapIT
## O aplikaci
– Aplikace je určená pro matky a otce, kteří mají věci, které jejich děti už nepoužívají a chtěli by je vyměnit za nové
– V této aplikaci si najdou někoho, kdo vyměnuje hračku dle jejich představ a domluví se na výměně
– Do svého profilu si přidají své hračky, které pak vidí osatní lidé, poté si budou dopisovat v aplikaci a domluví výměnu 
## Vlastnosti

## Dúležité věci

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
    ###Style
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
– Nacházejí se zde nejnovější objevy, mezi kterými se dá procházet. Pokud posunute obrázek do leva, tak se vám věc nelíbí a pokud posunute do prava, tak o ní máte zájem. 
– Tlačítko Info: vás přesměruje na více informací o produktu. 
– Tlačítko srdce: znamená, že se vám produkt líbí
– Tlačítko křížek: produkt se vám nelíbí
![Návrhová plocha 1](https://user-images.githubusercontent.com/79641987/162609725-4e1ebdae-69d5-4007-9a9e-31c17e75ad25.jpg)

### Vyhledávat
– Zde se dá vyhledávat konkrétní kategorie, která vás zajímá
### Kategorie
– Pod tím se nacházejí jednotlivé kategorie s produkty a tlačítkem na přidání do oblíbených 
## Stránka líbí se mi
– Zde se nacházejí jednotlivé produkty s profily, které se vám v minulosti líbili
– jednotlivé produkty se dají rozkliknout na stránku s více informacemi o produktu
– Jednotlivé profily inzertů se dají rozkliknout
– Tlačítko kontakt vás převede na chat s konkrétní osobou
## Stránka chatty
– Nacházejí se zde jendotlivé chatty s inzerci
### Nové shody
– Zde jsou vypsaný nové shody
### Líbí se vaše produkty
– Zde jsou vypsaný profili, kterým se líbil váš produkt a vy můžete rozkliknout jejich profil, zda se vám nelíbí něco 
## Stránka vyhledávání
– Zde se nachází vyhledávání různých kategorií, o které byste mohli mít zájem
## Stránka můj osobní profil 
– Zde je váš osobní profil
– Jméno, fotografie, váš krátký popisek, tlačítko filtrování, co vás zajímá a vaše inzeráy
### Filtrování, co vás zajímá
– zde můžete zaškrtnout kategorie, které vás zajímají, například: oblečení, hračky...
– dále tu jsou věkové hranice, například: 8-12 let, 2-3 roky
– Stav zboží: Nové, jako nové, použité
### Moje inzeráty
– Zde jsou vypsaný všechny vaše inzeráty
– Tlačítko plus –> přidat inzerát
