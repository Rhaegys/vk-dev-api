# vk-dev-api

Ссылка на [Mind-map](https://mm.tt/1660363187?t=Y3WKRcIZqc)  
Переработанная [Mind-map](https://mm.tt/1660582570?t=DdxukM6vJz)

В тестовых реквестах Postman в Tests указаны схемы положительных ответов, схемы респонсов с ошибкой не валидируются  
Сделано это потому что из ТЗ не было понятно что именно надо валидировать - то что реквест был НЕ верным, или что он был неверным правильно (т.е. респонс с ошибкой пришел такой, как ожидался). Можно и так и так делать, вопрос в концепции проверки, остановился на том, что валидируется против правильной схемы ответа, и любой ответ с ошибкой считается фейлом, без валидации респонса с ошибкой на предмет правильного респонса с ошибкой на данный запрос


