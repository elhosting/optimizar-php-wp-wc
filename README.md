# optimizar-php-wp-wc

## Parametros ideales para correr php-fpm en nginx para wordpress y woocommerce
 
### PHP

- Requrimientos minimos WordPress: https://wordpress.org/about/requirements/
- Requerimientos mínimos Woo: https://woocommerce.com/document/recomendaciones-de-servidor/
- max_execution_time 180
- memory_limit 128M
- post_max_size 32M
- upload_max_filesize 32M
- max_input_vars 5000

### Caché 

- FASTCGI a nivel servidor para Ngnix 
- Plugin para gestionar purga de caché desde WP: https://es.wordpress.org/plugins/nginx-cache/ 


  
