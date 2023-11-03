- [[Osnove]]
	- Tekst uvodi metodologiju za analizu statičkih struktura koristeći osnovne fizike i principe strukturalne analize. Ova metoda modeluje članove strukture kao opruge, sastavljene na način koji oponaša stvarni strukturalni sistem. Tako se može izračunati ukupna efektivna krutost strukture i odrediti njena deformacija pod primenjenim opterećenjima. 
	  id:: 653eb897-6333-4984-a225-900f7c57ba81
	- Iako je ovaj pristup istaknut u nekim naprednim tekstovima o strukturalnoj dinamici, nije često korišćen u osnovnim kursima strukturalne analize ili dizajna.. Dokument sugeriše da korišćenje ovog predstavljanja oprugom može ponuditi brzu i efikasnu analizu razmjerno složenih građevinskih struktura, i može služiti kao sredstvo za proveru tradicionalnih inženjerskih proračuna.
	- [[Kod]]
		- Sila osnovna formula
			- ```python
			  def calculate_Force(k,delta):
			      return k*delta
			  ```
		-
	- [[jednacina]]
		- $F=k\Delta$
		- F je zatezna ili sabojna sila opruge
		- k je krutoca opruge
		- $\Delta$ je duzinska deformacija opruge
		- ((653ec537-ebcf-4af0-acbe-e0d896833bd5))
		-
	- Figura 1b je ista opruga opterećena na zatezanje gde je Li duze od L0. Ako bi bila u sabijajnu Li bi bilo krace od L0.
	- Kako se ovo odnosi na proste strukture
		- najjednostavnija struktura je sipka koja nosi neku težinu (pr nosač cevi)
		- ((653ec526-7423-4df0-9e1b-bec7e4a7a32d))
		- ako sila deluje na kraju stapa, aksijalna deformacija se moze izračunati preko poznate formule
		- [[jednacina]]
			- $$\Delta=\frac{F L}{E A}$$
			- E je jungov modu elastičnosti
			- A je poprečni presek
			- L je duzina (neopterecena)
			- ako preuredimo jednačinu u formu hookovog zakona
			- $$F=\frac{E A}{L}\Delta$$
			- tako da je ekvivalentna krutost
			- $$k_{eq}=\frac{E A}{L}$$
		- Ovaj nosac mozemo posmatrati kao oprugu