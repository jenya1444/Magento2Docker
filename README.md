# Magento2Docker
Сборка работает если в /etc/hosts добавить :
  127.0.0.1       www.magento2.docker magento2.docker
А composer запуститься , только если внутри контейнера запустить composer install  
  
# Нужно сделать  
1) Нужно еще настроить composer
2) возможно лучше создать images (apache2 +php выделить в отдельный образ)
3) настроить  Varnish
4) hosts установить через hostname
5) сделать деплой базы через valumes ( задеплоить реальный проект)
Если с 0 ? А если проект?
