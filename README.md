NSPanelの使い方

ちょっとしたメモ

1. NSPanelの取り込み
Object ExplorerからPanelをInterface Builderのオブジェクト群にドラッグする

2. 起動時のPanelの振る舞い設定
NSPanel Objectの設定項目(Visible at launch)のチェックを外す。
こうしないと起動時にPanelが表示されてしまう。
もちろん表示したい場合はチェックをつけたままで良い。

3. Panelの表示
アプリケーションメニュ > PreferencesでPanelを表示させるために、
Preferencesを選択し、アクション設定から Send Actions > action の + をドラッグし、Panelにリンクさせる。
すると、リンク先のセレクターが表示されるので、orderFrontを選択する。
同様に、消すときは、アクション元からorderOutにリンクさせる。

画面付き説明は HowToUseNSPanel.rtfd を参照のこと。
