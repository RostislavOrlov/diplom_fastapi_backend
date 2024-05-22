Клиентская часть дипломной работы «Микросервисы организации онлайн-конференций». Стек: клиентская часть – HTML, CSS, CSS Flexbox, Vue JS, WebRTC, Websocket; серверная часть – Java, Spring, Spring Cloud Gateway, Python, Django, FastAPI, Golang, Gin, Websocket, gRPC, PostgreSQL, Redis. Реализован следующий функционал. В разработанном приложении представляются возможности работы с командами, чатами и конференциями. Имеется регистрация и авторизация. Пользователи могут создавать команды, вступать в них, добавлять новых участников. Далее, администраторы команд имеют возможность менять роли участников, что позволяет разграничивать права доступа для команд. Приложение позволяет создавать, изменять, удалять посты и получать их список, а также создавать, изменять и удалять комментарии к постам. Имеется возможность управлять участниками команд (получение списка участников, добавление и удаление), а также работать с ожидающими запросами. Ожидающие запросы представляют из себя запросы от пользователей, которые хотят вступить в определенную команду. Приложение обеспечивает следующие возможности для работы с чатами: получение списка чатов для пользователя, создание чата, добавление пользователя в чат по его электронной почте, отправка сообщений, получение списка сообщений чата, отслеживание статуса того, что сообщение прочитано собеседником, редактирование сообщение в режиме реального времени (Websocket). Обмен медиапотоками по технологии WebRTC. Код клиентской части: https://github.com/RostislavOrlov/diplom_client_vue_js
 Код остальной серверной части пока что не выложен на Github, но имеется отчёт по проделанной работе.
