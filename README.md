
# PRE-COMMIT HOOK

Данный скрипт при попытке сделать коммит автоматически запускает тесты и если они возвращают ошибку, коммит не выполняется.

## Установка

Введите в терминале:

    git clone https://github.com/santax666/14_pre_commit_hook.git
    cd 14_pre_commit_hook
    mv pre-commit .git/hooks
    chmod +x .git/hooks/pre-commit

## Зависимости

Скрипт написан на языке Python 3, поэтому требует его наличия.

## Поддержка

Если у вас возникли сложности или вопросы по использованию скрипта, создайте 
[обсуждение][] в данном репозитории или напишите на электронную почту 
<IvanovVI87@gmail.com>.

[обсуждение]: https://github.com/santax666/14_pre_commit_hook/issues
