# tomkoJAVA
Aston QA-automation

**ВАЖНО!!!**

_Для корректной работы приложения убедитесь, что параметр коммандной строки: текущая кодовая страница - 1251 (для Windows).
Для этого необходимо сделать следующие действия:
1) запустить редактор реестра: Start->Run->regedit
2) проследовать по следующему адресу: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Nls\CodePage
3) сменить кодировку в OEMCP с 866 на 1251._

Для запуска файла tomkoJAVA.exe на машине должна быть установлена JRE мин. версия - 1.6.0_22.

В программе реализована возможность запуска через коммандную строку с набором параметров для трех задач 
(число, имя, массив в виде чисел, разделенных запятой), например: 12 Вячеслав 45,5,12,9,45,0
Если параметров будет введено меньше трех, то программа проигнорирует введенные аргументы и выведет 
пользовательское меню на экран консоли.

Программа обрабатывает некорректно введеные значания.
