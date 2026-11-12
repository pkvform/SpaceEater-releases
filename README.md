# SpaceEater: готовые версии

Портативное приложение для Windows: поиск дубликатов и больших файлов, проверка структуры каталогов, сбор фото и видео с телефонов и камер в общий каталог, анализ занятого места, выгрузка папок в Git.

В этом репозитории публикуются только готовые версии программы (`SpaceEater.exe`). Исходный код закрыт.

## Скачать

Последняя версия: **[Releases → Latest](https://github.com/pkvform/SpaceEater-releases/releases/latest)**. Скачайте `SpaceEater.exe` из раздела Assets.

- Windows 10 или 11, 64-разрядная. Установка и .NET не нужны: положите файл в любую папку и запустите.
- Windows SmartScreen может предупредить о неизвестном издателе (exe не подписан): «Подробнее», затем «Выполнить в любом случае».
- Контрольная сумма лежит рядом в `SpaceEater.exe.sha256`. Проверить в PowerShell: `Get-FileHash .\SpaceEater.exe -Algorithm SHA256`.

## Обновление

Программа при запуске проверяет этот репозиторий и сообщает о новой версии (отключается в «Настройках» → «Обновления»). Чтобы обновиться, закройте SpaceEater, в том числе из трея, и замените старый `SpaceEater.exe` новым. Файл `SpaceEater.settings.json` рядом с ним не трогайте: настройки сохранятся.

## Отказ от ответственности

Программа предоставляется «как есть», без каких-либо явных или подразумеваемых гарантий. Автор и правообладатель не несут ответственности за любой ущерб, включая потерю или повреждение данных, возникший в результате использования программы, невозможности её использования или её неправильной работы. Пользователь сам принимает решения об удалении, перемещении и отправке файлов и отвечает за наличие резервных копий. Используя программу, вы соглашаетесь с условиями в [LICENSE](LICENSE).

---

**SpaceEater: released builds.** Portable Windows tool for duplicate and large file search, folder structure review and photo/video import. This repository only hosts the compiled `SpaceEater.exe`; the source code is private. The program is provided "as is", without warranty of any kind; the author accepts no liability for data loss or other damage. See [LICENSE](LICENSE).

© 2026 Polianskii Konstantin
