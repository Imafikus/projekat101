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

Možda zvuči grubo, ali ako je vama neka stvar nova, ne znači da ona nije opštepoznata i da ne postoji 1001 standardni način na koji se to što hoćete radi. Tako da, ako vam padne na pamet da predložite nekakav specifičan program za projekat, obavezno proverite da li to već postoji (spoiler alert: verovatno postoji).

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

Ovo je još jedna od stvari na koji ljudi ne obrate dovoljno pažnje. Niko od vas ne traži da posedujete znanje programiranja kada dođete na seminar, niti vam je ono suštinski potrebno da razumete predavanja.

Ipak, ako krenemo od toga da će vaš rad biti zasnovan upravo na nekom programu pomoću kog ćete vi raditi vađe istraživanje, tada dolazimo do problema ako vi ne znate bar osnovne stvari koje se tiču programiranja.

Zašto je ovo problem? - Problem je jer ćete vi tih 10ak dana koliko ste na seminaru provesti u učenju nekog programskog jezika, i provaljivanju kako se rade jako rutinske i jako tehničke stvari, a nećete se zapravo baviti vašim problemom. Dakle, **programiranje se ne uči na letnjem seminaru.**

Nemojte ovo da shvatite kao neku vrstu pretnje, naravno da se od vas ne očekuje da ćete znati sve i da će sve ići glatko. Saradnici će biti tu da vam pomognu gde god da zapnete.

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

Npr. Ako radite neku obradu teksta, dobar izbor bi bio Python, jer ima sasvim lepe standardne pakete koji služe baš za to, dok C nema toliko dobru podršku. Obrnuto, ako želite da se bavite nekim mikrokontrolerima čija se memorija meri u kilobajtima, C vam može biti jedina opcija.

O ovome treba da odlučite pre nego što dođete na seminar i, ako se odlučite za jezik sa kojim niste upoznati, krenete da vežbate pisanje koda. Najbolja vežba za ovakve stvari je da osmislite i napravite neki mali program koji radi neku stvar koja vam je kul, ili koji vam automatizuje nešto što vas smara da radite.

### Čuvanje rezultata

Gotovo svi polaznici nekako smetnu sa uma da su njima rezultati zapravo najvažniji deo celog projekta i generalno ne vode previše računa šta rade sa njima.

Dakle, ceo vaš fensi program uglavnom služi za to da vam u neki .txt fajl upiše neki output koji pokazuje nešto. To nešto su uglavnom neki brojevi, procenti uspešnosti, ili nešto slično...

Ako ne sačuvate ove fajlove, **vi nemate projekat.**

Takođe, ako postoji više verzija projekta koji vam daju rezultate, veoma je važno da imate sačuvane rezultate za svaku verziju.

**REZULTATE NIKAD NEMOJTE DA ČUVATE SAMO LOKALNO**

Dakle, neki Google Drive, GitHub, bilo koji cloud hosting. Niste svesni koliko je teško iskopati rezultate kada se za par nedelja vratite projektu. Ili, ako vam na random crkne hard. 

Rezultate čuvajte u lepom formatu, sa lepim imenima i kategorizovane tako da vam je, kada se za par nedelja od završetka letnjeg seminara setite da bi trebalo da nastavite da radite na projektu, bilo lako da odmah nađete rezultate i vidite šta vam koji rezultati pokazuju.

Još jedna stvar zbog koje je bitna kategorizacija je da bi bili sigurni koji rezultati su oni koje ćete konačno prikazati u radu. Projekat koji nema validne rezultate nije projekat.

Nikako nemojte čuvati samo grafike, ili slike, ili šta god. **Uvek čuvajte sirove podatke**. Grafici koje vi nacrtate i stavite u vašu verziju rada koju šaljete na reviziju se uglavnom ne koriste kada je vreme da se rad spremi u "spakuje" u petničku svesku, nego će vam se skoro uvek samo tražiti sirovi podaci. Ovo se radi kako bi se napravili grafici boljeg kvaliteta od onih koje ste vi stavili (uglavnom je potreban veći *dpi* da bi to izgledalo lepo kad se odštampa).  

Druga problematična stvar kod nečuvanja sirovih podataka je što onda dolazite u situaciju da neko vama treba da veruje na reč da je vama slika koju ste stavili merodavna i da zaista prikazuje dobijeni rezultat.

## Programiranje - Tricks & Tips

Kako je programiranje ono što vama suštinski uzima najveći deo vremena kod izrade projekta, ovaj deo će biti posvećen tome da vam pokaže i ukaže neke stvari koje će vaš programerski život učiniti dosta srećnijim.

### Source Control

Prva stvar o kojoj pričamo je *Source Control*. Verujem da su neki od vas već krenuli da uzdišu, ali ovo je jedan od krucijalnih alata koji se koristi svuda, pa ne postoji neki racionalan razlog da ga i vi ne koristite. Ako planirate da se profesionalno bavite bilo čim što ima veze sa programiranjem, **podrazumevaće** se da znate ovo.

#### Kako radi source control

Na *source control* možete da gledate kao na alat koji bukvalno pravi *snapshot* koda vašeg programa. Svaki ovaj *snapshot* se čuva, i svakom možete da se vratite.  
Još jedna bitna stvar, ti *snapshotovi* se čuvaju i kod vas i na nekom serveru, tako da vi automatski dobijate *backup* vašeg programa i mogućnost da isti taj program svučete na bilo koji računar koji ima instaliran *source control*.

Možda niste svesni, ali gomila vas već koristi "primitivni" *source control* koji podrazumeva da vi vaš kod snimite na neki fleš, ili pošaljete sebi na mejl ili kao poruku na fejsu / vocapu / nečem trećem. Ovo radite upravo jer želite da sačuvate nekakve verzije vašeg programa.

Source control samo olakšava ovo. Takođe, još jedna bitna prednost je što možete čuvati i sve dobijene rezultate, i čak i da se desi da zagubite starije rezultate ili vam se zapali komp recimo, uvek možete da pristupite svim *commitovanim* verzijama.

#### Git

Najpoznatiji i najkorišćeniji *source control*. Sigurno ste čuli za [GitHub](https://github.com/) ili [GitLab](https://github.com/). Postoji još gomila drugih koji ispod haube koriste git. Takođe, najčešće korišćen u industriji.

Druga bitna stvar, koja uopšte nema veze sa projektom. Ako budete tražili posao (posebno prvi posao) profil na nekom od ovakvih sajtova izuzetno znači, jer to pokazuje da ste vi nešto radili i činjenica da li imate ili nemate git repoe koje neko može da pogleda će da pravi razliku između toga da li će vas zvati ili ne.

#### Korisni linkovi

- [Introduction to Git](https://www.youtube.com/watch?v=OqmSzXDrJBk)
- [Understanding Git](https://hackernoon.com/understanding-git-fcffd87c15a3)
- [Git Cheatsheet](https://www.git-tower.com/blog/git-cheat-sheet)

### Pisanje koda

Stvari o kojima ćemo pričati ovde vas skoro sigurno smaraju, i gomila vas misli da su gubljenje vremena. Ja ću da pokušam da vam objasnim zašto to ipak nije tačno.

Dakle, rešili ste šta radite za projekat, imate plan, i došlo je vreme za pisanje koda. Baš zbog ovog pisanja koda propadne lep broj projekata. Ispod su kao mala poglavlja date neke česte greške koje se dešavaju u ovom procesu.

#### Imenovanje promenljivih

Koliko god vama ovo banalno zvučalo, dobro imenovanje unutar koda je jedna od najvažnijih stvari koje treba da naučite.  

Zašto je ovo bitno, i zašto vas smaramo oko ovoga? - Bitno je jer ćete vi sigurno u nekom trenutku posle pisanja ključnih delova koda morati da se vratite istom tom kodu (iz kog god razloga).

Takođe, verovatno će vam u nekom trenutku trebati pomooć oko debagovanja, a tu će vam pomagati ljudi koji verovatno prvi put u životu prolaze detaljno kroz vaš kod. E, u ovakvim slučajevima dolazimo do zanimljivih situacija.

Razlika između:

```
cc = s.c i currentCoef = simulation.coef

ili:

d(): i drawScreen():

````

**je ogromna**

Prva stvar koju eliminišete dobrim imenovanjem je razmišljanje potrebno da se skonta šta piše u liniji koda. Druga stvar, koju dobijate, je beskonačno puta lakše debagovanje i promene koda, jer vam bukvalno piše šta se dešava.

Pretpostavimo sledeću situaciju: Bili ste na letnjem seminaru, odmah posle ste otišli na letovanje, i treba da doradite par stvari kada dođete. Dakle, 10 dana ne vidite komp. Razmislite kada će vam biti lakše da se "vratite" u kod, kada imate deskriptivna imena, ili kada imate 1 ili 2 slova na sve strane.

Takođe, nečitljiv kod vam niko neće debagovati, jer je samo potrebno previše vremena da bi se uopšte shvatilo šta se događa u kodu, da bi tek onda moglo i nešto da se izdebaguje.