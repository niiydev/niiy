# niiy
 
**Софтуер за планиране на работата и автоматизиране на натоварването**

[English](../../README.md) ▪ [Русский](docs/introduction/README_ru.md) ▪ [日本語](docs/introduction/README_jp.md) ▪ [한국어](docs/introduction/README_ko.md)
 ▪ [中文](docs/introduction/README_ja.md) ▪ [Español](docs/introduction/README_es.md) ▪ [Português](docs/introduction/README_pt.md) ▪ [Italiano](docs/introduction/README_it.md)
 ▪ [Français](docs/introduction/README_fr.md) ▪ [हिन्दी](docs/introduction/README_hi.md)

---

* [Функции](#функции)
* [Архитектура](#архитектура)
* [Компоненти](#компоненти)
* [Ръководства](#ръководства)

## Функции

- Мултиплатформен
- Мултиезичен

## Архитектура

## Компоненти

### Основни компоненти

#### :small_blue_diamond: manager

Manager е административно приложение, което се грижи за управлението на целия софтуер. 

Основните функции

- Управление на задачи
- Управление на устройства
- Управление на потребители

Детайлна документация за този компонент може да намерите тук.

#### :small_blue_diamond: dispatcher

#### :small_blue_diamond: connector

#### :small_blue_diamond: monitor

### Помощни компоненти

#### :small_blue_diamond: deployer

Deployer е инструментът, който се използва за инсталиране/внедряване на платформата.

#### :small_blue_diamond: builder

Builder е помощен инструмент за изграждане на всички компоненти от изходния код.

#### :small_blue_diamond: creator

Creator е помощен инструмент, който улеснява създаването на нови типове задачи.

### Modes
<table>
  <tr>
    <td rowspan="2">Component</td>
    <td colspan="2">Mode</td>
    <td rowspan="2">Platforms</td>
  </tr>
  <tr>
    <td>GUI</td>
    <td>CLI</td>
  </tr>
    <tr>
      <td>manager</td>
      <td>:white_check_mark:</td>
            <td>:white_check_mark:</td>
                        <td>Linux, macOS, Windows, Web</td>
    </tr>
        <tr>
          <td>dispatcher</td>
          <td>:white_check_mark:</td>
                <td>:white_check_mark:</td>
                           <td>Linux, macOS, Windows</td>
        </tr>
            <tr>
              <td>connector</td>
              <td>:white_check_mark:</td>
                    <td>:white_check_mark:</td>
                                           <td>Linux, macOS, Windows</td>
            </tr>
                <tr>
                  <td>monitor</td>
                  <td>:white_check_mark:</td>
                        <td>:white_check_mark:</td>
                            <td>Linux, macOS, Windows, Web, Android, iOS</td>
                </tr>
                    <tr>
                      <td>builder</td>
                      <td>:white_check_mark:</td>
                            <td>:white_check_mark:</td>
                                <td>Linux, macOS, Windows</td>
                    </tr>
                              <tr>
                                          <td>creator</td>
                                          <td>:white_check_mark:</td>
                                                <td>:white_check_mark:</td>
                                                    <td>Linux, macOS, Windows</td>
                                        </tr>
</table>
 
## Guides

Building from source

Deployment

