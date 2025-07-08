# Osazovací návod - V1

Verze z roku 2021

## Jak postupovat

- **Vždy pájej pouze jednu úroveň najednou.**
- Vždy si vezmi jednu součástku, tu zapájej a až pak pokračuj s další.
- Pak můžeš zapájet ostatní součástky.
- Jakmile máš zapájeno, nalep zespodu USB konektoru podložku.

!!! info "Důležité informace"
	- Začni připájením integrovaného obvodu.
    	- U integrovaného obvodu si pohlídej jeho orientaci. Pokud si nejsi jistý, zeptej se lektora.
  	- Jako poslední připájej LED
	- U LED běžně na polaritě záleží. Na této desce však polaritu řešit nemusíte, obvod je navržen tak, aby na polaritě nezáleželo.



!!! danger "Bezpečnost práce"
	- Hrot páječky je horký (~300 °C).
	- Páječku vždy odkládejte do stojanu.
	- Udržujte pořádek na pracovišti.
	- Když se popálíte, tak si běžte popálené místo zchladit vodou, případně ledem. Popálené místo ničím nemastěte.


## L0
![](/media/solderingChallenge-v1/solderingChallenge-L0.png)

!!! Pozor danger
    Pozor, u kondenzátoru 4.7u záleží na polaritě. Popisek kondenzátoru
    musí směřovat <span style="color:red">**ven**</span> desky. Zeptej se lektora, pokud si nejsi jistý.


## L1 - THT
![](/media/solderingChallenge-v1/solderingChallenge-L1.png)

!!! Pozor danger
    Pozor, u kondenzátoru 4.7u záleží na polaritě. Popisek kondenzátoru
    musí směřovat <span style="color:red">**ven**</span> z desky (obráceně než u L0). Zeptej se lektora, pokud si nejsi jistý.

## L2 - 1206
![](/media/solderingChallenge-v1/solderingChallenge-L2.png)

## L3 - 0603
![](/media/solderingChallenge-v1/solderingChallenge-L3.png)

## L4 - 0402
![](/media/solderingChallenge-v1/solderingChallenge-L4.png)

## L5 - BGA + 0201
![](/media/solderingChallenge-v1/solderingChallenge-L5.png)

## Jak to funguje?

Pokud tě zajímá, jak funguje obvod, který jsi právě zapájel, podívej se např. na
[tento web](https://www.mylms.cz/zapojeni-casovace-555/). Tam se dočteš, jak
funguje integrovaný obvod 555. V naší pájecí výzvě používáme takzvané *astabilní
zapojení* neboli *multivibrátor*, který je na výše zmíněné stránce vysvětlen.
