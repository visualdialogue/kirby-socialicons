# Kirby Social

This plugin provides facebook, twitter, and instagram icons and allows quick customization of links via the site.yml?

### Composer

```
composer require visualdialogue/kirby-social
```
<!-- 
****

## Commerical Usage

This plugin is free but if you use it in a commercial project please consider to
- [make a donation 🍻](https://paypal.me/hashandsalt?locale.x=en_GB) or
- [buy a Kirby license using this affiliate link](https://a.paddle.com/v2/click/1129/36141?link=1170)

****
 -->

## Usage

1. @import the plugin stylesheet into your sass file.

```
@import "site/plugins/social-icons/assets/css/social-icons.scss";
```

1. Set the three social media links in your `site/config/config.php`. When these exist, the icons will show.

```
'visualdialogue.social.facebook-url' => 'https://www.facebook.com/.../',
'visualdialogue.social.instagram-url' => 'https://www.instagram.com/.../',
'visualdialogue.social.twitter-url' => 'https://twitter.com/...',
```

2. Add the snippet to your site.

```
<?php snippet('social-icons') ?>
```