# Map_xyz_tiles
https://docs.publicsectormapping.gov.scot/viaeuropa/maps/xyz-tiles

https://blog.yeshuanova.com/2018/04/implement-osm-map-tiles/

經緯度轉換：http://xshadowwolfx.blogspot.com/2017/10/osm-tile.html

-圖磚座標系統：  
使用Web麥卡托投影方法 ，以Z(zoom)、X、Y表示，(X,Y)=(0,0)從左上角開始，(X,Y)=($2^Z$ -1,$2^Z$ -1)為右下角。  

Z：表示縮放大小，數值從0~19，數值越大表示放大倍率越大。  
Z=0為涵蓋整個世界地圖( 世界地圖邊界西經180到東經180 )。  

X：表示地圖X軸，會隨著Zoom的縮放倍率變化，X值範圍從0~ $2^Z$ -1

Y：表示地圖Y軸，會隨著Zoom的縮放倍率變化，Y值範圍從0~ $2^Z$ -1。  

* Web麥卡托投影方法    
  為麥卡托投影的改良版，Web麥卡托在所有尺度都是使用球面投影進行，麥卡托投影在大比例尺中是使用橢球面投影。在全球比例尺下不會察覺，當離赤道越遠偏差越明顯。   
 
  https://zh.m.wikipedia.org/zh-hk/Web%E5%A2%A8%E5%8D%A1%E6%89%98%E6%8A%95%E5%BD%B1   

台灣圖磚範圍：  
  1. Z=6  
     X=53  Y=27  
     經度：118.125~23.75 、 緯度：    
     https://tile.openstreetmap.org/6/53/27.png
     
  2. Z=7   
     X=106、107  Y=54、55  共4個圖磚  
     經度：118.125、120.9375、123.75 、 緯度：    
     
  3. Z=8  
     X=213、214  Y=109、110、111  共6個圖磚  
     經度：119.53、120.93、122.34 、 緯度：     
  
  4. Z=9  X=
