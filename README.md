# Vshaurme
Инновационная социальная сеть для любителей лучшего блюда на свете! Вместо групп, как в большинстве социальных сетей, мы будем объединяться относительно точек продажи! Вы сможете найти новые знакомства среди людей, которые покупают еду неподалёку от вас, обмениваться отзывами о любимых сочетаниях мяса и овощей и ставить звёзды продавцам!

### Проект находится в разработке

Поэтому приветствуется любая помощь от знающих программистов! Построим социальную сеть будущего вместе!

Для того чтобы обновить код, вам достаточно сделать fork репозитория, сделать ряд изменений, запушить изменения в fork, а потом создать Pull Request с описанием проделанных изменений.

### Как помогать

Проект работает на [Django 1.11.1](https://www.djangoproject.com).
Сейчас очень нужна помощь с моделированием системы, почитать о котором можно [здесь](https://docs.djangoproject.com/en/1.11/intro/tutorial02/#craeting-models).

### Как запускать

Создайте файл local.py в папке vshaurme/settings/ и положите туда переменную `SECRET_KEY` с любым содержимым. После этого установите зависимости из requirements.txt любым удобным вам образом. Далее создайте базу данных командой ```python manage.py migrate```. Вам нужно будет повторять эту команду, если вы будете скачивать обновления нашего кода, в которых база данных будет меняться.

Затем соберите статичные файлы командой ```python manage.py collectstatic```. Вам также придётся повторять эту команду всякий раз, когда вы скачаете обновления, в которых будут изменены шаблоны проекта.

Сам сервер запускается командой ```python manage.py runserver```.

Код написан в образовательных целях на курсах для веб-разработчиков [dvmn.org](https://dvmn.org/).
