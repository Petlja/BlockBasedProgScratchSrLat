Crtanje
=======

Svi likovi u Skreču sadrže nevidljivu olovku i imaju sposobnost da, tokom kretanja, ostavljaju trag na pozornici.  

Za crtanje, potrebni su nam blokovi iz kategorije **Olovka (Pen)**. Ovu grupu blokova neophodno je da dodamo u radno okruženje Skreča. To činimo tako što kliknemo na dugme |Ekstenzija| koje se nalazi u donjem levom uglu prozora, a zatim odaberemo ekstenziju **Olovka**.
  .. |Ekstenzija| image:: ../_images/Ekstenzija.png

.. image:: ../_images/crtanje/ekstOlovka.png 
   :align: center

U okviru kartice **Programiranje (Code)**, pojaviće se nova kategorija blokova **Olovka**. U okviru nje, na raspolaganju nam je 9 blokova namenjenih crtanju po pozornici. Pomoću njih brišemo išaranu pozornicu (*erase all*), spuštamo i podižemo olovku (*pen down*, *pen up*), lako kontrolišemo boju i debljinu olovke (*set pen color*, *change pen color*, *set pen size*, *change pen size*). 

.. image:: ../_images/crtanje/BlokoviOlovka.png 
   :align: center

Inicijalno, olovka lika je podignuta. **Da bi crtanje bilo moguće, neophodno je da olovku spustimo.**

Crtanje "slobodnom rukom"
-------------------------

.. |LikOlovka| image:: ../_images/crtanje/LikOlovka.png
  		    :width: 70px
.. |OK1| image:: ../_images/kretanje/OK1.png

.. |Uradi| image:: ../_images/Uradi.png

Kada pomislimo na crtanje slobodnom rukom, obično zamislimo kako crtamo olovkom. Zato ćemo, u program koji simulira ovaj oblik crtanja koristiti lik |LikOlovka|, koji se nalazi u biblioteci likova.

Likovi u Skreču crtaju svojim centrom. Kako bi naša olovka crtala "grafitnim vrhom", moramo da promenimo poziciju centra lika. To činimo u okviru kartice **Kostimi (Costumes)**.  

VIDEO - CENTAR LIKA

Kada smo razmatrali načine kretanja lika po pozornici, predstavili smo blok |OK1|. Ako beskonačan broj puta (*Forever*) ponovimo izvršavanje ovog bloka, lik će se neprestano kretati po pozornici tako što će pratiti kursor miša. Dakle, upotrebom ovog bloka možemo da simuliramo crtanje - pomerajući kursor miša po pozornici "crtaćemo" po pozornici.
    
Analiziraj sledeće skripte:

.. image:: ../_images/crtanje/KodSR.png  
   :align: center

|Uradi| Napravi program koji omogućava crtanje slobodnom rukom i obezbedi da se, pritiskom na taster **s** izvršavanje programa zaustavi. Potraži odgovarajuće blokove u kategorijama **Događaji (Events)** i **Upravljanje (Control)**.

Upravljanje kretanjem lika pomoću tastature i crtanje
-----------------------------------------------------

Odlična je prilika da iskoristimo blokove koji obezbeđuju kretanje lika pomoću strelica i dodatno ih unapredimo tako da lik iscrtava linije određene boje i debljine. 

Neka lik crta na sledeći način:

•	dok se kreće udesno, neka iscrtava liniju plave boje, debljine 5 koraka (piksela);
•	dok se kreće ulevo, neka iscrtava liniju zelene boje, debljine 10 koraka (piksela);
•	dok se kreće nagore, neka iscrtava liniju crvene boje, debljine 15 koraka (piksela);
•	dok se kreće nadole, neka iscrtava liniju žute boje, debljine 20 koraka (piksela).

Kreiraj sledeće blokove:

.. image:: ../_images/crtanje/strelicebojadebljina.png
   :width: 840px   
   :align: center

Mi smo nacrtali ovu sliku:

.. image:: ../_images/crtanje/slobodnaruka.png
   :width: 650px   
   :align: center

Pokušaj da napraviš program koji iscrtava sličnu. 

Apsolutno kretanje i crtanje
----------------------------

.. image:: ../_images/crtanje/brodic.png
   :width: 650px   
   :align: center

Analizom gornje slike uočavamo da nije teško odrediti tačke čijim spajanjem nastaje crtež brodića. 

|Uradi| Napravi program koji iscrtava brodić linijama svetlo plave boje debljine 5 piksela. Ne zaboravi da obrišeš pozornicu pre nego što iscrtavanje započne. Takođe, ne zaboravi da postaviš macu-mornara na palubu brodića.


.. reveal:: sakrivanjeCrtanje1
   :showtitle: Uporedi rešenje sa našim
   :hidetitle: Sakrij rešenje
 
   **Moguće rešenje**
     
    .. image:: ../_images/crtanje/BrodicKod.png
	:width: 350px   
	:align: center

Pečat
-----

.. |BO2| image:: ../_images/crtanje/BO2.png

.. |Paint| image:: ../_images/crtanje/Paint.png

Ponekad je potrebno da na pozornici iscrtamo i rotiramo složenije slike. Umesto da iznova i iznova iscrtavamo željeni oblik, zgodno je da kreiramo kostim određenog oblika, a onda ga umnožavamo i rotiramo koristeći blok Pečat |BO2|.

  


Dovoljno je da kreiramo novi lik crtanjem |Paint|, a zatim, u grafičkom editoru kartice **Kostimi (Costumes)** nacrtamo oblik koji želimo.

OVDE VIDEO ZMAJEVI

Pečat možemo da koristimo i sa kostimima likova koje pronalazimo u Skreč biblioteci likova.


