[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/UO7VGONk)
# Патерн абстрактна фабрика

Потрібно вивчити теоретичний матеріал та написати власноруч приклад коду для патерну абстрактна фабрика.
Закомітити даних приклад та зробити pull request.
Згідно власного варіанту потрібно описати потрібні класи. Додати до даних класів потрібні, на вашу думку, методи. Варіанти завдань отримати у викладача.

В README файлі навести UML діаграму класів для коду згідно власного варіанту з короткими поясненнями.
Закомітити код та зробити pull request.

**Варіант 3:**
Абстрактна фабрика для створення космічних кораблів для різних планетарних умов — студенти розробляють фабрику, яка випускає космічні кораблі з різними характеристиками, залежно від умов планети призначення (наприклад, густої атмосфери, відсутності атмосфери, високої гравітації).
#**Коротко про програмую.**#
Цей код демонструє використання шаблону проектування "Абстрактна фабрика" для створення об'єктів космічних кораблів різних типів для різних умов: густої атмосфери, без атмосфери та високої гравітації.

Клас Spaceship є абстрактним базовим класом, який містить властивість Name, яка визначає назву космічного корабля. Класи Shuttle, CargoShip та Explorer є конкретними реалізаціями космічних кораблів.

Інтерфейс ISpacecraftFactory визначає методи для створення кожного типу космічного корабля.

Класи DenseAtmosphereFactory, NoAtmosphereFactory та HighGravityFactory є конкретними фабриками, які реалізують інтерфейс ISpacecraftFactory та надають конкретні реалізації методів створення космічних кораблів для різних умов.

У методі Main програми створюються екземпляри різних фабрик, які потім використовуються для створення космічних кораблів для різних умов (густа атмосфера, без атмосфери та висока гравітація). Всі створені кораблі виводяться на консоль разом з їх назвами.



