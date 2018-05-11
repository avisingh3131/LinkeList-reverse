# LinkeList-reverse
// LinkedList-implementation-in-Java
//single LinkedList-implementation
 class Node{
   int data;
   Node next;
 }
  class LinkedList{
     Node head=null;
 //to insert a new value at the given position
     void insert(int data){
       Node node=new Node();
        node.data=data;
        node.next=null;
       if(head==null)
        head=node;
        else{
         Node node1=head;
     while(node1.next!=null){
         node1=node1.next;
             }node1.next=node;
        }
  }
  //reverse the LinkedList by traversing.
 void reverse(){
    Node current,prev,next1;
    current=head;
    prev=null;
    while(current!=null){
    next1=current.next;
    current.next=prev;
    prev=current;
    current=next1;
    }head=prev;
 }

//to print the data by traversing the LinkedList
   void print(){
         Node temp=head;
        while(temp!=null){
      System.out.print(temp.data);
      System.out.print(" ");
       temp=temp.next;
          }
      }
   }
  public class MyClass{
    public static void main(String[] args){
     LinkedList l=new LinkedList();
     l.insert(1);
     l.insert(2);
     l.insert(3);
      l.insert(4);
      l.insert(5);
       l.print();
      l.reverse();
       System.out.println();
      System.out.println("after reverse:-");
      l.print();
    }
  }
  //o/p:-1 2 3 4 5
   //    after reverse:-
  //     5 4 3 2 1
