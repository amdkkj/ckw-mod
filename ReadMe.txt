/////////////////////////////////////////////
// 概要

  コマンドプロンプトウィンドウを使い易くしたソフトです。

  コマンドプロンプトを隠しておいて、画面表示や キー操作など
  ユーザーインターフェース部分だけを置き換えています。

  Vista/7/8.1/10で動作する Win32アプリケーションです。

  ※ckw-mod(ckw) は、オープンソースのフリーソフトウェアです。
    複数の有志の手を経て、段階的に修正、改良されています。

    オリジナル (ckw) を 1世代目とすると、
    2世代目 (1世代目の派生版) として 「ckw 改変版」       (  ckw-mod/ckw-mod)、
    3世代目 (2世代目の派生版) として 「ckw Unicode改変版」(rururutan/ckw-mod)
    が存在します。

    当バージョン (amdkkj/ckw-mod) は、
    3世代目の「ckw Unicode改変版」(rururutan/ckw-mod) を
    個人的なニーズで改変した「私家版」(amdkkj版) です。

  オリジナルの配布元は以下になります。（リンク切れ）
  http://www.geocities.jp/cygwin_ck/

  改変版はGithubにて公開しています。
  https://github.com/ckw-mod/ckw-mod

  Unicode改変版はGithubにて公開しています。
  https://github.com/rururutan/ckw-mod/

  当 私家版(amdkkj版) もGithubにて公開しています。
  https://github.com/amdkkj/ckw-mod/

  このソフトウェアのライセンスは GNU General Public License v2です。

////////////////////////////////////////////
// コンパイル

  ・Microsoft Visual C++ 2010 (SP1)
  ・Microsoft Windows SDK v7.0A
  という組み合わせでコンパイルを確認しています。

  なお、当 私家版(amdkkj版) の派生元である「Unicode改変版」(rururutan/ckw-mod) は、

  ・Microsoft Visual C++ 2015
  ・Microsoft Visual C++ 2013 v120_xp ランタイム
  という組み合わせでコンパイルを確認しています。

  とのことです。

  当 私家版(amdkkj版) は、ソースコードの大半が「Unicode改変版」と同じですので、
  同じように VC++ 2013/2015 でもコンパイルできる見込みです。
  ただし、実際に VC++ 2013/2015 でコンパイルができるかどうかは、
  コンパイル環境がなく確認しておりません。

  Visual C++ 2010以降向けのソリューションファイルを同梱しています。

////////////////////////////////////////////
// その他

  「Console」を参考にさせて頂きました。
  http://sourceforge.net/projects/console/

  改変版を作るにあたって多数の方のパッチを取り込ませていただきました。
  この場をお借りしてお礼申し上げます。
