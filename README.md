# Исходный для стримов Яндекс.Железо

## Как скачать
Установить `repo-tool`: https://gerrit.googlesource.com/git-repo/+/refs/heads/master/README.md#install

Инициализировать репозиторий:

    repo init -u git@github.com:ya-streams/manifest.git -b season02
    # -b <BRANCH> - выбрать ветку манифеста

Скачать исходники для выбранной ветки:
    
    repo sync -c 

## Как собрать
[Инструкция по сборке](https://github.com/ya-streams/buildroot_external/blob/master/README.md#%D0%BA%D0%B0%D0%BA-%D1%81%D0%BE%D0%B1%D1%80%D0%B0%D1%82%D1%8C-%D0%BF%D1%80%D0%BE%D1%88%D0%B8%D0%B2%D0%BA%D1%83)

## Полезные ссылки про `repo`
Как установить: 


Как использовать:
- https://source.android.com/setup/develop/repo 
- https://source.android.com/setup/create/coding-tasks

Про формат манифестов:
- https://gerrit.googlesource.com/git-repo/+/refs/heads/master/docs/manifest-format.md
