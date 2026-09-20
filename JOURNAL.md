# Мой журнал изучения Git

## Неделя 0. Настройка

### Что сделал
- Установил Git 2.55 на Windows (Git Bash)
- Настроил user.name=HelmutOtto, user.email=HelmutOtto1988@protonmail.com
- Задал core.autocrlf=true (Windows), init.defaultBranch=main, core.editor=nano
- Сгенерировал SSH-ключ ed25519 без passphrase
- Добавил публичный ключ на GitHub
- Обнаружил блокировку порта 22, настроил SSH через порт 443 (~/.ssh/config)
- Проверил связь: ssh -T git@github.com → успех
- Создал песочницу ~/dev/git-lab

### Проблемы и решения
- Порт 22 заблокирован → переключил SSH на ssh.github.com:443 через ~/.ssh/config

### Что запомнить
+ Приватный ключ (~/.ssh/id_ed25519) — НИКОМУ, никогда
+ Публичный (~/.ssh/id_ed25519.pub) — можно показывать всем
+ core.autocrlf=true нужен на Windows, чтобы CRLF не ломали диффы

а что самое непонятное - непонятно )))

