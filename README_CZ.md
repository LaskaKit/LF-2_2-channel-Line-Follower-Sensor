## LF 2.2 channel Line Follower Sensor
### Co to je?
LF 2.2 channel Line Follower Sensor je modul se dvěma optickými závorami, které dohromady pár sloužící k detekci čáry a mezery pro roboty určené ke sledování čáry.

![LF 2.2 channel Line Follower Sensor](https://github.com/LaskaKit/LF-2_2-channel-Line-Follower-Sensor/blob/main/img/LF-2_2-channel-Line-Follower-Sensor.gif)

### Proč?
Roboti sledující čáru patří mezi základní projekty nadšenců, kteří si chtějí postavit vlastní robot. 
Existuje mnoho soutěží, kde se můžete zúčastnit právě v této dovednosti robota. 

Velký důraz na kvalitu robota patří jeho čidlům, zvláště u nekvalitních modulů/čidel robotů sledující čáru se objevují falešné detekce čáry nebo mezery a na základě těchto falešných detekcí se může “robot zbláznit”, protože neví, kde se zrovna nachází. 
Takže je třeba klást velký důraz na kvalitu čidel. K tomu právě slouží modul LF 2.2 channel Line Follower Sensor.

LF 2.2 channel Line Follower Sensor obsahuje dvě optické závory a ke každé náleží vlastní Schmittův obvod, který zajistí indikaci čáry/mezery vždy za stejných podmínek. 

Jak můžete vidět na videu, ke každé optické závoře náleží jak výstup do vaší řídící desky, tak i LED umístěná přímo na desce.

### Jak?
Optická závora detekuje odražené světlo - skládá se tedy z vysílače - IR LED a přijímače - fototranzistor. Pokud je v cestě, přes odraz, tmavý podklad, vysílané světlo se neodrazí do fototranzistoru a příslušná LED nesvítí - znamená to, že optická závora se nachází nad sledovanou čarou. Pokud se odrazí, je aktivován výstup (logická “1”) a rozsvítí se příslušná LED. 
