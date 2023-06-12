
# Создание своей локации в Unity

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/d05e27db-5bed-42b0-929e-31b35f0c2f8d)

# Приступим

Для создания локации требуется объект  `"Terrain"`. Используя его создаем неровности и горы.

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/0e016e90-6107-4152-8f45-fee6ee7b36f4)

Для редактирования местности используется кисть `"Paint Terrain"` 


Чтобы сделать местность более красивой, я скачал из [Unity Asset Store](https://assetstore.unity.com/) специальные текстуры. С помощью `"Paint Texture"` расскрасил местность.


С помощью кисти `"Paint trees"` нанес на землю скачанные ранее из [Unity Asset Store](https://assetstore.unity.com/) деревья и камни.

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/e2ad61f7-496e-4cbd-b5f0-712b38939017)


Помимо удобного и быстрого добавления элементов одного типа на terrain, этот инструмент может предложить настроить несколько аргументов:

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/f8998673-f888-4364-9b50-bbe6ce1d5f47)

На небе я разместил облака, поставил на горе домик с кузнечиком и добавил всяких объектов на пляж.

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/9ac0495b-22ec-4558-93aa-a24c2994e9cf)

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/72ff7f5b-0b18-4d6a-acc1-a28b7768c4e6)

Для того, чтобы иметь возможность погулять по локации, я добавил готовый ассет персонажа с прикрепленной камерой (Видом от первого лица)

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/3827b966-98a4-4112-a64e-5e6ff25e5651)

![Desktop 2023 06 12 - 22 23 09 02](https://github.com/NimaDosOFF/UnityProject/assets/133951460/9e5ee9bb-7baf-4d8f-a438-989849014483)

Финальным штрихом я добавил на локацию некую область, в которой на камеру персонажа будут накладываться эффекты.

![image](https://github.com/NimaDosOFF/UnityProject/assets/133951460/e52cd7da-ecb5-4024-9342-59ae27c17776)

Для этого я создал пустой объект Box Collider.
В его свойствах включил функцию "Is Trigger"
Применил компоненты "Post-Process Layer" и "Post-Process Volume"
Во втором компоненте добавил желаемые эффекты.

Готово! Теперь когда персонаж будет заходить в область нашего пустого объекта, к нему будут применяться эффекты.

![Desktop 2023 06 12 - 22 31 12 03](https://github.com/NimaDosOFF/UnityProject/assets/133951460/17d1b8f4-aa69-40a9-a31d-4946dab2503b)






