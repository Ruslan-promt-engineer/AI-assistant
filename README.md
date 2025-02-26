![Иллюстрация к проекту](https://github.com/Ruslan-promt-engineer/AI-assistant/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%20%D0%B0%D1%81%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BD%D1%82%D0%B0%20%D0%B2%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B5%202.jpg?raw=true))

![Иллюстрация к проекту](https://github.com/Ruslan-promt-engineer/AI-assistant/blob/main/%D1%81%D0%BA%D1%80%D0%B8%D0%BD%20%D0%B0%D1%81%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BD%D1%82%D0%B0%20%D0%B2%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B5.jpg?raw=true))

[Наш ИИ-ассистент][@KFSservis_bot]

# ИИ-ассистент для компании по установке окон и продаже фурнитуры

## О проекте

Этот проект представляет собой интеллектуального ассистента, созданного специально для компаний, занимающихся установкой окон и продажей фурнитуры. Ассистент помогает автоматизировать процесс общения с клиентами, предоставляя точные ответы на вопросы, записывая клиентов на замеры, подбирая подходящую продукцию и оформляя заказы. Данный ассистент работает через телеграм.

---

## Функционал

### 1. **Осмысленное ведение диалога**
   - Используется нейросетевая технология для понимания контекста разговора и генерации осмысленных ответов.
   - Ассистент способен поддерживать естественный диалог, адаптируясь к стилю общения клиента.

### 2. **Ответы на вопросы по базе знаний**
   - Интегрирована база знаний, содержащая информацию о продукции, услугах, ценах и условиях работы компании.
   - Клиенты могут получить подробные ответы на часто задаваемые вопросы (FAQ).

### 3. **Запись клиента на замер**
   - Ассистент может забронировать удобное время для замера у клиента.
   - После записи данные автоматически добавляются в Google Календарь, обеспечивая синхронизацию расписания между сотрудниками компании.

### 4. **Поиск подходящей продукции и оформление заказа**
   - На основе запросов клиента ассистент предлагает оптимальные решения по выбору окон и фурнитуры.
   - Возможность оформления заказа через чат, что значительно упрощает процесс покупки.

---

## Использованные технологии и сервисы

### 1. **Qwen**
   - **Системный промпт**: Создан с помощью Qwen для настройки поведения ассистента и его адаптации под специфику бизнеса.
   - **База знаний**: Сформирована с использованием возможностей Qwen для хранения информации о продукции, услугах и политике компании.

### 2. **Savvy (https://suvvy.ai/)**
   - Платформа для создания и управления ИИ-ассистентами.
   - Обеспечивает простой интерфейс для настройки функционала, интеграции с внешними сервисами и аналитики взаимодействий с клиентами.

---

## Преимущества использования ассистента

- **Экономия времени**: Автоматизация рутинных задач позволяет сотрудникам сосредоточиться на более важных аспектах работы.
- **Повышение эффективности**: Быстрое и точное обслуживание клиентов увеличивает их удовлетворенность и лояльность.
- **Широкие возможности масштабирования**: Ассистент может работать одновременно с множеством клиентов без потери качества обслуживания.

---

## Как это работает

1. **Настройка ассистента**:
   - Подготовка системного промпта и базы знаний с помощью Qwen.
   - Конфигурация функционала через платформу Savvy.

2. **Интеграция с сервисами**:
   - Подключение к Google Календарю для записи на замеры.
   - Синхронизация с внутренними системами компании для оформления заказов.

3. **Общение с клиентами**:
   - Клиент обращается к ассистенту через чат или голосовой канал.
   - Ассистент анализирует запрос, предоставляет информацию из базы знаний, записывает на замер или помогает выбрать продукцию.

---

## Примеры использования

### Сценарий 1: Ответ на вопрос
**Клиент**: "Какие типы окон вы предлагаете?"  
**Ассистент**: "Мы предлагаем пластиковые и деревянные окна различных размеров и конфигураций. Для офисных помещений также доступны раздвижные системы. Хотите узнать больше о конкретной модели?"

### Сценарий 2: Запись на замер
**Клиент**: "Можно записаться на замер?"  
**Ассистент**: "Конечно! Когда вам будет удобно? Доступные слоты: 10:00, 14:00, 16:00."  
**Клиент**: "Выбираю 14:00."  
**Ассистент**: "Вы записаны на замер в 14:00. Напоминание придет за день до встречи."

### Сценарий 3: Выбор продукции
**Клиент**: "Нужна фурнитура для пластикового окна."  
**Ассистент**: "Для пластиковых окон мы рекомендуем комплект фурнитуры ProLine. Он включает петли, ручки и запорные механизмы высокого качества. Стоимость — 5000 рублей. Хотите оформить заказ?"

---

## Технические требования

- **Язык программирования**: Python (для настройки интеграций).
- **API**: Google Calendar API для записи на замеры.
- **Хостинг**: Работает через облачную инфраструктуру Savvy.

---

## Будущие планы развития

- Расширение базы знаний за счет дополнительной информации о продукции и услугах.
- Добавление многоканальной коммуникации (WhatsApp, Telegram, телефон).
- Внедрение системы аналитики для отслеживания эффективности работы ассистента.

---

## Контакты

Если у вас есть вопросы или предложения по сотрудничеству, свяжитесь с нами:

- Email: 7340104@gmail.com
- telegram: @Rus_Neo81

---

## Лицензия

Проект распространяется под лицензией MIT. Подробнее см. файл [LICENSE](LICENSE).
