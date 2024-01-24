# vMix_mix2_and_later_Audiofollow
## 導入手順
  
1.右上のCodeからDownload Zipを選択  
  
2.ダウンロードしたZipファイルを解凍  
  
3.vMixのSettingsを選択  
  
4.Scriptingのタブを選択  
  
5.Addをクリック  
  
6.出てきたウィンドウのName欄に好きなScriptの名前を入力  
  
7.Importをクリック  
  
8.ダウンロードしてきたファイル「mix_Audio_Auto_Follow.txt」を選択  
  
9.15行目の`dim mix_number As String = ""`にmix番号を入力  
  
  例 : `dim mix_number As String = "2"`  
    
10.16行目の`dim input_keys() As String = {""}`に紐づけたいInputのKeyを入力  
  
  例 : `dim input_keys() As String = {"ff58e63c-b799-42cd-9910-ece6cdcd8954", "98094b69-89c1-4d8c-86e7-73145f818a96", "9db82233-2966-490b-a0a9-c13c58b88212"}`  
    
11.そのプロファイルのみに適応したい場合はLocal Script (This Presst Only)をチェック  

12.Saveをクリック  

13.Closeでウィンドウを閉じる  

14.先ほど決めた名前の行を選択  

15.緑色のStartをクリックしてScriptスタート  

16.Scriptを停止する場合を先ほど決めた名前の行を選択してStopをクリックで停止  
