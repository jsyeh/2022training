# 2022training
2022暑假集訓

## Processing

靜態模式寫程式

```processing
size(300,300);
background(#83E32C);
fill(#CDE32C);
rect(100,100, 150, 150);
ellipse( 100,100, 30, 60);

fill(255,0,0);
rect(150,150, 50,50);
print("Hello World\n"); 
print("12345");
textSize(30);
text("Hello", 30,30);
```

互動模式寫程式
```processing
int x=0, y=0, vx=3, vy=2;
void setup(){//設定
  size(300,300);
}
void draw(){
  background(#83E32C);
  fill(#CDE32C);
  ellipse(x, y, 30,30);
  x+=vx;
  y+=vy;
  if(x<0 || x>300) vx = -vx;
  if(y<0 || y>300) vy = -vy;
}
//rect(10,10, 30,30);互動+靜態,會出錯
```
