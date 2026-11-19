|Этап	|Тип события	|Название события  |
|-------|---------------|------------------|
|Заказ создан        	|domain	    |OrderCreated |
|Товары зарезервированы	|domain  	|InventoryReserved |
|Ошибка резервирования	|failure	|InventoryReserveFailed |
|Оплата прошла                       	|domain	      |PaymentSucceeded|
|Ошибка оплаты                      	|failure	  |PaymentFailed|
|Заказ подтверждён                   	|domain	      |OrderConfirmed|
|Заявка на доставку создана           	|domain       |DeliveryScheduled|
|Ошибка создания доставки	            |failure	  |DeliveryScheduleFailed|
|Возврат средств (компенсация оплаты)	|compensation |RefundSucceeded|
|Освобождение резерва (компенсация резервирования)	|compensation	|InventoryReleased|
|Заказ отменён (финальное состояние)	|domain	      |OrderCancelled|
