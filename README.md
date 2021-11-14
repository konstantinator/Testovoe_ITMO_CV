# Testovoe_ITMO_CV

Дан граф G(V,E) с компонентой связности равной 1. Граф задается матрицей расстояний между вершинами distance_matrix, где distance_matrix[i][j] - расстояние между i и j вершинами. Если distance_matrix[i][j] = 0, то не существует пути из i вершины в j. Необходимо пройти по всем вершинам и вернутся в исходную так, чтобы суммарный путь был минимальным. Начало пути следует начинать с первой вершины. Разрешается проходить по одной вершине несколько раз.

На вход подается в первой строке количество вершин, далее следует матрица смежности, на выходе необходимо вернуть найденное минимальное расстояние. Решение будет проверяться на ряде тестов. Считается, что решение прошло тест, если найденное минимальное расстояние не больше чем на 4, чем реальное минимальное расстояние. 

Имейте ввиду, что граф может содержать мосты, а так же вершины, удаление которых увеличивает компоненту связности графа на единицу.

Sample Input:

4\
0 2 2 0\
2 0 2 2\
2 2 0 0\
0 2 0 0

Sample Output:

10







