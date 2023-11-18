- analiza ovoga po poglavljivma
	- ![tang2011.pdf](../assets/tang2011_1694545303070_0.pdf)
	- Uvod:
		- Mehanizam koji je opisan su objavili Thornson i Thompson 1977 i Brennan 2003.
			- ((6506d5cd-aed0-47e3-9218-612d2b42e16d))
			- Oni su zakljucili da ovaj nelinearni klik mehanizam ima prednosti nad resonatnim meahnizmima ako je operativna frekvencja mnogo manja od rezonatnne ( sto je slucaj za male muve)
			- Pretpostavke:
				- 1.gubitak energije mehanizma zbog renja i podizne sile krila je predstavljena prigsuivacem (viskoznim)
				- jednacine kretanja se mogu pojednostaviti na duffingove jednacine
			- Cheng 2010 je analizirao uticaj rotacije tela na aerodinamicne sile i moment koji se dobija brzim rotacionim manevrima i pokusao da dobije koeficjente  prigusenja  na osnovu eskperimentalnih i rezultata simulacija.
			- Aerodinamika muva je pod velilim uticajem Rejnoldosovog broja fludia kroz koji lete.
				- Kada telo prolazi kroz fluid sa velikim Re, tok se razdvaja i sila trenja je skoro proporcinalana kvadratu brzine i moze se tretirati kao kvadratna sila prigusenja.
				- kada je Re mali, sila prigusenja je priblizno ekvivaletna brzini.
				- Re za najmaje inskete (20-30 mikro grama) je 10, dok je za velke insekte 5000-10000
				- Ovo nam govori da je za muve sila prigusenja negde izmedju linearne i kvadratne forme.
			- ovaj rad dalje istrazuje brenana iz 2003 i daje boolji opis modela i numericke forme.
	- Dinamicki model:
	  collapsed:: true
		- ((6506ef25-4e73-4723-80bb-75431fa0a0de))
		- Ovaj model ima 3 staticke pozicije ravnoteze  (figura 2c)
			- kada je model u polozacu ravnom , on je u labilnoj ravnotezi i bilo koji poremecaj ga tera da predje u stabilniji polozaj.
		- Potencijalna energija sistema je data formulom: [[Formule MR/ Potenijalna energija sistema]]
			- $$U = \frac{k}{4} \left( b + \sqrt{l^2 - y^2} \right)^2$$
			- k je krtuost 2 vertikalne gredice,
			- 2b je distanca izmedju njih
			- l je duzina BC ili CD
		- Povratna sila se dobija integracijom potnecijalne energije [[Formule MR/Povratna sila]]
			- $$F = 2k \left( -1 + \frac{b}{\sqrt{l^2 - y^2}} \right) y$$
		- Kada se ovo iskombinuje sa masom m i sinusnom filom boude dobijaju se jednaine kretanja [[Formule MR/Jednacine kretanja]]
			- $$m \ddot{y} + 2k \left( -1 + \frac{b}{\sqrt{l^2 - y^2}} \right) y = P \cos(\omega t)$$
		- Bezidmenzioni oblik ove jednacine se moze napisati [[Formule MR/Bezdimenzijski oblik jednacina kretanja]]
			- $$\ddot{u} + g_1 \dot{u} - au + ab \sqrt{1 - u^2} = F \cos(\Omega t)$$
			- gde je:
				- $$u = \frac{y}{l}, $$
				  $$g_1 = \frac{c_1}{m \omega_0}$$
				  $$\omega_0^2 = \frac{2k(1 - b^2)}{m}$$
				  $$b = \frac{b}{l}$$
				  $$F = \frac{P}{m l \omega_0^2}$$
				  $$t = \omega_0 t$$
				  $$O = \frac{\omega}{\omega_0}$$
				  $$a = \frac{b^2}{1 - b^2}$$
			-
			- samo je ovde diferencija ne bezdimenzijsko vreme $\tau$
			- Ako je predpostavljena  kvadtana forma jednacina kretanja je data
				- $$
				  
				  \ddot{u} + g_2 \dot{u} \left | \dot{u} \right | - au + ab \sqrt{1 - u^2} = F \cos(Ot)
				  $$
				-
	- Dinamicka analiza i simulacija:
		- Preradi ovo ponovo
		- Koristene su drugacije aproksimacije za silu, potencijalnu energiju i krutost.
			- ((65073aca-3ae6-4c95-9540-b386c0243cea))
			- za vrednost y/l manje od 0,4  aprkosimiran model je priblizan pcetnom modelu
			- kako se ova vrednost priblizva 1 ci krutost postaje beskonacna i veze su krute, ovo ima veliki uticaj na sistem
		- parametar prigusenja
			- da bi se poredili moraju da se odaberu adekvatne mere prigusenja
			- prisuenje je dato sa $$g_1 = \frac{c_1}{m \omega_0}$$
				- u kome je $$\omega_0 = \sqrt{\frac{2k(1 - b^2)}{m}}$$
				  ovo se moze zapisati kao $$g_1 = \frac{2 z_1}{\sqrt{2(1 - b^2)}}$$
				  gde $$z_1 = \frac{c_1}{2 \sqrt{mk}}$$
				   sto je konvecionalni odnos prigusenja lienarnog sistema sa jednim stepenom slobode.
				- posto let inseka idukuje veliku silu prigusenja zbog sile podizanja i  trenja,i posto je brenen zakljucio da klik mehanizam ima predost samo sa velikim silama prigusenja, prepostavlja se vrenot od ((6507411a-11d4-4b44-a54e-7dccd29ab8fe))
			- da bi
			  ((650741e0-bd20-43dd-afda-819c9dd92ed6))
				-
				-
- FORMULE: