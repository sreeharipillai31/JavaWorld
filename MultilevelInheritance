import java.io.*; 
class Account 
{ 
 String cust_name; 
 int acc_no; 
 Account(String n, int no) 
 { 
  acc_no=no; 
  cust_name=n; 
 } 
 void display() 
 { 
  System.out.println("Customer name = "+cust_name); 
  System.out.println("Account number = "+acc_no); 
 } 
} 
class Saving_acc extends Account 
{ 
 int saving_bal; 
 int min_bal; 
 Saving_acc(String n, int no, int sbal, int mbal) 
 { 
  super(n,no); 
  saving_bal=sbal; 
  min_bal=mbal; 
 } 
 void output() 
 { 
  display();  
  System.out.println("Saving balance ="+saving_bal); 
  System.out.println("Minimum balance = "+ min_bal); 
 } 
}  
class Acc_detail extends Saving_acc 
{ 
 int deposit, withdrawal; 
 Acc_detail(String n, int no, int sbal, int mbal, int dep, int wd) 
 { 
  super(n, no, sbal, mbal); 
  deposit=dep; 
  withdrawal=wd; 
 }
void final_result() 
{ 
output(); 
System.out.println("Deposit amount = "+ deposit); 
System.out.println("Withdrawal amount = "+ withdrawal); 
} 
} 
public class MultilevelInheritance { 
public static void main(String[] args) 
{ 
Acc_detail a=new Acc_detail("Sreehari",6031,10000,500,1000,2000); 
a.final_result(); 
} 
} 
