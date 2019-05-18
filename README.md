# Projekat 101

Svake godine više od 80% projekata na seminaru Računarstva propadne. Većina od tih 80% zbog grešaka koje se iz godine u godinu ponavljaju. Ovo je pokušaj da se bar neke od tih grešaka preduprede.

## Odabir projekta

Kada birate projekat, prva stvar koju gledate je da uzmete stvar koja vas zaista interesuje, nemojte se voditi *"samo da imam nešto"* i *"samo da odem na konferenciju"*  motivima jer će vam biti dosadno i naporno, a ne zabavno.  

### Šta je u stvari dobar projekat

Vaš projekat će u 99% slučajeva biti eksperimentalnog tipa, iako to možda nije očigledno na prvi pogled. Ovo zvuči čudno ljudima, jer kad se kaže da se radi eksperiment, obično se prvo pomisli na laboratoriju sa gomilom nekih aparatura i instrumenata za merenje.

Vaš eksperiment će biti program uz pomoć kojeg ćete na neki način izmeriti i proveriti vašu hipotezu, što je sledeća vrlo bitna stvar.

#### Hipoteza

Hipoteza je zapravo srž vašeg projekta. To je nekakvo tvrđenje koje pokušavate da pokažete eksperimentalnim putem (tj. programom).  

Hipoteza mora da bude zasnovana na nekim činjenicama, ne može samo "da vam padne sa neba". Potrebno je da izložite zbog čega mislite da će vaša hipoteza važiti (odnosno neće).

#### Reference

Da bi krenuli da se bavite nekim problem, prva stvar koju treba da uradite je da proverite da li se neko drugi pre vas nije bavio istim, ili možda nečim sličnim.  

Ovo je jako bitno, jer se često dešava da je ono što hoćete da uradite jako poznata stvar i da nema smisla raditi je ponovo. A može se desiti i da je problem obrađivan, samo drugačijim metodama, pa odmah dobijate način da izmerite koliko je npr. neka vaša metoda bolja / gora od postojećih. Ovakva vrsta projekta je veoma česta na računarstvu.

Druga stvar zbog kojih su reference bitne je to što morate da se pozivate na njih. To pokazuje da ste zapravo istraživali nešto o problemu, a često ćete koristiti neke metode koje su opisane u referencama ili ćete se oslanjati na neke osobine za koje je u nekom drugom radu pokazano da važe.

Dakle, da rezimiramo. Dve vrlo bitne komponente dobrog projekat su dobra hipoteza i reference koje podržavaju vašu hipotezu. Bez ta dva se ne može.

### *"Ja bih da pravim program"*

Polaznici (a posebno novi polaznici) često mešaju pravljenje programa koji radi nešto i programa koji **pokazuje** nešto novo - AKA eksperimenta.

Možda zvuči grubo, ali ako je vama neka stvar nova, ne znači da ona nije opštepoznata i da ne postoji 1001 standardni način na koji se to što hoćete radi. Tako da, ako vam padne na pamet da predložite nekakav specifičan program za projekat, obavezno proverite da li to već ne postoji (spoiler alert: verovatno postoji).

Nemojte da vas ovo obeshrabri od pravljenja takvih programa. Oni su fenomenalan način da se nauče nove stvari, samo nemaju istraživačku komponentu koja je potrebna da bi bili naučni projekat.

### *"Ja bih da radim neki ML"*

Svake godine (ili svakih par godina) u računarstvu postoji neka *state-of-the-art* tehnologija koja je postala izuzetno popularna i sasvim je normalno da želite da radite projekat koji ima veze sa njom.  

Problem sa takvim tehnologijama / pojmovima / algoritmima je to što su još uvek relativno mladi i to što je potreban veoma visok nivo razumevanja nekih veoma teških stvari (uglavnom ili iz matematike ili iz programiranja, često iz oba) da bi se u toj oblasti dao nekakav doprinos.  
Tako da, ako želite da radite na ovakvim projektima, dobro razmislite da li je realno da savladate sve što je potrebno.  

Jer, nije isto zvati `.train()` funkciju iz biblioteke i napisati tu istu funkciju da radi bolje (po kom god parametru).

### Razumevanje

Ova stvar se direktno nadovezuje na priču iznad. Ne možete da uradite projekat ako to što radite ne razumete.  

Najveći problem je što za ovo "razumevanje" nema vremena na letnjem seminaru.  
Kada dođete na letnji seminar podrazumeva se da vam je bar nekih 80% toga što radite jasno.

Ako ovo nije slučaj, često nećete imati vremena da uradite bilo šta, jer saradnici koje ste mogli da cimate pre seminara preko mejla / fejsa / nečeg levog ili nisu tu, ili će većinu vremena morati da pomažu i drugim polaznicima.

## Znanje programiranja

Ovo je još jedna od stvari na koji ljudi ne obrate dovoljno pažnje. Niko od vas ne traži da posedujete znanje programiranja kada dođete na seminar,niti vam je ono suštinski potrebno da razumete predavanja.

Ipak, ako krenemo od toga da će vaš rad biti zasnovan upravo na nekom programu pomoću kog ćete vi raditi vađe istraživanje, tada dolazimo do problema ako vi ne znate bar osnovne stvari koje se tiču programiranja.

Zašto je ovo problem? - Problem je jer ćete vi tih 10ak dana koliko ste na seminaru provesti u učenju nekog programskog jezika, i provaljivanju kako se rade jako rutinske i jako tehničke stvari, a nećete se zapravo baviti vašim problemom. Dakle, **programiranje se ne uči na letnjem seminaru.**

## Tehničke stvari

Ovaj deo će biti posvećen tehničkim aspektima projekta. Ovo je deo na kom zaglavi dosta polaznika i upravo zbog tehničkih stvari ne završi projekat.

### Planiranje projekta

Pre nego što uopšte pipnete programski kod, trebalo bi da isplanirate šta ćete i kako ćete da radite.

Za početak, bar da vidite ugrubo od kojih logičkih celina će da se sastoji vaš projekat i šta vam eventualno treba od *third-party* biblioteka.

Kad odradite ovo, tek onda treba da gledate u kom programskom jeziku je najbolje raditi projekat (obično u kom god najviše radite).

### Odabir programskog jezika

Ovo je prva stvar koju treba da uradite kada završite sa planiranjem.

Na odabir programskog jezika pre svega treba da utiče činjenica koji programski jezik znate, jer se većina projekata može uraditi manje-više u bilo kom *general-purpose* jeziku.

Druga stvar o kojoj treba da razmislite je šta će tačno vaš program raditi. Jer je su za određene stvari određeni jezici bolji.

Npr. Ako radite neku obradu teksta, dobar izbor bi bio Python, jer sasvim lepe standardne pakete koji služe baš za to, dok C nema toliko dobru podršku. Obrnuto, ako želite da se bavite nekim mikrokontrolerima čija se memorija meri u kilobajtima, C vam može biti jedina opcija.

O ovome treba da odlučite pre nego što dođete na seminar i, ako se odlučite za jezik sa kojim niste upoznati, krenete da vežbate pisanje koda. Najbolja vežba za ovakve stvari je da osmislite i napravite neki mali program koji radi neku stvar koja vam je kul, ili koja vam automatizuje nešto što vas smara da radite.

### Čuvanje rezultata

Gotovo svi polaznici nekako smetnu sa uma da su njima rezultati zapravo najvažniji deo celog projekta i generalno ne vode previše računa šta rade sa njima.

Dakle, ceo vaš fensi program uglavnom služi za to da vam u neki .txt fajl upiše neki output koji pokazuje nešto. To nešto su uglavnom neki brojevi, procenti uspešnosti, ili nešto slično...

Ako ne sačuvate ove fajlove, **vi nemate projekat.**

Takođe, ako postoji više verzija projekta koji vam daju rezultate, veoma je važno da imate sačuvane rezultate za svaku verziju.

**REZULTATE NIKAD NEMOJTE DA ČUVATE SAMO LOKALNO**

Dakle, neki Google Drive, GitHub, bilo koji cloud hosting. Niste svesni koliko je teško iskopati rezultate kada se za par nedelja vratite projektu. Ili, ako vam na random crkne hard. 

Rezultate čuvajte u lepom formatu, sa lepim imenima i kategorizovane tako da vam je, kada se za par nedelja od završetka letnjeg seminara setite da bi trebalo da nastavite da radite na projektu, bilo lako da odmah nađete rezultate i vidite šta vam koji rezultati pokazuju.

