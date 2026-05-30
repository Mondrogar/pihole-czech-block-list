# Czech block list

Český blocklist reklam, sledování a dalšího internetového svinstva — zaměřený
hlavně na **české servery** (zpravodajství, e-shopy, ad-tech sítě).

Použitelný v **Technitium DNS**, **Pi-hole** a libovolném dalším DNS sinkholu
(AdGuard Home, Blocky, Unbound + blocklist atd.). Jde o prostý seznam domén,
jeden host na řádek.

## Použití

Přidej tento odkaz jako block list URL ve své DNS sinkhole:

```
https://raw.githubusercontent.com/Mondrogar/pihole-czech-block-list/master/turris-hole-czech-block-list
```

- **Pi-hole / AdGuard Home:** přidej URL do adlistů a aktualizuj (gravity / refresh).
- **Technitium DNS:** Settings → Blocking → Block List URLs → vlož URL → uložit a aktualizovat.

## Přispívání

Chybí ti tu nějaká reklamní/tracking doména, nebo naopak něco blokuje legitimní
web? Založ **issue** nebo pošli **pull request**.

⚠️ Prosím nepřidávej běžné weby (google.com, facebook.com apod.) ani nemaž věci
bezdůvodně. Cílem je blokovat reklamu a sledování, ne rozbít internet.

---

## English

A Czech-focused block list of ad, tracking and other junk sources — aimed mainly
at **Czech websites**. Works with **Technitium DNS**, **Pi-hole** and any other
DNS sinkhole (AdGuard Home, Blocky, …). Plain domain list, one host per line.

Add the raw URL above as a block list source. Missing a domain or hitting a false
positive? Open an issue or a pull request — just don't add normal sites
(google.com, facebook.com, …) and don't remove entries without reason.

---

Základ pochází z [qxstyles/turris-hole-czech-block-list](https://github.com/qxstyles/turris-hole-czech-block-list)
(původní repo už není udržováno) — díky za odražení. Dál žije tady.
