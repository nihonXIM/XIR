# XIR

## Robotics研究について
こちらにはコンピュータ科学のAIと共にロボットに関する紹介します。

色々な産業現場や様々な状況にとって、

そして、

国民の安全と国防を強くにするにも活用できます。

### Diagram
事前に3D環境でロボットを物理的にシミュレーションして、

改善したり、テストしたり活用する方法です。

IoT概念としてもあるので、

交換性やMODULE型を考えて全ての分野にも共通的に活用できるようにします。

MOTOR部分の代わりにセンサ(SENSOR)もいれます。

例えば、

ライダー(LiDAR)とカメラで収集した情報をServerに転送してOpenCVなどのComputerVisionで

認識させます。GPSなどで方向を設定して移動のルートを決定します。

移動しながら3DNavBakingやA*Pathfindingで障害物を避けて進みます。


Serverは離れている所にも設置して置く事が出来ます。

または、ロボットにも仕様がよいコンピュータを設置するのも可能です。



#### Robot Side
![img.png](img.png)

#### Client Side

![img_1.png](img_1.png)

<div><video controls src="./Movie_001.mp4" ></video></div>

