Notatka z reStructuredText
===========================


Nagłówki
---------
| ``Heading h1``

``===========``

| ``Heading h2``

``------------``

| ``Heading h3``

``~~~~~~~~~~~``

| ``Heading h4``

``^^^^^^^^^^^``



Paragraph
---------------
Tekst. By tworzyć nowe akapity trzeba odzielić tekst jednyną pustą linią. 



Note
--------------------------
| ``.. note::``

``____Jakaś notka``

.. note::
     W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie



Tip
-------------------------
| ``.. tip::``

``____Jakaś wskazówka``

.. tip::
      W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie    



Code
-----------------------
Fragment kodu oznaczamy `` na końcu i napoczątku frazy. Nie wolno dać spacji pomiędzy `` a wrazami.
````kod````



Code-block
-----------------------
| ``..  code-block:: txt``

| ``___:caption: podpis fragmentu kosu``

| ``(page break)``

``___<kod>``

  W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie
 


Ref
---------------------------------------------
``:ref:`ważne rzeczy tu <nazwa i lokacja podstrony w dokumencie>```



Link
---------------------------------------
```Tekst z linkiem <https://przykladowylink>`_``



Ordered list
----------------
| ``1. Punkt1``

``2. Punkt2``

``#. Punkt3 (którego numer wygeneruje się automatycznie)``



Unordered list
------------------
| ``* Punkt1``

| ``* Punkt2``

``* Punkt3 (do oznaczenia listy można użyć *,+,-)``



Definition List
---------------
| ``Nazwa1``

``_______Definicja rzeczy1``

| ``Nazwa2``

``_______Definicja rzeczy2``

| ``Nazwa3``

``_______Definicja rzeczy3``

  W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie



Img with path
---------------
| ``.. figure:: /_static/images/img.png``

| ``___:alt: To co jest na obrazku``

| ``(pusta linka co odziela)``

``___Napis pod obrazkiem``

  W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie



Table
-----------------

| ``+-----------+-----------+``

| ``| Header 1  | Header 2  |``

| ``+===========+===========+``

| ``| column 1  | column 2  |``

| ``+-----------+-----------+``

| ``| Cells may span        |``

``+-----------------------+``
