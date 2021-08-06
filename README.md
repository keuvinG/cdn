# cdn

https://keuving.github.io/cdn/
```text
https://getbootstrap.com/docs/5.1/customize/optimize/
```
##Business/Corporate/Customer
```
Working one - need both
sass --style=compressed scss/frontend-business.scss css/frontend-business.css
postcss css/frontend-business.css --replace --use autoprefixer

or
sass --style=compressed scss/frontend-business.scss css/frontend-business.css && postcss css/frontend-business.css --replace --use autoprefixer
sass --style=compressed scss/frontend-customer.scss css/frontend-customer.css && postcss css/frontend-customer.css --replace --use autoprefixer
sass --style=compressed scss/frontend-corporate.scss css/frontend-corporate.css && postcss css/frontend-corporate.css --replace --use autoprefixer

```
