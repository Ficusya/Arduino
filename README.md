# Arduino зачет

1. МП и его состав (краткое описание всех модулей), характеристики.  
    Микропроцессор - это устройство, которое выполняет арифметические, логические и управляющие операции над данными, представленными в двоичном коде. Микропроцессор реализован в виде одной или нескольких микросхем, содержащих миллионы транзисторов. В состав микропроцессора входят следующие основные модули:  
  Арифметико-логическое устройство (АЛУ) - выполняет все математические и логические операции над числовой и символьной информацией.  
  Блок управления и синхронизации (БУС) - обеспечивает выполнение процессором последовательности команд, хранящихся в памяти программ, и координирует взаимодействие различных частей компьютера.  
  Запоминающее устройство (ЗУ) - хранит данные и команды, необходимые для работы процессора. ЗУ может быть встроенным в микропроцессор или внешним к нему.  
  Регистры - это быстрые ячейки памяти, используемые для хранения промежуточных результатов вычислений, адресов памяти, флагов состояния и другой информации, необходимой для работы процессора.  
  Шины передачи данных и команд - это группы проводников, по которым передаются данные и команды между процессором и другими устройствами компьютера.  
Основные характеристики: тактовая частота - это количество тактов, которые процессор может выполнить за одну секунду, разрядность - это количество бит, которые процессор может обрабатывать за один такт, архитектура.

2. Архитектура МП.  
    Архитектура МП – это функциональные возможности аппаратных средств МП, используемые для представления данных, машинных операций, описания алгоритмов и процессов вычислений. Архитектура МП включает в себя разрядность адресов и данных, состав и назначение программно-доступных регистров, формат и систему команд, режим адресации памяти, способы машинного представления данных разного типа, структуру адресного пространства, способы адресации внешних устройств и средств выполнения операций ввода-вывода, классы прерываний, особенности инициирования и обработки прерываний.

3. Архитектура Фон-неймана (принстонская).  
  Архитектура Фон-неймана (принстонская) – это широко известный принцип совместного хранения команд и данных в памяти компьютера. Основные характеристики архитектуры фон Неймана: единая адресуемая память для хранения программ и данных, последовательное выполнение команд, разделение команд на операцию и операнды, наличие внутренних регистров для хранения промежуточных результатов, наличие арифметико-логического устройства (АЛУ) и устройства управления. Данная архитектура наиболее характерна для МП, ориентированных на использование в компьютерах.

4. Гарвардская архитектура.  
    Гарвардская архитектура – это архитектура ЭВМ, которая предполагает раздельное использование памяти программ и данных, т.е. хранилище инструкций и хранилище данных представляют собой разные физические устройства; канал инструкций и канал данных также физически разделены. Гарвардская архитектура позволяет одновременно считывать команду и данные, увеличивая скорость работы ЭВМ. Также возможно использование разных типов памяти для команд и данных, например, ROM для команд и RAM для данных. Гарвардская архитектура часто используется в микроконтроллерах и цифровых сигнальных процессорах.

5. Регистры, назначение основных регистров и основные флаги.  
    Регистры – это быстрые запоминающие устройства, входящие в состав микропроцессора. Регистры используются для хранения данных, адресов, команд, флагов и другой информации, необходимой для работы МП. Основные регистры МП: аккумулятор – регистр, в который поступают данные из памяти или портов ввода-вывода и в который записываются результаты арифметических и логических операций; счетчик команд – регистр, в который записывается адрес следующей выполняемой команды; регистр адреса – регистр, в который записывается адрес ячейки памяти или порта ввода-вывода, с которым производится обмен данными; регистр команд – регистр, в который считывается команда из памяти для дешифрации и выполнения; регистр состояния – регистр, в который записываются флаги, отражающие результаты выполнения команд и состояние МП. Основные флаги МП: флаг знака – устанавливается в 1, если результат операции отрицателен; флаг нуля – устанавливается в 1, если результат операции равен нулю; флаг переноса – устанавливается в 1, если при выполнении операции произошел перенос из старшего разряда; флаг переполнения – устанавливается в 1, если при выполнении операции произошло переполнение разрядной сетки; флаг четности – устанавливается в 1, если в результате операции четное число единиц; флаг прерывания – устанавливается в 1, если МП разрешает обработку прерываний.

6. Память. Иерархия памяти.  
    Память – это устройство хранения данных, используемое в вычислительных системах. Память в компьютерах имеет иерархическую структуру и обычно предполагает использование нескольких запоминающих устройств, имеющих различные характеристики. Иерархия памяти – это концепция построения взаимосвязи классов разных уровней компьютерной памяти на основе иерархической структуры. Сущность необходимости построения иерархической памяти – необходимость обеспечения вычислительной системы достаточным объемом памяти, как оперативной, так и постоянной. Часто выделяют 4 основных (укрупненных) уровня иерархии: внутренняя память процессора (регистры, организованные в регистровый файл и кэш процессора); ОЗУ системы (RAM) и вспомогательных карт памяти; накопители с «горячим» доступом (On-line mass storage) – или вторичная компьютерная память; накопители с «холодным» доступом (Off-line mass storage) – или третичная компьютерная память.

7. NOR и NAND память. Особенности, сходства и различия.  
    NOR и NAND память – это типы флеш-памяти, основанные на использовании логических элементов NOR и NAND соответственно. Особенности NOR памяти: возможность произвольного доступа к ячейкам памяти; высокая скорость чтения данных; низкая скорость записи и стирания данных; высокая стоимость и низкая плотность размещения ячеек. Особенности NAND памяти: невозможность произвольного доступа к ячейкам памяти; низкая скорость чтения данных; высокая скорость записи и стирания данных; низкая стоимость и высокая плотность размещения ячеек. Сходства NOR и NAND памяти: обе памяти являются неизменяемыми, то есть сохраняют данные при отключении питания; обе памяти имеют ограниченное число циклов записи и стирания; обе памяти используются для хранения программ и данных в различных устройствах. Различия NOR и NAND памяти: NOR память позволяет обращаться к данным размером до одного байта, тогда как NAND память работает постранично; NOR память выигрывает в ситуациях, когда данные случайным образом записываются или читаются, тогда как NAND память лучше подходит для последовательной записи и чтения; NOR память чаще всего встраивают в сотовые телефоны и планшеты для хранения операционной системы, тогда как NAND память чаще используется в твердотельных накопителях и других устройствах для хранения пользовательской информации.

8. Интерфейс. Понятия и классификация.  
    Интерфейс микропроцессора - это совокупность средств и правил, обеспечивающих взаимодействие микропроцессора с другими устройствами. Интерфейсы могут быть классифицированы по различным признакам, например, по способу передачи данных (параллельный или последовательный), по количеству линий (одно- или многопроводный), по типу сигналов (электрические, оптические, беспроводные и т.д.).

9. Интерфейс. Подтягивающие резисторы (питание и земля какой и для чего используется).  
    Подтягивающие резисторы - это резисторы, подключенные к питанию или земле, чтобы установить определенный уровень напряжения на входе или выходе микропроцессора. Они используются для предотвращения появления неопределенных состояний, когда линия не подключена к источнику сигнала, или для обеспечения совместимости сигналов разных логических семейств.

10. Прерывания.  
    Прерывания - это сигналы, поступающие от внешних устройств к микропроцессору, чтобы запросить его внимание. Они позволяют микропроцессору реагировать на события в реальном времени, приостанавливая текущую программу и переходя к специальной подпрограмме, называемой обработчиком прерывания.

11. Тактирование. Тактовый генератор.  
    Тактирование - это процесс генерации периодических импульсов, которые синхронизируют работу микропроцессора и других устройств. Тактовый генератор - это устройство, которое производит тактовые импульсы. Частота тактового генератора определяет скорость работы микропроцессора.

12. АЦП. ЦАП.  
    АЦП - это аналого-цифровой преобразователь, устройство, которое преобразует аналоговый сигнал (например, напряжение или ток) в цифровой код (например, двоичное число). ЦАП - это цифро-аналоговый преобразователь, устройство, которое преобразует цифровой код в аналоговый сигнал.

13. Синхронная передача данных.  
    Синхронная передача данных - это способ передачи данных, при котором передаваемые и принимаемые биты синхронизируются с общим тактовым сигналом. Синхронная передача данных обеспечивает высокую скорость и надежность, но требует дополнительных линий для передачи тактового сигнала.

14. Асинхронная передача данных.  
    Асинхронная передача данных - это способ передачи данных, при котором передаваемые и принимаемые биты не синхронизируются с общим тактовым сигналом. Асинхронная передача данных не требует дополнительных линий для передачи тактового сигнала, но имеет более низкую скорость и надежность, так как требует передачи специальных сигналов, называемых старт-битом и стоп-битом, для определения начала и конца каждого байта.

15. Передача данных. Особенности и Классификация.  
    Передача данных - это процесс обмена информацией между устройствами в виде последовательности битов. Передача данных может иметь различные особенности, такие как направление (одно- или двунаправленная), режим (симплексный, полудуплексный или дуплексный), скорость (бит/с), расстояние (локальная или глобальная), среда (проводная или беспроводная) и т.д. Передача данных может быть классифицирована по различным критериям, например, по способу кодирования (NRZ, RZ, Манчестерский и т.д.), по способу модуляции (АМ, ЧМ, ФМ и т.д.), по способу мультиплексирования (ЧДМ, ЧМ, КМ и т.д.) и т.д.

16. Интерфейс I2C.  
    Интерфейс I2C - это последовательный двухпроводный интерфейс, который позволяет подключать несколько устройств к одной шине данных. Он состоит из двух линий: SDA (Serial Data) и SCL (Serial Clock). Он использует схему мастер-ведомый, при которой одно устройство (мастер) инициирует и управляет передачей данных, а другие устройства (ведомые) отвечают на запросы мастера. Каждое устройство имеет уникальный адрес, который используется для идентификации. Интерфейс I2C обладает простотой, гибкостью и низким энергопотреблением.

17. Интерфейс SPI.  
    Интерфейс SPI - это последовательный четырехпроводный интерфейс, который позволяет подключать несколько устройств к одной шине данных. Он состоит из четырех линий: MOSI (Master Out Slave In), MISO (Master In Slave Out), SCK (Serial Clock) и SS (Slave Select). Он также использует схему мастер-ведомый, при которой одно устройство (мастер) генерирует тактовый сигнал и выбирает ведомое устройство, с которым хочет обмениваться данными. Интерфейс SPI обладает высокой скоростью, надежностью и простотой.

18. Встроенный контроллер последовательного интерфейса.  
    Встроенный контроллер последовательного интерфейса - это специализированный микроконтроллер, который обеспечивает передачу и прием данных по последовательному интерфейсу, такому как UART, USART, RS-232, RS-485 и т.д. Он освобождает микропроцессор от необходимости управлять такими деталями, как формирование и декодирование битов, контроль ошибок, буферизация данных и т.д. Он обычно имеет собственные регистры, буферы, таймеры и прерывания, которые позволяют настраивать параметры передачи данных, такие как скорость, количество битов, четность, стоп-биты и т.д.
