var connect = function(root) {
     let curr = root, head = null, prev = null;
        while (curr != null) {
            while (curr != null) {
                if (curr.left != null) {
                    if (head == null) head = curr.left;
                    if (prev != null) prev.next = curr.left;
                    prev = curr.left;
                }
                if (curr.right != null) {
                    if (head == null) head = curr.right;
                    if (prev != null) prev.next = curr.right;
                    prev = curr.right;
                }
                curr = curr.next;
            }
            curr = head;
            prev = null;
            head = null;
        }
        return root;
    }



/*
Success
Details 
Runtime: 84 ms, faster than 97.90% of JavaScript online submissions for Populating Next Right Pointers in Each Node II.
Memory Usage: 43.9 MB, less than 32.95% of JavaScript online submissions for Populating Next Right Pointers in Each Node II.
*/
