# dev-memos

開発関連のメモ・チートシートの置き場です。

## 目次

| メモ | 内容 |
|---|---|
| [web/bootstrap-honoka-cheatsheet.txt](web/bootstrap-honoka-cheatsheet.txt) | Bootstrap 4 (Honoka テーマ) のクラス名チートシート。命名ルール・部品別のコピペ用 HTML・余白ユーティリティの読み方・Honoka の導入手順 |
| [web/bootstrap-js-alternatives.txt](web/bootstrap-js-alternatives.txt) | Bootstrap の JS (jQuery依存) を使わず `<details>` / `<dialog>` 等の HTML 標準機能でドロップダウンやモーダルを作る方法 |
| [java/servlet-jsp-dao-dto-basics.txt](java/servlet-jsp-dao-dto-basics.txt) | Servlet + JSP + DAO/DTO の MVC 構成の要点。PRG パターン、WEB-INF 配下 JSP、PreparedStatement、`<c:out>`、Jakarta 版 JSTL の注意点 |
| [java/portable-jdk-tomcat-setup.txt](java/portable-jdk-tomcat-setup.txt) | インストーラ・管理者権限なしで JDK + Tomcat 環境を作る手順。javac 直ビルド、ROOT.xml でのフォルダ直接デプロイ |
| [db/h2-database.txt](db/h2-database.txt) | H2 Database の使い方。JDBC URL の種類、テーブル自動作成パターン、H2 コンソール、ファイルロックの注意点 |
| [windows/powershell51-pitfalls.txt](windows/powershell51-pitfalls.txt) | PowerShell 5.1 の落とし穴。BOM なし UTF-8 の .ps1 文字化け(実体験)、`&&` 不可、Out-File の UTF-16 問題など |

## メモの追加ルール(ゆるめ)

- カテゴリごとにフォルダを切る(`web/`, `java/`, `db/` など)
- 1メモ = 1ファイル、形式は .txt / .md どちらでも
- 追加したらこの README の目次にも1行足す
