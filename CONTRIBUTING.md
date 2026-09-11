# Contribuire alla Traduzione Italiana di Selah

Grazie per aiutare questa traduzione a diventare più precisa, più
chiara e più adatta all'italiano. Non serve essere studiosi: di'
ciò che vedi, porta le prove che hai, e distingui ciò che è certo
da ciò che è proposta.

## Segnalare errori o proporre correzioni

- Apri una **Issue** se il testo richiede discussione, se esistono
  più letture possibili, o se non sei sicuro di come la correzione
  toccherà l'allineamento delle parole.
- Apri una **Pull request** se l'errore e la correzione sono
  entrambi chiari.
- Per problemi del software, o questioni di sicurezza/account/
  privacy, usa [Selah Support](https://selahproject.com/support)

## Cosa includere

Libro, capitolo, versetto, il testo ebraico pertinente; il testo
attuale; il testo che proponi; la ragione del cambiamento; e le
prove da dizionari, grammatiche, contesto o fonti pubblicate.
Indica anche se l'italiano è la tua lingua madre e se leggi
l'ebraico direttamente.

## Regole per modificare i file

I file hanno la forma `<book>/<chapter>/<verse>.json`

- Se entrambi sono toccati, modifica `translation` e `gloss`
  della parte pertinente insieme.
- **Non** toccare `book`, `chapter`, `verse`, `ref`, i valori
  `surface` ebraici, né l'ordine e il numero dei token — lo
  slittamento dell'allineamento è l'errore più costoso.
- **Segui la tavola dei Nomi**: יהוה → **YHWH**; אלהים →
  **Elohim**; אדני → **Adonai**; שדי → **Shaddai**; שאול →
  **Sheol**; חסד → **chesed**. Al posto del Nome, **il Signore**,
  **l'Eterno** e **Geova** non sono accettati. (Per *elohim*
  comune, **Dio** può essere corretto — giudica token per token,
  non respingere in blocco.)
- Conserva il segno **⟨את⟩** e le aggiunte tra ⟨parentesi⟩;
  non cancellare in silenzio.
- Fuori dalle parentesi solo alfabeto latino — niente CJK,
  niente cirillico, niente arabo, niente devanagari.

## Criterio

Prima l'ebraico. Se due letture stanno entrambe in piedi, mostra
la differenza — non presentare una scelta come certezza. Non
copiare da traduzioni moderne protette da diritto d'autore.

## Lavorare con l'IA

Dichiara l'uso di modelli linguistici o traduzione automatica —
insieme alla tua verifica. Non inviare grandi quantità di testo
non controllato. Ogni parola proposta è responsabilità di chi
contribuisce.

## Licenza, registro e valutazione

Contribuendo, confermi di averne il diritto e accetti che tutto
ciò che viene incluso sarà pubblicato sotto
[CC BY-SA 4.0](LICENSE.md). La cronologia Git conserva un registro
aperto e la testimonianza. I manutentori confrontano le proposte
con l'ebraico, con le regole, con le fonti e con l'allineamento —
possono accettare, correggere insieme a te, attendere altre prove,
o respingere con la ragione. È il testo a essere valutato, non la
persona.

## Conduct

Be honest, be kind, show your evidence. Distinguish certainty from
suggestion. The maintainers weigh and decide.
