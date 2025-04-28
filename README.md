# Ebooks

**Ebooks** je webová aplikace pro správu a sdílení souborů a dokumentů, určená pro osobní použití. Umožňuje bezpečné nahrávání, třídění, popisování, sdílení a zálohování souborů v jednoduchém rozhraní.

## Funkce

- Správa souborů a složek (nahrávání, mazání, přejmenování, přesun, poznámky)
- Sdílení souborů pomocí odkazů s časově omezenou platností
- Hromadné operace (mazání, přesun
- To-do list pro uživatele
- Statistiky využití úložiště a typů souborů (grafy)
- Zálohování a údržba (zálohy, test zápisu, čištění dočasných souborů)
- Moderní rozhraní (Bootstrap 5, ikony)

## Instalace

1. Naklonujte repozitář:
   ```sh
   git clone https://github.com/uzivatel/ebooks.git
   ```
2. Nahrajte soubory na svůj webserver s podporou PHP 7.4+.
3. Složkám `/uploads`, `/backups`, `/shares`, `/data` a nastavte jim práva pro zápis.
4. Upravte `includes/config.php` a nastavte uživatele a hesla.
5. (Volitelné) Nastavte SMTP v `includes/share_email_send.php` pro odesílání sdílených odkazů emailem.
6. Přihlaste se přes webové rozhraní.

## Příklad použití

- Nahrávání a třídění souborů do složek
- Přidávání poznámek k souborům
- Sdílení odkazu na soubor s platností 10 minut až 90 dní
- Stahování více souborů najednou jako ZIP
- Hromadné mazání a přesun souborů
- Správa záloh a údržba systému z administrace

## Changelog

- **v0.1** – První veřejná verze, základní správa souborů, sdílení, zálohy, údržba
- **v0.1.1** – Hromadné operace, grafy statistik, emailové sdílení, to-do list
- **v0.2** – Opravy chyb, vylepšení bezpečnosti, nové možnosti nastavení
