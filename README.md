2020/3/10 pm 08:27 SPC

下一步->增加移動時障礙物判定 
/////////////////////////////////////////////////////////////////////////////////

2020/3/11 am 12:02 SPC

設定好map內的二維陣列 player可被MapObject阻擋

下一步->由於map呼叫所有MapObject時程式過於冗長 所以計畫編寫自定義vector

/////////////////////////////////////////////////////////////////////////////////

2020/3/11 a.m. 1:54 Asta

將game.rc內圖片路徑更改為相對路徑

下一步->如果每一次要加入一個物件至地圖都必須呼叫一次AddObject, 效率是否會有影響?

/////////////////////////////////////////////////////////////////////////////////

2020/3/11 pm 07:37 SPC

改動MapArray

下一步->將MapArray設定完畢並使用在map

/////////////////////////////////////////////////////////////////////////////////

2020/3/12 am 12:20 SPC

已設定好MapArray並成功運用在Map上

下一步->編寫Class MapFactory 來更有效的建置Map並佈署MapObject

/////////////////////////////////////////////////////////////////////////////////

2020/3/12 am 01:15 SPC

將非範例的.h檔加入 	#ifndef	#define	#endif 以後新增.h檔都要記得加	

為編寫factorye改動Map，目前要測試MapObject請到myGame加入

/////////////////////////////////////////////////////////////////////////////////

2020/3/12 am 09:25 SPC

變更Map.SetObject和Block建構元, 新增MapObject函式(LoadBitMap, SetPosition)

如果要編寫MapObject類型Class請參考Block, 並以myGame.cpp裡block的插入方法測試

注意map.SetObject要在map.LoadBitMap下方

下一步->編寫MapFactory

/////////////////////////////////////////////////////////////////////////////////

2020/3/12 pm 01:30 SPC

新增Map,MapArray解構元，更動myGame中加入MapObject方法(mygame.cpp line312~316)

新增class MapFactory

下一步->設定MapFactory

/////////////////////////////////////////////////////////////////////////////////