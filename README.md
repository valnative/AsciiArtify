# DevOps та Kubernetes. Практичний інтенсив
## Модуль 4. Основи Kubernetes
### Завдання на перевірку

Після успішного завершення PoC команда «AsciiArtify» готова перейти до розгортання MVP.

MVP є мінімальним продуктом з основними функціями, необхідними для того, щоб перевірити продукт на фокус-групі користувачів. На цьому етапі розробники додають додаткові функції, фіксять баги та вдосконалюють продукт на основі отриманого від користувачів фідбеку.

З боку DevOps для цього потрібно створити додаток у ArgoCD, який буде відслідковувати Git репозиторій продукту https://github.com/den-vasyliev/go-demo-app та налаштувати автоматичну синхронізацію.

Після успішного налаштування ArgoCD можна запустити повний цикл, щоб продемонструвати, як ArgoCD автоматично відслідковує та синхронізує зміни з Git репозиторію та розгортає їх на Kubernetes кластері.

Результатом завдання буде коротке демо у репозиторії проєкту, що демонструє як працює додаток, розгорнутий за допомогою налаштованої вами інфраструктурі. 

Приклад налаштувань можна знайти у відео Coding Session. 

Відповіддю на завдання буде посилання на репозиторій AsciiArtify з вбудованим демо, що демонструє роботу продукту на розгорнутій вами інфраструктурі (Файл doc/MVP.md у форматі Markdown, гілка main)
