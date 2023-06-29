
# Find leaf node

This is a function that returns true if the node is leaf node else returns false

```
bool isLeaf(Node* root)
 {
     return !root->left && !root->right;
 }
```
