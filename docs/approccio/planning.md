<!--__-->

# Planning

Dopo aver completato la fase di scoping e deciso il modello PMLC si procede con la fase di Planning. 
Considerando le dimensioni del progetto, i vari meeting e i documenti da produrre, sono stati dedicati sette giorni a questa fase. 

In previsione della fase di planning sono stati precedentemente identificati i documenti che sarebbero stati prodotti durante questa fase. In seguito, è stato definito un calendario dei meeting considerando le disponibilità dei membri di Mintendo coinvolti in questa fase. <br>
Ogni meeting effettuato verrà registrato in modo da poter essere consultato in seguito in caso di necessità.
<br>
<br>
Il primo documento da realizzare è il [Work Breakdown Structure](../documentazione/planningC/wbs.md) (WBS), basato sull'RBS e le User stories prodotte durante la fase di scoping. In questo documento si estendono le feature individuate nell'RBS, considerando anche gli elementi rilevanti emersi dalle User Stories, al fine da identificare task dettagliati per ogni singola fase del progetto.

Dopo aver completato il WBS si è effettuata un [Analisi MoSCoW](../documentazione/planningC/moscow.md) al fine di individuare le priorità tra le feature del progetto. Considerando che alcune feature hanno dipendenze parziali o totali tra loro si è estesa l'analisi identificandole.

Tra le possibilità per la metodologia di lavoro, per adattarsi al meglio all'approccio Agile e al modello PMLC iterativo, si è deciso di utilizzare una metodologia basata su Scrum, che ne mantiene l'idea originale e ne modifica alcuni elementi per meglio adattarsi alle necessità progetto.
La metodologia proposta prevede una scomposizione iniziale del progetto in Milestone, ognuna della durata di 2-3 mesi; all'inizio di ogni Milestone viene effettuato un meeting con i responsabili di ogni team coinvolto nel progetto. Questi stabiliscono il contenuto della Milestone sulla base dei punti funzione delle varie feature assegnandole ognuna a uno o più team. Successivamente a questo assegnamento ogni team organizza tra i membri i task individuati tramite scomposizione delle feature precedentemente effettuata durante il WBS. Ogni team lavora indipendentemente su sprint di due settimane e ha l'obiettivo di portare a termine le feature assegnate entro la conclusione della Milestone utilizzando l'approccio classico di Scrum. 

Anche in questo caso, considerando la dimensione del progetto, vi è la possibilità che alcuni task di grandi dimensioni siano ulteriormente suddivisi all'interno dei team per monitorarne il completamento in modo efficace.

Per la stima dei task si è deciso di utilizzare una tecnica ibrida tra Delphi e il Planning Poker. Questa tecnica prevede di utilizzare il Planning Poker in forma anonima corredato da un commento per motivare la stima. Il facilitatore raccoglie tutte le stime e valuta se sono unanimi almeno al 70%. 
La stima è effettuata tramite il mazzo di carte rappresentante la sequenza di Fibonacci.
L'azienda utilizza spesso questa tecnica, per cui possiede un'app proprietaria per effettuare la stima in anonimato e che permetta ai votanti, sempre in modo anonimo, di visionare le motivazioni delle stime dei partecipanti.
Si tenta di raggiunge il consenso entro 3 turni, se ciò non avviene il facilitatore decide se procedere con ulteriori turni o effettuare una media delle valutazioni proposte.

Le stime sono effettuate durante la produzione del [Product backlog](../documentazione/planningC/product_backlog.md). In questo documento sono indicate le feature e la loro scomposizione in task con corrispettiva stima in punti funzione. Viene inoltre indicato a quali ambiti afferisce ogni feature. 

In questa fase viene anche redatto il [cash flow](../documentazione/planningC/cash_flow.md) dove vengono indicate tutte le entrate e le uscite di denaro durante il corso del progetto.

Per ogni Milestone viene effettuato fin da subito un [Project Network Diagram e il relativo Gantt](../documentazione/planningC/gantt.md) per verificare che ogni Milestone sia completabile nei tempi previsti e individuare task completabili in parallelo.


