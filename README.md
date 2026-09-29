# Gleb Inside — пилот 0.3.1

Готовая двухстраничная сборка для пробного размещения. Само наличие этих файлов
не подтверждает публикацию сайта.

В корне: index.html, explanations/apnea/index.html, robots.txt, .nojekyll и этот README.
Загружать в GitHub нужно содержимое этой папки, сохраняя explanations/.
Публикация: Settings → Pages → Deploy from a branch → main → /(root) → Save.
.nojekyll — скрытый служебный файл без содержимого; его можно добавить в GitHub
через Add file → Create new file с именем .nojekyll и одной пустой строкой.

Сайт и содержимое публичного репозитория доступны всем. В HTML сохранён noindex:
он просит поддерживающие его поисковики не включать страницы в выдачу,
но не создаёт приватный режим. Данные пациентов в сайт не загружать.

Проверяй опубликованный адрес и прямую страницу объяснения после успешного deploy.
Условия GitHub Pages и лимиты: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
