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
 * 

