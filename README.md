# - 說明

提供給需要處理環境資料的朋友
不同單位提供的檔案格式差異很大
程式主要目的是將
逐時資料合併成一個檔案
並將資料清洗及統整

1.氣象測站資料
從大氣水文資料庫下載的測站資料
是txt檔，而且時間格式python無法讀取
裡面可以抓出自己想要的測站以及項目
stationlist = [] 放需要的測站編號 ＃第 19 行
[['PS01','PP01','TX01','RH01','WD01','WD02']] 需要的項目 ＃第 54 行
[f'PS01_{sta}', f'PP01_{sta}', f'TX01_{sta}',f'RH01_{sta}', f'WD01_{sta}', f'WD02_{sta}']  需要的項目＃第 55 & 60 行
