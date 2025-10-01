/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package cal;

/**
 *
 * @author dell`
 */
public class CaL {
void sum(){
    int x=10;
    int y=20;
    int z=x+y;
    System.out.println("tha sum="+z);         
}
    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        CaL a=new CaL();
 a.sum();
    
  math m=new math();
m.mult(10,2);
    }
    
    
}
class math{
    
    int mult (int a,int b){
        
        int R=a*b;
        System.out.println("the mull="+R);
        return R;
    }
}
