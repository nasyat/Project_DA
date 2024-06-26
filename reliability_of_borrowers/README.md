## Исследование надёжности заёмщиков — анализ банковских данных
На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок.

На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.

**Выводы:** На основе предоставленных данных, исключая из выборки категории с тремя, четырмя и пятью детьми, в связи с недостаточностью данных, соответственно низкой релевантностью. 
По остальным категориям граждан, данные по которым имеются, можно сделать следующие выводы:
1. Наличие детей негативно сказывается на прогнозе возврата кредитных средств;
2. Зависимость изменения уровня благонадежности от количества детей между гражданами имеющими одно или двух детей наблюдается незначительная.

В исходных данных пять категорий семейного положения, данные в каждой категории представленны очень неравномерно, учитывая, что такого понятия, как "гражданскиц брак" юридически не существует, с целью корректности выводов, я бы объединила данные с категорией "не женат/не замужем", тогда у нас получается только две категории достаточно сбалансированы для сравнения: "не женат/не замужем" и  "женат / замужем". На основе предоставленных данных, можно сделать вывод, что граждане, которые не состоят в официальном браке имеют более высокий риск невозврата кредитных средств, соответственно граждане состоящие в браке имеют более высокую степень благонадежности.

На основе предоставленных дннных были выделены пять категорий граждан, в зависимости от уровня дохода, в связи с низкой степенью релевантности не берем в расчет данные по категориям A, D, E. По итогам рассмотрения информации по категориям B и С, с ростом дохода, вероятность возврата кредита в срок увеличивается тоже.

На основе предоставленных данных можно сделать следующие выводы:
1. Самый высокий уровень риска невозврата в категориях: операции с автомобилем и получение образования
2. Самый позитивный сценарий прогноза возвратности кредитных средств у операций с недвижимостью

На основе анализа предоставленных данных, можно сделать вывод, что степень благонадежности заемщика повышается, а соответственно и вероятность возврата кредита в срок при следующих факторах:
1. У состоящих в официальном браке;
2. Наличие детей негативно сказывается на прогнозе возвратности кредитных средств;
3. Кредиты, предоставленные на образование или операции с недвижимостью, имеют более высокую вероятность возврата в срок.
