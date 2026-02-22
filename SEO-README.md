# TG STONE — SEO Оптимизация

## ✅ Выполненные работы

### 1. Meta-теги (все страницы)
- **Title** — оптимизированные заголовки с ключевыми словами
- **Description** — уникальные описания для каждой страницы (150-160 символов)
- **Keywords** — релевантные ключевые слова
- **Author** — указание автора
- **Robots** — инструкции для поисковых роботов
- **Canonical URL** — канонические ссылки
- **Language** — указание языка страницы

### 2. Open Graph (Facebook, VK, Telegram)
- `og:type` — тип контента
- `og:url` — URL страницы
- `og:title` — заголовок для соцсетей
- `og:description` — описание для соцсетей
- `og:image` — изображение для превью
- `og:locale` — локаль (ru_RU)
- `og:site_name` — название сайта

### 3. Twitter Cards
- `twitter:card` — тип карточки
- `twitter:url` — URL страницы
- `twitter:title` — заголовок
- `twitter:description` — описание
- `twitter:image` — изображение

### 4. Schema.org (Структурированные данные)

#### index.html:
- **Organization** — информация о компании
- **WebSite** — информация о сайте с поиском
- **Service** — услуги с каталогом предложений

#### panel.html:
- **SoftwareApplication** — информация о SMM-панели
- **Product** — продуктовая разметка

#### services.html:
- **ItemList** — список услуг с ценами
- **BreadcrumbList** — хлебные крошки

### 5. Технические файлы
- **sitemap.xml** — карта сайта для поисковиков
- **robots.txt** — инструкции для роботов
- **Favicon** — иконка сайта (SVG)

---

## 📋 Рекомендации по дальнейшей оптимизации

### 1. Контент (Высокий приоритет)

#### Блог / Статьи
Создайте раздел с полезными статьями:
- «Как продвигать канал в Telegram в 2025»
- «Топ-10 способов увеличить охваты в Telegram»
- «Что такое отлёжка аккаунтов и зачем она нужна»
- «Как вывести канал в топ поиска Telegram»
- «SMM-панель: что это и как использовать»

#### FAQ расширение
Добавьте больше вопросов в раздел FAQ на главной:
- Как быстро начать?
- Какие способы оплаты?
- Есть ли гарантия?
- Что делать если заказ не выполнен?

### 2. Изображения (Средний приоритет)

#### OG Image
Создайте файл `og-image.jpg` (1200×630px) и загрузите на сервер:
```
https://tgstone.ru/og-image.jpg
```

#### Логотип
Создайте `logo.png` для Schema.org:
```
https://tgstone.ru/logo.png
```

### 3. Внутренняя перелинковка (Средний приоритет)

Добавьте ссылки между страницами:
- На странице услуг → ссылка на SMM-панель
- На странице панели → ссылка на каталог услуг
- В подвале всех страниц → ссылки на все разделы

### 4. Внешние ссылки (Низкий приоритет)

Получите обратные ссылки с:
- Каталогов SMM-услуг
- Форумов о Telegram-маркетинге
- Обзорных статей о SMM-панелях
- Социальных профилей (Telegram-канал, VK)

### 5. Техническая оптимизация (Средний приоритет)

#### HTTPS
Убедитесь, что сайт работает по HTTPS:
```
https://tgstone.ru
```

#### Скорость загрузки
- Оптимизируйте изображения
- Используйте CDN для статики
- Минифицируйте CSS/JS

#### Мобильная версия
Сайт уже адаптивный — проверьте в Google Mobile-Friendly Test

### 6. Аналитика (Обязательно)

#### Google Search Console
1. Зарегистрируйтесь: https://search.google.com/search-console
2. Добавьте сайт tgstone.ru
3. Подтвердите владение (через DNS или файл)
4. Отправьте sitemap.xml

#### Яндекс.Вебмастер
1. Зарегистрируйтесь: https://webmaster.yandex.ru
2. Добавьте сайт
3. Подтвердите владение
4. Отправьте sitemap.xml

#### Google Analytics 4
```html
<!-- Добавьте в <head> всех страниц -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

#### Яндекс.Метрика
```html
<!-- Добавьте в <head> всех страниц -->
<script type="text/javascript">
   (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
   m[i].l=1*new Date();
   for (var j = 0; j < document.scripts.length; j++) {if (document.scripts[j].src === r) { return; }}
   k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
   (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");
   ym(YOUR_COUNTER_ID, "init", {
        clickmap:true,
        trackLinks:true,
        accurateTrackBounce:true,
        webvisor:true
   });
</script>
```

### 7. Локальное SEO (Дополнительно)

Если есть физический адрес, добавьте:
```json
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "TG STONE",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "...",
    "addressLocality": "...",
    "addressRegion": "...",
    "postalCode": "...",
    "addressCountry": "RU"
  },
  "telephone": "+7..."
}
```

---

## 📊 Ключевые слова (для отслеживания)

### Высокочастотные:
- продвижение в Telegram
- SMM панель
- накрутка Telegram

### Среднечастотные:
- купить подписчиков Telegram
- просмотры Telegram
- реакции Telegram
- вывод в топ поиска Telegram

### Низкочастотные:
- премиум подписчики Telegram
- автопросмотры Telegram
- инвайтинг в Telegram

---

## 🔍 Проверка SEO

Используйте эти инструменты:

1. **Google PageSpeed Insights**
   https://pagespeed.web.dev/

2. **Google Rich Results Test**
   https://search.google.com/test/rich-results

3. **Schema.org Validator**
   https://validator.schema.org/

4. **SEO Analyzer (SEMrush)**
   https://www.semrush.com/

5. **Яндекс.Вебмастер**
   https://webmaster.yandex.ru/

---

## 📞 Контакты для SEO-поддержки

Если нужна помощь с SEO — обратитесь к специалистам или используйте автоматические инструменты:
- SEMrush
- Ahrefs
- Serpstat
- Яндекс.Вордстат (для ключевых слов)

---

**Дата создания:** 15.01.2025  
**Версия:** 1.0