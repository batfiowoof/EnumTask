📖 Описание

Програмата симулира система за резервация на билети за пътуване с функционалности за създаване, промяна на статус и преглед на резервацията.

🎯 Цели на задачата

Да се разберат основите на използването на enum в C#.

Да се идентифицират и поправят логически и синтактични грешки.

Да се подобри умението за четене и разбиране на чужд код.

🛠️ Изисквания

Типове билети: Economy, Business, FirstClass

Статус на резервацията: Pending, Confirmed, Cancelled

⚠️ Задачи за учениците

Програмата съдържа следните грешки, които трябва да бъдат коригирани:

Неправилно зададена опция за изход в менюто.

Липсва проверка за невалидни входни данни при въвеждане на статус.

Имената на опциите в менюто не съвпадат с очакваните.

🔍 Примерен вход и изход

Изберете опция:
1. Създай резервация
2. Промени статуса
3. Показване на резервацията
4. Изход

> 1
Въведете име на пътника: Иван Иванов
Изберете тип билет (Economy, Business, FirstClass): Business
Резервацията е създадена успешно със статус Pending.

> 2
Изберете нов статус (Pending, Confirmed, Cancelled): Confirmed
Статусът е променен успешно.

> 3
Резервация:
Иван Иванов - Business - Confirmed

> 4
Програмата приключи.

💡 

Използвайте Enum.TryParse за проверка на валидността на въведените стойности.

Прегледайте внимателно логиката на менюто и проверете за несъответствия.

Тествайте с различни входни данни за откриване на грешки.
