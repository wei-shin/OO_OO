# 0624098 江維欣

## 0624098 江維欣

### 0624098 江維欣

#### 0624098 江維欣

##### 0624098 江維欣

[高科大](https://www.nkust.edu.tw/index.php)

##### 小組成員:
* **學號0624076 姓名:賴炳維:smile:**
* 學號0624032 姓名:黃偉傑 :smile:
* 學號0624058 姓名:陳宗順 :smile:
* 學號0624098 姓名:江維欣 :smile:

|學號|姓名|
|:------|:-------:|
|0624076|賴炳維|
|0624032|黃偉傑|
|0624058|陳宗順|
|0624098|江維欣|

[![Everything Is AWESOME](https://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")

public class CTriangle extends CShape{
  protected double x,y,z;
  public CTriangle(double x, double y, double z){
    this.x = x;
    this.y = y;
    this.z = z;
  }
  public void show(){
    System.out.print("color="+color+", ");
    System.out.println("area="+ 0.5*x*y);
  }
}

public abstract class CShape{
  protected String color;
  public void setColor(String str)
  {
    color=str;
  }
  public abstract void show();
}

public class main{
  public static void main(String[] args){
    CShape shape = new CTriangle(3,4,5);
    shape.setColor("red");
    shape.show();
  }
}
