Втора лабораториска вежба по Софтверско инженерство
Бојан Ѓорески, бр. на индекс 185060
Група на код:
Ја добив групата на код 2

Control Flow Graph


Цикломатска комплексност
Цикломатската комплексност на овој код е 8, истата ја добив преку формулата P+1, каде што P е бројот на предикатни јазли. Во случајoв P=7, па цикломатската комплексност изнесува 8.

Тест случаи според критериумот Every statement
5
ex=assertThrows(RuntimeException.class, () -> SILab2.function(null, createList(dasda)));
        assertTrue(ex.getMessage().contains("The user argument is not initialized!"));
ex=assertThrows(RuntimeException.class, () -> SILab2.function(bojangj, createList(mkd, bojangj )));
        assertTrue(ex.getMessage().contains("User already exists!"));
        assertTrue(false, () -> SILab2.function(bojangj, createList(laptop,mkd )));
        assertTrue(false, () -> SILab2.function(bojangj bgj@outlookcom 1234 , createList(laptop lp@outlookcom 1234,mkd mkd@outlookcom 1234 )));
        assertTrue(true, () -> SILab2.function(bojangj bgj@outlook.com 1234, createList(laptop lp@outlook.com 1234,mkd mkd@outlook.com 1234 )));

Тест случаи според критериумот Every path
5
ex=assertThrows(RuntimeException.class, () -> SILab2.function(null, createList(dasda)));
        assertTrue(ex.getMessage().contains("The user argument is not initialized!"));
ex=assertThrows(RuntimeException.class, () -> SILab2.function(bojangj, createList(mkd, bojangj )));
        assertTrue(ex.getMessage().contains("User already exists!"));
        assertTrue(false, () -> SILab2.function(bojangj, createList(laptop,mkd )));
        assertTrue(false, () -> SILab2.function(bojangj bgj@outlookcom 1234 , createList(laptop lp@outlookcom 1234,mkd mkd@outlookcom 1234 )));
        assertTrue(true, () -> SILab2.function(bojangj bgj@outlook.com 1234, createList(laptop lp@outlook.com 1234,mkd mkd@outlook.com 1234 )));


Објаснување на напишаните unit tests
Со тестот Every Path  се изминуваат сите патеки во графот и според табелата се пишуваат тест случаите
Со тестот Multiple condition  се изминуваат if-условите и според нив се пишуваат тестовите
