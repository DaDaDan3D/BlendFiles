# BlendFiles

Blender の様々な実験をした .blend ファイルです。

## アウトライン
### xlu_outline/xlu_inverted_hull.blend
ソリッドモディファイアで拡大した面の法線を反転して重ねる方法です。
マテリアルをアルファブレンドにして、マテリアルスロットでの順番や、コレクションの順番で描画順をコントロールすることで、半透明なマテリアルにアウトラインを付けています。
![materials](https://github.com/DaDaDan3D/BlendFiles/assets/108515309/67a17687-7082-41da-8673-534e432fbfee)

### xlu_outline/xlu_outline_composite.blend
Cycles 用に、オブジェクト単位で、一定の幅のアウトラインを付けます。
F12 を押してレンダリングするとアウトラインが付いた画像が見られます。
コンポジットノードでオブジェクト ID を得て、膨張させた領域から元の領域を取り除くことでアウトラインを得ています。
![composite_settings](https://github.com/DaDaDan3D/BlendFiles/assets/108515309/2fe1401d-5bd6-4934-8b0c-e3655c0cf777)
![composite_nodes](https://github.com/DaDaDan3D/BlendFiles/assets/108515309/0ed73b13-0c90-4b2d-b0c3-b813646429ca)
![composite_image](https://github.com/DaDaDan3D/BlendFiles/assets/108515309/9939460c-4bb7-43b8-a7bd-99088e2bc587)
