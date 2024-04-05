---
layout: home

hero:
  name: "Plasmo Voice"
  text: "Мод на голосовой чат в Minecraft"
  # tagline: ""
  image:
    src: /logo512.png
    alt: Plasmo Voice
  actions:
    - theme: brand
      text: Открыть документацию
      link: /ru/docs/
    - theme: alt
      text: Поддержка в дискорде
      link: https://discord.com/invite/uueEqzwCJJ
---

<div class="vp-doc">

## Доступен для Paper, Fabric, Forge, Bungee, и Velocity
Paper, Fabric и Forge сервера совместимы с клиентами Fabric и Forge одновременно.

Для работы голосового чата игрокам необходимо установить Fabric или Forge мод на клиенте. Игроки без мода всё еще могут присоединяться и играть как обычно

![](/landing/compatability-chart.png)

*Предполагается, что Plasmo Voice установлен как на клиенте, так и на сервере*

## Особенности

![](/landing/hud-icons.png)

![](/landing/player-icons.png)

![](/landing/voice-settings.png)

<img src="/landing/visualise-distance.gif" width="1280px" />

<img src="/landing/rbm-scroll.gif" width="1280px" />

## Возможности мода

- **Шумоподавление RNNoise.**
- **Звуковой движок OpenAL, отличное позиционирование звука.**
- **Поддерджка [Sound Physics Remastered](https://modrinth.com/mod/sound-physics-remastered) с аддоном [pv-addon-soundphysics](https://modrinth.com/mod/pv-addon-soundphysics).**
- **Менять расстояние голосового чата.**
- **Дополнительная опциональная звукоизоляция.** Приглушает звук, если на пути стоят блоки.
- **Выбор устройств вывода и ввода.**
- **Выбор между Push to Talk и активацией голосом.**
- **Дополнительные источники.** Звук становится тише, если источник не направлен непосредственно на вас.
- **Выбор позиции значков GUI и переключение видимости значков игроков.**
- **Мут и изменение громкости игроков в социальном меню Minecraft.**
- **Удерживайте `ПКМ`, глядя на игрока, а затем используйте колёсико мыши для изменения громкости.**
- **Поддержка Стерео.**
- **Оверлей в стиле Discord.**
- **Плавные регуляторы громкости.**

![](/landing/keybindings.png)

Проверьте настройки мода, нажав `V`. Убедитесь, что выбраны нужные устройства и работает микрофон.

## Возможности плагина

- **Кодек Opus.** Высокое качество и низкий расход трафика.
- **Настраиваемое расстояние голоса.**
- **Серверный мут с помощью команд**
- **Возможность автоматического кика игроков, у которых не установлен клиентский мод.**
- **Настройка прав.**
- **Голосовой чат работает и в одиночной игре при использовании функции Open to LAN.**
- **Поддержка PlaceholderAPI.**
- **Поддержка плагинов на Vanish.**
- **Поддержка Bungee и Velocity.**
- **Продвинутое API.**
- **Шифрование.**

## Серверные аддоны

Универсальные аддоны работают на Fabric, Forge и Paper.

Также прочтите: [Типы аддонов](https://plasmovoice.com/ru/docs/addons/types)

| Иконка                                                                                      | Ссылка                                                                         | Описание                                                                                                                                                                                                                                                                   |
|---------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [![](https://i.imgur.com/mKJDsiC.png)](https://modrinth.com/mod/pv-addon-groups/)           | [pv-addon-groups](https://modrinth.com/plugin/pv-addon-groups)                 | Создавайте групповые каналы голосового чата. Общайтесь с игроками на расстоянии.                                                                                                                                                                                           |
| [![](https://i.imgur.com/enqKs5d.png)](https://modrinth.com/mod/pv-addon-sculk)             | [pv-addon-sculk](https://modrinth.com/mod/pv-addon-sculk)                      | С помощью этого аддона скалк-сенсоры и варден будут реагировать на разговоры в голосовом чате.                                                                                                                                                                           |
| [![](https://i.imgur.com/DZU7wrI.png)](https://modrinth.com/mod/pv-addon-broadcast)         | [pv-addon-broadcast](https://modrinth.com/mod/pv-addon-broadcast)              | Транслируйте свой голос всем игрокам в радиусе, мире, сервере или прокси.                                                                                                                                                                                               |
| [![](https://i.imgur.com/tI24pN7.png)](https://modrinth.com/plugin/pv-addon-spectator)      | [pv-addon-spectator](https://modrinth.com/plugin/pv-addon-spectator)           | С помощью этого аддона все игроки могут слышать наблюдателей.                                                                                                                                                                                                           |
| [![](https://i.imgur.com/qswCndF.png)](https://modrinth.com/mod/pv-addon-whisper/)          | [pv-addon-whisper](https://modrinth.com/mod/pv-addon-whisper/)                 | По умолчанию шёпот равен половине текущего расстояния голоса. Вы можете изменить процент в конфигурации.                                                                                                                                                                   |
| [![](https://i.imgur.com/lRQ0ZEY.png)](https://modrinth.com/mod/pv-addon-priority/)         | [pv-addon-priority](https://modrinth.com/mod/pv-addon-priority/)               | Трансляция голоса с большим и настраиваемым расстоянием.                                                                                                                                                                                                                   |
| [![](https://i.imgur.com/GNfK81A.png)](https://modrinth.com/plugin/pv-addon-lavaplayer-lib) | [pv-addon-lavaplayer-lib](https://modrinth.com/plugin/pv-addon-lavaplayer-lib) | Аддон с форком библиотеки LavaPlayer, необходимой для некоторых аддонов Plasmo Voice                                                                                                                                                                                        |
| [![](https://i.imgur.com/LB320On.png)](https://modrinth.com/plugin/pv-addon-discs)          | [pv-addon-discs](https://modrinth.com/plugin/pv-addon-discs)                   | Воспроизводите аудио из Youtube и других источников в Minecraft с помощью музыкальных дисков. <br/> Аддон может воспроизводить звук из различных источников вместо того, чтобы сохранять аудиофайлы на сервере. Он даже поддерживает прямые трансляции с YouTube и Twitch. |

## Клиентские аддоны

| Иконка                                                                                    | Ссылка                                                                      | Описание                                                                                                                      |
|-----------------------------------------------------------------------------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| [![](https://i.imgur.com/NjGmgGA.png)](https://modrinth.com/mod/pv-addon-soundphysics/) | [pv-addon-sound-physics](https://modrinth.com/mod/pv-addon-soundphysics/) | Добавляет совместимость с модом Sound Physics Remastered. <br/> С этим дополнением на Plasmo Voice будет влиять мод Sound Physics. |
| [![](https://i.imgur.com/VTndchu.png)](https://modrinth.com/mod/pv-addon-replaymod/)    | [pv-addon-replaymod](https://modrinth.com/mod/pv-addon-replaymod/)        | Форк Replay Voice Chat, который работает с Plasmo Voice, позволяющий записывать голосовой чат с помощью ReplayMod.                       |

## Скачать

- [Plasmo Voice на Modrinth](https://modrinth.com/mod/plasmo-voice)
- [Релизы на GitHub](https://github.com/plasmoapp/plasmo-voice/releases/)

## Документация
- [Документация](https://plasmovoice.com/ru/docs/)

## bStats

[![](https://bstats.org/signatures/bukkit/plasmovoice.svg)](https://bstats.org/plugin/bukkit/PlasmoVoice/10928)

## Авторство
- Создано для [Plasmo](https://rp.plo.su)

</div>
