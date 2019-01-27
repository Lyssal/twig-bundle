# The templates for the flash messages


## Foundation 6

```twig
{%- include '@LyssalTwig/MessagesFlash/foundation_6.html.twig' -%}
```

Message types are:

* success
* warning
* alert (or error)
* secondary (or info)


## Foundation 5

```twig
{%- include '@LyssalTwig/MessagesFlash/foundation_5.html.twig' -%}
```

Message types are:

* success
* warning
* info
* alert (or error)
* secondary


## Bootstrap 3

```twig
{%- include '@LyssalTwig/MessagesFlash/bootstrap_3.html.twig' -%}
```

Message types are:

* success
* info
* warning
* danger (or error)


## Translations

If you want to translate your messages, add the suffix `_translated` :

```twig
{%- include '@LyssalTwig/MessagesFlash/bootstrap_3_translated.html.twig' -%}
```
