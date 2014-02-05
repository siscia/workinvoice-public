## 5 Febbraio, 2014

Il codice è buono, non è da riscrivere ma solo da modulizzare.

Abbiamo troppi pochi namespace e troppe linee di codice in un solo file, il che rende difficile il debug, già non semplice in clojure.

Più namespace rendono più ovvio la separazione di responsabilità nel codebase il che rende più semplice aggiungere ulteriori funzionalità e features.

Notare ad esempio il namesoace `wit.models.db` ma anche `wit.routes.home`.

Non ho trovato una suit di test, per quanto possa sembrare una perdita di tempo sul lungo termine porta un enorme aumento di produttività, in più essendo un sistema commerciale vogliamo essere sicuri di aver codice solido, il tempo down non costa solo in termine di immagine ma anche in meri termini monetari.

Infine non ho trovato documentazione, il codice viene spiegato solo dal codice stesso, il che rende lento per chiunque nuovo iniziare a essere produttivo.

Ho trovato abbastanza riduttiva anche la documentazione (inline) nel codice stesso.

I ordine proporei di:
- modulizzare il codice
- scrivere una test suit
- scrivere documentazione, sia in codice che come documento a se stante.

La quantità di tempo necessaria per queste operazioni non sarebbe eccessiva, ma ancora non ho famigliarità con il codice.



