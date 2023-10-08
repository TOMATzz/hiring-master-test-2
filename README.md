# По условию компании код запрещен в открытом доступе,по всем вопросам пишите dimapl7653@gmail.com
# Результат решения:

test/run.spec.ts

    run() without threads limit
	√ run() executed sucessfully
    √ all tasks completed in proper order
    √ `performance.max` should be `12` (equal to number of distinct `targetId`)(12)
    √ `performance.avg` should be greater than `8.5`
		(~number of distinct `targetId`) (11.001912007523758)
    
    run() with 2 max threads
    √ run() executed sucessfully
    √ all tasks completed in proper order
    √ `performance.max` should be `2` (2)
    √ `performance.avg` should be greater than `1.5` (1.9723307177333325)
    
    run() with 3 max threads
    √ run() executed sucessfully
    √ all tasks completed in proper order
    √ `performance.max` should be `3` (3)
    √ `performance.avg` should be greater than `2` (2.9495132012920116)
    
    run() with 5 max threads
    √ run() executed sucessfully
    √ all tasks completed in proper order
    √ `performance.max` should be `5` (5)
    √ `performance.avg` should be greater than `3.8` (4.896584077938909)
    
    run() with 2 threads on modifying queue
    √ run() executed sucessfully
    √ all tasks completed in proper order
    √ `performance.max` should be `2` (2)
    √ `performance.avg` should be greater than `1.5` (1.8665213727660364)
    
    run() with 3 threads on infinite queue
    √ `performance.max` should be `3` (3)
    √ `performance.avg` should be greater than `2.5` (2.7442156779723534)
    
    24 passing (39s)

File         |  % Stmts | % Branch |  % Funcs |  % Lines | Uncovered Line #s |
-------------|----------|----------|----------|----------|-------------------|
All files    |      100 |       94 |      100 |      100 |                   |
 Executor.ts |      100 |    83.33 |      100 |      100 |         49,92,135 |
 run.ts      |      100 |      100 |      100 |      100 |                   |
