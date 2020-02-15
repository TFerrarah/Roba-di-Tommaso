# Da Stonks Table
## Made by Tommaso Ferrara

## Changelog:
### 1.0.0
Initial release

## Di che si tratta?
È un semplice foglio di calcolo che ti permette di seguire l'andamento dei voti nel corso del biennio di scuola superiore.

![alt text](https://image.prntscr.com/image/FKyNF0OYRR_9G_0nj_mKtg.png "Demo")

### Abbreviazioni utilizzate
Queste vengono usate nelle celle 2D, 2F e 2H
<br>Esempio: `Variazione 1S1Q` (Letto "Variazione rispetto al primo quadrimestre del primo superiore")
<br>Ogni carattere dopo `Variazione `  ha un numero assegnato, da 0 a 3
#### Carattere 0
Numero dell'anno scolastico. Va da 1 a 2
#### Carattere 1
`S` Sta per "Superiore", il grado della scuola frequentato.
#### Carattere 2
Numero del quadrimestre. Va da 1 a 2
#### Carattere 3
`Q` Sta per "Quadrimestre". Può essere cambiato, se necessario, in `T` per Trimestre; `B` per bimestre etc.
<br>
### Stonks e Not Stonks
Il valore sarà `stonks` quando il voto sarà maggiore rispetto all'anno/quadrimestre precedente.
<br>Il valore sarà `not stonks` quando il voto sarà minore rispetto all'anno/quadrimestre precedente.
<br>Esempio: Se il voto `Chimica` del `1S1Q` è maggiore del voto della medesima materia nel `2S1Q`, il valore sarà `not stonks`
### Mega stonks e stinks
Il valore sarà `Mega stonks` se il numero di `stonks` è maggiore del numero di `not stonks` e `-` (invariato)
<br>Ciò indica che complessivamente i voti sono aumentati.
<br>Il valore sarà `Stinks` se il numero di `stonks` è minore del numero di `not stonks` e `-` (invariato)
<br>Ciò indica che complessivamente i voti si sono ridotti.
