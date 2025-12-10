Progetto sviluppato per l'esame di codifica di testi, corso del terzo anno di Informatica Umanistica dell'Università di Pisa, svolto insieme a Sarah Del Buono.
Il progetto consiste nella codifica di alcuni articoli tratti dalla rivista La Rassegna Settimanale.
All’interno della cartella del progetto è stata inserita la directory xerces-2_12_2-xml-schema-1.1
contenente i file della libreria Xerces-J.
Dopo essere entrati nella cartella del progetto, il file è stato validato con il comando (per windows):
java -cp ".;xerces-2_12_2-xml-schema-1.1\*" dom.Counter -v "codifica.xml"
Questo ha permesso di verificare la correttezza del documento XML tramite Xerces-J.

