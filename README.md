## Instruction
The smallest unit JaCoCo counts are single Java byte code instructions.
(т.е. здесь выполняется анализ байт-кода)

## Branches
JaCoCo also calculates branch coverage for all if and switch statements. This metric counts the total number of such branches in a method and determines the number of executed or missed branches. Note that exception handling is not considered as branches in the context of this counter definition.
(т.е идет подсчет общего количества веток)

## Lines
For all class files that have been compiled with debug information, coverage information for individual lines can be calculated. A source line is considered executed when at least one instruction that is assigned to this line has been executed.
(идет подсчет для отдельных строк, при этом строка выполнена, даже если выполненна хотя бы часть ее кода.

## Cyclomatic Complexity 
JaCoCo also calculates cyclomatic complexity for each non-abstract method and summarizes complexity for classes, packages and groups. According to its definition by McCabe1996 cyclomatic complexity is the minimum number of paths that can, in (linear) combination, generate all possible paths through a method. Thus the complexity value can serve as an indication for the number of unit test cases to fully cover a certain piece of software. Complexity figures can always be calculated, even in absence of debug information in the class files.
(рассчитывается сложность теста)
