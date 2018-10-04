# MC-OL48A31
Schema quadro elettrico per ascensore serie `mcpx`. Impianto oleodinamico con emergenza 48VDC 3 gestione emendamento A3.

## Licenza
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licenza Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Quest'opera è distribuita con Licenza <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribuzione - Condividi allo stesso modo 4.0 Internazionale</a>.

Fatta eccezione del logo

![logo](./assets/images/eca-logo.png)

e del nome `Eca di Belardi Roberto`.

Copyright (C) 2018  Eca di Belardi Roberto.

### Scheda controllo
MCPX2015-SMD - PER16B-SMD
###### Firmware
[P](https://docs.ecaq.in/it/info/mcpx-board-manual-p).

### Tipo impianto
Oleodinamico.

### Manovra
Universale.

### Collegamento vano / cabina
| Vano     | Cabina     |
| :------------- | :------------- |
| parallelo | parallelo |

### Operatore porte
* manuale
* automatico 48VDC

### Avviamento / controllo motore
* diretto
* stella-triangolo
* soft-starter (SMS-Start)

### Potenza massima motore

##### Avviamento diretto
| Taglia | Potenza |
| :------------- | :------------- |
| S20 | 8CV-230VAC/15CV-400VAC |
| S30 | 10CV-230VAC/17CV-400VAC |

#### Avviamento stella-triangolo
| Taglia | Potenza |
| :------------- | :------------- |
| S40 | 14CV-230VAC/22CV-400VA |
| S50 | 17CV-230VAC/28CV-400VAC |

#### Avviamento soft-starter
| Taglia | Potenza |
| :------------- | :------------- |
| S40 | 10CV-230VAC/20CV-400VAC |
| S50 | 13CV-230VAC/25CV-400VAC |


### Allarme
* 12VDC
* legge 13

### Emergenza
Emergenza con riapertura porte tramite gruppo batterie 48VDC.

### Emendamento A3
Gestione con doppia valvola discesa controllata da boxA3 (SMS).
