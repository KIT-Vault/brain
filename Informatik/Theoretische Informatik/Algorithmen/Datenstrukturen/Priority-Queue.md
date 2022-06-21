---
aliases: []
---

# Priority-Queue #card
Wird klassischerweise mit einem [[Binary-Heap]] implementiert
## Methoden
- push $(v, 7)$ : füge $v$ mit Priorität 7 ein
- popMin(): extrahiere Element mit kleinster Priorität
- decPrio $(v, 4)$ : verkleinere Priorität von $v$ auf 4
## Laufzeit
### [[Binary-Heap]]
- popMin: $\Theta(\log n)$
- push: $\Theta(\log n)$
- decPrio: $\Theta(\log n)$
### [[Fibonacci-Heap]]
- popMin: $\Theta(\log n)$
- push: $\Theta(1)$
- decPrio: $\Theta(1)$
^c-gPBTtpc3UQ
---
**Tags**: 