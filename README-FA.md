# تاریخ خورشیدی

برای تبدلی تاریخ UTC به تاریخ شمسی باید مقدار تفاوت ثانیه ها را از Timestamp اصلی کم کرد که برابر با ```16193433600``` است


### PHP
```php

# get khorshidi time

function fa_time(){
  return time()-16193433600;
}

```
