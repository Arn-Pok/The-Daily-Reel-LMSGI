# Registre d'ús d'IA — Itinerari B

Aquest document recull l'ús d'eines d'IA durant el desenvolupament de **The Daily Reel**. S'ha redactat a partir de la documentació i els fitxers presents en el projecte lliurat.

> **Nota sobre la traçabilitat:** els fitxers del projecte indiquen que s'ha utilitzat IA com a suport per revisar la semàntica de la taula de l'historial i que es van acceptar recomanacions sobre `scope="row"` i `scope="col"`. No s'hi conserven les converses originals de GitHub Copilot ni un historial de terminal. Per tant, no és possible reproduir literalment els prompts ni atribuir a Copilot ordres concretes que no consten als materials. Els camps marcats com a «no documentat» s'han de completar només si es disposa de l'historial real.

## 1. Eina utilitzada

- **Eina indicada a la documentació:** IA com a suport de revisió.
- **Eina concreta esmentada en la tasca:** GitHub Copilot.
- **Ús que es pot acreditar amb els fitxers:** suport per revisar la semàntica de la taula de l'historial de pel·lícules.
- **Prompts literals de Copilot:** no documentats als fitxers lliurats.

## 2. Prompts i resultats documentats

| Àmbit | Prompt literal utilitzat | Suggeriment o resultat documentat | Decisió |
|---|---|---|---|
| Taula de l'historial | No consta el text literal del prompt. | La documentació indica que la IA va recomanar utilitzar `scope="col"` per als encapçalaments de columna i `scope="row"` per identificar la pel·lícula de cada fila. | Recomanació acceptada, perquè associa semànticament les capçaleres amb les dades corresponents. |

La decisió també queda descrita a `tabla decisiones.md` i `reflexion_critica.md`.

## 3. Comandes suggerides per Copilot

Als fitxers lliurats no hi ha cap registre de comandes de terminal suggerides per GitHub Copilot ni cap historial de comandes executades.

| Comanda suggerida | Finalitat | Comprovació abans d'executar-la |
|---|---|---|
| No documentada | No es pot determinar sense l'historial de Copilot. | No consta cap comprovació associada a una ordre concreta. No s'ha d'afegir una ordre suposada com si s'haguera suggerit o executat. |

Per completar aquest apartat, cal recuperar la conversa real de Copilot i copiar-hi cada ordre suggerida. Per a cada ordre, anota què fa, quins fitxers pot modificar i si pot instal·lar, eliminar o descarregar elements abans d'executar-la.

## 4. Comprovacions que cal registrar

La documentació del projecte assenyala que la validació W3C, la navegació amb teclat i la prova amb lector de pantalla s'han de comprovar en el navegador i documentar amb evidències. No afirma que aquestes proves s'hagen completat, per la qual cosa no es marquen com a superades.

Abans d'executar qualsevol ordre suggerida per una IA, registra les comprovacions reals següents:

1. Llegir l'ordre completa i entendre'n cada part.
2. Comprovar que s'executa dins de la carpeta correcta del projecte.
3. Identificar els fitxers que pot crear, modificar o eliminar.
4. Revisar si necessita permisos, connexió a Internet o instal·la dependències.
5. Fer una còpia o comprovar que els canvis actuals estan guardats al control de versions.
6. Executar-la només si el resultat esperat és clar i adequat per a la tasca.
7. Revisar el resultat i les diferències dels fitxers després de l'execució.

Aquestes són pautes per a futures comprovacions; no s'han de presentar com a accions ja realitzades si no es van fer.

## 5. Verificació del codi relacionat

Les decisions documentades per a la taula inclouen:

- `scope="col"` per als encapçalaments de columna.
- `scope="row"` per a la capçalera que identifica cada pel·lícula.
- Ús de cel·les `td` per a les dades.
- Ús de `caption` per descriure la taula i `time` per representar dates, segons el document de decisions.
- Revisió de la navegació amb teclat i del focus visible.

**Estat de les proves:** pendents de confirmar en el navegador i amb les eines de validació. La reflexió del projecte indica expressament que la validació W3C, la prova amb lector de pantalla i la navegació amb teclat s'han de comprovar i registrar amb evidències reals.

## 6. Valoració de l'ús de la IA

La IA s'ha utilitzat com a suport, no com a substitut de la revisió pròpia. La recomanació semàntica documentada s'ha acceptat perquè concorda amb la funció de les capçaleres de fila i de columna. El codi final i el comportament de la pàgina s'han de revisar i validar independentment.

## 7. Informació pendent per tancar el registre

- [ ] Afegir els prompts literals copiats de l'historial de GitHub Copilot.
- [ ] Afegir les comandes exactes que Copilot va suggerir, o indicar «cap» si no en va suggerir.
- [ ] Escriure la comprovació real feta abans d'executar cada comanda.
- [ ] Indicar quines proves de validació i accessibilitat s'han executat i adjuntar-ne les evidències.

**Criteri d'honestedat:** no inventar prompts, ordres, resultats ni proves. Si no es va utilitzar cap ordre de terminal, deixar-ho indicat explícitament.
