#TSDT18 Fö 1

##Signal operationer (PPT 2)

* Skiftning - y(t) = x(t±T)
  * Man kan tänka sig att man förskjuter tids axeln inte signalen
* Spegling - y(t) = x(-t)
  * Signalen speglas i y-axeln
* Tidsskalning - y(t) = x(at)
  * Större a ger mindre signal. Även här kan man tänka sig att det
    är tidsaxeln som påverkas inte signalen.

Då man löser signal operations uppgifter så är det smidigast att 
göra det steg för steg! Blir lättare och tydligare!!

===
##Signaltyper (PPT 3)

* Tidskontinuerliga signaler x(t)
* Tidsdiskreta signaler x[n] - oftast samplad från en kontinuerlig signal. n är värdet vid sample numer n på x(t)
 * x[n] = x(t)=/t=nT/=x(nT)
* Periodisk signal x(t) är peiodisk med periodtiden T om den upprepar sig själv efter tiden T.
* Kausal signal - x(t) = 0 då x<0
* Antikausal signal - x(t) = 0då t>=0

Vi delar gärna upp signaler i två delar t<0  och t>=0 x(t) då t<0 är en antikausal signal term och då t>=0 är en kausal signal term. På kausala signaler kan vi annvända enkelsidig laplace transform!

* Energisignal - signaler som har ändlig signal energi
 * Mått på styrkan hos en signal, fouriertransformerbar 
* Effektsignal - signaler som har ändlig signaleffekt
 * T.ex periodisk signaler, man kollar då istället på effekten under en period för att få reda på signalens styrka
 
===
##Signalmodeller - de viktigaste (PPT 5)

* Enhetssteget u(t) - heavyside, unit step function u(t) = 0 då, t<0 u(t)=1 då t>=o
 * Annvänds för att definera och forma signaler till olika tids intervall.
 * Annvänds för att studera en systems stegsvar, bra vid linjära system.
* Diracimpulsen δ(t) - δ(t)=0 ,t!=0, med area 1
 * Egenskaper g(t)δ(t-T)=g(T)δ(t-T)
 * Konstant eller funktion framför en dirac kallas för diracens vikt
 * Integralen över hela talplanet av g(T)δ(t-T) = g(T) då integralen av dirac blir 1 och g(T) = 1.
 * Distrubutioner definieras genom deras verkan på snälla funktioner
 * Integrear vi över diracen får man u(t) dvs enhetssteget
* Exponentsialfunktionen e^st där s = a+jb
 * Se TATA45..
 * Väldigt skysta tillsamans med linjära transformer
*Stationär signal - periodiska signaler, cosinus, sinus, konstanter

===
##Systemegenskaper

* Linjäritet - låt signalerna xi(t) alla ha utsignalerna yi(t) och betrakta x(t)=sum(ci xi(t)) så kan utsignalen skrivas som y(t)=sum(di yi(t)) annars är det icke linjärt. 
 * Vi kan bygga en utsignal från linjärkombinatoner av insignalen. 
 * H{x(t)}=sum(H{ci xi(t)})
 * Linjäritet => homogent och additivitet
 
* Testa linjäritet
 * H{x(t)}=tx(t) 
 * y(t)=tx(t-T)
 * xi(t) => yi(t)'
 * x(t) = sum(ci xi(t))
 * y(t) = tsum(ci xi(t))
 * ci(t xi(t)) = yi(t)
 * y(t) = sum(di yi(t))
 * LINJÄRT!
 
TEST - Visa att y(t) = 5x(t) + 3 inte är linjärt

* Tidsinvarians - systemets parametrar ändras inte med tiden! Ex - Bilens fjäder ändras inte med tiden.
 * x(t) ger y(t) => x(t-T) ger y(t-T) dvs om jag väntar 5 sek med att starta systemet så beter det sig lika.
 
* Undersöka tidsinvarians
* H{x(t)}=y(t)=x(2-t) tidsivariant? (1)
 * ẍ(t)=x(t-T) (2)
 * ÿ(t)=/(1)/=ẍ(2-t)=/(2)/=x((2-t)-T)=x(2-(t+T))=/(1)/=y(t+T)!=y(t-T) => TIDSIVARIANT SYSTEM!


