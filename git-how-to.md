# Git how do
## Создание SSH ключ
1. На линуксе в терминале введите команду; 
ssh-keygen -t \<формат файла например ed25519\> -C \*<электронная почта>\*;
---
## Добавление SSH ключа в аккаунт на GitHub
1. Войдите на GitHub;
2. Перейдите в настройки профиля -> раздел SSH и PGP ключей;
3. Нажмите на кнопку "New SSH key";
4. Загрузите файл с публичным ключём.
---
## Клонирование репозиторий
1. Создайте пустой репозиторий на GitHub;
2. Получите его SSH ссылку;
3. Выполните в терминале команду git clone \<ссылка на репозиторий\>;
