<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Laravel HCaptcha

## HCaptcha Package

composer require buzz/laravel-h-captcha

## Configuration
Add CAPTCHA_SECRET and CAPTCHA_SITEKEY to .env file:

CAPTCHA_SECRET=[secret-key]
CAPTCHA_SITEKEY=[site-key]

## Display hcaptcha

{!! HCaptcha::display() !!}


<img src="https://github.com/Parasnshah/laravel_hcaptcha/blob/master/public/hcaptcha.PNG">

Enjoy
