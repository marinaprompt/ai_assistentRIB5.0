# ИИ-ассистент для инвест-брокера по недвижимости

[Ссылка на проект](https//t.me/Sofiyavesta_bot)

[Ссылка на бот Веста ЗАПИСЬ на консультацию
](https://github.com/marinaprompt/ai_assistentRIB5.0/blob/main/%D0%92%D0%B5%D1%81%D1%82%D0%B0%D0%97%D0%90%D0%9F%D0%98%D0%A1%D0%AC%202025-02-27%20%D0%B2%2011.49.57.png?raw=true)
## О проекте

Этот проект представляет собой ИИ-ассистента, разработанного специально для инвест-брокеров в сфере недвижимости. Ассистент помогает брокерам эффективно взаимодействовать с клиентами, предоставляя осмысленные ответы на вопросы и автоматизируя рутинные задачи.

---

## Функционал

### 1. **Осмысленное ведение диалога**
   - Ассистент использует передовые технологии нейросетей для понимания контекста разговора и предоставления релевантных ответов.
   - Поддерживает естественный стиль общения, что делает взаимодействие с клиентами более комфортным и продуктивным.

### 2. **Ответы на вопросы по базе знаний**
   - Интегрирована база знаний, содержащая информацию о процессах покупки/продажи недвижимости, инвестиционных стратегиях, рыночных тенденциях и других важных аспектах.
   - Ассистент способен быстро находить нужную информацию и предоставлять точные ответы на вопросы клиентов.

### 3. **Запись клиента на встречу**
   - Клиент может запросить встречу через чат с ассистентом.
   - Ассистент автоматически согласует время встречи с доступностью брокера.

### 4. **Добавление встречи в Google Календарь**
   - После подтверждения времени встречи ассистент самостоятельно добавляет событие в Google Календарь брокера.
   - Клиент также получает уведомление о запланированной встрече.

### 5. **Запись клиента на встречу через бот в Telegram**
   - Реализована возможность записи на встречу через Telegram-бота.
   - Клиент может напрямую общаться с ботом, указать желаемое время встречи и получить подтверждение.
   - Бот автоматически синхронизирует данные с Google Календарём брокера.

---

## Используемые сервисы

### 1. **Qwen**
   - **Назначение**: Создание системного промпта и базы знаний.
   - **Описание**: Qwen был использован для генерации качественного системного промпта, который определяет правила поведения ассистента и структуру его ответов. Также с помощью Qwen была создана база знаний, содержащая специализированную информацию для работы в сфере недвижимости.

### 2. **Savvy (https://suvvy.ai/)**
   - **Назначение**: Платформа для создания ИИ-ассистента.
   - **Описание**: Savvy предоставляет удобный интерфейс для разработки и настройки ИИ-ассистентов. Благодаря этой платформе удалось быстро реализовать основной функционал ассистента, включая интеграцию с внешними сервисами (например, Google Календарь).

### 3. **Telegram API**
   - **Назначение**: Создание Telegram-бота для записи на встречи.
   - **Описание**: С помощью Telegram API был разработан бот, который позволяет клиентам записываться на встречи с брокером через популярный мессенджер. Бот интегрируется с основной системой ассистента и обеспечивает seamless用户体验.

---

## Преимущества решения

- **Экономия времени**: Автоматизация рутинных задач позволяет брокеру сосредоточиться на более важных аспектах работы.
- **Улучшение клиентского опыта**: Быстрые и точные ответы на вопросы, а также удобная запись на встречи через различные каналы (включая Telegram) повышают удовлетворённость клиентов.
- **Гибкость и масштабируемость**: Решение легко адаптируется под потребности конкретного брокера или компании.

---

## Как работает запись через Telegram-бот?

1. **Начало диалога**:
   - Клиент запускает бота через Telegram и выбирает опцию "Записаться на консультацию".

2. **Выбор даты и времени**:
   - Бот предлагает доступные слоты времени из календаря брокера.
   - Клиент выбирает удобное для себя время.

3. **Подтверждение встречи**:
   - После выбора времени бот отправляет запрос брокеру для подтверждения.
   - Если слот занят, бот предложит альтернативные варианты.

4. **Синхронизация с Google Календарём**:
   - После подтверждения встречи бот автоматически добавляет её в Google Календарь брокера.
   - Клиент получает уведомление с деталями встречи.

---

## Возможные направления развития

1. **Расширение базы знаний**:
   - Добавление информации о новых рыночных трендах, законодательных изменениях и инвестиционных инструментах.

2. **Интеграция с CRM-системами**:
   - Синхронизация данных между ассистентом и существующими CRM-системами для более эффективного управления клиентскими взаимодействиями.

3. **Мультиязычность**:
   - Добавление поддержки дополнительных языков для работы с международными клиентами.

4. **Аналитика и отчёты**:
   - Внедрение системы аналитики для мониторинга эффективности работы ассистента и выявления областей для улучшений.

5. **Расширение каналов коммуникации**:
   - Добавление поддержки других мессенджеров (WhatsApp, Viber, Signal) для увеличения доступности бота.

---

## Заключение

ИИ-ассистент для инвест-брокера по недвижимости — это современное решение, которое помогает оптимизировать рабочие процессы и повысить качество обслуживания клиентов. Благодаря использованию передовых технологий, таких как Qwen, Savvy и Telegram API, проект обеспечивает высокую производительность и удобство использования. Интеграция Telegram-бота делает процесс записи на встречу максимально простым и доступным для клиентов.
