------------------
Performance Global
------------------

.. code:: php
    
    $regex = new \Cajudev\Regex('/\w/g'); // repare no modificador aqui

    if ($regex->match('Lorem')) {  // true
        $regex->get(); // ['L', 'o', 'r', 'e', 'm'];
    }