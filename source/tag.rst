Tag
====

タグは、特定のバージョンをマークするのに使われます。
通常は、タグが移動されることはありません。
下の画像は、[1.08]と[1.06]のタグが打たれた、Git Extensionsのコミットログのイメージです。

.. image:: /images/tag.png

.. index::
   single: Tag; タグの作成

タグの作成
----------

Git Extensionsでは、コミットログのコンテキストメニューから ``タグの作成`` を選択することで、リビジョンにタグを付けることができます。
タグの名前を付けるためにダイアログが表示されます。
``Gitコマンド`` メニューからも ``タグの作成`` を選択することができます。
こちらは、タグを付けるリビジョンを選択して名前を入力するためのダイアログが開きます。

.. image:: /images/new_tag.png

タグが作成されると、それを変更することはできません。
変更するには、タグを削除して再度作成する必要があります。

.. index::
   single: Tag; タグの削除

タグの削除
----------

いくつかの操作をするために、一時的なタグを使用するのは非常に便利です。
Gitは各コミットを識別するために、SHA1ハッシュを使用します。
無名ブランチにタグを付けるのはいい選択です。
無名ブランチをマージする際に、タグを使用してマージしてから、そのタグを削除するのです。

.. image:: /images/delete_tag.png

Re-Tag?
^^^^^^^

次の "What should you do when you tag a wrong commit and you would want to re-tag?" という記事を読みましょう:
https://www.kernel.org/pub/software/scm/git/docs/git-tag.html#_on_re_tagging
