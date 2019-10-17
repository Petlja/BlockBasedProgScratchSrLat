Procedure
=========

Program ne moramo da kreiramo kao celinu. 

Daleko je preglednije ako izdvojimo delove koda u manje, zasebne delove - **procedure**. Definisanjem procedura olakšavamo pisanje programa, ali i otkrivanje grešaka. Zato je dobro da čuvaš procedure u "rancu". Tako ćeš moći da ih koristiš u drugim programima koje stvaraš, ne gubeći vreme na njihovo ponovno kreiranje.

Razglašavanje
-------------

Programi napravljeni u Skreču obično sadrže više likova koji su u određenoj interakciji. Interakciju možemo sami da definišemo, ali možemo i da koristimo ugrađenu proceduru koja omogućava likovima da oglašavaju poruke (broadcasting messages) i tako utiču na tok programa. Korišćenjem procedure za oglašavanje bitno smanjuje broj blokova koje program sadrži, a i olakšava čitanje kloda.

.. image:: ../_images/procedure/ProcZ1a.png
   :width: 800px   
   :align: center

.. image:: ../_images/procedure/ProcZ1b.png
   :width: 800px   
   :align: center

.. mchoice:: ProcedureZ1
   :answer_a: Program A
   :answer_b: Program B
   :feedback_a: Izvršavanjem programa uočavamo da devojke uglas izgovaraju pozdrav na svom jeziku. To nije slučaj u svarnosti, tokom prirodnog razgovora. Sagovornika obično saslušamo, pa tek onda govorimo.    
   :feedback_b: U pravu si! Oglašavanjem poruke obezbedili smo da sagovornici budu pristojni - da ne upadaju u reč jedni drugima.
   :correct: b

   Na gornjim slikama data su dva programa - A i B. Oba programa sadrže 3 lika, devojke koje govore engleskim, nemačkim i francuskim jezikom. Ispod svake od njih nalaze se blokovi koji im pripadaju (obezbeđuju da pozdrave sagovornice na svom jeziku). Kreiraj programe kao na gornjim slikama. Analiziraj njihovo izvršavanje. Koji program predstavlja simulaciju prirodnog razgovora tri stranca?

.. reveal:: sakrivanjeDevojke
   :showtitle: Pogledaj video-uputstvo za kreiranje razgovora tri devojke
   :hidetitle: Sakrij video-uputstvo
 
   **Pogledaj proces izrade programa koji omogućava sagovornicama da ne upadaju jedna drugoj u reč:**
     
   .. youtube:: QgCCzBw6DKU
      :width: 735
      :height: 415
      :align: center

Definisanje nove procedure
--------------------------

.. |Vazno| image:: ../_images/Vazno.png

.. |Uradi| image:: ../_images/Uradi.png

U Skreču možemo da napravimo sasvim novu proceduru, u skladu sa našim potrebama. 

Zamisli da želimo da napravimo program koji iscrtava cvet na pozornici. Cvet se sastoji od latica. Dakle, potrebne su nam dve procedure:

•	**Latica**, u okviru koje ćemo definisati iscrtavanje jedne latice i
•	**Cvet**, u okviru koje ćemo definisati iscrtavanje pet latica.

Drugim rečima, procedura **Cvet** pozivaće proceduru **Latica**, dok će glavni program pozivati proceduru **Cvet**.

Proceduru kreiramo klikom na kategoriju **My Blocks**, u okviru koje treba da kliknemo na dugme **Make a Block**. Otvoriće se prozor koji nam omogućava da svojoj proceduri damo ime.

.. image:: ../_images/procedure/ProcLatica.png
   :width: 600px   
   :align: center

Ako želiš da i tvoj cvet ima latice kao na donjoj slici, napravi proceduru **Latica**, koju smo prikazali:

.. image:: ../_images/procedure/KodProcLatica.png
   :width: 780px   
   :align: center

|Uradi| Prepuštamo ti da napraviš proceduru koja iscrtava 5 latica. **Mala pomoć**: Nakon iscrtavanja jedne latice neophodno je da okreneš lik 72 stepena udesno.

.. reveal:: sakrivanjeCvet1
   :showtitle: Uporedi svoje rešenje sa našim
   :hidetitle: Sakrij rešenje
 
   **Moguće rešenje**
     
    .. image:: ../_images/procedure/Cvet.png
	:width: 770px   
	:align: center

.. infonote::

  |Vazno|   **Dakle, korišćenjem procedura pojednostavljujemo pisanje programa i otkrivanje grešaka.**




   
   
