Realizzazione di un sito web utilizzando reST_ e Sphinx_
========================================================

|image01|

Clicca qui per visitare il sito-in-costruzione_.

PRIMO step: conversione da *docx* a *txt*
-----------------------------------------

Utilizzare lo script bash per la conversione massive dei file.
E' necessario aver installato **pandoc**.


SECONDO step: inserimento markup reStructuredText
-------------------------------------------------

Per convertire un documento ci si può aiutare usando il semplice editor online:
RestructuredText-on-line_

o, in alternativa, si può utilizzare un qualunque editor di testo aggiungendo i simboli grafici necessari ad individuare i titoli e i paragrafi.

Al termine delle modifiche, rinominare l'estensione del file da .txt a .rst, aiuterà a capire quali file sono stati modificati.

TERZO step: creazione indici
----------------------------

Ordinare i documenti in sottocartelle in base ai temi delle schede e creare una pagina di indice.

Le sottocartelle conterranno i file ed eventuali immagini. Queste verranno salvate nella stessa cartella del file ed avranno lo stesso nome file del file .rst a cui si riferiscono ed eventualmente, se sono presenti più di una immagine, un numero progressivo, per esempio: *nomefile01.jpg*.


.. |image01| image:: PhiYV.png
             :height: 400 px

.. _Sphinx: http://www.sphinx-doc.org/en/master/
.. _reST: http://docutils.sourceforge.net/rst.html
.. _sito-in-costruzione: https://esperimenti-nel-laboratorio-di-scienza.readthedocs.io/it/latest/
.. _RestructuredText-on-line: http://rst.ninjs.org/
