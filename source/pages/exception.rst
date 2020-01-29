----------------------
Tratamento de Exceções
----------------------

.. code:: php
    
    try {
        $regex = new \Cajudev\Regex('/\w'); // repare que a regex não foi fechada
    } catch (\Cajudev\RegularExpressionException $e) {
        echo $e->getMessage(); // No ending delimiter '/' found
    }