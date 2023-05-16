# 1. я, как юзер, создаю свою оценку
1. [авторизация, регистрация с помощью oauth и логин/пароль](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=605-11411&t=lutcolinooqkctp0-0)

2. выход пользователя

3. [отправка списка вопросов с ответами от пользователей](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=595-10831&t=lutcolinooqkctp0-0)

4. [отправка списка пользователей которых мы можем попросить об оценке](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=657-15388&t=lutcolinooqkctp0-0)

5. [фильтрация и отправка пользователей с ролью admin или пм чтобы назначить их на роль mentor или lead](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=657-18402&t=jweoc9nz6cjbjihz-0)


6. [cоздание записи оценки с назначенными пользователями](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=657-18402&t=jweoc9nz6cjbjihz-0)

# 2. я, как юзер, оцениваю своих коллег
1. [сохранение формы в draft](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=928-22205&t=jweoc9nz6cjbjihz-0)

2. [отправка списка вопросов](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-23686&t=yfxsfufolcmxbtcs-0)

3. [отправка пользователей у которых юзер оставил ревью](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=595-11878&t=jv021tjreopqlmv4-0)

4. [сохранение в бд на ревью ответа пользователя ](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-23389&t=yfxsfufolcmxbtcs-0)

# 3. я, как лид и/или ментор, просматриваю чужие оценки (тех, кто поделился со мной? или кто прикреплён ко мне?)

1. [отправка пользоватлей которым админ назначил ревью](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=592-10676&t=jweoc9nz6cjbjihz-0)

2. Расширенная оценка
    1. [версия 1](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-24708&t=yfxsfufolcmxbtcs-0)

    2. [версия 2](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=812-25121&t=yfxsfufolcmxbtcs-0)
    * фильтрация пользователей и отправка отдельно тех кто оставил отзыв и тех кто не оставил
    * отправка вопросов
    * отправка ответов пользователей прошедших опрос


# 4. я, как лид и/или ментор, создаю шаблон
1. [cоздание шаблона заданного лидом](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-12436&t=jweoc9nz6cjbjihz-0)

2. [отправляем созданные шаблоны](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-12869&t=yfxsfufolcmxbtcs-0)

3. [отправляем созданные шаблоны](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-12372&t=yfxsfufolcmxbtcs-0)

4. [отправка ползьователей которых мы можем попросить об оценке](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-12372&t=yfxsfufolcmxbtcs-0)

5. [фильтрация и отправка пользователей с ролью admin или пм чтобы назначить их на роль mentor или lead](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-12372&t=yfxsfufolcmxbtcs-0)

6. [рассылаем форму с вопросами пользователям на оценку](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=613-12372&t=yfxsfufolcmxbtcs-0)

# 5. я, как админ, создаю пользователя
1. [отправка всех пользователей](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=948-20148&t=yfxsfufolcmxbtcs-0)

2. [приглашение в компанию по ссылке](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=488-9483&t=yfxsfufolcmxbtcs-0)

3. [изменение информации о пользователе](https://www.figma.com/file/kqtf0dgtconxs7y4tvwjkr/assessment?type=design&node-id=488-9483&t=yfxsfufolcmxbtcs-0)




# Mодели:
## 1. Mодель шаблона
* название шаблона
* вопросы -> модель-вопроса(onetomany)
```
множественный выбор вопросов в дроп на фронте
```

## 2. Mодель вопроса
* вопрос
* описание вопроса
* ответа на вопрос

## Модель ответа
* Вопрос -> Модель вопроса()
* Draft(Bool) 

## 3. Модель пользователя:
* имя
* никнейм
* почта
* баланс пособия
* роль(choice) hr || employee
* статус(choice) active || suspended
* 3 пермишена - ползьователь, админ, пм

## 4. Mодель оценки
* шаблон(choice) -> [onetoone](#модель-шаблона)
* о каком пользователе собираем информацию -> [onetoone](#модель-пользователя)
* кому отправить(multiplechoice) -> [onetomany](#модель-пользователя)
* mentor -> [onetoone](#модель-пользователя) c пермишеном admin
* lead -> [onetoone](#модель-пользователя) c пермишеном admin


