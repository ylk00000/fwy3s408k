# fwy3s408k
|--|[date:1090419sun]-[動作:登入-或-登出-網頁:github]
|----|with-${username}
|------|登入-github-網頁-

|--------|[入口-http://github.com]

|----------|[頁面:右上角]-[按鈕:Sign-in]

|--------|[彈出視窗:Sign-in-to-GitHub]

|----------|[填寫:${帳號}]+[填寫:${密碼}]+[按鈕:Sign-in]

|------|登出-github-網頁-

|--------|[入口-http://github.com]

|----------|[頁面:右上角]-[呃:我不知是啥圖示]

|------------|[按鈕:下拉:選單標題:Signed-in-as-${username}]

|------------|[按鈕:下拉:選單項目:Sign-out]

|--|[date:1090419sun]-[動作:repo-私有-private-改-公開-public]

|----|[登入-網頁:Github-後]

|------|[頁面:左側]-[點擊:${username}/${repository}]-[顯示為:private]

|--------|[選擇:${repo}-後]-[頁面上方-橫向選單]-[點擊-項目:Setting]

|------|[頁面:右側]-[頁面標題:Settings]

|--------|[滾動:滑鼠]-[尋找-區域:Danger-Zone]

|--------|[項目:Make-this-repository-public]-[按鈕:Make-public]

|------|[點擊-按鈕:Make-public]-

|------|[彈出-視窗-標題:Make-this-repository-public]-

|------|[輸入-${username}/${repo}]-進行確認-[按鈕:I-understand-make-this-repositoty-public]

|------|回到-[頁面標題:Settings]

|--|[date:1090419sun]-[動作:repo-刪除]

|----|[登入-網頁:Github-後]

|------|[頁面:左側]-[點擊:${username}/${repository}]

|--------|[選擇:${repo}-後]-[頁面上方-橫向選單]-[點擊-項目:Setting]

|------|[頁面:右側]-[頁面標題:Settings]

|--------|[滾動:滑鼠]-[尋找-區域:Danger-Zone]

|--------|[項目:Delete-this-repository]-[按鈕:delete-this-repository]

|------|[彈出-視窗-標題:Are-you-absolutely-sure]-

|------|[輸入-${username}/${repo}]-進行確認-[按鈕:I-understand-the-consequences-delete-this-repository]

|------|回到-[頁面標題:Create-your-first-project]-[建造第一個project]

