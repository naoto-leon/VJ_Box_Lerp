# Vj_Box_Lerp
Vjで使用する素材の一つ　

#### Boxモーション
![vj_box_gif](https://user-images.githubusercontent.com/43961147/62051983-91d00380-b24f-11e9-8c6f-b553a2dacde4.gif)
*** 

Keijiroさんのlaspを使わせていただき、外部からのBeatで反応するようにして、Vj時の操作負担をなるべく減らす作戦。

        var localScale = cube.localScale;
        localScale.y = (input * 0.25f) + scale;
        localScale.x = (input * 0.25f) + scale;
        localScale.z = (input * 0.25f) + scale;
        cube.localScale = localScale;


##### [keijiro/Lasp](https://github.com/keijiro/Lasp/blob/master/README.md)

