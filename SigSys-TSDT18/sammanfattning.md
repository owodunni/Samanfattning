#TSDT18 Sammanfattning

* Kausalt - Nollskiljt först vid t=0
* Externt stabilt - Utifrån är systemet stabilt sett
  * Imaginär axeln måste ligga i konvergensområdet. Därför kan kausala och icke kausala system ha poler i olika halvplan, utan att systemet blir externt instabilt.
* 
* Testa linjäritet
 * H{x(t)}=tx(t) 
 * y(t)=tx(t-T)
 * xi(t) => yi(t)'
 * x(t) = sum(ci xi(t))
 * y(t) = tsum(ci xi(t))
 * ci(t xi(t)) = yi(t)
 * y(t) = sum(di yi(t))
 * LINJÄRT!
 

* Undersöka tidsinvarians
 * H{x(t)}=y(t)=x(2-t) tidsivariant? (1)
 * ẍ(t)=x(t-T) (2)
 * ÿ(t)=/(1)/=ẍ(2-t)=/(2)/=x((2-t)-T)=x(2-(t+T))=/(1)/=y(t+T)!=y(t-T) => TIDSIVARIANT SYSTEM!



##Laplace transformer

* Vid Laplace transformer måste man ha koll på konvergens område och vid transformering så måste man se till att man tar  hänsyn till polernas placering vid vall av transform.

* Då en trignometrisk funktion x(t) = cos(Wt) faltas med ett sysem h(t) så blir y(t)=|h(2j)|cos(wt+arg(h(j2))

## System funktioner

* För att bestämma förstärkningen som en system funktion ger i en punkt (P) kan man annvända sig av följande,
 * |H(S)|<sub>s=p</sub>=b<sub>0</sub>(produkten av avståndet av nollställen till p)/(produkten av avståndet av poler till p)
* Alla riktiga system funktioner har komplex konjugerade poler om polerna är skiljda från realaxeln.
* 

## Sampling

* B - bandbrädd
* f<sub>s</sub> - samplingfrekvens - f<sub>s</sub>=2B
* T - Avstånd mellan sampels i tid
* T<sub>0</sub> - Avståndet i tid innan den samplade signalen upprepar sig själv
* N<sub>0</sub> - Antal samples per period - N<sub>0</sub>=T<sub>0</sub>/T
* N<sub>0</sub>' - Antal samples per period - N<sub>0</sub>'=f<sub>s</sub>/f<sub>0</sub>


* Olika samplings metoder
 * 
 

