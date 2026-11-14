# lekalo-php-symfony

Framework-пакет Symfony для [Lekalo](https://github.com/ichinya/lekalo), подключаемый внутри процесса языкового адаптера [lekalo-php](https://github.com/ichinya/lekalo-php) через versioned provider API.

- Symfony-факты: services, routes (attributes), security voters, Doctrine storage mappings;
- переиспользует общую PHP-инфраструктуру lekalo-php без зависимости от Laravel;
- библиотечный пакет с manifest и схемами — собственный демон не требуется.

Общий план отделения — [ichinya/lekalo#241](https://github.com/ichinya/lekalo/issues/241); задача создания адаптера — [#1](https://github.com/ichinya/lekalo-php-symfony/issues/1).
