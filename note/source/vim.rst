=====================
vimエディタ
=====================

基本操作
========


.. list-table:: モード切替

   * - i
     - 挿入モード(カーソル左)

   * - a
     - 挿入モード(カーソル右)

   * - :
     - コマンドラインモード

   * - esc
     - ノーマルモード


.. list-table:: ノーマルモード
   :header-rows: 1

   * - 保存＆終了
     - コピー＆ペースト
     - 取り消し＆削除
     - 選択

   * - :w 保存(:w!で強制保存)
     - dd 行をカット
     - u 取り消し
     - v 選択開始

   * - :q 終了(:q!で破棄して保存)
     - yy 行をコピー
     - U 行に対して行った変更の全てを取り消す
     - V 行選択

   * - :f ファイル名を変更して編集を続ける
     - P ペースト(カレント行)
     - x 1文字を削除
     - gv 直前の選択範囲を再選択

   * - :e ファイルを開く。
     - p ペースト(カーソルの下)
     - D カーソル位置から行末まで削除
     - C-v 短形選択

.. image:: _static/vimgazou.PNG


その他コマンド
=================

・検索する
..  code-block:: bash
    
    /hoge :コマンドと同じく下に/と表示され
    検索したい語をタイプする
    同じ語に飛ぶときnをタイプ
