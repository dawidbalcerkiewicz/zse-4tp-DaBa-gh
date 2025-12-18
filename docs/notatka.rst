Składnia elementów dokumentu
============================

1. Nagłówki tekstowe (poziomy 1–4)
---------------------------------

Nagłówek poziom 1
================

Nagłówek poziom 2
----------------

Nagłówek poziom 3
~~~~~~~~~~~~~~~~

Nagłówek poziom 4
^^^^^^^^^^^^^^^^


2. Akapit tekstowy (treść)
--------------------------

To jest zwykły akapit tekstowy. Może składać się z jednego lub wielu zdań.
Nowy akapit oddzielamy pustą linią.

To jest drugi akapit tekstu.


3. Akapit informacyjny (Note, Tip)
----------------------------------

.. note::
   To jest akapit informacyjny typu NOTE.

.. tip::
   To jest akapit informacyjny typu TIP.


4. Fragment kodu (liniowy, blokowy)
-----------------------------------

Kod liniowy (inline):
Użycie funkcji ``print()`` w języku Python.

Kod blokowy:

.. code-block:: python

   print("Hello World")


5. Odnośnik (lokalny RtD, zewnętrzny)
------------------------------------

Link zewnętrzny:
`Google <https://www.google.com>`_

Link lokalny (do innej strony dokumentacji):
:doc:`autor`


6. Listy
--------

Lista wypunktowana:

- element pierwszy
- element drugi
- element trzeci

Lista numerowana:

1. element pierwszy
2. element drugi
3. element trzeci

Lista definicji:

Python
   Język programowania wysokiego poziomu.

Sphinx
   Narzędzie do generowania dokumentacji.


7. Obraz (alternatywny tekst oraz podpis)
-----------------------------------------

Obraz z tekstem alternatywnym:

.. image:: obraz.png
   :alt: Alternatywny opis obrazu
   :align: center

Obraz z podpisem:

.. figure:: obraz.png
   :alt: Alternatywny opis obrazu

   To jest podpis pod obrazem.


8. Tabela
---------

+-----------+------------+
| Kolumna 1 | Kolumna 2  |
+===========+============+
| Dane A    | Dane B     |
+-----------+------------+
| Dane C    | Dane D     |
+-----------+------------+
