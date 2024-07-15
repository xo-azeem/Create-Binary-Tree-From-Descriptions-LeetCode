# Create Binary Tree From Descriptions

LeetCode Q # 2196.

You are given a 2D integer array descriptions where descriptions[i] = [parenti, childi, isLefti] indicates that parenti is the parent of childi in a binary tree of unique values. Furthermore,

- If isLefti == 1, then childi is the left child of parenti.</br>
- If isLefti == 0, then childi is the right child of parenti.

Construct the binary tree described by descriptions and return its root.

The test cases will be generated such that the binary tree is valid.

Example 1:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/9ce8ecd3-2733-4b5c-873e-1e20e18d0332)

</div>

> Input: descriptions = [[20,15,1],[20,17,0],[50,20,1],[50,80,0],[80,19,1]]</br>
> Output: [50,20,80,15,17,19]</br>
> Explanation: The root node is the node with value 50 since it has no parent.</br>
> The resulting binary tree is shown in the diagram.

Example 2:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/91acb40d-cded-4818-b809-7340fe621285)

</div>

> Input: descriptions = [[1,2,1],[2,3,0],[3,4,1]]</br>
> Output: [1,2,null,null,3,4]</br>
> Explanation: The root node is the node with value 1 since it has no parent.</br>
> The resulting binary tree is shown in the diagram.

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/3d7b3268-9893-47fd-a83d-f031567f548c)

  Time complexity: O(n).</br>Space complexity: O(n).
</div>
