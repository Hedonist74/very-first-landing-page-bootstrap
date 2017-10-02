Практикую ReadMe
---------------

Базовая структура
===========
```html
<div class="header navbar-fixed-top">...</div>
<div class="main">
    <div class="inner">...</div>
    <div class="about-us default-section">...</div>
    <div class="services default-section  border-top">...</div>
    <div class="lets-talk black-bg">...</div>
    <div class="portfolio">...</div>
    <div class="start-project small-section black-bg text-center ">...</div>
    <div class="why-choose-us default-section ">...</div>
    <div class="reviews default-section ">...</div>
    <div class="latest-news default-section ">...</div>
    <div class="stay-informed small-section grey-bg text-center ">...</div>
    <div class="contact default-section">...</div>
    <div class="map">...</div>
</div>
```

Основные DEFAULT COMPONENTS:
================

  * .main - Родительский баг фикс бокового отступа от карусельной стрелки
  * .default-section - Главные отступы для контейнеров
  * .title - Основные заголовки
  * .title-small - Маленькие заголовки (..Why Choose Us, Footer)
  * .title-grey - Серый заголовок (..Stay Informed)
  * ..и так далее

КОНТРОЛЬНЫЕ ТОЧКИ:
-----------------------------

|Строка|Кому|max-width|
|:-------------:|:-------------|:-----:|
|179|.text-section p|767|
|200|.latest-news .btn-xs|991|
|363|.header, #header-nav, .container-fluid > .navbar-collapse, .header .header-nav > li, .header-nav li + li|767|
|447|.inner, .inner .inner-content h6, .inner-content|991|
|461|.inner-content h6, .inner .rhomb-icon, .inner .rhomb-icon span.fa|767|
|480|.inner-content span, .inner-content h6|599|
|493|.inner-content h6, .inner .rhomb-icon, .inner .rhomb-icon span.fa|479|
|512|.about-us blockquote|991|
|547|.team-person|767|
|584|.services-tabs .tablist-title|991|
|591|.services-tabs .nav-tabs li|767|
|689|.portfolio .picture, .portfolio-tabs .nav-tabs li, .portfolio-tabs .nav-tabs li + li|767|
|702|.portfolio .picture|599|
|713|.why-choose-us .text-section-light, .why-choose-us .space-after-row + .space-after-row|991|
|826|.reviews .carousel-caption, .reviews .carousel-caption p|991|
|836|.reviews .title.text-white.text-light, .reviews .carousel-caption p|599|
|875|.latest-news .title span, .latest-news .heading-latest-news .sub-title|479|
|912|.small-section form input, .small-section .btn-dark, .small-section .form-group input.form-control, .form-group a, .form-col|767|
|930|.small-section .form-group input.form-control, .form-group a|479|
|938|.form-submit .btn.btn-dark, .form-submit, .form-submit .help-info|767|
|1006|.contact-item-content|1199|
|1013|.contact-item|991|
|1018|.form-col|599|