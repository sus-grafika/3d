# 3D Grafika

- pracuje s 3D objekty
- **využití** 3D grafiky
	- počítačové hry (CSGO), 
	- filmy (Pixar), 
	- Architektura (návrh domů), 
	- obecně trojrozměrné modely (zdravotnictví, technické vědy)
	- simulace
- **model** 
	- matematický popis objektu z reálného světa, nejčastěji pomocí meshe (není dokonalý)
	- nejznámější 3D model je konvice z utahu
- **modelování**
	- proces vytvoření modelu
	- tělesa jsou většinou reprezentovaný svym povrchem, ten je aproximovanej trojrozměrnou mřížkou, říká se jí mesh
	- například v blenderu se obvykle začne s kostkou a pomocí nějakých nástrojů se člověk dostane třeba ke konvici
- **scéna** - modely objektů, jejich textury, světlo, případné pozadí, kamera, ..., dohromady tvoří scénu
- **mesh** - síť polygonů která obvykle tvoří tvar daného tělesa. Šlo by těleso popsat matematickou plochou, místo jednoduchejch trojúhelníků, ale mesh vypadá dostatečně dobře, výpočty s ní jsou rychlý (ve hrách) a proces tvorby modelu/objektu je značně lepší
- **animace**
	- matematický popis pohybu objektů, zdrojů světla, kamery a dalších prvků
- **textura, materiál** - obrázek zobrazený na povrch objektu, aby nějak vypadal
- **rendering**
	- proces při kterym se vemou všechny ty trojúhelníkový meshe a jejich textury, osvětlení, kamera atd a actually se vykreslí do (2D) obrázku. V počítači je to jen složitej matematickej popis, když to chce šlověk vidět, musí renderovat. 
	- renderování je tedy proces 3D -> 2D.
	- Složitej, ale je důležitý vědět že existuje
	- zahrnuje věci jako ray-tracing, anti-aliasing, stíny, ...
	- dnes lze udělat fotorealistické 3D modely (ale dlouhý render a modelling)
- **praxe**
	- blender, malování 3D
