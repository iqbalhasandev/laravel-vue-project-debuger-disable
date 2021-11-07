## About <a href="javascript:void();" target="_blank">Laravel Vue Project Debuger Disable</a>

Laravel Vue Project Debuger Disable.

## Doc:

<hr/>

- Go to your .env file then paste this code

  ```
    MIX_ENV_MODE=${APP_DEBUG}
  ```

- Go to your resource/js/app.js file and Paste this code below

  ```
  if (process.env.MIX_ENV_MODE === 'production') {
    Vue.config.devtools = false;
    Vue.config.debug = false;
    Vue.config.silent = true;
   }
  ```

## <a href="https://iqbalhasan.dev" target="_blank">iqbalhasan.dev</a> Sponsors

We would like to extend our thanks to the following sponsors for funding <a href="https://iqbalhasan.dev" target="_blank">iqbalhasan.dev</a> development. If you are interested in becoming a sponsor, please email us <a href="mailto:info@iqbalhasan.dev">info@iqbalhasan.dev</a>

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to <a href="https://iqbalhasan.dev" target="_blank">IQBAL HASAN</a> via [info@iqbalhasan.dev](mailto:info@iqbalhasan.dev). All security vulnerabilities will be promptly addressed.

## License

The iqbalhasan.dev Project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
