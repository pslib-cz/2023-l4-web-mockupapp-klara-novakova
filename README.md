# Aplikace na seznamy
## Úvod
Vytvořila jsem návrh aplikace pro shromáždění a vytváření nákupních seznamů. Dávalo by smysl, že by byla navrhnutá pro mobil, ale začala jsem desktop návrhem a nestíhám to dodělat, takže je návrh designu hlavně pro desktop. Do aplikace se vkládají produkty, které se pak dají shromažďovat do seznamů. Seznamy se dají uložit do oblíbených, nebo sdílet. <br>
Grafika se dá vyexportovat z figma souboru.
### Barevná paleta
```
:root {
    --zluta:#FFDE33;
    --svetle_zluta: #FCEB95;
    --cervena:#FF83232;
    --svetle_cervena: #FFABAB;
    --modra:#4596E6;
    --svetle_modra: #C9E8ED;
    --zelena:#378E43;
    --svetle_zelena: #7CDC89;
   }
```


### Font
Varela Round<br>
Embed code in the <head> of your html:<br>
```
<link rel="preconnect" href="https://fonts.googleapis.com"><br>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><br>
<link href="https://fonts.googleapis.com/css2?family=Varela+Round&display=swap" rel="stylesheet"><br>
```
Varela Round: CSS class:<br>
```
.varela-round-regular {
  font-family: "Varela Round", sans-serif;
  font-weight: 400;
  font-style: normal;
}
```
## Registrace
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2019.jpg)
Na začátku se každý uživatel musí registrovat s jedinečným uživatelským jménem.<br>
Registrace na mobilu:<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Android%20Small%20-%201.jpg)
 ## Homepage
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%207.jpg)<br>
Na homepage jsou už vytvořené seznamy. Tlačítkem přidat seznam se otevře formulář na přidání nového seznamu.<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2010.jpg)<br>
Po kliknutí na seznam se otevře stránka níže.<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2011.jpg)<br>
Po kliknutí na přidat člena se otevře okno, kam se zadá uživatelské jméno člověka, kterého chceme přidat a tomu přijde pozvánka na email.<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2018.jpg)<br>
Na mobilu by homepage mohla vypadat takto:<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Android%20Small%20-%202.jpg) <br>
Takhle vypadá rozbalené hamburger menu:<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Android%20Small%20-%203.jpg)<br>
 ## Katalog potravin
 ![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%202.jpg)
 Po najetí myší na potravinu se ukáže poznámka.<br>
 ![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2020.jpg)
 Katalog se dá filtrovat podle kategorií.<br>
Po kliknutí na jednotlivé produkty se ukáže toto: <br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2013.jpg)
## Oblíbené
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2012.jpg)
Po kliknutí na oblíbené:<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2014.jpg)
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%2015.jpg)
## Přidat produkt
Při přidávání produktu se nejdříve prokliká kategoriemi a pak zadají informace do okna.<br>
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%201.jpg)
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%208.jpg)
![ukazka](https://github.com/pslib-cz/2023-l4-web-mockupapp-klara-novakova/blob/main/uk%C3%A1zkov%C3%A9%20obr%C3%A1zky/Desktop%20-%209.jpg)

Odkaz na Figmu:
https://www.figma.com/file/tjWIvFYXmySyuIooD0Xv2Y/Untitled?type=design&node-id=0%3A1&mode=design&t=w9bETZ5pcuBw2wPW-1
