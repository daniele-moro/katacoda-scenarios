A questo punto siamo pronti a configurare gli indirizzi IP che si troveranno in due reti distinte:

* Collegamento Fiber Ethernet (Router 2-Router 0)​: 10.0.0.0/8, mask 255.0.0.0 ​
* Collegamento Seriale (Router 2-Router 0)​: 11.0.0.0/8, mask  255.0.0.0 (Settare il clock)​

![Topo4-1](https://github.com/daniele-moro/katacoda-scenarios/raw/master/PacketTracer/images/es4.1.png)

Andiamo nel pannello *Config* di ogni router ed effettuiamo la configurazione delle interfacce.
In figura un esempio di configurazione dell'interfaccia Seriale del `Router0`.

> N.B.: configurare il clock dell'interfaccia DCE della connessione seriale

![indirizzi](https://github.com/daniele-moro/katacoda-scenarios/raw/master/PacketTracer/images/indirizzi.png)
