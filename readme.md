#Eclipse Code Templates
Let's share code templates for PHP and HTML!
Pull requests are also welcome for other languages.

##How to install
###PHP Templates
Go to `Eclipse -> Preferences -> PHP -> Editor -> Templates -> Import`

###HTML Templates
Go to `Eclipse -> Web -> HTML Files -> Editor -> Templates -> Import`

Note: To use an HTML template you should first `cmd + space` (`ctrl + space` for windows).


##Templates

###PHP
`pf`

```php
public function ${function_name}(${params}) {
	${body}
}
```

`psf`

```php
public static function ${function_name}(${params}) {
	${body}
}
```

###PHP in HTML views
Those templates are available only editing the HTML view.

`echo`

```php
<?= $$${var} ?>
```

`if`

```php
<? if (${expression}): ?>
	${cursor}
<? endif; ?>
```

`each`

```php
<? foreach ($$${array} as $$${value}): ?>
	${cursor}
<? endforeach; ?>
```


###HTML
`link css`

```html
<link href="${href}" rel="stylesheet" type="text/css" />
${cursor}
```
