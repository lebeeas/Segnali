### Definizione di segnale

**Ambito dei circuiti, sistemi e della trasmissione dei dati**
Un fenomeno (visivo, uditivo o altro) utilizzato per trasportare un'informazione di varia natura

**Ambito matematico**






103
## introduzione allo studio dei mezzi trasmissivi
**distorsione di ampiezza**
Una linea bifilare manifesta un comportamento selettivo in frequenza (frequency selective).
**distorsione di fase**
**ritardo temporale dipendente dalla frequenza**
I mezzi propagativi sono dispersivi in frequenza e nel tempo.
l'espressione dell’attenuazione 
![image](https://github.com/user-attachments/assets/f4c2b491-f7ee-4082-9268-1841ee4a5d13)
è valida se la distanza d fra i conduttori della linea è piccola rispetto alla lunghezza d'onda impiegata.

### cavo coassiale
costituito da:
- core: conduttore di raggio r posto al centro del cavo
- inner dielectric: un dielettrico interno che isola l'anima centrale dallo schermo
- shield: schermo conduttore esterno avente raggio R, e costituito da fili metallici intrecciati (_maglia_) o da una lamina avvolta a spirale (_treccia_)
- outer plastic sheath: guaina esterna di protezione realizzata in materiale plastico

### doppino in rame
### fibra ottica
Le fibre più semplici sono composte da un nucleo filiforme (_detto core_) realizzato in vetro coperto da un rivestimento (_detto cladding_) di materiale dielettrico diverso (materiale plastico, di solito).
Indice di rifrazione del cladding minore dell'indice di riflessione totale.
L'utilizzo della fibra comporta l'impiego di una **sorgente luminosa** per la trasmissione e di un dispositivo **fotorivelatore** per la ricezione. 

Fibra **step-index**: fibra in cui l'indice di rifrazione del nucleo (n₁) e quello del rivestimento (n₂) sono costanti e n₂ < n₁

Nel passaggio dal core al cladding si manifesta una brusca diminuzione nell'indice di rifrazione:
![image](https://github.com/user-attachments/assets/0a8a5cc9-22be-4e41-95c2-832fcaa0a79a)

lungo un fibra si manifestano i fenomeni di dipendenza dell'attenuazione dalla frequenza e della dispersione temporale. Tuttavia, l'attenuazione introdotta dalle fibre utilizzate nei sistemi reali è significativamente più piccola di quella dovuta alle linee conduttrici.

Questo risultato viene conseguito sfruttando per la trasmissione dei segnali ottici uno degli intervalli di frequenza in cui l'attenuazione è minima cioè, come si suol dire, una delle cosiddette finestre (**windows**).

## Propagazione radio
i fenomeni fisici che si manifestano nella trasmissione di segnali elettromagnetici 
nello spazio libero (_free space_) e sulla superficie terrestre.

frequenze piccole richiedono antenne enormi

Lo spettro radio è suddiviso in intervalli, detti **bande**. Inoltre, ciascuna banda è identificata da un acronimo

UHF Radio 
VHF UHF televisione

Relazione tra frequenza f e lunghezza d'onda lambda nello spazio vuoto: lambda = c/f
Attenuazione spazio libero (free space)
se l'antenna ricevente è situata nella regione di campo lontano (far field region), l'attenuazione
![image](https://github.com/user-attachments/assets/ec2e8ed7-1b86-4fa1-bbff-1d71fc0bbdf6)
introdotta dal collegamento e comunemente detta perdita di propagazione (propagation loss) o perdita di cammino (path loss), è espressa dalla relazione:
![image](https://github.com/user-attachments/assets/ddd36946-b928-4867-9b3f-dccbdf76c530)
con Gt e Gr: guadagni delle antenne ricevente e trasmettente e d la distanza tra le due antenne

L'attenuazione è proporzionale all'inverso del quadrato del prodotto fra distanza e frequenza.

![image](https://github.com/user-attachments/assets/27eb76b8-c940-4b23-97fb-cffd5bdfc46a)

### Fenomeno del multipath - cammini multipli

**MIMO massiccio (_massive MIMO_)**

l'attenuazione media che si osserva in uno spostamento radiale è direttamente proporzionale al quadrato della distanza d.

![image](https://github.com/user-attachments/assets/a3ae8b86-af0f-49a5-837c-01cb57164f52)
Si passa da d^2 a d^4

la dipendenza dell’attenuazione media (average path loss) dalla distanza d possa essere di tipo esponenziale, cioè che valga la relazione di proporzionalità:
![image](https://github.com/user-attachments/assets/4ff739ef-0378-4c50-8968-1f7cadcf711f)
dove n è un parametro non negativo noto come esponente della perdita di cammino (_path loss exponent_)

n < 2 nello scenario immaginario di un corridoio

### Flessione (bending)

### Assorbimento






