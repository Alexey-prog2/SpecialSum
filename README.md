using System;
    
public class Program
{
static int SpecialSum(int a, int b)
{
/*return specialSum (5 + 2)
if specialSum => 10 && <= 19{
  Console.WriteLine("20")
  else {
    Console.WriteLine(SpecialSum)
  }
}
return specialSum (11 + 10)
if specialSum => 10 && <= 19{
  Console.WriteLine("20")
  else{
    Console.WriteLine(SpecialSum)
  }
}
}
*/
    
            sumRes = SpecialSum(5, 2);
Console.WriteLine("Result: {0}; expected: 7; successfully: {1}",sumRes, sumRes == 7);
sumRes = SpecialSum(11, 10);
Console.WriteLine("Result: {0}; expected: 21; successfully: {1}",sumRes, sumRes == 21);

}
