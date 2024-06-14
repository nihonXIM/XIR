# XIR

## Robotics研究について
こちらにはコンピュータ科学のAIと共にロボットに関する紹介します。\
色々な産業現場や様々な状況にとって、\
そして、\
国民の安全と国防を強くにするにも活用できます。

### 家庭に手伝って少子化に対応する
* 赤ちゃんの看護するだけじゃなくて、色々な家庭の用事を補足する
### 農業の生産性と品質を高めにする。
* 24時間、状況によって管理できる。
### 産業の生産性と品質を高めにする
* 24時間、状況によって管理できる。
### 国防力を強くにする



## ロボットとAIの発展と過程
ロボットの開発するには以下のような科目が必要です。
```mermaid
flowchart LR
    
    Painting
    subgraph Telecommunication
        WIRL(Wireless)
        SAT(Satellite)
        INT(Internet)
        SER(Server)
        NET(Network)
    end

    MEC --> MOT
    MET --> MEC
    MOT --> SMO
    ELE --> CIRC
    CHIP --> SMO
    CIRC --> CHIP
    subgraph Computer Science
        AI(AI)
        PL(Programming Languages)
        NP(Network Programming)
        SI(Simulation)
    end
    PL --> SI
    PL --> AI
    PL --> NP

    
    subgraph Robotics
        MET(Machining)
        MEC(Mechanics)
        ELE(Electronics)
        CHIP(Chipsets)
        CIRC(Circuits)
        MOT(Motor)
        SMO(Servo Motor)
        subgraph 3D CAD/CAM
            DES(Design)
            DOC(Documentation)
            TOL(Tools)
            FEM(FEM)
        end
        subgraph 3D Printer
            ALM(AllMaterials)
            MAC(Machining)
            ASS(Assembly)
        end
    end
    
    subgraph Fundamentals
        SCI(Science)
        PHY(Physics)
        CHE(Chemistry)
        EE(Electrics)
        EMW([ElectroMagnetic Wave])
        PHY([Physics])
        
        CHE --> EE
        SCI --> EMW
        SCI --> PHY
    end

```
* [Telecommunication](Telecom.md)
* [Painting](Painting.md)
* [Machining](Machining.md)
* [Simulation](Simulation.md)

## ロボットの発展にAIを利用する

### AIで新しいエアコンの原理の生成
エアコンの原理は科学者が発見した一つの方法しかないのか\
AIに新しいエアコンの原理を発見させてもらったら、\
いい結果が出ることもおかしいことはないだと思います。

### AIで新しいロボットの構造の生成

### AIでエネルギーは最小化させて、効率は最大化させて
色々な部品の形を作り方


### General Robotics Diagram
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

![Movie_002.gif](Movie_002.gif)
![Movie_003.gif](Movie_003.gif)
![Movie_007.gif](Movie_007.gif)

シミュレーションの結果でまたはシミュレーションで動くことも可能です。

現場の位置とシミュレーション環境の位置(Rotation, Coordination, Etc)を同期化したら、

一度、事前にシミュレーションして問題を解決して行う事も可能です。

PhysicsとJoint情報として活用する方法なので、モーターの詳細調整もできると思います。

### GRID SYSTEM & AUTO PAIRING
無人ドロンや飛行機などで

いくつかの機器は

端末(TERMINAL)として、サーバー(SERVER)として役割を果たします。

増幅器を付けたら、通信の可能範囲を広げることも可能です。


### REMOTE PAIRING & MODULE UPDATE & CHARGE SYSTEM
バッテリーが切れる前に他のバッテリーを持つ無人飛行機で

バッテリーを提供する事も可能だと思います。

他のMODULEで交換するのも。。。

### 空間のシミュレーション

#### Water Simulation
深い海に移動する魚を作り方法はどのようにしたらいいと思いますか


#### Air Simulation
水のような空気の空間を仮想の空間に設計しても、ファンーの翼を回転するようにします。
オブジェクトに当てたら物理的に回転てきます。


#### AIが設計するように


#### 動物の模様にどのような特徴がありますか?
魚、鳥、昆虫
