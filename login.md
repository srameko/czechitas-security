# Přihlašování

Vždy když se přihlašujete (odesíláte) Vaše (osobní) data ujistěte se, že používáte protokol *HTTPS*. Není-li tomu tak, vystavujete se riziku, že kdokoli po cestě (mezi vaším počítačem a serverem) tyto informace zachytí a zneužije je.

Proto pokud platíte kartou, přihlašujete se anebo zadáváte jiná citlivá data (číslo občanského průkazu, pasu,...) zkontrolujte, že stránka používá protokol HTTPS.

## 2FA

Dvoufaktorová autentizace, 2FA, dvoufaktor, multifaktorová autentizace, „ta otravná věc když chci poslat peníze a přijde mi SMS“. To jsou jen některé z názvů bezpečnostní metody zajišťující ověření uživatele, kterou byste měli používat minimálně u klíčových služeb všude, kde je to možné.

Dvoufaktorové ověření v principu rozděluje přihlašovací sekvenci do více kroků a zpravidla pro přihlášení potřebujete znát nejen uživatelské jméno a heslo, ale zároveň mít přístup k dalšímu zařízení či aplikaci, které vygeneruje příslušný kód(Authy)/potvrdí přihlášení(YubiKey/Duo).

## Heslo

Slouží k autentizaci uživatele, tedy k doložení, že je to skutečně on a je oprávněný využívat určité služby či funkce. Oprávněný uživatel musí držet své heslo v tajnosti.

Heslo je složeno ze znaků (malá abeceda, velká abeceda, číslice, speciální znaky). Čím je heslo delší, tím je pro útočníka těžší takové heslo rozlomit (útok hrubou silou). Ideálně by v současné době mělo být heslo delší než 13 znaků (složené jen ze znaků malé abecedy).

Není v lidských silách pamatovat si všechna hesla (měla by být unikátní pro všechny služby a tvořena náhodně). Proto je vhodné používat správce hesel. Zajištuje také náhodné generování hesel nových.

Pomůcka pro online vygenerování [frázového](https://1password.com/password-generator/) hesla, vhodného jako _hlavního_ hesla pro správce hesel.

## Správce hesel

Software pro správu hesel je program, který umožňuje vytváření, uchovávání a správu hesel, které se používají k ověření identity uživatele. Výhodou softwarového správce je možnost použití silných hesel, jedinečného hesla pro každou službu a bezpečného, šifrovaného uložení hesel.

Přístup do správce hesel je zpravidla zajištěn pomocí _hlavního_ hesla a dalšího faktoru (ideálně).

Správce hesel vám také může pomoct s kontrolou, jestli vaše heslo není mezi uniklými. Jestli vaše heslo už někde nepoužíváte (opětovné použití hesla) anebo jestli pro danou službu můžete nastavit 2FA. Mezi užitečné funkce patří i uložení souborů, tzn. pokud máte klíč, určený k přihlašování můžete si jej do správce hesel uložit také.

---
[zpět](index.md)
