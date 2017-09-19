# PageRank
1. PageRank is an algorithm used by Google Search to rank websites in their search engine results.
2. In this project, I got the input data from wiki to implement pageRank algorithm.
3. Since Self-rank is not accurate, we involve all the web pages to rank based on two basic theory: 1).More important websites are likely to receive more links from other websites; 2).Website with higher PageRank will pass higher weight. 
4. The project used pageRank Matrix * transition matrix to calculate PRN for each itiration(that is PRN = PR(N-1) * Transition Matrix).
5. The project also deal with edge case problem of pageRank, that is 1).Dead ends; 2).Spider traps by using a parameter. 
