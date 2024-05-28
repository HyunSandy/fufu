RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://HyunSandy.github.io/fufu/index.html$1 [R,L]
