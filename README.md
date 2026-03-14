<div align = "center">

<h1>Алгоритмы и структуры данных - C#</h1>

Репозиторий представляет собой коллекцию разнообразных алгоритмов, реализованных на C#. Алгоритмы охватывают широкий спектр тем, от информатики, математики и статистики, анализа данных, машинного обучения, инженерии и т. д. Реализации и связанная с ними документация предназначены для предоставления учебного ресурса преподавателям и студентам. Поэтому можно найти несколько реализаций для одной и той же задачи, но с использованием различных алгоритмических стратегий и оптимизаций.

<h2>Лист алгоритмов и структур данных</h2>
</div>

> [Английская версия документации](README_EN.md)

- [Алгоритмы](#алгоритмы)
    - [Криптография](#криптография)
        - [Padding (добавление выравнивания блоков)](#padding-добавление-выравнивания-блоков)
        - [Хеш-функции (Digest)](#хеш-функции-digest)
    - [Сжатие данных](#сжатие-данных)
    - [Кодировщики и шифры](#кодировщики-и-шифры)
    - [Алгоритмы графов](#алгоритмы-графов)
        - [Минимальное остовное дерево](#минимальное-остовное-дерево)
        - [Обходы и поиск](#обходы-и-поиск)
        - [Алгоритмы кратчайших путей](#алгоритмы-кратчайших-путей)
        - [Алгоритмы анализа графов](#алгоритмы-анализа-графов)
    - [Задача рюкзака](#задача-рюкзака)
        - [Реализации](#реализации)
    - [Линейная алгебра](#линейная-алгебра)
        - [Метрики расстояния](#метрики-расстояния)
        - [Собственные значения](#собственные-значения)
    - [Модульная арифметика](#модульная-арифметика)
    - [Численные алгоритмы](#численные-алгоритмы)
        - [Разложения](#разложения)
        - [Округление](#округление)
        - [Наибольший общий делитель](#наибольший-общий-делитель)
        - [Факторизация](#факторизация)
        - [Степени и ряды](#степени-и-ряды)
        - [Ряды](#ряды)
        - [Алгебраические методы](#алгебраические-методы)
        - [Комбинаторика и числа](#комбинаторика-и-числа)
        - [Псевдообратная матрица](#псевдообратная-матрица)
        - [Специальные числа](#специальные-числа)
        - [Численные методы](#численные-методы)
        - [Проверка простоты](#проверка-простоты)
        - [Другие числовые алгоритмы](#другие-числовые-алгоритмы)
    - [Системы рекомендаций](#системы-рекомендаций)
    - [Машинное обучение](#машинное-обучение)
    - [Алгоритмы поиска](#алгоритмы-поиска)
    - [Алгоритмы сортировки](#алгоритмы-сортировки)
        - [Сравнительные сортировки](#сравнительные-сортировки)
        - [Быстрая сортировка](#быстрая-сортировка)
        - [Стратегии выбора опорного элемента](#стратегии-выбора-опорного-элемента)
        - [Дополнительные алгоритмы сортировки](#дополнительные-алгоритмы-сортировки)
        - [Внешняя сортировка](#внешняя-сортировка)
        - [Сортировки целых чисел](#сортировки-целых-чисел)
        - [Сортировки строк](#сортировки-строк)
    - [Перемешивание (Shuffling)](#перемешивание-shuffling)
    - [Последовательности](#последовательности)
    - [Алгоритмы работы со стеком](#алгоритмы-работы-со-стеком)
    - [Алгоритмы для строк](#алгоритмы-для-строк)
        - [Метрики сходства строк](#метрики-сходства-строк)
        - [Поиск шаблонов](#поиск-шаблонов)
        - [Другие алгоритмы строк](#другие-алгоритмы-строк)
    - [Другие алгоритмы](#другие-алгоритмы)
    - [Алгоритмические задачи](#алгоритмические-задачи)
        - [Stable Marriage](#stable-marriage)
        - [N-Queens](#n-queens)
        - [Knight Tour](#knight-tour)
        - [Раскраска графа](#раскраска-графа)
        - [Динамическое программирование](#динамическое-программирование)
        - [Задача коммивояжёра](#задача-коммивояжёра)
        - [Планирование задач](#планирование-задач)
- [Структуры данных](#структуры-данных)
    - [Bag (мешок)](#bag-мешок)
    - [Битовый массив](#битовый-массив)
    - [Двусторонняя очередь](#двусторонняя-очередь)
    - [Временная линия](#временная-линия)
    - [Деревья сегментов](#деревья-сегментов)
    - [Деревья поиска](#деревья-поиска)
    - [Стек](#стек)
    - [Кучи (Heap)](#кучи-heap)
    - [Вероятностные структуры данных](#вероятностные-структуры-данных)
    - [Очереди](#очереди)
    - [Связанные списки](#связанные-списки)
    - [Графы](#графы)
    - [Непересекающиеся множества](#непересекающиеся-множества)
    - [Отсортированный список](#отсортированный-список)
    - [Инвертированный индекс](#инвертированный-индекс)
    - [Unrolled Linked List](#unrolled-linked-list)
    - [Trie (префиксное дерево)](#trie-префиксное-дерево)
    - [Хеш-таблица](#хеш-таблица)
    - [Кэш](#кэш)

# Алгоритмы

- [Algorithms](./Algorithms)

## Криптография

### Padding (добавление выравнивания блоков)

- [Paddings](./Algorithms/Crypto/Paddings/)
    - [ISO 10125-2 Padding](./Algorithms/Crypto/Paddings/Iso10126D2Padding.cs)
    - [ISO 7816-4 Padding](./Algorithms/Crypto/Paddings/Iso7816D4Padding.cs)
    - [X9.32 Padding](./Algorithms/Crypto/Paddings/X932Padding.cs)
    - [TBC Padding](./Algorithms/Crypto/Paddings/TbcPadding.cs)
    - [PKCS7 Padding](./Algorithms/Crypto/Paddings/Pkcs7Padding.cs)

### Хеш-функции (Digest)

- [Digests](./Algorithms/Crypto/Digests/)
    - [Ascon Hash Digest](./Algorithms/Crypto/Digests/AsconDigest.cs)
    - [MD2 Digest](./Algorithms/Crypto/Digests/Md2Digest.cs)

## Сжатие данных

- [Data Compression](./Algorithms/DataCompression)
    - [Burrows-Wheeler transform](./Algorithms/DataCompression/BurrowsWheelerTransform.cs)
    - [Huffman Compressor](./Algorithms/DataCompression/HuffmanCompressor.cs)
    - [Shannon-Fano Compressor](./Algorithms/DataCompression/ShannonFanoCompressor.cs)

## Кодировщики и шифры

- [Encoders](./Algorithms/Encoders)
    - [Caesar](./Algorithms/Encoders/CaesarEncoder.cs)
    - [Vigenere](./Algorithms/Encoders/VigenereEncoder.cs)
    - [Hill](./Algorithms/Encoders/HillEncoder.cs)
    - [NYSIIS](./Algorithms/Encoders/NysiisEncoder.cs)
    - [Soundex](./Algorithms/Encoders/SoundexEncoder.cs)
    - [Feistel](./Algorithms/Encoders/FeistelCipher.cs)
    - [Blowfish](./Algorithms/Encoders/BlowfishEncoder.cs)
    - [Autokey](./Algorithms/Encoders/AutokeyEncoder.cs)

## Алгоритмы графов

- [Graph](./Algorithms/Graph)

### Минимальное остовное дерево

- [Minimum Spanning Tree](./Algorithms/Graph/MinimumSpanningTree)
    - [Prim's Algorithm (Adjacency Matrix)](./Algorithms/Graph/MinimumSpanningTree/PrimMatrix.cs)
    - [Kruskal's Algorithm](./Algorithms/Graph/MinimumSpanningTree/Kruskal.cs)

### Обходы и поиск

- [BreadthFirstTreeTraversal](./Algorithms/Graph/BreadthFirstTreeTraversal.cs)
- [BreadthFirstSearch](./Algorithms/Graph/BreadthFirstSearch.cs)
- [DepthFirstSearch](./Algorithms/Graph/DepthFirstSearch.cs)

### Алгоритмы кратчайших путей

- [Dijkstra Shortest Path](./Algorithms/Graph/Dijkstra/DijkstraAlgorithm.cs)
- [FloydWarshall](./Algorithms/Graph/FloydWarshall.cs)

### Алгоритмы анализа графов

- [Kosaraju](./Algorithms/Graph/Kosaraju.cs)
- [Topological Sort](./Algorithms/Graph/TopologicalSort.cs)

## Задача рюкзака

- [Knapsack problem](./Algorithms/Knapsack)

### Реализации

- [Naive solver](./Algorithms/Knapsack/NaiveKnapsackSolver.cs)
- [Dynamic Programming solver](./Algorithms/Knapsack/DynamicProgrammingKnapsackSolver.cs)
- [Branch and bound solver](./Algorithms/Knapsack/BranchAndBoundKnapsackSolver.cs)
- [IHeuristicKnapsackSolver](./Algorithms/Knapsack/IHeuristicKnapsackSolver.cs)

## Линейная алгебра

- [Linear Algebra](./Algorithms/LinearAlgebra)

### Метрики расстояния

- [Distances](./Algorithms/LinearAlgebra/Distances)
    - [Chebyshev](./Algorithms/LinearAlgebra/Distances/Chebyshev.cs)
    - [Euclidean](./Algorithms/LinearAlgebra/Distances/Euclidean.cs)
    - [Manhattan](./Algorithms/LinearAlgebra/Distances/Manhattan.cs)
    - [Minkowski](./Algorithms/LinearAlgebra/Distances/Minkowski.cs)

### Собственные значения

- [Eigenvalue](./Algorithms/LinearAlgebra/Eigenvalue)
    - [Power Iteration](./Algorithms/LinearAlgebra/Eigenvalue/PowerIteration.cs)

## Модульная арифметика

- [Modular Arithmetic](./Algorithms/ModularArithmetic)
    - [Chinese Remainder Theorem](./Algorithms/ModularArithmetic/ChineseRemainderTheorem.cs)
    - [Extended Euclidean Algorithm](./Algorithms/ModularArithmetic/ExtendedEuclideanAlgorithm.cs)
    - [Modular Multiplicative Inverse](./Algorithms/ModularArithmetic/ModularMultiplicativeInverse.cs)

## Численные алгоритмы

- [Numeric](./Algorithms/Numeric)
    - [Absolute](./Algorithms/Numeric/Abs.cs)
    - [Addition Without Arithmetic](./Algorithms/Numeric/AdditionWithoutArithmetic.cs)
    - [Aliquot Sum Calculator](./Algorithms/Numeric/AliquotSumCalculator.cs)
    - [Amicable Numbers Checker](./Algorithms/Numeric/AmicableNumbersChecker.cs)
    - [Ceil](./Algorithms/Numeric/Ceil.cs)

### Разложения

- [Decomposition](./Algorithms/Numeric/Decomposition)
    - [LU Decomposition](./Algorithms/Numeric/Decomposition/LU.cs)
    - [Thin Singular Vector Decomposition](./Algorithms/Numeric/Decomposition/ThinSVD.cs)

### Округление

- [Floor](./Algorithms/Floor.cs)

### Наибольший общий делитель

- [Greatest Common Divisor](./Algorithms/Numeric/GreatestCommonDivisor)
    - [Euclidean GCD](./Algorithms/Numeric/GreatestCommonDivisor/EuclideanGreatestCommonDivisorFinder.cs)
    - [Binary GCD](./Algorithms/Numeric/GreatestCommonDivisor/BinaryGreatestCommonDivisorFinder.cs)

### Факторизация

- [Factorization](./Algorithms/Numeric/Factorization)
    - [Trial division Factorization](./Algorithms/Numeric/Factorization/TrialDivisionFactorizer.cs)

### Степени и ряды

- [Modular Exponentiation](./Algorithms/Numeric/ModularExponentiation.cs)

### Ряды

- [Series](./Algorithms/Numeric/Series)
    - [Maclaurin Series](./Algorithms/Numeric/Series/Maclaurin.cs)

### Алгебраические методы

- [Gauss-Jordan Elimination](./Algorithms/Numeric/GaussJordanElimination.cs)

### Комбинаторика и числа

- [BinomialCoefficient](./Algorithms/Numeric/BinomialCoefficient.cs)
- [Factorial](./Algorithms/Numeric/Factorial.cs)
- [Keith Number Checker](./Algorithms/Numeric/KeithNumberChecker.cs)

### Псевдообратная матрица

- [Pseudo-Inverse](./Algorithms/Numeric/Pseudoinverse/PseudoInverse.cs)

### Специальные числа

- [Narcissistic Number Checker](./Algorithms/Numeric/NarcissisticNumberChecker.cs)
- [Perfect Cube Checker](./Algorithms/Numeric/PerfectCubeChecker.cs)
- [Perfect Number Checker](./Algorithms/Numeric/PerfectNumberChecker.cs)
- [Perfect Square Checker](./Algorithms/Numeric/PerfectSquareChecker.cs)

### Численные методы

- [Euler Method](./Algorithms/Numeric/EulerMethod.cs)
- [Classic Runge-Kutta Method](./Algorithms/Numeric/RungeKuttaMethod.cs)

### Проверка простоты

- [Miller-Rabin primality check](./Algorithms/Numeric/MillerRabinPrimalityChecker.cs)

### Другие числовые алгоритмы

- [KrishnamurthyNumberChecker](./Algorithms/Numeric/KrishnamurthyNumberChecker.cs)
- [Automorphic Number](./Algorithms/Numeric/AutomorphicNumber.cs)
- [Josephus Problem](./Algorithms/Numeric/JosephusProblem.cs)
- [Newton's Square Root Calculation](./Algorithms/NewtonSquareRoot.cs)
- [SoftMax Function](./Algorithms/Numeric/SoftMax.cs)

## Системы рекомендаций

- [RecommenderSystem](./Algorithms/RecommenderSystem)
    - [CollaborativeFiltering](./Algorithms/RecommenderSystem/CollaborativeFiltering)

## Машинное обучение

- [Machine Learning](./Algorithms/MachineLearning)
    - [Linear Regression](./Algorithms/MachineLearning/LinearRegression.cs)
    - [K-Nearest Neighbors](./Algorithms/MachineLearning/KNearestNeighbors.cs)
    - [Logistic Regression](./Algorithms/MachineLearning/LogisticRegression.cs)

## Алгоритмы поиска

- [Searches](./Algorithms/Search)
    - [A-Star](./Algorithms/Search/AStar/)
    - [Binary Search](./Algorithms/Search/BinarySearcher.cs)
    - [BoyerMoore Search](./Algorithms/Search/BoyerMoore.cs)
    - [Fast Search](./Algorithms/Search/FastSearcher.cs)
    - [Fibonacci Search](./Algorithms/Search/FibonacciSearcher.cs)
    - [Interpolation Search](./Algorithms/Search/InterpolationSearch.cs)
    - [Jump Search](./Algorithms/Search/JumpSearcher.cs)
    - [Linear Search](./Algorithms/Search/LinearSearcher.cs)
    - [Recursive Binary Search](./Algorithms/Search/RecursiveBinarySearcher.cs)

## Алгоритмы сортировки

- [Sorts](./Algorithms/Sorters)

### Сравнительные сортировки

- [Comparison](./Algorithms/Sorters/Comparison)
    - [Binary Insertion Sort](./Algorithms/Sorters/Comparison/BinaryInsertionSorter.cs)
    - [Bogo Sort](./Algorithms/Sorters/Comparison/BogoSorter.cs)
    - [Bubble Sort](./Algorithms/Sorters/Comparison/BubbleSorter.cs)
    - [Cocktail Sort](./Algorithms/Sorters/Comparison/CocktailSorter.cs)
    - [Comb Sort](./Algorithms/Sorters/Comparison/CombSorter.cs)
    - [Cycle Sort](./Algorithms/Sorters/Comparison/CycleSorter.cs)
    - [Exchange Sort](./Algorithms/Sorters/Comparison/ExchangeSorter.cs)
    - [Gnome Sort](./Algorithms/Sorters/Comparison/GnomeSorter.cs)
    - [Heap Sort](./Algorithms/Sorters/Comparison/HeapSorter.cs)
    - [Insertion Sort](./Algorithms/Sorters/Comparison/InsertionSorter.cs)
    - [Merge Sort](./Algorithms/Sorters/Comparison/MergeSorter.cs)
    - [Pancake Sort](./Algorithms/Sorters/Comparison/PancakeSorter.cs)

### Быстрая сортировка

- [Quick Sort](./Algorithms/Sorters/Comparison/QuickSorter.cs)

### Стратегии выбора опорного элемента

- [Median of three pivot](./Algorithms/Sorters/Comparison/MedianOfThreeQuickSorter.cs)
- [Middle point pivot](./Algorithms/Sorters/Comparison/MiddlePointQuickSorter.cs)
- [Random pivot](./Algorithms/Sorters/Comparison/RandomPivotQuickSorter.cs)

### Дополнительные алгоритмы сортировки

- [Selection Sort](./Algorithms/Sorters/Comparison/SelectionSorter.cs)
- [Shell Sort](./Algorithms/Sorters/Comparison/ShellSorter.cs)
- [Tim Sort](./Algorithms/Sorters/Comparison/TimSorter.cs)
- [Simplified Tim Sort](./Algorithms/Sorters/Comparison/BasicTimSorter.cs)

### Внешняя сортировка

- [External](./Algorithms/Sorters/External)
    - [Merge Sort](./Algorithms/Sorters/External/ExternalMergeSorter.cs)

### Сортировки целых чисел

- [Integer](./Algorithms/Sorters/Integer)
    - [Counting Sort](./Algorithms/Sorters/Integer/CountingSorter.cs)
    - [Bucket Sort](./Algorithms/Sorters/Integer/BucketSorter.cs)
    - [Radix Sort](./Algorithms/Sorters/Integer/RadixSorter.cs)

### Сортировки строк

- [String](./Algorithms/Sorters/String)
    - [MSD Radix Sort](./Algorithms/Sorters/String/MsdRadixStringSorter.cs)

## Перемешивание (Shuffling)

- [Shufflers](./Algorithms/Shufflers)
    - [Fisher-Yates Shuffler](./Algorithms/Shufflers/FisherYatesShuffler.cs)
    - [LINQ Shuffler](./Algorithms/Shufflers/LinqShuffler.cs)
    - [Naive Shuffler](./Algorithms/Shufflers/NaiveShuffler.cs)
    - [Recursive Shuffler](./Algorithms/Shufflers/RecursiveShuffler.cs)

## Последовательности

- [Sequences](./Algorithms/Sequences)
    - [A000002 Kolakoski](./Algorithms/Sequences/KolakoskiSequence.cs)
    - [A000004 Zero](./Algorithms/Sequences/ZeroSequence.cs)
    - [A000005 Count of Divisors](./Algorithms/Sequences/DivisorsCountSequence.cs)
    - [A000008 Make Change](./Algorithms/Sequences/MakeChangeSequence.cs)
    - [A000010 Euler's Totient](./Algorithms/Sequences/EulerTotientSequence.cs)
    - [A000012 All Ones](./Algorithms/Sequences/AllOnesSequence.cs)
    - [A000027 Natural](./Algorithms/Sequences/NaturalSequence.cs)
    - [A000032 Lucas Numbers](./Algorithms/Sequences/LucasNumbersBeginningAt2Sequence.cs)
    - [A000040 Primes](./Algorithms/Sequences/PrimesSequence.cs)
    - [A000045 Fibonacci](./Algorithms/Sequences/FibonacciSequence.cs)
    - [A000079 Powers of 2](./Algorithms/Sequences/PowersOf2Sequence.cs)
    - [A000108 Catalan](./Algorithms/Sequences/CatalanSequence.cs)
    - [A000120 1's Counting](./Algorithms/Sequences/OnesCountingSequence.cs)
    - [A000124 Central Polygonal Numbers](./Algorithms/Sequences/CentralPolygonalNumbersSequence.cs)
    - [A000125 Cake Numbers](./Algorithms/Sequences/CakeNumbersSequence.cs)
    - [A000142 Factorial](./Algorithms/Sequences/FactorialSequence.cs)
    - [A000213 Tribonacci Numbers](./Algorithms/Sequences/TribonacciNumbersSequence.cs)
    - [A000215 Fermat Numbers](./Algorithms/Sequences/FermatNumbersSequence.cs)
    - [A000288 Tetranacci Numbers](./Algorithms/Sequences/TetranacciNumbersSequence.cs)
    - [A000290 Squares](./Algorithms/Sequences/SquaresSequence.cs)
    - [A000292 Tetrahedral numbers](./Algorithms/Sequences/TetrahedralSequence.cs)
    - [A000578 Cubes](./Algorithms/Sequences/CubesSequence.cs)
    - [A000720 PrimePi](./Algorithms/Sequences/PrimePiSequence.cs)
    - [A001146 Number of Boolean Functions](./Algorithms/Sequences/NumberOfBooleanFunctionsSequence.cs)
    - [A001462 Golomb's](./Algorithms/Sequences/GolombsSequence.cs)
    - [A001478 Negative Integers](./Algorithms/Sequences/NegativeIntegersSequence.cs)
    - [A002110 Primorial Numbers](./Algorithms/Sequences/PrimorialNumbersSequence.cs)
    - [A002717 Matchstick Triangle Arrangement](./Algorithms/Sequences/MatchstickTriangleSequence.cs)
    - [A005132 Recaman's](./Algorithms/Sequences/RecamansSequence.cs)
    - [A006577 Number of '3n+1' steps to reach 1](./Algorithms/Sequences/ThreeNPlusOneStepsSequence.cs)
    - [A006862 Euclid Numbers](./Algorithms/Sequences/EuclidNumbersSequence.cs)
    - [A006879 Number of Primes by Number of Digits](./Algorithms/Sequences/NumberOfPrimesByNumberOfDigitsSequence.cs)
    - [A006880 Number of Primes by Powers of 10](./Algorithms/Sequences/NumberOfPrimesByPowersOf10Sequence.cs)
    - [A007318 Binomial](./Algorithms/Sequences/BinomialSequence.cs)
    - [A007395 All Twos](./Algorithms/Sequences/AllTwosSequence.cs)
    - [A010051 Binary Prime Constant](./Algorithms/Sequences/BinaryPrimeConstantSequence.cs)
    - [A010701 All Threes](./Algorithms/Sequences/BinaryPrimeConstantSequence.cs)
    - [A011557 Powers of 10](./Algorithms/Sequences/PowersOf10Sequence.cs)
    - [A057588 Kummer Numbers](./Algorithms/Sequences/KummerNumbersSequence.cs)
    - [A019434 Fermat Primes](./Algorithms/Sequences/FermatPrimesSequence.cs)
    - [A181391 Van Eck's](./Algorithms/Sequences/VanEcksSequence.cs)

## Алгоритмы работы со стеком

- [Stack](./Algorithms/Stack)
    - [Next Greater Element](./Algorithms/Stack/NextGreaterElement.cs)
    - [Balanced Parentheses Checker](./Algorithms/Stack/BalancedParenthesesChecker.cs)
    - [Reverse Stack](./Algorithms/Stack/ReverseStack.cs)

## Алгоритмы для строк

- [String](./Algorithms/Strings)

### Метрики сходства строк

- [Similarity](./Algorithms/Strings/Similarity/)
    - [Cosine Similarity](./Algorithms/Strings/Similarity/CosineSimilarity.cs)
    - [Damerau-Levenshtein Distance](./Algorithms/Strings/Similarity/DamerauLevenshteinDistance.cs)
    - [Hamming Distance](./Algorithms/Strings/Similarity/HammingDistance.cs)
    - [Jaro Similarity](./Algorithms/Strings/Similarity/JaroSimilarity.cs)
    - [Jaro-Winkler Distance](./Algorithms/Strings/Similarity/JaroWinklerDistance.cs)
    - [Optimal String Alignment](./Algorithms/Strings/Similarity/OptimalStringAlignment.cs)

### Поиск шаблонов

- [Pattern Matching](./Algorithms/Strings/PatternMatching/)
    - [Bitop Pattern Matching](./Algorithms/Strings/PatternMatching/Bitap.cs)
    - [Naive String Search](./Algorithms/Strings/PatternMatching/NaiveStringSearch.cs)
    - [Rabin Karp](./Algorithms/Strings/PatternMatching/RabinKarp.cs)
    - [Boyer Moore](./Algorithms/Strings/PatternMatching/BoyerMoore.cs)
    - [Knuth–Morris–Pratt Search](./Algorithms/Strings/PatternMatching/KnuthMorrisPrattSearcher.cs)
    - [WildCard Pattern Matching](./Algorithms/Strings/PatternMatching/WildCardMatcher.cs)
    - [Z-block substring search](./Algorithms/Strings/PatternMatching/ZblockSubstringSearch.cs)

### Другие алгоритмы строк

- [Longest Consecutive Character](./Algorithms/Strings/GeneralStringAlgorithms.cs)
- [Manacher's Algorithm](./Algorithms/Strings/ManachersAlgorithm.cs)
- [Palindrome Checker](./Algorithms/Strings/Palindrome.cs)
- [Get all permutations of a string](./Algorithms/Strings/Permutation.cs)

## Другие алгоритмы

- [Other](./Algorithms/Other)
    - [Fermat Prime Checker](./Algorithms/Other/FermatPrimeChecker.cs)
    - [Sieve of Eratosthenes](./Algorithms/Other/SieveOfEratosthenes.cs)
    - [Kadane's Algorithm](./Algorithms/Other/KadanesAlgorithm.cs)
    - [Luhn](./Algorithms/Other/Luhn.cs)
    - [Int2Binary](./Algorithms/Other/Int2Binary.cs)
    - [GeoLocation](./Algorithms/Other/GeoLocation.cs)
    - [Mandelbrot](./Algorithms/Other/Mandelbrot.cs)
    - [Koch Snowflake](./Algorithms/Other/KochSnowflake.cs)
    - [RGB-HSV Conversion](./Algorithms/Other/RGBHSVConversion.cs)
    - [Flood Fill](./Algorithms/Other/FloodFill.cs)
    - [Pareto Optimization](./Algorithms/Other/ParetoOptimization.cs)
    - [Gauss Optimization](./Algorithms/Other/GaussOptimization.cs)
    - [Decisions Convolutions](./Algorithms/Other/DecisionsConvolutions.cs)
    - [Welford's Variance](./Algorithms/Other/WelfordsVariance.cs)
    - [Julian Easter](./Algorithms/Other/JulianEaster.cs)
    - [Pollard's Rho](./Algorithms/Other/PollardsRhoFactorizing.cs)
    - [GeoLocation Hash](./Algorithms/Other/Geohash.cs)
    - [Geofencing](./Algorithms/Other/Geofence.cs)
    - [Triangulation Algorithm](./Algorithms/Other/Triangulator.cs)

## Алгоритмические задачи

- [Problems](./Algorithms/Problems)

### Stable Marriage

- [Stable Marriage](./Algorithms/Problems/StableMarriage)
    - [Gale-Shapley](./Algorithms/Problems/StableMarriage/GaleShapley.cs)
    - [Accepter](./Algorithms/Problems/StableMarriage/Accepter.cs)
    - [Proposer](./Algorithms/Problems/StableMarriage/Proposer.cs)

### N-Queens

- [N-Queens](./Algorithms/Problems/NQueens)
    - [Backtracking](./Algorithms/Problems/NQueens/BacktrackingNQueensSolver.cs)

### Knight Tour

- [Knight Tour](./Algorithms/Problems/KnightTour/)
    - [Open Knight Tour](./Algorithms/Problems/KnightTour/OpenKnightTour.cs)

### Раскраска графа

- [Graph Coloring](./Algorithms/Problems/GraphColoring)
    - [Backtracking Graph Coloring Solver](./Algorithms/Problems/GraphColoring/GraphColoringSolver.cs)

### Динамическое программирование

- [Dynamic Programming](./Algorithms/Problems/DynamicProgramming)
    - [Coin Change](./Algorithms/Problems/DynamicProgramming/CoinChange/DynamicCoinChangeSolver.cs)
    - [Levenshtein Distance](./Algorithms/Problems/DynamicProgramming/LevenshteinDistance/LevenshteinDistance.cs)

### Задача коммивояжёра

- [Traveling Salesman Problem (TSP)](./Algorithms/Problems/TravelingSalesman/TravelingSalesmanSolver.cs)
    - [Brute-force and Nearest Neighbor algorithms](./Algorithms/Problems/TravelingSalesman/TravelingSalesmanSolver.cs)

### Планирование задач

- [Job Scheduling](./Algorithms/Problems/JobScheduling)
    - [Interval Scheduling (Greedy)](./Algorithms/Problems/JobScheduling/IntervalSchedulingSolver.cs)

# Структуры данных

- [Data Structures](./DataStructures)

## Bag (мешок)

- [Bag](./DataStructures/Bag)

## Битовый массив

- [Bit Array](./DataStructures/BitArray.cs)

## Двусторонняя очередь

- [Deque (Double-Ended Queue)](./DataStructures/Deque/Deque.cs)

## Временная линия

- [Timeline](./DataStructures/Timeline.cs)

## Деревья сегментов

- [Segment Trees](./DataStructures/SegmentTrees)
    - [Segment Tree](./DataStructures/SegmentTrees/SegmentTree.cs)
    - [Segment Tree Multiplication](./DataStructures/SegmentTrees/SegmentTreeApply.cs)
    - [Segment Tree Update](./DataStructures/SegmentTrees/SegmentTreeUpdate.cs)

## Деревья поиска

- [Binary Search Tree](./DataStructures/BinarySearchTree)
- [Scapegoat Tree](./DataStructures/ScapegoatTree)
- [Fenwick tree (or Binary Indexed Tree)](./DataStructures/Fenwick/BinaryIndexedTree.cs)
- [AA Tree](./DataStructures/AATree)
- [AVL Tree](./DataStructures/AVLTree)
- [B-Tree](./DataStructures/BTree)
- [Red-Black Tree](./DataStructures/RedBlackTree)

## Стек

- [Stack](./DataStructures/Stack)
    - [Array-based Stack](./DataStructures/Stack/ArrayBasedStack.cs)
    - [List-based Stack](./DataStructures/Stack/ListBasedStack.cs)
    - [Queue-based Stack](./DataStructures/Stack/QueueBasedStack.cs)

## Кучи (Heap)

- [Heap](./DataStructures/Heap)
    - [Min-Max Heap](./DataStructures/Heap/MinMaxHeap.cs)
    - [Binary Heap](./DataStructures/Heap/BinaryHeap.cs)
    - [Fibonacci Heap](./DataStructures/Heap/FibonacciHeap/FibonacciHeap.cs)
    - [Pairing Heap](./DataStructures/Heap/PairingHeap/PairingHeap.cs)

## Вероятностные структуры данных

- [Probabilistic](./DataStructures/Probabilistic)
    - [BloomFilter](./DataStructures/Probabilistic/BloomFilter.cs)
    - [Count-Min Sketch](./DataStructures/Probabilistic/CountMinSketch.cs)
    - [HyperLogLog](./DataStructures/Probabilistic/HyperLogLog.cs)

## Очереди

- [Queue](./DataStructures/Queue)
    - [Array-based Queue](./DataStructures/Queue/ArrayBasedQueue.cs)
    - [List-based Queue](./DataStructures/Queue/ListBasedQueue.cs)
    - [Stack-based Queue](./DataStructures/Queue/StackBasedQueue.cs)

## Связанные списки

- [Linked List](./DataStructures/LinkedList)
    - [Singly Linked List](./DataStructures/LinkedList/SinglyLinkedList/SinglyLinkedList.cs)
    - [Doubly Linked List](./DataStructures/LinkedList/DoublyLinkedList/DoublyLinkedList.cs)
    - [Skip List](./DataStructures/LinkedList/SkipList/SkipList.cs)
    - [Circular Linked List](./DataStructures/LinkedList/CircularLinkedList/CircularLinkedList.cs)

## Графы

- [Graph](./DataStructures/Graph)
    - [Directed Weighted Graph Via Adjacency Matrix](./DataStructures/Graph/DirectedWeightedGraph.cs)

## Непересекающиеся множества

- [Disjoint Set](./DataStructures/DisjointSet)

## Отсортированный список

- [SortedList](./DataStructures/SortedList.cs)

## Инвертированный индекс

- [Inverted index](./DataStructures/InvertedIndex.cs)

## Unrolled Linked List

- [Unrolled linked list](./DataStructures/UnrolledList/UnrolledLinkedList.cs)

## Trie (префиксное дерево)

- [Tries](./DataStructures/Tries/Trie.cs)

## Хеш-таблица

- [HashTable](./DataStructures/Hashing/HashTable.cs)

## Кэш

- [Cache](./DataStructures/Cache)
    - [Least Frequently Used (LFU) Cache](./DataStructures/Cache/LfuCache.cs)
    - [Least Recently Used (LRU) Cache](./DataStructures/Cache/LruCache.cs)

<div align = "left">
  <h1 align = "center">Новые требования</h1>
  <ul>
    <li>Для сборки и запуска этого проекта теперь требуется <b>.NET 8 SDK</b>.</li>
    <li>Убедитесь, что ваши инструменты разработки совместимы с <b>.NET 8</b></li>
  </ul>
</div>

<div align = "left">
  <h1 align = "center">Сборка проекта</h1>
  <ul>
    <li>После установки .NET 8 SDK вы можете собрать проект, используя стандартную команду <b>dotnet build</b>.</li>
    <li>Все существующие скрипты сборки были обновлены с учетом поддержки <b>.NET 8 SDK</b>.</li>
  </ul>
</div>

<div align = "left">
  <h1 align = "center">Запуск тестов</h1>
  <ul>
    <li>Наш полный набор модульных тестов обеспечивает совместимость с <b>.NET 8</b>.</li>
    <li>Запускайте тесты с помощью команды <b>dotnet test</b> как обычно.</li>
  </ul>
</div>

<div align = "left">
  <h1 align = "center">Вклад в проект</h1>
</div>

> Вы можете с удовольствием внести свой вклад в этот репозиторий. Пожалуйста, ознакомьтесь со структурой каталогов и общим стилем кода этого репозитория, и обратитесь к [нашим рекомендациям по участию в проекте](./CONTRIBUTING.md) для получения более подробной информации. Если вы хотите задать вопрос или что-то предложить, пожалуйста, создайте заявку (issue).
