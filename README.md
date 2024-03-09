# Konvolúciós gépi tanulás az önvezető autók adatfeldolgozásában

## Téma Címe: Konvolúciós gépi tanulás az önvezető autók adatfeldolgozásában

---

## Feladat

A félév során a feladatom egy képfelismerő alkalmazás fejlesztése volt, konvolúciós neurális hálózatok (CNN) segítségével. Ezen belül, specifikusan egy olyan CNN modell kialakítása volt a cél, mely képes a kiválasztott objektum pontos felismerésére és lokalizálására a képeken. A kiválasztott objektum egy általam tetszőlegesen választható objektum, jelen esetben a tanító adatokban megtalálható oszlopokra esett a választás. A modell lehetett saját architektúrájú és lehetett egy előre tanított modell, amely modell tovább tanításával érjük el a kívánt eredményt.

---

## Laboratóriumi munka környezetének ismertetése

### Bevezető

A projekt, amelynek keretében dolgoztunk, a Federated Learning technológiát fejlesztett önvezető autók működéséhez. A Federated Learning alapelve, hogy a tanulási folyamat elosztottan, az összes részt vevő eszközön párhuzamosan zajlik. Minden autóban egy különálló modell tanul, amely csak az általa megtanult összefoglaló információkat - azaz a súlyokat - továbbítja a központi modellnek. Ez a módszer kiemelkedően magas szintű adatvédelmet biztosít, valamint jól skálázható, így nagyszámú eszközt lehet bevonni a tanulási és modellképzési folyamatokba. A projekt legfőbb célja a Federated Learning elveinek alkalmazása az önvezető autók objektum felismerési képességének fejlesztésére.

---

### Elméleti összefoglaló

A projektünkben alkalmazott technológiák közül talán a legfontosabb a konvolúciós neurális hálózat (CNN), melyet az objektum felismerés feladatára használtunk. A konvolúciós neurális hálózatok a gépi tanulásnak egy speciális, képfelismerésre optimalizált ága. Képesek a képen található összetett mintázatok felismerésére, lokalizálására és osztályozására, így kiválóan alkalmazhatóak önvezető autók számára, ahol a környezetben lévő objektumok azonosítása és helyzetük meghatározása elengedhetetlen.

---

