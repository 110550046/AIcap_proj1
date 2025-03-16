# AI 畫風辨識 - Dataset

## i.	data type: 
*.jpg

## ii.	external source: 
wikiart.org

## iii.	amount and composition:
### dataset overview:
1.	total images: 2464 (部分重複)
2.	total size: 30.0MB
3.	number of classes: 5

### image composition:
1.	resolution range: Min (194x63), Max (210x840), Avg (210x247)
2.	class distribution: 
class畢卡索(24.4%)
class梵谷(20.2%)
class塞尚(16.5%)
class安迪沃荷(17.6%)
class林布蘭(21.4%)

### File Organization:
```
📂 dataset/
  ├── famous style/
  │   ├── 畢卡索_超現實主義/
  │   ├── 梵谷_後印象派/
  │   ├── 塞尚_後印象派/
  │   ├── 安迪沃荷_普普藝術/
  │   ├── 林布蘭_巴洛克主義/
  ├── portrait/
  │   ├── 畢卡索/
  │   ├── 梵谷/
  │   ├── 塞尚/
  │   ├── 安迪沃荷/
  │   ├── 林布蘭/
```

## iv.	conditions:
使用wikiart.org內建的篩選器，篩選出畫家成名的風格各300張，以及藝術家所畫的肖像畫類型的畫作106張到300張不等，挑選方法為網頁的前300張，不足300張則全部保存。

## v.	data collection process:
手動保存，部分畫作為png檔，寫了一段小程式確保每個檔案都是jpg檔。(convert_png_to_jpg.py)

## 聲明
本資料集僅用於學術研究，非商業用途，也請勿將此數據集用於商業用途。
