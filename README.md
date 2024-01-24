# vMix_mix2-_Audiofollow
## 導入手順
  
1.右上からダウンロード。  
  
2.vMixのSettingsを選択  
  
3.Scriptingのタブを選択  
  
4.Addをクリック  
  
5.出てきたウィンドウのName欄に好きなScriptの名前を入力  
  
6.Importをクリック  
  
7.ダウンロードしてきたファイル「mix_Audio_Auto_Follow.txt」を選択  
  
8.15行目の`dim mix_number As String = ""`にmix番号を入力  
  
  例 : `dim mix_number As String = "2"`  
    
9.16行目の`dim input_keys() As String = {""}`に紐づけたいInputのKeyを入力  
  
  例 : `dim input_keys() As String = {"ff58e63c-b799-42cd-9910-ece6cdcd8954", "98094b69-89c1-4d8c-86e7-73145f818a96", "9db82233-2966-490b-a0a9-c13c58b88212"}`  
    
10.そのプロファイルのみに適応したい場合はLocal Script (This Presst Only)をチェック  
