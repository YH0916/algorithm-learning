# Algorithm Learning

算法与深度学习学习笔记，以 Jupyter Notebook 形式记录。

## 仓库内容

### 数据结构

| 文件 | 主题 | 说明 |
|------|------|------|
| `ListNode.ipynb` | 单链表 | 链表创建、头插/尾插/中间插入、删除头尾节点 |
| `DoublyListNode.ipynb` | 双向链表 | 双向链表创建、插入与删除操作 |
| `CycleArray.ipynb` | 环形数组 | 利用求模运算实现环形数组，`start`/`end` 指针管理 |
| `hashmap.ipynb` | 哈希表 | 拉链法与线性探查法、双链表实现哈希表、数组增强哈希表 |
| `BinaryTree.ipynb` | 二叉树 | 递归与非递归（栈）遍历：前序、中序、后序 |
| `N_Tree.ipynb` | N 叉树 | DFS 递归遍历、BFS 层序遍历、带深度信息的遍历 |
| `PriorityQueue.ipynb` | 二叉堆 / 优先级队列 | 大顶堆与小顶堆原理、`sink` 下沉与 `swim` 上浮操作 |

### 算法刷题

| 文件 | 主题 | 说明 |
|------|------|------|
| `hot100.ipynb` | LeetCode Hot 100 | 滑动窗口（无重复最长子串、字母异位词）、子数组求和等高频题解 |
| `test.ipynb` | 股票买卖 | 动态规划解法，支持最多 k 笔交易的最大利润 |
| `tools.ipynb` | DP 工具模板 | 一维/二维/三维 DP 数组初始化模板 |

### 深度学习

| 文件 | 主题 | 说明 |
|------|------|------|
| `deeplearning.ipynb` | Transformer 核心组件 | 固定位置编码（Positional Encoding）、单头注意力机制、多头注意力机制（MHA） |

## 技术栈

- **Python 3**
- **Jupyter Notebook**
- **PyTorch**（深度学习部分）

## 使用方式

```bash
# 克隆仓库
git clone https://github.com/YH0916/algorithm-learning.git

# 安装依赖（深度学习部分）
pip install torch

# 启动 Jupyter
jupyter notebook
```

## License

MIT
