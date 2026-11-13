# Underground Night Racer: материалы и авторы

Машины, текстуры и звуки загружаются из сети при запуске игры. Необычная техника, люди и звери лежат в папке `models/`.

## Модели машин

| Машина в игре | Исходная модель | Автор | Лицензия |
|---|---|---|---|
| Ferrari 458 | Ferrari 458 Italia, пример из three.js | vicent.lopez (vicent091036) | CC BY |
| Concept GT | CarConcept, Khronos glTF Sample Assets | Eric Chadwick, Darmstadt Graphics Group | CC BY 4.0 |
| Honda Civic Type R | Honda Civic Type R -98 (Free Asset) | tiedtke | CC BY 4.0 |
| Subaru Impreza WRX STi | Subaru Impreza WRX STi 2004 Custom | Mac CGI (MAC ULT ARTS) | CC BY 4.0 |
| BMW M3 E30 | [FREE] BMW M3 E30 | Martin Trafas | CC BY 4.0 |
| Mercedes 190E Evo II | Mercedes 190E EVO 1982 3D Model Free | Betier Models | CC BY 4.0 |
| Mustang Shelby GT500 | Ford Mustang Shelby GT500 | Jiaxing | CC BY 4.0 |
| Lamborghini Revuelto | Free Lamborghini Revuelto | ALIEEEN | CC BY 4.0 |
| Toyota Corolla (поток) | Toyota Corolla (KE80) | PHAC | CC BY 4.0 |
| Ford Focus (поток) | Ford Focus Sedan | Luquita | CC BY 4.0 |

Модели со Sketchfab взяты облегчёнными копиями (упрощённая сетка, сжатие) из репозитория
`pedrosoandre/carros`. В игре они перекрашиваются, у них анимируются колёса и детали.

## Необычная техника, люди и звери

Модели лежат в папке `models/` рядом с игрой. Взяты со Sketchfab, лицензия у всех CC BY 4.0 (нужно указывать автора).
В игре они раскладываются по узлам (колёса, руль, подвижные части), перекрашиваются и получают оружие, фары и нитро.

| В игре | Исходная модель | Автор | Ссылка |
|---|---|---|---|
| Спортбайк «Молния» | Yamaha R6 -Sportbike | AwEsZ | https://sketchfab.com/3d-models/yamaha-r6-sportbike-97cbd14896e04b538e302e609d17ce5e |
| Чоппер «Бизон» | Low-Poly Motorcycle LiFanV16 | MadCatD | https://sketchfab.com/3d-models/low-poly-motorcycle-lifanv16-a6c86b5f47ba46c4afee74a23e704af4 |
| Велосипед | Yellow bicycle | Tatyana Volk. (volkovatatyana) | https://sketchfab.com/3d-models/yellow-bicycle-4cc719f387cb4cb4aea6e12a27e06e2e |
| Велосипедист | Rigged cyclist | novusod | https://sketchfab.com/3d-models/rigged-cyclist-ff9f413898844f1d8ee7318f048b3619 |
| Гонщик на мотоциклах | race driver | BELAZ (asset_for_games) | https://sketchfab.com/3d-models/race-driver-e4e97df9865d466c8359fbb23e757308 |
| Педальная машинка | Pedal car "Strela" | hockerr102 | https://sketchfab.com/3d-models/pedal-car-strela-112908569dbc430fb2f369166f24cb8d |
| Пингвин | Penguin | Mateus Schwaab (Mehrus) | https://sketchfab.com/3d-models/penguin-2c079bc491fb4bb4942c0f87927f8d87 |
| Аист | Cigüeña blanca, animada, low poly | @x_y_es (estadisticas) | https://sketchfab.com/3d-models/ciguena-blanca-animada-low-poly-5d23f5626f324b8bb8cd634c90a8de8d |
| Леопард | Leopard Animation Run | GremorySaiyan | https://sketchfab.com/3d-models/leopard-animation-run-5a36868106f843d4a24d87334f1550fe |
| Лошадь | Horse Rigged(Game Ready) | abhayexe | https://sketchfab.com/3d-models/horse-riggedgame-ready-bc64f4ff7966474ca9bacd42fa73a754 |
| Овчарка | Stylized Low Poly German Shepherd | DreamNoms | https://sketchfab.com/3d-models/stylized-low-poly-german-shepherd-18d8fbe184c5448283762893b6ea9752 |
| Маслкар «Классик» | Classic Muscle car | Lexyc16 | https://sketchfab.com/3d-models/classic-muscle-car-641efc889e5f4543bae51d0922e6f4b3 |
| Монстр-трак | Monster Truck 3d Model | DBDIEL | https://sketchfab.com/3d-models/monster-truck-3d-model-a8fedf8df8004f97b998cca206fb6c80 |
| Болид «Формула» | ( FREE ) Formula One LP-830 SDC | SDC PERFORMANCE (3Duae) | https://sketchfab.com/3d-models/free-formula-one-lp-830-sdc-aeebdfa53e294e0390f3c2e8bbfe31b6 |
| Кубик-гонщик | Racing Car | cherryslugeater | https://sketchfab.com/3d-models/racing-car-f209f3702fc04371806054e43c496c3a |
| Кубик-ниндзя | [Project Catnip] Voxel Ninja Run | Raushen | https://sketchfab.com/3d-models/project-catnip-voxel-ninja-run-dab3f156b5dd498490c20bf21a0ded6b |

Упряжь зверей, ранец ниндзя, фонари, оружие и остальные надстройки собраны в коде игры.

## Остальное

- Текстуры, панорамы неба и реквизит: Poly Haven, CC0.
- Карта нормалей воды: three.js examples.
- Звуки двигателя, шин и ударов: pmndrs/racing-game, MIT.
- Городские здания: набор фасадных деталей сделан в Blender 5.3 скриптом `tools/blender/city_kit.py`, собственная работа проекта.
- Движок: three.js r160, MIT.
