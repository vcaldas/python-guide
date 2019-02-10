Como contribuir
-----------------

Este guia está em intenso desenvolvimento. Se você deseja contribuir, por favor veja: 

https://docs.python-guide.org/notes/contribute/


Contribuir com traduções
------------------------

Caso você queira contribuir com traduções e revisões, visite:
https://www.transifex.com/own-16/python-guide-pt_br/dashboard/


Como testar suas modificações
-----------------------------

A versão html deste guia é construída com [sphinx](http://www.sphinx-doc.org/en/stable/). Você pode testar suas revisões localmente se tiver sphinx instalado. Você consegue instalá-lo facilmente using pip (como descrito no link). 

``` bash
pip install --user sphinx
```

Navegue, então, para o diretório em que está a "makefile" e digite ```make build``` ou ```make html```. Sphinx então gerará a página em html na pasta chamada _build/html.

*Nota para versão em pt_BR:* A versão traduzida contém a flag  ```-D language='pt_BR'```ativada. 

Após navegar até a pasta, você pode então iniciar um servidor web para verificar suas modificações localmente: 


``` bash
python3 -m http.server
```

Por padrão, http.server monitora cada endereço de ip atrelado ao servidor na porta 8000. Para mudar a porta, digamos, para 8005: l

``` bash
python3 -m http.server 8005 --bind 127.0.0.1
```

No browser de sua preferência, digite:  http://localhost:8005


Guia de Estilo
--------------

Para todas as contribuições, por favor siga o "Guia de Estilo" para Python.

https://docs.python-guide.org/notes/styleguide/
