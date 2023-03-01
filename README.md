

**Featured**
------
- [Payme](http://payme.uz) - Merchant <img src="https://cdn.paycom.uz/documentation_assets/payme_01.png" alt="Payme" width="80"/>
- [Click](http://click.uz) - Merchant <img src="http://click.uz/wp-content/themes/click_theme/assets/img/logo.png" alt="Click" width="80"/>

**Planed**
------
- Paynet
- Upay
- Oson
- Visa
- [Uzcard](http://uzcard.uz) - Merchant <img src="http://uzcard.uz/templates/uzcard_ordinary/images/logo-f.png" alt="UZCARD" width="80"/>

## Installation

You can install the package via composer:

```bash
composer require abduvohid/paymeuz:*
```

## Usage
------
- Request handle: `PayUz::driver('payme')->redirect($model, $amount, $currency)`
- Redirect user:  `PayUz::driver('payme')->handle()`

**Exception:**
------

PaymentException 

### Testing

``` bash
composer test
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email abduvohid.mirzamahmudov@gmail.com.com instead of using the issue tracker.

## Credits

- [Abduvohid](https://github.com/Abduvohid123)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
