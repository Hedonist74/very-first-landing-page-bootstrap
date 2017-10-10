Практикую ReadMe
---------------

Базовая Структура:
===========
```html
<div class="header navbar-fixed-top">...</div>
<div class="main">
    <div class="inner">...</div>
    <div class="about-us default-section">...</div>
    <div class="services default-section  border-top">...</div>
    <div class="lets-talk black-bg">...</div>
    <div class="portfolio default-section">...</div>
    <div class="start-project small-section black-bg text-center ">...</div>
    <div class="why-choose-us default-section ">...</div>
    <div class="reviews default-section ">...</div>
    <div class="latest-news default-section ">...</div>
    <div class="stay-informed small-section grey-bg text-center ">...</div>
    <div class="contact default-section">...</div>
    <div class="map">...</div>
</div>
<div class="footer">...</div>
<div class="anchor-up">...</div>
```

Основные Default Components:
================

  * .main - Родительский баг фикс бокового отступа от карусельной стрелки
  * .default-section - Главные отступы для контейнеров
  * .title - Основные заголовки
  * .title-small - Маленькие заголовки (..Why Choose Us, Footer)
  * .title-grey - Серый заголовок (..Stay Informed)
  * .. и так далее

Контрольные Точки:
-----------------------------

|Кому|max-width|
|:-------------|:-----:|
|.text-section p|767|
|.latest-news .btn-xs|991|
|.header, #header-nav, .container-fluid > .navbar-collapse, .header .header-nav > li, .header-nav li + li|767|
|.inner, .inner .inner-content h6, .inner-content|991|
|.inner-content h6, .inner .rhomb-icon, .inner .rhomb-icon span.fa|767|
|.inner-content span, .inner-content h6|599|
|.inner-content h6, .inner .rhomb-icon, .inner .rhomb-icon span.fa|479|
|.about-us blockquote|991|
|.team-person|767|
|.services-tabs .tablist-title|991|
|.services-tabs .nav-tabs li|767|
|.portfolio .picture, .portfolio-tabs .nav-tabs li, .portfolio-tabs .nav-tabs li + li|767|
|.portfolio .picture|599|
|.why-choose-us .text-section-light, .why-choose-us .space-after-row + .space-after-row|991|
|.reviews .carousel-caption, .reviews .carousel-caption p|991|
|.reviews .title.text-white.text-light, .reviews .carousel-caption p|599|
|.latest-news .title span, .latest-news .heading-latest-news .sub-title|479|
|.small-section form input, .small-section .btn-dark, .small-section .form-group input.form-control, .form-group a, .form-col|767|
|.small-section .form-group input.form-control, .form-group a|479|
|.form-submit .btn.btn-dark, .form-submit, .form-submit .help-info|767|
|.contact-item-content|1199|
|.contact-item|991|
|.form-col|599|

Начиная с 16-го коммита точек @media больше чем представлено в списке выше.