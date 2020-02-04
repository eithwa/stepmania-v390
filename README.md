# 編輯器增進功能
[STEPMANIA 3.9 編輯器我流版](https://forum.gamer.com.tw/C.php?bsn=16862&snA=1184)  
1. BPM與STOP顯示最小可到小數點第三位  
2. 右上方BEAT與時間顯示可到小數點第六位(特殊用)  
3. 箭頭間距拉伸變更成以0.5倍為單位，範圍可到0.25x~8x  
   若想整數拉伸可用ctrl+pageup與ctrl+pagedown鍵控制  
4. STEP停拍可以變負數  
5. 增加N鍵直接轉換負數功能，直接按N鍵會建立一個BPM標籤  
   CTRL+N會直接轉換BPM為負數，ALT+N會直接轉換STOP為負數  
6. 支援192nd箭頭編輯  
7. 增加直接編輯BPM與STOP功能  
//===8以後code缺失需要重寫=====  
8. (完成) 修正使用AUTOPLAY會崩潰的問題  
9. (完成) 可追朔以前的備份  
   (編輯的歌曲資料夾會多個FileBackup資料夾，並以時間戳記為檔案名稱)  
10. (完成) 自動儲存  
    (可選擇你要儲存的時間間隔，也可以關閉，預設自動儲存時間是5分鐘)  
11. (完成) Reverse逆流編輯環境下可直覺操作  
    (PlayerOption的Reverse選項開下去就知道了)  
12. (完成) Reverse逆流編輯直覺操作性可在Preferences下的Reverse Control Intuitive更改  
13. (完成) 增加DisplayBPM編輯，可在Edit Song Info下找到

# 另外增加  
+ hold結尾改為TNS_MARVELOUS(白光)不確定是否影響分數
+ 影片速度根據取速改變
+ editor 影片預覽撥放位置修正
+ option 語言ini紀錄儲存
+ editor 變速結尾bpm錯誤修正
+ editor 變速長條截斷修正
+ 0203editor 變速切換難度 紀錄bug修改
+ 0203editor 多段變速bpm修正
+ 0203editor 多難度停拍位置修正
+ 0203editor 測試前緩衝調整選項(Preferences->play mode beats buffer)
+ 0204option選預設charater

# TODO
+ hold結尾判定
+ 打擊軌道背板
+ (完成) editor 測試前緩衝調整選項(Preferences->play mode beats buffer)
+ (完成) editor 變速長條截斷修正
+ (完成) editor 變速結尾bpm錯誤修正
+ (完成) editor 多段變速bpm修正
+ (完成) editor 變速切換難度 紀錄bug修改([stream_rate0.5->back from song_option or player_option]=behind level note skewed)SONGMAN->Cleanup(); ignore
+ (完成) editor 多難度停拍位置修正
+ 連線模式聊天輸入中文
+ 連線模式檔案傳送
+ (完成) option選預設charater
+ 連線模式 傳送血條變化圖
+ (完成) option 語言ini紀錄儲存
+ (完成) editor 影片預覽撥放位置修正
+ (完成) 影片速度根據取速改變
