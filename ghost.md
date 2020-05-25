# 幽霊のプログラムの作り方

## 1.プログラムを作る前の準備(Preparation before develop the program)

- ![sprite-select-button](figure/common/sprite-select-button.png) ボタンをクリックしてください。

  Click on the ![sprite-select-button](figure/common/sprite-select-button.png) button.

- Ghostを選択、クリックしてください。

  Select Ghost and click on it.

![sprite-select-ghost](figure/ghost/sprite-select-ghost.png)

- スプライトが設定されていることを確認してください。

  Make sure the sprites are set.

![sprite-ghost](figure/ghost/sprite-ghost.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![ghost-program-completed](figure/ghost/ghost-program-completed.png)

### 2-2. 作り方(How to develop)

- ![block-button](figure/common/block-button.png) を押してください。

  Press ![block-button](figure/common/block-button.png) .

- ![make-block-button](figure/common/make-block-button.png) を押してください。

  Press ![make-block-button](figure/common/make-block-button.png) .

- ・以下の画面が表示されるので、 **『ブロック名』を『ゴーストコスチューム』 に変更** してください。

  Changed "Block Name" to "Ghost Costume".

![init-screen_ghost-costume](figure/ghost/init-screen_ghost-costume.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『コスチューム番号』に変更** してください。

  Click on "Add argument (number or text)" and change "number or text" to "costume number"

![init-screen_ghostcos-costume](figure/ghost/init-screen_ghostcos-costume.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『x座標』に変更** してください。

  Click on "Add argument (number or text)" and change "number or text" to "x-coordinate".

![init-screen_ghostcos-x](figure/ghost/init-screen_ghostcos-x.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『y座標』に変更** してください。

  Click on "Add argument (number or text)", change "number or text" to "y-coordinate".

![init-screen_ghostcos-y](figure/ghost/init-screen_ghostcos-y.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『タイマー』に変更** し、OKボタンを押してください。

  Click on "Add argument (number or text)", change "number or text" to "timer" and press the OK button.

![init-screen_ghostcos-timer](figure/ghost/init-screen_ghostcos-timer.png)

- 以下の画面が表示されることを確認してください。

  Confirm that the following screen is displayed.

![ghost_costume-definition](figure/ghost/ghost_costume-definition.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![action-button](figure/common/action-button.png) ![action_sec-xy-change](figure/ghost/action_sec-xy-change.png)

![appearance-button](figure/common/appearance-button.png) ![appearance_costume-d](figure/ghost/appearance_costume-d.png)

- ![action_sec-xy-change](figure/ghost/action_sec-xy-change.png) ○秒に ![timer](figure/common/timer.png) を、x座標の○に ![x-coordinate](figure/common/x-coordinate.png) を、y座標の○に ![y-coordinate](figure/common/y-coordinate.png) をドラッグ&ドロップしてください。

  Drag and drop ![timer](figure/common/timer.png) into the "X seconds" of ![action_sec-xy-change](figure/ghost/action_sec-xy-change.png) ,  ![x-coordinate](figure/common/x-coordinate.png) into the "x-coordinates X", and ![y-coordinate](figure/common/y-coordinate.png) into the "y-coordinates X".

- ![appearance_costume-d](figure/ghost/appearance_costume-d.png) の「ghost-d」に ![costume-number](figure/common/costume-number.png) をドラッグ&ドロップしてください。

  Drag and drop ![costume-number](figure/common/costume-number.png) into the "ghost-d" of ![appearance_costume-d](figure/ghost/appearance_costume-d.png) .

- ブロックをくっつけてください。

  Connect the blocks.

![block-definition_ghost-costume](figure/common/block-definition_ghost-costume.png)

- ![variable-button](figure/common/variable-button.png) を押してください。

  Press ![variable-button](figure/common/variable-button.png) .

- ![make-list-button](figure/common/make-list-button.png) を押してください。

  Press ![make-list-button](figure/common/make-list-button.png) .

- **『新しいリスト名：』に『ゴーストの台詞』と入力後、『このスプライトのみ』を選択** してOKボタンを押してください。

  Enter "Ghost's dialogue" in the "New List Name:" field, select "This sprite only" and click the OK button.

![make-new-list_ghost](figure/ghost/make-new-list_ghost.png)

- 空のリストが画面上に表示されることを確認してください。

  Confirm that the blank list display on the screen.

![blank-list](figure/ghost/blank-list.png)

- リストの＋ボタンを押し、 **『こっちだよ』、『こっちだってば』** 計2項目を設定してください。(1つ入力したら＋ボタンで項目を追加してください。)

  Press the + button on the list to set two items in total: "This way" and "This way". (When you enter one item, please add an item with the + button.)

![words-list](figure/ghost/words-list.png)

- ![block-button](figure/common/block-button.png) を押してください。

  Press ![block-button](figure/common/block-button.png) .

- ![make-block-button](figure/common/make-block-button.png) を押してください。

  Press ![make-block-button](figure/common/make-block-button.png) .

- 以下の画面が表示されるので、 **『ブロック名』を『ゴーストアクション』に変更** してください。

  Change the "Block Name" to "Ghost Action".

![init-screen_ghost-action](figure/ghost/init-screen_ghost-action.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『コスチューム番号』に変更** してください。

  Click on "Add argument (number or text)" and change "number or text" to "costume number".

![init-screen_ghostact-costume](figure/ghost/init-screen_ghostact-costume.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『ゴーストの台詞の番号』に変更** してください。

  Click on "Add argument (number or text)" and change "number or text" to "Ghost's dialogue numbers".

![init-screen_ghostact-word](figure/ghost/init-screen_ghostact-word.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『x座標』に変更** し、OKボタンを押してください。

  Click on "Add argument (number or text)" and change "number or text" to "x coordinate" and press the OK button.

![init-screen_ghostact-x](figure/ghost/init-screen_ghostact-x.png)

- 以下の画面が表示されることを確認してください。

  Confirm that the following screen is displayed.

![ghost_action-definition](figure/ghost/ghost_action-definition.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_words-time](figure/common/appearance_words-time.png) ![appearance_display](figure/common/appearance_display.png)

![control-button](figure/common/control-button.png) ![control-wait-sec](figure/common/control-wait-sec.png)

![variable-button](figure/common/variable-button.png) ![variable_words-number1](figure/ghost/variable_words-number1.png)

![block-button](figure/common/block-button.png) ![block_ghost-costume](figure/ghost/block_ghost-costume.png)

- 『1秒待つ』の「1」を **『0.1』に変更** してください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Change "1" in "Wait 1 second" to "0.1" . (Double-click on the number to make it ready for editing.)

![control-wait-sec01](figure/ghost/control-wait-sec01.png)

- ![variable_words-number1](figure/ghost/variable_words-number1.png) の○に ![ghost-words-number](figure/ghost/ghost-words-number.png) をドラッグ&ドロップしてください。

  Drag and drop ![ghost-words-number](figure/ghost/ghost-words-number.png) to the X of ![variable_words-number1](figure/ghost/variable_words-number1.png) .

- ![appearance_words-time](figure/common/appearance_words-time.png) の「こんにちは!」に、 ![variable_words_ghost-words](figure/ghost/variable_words_ghost-words.png) をドラッグ&ドロップしてください。

  Drag and drop  ![variable_words_ghost-words](figure/ghost/variable_words_ghost-words.png) to the X of ![appearance_words-time](figure/common/appearance_words-time.png) .

- ![block_ghost-costume](figure/ghost/block_ghost-costume.png) の一番左の○に ![costume-number](figure/common/costume-number.png) を、左から2番目の○に ![x-coordinate](figure/common/x-coordinate.png) をドラッグ&ドロップしてください。また、 **右から2番目の○に『51』、一番右の○には『1』** と入れてください。

  Drag and drop ![costume-number](figure/common/costume-number.png) to the leftmost X of ![block_ghost-costume](figure/ghost/block_ghost-costume.png) , and ![x-coordinate](figure/common/x-coordinate.png) to the second X from the left.

  Put "51" in the second X from the right and "1" in the rightmost X.

- ブロックをくっつけてください。

  Connect the blocks.

![block-definition_ghost-action](figure/common/block-definition_ghost-action.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_words-time](figure/common/appearance_words-time.png) ![appearance_display](figure/common/appearance_display.png) ![appearance_hide](figure/common/appearance_hide.png) ![appearance_move-front](figure/common/appearance_move-front.png)

![event-button](figure/common/event-button.png) ![event-flag](figure/common/event-flag.png) ![event_send-message1](figure/common/event_send-message1.png)

![variable-button](figure/common/variable-button.png) ![variable_hide-words](figure/ghost/variable_hide-words.png)

![block-button](figure/common/block-button.png) ![block_ghost-costume](figure/ghost/block_ghost-costume.png)

- ![appearance_words-time](figure/common/appearance_words-time.png) の **「こんにちは!」を『やあ』に変更** してください。(文字をダブルクリックすることで、編集できる状態になります。)

  "Hello!" in ![appearance_words-time](figure/common/appearance_words-time.png) to "Hi". (Double-click on a character to make it ready for editing.)

- ![block_ghost-costume](figure/ghost/block_ghost-costume.png) の○に、 **左から『2』『134』『51』『1』と入れて** ください。

  Put "2", "134", "51", and "1" in X of ![block_ghost-costume](figure/ghost/block_ghost-costume.png) from the left.

- ブロックをくっつけてください。

  Connect the blocks.

![ghost-program1](figure/ghost/ghost-program1.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。
  
  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_hide](figure/common/appearance_hide.png)

![event-button](figure/common/event-button.png) ![event_get-message1](figure/common/event_get-message1.png) ![event_send-message1](figure/common/event_send-message1.png)

![block-button](figure/common/block-button.png) ![block_ghost-action](figure/ghost/block_ghost-action.png)

- 『メッセージ1を受け取ったとき』の▼ボタンを押して、表示される **一覧から『メッセージ2』を選んで** ください。

  Press the ▼ button on "When you received message 1" and select "Message 2" from the list that appears.

![event_get-message2](figure/common/event_get-message2.png)

- 『メッセージ1を送る』の▼ボタンを押して、表示される **一覧から『メッセージ3』を選んで** ください。

  Press the ▼ button for "Send Message 1" and select "Message 3" from the list that appears.

![event_send-message3](figure/common/event_send-message3.png)

- ![block_ghost-action](figure/ghost/block_ghost-action.png) の○に、 **左から『1』『1』『-134』と入れて** ください。

  Put "1", "1", and "-134" in the X of ![block_ghost-action](figure/ghost/block_ghost-action.png) from the left.

- ブロックをくっつけてください。

  Connect the blocks.

![ghost-program2](figure/ghost/ghost-program2.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![event-button](figure/common/event-button.png) ![event_get-message1](figure/common/event_get-message1.png) ![event_send-message1](figure/common/event_send-message1.png)

![block-button](figure/common/block-button.png) ![block_ghost-action](figure/ghost/block_ghost-action.png)

- 『メッセージ1を受け取ったとき』の▼ボタンを押して、表示される **一覧から『メッセージ4』を選んで** ください。

  Press the ▼ button on "When you received message 1" and select "Message 4" from the list that appears.

![event_get-message4](figure/common/event_get-message4.png)

- 『メッセージ1を送る』の▼ボタンを押して、表示される **一覧から『メッセージ5』を選んで** ください。

  Press the ▼ button for "Send Message 1" and select "Message 5" from the list that appears.

![event_send-message5](figure/common/event_send-message5.png)

-  ![block_ghost-action](figure/ghost/block_ghost-action.png) の○に、 **左から『2』『2』『134』と入れて** ください。

  Put "2", "2", and "134" in the X of ![block_ghost-action](figure/ghost/block_ghost-action.png) from the left.

- ブロックをくっつけてください。

  Connect the blocks.

![ghost-program3](figure/ghost/ghost-program3.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_words-time](figure/common/appearance_words-time.png) ![appearance_hide](figure/common/appearance_hide.png)

![event-button](figure/common/event-button.png) ![event_get-message1](figure/common/event_get-message1.png) ![event_send-message1](figure/common/event_send-message1.png)

![control-button](figure/common/control-button.png) ![control-wait-sec](figure/common/control-wait-sec.png)

![block-button](figure/common/block-button.png) ![block_ghost-costume](figure/ghost/block_ghost-costume.png) ×2

- ![appearance_words-time](figure/common/appearance_words-time.png) の **「こんにちは!」を『ばぁっ』に、「2秒」を『1秒』に変更** してください。(文字や数字をダブルクリックすることで、編集できる状態になります。)

  "Hello!" in ![appearance_words-time](figure/common/appearance_words-time.png) to "blah" and "2 seconds" to "1 second". (Double-click on a character to make it ready for editing.)

- 『メッセージ1を受け取ったとき』の▼ボタンを押して、表示される **一覧から『メッセージ6』を選んでく** ださい。

  Press the ▼ button on "When you received message 1" and select "Message 6" from the list that appears.

![event_get-message6](figure/common/event_get-message6.png)

- 『メッセージ1を送る』の▼ボタンを押して、表示される **一覧から『メッセージ7』を選んで** ください。

  Press the ▼ button for "Send Message 1" and select "Message 7" from the list that appears.

![event_send-message7](figure/common/event_send-message7.png)

- ![block_ghost-costume](figure/ghost/block_ghost-costume.png) の○に、 **左から『3』『110』『40』『0.01』と入れて** ください。

  Put "3", "110", "40" and "0.01" in the X of ![block_ghost-costume](figure/ghost/block_ghost-costume.png) from the left.


- もう一つの![block_ghost-costume](figure/ghost/block_ghost-costume.png) の○に、 **左から『4』『-256』『45』『0.05』と入れて** ください。

  Put "4", "-256", "45" and "0.05" in the X of ![block_ghost-costume](figure/ghost/block_ghost-costume.png) from the left.

- ブロックをくっつけてください。

  Connect the blocks.

![ghost-program4](figure/ghost/ghost-program4.png)

- これで幽霊のプログラムは完成です。

  The ghost program is now complete.
