# BSA00
## Роль и функции ИТ-аналитика в команде разработки ИТ-систем

### Задачи для упражнений

### Задача 1. Запись на стрижку (Sign up for a haircut) 

Руководство сети барбершопов приняло решение о внедрении системы, обеспечивающей онлайн-запись на прием. Основная цель — развитие бизнеса путем расширения клиентской базы за счет возможности онлайн-записи, а также снижение трудозатрат сотрудников и уменьшение ручного труда за счет автоматического информирования клиентов по каналам связи. 

Запись может осуществлять как зарегистрированный, так и незарегистрированный посетитель сайта. При записи можно выбрать тип услуги: парикмахерские или косметологические, а также саму услугу, мастера и время из свободных интервалов. Система должна обеспечивать автоматическую отправку напоминаний клиентам через выбранный клиентом канал связи (Telegram, WhatsApp, VK, СМС) по настроенному менеджером расписанию. После получения услуги система предлагает клиенту оценить услугу и написать предложения по улучшению работы.

Расписание мастеров и выполняемые каждым мастером услуги должен вводить менеджер, возможно, это будет не один человек. Он же отвечает за актуальность расписания и при необходимости корректирует его, осуществляет связь с клиентами в ручном режиме, проставляет отметку о выполнении услуги, начисляет и принимает оплату, передает данные об оплате в бухгалтерию. Также менеджер может получать отчеты о выполненных услугах и просматривать отзывы клиентов.

Любой мастер имеет возможность посмотреть расписание и запись на свои услуги, отзывы клиентов. 

### Задача 2. Доставка заказов (Delivery of orders) 

В локдаун многие продуктовые магазины и предприятия питания резко увеличили объемы онлайн-продаж, и потому возросла потребность в быстрой доставке мелких партий товаров индивидуальным клиентам. 

Компания студентов собрались и решила создать стартап службы доставки. 

Идея состоит в том, чтобы оперативно получать информацию о заказах, месте и сроке комплектации, месте доставки, желаемых сроках доставки и раздавать инфо курьерам, которые будут получать заказ в месте комплектации и доставлять в место доставки. Решили развернуть онлайн-систему, куда стекаются заказы и откуда курьеры оперативно разбирают заказы для выполнения. На первом этапе решили собирать заказы от магазинов и предприятий питания любым доступным способом и вводить в систему в едином формате силами оператора, но разработать мобильное приложение для курьеров. 

Курьер должен иметь возможность просматривать информацию о заказах, выбирать заказ из свободных, бронировать его, забирать в точке выдачи и доставлять клиенту. Результат своих действий курьер должен оперативно отражать в системе через мобильное приложение. Также в системе должен работать диспетчер, который контролирует курьеров и при необходимости переназначает заказы. Информация о поступивших заказах должна направляться в бухгалтерию (в другую ИТ-систему) для расчета с поставщиками заказов за доставку. Также в бухгалтерию должна направляться информация о доставке заказа, где будет производиться расчет оплаты курьеров. Начисленная оплата должна передаваться в систему и отражаться в личном кабинете курьера. И еще запланировано рабочее место администратора, регистрирующего курьеров и назначающего всем права доступа.

### Задания

### Задание 00 — Creating a workspace (Создание пространства)
**Для каждой задачи**:

1. Определи префикс продукта.
2. Создай отдельную директорию в своем GIT-репозитории в подпапке src, имя директории должно содержать префикс продукта. 

### Задание 01 — Identifying information sources (Выявление источников информации) 
**Для каждой задачи:**

1. Создай каталог источников информации. 
2. Найди не менее 5 источников информации и занеси их в каталог.
3. Укажи приоритет изучения источников информации.
4. Определи необходимые параметры каталога.
5. Укажи свои ответы в turn-in файле ex01\_<префикс продукта>\_infosources.xlsx. 

### Задание 02 — Creating and maintaining a glossary (Создание и ведение глоссария) 
**Для каждой задачи:**

1. Создай глоссарий.
2. Размести в глоссарии не менее 10 понятий.
3. Укажи свои ответы в turn-in файле ex02\_<префикс продукта>\_glossary.xlsx.

**Рекомендации по выполнению задания:**

1. В работе над проектами (здесь и далее) в качестве даты добавления понятия в глоссарий следует указывать номер проекта, выполняя который было добавлено данное понятие (Пример: BSA 00).

### Задание 03 — Concept of Decomposition (Основные понятия декомпозиции) 

1. Найди демографическую пирамиду РФ. Отрази найденную пирамиду в файле.
2. Укажи показатель разбиения демографической пирамиды.
3. Укажи цель составления демографической пирамиды.
4. Определи вид декомпозиции демографической пирамиды.
5. Укажи:
   - Сколько уровней декомпозиции у демографической пирамиды;
   - Какие это уровни;
   - Какие критерии применяются для разбиения каждого уровня.
6. Определи порядок построения демографической пирамиды.
7. Укажи свои ответы в turn-in файле ex03\_decomposition.docx.

### Задание 04 — Types of Decomposition (Виды декомпозиции) 
**Меню завтрака:** вареное яйцо, тост с маслом, сок, чай.

1. Рассмотри декомпозицию завтрака на рисунке 3:
   - Определи цель и вид декомпозиции; 
   - Укажи количество уровней декомпозиции;
   - Найди ошибки декомпозиции и перечисли их;
   - Исправь ошибки в декомпозиции и примени исправленную версию для следующего задания.
2. Разработай объектную декомпозицию завтрака на основе уточненной декомпозиции в пункте выше:
   - Укажи цель декомпозиции;
   - Построй декомпозицию до уровня 2;
   - Укажи критерии разбиения для каждого уровня построенной декомпозиции.
3. Укажи свои ответы в turn-in файле ex04\_types.docx.

*Рисунок 3. Декомпозиция завтрака*

![](images/img1.png)

**Условия:** 

Средство для изображения декомпозиции — на твое усмотрение.

### Задание 05 — Types of Decomposition (Виды декомпозиции) 
**Для задачи 2:**

1. Изучи задачу 2.
2. Разработай декомпозицию действий курьеров.
3. Определи цель и вид декомпозиции.
4. Укажи количество уровней.
5. Разработай объектную декомпозицию действующих лиц (ролей) задачи.
6. Укажи цель объектной декомпозиции.
7. Укажи количество уровней.
8. Укажи свои ответы в turn-in файле ex05\_types.docx.

### Задание 06 — Decomposition Rules (Правила декомпозиции) 
**Активности дня:**

1. Перечисли не менее 10 активностей своего дня. 
2. Определи минимум 2 цели декомпозиции, в рамках каждой цели определи пользователей и потребности.
3. Построй событийную декомпозицию активностей своего дня в соответствии с выбранной целью. Во время построения придерживайся правил декомпозиции.
4. Укажи свои ответы в turn-in файле ex06\_rules.docx.
