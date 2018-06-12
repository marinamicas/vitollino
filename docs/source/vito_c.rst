.. _vito_a:


Terceiro Cenário do Jogo
========================

Nesse módulo veremos os labirintos:

.. image:: /_static/tartarugas.png

.. code-block:: python

    from _spy.vitollino import Cena

    TARTARUGAS = "https://activufrj.nce.ufrj.br/studio/labase/lago.jpg?disp=inline&size=G"

    def main():
        uma_cena = Cena(img=TARTARUGAS)
        uma_cena.vai()

    if __name__ == "__main__":
        main()

.. moduleauthor:: Carlo Oliveira <carlo@nce.ufrj.br>

.. note::
    Marina Micas iniciando o tutorial interativo.

