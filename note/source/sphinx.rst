========
sphinx
========


.. contents:: SphinxとGitHubでHTMLページを作る


html編集
===============

virtualenv をアクティベート
------------------------------------

..  code-block:: bash

    $ workon main


Sphinxプロジェクトディレクトリに移動する
------------------------------------------------------------------------

..  code-block:: bash

    $ cdvirtualenv
    $ cd src/myuttan.github.com/note/


ソースコードを変更する
------------------------------------

..  code-block:: bash

    $ vi source/○○   ← 編集したいフォルダ名


ビルドする
------------------------------------

..  code-block:: bash

    $  make html

確認
------------------------------------

.. todo::

    - ネットワーク共有でExploreeでかくにん



コミット＆プッシュ
------------------------------------

.. code-block:: bash

    $ git add  file
    $ git commit -a -m "hohoge"
    $ git push


Sphinxについて
================== 

reStructuredText
-----------------------------

- `reStructuredText入門 <http://sphinx.shibu.jp/rest.html>`_
- http://openalea.gforge.inria.fr/doc/openalea/doc/_build/html/source/sphinx/rest_syntax.html
- http://www.planewave.org/translations/rst/quickstart.ja.html
- http://hehe.s9.xrea.com/html/restructured.rst.html

