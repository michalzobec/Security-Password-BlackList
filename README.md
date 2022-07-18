# Seznam zakázaných slov v heslech | Password Blacklist

<a name="documenttitle"></a>

**Verze 2207.2 (2022/07/18)**

Copyright &copy; 2021-2022 Michal Zobec, ZOBEC Consulting. All Rights Reserved.

## O tomto repozitáři

Tento repozitář řeší problematiku často používaných slov, frází a znaků v heslech. Budu zde řešit jak soubor pravidel definující zákaz užívání nežádoucích znaků, slov a frází v heslech, tak také evidenci konkrétního seznamu nejčastěji užitých zakázaných slov pro jejich možnost implementace do nástrojů a služeb, která podporují volitelné seznamy zakázaných termínů v heslech.

Cílem tohoto repozitáře je zaměřit se na užívání s ohledem na uživatele v České republice, což je hlavní prioritou tohoto repozitáře, ale s ohledem na praxi se budu snažit zahrnout i termíny slovenské, či anglické.

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")

### About this repository (English)

This repository solves the problem of frequently used words, phrases and characters in the password. Here I will deal with both the set of rules defining the use of unwanted characters, words and phrases in the password, as well as the registration of a specific list of the most frequently used prohibited words for the possibility of their implementation into tools and services that support optional lists of prohibited terms in the password.

The goal of this repository is to focus on usage with regard to users in the Czech Republic, which is the main priority of this repository, but with regard to practice, I will try to include Slovak and English terms as well.

With the above in mind, I will not (at least for now) translate this project into English. If you are interested in the topic, please use Google Translator.

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")

## Proč bych se měl zajímat o seznam zakázaných slov?

Vzhledem k tomu, jak je v poslední době důležité věnovat kvalitě hesel zvýšenou pozornost, je na místě implementovat, či definovat zakázaná slova, fráze, výrazy, znaky, či definice, co by heslo obecně nemělo obsahovat.

Definice zakázaných slov v heslech (password blacklist) by se měla implementovat jak procesně (pracovně/právně), tak pokud možno i technicky. Na základě mých zkušeností je nejlepší rovnou znemožnit, či omezit slabá místa v heslech, než spoléhat na to, že uživatelé budou dodržovat důsledně všechna pravidla. Ostatně všichni jsme jen lidé. :)

Mimo jiné by vás mělo zajímat také to, že využití seznamu zakázaných slov 

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")

## Kde mohu použít seznam zakázaných slov?

Implementace volitelného seznamu zakázaných slov v heslech je možná v následujících službách, či nástrojích:

* Azure Active Directory Premium 1,
* Azure Active Directory Premium 2,
* ZOBEC Sign-In Protection,
* vlastní řešení filtru pro hesla v Active Directory,
* vlastní řešení filtru pro hesla ve vlastní aplikaci.

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")

## Pravidla

Dokument [pravidla](PRAVIDLA.md) definuje pravidla jak hesla vytvářet a především, co by hesla neměly obsahovat. Snažil jsem se o relativně podrobný popis, ale šlo mi v tomto případě o pochopení na straně uživatelů, než o podrobný a úplný popis zákazů.

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")

## Seznam zakázaných slov

*Je v plánu (To-do).*

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")

## Documentation (all documents)

* [Hlavní dokument](README.md).
* [Pravidla](PRAVIDLA.md).
* [Historie změn](HISTORY.md).
* [Licence](LICENSE.).

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")

## Links

- [NIST Special Publication 800-63B: Digital Identity Guidelines - Authentication and Lifecycle Management](https://pages.nist.gov/800-63-3/sp800-63b.html) (anglicky)
- [Twitter's List Of 370 Banned Passwords](https://www.businessinsider.com/twitters-list-of-370-banned-passwords-2009-12) (anglicky)
- [Tutorial: Configure custom banned passwords for Azure Active Directory password protection](https://docs.microsoft.com/en-us/azure/active-directory/authentication/tutorial-configure-custom-password-protection) (anglicky)

[*Zpět nahoru*](#documenttitle "Zpět na začátek dokumentu")
