// import static org.junit.jupiter.api.Assertions.assertEquals;
import java.util.ArrayList;
// import org.junit.jupiter.api.Test;

class intList {
  private int[] list;
  public intList(int[] list) {
    this.list = list;
  }
  public ArrayList<Integer> reversedList(){
    ArrayList<Integer> reverse = new ArrayList<Integer>();
    for (int i = list.length - 1; i >= 0; i--){
      reverse.add(list[i]);
    }
    return reverse;
  }
  public int highestVal(){
    int high = list[0];
    for (int i = 0; i <= list.length - 1; i++){
      if(list[i] > high){
        high = list[i];
      }
    }
    return high;
  }
  

  // @Test
  // void addition() {
  //     assertEquals(2, 1 + 1);
  // }
  
}
public class Main{
  public static void main(String[] args) {
    int[] list = {10, 20, 40, 55, 6};
    intList listA = new intList(list);
    System.out.println(listA.highestVal());
    int[] list2 = {4, 5, 6, 7, 8, 9};
    intList listB = new intList(list2);
    System.out.println(listB.reversedList());
  }
}
