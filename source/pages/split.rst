-----------------
Divisão em partes
-----------------

.. code:: php
    
    $regex = new \Cajudev\Regex('/[aeiou]/');

    $regex->split('lorem'); // ['l', 'r', 'm'];
