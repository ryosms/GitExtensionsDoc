.. index::
   single: Integration

Integration
===========

インストール時に、Visual Studio用のプラグインと、シェルの拡張機能もインストールするかどうかを選択できます。

.. index::
   single: Integration; Visual Studio

Visual Studio
-------------

ファイルのコンテキストメニューには2つのオプションがあります:

* ``ファイルの履歴`` オプションを選択して、ファイルの履歴を確認する
* 最後にコミットされたリビジョンにファイルをリセットする

.. image:: /images/visual_studio/context_menu.png

Git Extensionsのツールバーからは、最も一般的な操作を実行することができます。

+-------------------------------------------------+---------------------------------------------------------------+
|.. image:: /images/visual_studio/commit.png      | Commit (branch)                                               |
+-------------------------------------------------+---------------------------------------------------------------+
|.. image:: /images/visual_studio/browse.png      | Browse                                                        |
+-------------------------------------------------+---------------------------------------------------------------+
|.. image:: /images/visual_studio/pull.png        | Pull                                                          |
+-------------------------------------------------+---------------------------------------------------------------+
|.. image:: /images/visual_studio/push.png        | Push                                                          |
+-------------------------------------------------+---------------------------------------------------------------+
|.. image:: /images/visual_studio/stash.png       | 変更のStash                                                   |
+-------------------------------------------------+---------------------------------------------------------------+
|.. image:: /images/visual_studio/settings.png    | 設定                                                          |
+-------------------------------------------------+---------------------------------------------------------------+

.. image:: /images/visual_studio/toolbar.png

ほとんどすべての機能が、Visual Studioの ``Git`` メニューから実行できます。

.. image:: /images/visual_studio/git_menu.png

.. index::
   single: Integration; Windows Explorer

Windows Explorer
----------------

一般的なコマンドは、シェルの拡張機能を使用してWindowsのExplorerから実行できます。
このオプションは、シェルの拡張機能がインストールされている場合にのみ有効になります。

.. image:: /images/explorer_integration.png

gitの管理下にないフォルダに対して、リポジトリの作成やクローンをすることもできます。

.. image:: /images/explorer_integration_new.png

