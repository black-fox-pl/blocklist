#### Osobiste filtry do blokowania na poziomie DNS przeznaczone pierwotnie do pi-hole.

**blackfox\_blocklist.txt**
Lista zawiera osobiście zebrane nazwy domen, które są blokowane w związku z:

* próbami phishingu,
* natrętnymi reklamami,
* domenami używanymi przez spamerów.

**malware\_blocklist.txt**
Lista zawiera nazwy domen zebranych z dostępnych blogów i innych źródeł, które są blokowane w związku z:

* złośliwymi domenami,
* rozprzestrzenianiem malware.

**IP\_blocklist.txt**
Lista stanowi kombinację zawartości **blackfox\_blocklist.txt** oraz **malware\_blocklist.txt** dla przypadków gdy złośliwy serwis jest hostowany bez wykorzystania nazw DNS.
