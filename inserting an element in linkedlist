
#inserting an element 
import java.util.*;
class Main
{
  class Node{
    int data;
    Node next;
    Node(int a)
    {
      this.data=a;
      this.next=null;
    
    }
  }
  Node head=null;
  Node temp=null;
      
  void ins(int a){
    Node nn=new Node(a);
    if(head==null){
      head=nn;
      temp=nn;
    }
    else{
      temp.next=nn;
      temp=nn;
    }
      
  }
  void print(){
   temp=head;
    while(temp!=null){
      System.out.println(temp.data);
      temp=temp.next;
    }
  }
  public static void main(String args[])
  {
    Scanner in=new Scanner(System.in);
    Main o=new Main();
    
    
    while(true){
      int a=in.nextInt();
      if(a>0){
        o.ins(a);
      }
      else{
        break;
      }
     
  
  }
  o.print();
}
}
  
