# Map_xyz_tiles
https://docs.publicsectormapping.gov.scot/viaeuropa/maps/xyz-tiles

https://blog.yeshuanova.com/2018/04/implement-osm-map-tiles/

經緯度轉換：http://xshadowwolfx.blogspot.com/2017/10/osm-tile.html

-圖磚座標系統：  

以Z(zoom)、X、Y表示，  
Z：表示縮放大小，數值從0~19，數值越大表示放大倍率越大。Z=0圍涵蓋整個世界地圖。

X：表示地圖X軸，會隨著Zoom的縮放倍率變化，X值範圍從0~ $2^Z$ -1

Y：表示地圖Y軸，惠歲著Zoom的縮放倍率變化，Y值範圍從0~ $2^Z$ -1。  



台灣圖磚範圍：  
  1. Z=6 X=53 Y=27  
     經度：118.125~23.75 、 緯度：    
     https://tile.openstreetmap.org/6/53/27.png
     
  2. Z=7 X=106-107 Y=53-54
     經度：118.125、120.9375、123.75 、 緯度：  
  
  3.
