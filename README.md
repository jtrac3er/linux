Linux Kernel Fork am 13.04.2021 - 22:06

Dieser Fork soll für die Modifikation des Kernels dienen, um dessen Funktionalität zu erweitern. 

Konkret soll ein neuer Syscall implementiert werden, welcher alle Informationen über geswappte Pages
ausgibt. Zudem soll der Kernel noch mehr KPrints verwenden, vorallem wenn es um Swapping geht. 

Ziele dieses Unternehmens:
* Herausfinden, welche Pages geswappt werden, vorallem die Frage, ob .text Sektionen von Prozessen geswappt werden können oder nicht
* Mehr über den Linux Kernel und auch allgemein über Kernel lernen
* Lernen, wie man ein Projekt forkt
* Lernen, wie man neue Syscalls zum Linux Kernel hinzufügt
* Lernen, wie man den Kernel überhaupt kompiliert und einsetzt 
