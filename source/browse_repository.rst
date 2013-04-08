.. index::
   single: Browse Repository

Browse Repository
=================

Git Extensionsを起動して、開くリポジトリを選択すればリポジトリをブラウズすることができます。
メインのウィンドウにはコミットログが表示されます。
また、シェル拡張やVisual StudioのIDEからも ``Browse`` ウィンドウを開くことができます。

.. index::
   single: Browse Repository; コミットログの表示

コミットログの表示
------------------

コミットの全履歴を確認できます。
グラフはブランチをマージを表示します。
Ctrlクリックで2つのリビジョンを選択することで、リビジョン間のDiffを表示できます。

.. image:: /images/commit_diff_view.png

コミットログのコンテキストメニューでリビジョングラフの有効／無効を切り替えられます。
また、すべてのブランチを表示するのではなく、現在のブランチのみを表示するようにもできます。
その他のオプションについては後述します。

.. image:: /images/commit_contextual_menu.png

.. index::
   single: Browse Repository; 検索履歴

検索履歴
--------

履歴は、基本的な検索方法である正規表現を使用して検索することができます。
ツールバー上のクイックフィルターは、コミットメッセージ、作成者、そしてコミッターを検索します。

.. image:: /images/quick_filter.png

コミットログのコンテキストメニューから、高度なフィルターダイアログを開くことができます。
フィルターダイアログでは、より詳細にコミットを検索できます。
フィルターを解除するには、ツールバー上のクイックフィルターを空にして ``Enter`` を押下するか、ダイアログからすべてのフィルターを除去します。


.. image:: /images/advance_filter_dialog.png

.. index::
   single: Browse Repository; 単一ファイルの履歴

単一ファイルの履歴
------------------

単一ファイルの履歴を表示するには、 ``ファイルツリー`` タブか ``Diff`` タブでファイル名を右クリックし、 ``blame`` を選択します。

.. image:: /images/context_menu_blame.png

履歴ビューアには、単一のファイルの全リビジョンが表示されます。
``表示`` タブでは、各コミット後のファイルの内容を確認できます。

.. image:: /images/file_history.png

``Diff`` タブでは、コミット間のDiffを確認できます。

.. note::
	追加された行には ``+`` が、削除された行には ``-`` が付きます。

.. image:: /images/file_history_diff.png

.. index::
   single: Browse Repository; Blame

Blame
-----

ファイル履歴ビューアには、blameの機能があります。
ある行を最後に編集した人を確認できます。

.. image:: /images/blame.png

コードの行をダブルクリックすることで、その変更が行われたコミットにジャンプします。
