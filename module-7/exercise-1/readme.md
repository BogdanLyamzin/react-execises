### Задание

Возьмите код из задания "module-6/exercise-3" и переделайте его так:
- при добавлении товара в корзину должен отправляться POST запрос по адресу `https://62becfba0bc9b125615fd0f7.mockapi.io/api/carts`;
- при удалении - DELETE запрос по адресу `https://62becfba0bc9b125615fd0f7.mockapi.io/api/carts/:id`;
- для получения всех товаров из корзины отправьте GET запрос по адресу `https://62becfba0bc9b125615fd0f7.mockapi.io/api/carts`;
- одинаковые товары в корзину добавлять нельзя;
- все запросы выполняйте в Redux, actions создавайте с помощью `createAction`, а reducer - `createReducer`;
