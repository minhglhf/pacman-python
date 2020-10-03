# pacman-python
# question1 DFS sử dụng stack, mỗi stack chứa các trạng thái,push trạng thái ban đầu startState vào stack, duyệt vòng lặp với điều kiện stack khác rỗng, trong vòng lặp luôn, pop để lấy state đầu của Stack rồi đánh dấu , lặp lại cho đến khi state là goal state hoặc không có solution.

# question2 BFS tưởng tự question1 chỉ thay stack  = queue

# question3 USC sử dụng PriorityQueue, trạng thái, state và chi phí đc đưa vào PQ theo ưu tiên chi phí. thuật toán kết thúc  khi queue rỗng

# question4 A* sử dụng PriorityQueue và hàm heuristic 

# question5 Finding All corner gồm getStartState() (trạng thái ban đầu lưu vị trí bắt đầu và các corner đã visited), isGoalState() (kiểm tra các corner đã được visited hay chưa)
#           getSuccesors (trả về các state tiếp theo, nếu là corner và chưa visited thì append vào list, nếu không phải wall thì đi tiếp)

# question6 Corners Problem: Hàm cornersHeuristic() kiểm tra corner chưa visited và tính max của đường đi  đến các góc 

# question7 Eating All The Dots: dùng hàm mazeDistance() tính của đường đi đến các dots

# question8 hàm isGoalState() của class AnyFoodSearchProblem return true nếu vị trí trùng food 
