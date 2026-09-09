# Únik do 4D

Pro navštívení 4D světa ze 3D světa je nutno prvně pochopit jak by se dal navštívit 3D svět ze 2D. Budeme využívat místo metrů tvz. jednotky (zkratka `j`)

## Fungování 2D světa
2D svět je popsán osami X a Y. Proto může obsahovat vektory $(x, y)$.
První rozebereme jak funguje základní pohyb, fyzika, gravitace ve 2D a zjistíme co by člověk viděl ve 2D světě.

### Pohyb
Představme si trojúhelník $T$ s vrcholy $A[1, 1]$, $B[1, 2]$ a $C[2, 2]$.    

Můžeme se pohybovat 2 směry x a y. Což můžeme velmi jednoduše popsat přes vektory pohybu. Proto si zavoláme nového speciálního 2D člověka jménem Pepa.      

Pepa se dostat z bodu $[0, 0]$ do bodu $[0, 1.5]$. Pro nás pozorovatele se Pepa posunul po ose $y$ o $1.5\text{ j}$      

Pepa vidí pouze osu $y$, ale jelikož je dostatečně vyvinutý dokáže vnímat "hloubku", neboli osu $x$. Z trojúhelníku $T$ by tak viděl jednu jednorozměrnou úsečku, která je záhadným zůsobem nakloněná. První bod $A$ by se mu díky perspektivě a jasu zdál blíže než bod $C$.

Nová otázka je kdyby ten trojúhelník byl například červený, viděl by to náš pozorovatel? Abychom mohli na tuto otázku si zodpovědět musíme se první zeptat jak by ve světě Pepy fungovala Fyzika.

### Fyzika a gravitace
Začneme velmi jednoduchou a základní částí fyziky – gravitací. Existovala by ve 2D světě vůbec?

Odpověď zní: **Ano.** Kam by ale Pepu přitahovala, když „dole“ ani „nahoře“ (osa Z) v jeho světě neexistuje? Přitahovala by ho k ostatním objektům v rovině jeho světa. 

Protože uvažujeme uzavřený a autonomní 2D vesmír, síla gravitačního pole se nemůže šířit do prostoru (po povrchu koule), ale šíří se pouze v rovině (po obvodu kružnice). Podle Gaussova zákona proto intenzita gravitace neubývá se čtvercem vzdálenosti ($r^2$), nýbrž klesá **lineárně se vzdáleností ($r$)**.

2D Newtonův gravitační zákon má tedy tvar:

$$F_g = G_{2D} \frac{m_1 \cdot m_2}{r}$$

*Kde $G_{2D}$ je dvourozměrná gravitační konstanta s rozměrem $\text{j}^2 \cdot \text{kg}^{-1} \cdot \text{s}^{-2}$. Pro náš model uvažujme její hodnotu $6.674 \times 10^{-11}$, což nám umožní přímé srovnání sil s naším světem na jednotkovou vzdálenost.*

Pokud by Pepa vážil $50\text{ kg}$ a náš trojúhelník by byl masivní objekt o hmotnosti $1200\text{ kg}$ ve volném prostoru, při vzdálenosti $2\text{ j}$ by se přitahovali silou:

$$F_g = 6.674 \times 10^{-11} \frac{50 \cdot 1200}{2} \approx 2.002 \times 10^{-6} \text{ N}$$

Díky lineárnímu poklesu je gravitace na delší vzdálenosti ve 2D světě mnohem silnější než v našem 3D světě. Tento trojúhelník by pro Pepu fungoval jako malá „planeta“. Pepa by mohl po jeho povrchu (který tvoří obvodové úsečky) chodit a žít na něm. Gravitace by pro něj směřovala do těžiště trojúhelníku, což by definovalo jeho lokální směr „dolů“.

### Světlo a barvy
Nyní se můžeme vrátit k naší otázce: Pokud by byl trojúhelník červený, viděl by to Pepa? A jak by vlastně světlo v jeho světě fungovalo?

Stejně jako u gravitace, i pro světlo musíme uplatnit pravidlo dimenzionální fyziky. V našem 3D světě se světlo šíří ze zdroje všemi směry a vytváří zvětšující se kouli. Jeho jas (intenzita) proto s dálkou klesá se čtvercem vzdálenosti ($1/r^2$). V Pepově čistě 2D světě se však světlo šíří pouze v rovině – jako kruhy na hladině vody po vhození kamene.

Z toho plynou pro 2D světlo tři zásadní vlastnosti:

1. **Lineární úbytek jasu:** Intenzita světla ve 2D klesá pouze lineárně se vzdáleností ($1/r$). To znamená, že světlo v Pepově světě dosvítí mnohem dále a objekty ve tmě jsou vidět na podstatně větší vzdálenost než u nás.
2. **2D vlnová délka (Barva):** Barva je frekvence vlnění. Zatímco naše 3D světlo může kmitat v jakémkoliv směru kolmém na směr letu (nahoru/dolů, vlevo/vpravo), Pepovo 2D světlo má k dispozici pouze jeden směr kmitání. Pokud letí vpřed po ose $x$, může vlnění kmitat pouze do stran podél osy $y$. Pepovo lineární oko (sítnice) zachycuje právě tyto kmity. Pepa tedy **vidí barvy**, ale vnímá je jako barevné body či úsečky na své jednorozměrné zrakové linii.


#### Jak by Pepa viděl náš červený trojúhelník?
Když se Pepa podívá na červený trojúhelník `T - ABC`, světelné paprsky se odrazí od jeho obvodových úseček a dopadnou na Pepovo oko. 

Pepa neuvidí červenou plochu. Uvidí jednorozměrnou linku (osu $y$). Střed této linky (bod $A$, který je k němu nejblíže) bude zářit nejjasnější červenou barvou. Jak úsečka $AC$ směřuje k bodu $C$ , jas červené barvy bude kvůli vzdálenosti lineárně slábnout. 

Pepa tedy červenou barvu uvidí, a navíc díky postupnému slábnutí jejího jasu jeho mozek okamžitě dopočítá osu $x$ (hloubku) a pozná, že se dívá na špičatý objekt.


## Únik ze 2D do 3D prostoru

Aby mohl Pepa (nebo my v našem 3D světě) uvažovat o úniku do vyšší dimenze, musí nejprve zjistit, že tato dimenze vůbec existuje. V uzavřeném 2D vesmíru, kde osa $Z$ zdánlivě neexistuje, to vyžaduje schopnost odhalit anomálie, které běžná fyzika dané dimenze nedokáže vysvětlit.

### Teorie nekonečných 2D vesmírů (Osa Z)
Jakmile Pepa pochopí koncept osy $Z$, dojde k fascinujícímu kosmologickému závěru: **Náš 3D vesmír je složen z $n$ počtu 2D vesmírů.**

Stejně jako se 2D čtverec skládá z nekonečného množství 1D úseček položených těsně vedle sebe, tak se náš 3D prostor skládá z nekonečného množství 2D ploch (vesmírů) naskládaných na sebe podél osy $Z$. Celkový počet těchto paralelních 2D světů je určen tím, jak moc „široký“ je náš 3D vesmír ve směru výšky.

Každý tento 2D vesmír je od druhého oddělen jen nekonečně malým posunem po ose $Z$. Lidé v těchto sousedních světech žijí své vlastní životy na svých vlastních „plackách“, ale jsou od sebe izolovaní, protože jejich fyzika (světlo i gravitace) je uzamčena pouze v jejich konkrétní rovině. To by však znamenalo, že i když je fyzika uzamčena, ostatní 2D vesmíry by měli působit na Pepovo vesmír a ovlivňovat ho.

### Anomalie a objev třetí dimenze
Prvním krokem k objevu 3D světa by pro Pepu bylo pozorování jevů, které se v jeho rovině objevují „z čistého nebe“. 

Představme si, že skrz Pepovu 2D rovinu proletí trojrozměrný objekt – například **3D zelená koule**. 
1. **Z pohledu 3D pozorovatele:** Koule plynule klesá dolů skrz stůl.
2. **Z pohledu Pepy:** Pepa v dáli uvidí zelený kruh z boku, který se z ničeho nic víc a víc přibližuje a jeho velikost zvětšuje. Po dosáhnutí maxima se začne zase zmenšovat až úplně zmizí.

Zároveň by to znamenalo že do Pepovo vesmíru jsme přidaly hmotu, která vznikla z ničeho nic, což díky zákonu zachování energie nejde.



### Samotný únik
Pokud by Pepa našel způsob, jakým by mohl manipulovat s hmotou mimo své osy $X$ a $Y$, a dokázal by se posunout o jedinou jednotku podél osy $Z$, pro své spoluobčany by **doslova přestal existovat**. Zmizel by v jediném okamžiku bez jakéhokoliv záblesku či výbuchu.

Pepa by opustil svůj domovský svět a vstoupil by do **sousedního 2D vesmíru**, který pro něj byl dosud zcela nepoznaný. Mohl by tak cestovat napříč těmito paralelními světy jednoduše tím, že by „skákal“ nahoru a dolů po ose $Z$. 

Skutečným šokem by pro něj ale bylo, kdyby v ose $Z$ nezůstal jenom stát, ale kdyby dokázal své lineární oko **otočit směrem do třetí dimenze**. Poprvé v životě by neviděl sousední svět jako úsečku, ale spatřil by ho celý najednou – shora, jako dokonalou plochu.

