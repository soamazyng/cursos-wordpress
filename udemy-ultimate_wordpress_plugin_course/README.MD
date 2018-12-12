# Gancho mais importante do plugin
> https://codex.wordpress.org/Plugin_API/Action_Reference/plugins_loaded

```php
  <?php add_action( 'plugins_loaded', 'function_name' ); ?>
```

Este gancho é disparado depois que tudo está configurado, ele é a primeira coisa a ser disparada para plugins ativos

---

> https://codex.wordpress.org/Plugin_API/Action_Reference/wp_head

```php
  <?php add_action('wp_head', 'your_function'); ?>
```

Theme Hooks para o `<head>` Você pode injetar css ou js no head do theme

---

> https://codex.wordpress.org/Plugin_API/Action_Reference/template_redirect

```php
  <?php add_action( 'template_redirect', 'my_page_template_redirect' ); ?>
```

Este hook é um redirect que é feito assim que o usuário habilita um theme

---

> https://codex.wordpress.org/Plugin_API/Action_Reference/admin_menu

```php
  <?php add_action('admin_menu', 'function_name'); ?>
```

Utilizado para alterar a estrutura do menu do admin

---
> https://codex.wordpress.org/Plugin_API/Action_Reference

Lista das ações disponíveis no wordpress

---
> https://codex.wordpress.org/Plugin_API/Filter_Reference
Lista dos filtros disponíveis no wordpress

---

> https://codex.wordpress.org/pt-br:Tipos_de_Posts_Customizados

Informações sobre os posts types

---

> https://en.support.wordpress.com/shortcodes/

Lista de shortcode wordpress

---

> https://developer.wordpress.org/plugins/

Handbook plugin