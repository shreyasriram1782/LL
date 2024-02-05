Dummy node concept:
we use dummy nodes when we want to modify the existing linked list.

How we use dummy nodes:
  First create a node with a dummy val like 0
  initialize it to starting of the LL. i.e dummy.next = head
  if you have any pointers to be initialised u can initialise it to dummy instead of head.
  we are doing all of this instead of using head.
  because if we dont use dummy node:
  
What happens when yuou dont use dummy node:
  lets say if u have a question to delete nth node from the end,
  if the nth node from end is heaad itself, then you not have head if you delete it.
  beacuse normally you return head or head.next after doing everything. 
  so in this case if you delete head, you should update the head to a new node again. 
  instead if we use a dummy node u can do everything and then return dummy or dummy.next

