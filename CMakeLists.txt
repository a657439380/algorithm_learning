cmake_minimum_required(VERSION 3.5)
project(C)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    data_structure/src/3-line-array/01_ArrayList.c
    data_structure/src/3-line-array/02_LinkList.c
    data_structure/src/3-line-array/03_StaticLinkList.c
    data_structure/src/4-stack-quene/01_Stack.c
    data_structure/src/4-stack-quene/02_DoubleStack.c
    data_structure/src/4-stack-quene/03_LinkStack.c
    data_structure/src/4-stack-quene/04_Fibonacci.c
    data_structure/src/4-stack-quene/05_Queue.c
    data_structure/src/4-stack-quene/06_LinkQueue.c
    data_structure/src/5-string/01_String.c
    data_structure/src/5-string/02_KMP.c
    data_structure/src/6-tree/01_BiTreeArray.c
    data_structure/src/6-tree/02_BiTreeLink.c
    data_structure/src/6-tree/03_ThreadBinaryTree.c
    data_structure/src/7-graph/01_CreateMGraph.c
    data_structure/src/7-graph/02_CreateALGraph.c
    data_structure/src/7-graph/03_DFS_BFS.c
    data_structure/src/7-graph/04_DFS_BFS.c
    data_structure/src/7-graph/05__Prim.c
    data_structure/src/7-graph/06_Kruskal.c
    data_structure/src/7-graph/07_Dijkstra.c
    data_structure/src/7-graph/08_Floyd.c
    data_structure/src/7-graph/09_TopologicalSort.c
    data_structure/src/7-graph/10_CriticalPath.c
    data_structure/src/8-search/01_Search.c
    data_structure/src/8-search/02_BinarySortTree.c
    data_structure/src/8-search/03_AVLTree.c
    data_structure/src/8-search/04_BTree.c
    data_structure/src/8-search/05_HashTable.c
    data_structure/src/9-sort/01_Sort.c
    GraphDFS.cpp)

add_executable(C ${SOURCE_FILES})