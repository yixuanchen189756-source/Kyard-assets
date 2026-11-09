# Kyard-assets

Kyard 运行时按需下载的公开资产。各模型的作者、来源、许可与改动见下表；使用 CC BY 资产时须保留署名。

## director3d-models-v2

3D 导演台写实物体模型与材质库。所有模型均经过以下改动：转换为 glb，统一为 +Y 向上、+Z 朝前与真实尺寸，烘焙网格变换并按材质合并，按部件（车轮、头尾四肢、屏幕、箱盖、座椅、云台等）切分出以转轴为原点的节点（动物改为蒙皮网格，骨骼位于关节转轴并在关节处平滑过渡权重），贴图重新压缩为不超过 1024（部分 512）像素的 JPEG。

### Poly Haven（CC0 1.0）

许可：https://polyhaven.com/license

| 文件 | Poly Haven 资产 |
| --- | --- |
| table.glb | [dining_table](https://polyhaven.com/a/dining_table) |
| roundTable.glb | [coffee_table_round_01](https://polyhaven.com/a/coffee_table_round_01) |
| chair.glb | [dining_chair_02](https://polyhaven.com/a/dining_chair_02) |
| stool.glb | [wooden_stool_01](https://polyhaven.com/a/wooden_stool_01) |
| bench.glb | [painted_wooden_bench](https://polyhaven.com/a/painted_wooden_bench) |
| sofa.glb | [sofa_02](https://polyhaven.com/a/sofa_02) |
| rock.glb | [boulder_01](https://polyhaven.com/a/boulder_01) |
| vase.glb | [ceramic_vase_01](https://polyhaven.com/a/ceramic_vase_01) |
| planter.glb | [potted_plant_01](https://polyhaven.com/a/potted_plant_01) |
| streetLamp.glb | [street_lamp_01](https://polyhaven.com/a/street_lamp_01) |
| pendantLamp.glb | [hanging_industrial_lamp](https://polyhaven.com/a/hanging_industrial_lamp) |
| bed.glb | [GothicBed_01](https://polyhaven.com/a/GothicBed_01) |
| chest.glb | [treasure_chest](https://polyhaven.com/a/treasure_chest) |
| laptop.glb | [classic_laptop](https://polyhaven.com/a/classic_laptop) |
| book.glb | [book_encyclopedia_set_01（单册）](https://polyhaven.com/a/book_encyclopedia_set_01) |
| bottle.glb | [wine_bottles_01（单瓶）](https://polyhaven.com/a/wine_bottles_01) |
| cup.glb | [tea_set_01（单只茶杯）](https://polyhaven.com/a/tea_set_01) |

`materials.glb`：写实材质库（1k 贴图：颜色、法线、粗糙度），由 Poly Haven 贴图组成：plaster=[painted_plaster_wall](https://polyhaven.com/a/painted_plaster_wall)、wood=[oak_veneer_01](https://polyhaven.com/a/oak_veneer_01)、floor=[wood_floor](https://polyhaven.com/a/wood_floor)、concrete=[concrete_floor_02](https://polyhaven.com/a/concrete_floor_02)、marble=[marble_01](https://polyhaven.com/a/marble_01)、planks=[weathered_planks](https://polyhaven.com/a/weathered_planks)、fabric=[rough_linen](https://polyhaven.com/a/rough_linen)。

### Sketchfab（经 Objaverse 收录，CC BY 4.0）

许可：https://creativecommons.org/licenses/by/4.0/ 。下列模型的原作者保留署名权，改动如上所述，原作者不对改动后的版本背书。

| 文件 | 原模型 | 作者 | 来源 |
| --- | --- | --- | --- |
| car.glb | 80s Generic midsize sedan - Low poly model | DanielZhabotinsky | https://sketchfab.com/3d-models/e2678da920cc4be68dbc193727919ffb |
| bus.glb | Karosa C734 | swifterik | https://sketchfab.com/3d-models/21262813724e401b88333d381c4626f7 |
| truck.glb | French delivery van | DanielZhabotinsky | https://sketchfab.com/3d-models/a350a422d200485ea57778dc42139edc |
| bicycle.glb | retro bicycle | korovnikov-vladislav | https://sketchfab.com/3d-models/89fe9b1ca558441b93975fb715044530 |
| motorcycle.glb | Classic Motorcycle | MoraAzul | https://sketchfab.com/3d-models/4b76c94d593b4dc297d91c5c545193da |
| horse.glb | Horse | tungpv90 | https://sketchfab.com/3d-models/29a679df4a014b55a9476b520b430895 |
| deer.glb | Little Buck 2.0 | thecaitasaurus | https://sketchfab.com/3d-models/339b8902625e4f458882aeb764ecfb0c |
| dog.glb | Dog | Tim0 | https://sketchfab.com/3d-models/a89b49b3d9c647a8805d8d5287f47f48 |
| cat.glb | Miniature cat | thesidekick | https://sketchfab.com/3d-models/7aabffe566ef462db6d1cd6a6dd46345 |
| fox.glb | Fox-rigged | freddy1231 | https://sketchfab.com/3d-models/b8a7c0e7778741568dd3d4ad80a01249 |
| rabbit.glb | Bunny | yellokab | https://sketchfab.com/3d-models/4cc18d8e0552459b8897948b81cb20ad |
| bird.glb | Crow | zixisun51 | https://sketchfab.com/3d-models/45a169ef98804f06a9b7a4af1a04d6f9 |
| fish.glb | Fish | yimit | https://sketchfab.com/3d-models/c4328d6c1ae445198abc1a3d4c1e2570 |
| palmTree.glb | Palm Tree | Swanoff | https://sketchfab.com/3d-models/b9922dd105ee4536b9ca983c26f58e66 |
| pineTree.glb | Blue spruce | RosticOstafi | https://sketchfab.com/3d-models/f2e8b0f630624e0ea0744057ea5ec560 |
| tree.glb | Tree For Games | dangry | https://sketchfab.com/3d-models/f91d3c3c527d47fdb217c291e4c7df4b |
| trafficCone.glb | Traffic / road cone | krolzuzannapl | https://sketchfab.com/3d-models/87e57a593d684dc4a6dfd70e598b1cef |
| officeChair.glb | Office Chair | FangedAnteater | https://sketchfab.com/3d-models/db03012c3c484314a480b4137da8eb30 |
| rug.glb | Persian Tabriz Pictorial Carpet | mfb64 | https://sketchfab.com/3d-models/0ce2fc1e54724cb79cbb08ab2182760a |
| counter.glb | Counter | gorzi90 | https://sketchfab.com/3d-models/47e1be52888640f89ab6dd8eeb008b35 |
| floorLamp.glb | PBR Floor Lamp (Free Download) | Justin.Foley | https://sketchfab.com/3d-models/083c9408b89949d8b201e8a1bb6ce41c |
| monitor.glb | Wide Monitor Model 1 | Naudaff3D | https://sketchfab.com/3d-models/0178dfc498eb4593891a491fa2469ede |
| softbox.glb | Simple Studio Light | AleixoAlonso | https://sketchfab.com/3d-models/771d351d2329444fab348909ebfd160b |
| cameraRig.glb | Camera Tripod Slik 38T4 | Cymen05 | https://sketchfab.com/3d-models/bd4c17d17c394c688cea2294bafc7594 |
| cameraRig.glb | Cinema Camera | re1monsen | https://sketchfab.com/3d-models/e1fec87c8ae0487f964d20de2559aa62 |

`cameraRig.glb` 由两件模型组合（脚架与摄影机），并去除了摄影机原有的地面圆盘。

## director3d-models-v1

早期版本，仅含 11 个 Poly Haven CC0 模型（table、roundTable、chair、stool、bench、sofa、rock、vase、planter、streetLamp、pendantLamp）原样打包，已由 v2 取代。
