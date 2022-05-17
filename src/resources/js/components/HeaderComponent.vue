  <template>
      <div class="outline">
          <div class="container">
              <nav class="navigation">
                  <span class="title">i-Match</span>
                 <div class="menu_bar">
                      <button class="btn" id="button1">お知らせ</button><br>
                      <button class="btn btn-success" id="button2">掲示板</button><br>
                      <button class="btn btn-success" id="button3">チャット</button><br>
                      <button class="btn btn-success" id="button4">ユーザーリスト</button><br>
                      <button class="btn btn-success" id="button5">参加履歴</button><br>
                      <button class="btn btn-success" id="button6">アカウント名(仮)</button>
                  </div>
                  <div>
                      <a href="#" class="urlButton">ログアウト</a>
                  </div>
              </nav>
          </div>
      </div>
  </template>
  
  <script>
      export default {}
  </script>

  <style scoped lang="scss">
  ::v-deep .outline{
    background-color: grey;
    color: blue;
    float: left;
}
  ::v-deep .container{
      background-color: lightgreen;
  }
  
  </style>