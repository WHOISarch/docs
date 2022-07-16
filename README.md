
![logo](http://logo.whoisarch.com/2/cover.png)

# [docs.whoisarch.com](https://docs.whoisarch.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/whoisarch/docs/edit/main/DOCS/MENU.md)

+ [Website - www.whoisarch.com](http://www.whoisarch.com/)
+ [Sourcecode - bash.whoisarch.com](http://bash.whoisarch.com/)
+ [Offer - offer.whoisarch.com](http://offer.whoisarch.com/)
+ [Documentation - docs.whoisarch.com](http://docs.whoisarch.com/)
+ [News - blog.whoisarch.com](http://blog.whoisarch.com/)
+ [Offer - offer.whoisarch.com](http://offer.whoisarch.com/)
+ [logo.whoisarch.com](https://logo.whoisarch.com/)
+ [LICENSE](LICENSE)



## ABOUT [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/whoisarch/docs/edit/main/DOCS/ABOUT.md)

Celem WHOISarch jest archiwizacja stanu domen, dzień po dniu
za pomocą narzędzia letWHOIS możliwe jest zarządzanie wieloma agentami grabWHOIS


Lista osbługiwanych agentów:

+ grabWHOIS
+ WebPageShot.bash


### letWHOIS

letWHOIS umożliwia pobieranie danych od wielu agentów na bieżaco lub raz dziennie
może być wykorzystywane w systemie do pokazywania danych w odpowiednim formacie:
+ CSV,
+ JSON,
+ TXT


### WebPageShot

archiwizuje wybrane strony www do postaci:
+ pliku graficznego, zrzutu ekranu:
  + png
  + jpg

+ pliku tekstowego:
  + html,
  + txt
  + md

## Install [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/whoisarch/docs/edit/main/DOCS/INSTALL.md)

Install from repo: https://github.com/plainedit/bash.git
```bash
./install.sh
```

Update works such git pull for bash repo: https://github.com/plainedit/bash.git
```bash
./update.sh
```

clean folders from temp files
```bash
./clean.sh
```



## EXAMPLES [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/whoisarch/docs/edit/main/DOCS/EXAMPLES.md)



```bash
./plainedit "1/in.md" "1/out.md" "1/auth.md"
```

```bash
./whoisarch.sh "input/catch/2022.05.txt"
```




## TODO [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/whoisarch/docs/edit/main/DOCS/TODO.md)

+ projekty:
+ grabwhois

Przenoszenie z input / today  to input / month

jesli dzisiejsza data w output nie istnieje to przenies zawartosc input i stworz nowy

move_from_output.sh


sprawdzic kt5orre nie byly jescze dzis sprawdzane


Dane do monitorowania
+ lista newsletterów od registrarów
+ lista zbanowanych stron, domen
+ lista wygasających
+ 


## Funkcje:
głowny:
diff.sh

folder:
diff/

day.sh
week.sh
month.sh
quartal

---

+ [edit](https://github.com/whoisarch/docs/edit/main/DOCS/README.md)
+ [whoisarch/docs](https://github.com/whoisarch/docs)
