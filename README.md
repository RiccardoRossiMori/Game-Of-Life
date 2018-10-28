# Game Of Life
 Si è realizzato un gioco simile al Gioco della vita.

Il gioco si svolge su una griglia bidimensionale in cui vi sono animali di due specie differenti e alimenti di un solo tipo. Una cella può contenere un solo animale o un solo alimento.

Lo stato del gioco, dato dalla distribuzione degli animali e degli alimenti sulla griglia, evolve con il tempo.

Le due specie animali si differenziano per il meccanismo riproduttivo: o si accoppiano o si clonano.

Le regole che gli animali rispettano sono le seguenti:

    Si spostano di una casella per volta.
    Quando si spostano su una cella con un alimento, lo mangiano e aumentano la loro capacità di spostarsi (cioè la loro vita) di due unità. Gli alimenti si trovano nella griglia in posizioni casuali e con una densità di al più 50% della griglia.
    Alla nascita hanno una aspettativa di vita di 10 spostamenti.
    Una unità di alimentazione aggiunge 2 spostamenti alla vita dell'animale.
    Un animale in grado di clonarsi, se ha più di 20 spostamenti si clona e la sua vita si riduce a 10 spostamenti.
    Un animale in grado di accopiarsi, se ha più di 5 spostamenti e meno di 20, si può accoppiare con un altro individuo vicino (cella adiacente).
    Se un animale ha 0 spostamenti muore.

Il programma, distribuisce un certo numero (richiesti all'utente) di individui e alimenti casualmente sulla griglia, produce il numero e il tipo degli individui dopo un certo numero di spostamenti.
Oltre a queste indicazioni generali assegnate dai professori sono state inserite ulteriori regole e linee guida:
    
     I mammiferi che muoiono per la troppa distanza percorsa si tramutano in cibo, ma se mangiati aumentano la capacità di spostamento di 5 unità anziché di due.
     Si è voluto dare un senso agli spostamenti degli animali cercando di equilibrare la situazione (I mammiferi sarebbero molto più attivi "sessualmente").
     I mammiferi cercano i propri simili anziché il cibo, i cloni (o "amebe") vanno in cerca di cibo.
     Gli animali non possono rimanere fermi per più di 5 turni, in tal caso si spostano verso una direzione randomica.
Il Progetto è stato realizzato nel Febbraio del 2018 da Riccardo Rossi Mori (proprietario di questo account) e Lucia Passeri.

P.S.: Posto questo progetto solo ora, dunque sono abbastanza sicuro di dimenticare qualche linea guida da noi aggiunta.
