1.God Object – Весь код написан в одном классе Main, который делает вообще всё: получает ввод, считает, выводит. Таким образом код сложный и запутанный.
2.Hard Code – Число 21 (fixedValue) просто прописано в коде, а не вынесено в настройки. Если его нужно будет изменить, придётся лезть в код.
3.Magic Numbers – Числа 21 и 50 встречаются в коде без объяснения, что затрудняет понимание, зачем они нужны.
4.Глобальная переменная – Переменная total объявлена вверху и доступна везде. Это плохо, потому что такие переменные могут неожиданно менять значение и сложно отлаживать код.
5.Spaghetti Code – В методе processNumbers() всё намешано: ввод, вычисления, вывод. Если нужно что-то поменять, придётся разбираться во всём этом.
6.Blind Faith – Программа никак не проверяет, что вводит пользователь. Если ввести буквы вместо числа, программа просто сломается.
7.Dependency Hell – Scanner и Random сделаны глобальными переменными, хотя их можно было передавать в методы.8.
8.Copy Paste Programming – Метод extraComputation() делает почти то же самое, что processNumbers(), но с другими именами переменных. Ненужное дублирование кода.
9.Игнор ошибок – если пользователь введёт что-то неправильно, программа просто подставит 37, но не скажет об ошибке. Это может ввести в заблуждение.
10.Lava Flow – В коде есть бесполезный if (rnd.nextInt(50) == 25), который почти никогда не срабатывает. Его можно спокойно убрать, но он остался.
