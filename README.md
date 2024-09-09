# Organize-flac
透過腳本進行.flac以及.lrc的分類任務 將flac以及lrc同個檔名歸類同一個資料夾

1.將變數 directory 設定為你想要處理的資料夾路徑，例：'/home/user/documents'。

2.將變數 ffmpeg_path 設定為你的ffmpeg路徑，例：'C:\ffmpeg-7.0.2-full_build\bin\ffmpeg.exe'。

3.執行程式 記得先安裝python

4.!!!!!如果有故障後果自負，請警慎使用，最好獨立用個資料夾先測試是否可運行!!!!!

5.這個腳本是用來整理零散的flac以及lrc專用


[注意事項]
1.請一定要去下載ffmpeg否則無法執行
https://www.gyan.dev/ffmpeg/builds/
選擇ffmpeg-6.1.1-full_build.7z 那個6.1.1是版本 
下載完成解壓縮找到/bin 把那串目錄複製到ffmpeg_path 記得加入ffmpeg.exe



2.如果要把腳本分開需要使用以下範例
修改directory = './子目錄'
