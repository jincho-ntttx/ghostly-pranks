# 恐竜2のプログラムの作り方

## 1.プログラムを作る前の準備(Preparation before develop the program)

- Scratch 3.0を起動し、スプライト1を削除してください。(スプライト1を選択→×をクリック)

  Start Scratch 3.0 and delete sprite 1.(Select sprite 1　→　Click ×)

![sprite-cat-delete](figure/dinosaur2/sprite-cat-delete.png)

- ![sprite-select-button](figure/common/sprite-select-button.png) ボタンをクリックしてください。

  Click on the  ![sprite-select-button](figure/common/sprite-select-button.png) button.

- Dinosaur2を選択、クリックしてください。

  Select Dinosaur2 and click on it.

![sprite-select-dino2](figure/dinosaur2/sprite-select-dino2.png)

- スプライトが設定されていることを確認してください。

  Make sure the sprites are set.

![sprite-dino2](figure/dinosaur2/sprite-dino2.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![dino2-program-completed](figure/dinosaur2/dino2-program-completed.png)

### 2-2. 作り方(How to develop)

- ![block-button](figure/common/block-button.png) を押してください。

  Press ![block-button](figure/common/block-button.png) .

- ![make-block-button](figure/common/make-block-button.png) を押してください。

  Press ![make-block-button](figure/common/make-block-button.png) .

- 以下の画面が表示されるので、 **『ブロック名』を『恐竜2のリアクション』に変更** してください。

  Change the "Block Name" to "Dinosaur 2's Reaction".

![init-screen](figure/common/init-screen.png)

- 『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『コスチューム番号』に変更** してください。

  Click on "Add argument (number or text)" and change "number or text" to "costume number".

![init-screen_costume](figure/common/init-screen_costume.png)

- もう一度『引数を追加(数値またはテキスト)』をクリックし、 **『number or text』を『台詞』に変更** し、OKボタンを押してください。

  Click "Add argument (number or text)" again, change "number or text" to "dialogue" and press the OK button.

![init-screen_costume-words](figure/common/init-screen_costume-words.png)

- 以下の画面が表示されることを確認してください。

  Confirm that the following screen is displayed.

![dino2_reaction-definition](figure/common/dino2_reaction-definition.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![appearance-button](figure/common/appearance-button.png) ![appearance_costume-dino2d](figure/common/appearance_costume-dino2d.png) ![appearance_words-time](figure/common/appearance_words-time.png)

- ![appearance_costume-dino2d](figure/common/appearance_costume-dino2d.png)  の『[donosaur2-d』に ![costume-number](figure/common/costume-number.png) をドラッグ&ドロップしてください。

  Drag and drop ![costume-number](figure/common/costume-number.png) to "donosaur2-d" in ![appearance_costume-dino2d](figure/common/appearance_costume-dino2d.png) .

- ![appearance_words-time](figure/common/appearance_words-time.png)  の『こんにちは！』に ![dialogue](figure/common/dialogue.png) をドラッグ&ドロップし、 **「2」を『1』に変更** してください。

  ![appearance_words-time](figure/common/appearance_words-time.png) of "Hello!" drag and drop ![dialogue](figure/common/dialogue.png) to "1" and change "2" to "1".

- ブロックをくっつけてください。

  Connect the blocks.

![block-definition_reaction-dino2](figure/common/block-definition_reaction-dino2.png)

- ![variable-button](figure/common/variable-button.png) を押してください。

  Press ![variable-button](figure/common/variable-button.png) .

- ![make-list-button](figure/common/make-list-button.png) を押してください。

  Press ![make-list-button](figure/common/make-list-button.png) .

- **『新しいリスト名：』に『恐竜2の台詞』と入力後、『このスプライトのみ』を選択** してOKボタンを押してください。

  Enter "Dinosaur 2 dialogu" in the "New List Name:" field, select "This Sprite Only" and click the OK button.

![make-new-list](figure/common/make-new-list.png)

- 空のリストが画面上に表示されることを確認してください。

  Confirm that the blank list display on the screen.

![blank-list](figure/dinosaur2/blank-list.png)

- リストの＋ボタンを押し、 **『えっ？』『何？』『誰？』『ギャーーー』**  計4項目を設定してください。(1つ入力したら＋ボタンで項目を追加していってください。)

  Press the + button on the list and say, "Huh?" "What?" "Who is it?" "Gah!" ,set a total of four items.(Once you have entered one item, please add more items by pressing the + button.)

![words-list](figure/dinosaur2/words-list.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![action-button](figure/common/action-button.png) ![action_xy-coordinates](figure/common/action_xy-coordinates.png)

![appearance-button](figure/common/appearance-button.png) ![appearance_costume-dino2d](figure/common/appearance_costume-dino2d.png)

![event-button](figure/common/event-button.png) ![event-flag](figure/common/event-flag.png)

![variable-button](figure/common/variable-button.png) ![variable_hide-words-list](figure/dinosaur2/variable_hide-words-list.png)

- 『x座標を○、y座標を○にする』の **x座標に『0』、y座標に『-27』と入れて** ください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Enter "0" in the x-coordinate and "-27" in the y-coordinate in "Make x-coordinate X and y-coordinate X". (Double-click on the number to make it ready for editing.)

![action_xy-change](figure/dinosaur2/action_xy-change.png)

- 『コスチュームをdinosaur2-dにする』の▼ボタンを押し、表示される **コスチュームの一覧から『dinosaur2-c』を選んで** ください。

  Press ▼ on the "Make costume dinosaur2-d" button and select "dinosaur2-c" from the list of costumes that appears.

![appearance_costume-c](figure/dinosaur2/appearance_costume-c.png)

- ブロックをくっつけてください。

  Connect the blocks.

![dino2-program-1](figure/dinosaur2/dino2-program-1.png)

- 以下のブロックを画面中央にドラッグ&ドロップします。

  Drag and drop the following blocks to the center of the screen.

![action-button](figure/common/action-button.png) ![action_sec-xy-change](figure/dinosaur2/action_sec-xy-change.png)

![event-button](figure/common/event-button.png) ![event_get-message1](figure/common/event_get-message1.png) ×4　 ![event_send-message1](figure/common/event_send-message1.png) ×3

![variable-button](figure/common/variable-button.png) ![variable_words-number1](figure/dinosaur2/variable_words-number1.png) ×4

![block-button](figure/common/block-button.png) ![block_dino2-reaction](figure/dinosaur2/block_dino2-reaction.png) ×4

- 『○秒でx座標を○に、y座標を○に変える』のそれぞれの数字を、 **『0.05秒』、『x座標を-10』、『y座標を-12』に変更** してください。

  Change the numbers in "Change x-coordinate to X and y-coordinate to X in X seconds" to "0.05 seconds", "x-coordinate to -10", and "y-coordinate to -12", respectively.

![action_sec005-xy-change](figure/dinosaur2/action_sec005-xy-change.png)

- 『メッセージ1を送る』の▼ボタンを押して **『新しいメッセージ』を選択** してください。

  Press the ▼ button for "Send Message 1" and select "New Message".

![event_send-new-message](figure/dinosaur2/event_send-new-message.png)

- 以下の画面が表示されることを確認し、 **『新しいメッセージ名：』に『メッセージ2』と入力し** OKボタンを押してください。

  Enter "Message 2" in the "New Message Name:" field and click the OK button.

![init-screen_new-message2](figure/dinosaur2/init-screen_new-message2.png)

- 同様に **『メッセージ4を送る』『メッセージ6を送る』を作成** してください。

  Create "Send Message 4" and "Send Message 6" in the same way.

- 以下のブロックができます。

  You can create the following blocks.

![event_send-message2](figure/dinosaur2/event_send-message2.png) , ![event_send-message4](figure/dinosaur2/event_send-message4.png) , ![event_send-message6](figure/dinosaur2/event_send-message6.png)

- 『メッセージ1を受け取ったとき』の▼ボタンを押して **『新しいメッセージ』を選択** してください。

Press the ▼ button under "When you received message 1" and select "New message".

![event_get-new-message](figure/dinosaur2/event_get-new-message.png)

- 以下の画面が表示されることを確認し、 **『新しいメッセージ名：』に『メッセージ3』と入力し** OKボタンを押してください。

  Enter "Message 3" in the "New Message Name:" field and click the OK button.

![init-screen_new-message3](figure/dinosaur2/init-screen_new-message3.png)

- 同様に **『メッセージ5を受け取ったとき』『メッセージ7を受け取ったとき』を作成** してください。

  Similarly, create "When I received message 5" and "When I received message 7".

- 『メッセージ○を受け取ったとき』のブロックが4種類できます。

  You can create 4 types of blocks for "when you receive a message".

![event_get-message1](figure/common/event_get-message1.png) , ![event_get-message3](figure/dinosaur2/event_get-message3.png) , ![event_get-message5](figure/dinosaur2/event_get-message5.png) , ![event_get-message7](figure/dinosaur2/event_get-message7.png)

- 『恐竜2の台詞の1番目』の「1」を、それぞれ **『1』、『2』、『3』、『4』と設定** してください。(数字をダブルクリックすることで、数字を編集できる状態になります。)

  Set "1" in "Dinosaur 2" to "1", "2", "3", and "4", respectively. (Double-click on the number to make it ready for editing.)

![variable_words-number1](figure/dinosaur2/variable_words-number1.png) , ![variable_words-number2](figure/dinosaur2/variable_words-number2.png) , ![variable_words-number3](figure/dinosaur2/variable_words-number3.png) , ![variable_words-number4](figure/dinosaur2/variable_words-number4.png)

- 『恐竜2のリアクション○○』の **左側の○に『2』を入れ** 、右側の○に『恐竜2の台詞の1番目』をドラッグ&ドロップしてしてください。

  Put a "2" in the left X of "Dinosaur 2's Reaction XX" and drag and drop "Dinosaur 2's first line of dialogue" in the right X.

![block_reaction2-word1](figure/dinosaur2/block_reaction2-word1.png)

- 『恐竜2のリアクション○○』の **左側の○に『3』を入れ** 、右側の○に『恐竜2の台詞の2番目』をドラッグ&ドロップしてしてください。

  Put a "3" in the left X of "Dinosaur 2's Reaction XX"" and drag and drop the "Second dialogue of Dinosaur 2" in the right X.

![block_reaction3-word2](figure/dinosaur2/block_reaction3-word2.png)

- 『恐竜2のリアクション○○』の **左側の○に『1』を入れ** 、右側の○に『恐竜2の台詞の3番目』をドラッグ&ドロップしてしてください。

  Put a "1" in the left X of "Dinosaur 2's Reaction XX" and drag and drop the "Third dialogue of Dinosaur 2" in the right X.

![block_reaction1-word3](figure/dinosaur2/block_reaction1-word3.png)

- 『恐竜2のリアクション○○』の **左側の○に『4』を入れ** 、右側の○に『恐竜2の台詞の4番目』をドラッグ&ドロップしてしてください。

  Put a "4" in the left X of "Dinosaur 2's Reaction XX" and drag and drop the "4th dialogue of Dinosaur 2" in the right X.

![block_reaction4-word4](figure/dinosaur2/block_reaction4-word4.png)

- 下記のように、それぞれブロックをくっつけてください。

  Stick each block together as shown below.

![dino2-program-2](figure/dinosaur2/dino2-program-2.png)

- これで恐竜2のプログラムは完成です。

  The Dinosaur 2 program is now complete.