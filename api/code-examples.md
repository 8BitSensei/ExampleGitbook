# Code Examples

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Hac habitasse platea dictumst quisque sagittis purus. Imperdiet massa tincidunt nunc pulvinar sapien. Elit eget gravida cum sociis. Sit amet mauris commodo quis imperdiet massa tincidunt nunc pulvinar. Odio ut sem nulla pharetra diam sit amet nisl suscipit. Pulvinar elementum integer enim neque volutpat ac tincidunt. Tincidunt praesent semper feugiat nibh. Elit scelerisque mauris pellentesque pulvinar pellentesque habitant. Interdum posuere lorem ipsum dolor sit amet consectetur.



```java
import java.util.*; 
  
public class LowestCommonMultiple { 
  
    private static long
    lcmNaive(long numberOne, long numberTwo) 
    { 
  
        long lowestCommonMultiple; 
  
        lowestCommonMultiple 
            = (numberOne * numberTwo) 
              / greatestCommonDivisor(numberOne, 
                                      numberTwo); 
  
        return lowestCommonMultiple; 
    } 
  
    private static long
    greatestCommonDivisor(long numberOne, long numberTwo) 
    { 
  
        if (numberTwo == 0) 
            return numberOne; 
  
        return greatestCommonDivisor(numberTwo, 
                                     numberOne % numberTwo); 
    } 
    public static void main(String args[]) 
    { 
  
        Scanner scanner = new Scanner(System.in); 
        System.out.println("Enter the inputs"); 
        long numberOne = scanner.nextInt(); 
        long numberTwo = scanner.nextInt(); 
  
        System.out.println(lcmNaive(numberOne, numberTwo)); 
    } 
} 
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Odio ut sem nulla pharetra diam sit amet. Pellentesque adipiscing commodo elit at imperdiet. Iaculis eu non diam phasellus vestibulum lorem sed risus. Semper risus in hendrerit gravida rutrum. In pellentesque massa placerat duis ultricies lacus sed turpis. Tincidunt praesent semper feugiat nibh sed pulvinar proin gravida. Nec ultrices dui sapien eget mi proin sed libero. Turpis massa sed elementum tempus egestas. Ultricies tristique nulla aliquet enim tortor at auctor. Lectus sit amet est placerat in egestas erat. Eget dolor morbi non arcu risus.

