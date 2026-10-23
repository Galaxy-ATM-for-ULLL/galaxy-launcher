<p align="center">
  <img src=".github/banner.png" alt="Galaxy ATM System" width="100%">
</p>

<h1 align="center">Лаунчер Galaxy ATM</h1>

<p align="center">
  <a href="https://github.com/Galaxy-ATM-for-ULLL/galaxy-launcher/releases/latest"><img alt="Последний выпуск" src="https://img.shields.io/github/v/release/Galaxy-ATM-for-ULLL/galaxy-launcher?style=for-the-badge&label=выпуск&color=3D5376"></a>
  <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20%7C%2011-31425E?style=for-the-badge">
  <a href="https://galaxy-atm.ru"><img alt="Сайт" src="https://img.shields.io/badge/сайт-galaxy--atm.ru-253247?style=for-the-badge"></a>
</p>

<p align="center">
  <b><a href="https://github.com/Galaxy-ATM-for-ULLL/galaxy-launcher/releases/latest">⬇ Скачать последнюю версию</a></b>
</p>

Лаунчер готовит EuroScope к работе на позициях РПИ Санкт-Петербург (ULLL) в сети VATSIM и запускает его одной кнопкой. Он сам ставит и обновляет плагин Galaxy ATM System, шрифты и сектор, так что вручную ничего копировать не нужно.

## Что умеет

- 🧩 **Плагин и шрифты** — ставит, подключает к профилям EuroScope и обновляет без переустановки
- 🗺️ **Сектор** — скачивает свежий сектор с aero-nav
- 👤 **Профили EuroScope** — находит их и настраивает под плагин
- 📰 **Новости и обновления** — показывает новости проекта и обновляется сам, без перезапуска
- 🚀 **Запуск** — проверяет, что всё на месте, и открывает EuroScope на выбранной позиции; есть режим Sweatbox
- 🌗 **Светлая и тёмная темы** в стиле сайта galaxy-atm.ru

## Установка

1. Скачайте `GalaxyLauncher-<версия>.exe` со страницы [последнего выпуска](https://github.com/Galaxy-ATM-for-ULLL/galaxy-launcher/releases/latest) или с сайта [galaxy-atm.ru](https://galaxy-atm.ru).
2. Запустите его. Установка не нужна: лаунчер — один файл, дальше он обновляется сам.
3. Пройдите регистрацию в КСА на [galaxy-atm.ru](https://galaxy-atm.ru) — без неё большинство функций плагина недоступно.

**Требования:** Windows 10 или 11, EuroScope и Microsoft Edge WebView2 Runtime (в Windows 11 он уже есть; если его нет, лаунчер сам предложит скачать).

> Windows SmartScreen может предупредить о неизвестном издателе: файл не подписан сертификатом. Чтобы убедиться, что файл не подменён, сравните его SHA-256 с указанным в описании выпуска:
> ```powershell
> Get-FileHash .\GalaxyLauncher-<версия>.exe -Algorithm SHA256
> ```

## О репозитории

Здесь публикуются только готовые выпуски лаунчера. Исходный код лаунчера, плагина и сервера ведётся в закрытых репозиториях организации [Galaxy-ATM-for-ULLL](https://github.com/Galaxy-ATM-for-ULLL).

---

<sub>Galaxy ATM System — проект для виртуальной авиации (EuroScope / VATSIM). Не предназначен для реального управления воздушным движением и не связан с организациями реальной авиации.</sub>
