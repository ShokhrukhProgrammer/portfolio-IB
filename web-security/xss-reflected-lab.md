# 💥 Reflected XSS — PortSwigger Web Security Academy

## 🧩 Задание
Пройти лабораторию **"Reflected XSS in search function"** на платформе [PortSwigger Web Security Academy](https://portswigger.net/web-security/cross-site-scripting/reflected/lab-reflected-xss-simple).

Цель — найти и проэксплуатировать XSS-уязвимость в строке поиска веб-приложения.

---

## 🔧 Действия

1. Открыл веб-лабораторию в браузере
2. Ввёл случайные символы (`test123`), чтобы убедиться, что данные из формы отражаются на странице
3. Определил HTML-контекст (вставка прямо в тело страницы)
4. Отправил инъекцию:
```html
<script>alert(1)</script>

