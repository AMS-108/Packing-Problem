This paper proposes an innovative algorithm SCC (Shuffle Combine Climber) to efficiently solve the classic Knapsack Problem. The Knapsack Problem is an important challenge in the field of combinatorial optimization, involving how to maximize the value of items under capacity constraints, and is widely used in practical scenarios such as logistics optimization and resource allocation.
SCC improves the limitations of traditional hill climbing algorithms by introducing "shuffle" and "combine" strategies, and balances local exploration and global optimization capabilities in the search process. The core idea of ​​the algorithm is to enhance the quality of the initial solution by using randomness and diversity, and quickly converge to a high-quality solution through an efficient hill climbing mechanism.

Algorithm comparison experiment
To verify the superiority of SCC, this paper compares it with two classic algorithms:
1. Traditional hill climbing algorithm (T): This is a simple algorithm based on neighborhood search, which runs fast but is prone to local optimal solutions.
2. Genetic algorithm (G): It simulates the biological evolution process for global search and has a strong ability to jump out of the local optimal solution, but at the cost of high computational complexity.

The experiment tested the performance of SCC, T and G through multiple data sets, and statistically analyzed the experimental results with the help of Minitab tools to ensure the accuracy and reliability of the data. The main conclusions are as follows:
* Solution quality: The solution quality of SCC is better than that of T and G overall, especially in instances with higher complexity.
* Computational efficiency: The running time of SCC is much faster than that of T and G, reflecting its significant advantage in efficiency.
* Stability: Although SCC has slight fluctuations in solution stability compared with G, the overall effect is better, especially in the frequency and distribution of high-quality solutions.

Disclaimer
The algorithm design and experimental results of this article are independently completed by the author based on personal learning and practice. However, as a beginner, the author's programming ability and algorithm implementation may not be perfect, there may be potential problems in the code, and the experimental results may also be affected by implementation details. In addition, the experimental background of this article is based on a limited number of data sets, and the performance of the algorithm can only be reflected in these specific conditions, and it is not guaranteed to be applicable to data sets of all sizes or complexities. Therefore, the conclusions of this article are for reference only, and further discussion and improvement are welcome.