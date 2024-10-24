# Краткое описание
Web-ларек - одностраничное приложение. Страница состоит по факту из двух частей: шапка и лента с товарами.

## Описание шапки

Шапка состоит из двух блоков, которые разъединены по разные стороны экрана: логотип и иконка-кнопка "Корзина", на которую можно нажать.

## Описание ленты

Лента состоит из контейнейров. 
Контейнер представляет собой элемент управления, на который можно нажать, и состоит из: названия продукта, категории (софт-скилл, например), картинки продукта и стоимости в синапсах.
Если на контейнер нажали, то начинается диалог с пользователем. 
Появляется pop-up с подробной информацией о продукте с кнопкой "В корзину". 
Подробная информация о продукте включает в себя название продукта, категория продукта, цена в синапсах, картинка продукта и его описание.
При нажатии на кнопку "В корзину", товар добавляется в корзину

## Описание механики работы корзины

При нажатии иконки "Корзина" из шапки начинается диалог с пользователем об оформлении заказа. Всего 4 фазы диалога
1. Показывается список товаров, которые выбрал пользователь. Элементы списка включают в себя название продукта, цену в синапсах. Также на этом этапе можно удалить товар. Помимо списка товров, показывается суммарная стоимость всех выбюранных товаров в синапсах, а также кнопка "Офрмить", при нажати на которую происходит переход на следующую фазу.
2. Далее пользователь вводит следующие данные: выбор способа оплаты при получении/онлайн, адрес доставки. При нажатии на кнопку "Далее" происходит переход на 3-ью фазу
3. Пользователь вводит свой email и телефон. При нажатии кнопки "Оплатить", происходит валидация email и телефона
4. Pop-up об успешной оплате. После него корзина очищается
