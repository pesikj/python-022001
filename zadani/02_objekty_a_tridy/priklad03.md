# Vrácení auta

Pokračuj ve své práci pro autopůjčovnu z [příkladu 1](priklad01.md) a [příkladu 2](priklad02.md).

Přidej třídě `Auto` metodu `vrat_auto()`, která bude mít (krom obligátního `self`) 2 parametry, a to je stav tachometru při vrácení a počet dní, po které zákazník auto používal. Ulož stav tachometru do atributu objektu. Nastav vozidlo jako volné.

Dále v metodě vypočti cenu za půjčení. Cena je 400 Kč na den, pokud měl zákazník celkem auto méně než týden, a 300 Kč na den, pokud měl zákazník auto déle. Cena je stejná pro obě auta. Vlož cenu do nějakého informativního textu a ten vrať pomocí klíčového slova `return`.

Na konec programu (mimo třídu) přidej dotaz na uživatele, kolik kilometrů zákazník ujel a jak dlouho ho měl půjčené. Poté vypiš informaci o ceně.
