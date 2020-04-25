Provare ora con la modalità *Simulation* per verificare il comportamento dei singoli pacchetti​.

![sim](https://github.com/daniele-moro/katacoda-scenarios/raw/master/PacketTracer/images/sim-ico.png)

1. In “Event List Fiters” con “Edit  Filters” disabilitare tutti i protocolli tranne ICMP​

2. Aggiungere ![simple_pdu](https://github.com/daniele-moro/katacoda-scenarios/raw/master/PacketTracer/images/simple_pdu.png)
una Simple PDU (è il comando PING) tra il `Router0` e il `Router2` 
(basta cliccare sui dispositivi coinvolti dallo scambio) e eseguire passo-passo gli invii di pacchetto con​ ![cap_fwd](https://github.com/daniele-moro/katacoda-scenarios/raw/master/PacketTracer/images/cap_fwd.png)

3. Eliminare le precedenti Simple PDU (“Delete” sotto “scenario 0”) e questa volta aggiungere una Simple PDU tra il `Router2` e il `Router1`, lanciare auto/capture play. ​

**​Che differenze ci sono tra le 2 esecuzioni e perché?​**
