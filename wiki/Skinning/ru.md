**Скининг** — множество способов настройки оформления и внешнего вида osu!.

Скины
-----

**Скином** называется набор элементов интерфейса. Чаще всего эти элементы объединены общей идеей и выполнены в единой стилистике (напр., оформлены в духе [какой-нибудь игры или аниме](https://osu.ppy.sh/forum/t/224323)). За время существования osu! возможности скинов и их внешний вид претерпели множество изменений: встречаются как [яркие и «тяжёлые» скины](https://osu.ppy.sh/forum/t/135588), [серьёзно играть с которыми невозможно](https://osu.ppy.sh/forum/t/36698), так и [минималистичные скины](https://osu.ppy.sh/forum/t/202277) для про-игроков, где убрано всё, что может отвлекать, а порой — даже то, что не может.

Для помощи новичкам в скининге было создано несколько гайдов, ссылки на которые проставлены выше.

Где скачать?
------------

-   [Форум, посвящённый скинам](https://osu.ppy.sh/forum/15). Содержит всё подряд: скины, над которыми ведётся работа, вопросы, полезную информацию.
-   [Готовые скины](https://osu.ppy.sh/forum/109), работа над которыми завершена.
-   Для любителей истории — [скины некоторых топ-игроков](https://osu.ppy.sh/forum/t/87675) (не обновляется с 2013 года).

Основы скининга
---------------

-   С некоторой полезной информацией можно ознакомиться здесь: [Руководство по скинингу](RU:Skinning_Tutorial "wikilink").
-   Не забудьте о [skin.ini](RU:Skin.ini "wikilink")!

Версии скинов
-------------

| Номер версии | Описание                                                                                                                                                               |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.x          | 1.0                                                                                                                                                                    |
| 2.x          | 2.0                                                                                                                                                                    |
| 2.1          | Добавлена поддержка спрайтов @2x для тайко и изменено выравнивание некоторых элементов.                                                                                |
| 2.2          | Изменены панели в списке карт. Добавлены поворачивающиеся и отмасштабированные звёзды (на замену «половинкам») и миниатюры карт. Улучшено выравнивание всех элементов. |
| 2.3          | Добавлен [маскот](wikipedia:ru:Маскот "wikilink") Catch the Beat по имени Yuzu, а также изменено поведение ловца в Catch the Beat.                                     |
| 2.4          | В osu!mania при изменени размера игрового поля под него подстраиваются: счётчик комбо, счёт, вспышки от клавиш и предупреждающие стрелки.                              |
| 2.5          | Больше возможностей скининга для osu!mania! См. [статью о skin.ini](RU:Skin.ini#.5BMania.5D "wikilink").                                                               |
| Другое       | latest                                                                                                                                                                 |
| User         | Для изменения нескольких элементов скина в личных целях.  

                -   <span style="text-decoration:underline;">**Назовите папку с изменёнными элементами *User***</span>
                -   Не указывайте эту версию при распространении своих скинов!
                -   Наличие [skin.ini](RU:Skin.ini "wikilink") не требуется.
                -   osu! будет считать, что ваш скин — самой последней версии.                                                                                                          |

Советы по скинингу
------------------

Для изображений старайтесь использовать **только формат PNG,** другие форматы могут не поддерживать прозрачность и просто-напросто удалят её при сохранении.

Старайтесь **обрезать** изображения, чтобы они не содержали лишней прозрачности и меньше нагружали компьютер при отрисовке.

При скининге ориентируйтесь на эти размеры экрана:

-   **1024×768** (4:3, стандартное разрешение, лежащее в основе osu!)
-   **2048×1536** (4:3, HD)
-   **1366×768** (16:9, стандартное широкоформатное разрешение)
-   **2732×1536** (16:9, широкоформатное HD)
-   **1920×1080** (16:9, Full HD)

Масштаб элементов будет подобран osu! автоматически с учётом выбранного разрешения экрана (элемент будет растянут и/или помещён в другое место при различных пропорциях экрана).

**Вместо всего, что не отскинено, показываются элементы стандартного скина.**

Стоит обратить внимание на **направление,** в котором указывают некоторые элемены скина, например, *reversearrow.png* или *fruit-ryuuta.png*.

### Для саппортов

![](Supporter tag.png "fig:") могут дополнительно отскинить следующие файлы:

-   *menu-background.jpg* (фон меню, единственный спрайт, который может быть в формате JPEG)
-   *triangle.png* (временно отключено; частицы, использовавшиеся при переходе между экранами игры)
-   *welcome\_text.png* (картинка-приветствие при входе в игру)
-   *seeya.wav* (голосовое прощание)
-   *welcome.wav* (голосовое приветствие)

### В чём разница между image.png и image-overlay.png?

Оверлей — это верхний слой; то, что накладывается на исходный элемент и не окрашивается.
Если Вы не уверены в том, что делаете со скином, то:

-   Для исходного элемента используйте **только** оттенки серого, чтобы получить ожидаемую окраску;
-   Сделайте оверлей частично прозрачным, чтобы через него была видна и подложка.

Пример элемента скина и его оверлея: "fruit-apple.png" и "fruit-apple-overlay.png".

HD-спрайты
----------

При достаточно большм разрешении экрана элементы скина выглядят размыто и нечётко. В связи с этим, osu! поддерживает HD-версии спрайтов и использует их при ширине экрана **от 800 пикселей**. В [файле настроек osu!](RU:User_configuration_file "wikilink") есть две опции, отвечающие за работу с HD:

-   *LowResolution = 1*: osu! будет использовать обычные элементы и игнорировать HD;
-   *HighResolution = 1*: будут использоваться HD-спрайты, обычные же версии будут показаны только при отсутствии HD.

Названия HD-спрайтов заканчиваются на @2x (*cursor**@2x**.png*), а их измерения вдвое больше обычных (напр., 256×256 у *hitcircle@2x.png* против 128×128 у его обычной версии). HD-версию имеет каждый элемент скина, в том числе состоящий из нескольких кадров.

Наборы элементов
----------------

Если Вы собираетесь добавлять скин в созданную Вами карту, следует учесть, что некоторые элементы нужно добавлять наборами. Даже если Вы отскинили всего один элемент из набора, **необходимо добавить весь набор целиком,** заменив отсутствующие спрайты стандартными. В дополнение к этому (но не вместо!) можно выбрать стандартный скин в настройках карты.

Список наборов для каждого режима игры можно узнать здесь:

-   [Стандарт](RU:Skinning_Standard "wikilink")
-   [Тайко](RU:Skinning_Taiko "wikilink")
-   [Catch the Beat](RU:Skinning_Catch_the_Beat "wikilink")
-   [osu!mania](RU:Skinning_Mania "wikilink")
-   [Интерфейс](RU:Skinning_Interface "wikilink")
-   [Звуковые файлы](RU:Skinning_Sounds "wikilink")

<Category:Editor/RU> <Category:Beatmapping/RU> <Category:Skinning/RU>
