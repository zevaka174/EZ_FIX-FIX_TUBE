# EZ_FIX - Простой фикс ваших проблем 
Данная программа очень легко исправляет блокировку дискорда в России. Вы сможете легко и быстро общаться в войсе, без каких либо проблем и танцев с бубном.

# Наши плюсы:
- Простой запуск 
Вы можете удобно запустить ez_fix (discord) и вуаля! Дискорд работает.

- Остуствие вирусов. (Только 2 детекта на вирустотале, ниже распишу почему так происходит.)
Да, у нас нет вирусов, я использовал шаблон goodbyedpi, немного поменяв dllки windivert`а и изменив настройки фильтров, сделав их быстрыми.
По поводу детектов: windivert отвечает за dpi пакеты, он имеет доступ ТОЛЬКО к сетевому трафику, а также у него есть офиц. гитхаб, с которого файлы качали больше 10.000 раз: https://github.com/basil00/WinDivert
Насчёт "скрытого" майнера: да, в описании dll есть биткоин кошелёк, но вот чудо, оно сделано для поддержки автора. У него есть офиц. сайт, где вы можете ему добровольно задонатить по указанному биткоин кошельку, так что ничего в этом нет. 
Если вы не сможете удалить файлы, то это из за windivert.sys, системный файл, работающий как драйвер. Вам необходимо открыть cmd и прописать принудительное отключение драйвера: "cs stop windivert" (без кавычек)

- Частые обновления
Да, я стараюсь обновлять программу, добавлять новые сайты для доступа. Пока что есть только дискорд, а также ютуб, который работает, но ооочень медленно (советую открывать его через microsoft edge)
Постараюсь добавить все сайты внесённые в реестр, чтобы помочь вам!

- По поводу файлов:
EZ-fix (all) - ютуб, а также дискорд, а позднее уже остальные сайты и ускорение ютуба.
main.txt - список со всеми сайтами основного файла (all)
zevaka-ezfix-ascii - картинка из символов ascii, которая открывается во время открытия консоли.
bin - папка со всеми исходными файлами для работы с dpi пакетами. НЕ рекомендую трогать.

# ВСЕ ВОПРОСЫ ЗАДАВАЙТЕ ЧЕРЕЗ ISSUES Я ПОСТАРАЮСЬ ОТВЕТИТЬ И ПОМОЧЬ!