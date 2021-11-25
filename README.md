nginx-install
===============

### Использование
1. Скопируйте репозиторий:
    ```sh
    $ git clone https://github.com/havelockz/nginx-install.git
    ```

2. Загрузите модули:
   ```sh
   $ ./install-module.sh <module>
   ```

     Параметр `<module>` должен быть заменём с параметрами, которые представлены ниже в списке.

3. Применить изминения
   1. Создать директорию `patches` :
  	  ```sh
      $ mkdir -p patches
      ```
   2. Поместить все патчи в директории `patches` :

4. Установить!
   ```sh
   $ sudo ./install-nginx.sh <version>
   ```

   Параметр `<version>` должен быть заменён с актуальной версией nginx, которую Вы хотите скачать и установить. Например, `$ sudo ./install-nginx 1.5.10` скачает и установит **nginx 1.5.10** на Ваш сервер.

### Список модулей доступных к установке

- **ngx_brotli** ~ Google https://github.com/google/ngx_brotli/
- **ngx_cache_purge** ~ FRiCKLE https://github.com/FRiCKLE/ngx_cache_purge/
- **ngx_devel_kit** ~ simpl https://github.com/simpl/ngx_devel_kit/
- **ngx_drizzle** ~ chaoslawful https://github.com/chaoslawful/drizzle-nginx-module/
- **ngx_echo** ~ agentzh https://github.com/agentzh/echo-nginx-module/
- **ngx_ench_memcache** ~ bpaquet https://github.com/bpaquet/ngx_http_enhanced_memcached_module/
- **ngx_headers_more** ~ openresty https://github.com/openresty/headers-more-nginx-module/
- **ngx_memc** ~ agentzh https://github.com/agentzh/memc-nginx-module/
- **ngx_mod_zip** ~ evanmiller https://github.com/evanmiller/mod_zip/
- **ngx_mongo** ~ simpl https://github.com/simpl/ngx_mongo/
- **ngx_postgres** ~ FRiCKLE https://github.com/FRiCKLE/ngx_postgres/
- **ngx_redis2** ~ agentzh https://github.com/agentzh/redis2-nginx-module/
- **ngx_rtmp** ~ arut https://github.com/arut/nginx-rtmp-module/
- **ngx_set_misc** ~ agentzh https://github.com/agentzh/set-misc-nginx-module/
- **ngx_sphinx2_search** ~ reeteshranjan https://github.com/reeteshranjan/sphinx2-nginx-module/
