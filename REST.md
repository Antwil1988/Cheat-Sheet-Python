# REST


***Representational State Transfer***
 — это архитектурный стиль взаимодействия компонентов распределённого приложения в сети

Назначение REST в том, чтобы придать проектируемой системе такие свойства как:  
- Производительность  
- Масштабируемость  
- Гибкость к изменениям  
- Отказоустойчивость   
- Простота поддержки  

***Принципы REST***
1. Клиент-серверная архитектура
концепция заключается в разделении некоторых зон ответственности: в разделении функций клиента и сервера
2. Stateless
сервер не должен хранить у себя информацию о сессии с клиентом, он должен в каждом запросе получать всю информацию для обработки
3. Кэширование
каждый ответ сервера должен иметь пометку, можно ли его кэшировать
4. Единообразие интерфейса
Hypermedia as the Engine of Application State (HATEOAS) — одно из ограничений REST, согласно которому сервер возвращает не только ресурс, но и его связи с другими ресурсами и действия, которые можно с ним совершить
5. Layered system
концепция слоистой архитектуры заключается в том, что ни клиент, ни сервер не должны знать о том, как происходит цепочка вызовов дальше своих прямых соседей
6. Code on demand
идея передачи некоторого исполняемого кода (по сути какой-то программы) от сервера клиенту