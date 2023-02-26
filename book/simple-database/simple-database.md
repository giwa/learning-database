# Simple Database

Database と聞くと重厚なものを連想しがちであるが、定義にもよるがとてもかんたんなデータベースも存在する。いきなり複雑なDBを作ろうとせずまずは、つくれることを実感してみよう。

DBの種類をかんたんに触れる

DBとは？

> ConnollyとBeggは、データベース管理システム（DBMS）を「ユーザーがデータベースを定義、作成、保守、およびアクセスを制御できるようにするソフトウェアシステム」と定義している[\[25\]](https://ja.wikipedia.org/wiki/%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9#cite\_note-FOOTNOTEConnollyBegg201464-25)。DBMSの例として、[MySQL](https://ja.wikipedia.org/wiki/MySQL)、[PostgreSQL](https://ja.wikipedia.org/wiki/PostgreSQL)、[Microsoft SQL Server](https://ja.wikipedia.org/wiki/Microsoft\_SQL\_Server)、[Oracle Database](https://ja.wikipedia.org/wiki/Oracle\_Database)、[Microsoft Access](https://ja.wikipedia.org/wiki/Microsoft\_Access)があげられる。

{% embed url="https://ja.wikipedia.org/wiki/%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9" %}

> DBMSが提供する機能は非常に多様である。中心的な機能は、データの保存、検索、更新である。コッドは、本格的な汎用DBMSが提供すべき機能およびサービスとして、次のようなものを提案した[\[26\]](https://ja.wikipedia.org/wiki/%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9#cite\_note-FOOTNOTEConnollyBegg201497%E2%80%93102-26)。
>
> * データの保存、検索、更新
> * メタデータを記述した、ユーザーがアクセス可能なカタログまたは[データディクショナリ](https://ja.wikipedia.org/wiki/%E3%83%87%E3%83%BC%E3%82%BF%E3%83%87%E3%82%A3%E3%82%AF%E3%82%B7%E3%83%A7%E3%83%8A%E3%83%AA)
> * トランザクションと並行処理のサポート
> * データベースが破損した場合に復旧するための機能
> * データへのアクセス時および更新時の承認のサポート
> * 遠隔地からのアクセスサポート
> * データベース内のデータが特定の規則に従うことを保証するための制約の適用





KVSのとても単純なものからやってみる



