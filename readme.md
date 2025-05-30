# Шпаргалка по Git
## Основные команды
- **git init** - инициализировать репозиторий
```
git init
```
- **git status** - вывести статус репозитория
```
git status
```
- **git add** - добавить файл(ы) в репозиторий
```
git add <filename>
git add .
git add --all
```
- **git commit** - сохранить состояние репозитория (сделать коммит)
```
git commit -m <message>
```
- **git log** - вывести историю коммитов
```
git log
```
- **git remote add** - связать локальный репозиторий с удаленным
```
git remote add origin <link_to_remote_repo>
```
- **git remote -v** - вывести информацию об удаленном репозитории
```
git remote -v
```
- **git push** - отправить изменения на удаленный репозиторий
```
git push -u origin main *(связать локальную ветку с удаленной)*
git push
```

