hugeNumber.py: Even though this question might be trivial, My implementation is O(N) complexity and faster than the N log N method proposed by official analysis. Based on pigeon - hole theorem, we know that in the worst case, we are guaranteed to see a modolo loop if we times A with itself for 10^5+1 times. Based on this observation, we can identify the start of the modolo loop and the length of the modolo loop. The final answer is thus simply N's position in the modolo loop. 

cardsGame.py: The key to solve this questions is to realize that it is a graph problem and not a dp problem. We can translates the entire problem into finding the minimum spanning tree. 

matrixCutting.cpp: Sometimes a dp solution might not be right away handy, but a recursion with memorization would still work. Also, precomputation helps to reduce complexity.
