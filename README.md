# BlendFiles

Blender の様々な実験をした .blend ファイルです。

## アウトライン
### https://github.com/DaDaDan3D/BlendFiles/blob/main/xlu_outline/xlu_inverted_hull.blend
ソリッドモディファイアで拡大した面の法線を反転して重ねる方法です。
マテリアルをアルファブレンドにして、マテリアルスロットでの順番や、コレクションの順番で描画順をコントロールすることで、半透明なマテリアルにアウトラインを付けています。

### https://github.com/DaDaDan3D/BlendFiles/blob/main/xlu_outline/xlu_outline_composite.blend
Cycles 用に、オブジェクト単位で、一定の幅のアウトラインを付けます。
コンポジットノードでオブジェクト ID を得て、膨張させた領域から元の領域を取り除くことでアウトラインを得ています。
