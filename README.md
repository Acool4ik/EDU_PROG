| №  | Title | HW | prerequisites
|---|---|---|---|
| 1 | [Основы архитектуры компьютера и OS](https://github.com/Acool4ik/EDU_PROG/blob/master/lessons/less1.one)  | [Работа процессора](https://youtu.be/k9wK2FThEsk?si=clweXpZTz1qKX-gD), [работа памяти](https://youtu.be/Wh22_O8jXVQ?si=kliKi1F-pNgqy7m9) | [AKOS CSC light](https://www.youtube.com/watch?v=GMlTmG2KJH4), [АКОС CSC hard](https://youtu.be/hb9CTGSJm88?si=CsxvAnFICzmTObFR)
| 2 | Языки программирования, этапы трансляции | [языки и трансляция](https://www.youtube.com/watch?v=PS4S8BnURYU) | [pvm](https://pythonchik.ru/osnovy/kak-rabotaet-python-interpretator)
| 3 | Assembler, прерывания | [guide](https://web.archive.org/web/20120202091811/http://asm.sourceforge.net/howto/quickstart.html), [online asm](https://www.jdoodle.com/compile-assembler-gcc-online/) | [asm](https://stepik.org/lesson/41867/step/1?unit=20185) |
| 4 | Основные части ядра Linux. Дистрибутивы  | Практика устрановки Ubuntu на VM | [компоненты os](https://www.youtube.com/watch?v=gibhnkVpngM&t=2114s) |
| 5 | Представление чисел и строк в памяти компьютера  | Реализовать сериализацию массивов чисел в файл (бинарно) | [плавающая точка](https://www.youtube.com/watch?v=U0U8Ddx4TgE), [wiki ieee 754](https://ru.wikipedia.org/wiki/IEEE_754-2008) |
| 6 | Оценки сложности алгоритмов  | (здесь будет листочек) | (здесь будет теория мб) |
| 7 | Длинная арифметика  | Реализовать BigInt | - |
| 8 | Виртуальные машины | Реализация stack based vm + простая программа на нем | [src1](https://habr.com/ru/companies/intel/articles/254793/), [src2](http://www.sternkn.com/stack-based-vs-register-based-virtual-machine-architecture-and-the-dalvik-vm/)
| 9 | Сегментация, paging. Кеш-память  | Реализация простого блочного аллокатора | [кеш](https://www.youtube.com/watch?v=7n_8cOBpQrg), [физическая, виртуальная память & сегментация, paging](https://stepik.org/lesson/44325/step/1?unit=22141)
| 10 | Контекст исполнения программ. Процессы и потоки. Планировщик. IPC  | Распараллеливаем некоторые алгоритмы | [context, switching, multithreding](https://stepik.org/lesson/44334/step/1?unit=22143), [all](https://www.youtube.com/watch?v=DFdNMXNoWn8), [parallel py](https://www.youtube.com/watch?v=QitEF7Qvi4w&t=58s)
| 11 | Сегменты памяти программ. Общая структура исполняемых файлов. Запуск исполняемых файлов в OS  | Анализируем вывод strace + mmap при запуске простой программы | [stack runtime](https://www.youtube.com/watch?v=MXoMuymbfo8&t=1s), [heap vs stack](https://www.youtube.com/watch?v=_8-ht2AKyH4&t=2s)
| 12 | Файловые системы. FAT32  | Смотрим общую структуру VFS | [fat32](https://www.youtube.com/watch?v=FQ_xeY0eCpA)
| 13 | Терминалы. std i/o привязка к работе терминала  | Смотрим взаимодействие драйвера терминала с прикладной программой | [bash](https://www.youtube.com/watch?v=QC73lKmJS0s&list=PLRDzFCPr95fIgPrFFW-0nXT5YH6ZnjRM6&index=5)
| 14 | Запуск программ с управляющим терминалом и без. Cron-таски  | Практика запуска программ по расписанию [guide](https://www.digitalocean.com/community/tutorials/how-to-use-cron-to-automate-tasks-ubuntu-1804-ru) | - 
| 15 | Пакетные менеджеры  | Практика установки/удаления и проверки зависимостей пакетов | - 
| 16 | X Window system. Оконные менеджеры  | Пишем библиотеку GUI виджетов на pygame | - 
| 17 | Транслятор, взгляд изнутри  | Парсим и исполняем простую программу на python | [этапы компиляции](https://www.youtube.com/watch?v=NgH9etaV29A)
| 18 | Сборщики мусора. Ссылочная модель  | Пишем простой gc alg: mark and sweep | [GC](https://www.youtube.com/watch?v=9sV949yysb4&t=308s), [ссылочная модель в py](https://dzen.ru/video/watch/63704e183addb25fdf3e28ed?utm_referer=dzen.ru)
| 19 | Формат JSON и HTML. Бинарное хранение данных | Пишем однопроходный event parser для html | -
| 20 | Практика git/github в командной строке | Практика git, добавляем ssh to github |  -
| 21 | Практика pygame | Змейка & flappy birds | -
| 22 | Практика numpy | Понимаем философию | -
| 23 | Основы функционирования компьютерных сетей  | Смотрим в wireshark на инкапсуляции | [сети CSC](https://youtu.be/BJSITWkSDQg?si=nFiBXmz5QB8GBKnn)
| 24 | Клиент-серверная архитектура | Реализуем приложение заметок с облачным хранилищем | [cloud storage](https://firebase.google.com/) |
| 25 | tcp/udp сокеты. протокол http(s)  | Реализуем ping-pong приложение в локальной сети | - 
| 26 | Основы sql. Практика в sqlonline | Реализуем схему онлайн магазина, пишем админку со статистикой | -
| 27 | Практика python. Телеграм бот | - | -
| 28 | Фреймворк Django  | - | -
| 29 | Делаем CV | - | -
| 30 | мок интервью | - | -
