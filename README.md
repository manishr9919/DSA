# DSA
 # Linked_List question  # 

**01 : add the Element 10,20,30 and print**
```

class node {
constructor(data) {
this.data = data;
this.next = null;
}
}
const head=new node(10)
const second=new node(20)
const third=new node(30)
head.next=second
second.next=third

let current =head
while(current){
console.log(current.data)
current=current.next
}
```

