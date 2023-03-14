# Map_xyz_tiles
https://docs.publicsectormapping.gov.scot/viaeuropa/maps/xyz-tiles

https://blog.yeshuanova.com/2018/04/implement-osm-map-tiles/

https://wiki.openstreetmap.org/wiki/Slippy_map_tilenames#Resolution_and_Scale

# 圖磚座標系統    
使用Web麥卡托投影方法 ，以Z(zoom)、X、Y表示，(X,Y)=(0,0)從左上角開始，(X,Y)=( $2^Z$ -1, $2^Z$ -1)為右下角。  

Z：表示縮放大小，數值從0~19，數值越大表示放大倍率越大。Z=0為涵蓋整個世界地圖。  

X：表示地圖X軸，會隨著Zoom的縮放倍率變化，X值範圍從0~ $2^Z$ -1。經度範圍從-180~180。  

Y：表示地圖Y軸，會隨著Zoom的縮放倍率變化，Y值範圍從0~ $2^Z$ -1。緯度範圍從-85.05~85.05。  

* Web麥卡托投影方法    
  為麥卡托投影的改良版，Web麥卡托投影在所有尺度都是使用球面投影進行，麥卡托投影在大比例尺中是使用橢球面投影。在全球比例尺下不會察覺，當離赤道越遠偏差越明顯。  
  https://zh.m.wikipedia.org/zh-hk/Web%E5%A2%A8%E5%8D%A1%E6%89%98%E6%8A%95%E5%BD%B1  
    
* 經緯度、圖磚 轉換：http://xshadowwolfx.blogspot.com/2017/10/osm-tile.html  
 
## 台灣圖磚範圍    
  1. **Z=6**  
     **X =53**、**Y = 27**  
     經度：118.125、123.75  
     緯度：26.8、21.7   
     共1個圖磚       
     [( 53 , 27 )](https://tile.openstreetmap.org/6/53/27.png)  
     
  2. **Z=7**   
     **X = 106、107** 、 **Y =54、55**     
     經度：118.125、120.9375、123.75   
     緯度：27.0、24.4、21.8   
     共4個圖磚    
      [( 106 , 54 )](https://tile.openstreetmap.org/7/106/54.png) [( 107 , 54 )](https://tile.openstreetmap.org/7/107/54.png)  
      [( 106 , 55 )](https://tile.openstreetmap.org/7/106/55.png) [( 107 , 55 )](https://tile.openstreetmap.org/7/107/55.png)  
      
  3. **Z=8**  
     **X = 213、214**、**Y = 109、110、111**        
     經度：119.53、120.93、122.34   
     緯度：25.7、24.5、23.2、21.9  
     共6個圖磚        
     [( 213 , 109 )](https://tile.openstreetmap.org/8/213/109.png) [( 214 , 109 )](https://tile.openstreetmap.org/8/214/109.png)  
     [( 213 , 110 )](https://tile.openstreetmap.org/8/213/110.png) [( 214 , 110 )](https://tile.openstreetmap.org/8/214/110.png)  
     [( 213 , 111 )](https://tile.openstreetmap.org/8/213/111.png) [( 214 , 111 )](https://tile.openstreetmap.org/8/214/111.png)  
     
  4. **Z=9**    
     **X = 427、428、429** 、 **Y = 218、219、220、221、222、223**                
     經度：120.2343、120.9375、121.64、122.34  
     緯度：25.79、25.16、24.52、23.88、23.23、22.59、21.94    
     共18個圖磚    
     [( 427 , 218 )](https://tile.openstreetmap.org/9/427/218.png) [( 428 , 218 )](https://tile.openstreetmap.org/9/428/218.png) [( 429 , 218 )](https://tile.openstreetmap.org/9/429/218.png)  
     [( 427 , 219 )](https://tile.openstreetmap.org/9/427/219.png) [( 428 , 219 )](https://tile.openstreetmap.org/9/428/219.png) [( 429 , 219 )](https://tile.openstreetmap.org/9/429/219.png)  
     [( 427 , 220 )](https://tile.openstreetmap.org/9/427/220.png) [( 428 , 220 )](https://tile.openstreetmap.org/9/428/220.png) [( 429 , 220 )](https://tile.openstreetmap.org/9/429/220.png)  
     [( 427 , 221 )](https://tile.openstreetmap.org/9/427/221.png) [( 428 , 221 )](https://tile.openstreetmap.org/9/428/221.png) [( 429 , 221 )](https://tile.openstreetmap.org/9/429/221.png)  
     [( 427 , 222 )](https://tile.openstreetmap.org/9/427/222.png) [( 428 , 222 )](https://tile.openstreetmap.org/9/428/222.png) [( 429 , 222 )](https://tile.openstreetmap.org/9/429/222.png)  
     [( 427 , 223 )](https://tile.openstreetmap.org/9/427/223.png) [( 428 , 223 )](https://tile.openstreetmap.org/9/428/223.png) [( 429 , 223 )](https://tile.openstreetmap.org/9/429/223.png) 
