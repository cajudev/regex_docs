---------------
Casando padrões
---------------

.. code:: php
    
    $regex = new \Cajudev\Regex('/\w/');

    if ($regex->match('Lorem')) {  // true
        $regex->get(); // 'L'
    }