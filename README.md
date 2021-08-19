# Victorian Coronavirus exposure sites RSS feed

[Live](https://vicexposurerss.kivikakk.ee).

Designed to be run on cron:

```
*/30 * * * *  sh -c 'cd /usr/home/kameliya/www/vicexposurerss; bundle exec ruby fetch'
```

Data fetched and displayed is copyright © State Government of Victoria.

Code (such as it is) is MIT licensed.
