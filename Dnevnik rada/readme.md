TO DO LIST: https://docs.google.com/document/d/1Cj1unGtLQEU8l7k70o4UbekOnB9Lpk5HJaf42gSUOio/edit?usp=sharing

<br><br>**DNEVNIK RADA**
## zimski seminar
<br>_subota, 1. jul 2023._
- sastavila sam kolo na protobordu
- završila sa instalacijom TLSPICE
- rešila problem napajanja
<br>_nedelja, 2. jul 2023._
- uz pomoć stručnih saradnika, naučila sam kako se rešavanju kola pomoću diferencijalnih jednačina i pomoću Laplasovog pravila. Takođe, upoznala sam se sa pojmom jednačina stanja kola i onsnovama rešavanja električnih kola. 
- dva puta sam konstrusala Čua kolo na proto bordu. Ni jednom nisam uspela da uočim haos na osciloskopu. Nakon što sam se uverila da greška nije do spajanja komponenata, odlučila sam da napravim simulaciju u LTspice-u (to je simulacija sa integrisanim kolom TL082). Tamo, takođe nisam imala pokazatelje haosa. 
<br>_ponedeljak, 3. jul 2023._
- sastavila sam kolo na ploči i zalemila komponente prateći šemu.
- Kada radim sa oscilatornim kolom, moguća je oscilacija napona koja nije poželjna kada pokušavam da pobudim haos u kolu, a javlja se pri upotrebi operacionih pojačavača. Zbog toga, dodajem dva Bypass kondenzatora na Vcc+ i  Vcc- pinove TL082. (primer za pozitivan pin: jedan kraj kondenzatora vežem za COM, a drugi za pin 8, odnosno Vcc+)
- Kako ne postoje indukrivnosti sa vrednošću od 18mH, moja prvobitna ideja bila je da vežem redno tri induktivnosti: 15, 1.5 i 1.5. Kolo sa tim stvara haos, ali to nije pravilan način za vezivanje induktivnosti. Umesto njih, koristila sam drugačije kolo koje je menjalo te induktivnosti. Haos se stvara u oba slučaja.
- Ukoliko mi ne radi, treba proveriti sledeće: da li je dobro povezano? (obavezn proveriti šemu!!) da li su COM i +9 i -9 na dobrim mestima? da li postoje kratki spojevi? mogu pomoću ultimetra gledati napon koji se nalaz na pinovima integrisanog kola, ne treba da bude čist jer, ako je dobro povezano i ako je inttegrisano kolo ispravno (ako ga nisam spalila ;)), onda mora da postoji neki gubiak 1-2V.
- Kada sam uspela da dovedem kolo u mood da osciluje i da je u rezonanciji, treba menjati vrednosti na potenciometrima dok ne uočim haos.
<br>_sreda, 4. jul 2023._
- Istaživala sam primenu Čua oscilatora u nauci i naišla sam članak o tome kako se sinhronizovani haos u Čua oscilatoru može poistovetiti sa moždanim aktivnostima tokom epileptičnog napada. Plan mi je da dana istražim tu metodologiju.
- Ognjen mi je dao uputstvo za skidanje naučnih radova koji ne mogu da se skinu direktno sa neta. Pomoću ova dva sajta: https://sci-hub.se/ i https://libgen.is/
- Simulacija u LTSpicue-u mi je proradila. Za sad, kolo samo osciluje. Greška zbog koje nije oscilovalo je jer sam imala pogrešan model operacionog pojačivača i pogrešno su bili polarizovani.
<br>_petak, 5. jul 2023._
- Napravila sam simulaciju za treću šemu kola. 
<br>_četvrtak, 6. jul 2023._
- Konstruisala sam treću šemu kola, koja sadrži jedan pperacioni pojačavač i diode. U njoj sam uspela da pobudim haos, koji sam uočila na analognom osciloskopu.
<br>
### period između zimskog i letnjeg seminara

Samostalno istraživanje: 
Pokazatelji haosa u Čua kolu: 
