BFS (Пошук у ширину) знайшов шлях:

 ['Server', 'Concentrator_A', 'Concentrator_B', 'PC_3', 'PC_7', 'Phone']. 

BFS забезпечує пошук найкоротшого шляху за кількістю кроків у неваговому графі. Оскільки BFS розглядає вершини рівномірно з кожного рівня перед переходом на наступний, він знаходить найкоротший шлях за кількістю переходів між вершинами.

DFS (Пошук у глибину) знайшов такий шлях:

 ['Server', 'Concentrator_A', 'Concentrator_B', 'PC_1', 'PC_2', 'PC_3', 'PC_7', 'Concentrator_D', 'PC_5', 'Phone']. 
 
DFS продовжує занурення в граф, поки не досягне цілі або тупика, а потім повертається назад, щоб спробувати інші шляхи. Це означає, що шлях, знайдений за допомогою DFS, не обов'язково є найкоротшим; він просто є одним із можливих шляхів, який алгоритм знаходить першим в процесі свого "занурення" і повернення.