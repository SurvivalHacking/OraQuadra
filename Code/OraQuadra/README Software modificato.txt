Modifiche del software OraQuadra_my rispetto al codice OraQaudra_V12:
1) solo un pulsante.
2) aggiunta fotoresistore per regolazione luminosità automatica.
3) aggiunti di nuovi colori.
4) cambio veloce tra ora legale/solare.
5) aggiunto test di verifica funzionamento di tutti i led della matrice al boot.

Funzionamento:
1) con un clic veloce del pulsante si cambia il colore e modalità grafica della matrice (Preset).
2) luminosità varia automaticamente nel range 1-50.
Per scelta la matrice non si spegne mai, rimossa la funzione di regolazione secondo fasce orarie.
Valore massimo 50 per limitare assorbimento.
4) con un clic prolungato (5 secondi) l'ora avanza di +1h. Al secondo clic prolungato l'ora arretra di -2h.
Questo permette di poter effettuare il cambio tra ora legale/solare.
5) all'avvio viene eseguito un veloce ciclo di lampeggio RGBW per verificare che non vi siano led bruciati.

NOTA:
Si fa presente, per una futura versione, che è possibile leggere dal modulo RTC anche la temperatura ambiente tramite la funzione rtc.getTemperature();

	
