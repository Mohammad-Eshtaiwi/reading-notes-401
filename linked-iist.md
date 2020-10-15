# Linked list

Linked list is a data structure that is liner like arrays but not stored in particular memory location.

- Each element have 2 parts (value,next) the first node called node
- Last element next will be always null

<img src="./linked-list.png">

<br>
<br>

## linked list methods

```
class ListNode {
    constructor(data) {
        this.data = data
        this.next = null
    }
}
```

clear:

```
clear() {
    this.head = null;
}
```

getLast:

```
getLast() {
    let lastNode = this.head;
    if (lastNode) {
        while (lastNode.next) {
            lastNode = lastNode.next
        }
    }
    return lastNode
}
```

getFirst:

```
getFirst() {
    return this.head;
}
```
