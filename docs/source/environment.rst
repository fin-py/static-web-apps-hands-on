環境構築
========

:numref:`clone-repository` のコマンドを実行して、ハンズオンのリポジトリをクローンします。

.. code-block:: bash
   :name: clone-repository
   :caption: リポジトリのクローン

   git clone https://github.com/fin-py/static-web-apps-hands-on.git

.. note::

   PCにGitがインストールされていない場合はzipファイルをダウンロードして展開します

   https://github.com/fin-py/static-web-apps-hands-on/archive/refs/heads/main.zip

:numref:`launch-vscode` のコマンドを実行してVS Codeを起動します。

.. code-block:: bash
   :name: launch-vscode
   :caption: VS Codeの起動

   cd static-web-apps-hands-on.git
   code .

VS Codeの拡張から、 `Remote - Containers` を検索し、インストールします（ :numref:`install-remote-containers` ）。

.. figure:: ./images/install-remote-containers.png
   :name: install-remote-containers
   
   Remote - Containers拡張のインストール

:numref:`reopen-in-container` の画面がでたら、 `Reopen in Contaier` をクリックします。

.. figure:: ./images/reopen-in-container.png
   :name: reopen-in-container

   Reopen in Contaier

.. caution::

   初回はDev Containerを構築するため、時間がかかります。