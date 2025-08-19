# 直播、錄播

直播、錄播皆使用OBS Studio，功能上最全。（唯一要注意的是4小時以上容易crash，包含錄播檔也GG）OBS相關可看nutty頻道

直播規格：

碼率要看各自平台。能播1080就用1080 30/60FPS。

音頻部分，採樣率44100Hz。192k以上。

直播用CBR。

改善OBS的錄入音頻

[https://www.youtube.com/watch?v=hy_2qJHdAqE](https://www.youtube.com/watch?v=hy_2qJHdAqE)

優化OBS本身：

用 Nested Scene來導入Source便於整理和切換。

Source最好用tag在最初命名，便於排序。

轉場優化：用Add Stinger並用遮罩視頻。[https://www.youtube.com/watch?v=Tc9uL2bzPrU](https://www.youtube.com/watch?v=Tc9uL2bzPrU)

刪除plug-in：

1.有直接uninstall的選項。
2.OBS Studioのインストールフォルダ（例：C:\Program Files\obs-studio）のobs-pluginsフォルダ内、自分の使用するOBS Studioのバージョンのフォルダを開きます。アンインストールしたいプラグイン名のdll、pdb（ある場合）ファイルを削除します。

OBS新增視頻截取時宕機的原因：DirectShow錯誤導致，可將實體webcam項目拔掉重新插看看。

加特殊遮罩：

splitcam可以讀取虛擬攝像機（比如小K的或OBS的） 然後投到Snap Camera上

可用 [https://streamelements.com](https://streamelements.com/) 來增加與觀眾動作互動

OBS Virtualcam 在Tools內

- 【必】聲音分軌 - 只播放、錄製指定來源（程式、麥克風）
    
    ✦虛擬聲卡可分軌和調音 voicemeeter [https://hackmd.io/@f6bfb5/SJOUv1Dhw](https://hackmd.io/@f6bfb5/SJOUv1Dhw)
    
    ✦音軌分軌插件（可選擇只載入一個程序的音頻，直播還可以，有時候會有音損不適合錄播）win-capture-audio
    [github.com/bozbez/win-capture-audio/](http://github.com/bozbez/win-capture-audio/)
    

【必】Source Record - 只錄製指定
[https://obsproject.com/forum/resources/source-record.1285/](https://obsproject.com/forum/resources/source-record.1285/)

【必】Source Dock - 可在直播、錄製的同時開啟其他Source監控或開啟其他Scene修改。
[https://kurocha.jp/obs-source-dock](https://kurocha.jp/obs-source-dock)

【必】Transition Table - 可簡單設定的轉場特效 [https://kurocha.jp/obs-transition-table](https://kurocha.jp/obs-transition-table)

【必】Gradient Source - 可加漸層圖層（也可用來做霓虹跑馬燈邊框特效）。
[https://obsproject.com/forum/resources/gradient-source.1172/](https://obsproject.com/forum/resources/gradient-source.1172/)

【必】Move transition - 移動各種物件。
 [https://obsproject.com/forum/resources/move-transition.913/](https://obsproject.com/forum/resources/move-transition.913/)

【必】Advanced Scene Switcher - 可做很多事情……（只要滿足條件就可以做Scene切換）。
[https://kurocha.jp/obs-advanced-ss](https://kurocha.jp/obs-advanced-ss)
[https://www.youtube.com/watch?v=c0M56sAGLNI](https://www.youtube.com/watch?v=c0M56sAGLNI)

【必】Zoom and Follow（Script）  - 可放大部分區域並且追蹤滑鼠位置。
[https://www.youtube.com/watch?v=jQk7HcOpL_U](https://www.youtube.com/watch?v=jQk7HcOpL_U)

【必】Media Hide（Script） - 在一個影片或特效Source增加，播放完即隱藏。
【必】Source Switcher - 定時切換Source顯示。
[https://obsproject.com/forum/resources/source-switcher.941/](https://obsproject.com/forum/resources/source-switcher.941/)

【未研究】StreamFX - 可以做很多事。

Scale To Sound - 藉由聲音觸發圖片尺寸變化。
[https://obsproject.com/forum/resources/scale-to-sound.1336/](https://obsproject.com/forum/resources/scale-to-sound.1336/)

Image Reaction - 藉由聲音出發圖像變化等。
[https://obsproject.com/forum/resources/image-reaction.1342/](https://obsproject.com/forum/resources/image-reaction.1342/)

【未研究】Audio Monitor - 監控音頻用。

【選】Virtual Cam Filter - OBS自帶的輸出到虛擬攝像機是全畫面，這個可選擇一個來源輸出。

【選】Directory watch media - 可在播放reply時，可自動截取文件夾下篩選出的最新的內容。

【選】Source Copy - 可複製貼上Source，也可以儲存成設定檔在其他電腦開啟。

【選】Media Controls - 可以在OBS播放影片中使用播放、暫停等控制按鈕。

【選】Scene Notes Dock - 當Scene太多的時候可加，能在Note簡寫這個Scene是做什麼的、怎麼用。

【選】Scene Collection Manager - 可以管理、定期備份Scene Collection。

【選】Soundboard Dock - 可在OBS上有音效按板，但如果有外置按鈕板則不用。

【選】Source Search Helper（Script） - 可搜索某一個Source在哪幾個Scene內。

錄播

在選擇錄播檔案上，若希望斷線、Crash的時候影片還能保留則選mkv（OBS有轉換成mp4功能），若不怕此風險可選擇mp4（較好上傳）。Encode可用H264

Steam Deck

[https://www.youtube.com/watch?v=_WwnM2VgYHU](https://www.youtube.com/watch?v=_WwnM2VgYHU)

[https://www.youtube.com/watch?v=1WidFdW-yNo](https://www.youtube.com/watch?v=1WidFdW-yNo)

[https://www.youtube.com/watch?v=-JGtRaphidA](https://www.youtube.com/watch?v=-JGtRaphidA)

[https://www.youtube.com/watch?v=zPGtYT3HVkk](https://www.youtube.com/watch?v=zPGtYT3HVkk)

[https://www.youtube.com/watch?v=5PTlhMeqYvk](https://www.youtube.com/watch?v=5PTlhMeqYvk)

[https://www.youtube.com/watch?v=6eSgiowHTCc](https://www.youtube.com/watch?v=6eSgiowHTCc)

[https://www.youtube.com/watch?v=4hOzXidbMLw](https://www.youtube.com/watch?v=4hOzXidbMLw)

[https://www.youtube.com/watch?v=GhJXVKbZyH0](https://www.youtube.com/watch?v=GhJXVKbZyH0)

[https://www.youtube.com/watch?v=NuWKrpNCE1k](https://www.youtube.com/watch?v=NuWKrpNCE1k)

[https://www.youtube.com/watch?v=WUynHmAFitg](https://www.youtube.com/watch?v=WUynHmAFitg)

[https://www.youtube.com/watch?v=sMb14n0qTkQ](https://www.youtube.com/watch?v=sMb14n0qTkQ)

[https://www.youtube.com/watch?v=XD9sWOjITYU](https://www.youtube.com/watch?v=XD9sWOjITYU)

[https://www.youtube.com/watch?v=yNQHXqCJYtQ](https://www.youtube.com/watch?v=yNQHXqCJYtQ)

[https://www.youtube.com/watch?v=qgucAskxdfU](https://www.youtube.com/watch?v=qgucAskxdfU)

[https://www.youtube.com/watch?v=Wgg_7gfbfCc](https://www.youtube.com/watch?v=Wgg_7gfbfCc)

[https://www.youtube.com/watch?v=VJQs62Rry7o](https://www.youtube.com/watch?v=VJQs62Rry7o)

[https://www.youtube.com/watch?v=IWdk6hdwVPw](https://www.youtube.com/watch?v=IWdk6hdwVPw)

[https://www.youtube.com/watch?v=LJw_dw46DxA](https://www.youtube.com/watch?v=LJw_dw46DxA)

[https://kurocha.jp/obs-noobs-cmdr](https://kurocha.jp/obs-noobs-cmdr)

用來錄製how-to視頻很好用的：[https://kurocha.jp/bandicam-cursor](https://kurocha.jp/bandicam-cursor)

錄屏好用ocam

Stream Desk

要顯示Youtube Status的話要先開 [Google Developer's API Dashboard](https://console.developers.google.com/apis/dashboard)。創建新project然後將YouTube Data v3 API服務加入。在認證資料裡面新增APIkey。

Plugins

Twitch Tools
Twitch
Youtube
Discord
Youtube Channel Statstics
VtubeStudio
Spotify Integration
YouTube Music Desktop Connector
Windows Mover & Resizer
Win Tools
Advanced Launcher
SuperMacro
IFTTT
Counter
[Streamroll.io](http://streamroll.io/) Controller
Stream Counter
Stream Countdown Timer
Stopwatch
Weather
VLC Remote
Color Picker
Windows Gizmos
Text File Tools
Delayed Text Input
Focus Window
Timestamp
Emoji Picker
OBS Tools
4K Capture Utility

Minecraft Stats
Flight Tracker