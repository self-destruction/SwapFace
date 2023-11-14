# 🗿 SwapFace Colab Extended Edition

С помощью этого Google Colab блокнота ты можешь <b>в пару кликов</b> сделать дип-фейк видео. Для этого нужна YouTube-ссылка на видео и фотография лица, которое необходимо внедрить в видео. Для замены лица в [v1-блокноте](https://colab.research.google.com/github/self-destruction/SwapFace/blob/main/SwapFace_Video_Colab_Edition.ipynb) используется репозиторий [Swap-Mukham](https://github.com/harisreedhar/Swap-Mukham). Для замены лица в [v2-блокноте](https://colab.research.google.com/github/self-destruction/SwapFace/blob/main/SwapFace_Video_Colab_Edition_V2.ipynb) используется репозиторий [FaceFussion](https://github.com/facefusion/facefusion). Все возможные настройки перенесены в интерфейс Google Colab без использования Gradio.

Swap-Mukham:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/self-destruction/SwapFace/blob/main/SwapFace_Video_Colab_Edition.ipynb) - блокнот для работы с видео.  
[![Open In Colab](https://img.shields.io/badge/Open%20In-Colab-blue?logo=google-colab&logoColor=white)](https://colab.research.google.com/github/self-destruction/SwapFace/blob/main/SwapFace_Image_Colab_Edition.ipynb) - блокнот для работы с изображением.  

FaceFussion:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/self-destruction/SwapFace/blob/main/SwapFace_Video_Colab_Edition_V2.ipynb) - блокнот для работы с видео.  
[![Open In Colab](https://img.shields.io/badge/Open%20In-Colab-blue?logo=google-colab&logoColor=white)](https://colab.research.google.com/github/self-destruction/SwapFace/blob/main/SwapFace_Image_Colab_Edition_V2.ipynb) - блокнот для работы с изображением.  

## 💪 Как работает

### Установка и подготовка

Устанавливаем репозиторий, загружаем все модели, исправляем код для оптимальной работы на облачных вычислителях.

### Загрузка исходных данных

Загружаем фотографию лица, на которое мы хотем делать замену. Предоставляем ссылку на YouTube-видео, в котором будет производиться замена лиц (либо загружаем видео вручную). Можем загрузить скриншоты из видео тех лиц, которые необходимо заменять.

### Тестовый прогон

Здесь есть возможность максимально точно настроить параметры замены лиц, такие как - условия замены (возвраст, мужчины, женщины и так далее), выбрать улучшение лица после замены, выбрать отдельные регионы маски замены лица, и прочее. Также тестовый прогон позволяет не ждать обработки всего видео, а выбрать слайдером один кадр из видео и обработать только его.

### Боевой прогон

Здесь запускается замена лица на нашем видео с выбранными настройками. Есть возможность провести замену не на всём видео, а на тестовых 10 секундах. Итоговое видео может быть большим, поэтому предпросмотр в Colab позволяет вывести несколько видео по 30 секунд, также обработанное видео остаётся на Google Drive, откуда его можно быстро скачать.

## 💬 Задать вопрос
Все предложения и замечания приветствуются! Пожалуйста, используйте специальные каналы для вопросов и обсуждений. Помощь гораздо ценнее, если она предоставляется публично, чтобы ею могли воспользоваться больше людей.

| Type                            | Platforms                               |
| ------------------------------- | --------------------------------------- |
| 🚨 **Баг-репорты**              | [GitHub Трекер]                  |
| 🎁 **Feature Requests & Идеи** | [GitHub Pull Requests]                  |

[gitHub трекер]: https://github.com/self-destruction/SwapFace/issues
[github pull requests]: https://github.com/self-destruction/SwapFace/pulls

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=self-destruction/SwapFace&type=Date&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=self-destruction/SwapFace&type=Date" />
  <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=self-destruction/SwapFace&type=Date" />
</picture>

[![](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20Coffee%20for%20Morning&emoji=:☕&slug=intercross&button_colour=c69d8a&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=FFDD00)](https://ko-fi.com/intercross) &nbsp;
[![](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20Beer%20for%20the%20Night&emoji=🍺&slug=intercross&button_colour=FFDD00&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=ffffff)](https://www.buymeacoffee.com/intercross)  
