# Enoa-Engine II — veřejné informace

**Vlastní 3D herní engine a editor EnoaSoftu, vyvíjený v C++17.** Tento repozitář je **veřejná prezentace projektu**, nikoliv zveřejnění zdrojového kódu.

![Enoa-Engine II editor](../media/screenshots/editor-scene.jpg)

## O projektu

Enoa-Engine II vzniká jako nezávislá technologie pro tvorbu 3D prostředí a taktických FPS. Součástí vývoje je vlastní editor pro Windows s rendererem Direct3D 11. Projekt zahrnuje nástroje pro scény, materiály, terén, vegetaci, animace a herní systémy.

Hlavním dlouhodobým cílem je **Silent Patrol: Vietnam**, jedna připravovaná hra, kterou vyvíjíme dvěma paralelními technologickými cestami — v Unreal Engine 5 a na Enoa-Engine II. Smyslem vlastního enginu je postupně omezovat závislost na externí technologii.

## Co je v aktivním vývoji

- **Editor a render:** hierarchie scén, nástroje pro výběr a transformaci objektů, PBR materiály, stíny, atmosféra, parallax mapping a automatické LOD.
- **Tvorba světa:** generování a úpravy terénu, rozmísťování vegetace, import glTF/GLB, propojení s Blenderem a knihovna Poly Haven.
- **Herní systémy:** FPS controller, kolize, Lua skripty, navigace a vnímání AI, zvuk.
- **Prezentace hry:** hlavní menu, cutscény, kamerové cesty a sestavení samostatného herního balíčku.

Nejde o tvrzení, že všechny oblasti jsou hotové nebo produkčně ověřené. Projekt stále prochází vývojem a testováním.

## Jak byly získány ukázky

Přiložené snímky zachycují **postupný vývoj testovaný přes Wine**. Případné zobrazené FPS se **nesmí** vydávat za výkon nativního Windows buildu. Porovnávací screenshoty ukazují změnu konkrétní funkce, nikoli finální podobu hry.

## Přístup k projektu

Zdrojový kód, editor a herní projekt jsou zatím soukromé. Tento veřejný repozitář neobsahuje otevřenou licenci, SDK ani vydanou hru. Další informace najdete v [aktuálním statusu](STATUS.md) a [FAQ](FAQ.md).

**Oficiální web:** https://enoasoft.cz  
**Projekt:** Enoa-Engine II · **Studio:** EnoaSoft
