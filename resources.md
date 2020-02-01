# Ресурсы

* [Компоненты IdentityServer4 для ASP.NET Core 3.0 | Официальные продукты и услуги для IdentityServer](https://www.identityserver.com/articles/identityserver4-components-for-aspnet-core-30?__cf_chl_jschl_tk__=871e8163d4d2357c04e3e1e35fa847cc509f4251-1579988275-0-Ae4NUurGGS5NEce3BjnMkAsl8Pvoqpi1n87geENwlRZhH7nC1ZeIhci7o94fLg1jhxs8V1-DkmDyoHjFBHUp7uHh3Pnl-rhnK2NxESy5hVSbnmOyS_wumYCGSrMwauDaA5FsDTWtRkWbGDRJnZD4oaJSdDs-MKqmHwQ4Iko4WpW1EeLX1krAZ8SS1M4iP9uW35mcr8PYcd6TSXrQdk1TgeOAYo2u9MQIQYVPzmjkhp-OWcF5Bh6BMfhZUgkbZuuPbalSSqrvUBCoMzmaV2_sjCsYgse0meg-jMYxWJwR_cZsJRl8CF1E28-wrHELXBbLsSDhzf_cksaYE1Ek8ZQGpFTJ-QSXV36sirHEwraXrw-zGUOl5gtCHzSqliuV4oPF7lMKLvjBMSknPPQiLgwf-d8)

* [Добро пожаловать в IdentityServer4 (последняя версия) - документация по IdentityServer4 1.0.0](http://docs.identityserver.io/en/latest/)

* [Имплементация OpenId Connect в ASP.NET Core при помощи IdentityServer4 и oidc-client / Хабр](https://habr.com/ru/post/337784/)

* [ASP.NET Identity | Использование OpenID и OAuth](https://professorweb.ru/my/ASP_NET/identity/level1/1_10.php)

* [Реализация OAuth 2.0 и OpenID Connect в C # (Authlete)](https://medium.com/@darutk/oauth-2-0-and-openid-connect-implementation-in-c-authlete-8a8f9efc9361)

* [Иллюстрированное руководство по OAuth и OpenID Connect / Блог компании Флант / Хабр](https://habr.com/ru/company/flant/blog/475942/)

* [Авторизация доступа к веб-приложениям с помощью OpenID Connect Connect & Azure AD | Microsoft Docs](https://docs.microsoft.com/ru-ru/azure/active-directory/develop/v1-protocols-openid-connect-code)

* [OpenID Connect 1.0 На Пальцах / Хабр](https://habr.com/ru/post/422765/)

* [Разница между OpenID и OAuth](https://softwaremaniacs.org/blog/2011/07/14/openid-oauth-difference/)

* [OpenID — Википедия](https://ru.m.wikipedia.org/wiki/OpenID)

* [Введение в OAuth 2 | DigitalOcean](https://www.digitalocean.com/community/tutorials/oauth-2-ru)

* [Аутентификация и авторизация в микросервисных приложениях / Блог компании DataArt / Хабр](https://habr.com/ru/company/dataart/blog/311376/)

* [Как сервер аутентификации взаимодействует с другими серверами и устройством пользователя? — Хабр Q&A](https://qna.habr.com/q/535576)

* [Сервер аутентификации Blitz Identity Provider. Единый вход, SSO, двухфакторная аутентификация.](https://identityblitz.ru/products/blitz-identity-provider/)

* [Как объединить авторизацию на нескольких доменах? — Хабр Q&A](https://qna.habr.com/q/436413)

Можно почитать мнения в комментариях к вопросу. Хорошее предложение - использовать сервис для доступа к домену авторизации.

* [Как установить одинаковые куки на разных доменах - Subin's Blog](https://subinsb.com/set-same-cookie-on-different-domains/)

2014г. Через тег IMG вместо картинки, вызывается страница другого сервера для установки куков. Этот способ использует Google и др.

* [Межсайтовая авторизация 2 / Хабр](https://habr.com/ru/post/80900/)

2010г. 
Через общую базу и шифрование токенов в url

* [Межсайтовая авторизация (SSO) / Хабр](https://habr.com/ru/post/64002/)

2009г. 

Вариант 1:
Алгоритм, построен на ридеректах, шифровании параметров url и куках авторизации.
Из плюсов хочу заметить что все работает с использованием обычного протокола HTTP без применения дополнительных технологий.
Минус достаточно большой и связан с авторизацией по куки: если у пользователя отключены куки или к нам зашел робот то начинается кошмар: на каждый его запрос будет 3 редиректа + создаваться новая сессия.

Вариант 2:
Через однопиксельную псевдокартинку, все домены должны знать друг друга

