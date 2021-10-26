### Генерация для сервера

Для генерации сервера на Windows 10 я использовал следующую команду:

`protoc -I ecommerce ecommerce/ProductInfo.proto --go_out=plugins=grpc:<Путь к каталогу productinfo>\productinfo\service\ecommerce`

Запускать команду необходимо из каталога **service**

### Генерация для клиента

Для генерации сервера на Windows 10 я использовал следующую команду:

`protoc -I ecommerce ecommerce/ProductInfo.proto --go_out=plugins=grpc:<Путь к каталогу productinfo>\productinfo\client\ecommerce`

Запускать команду необходимо из каталога **client**