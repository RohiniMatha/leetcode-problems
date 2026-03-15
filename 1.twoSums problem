import java.util.Scanner;
class Solution
{
    public int[] twoSum(int[] nums, int target) 
    {
for(int i=0;i<nums.length;i++)
{
    for(int j=i+1;j<nums.length;j++)
    {
        if(nums[i]+nums[j]==target)
        {
            return new int[]{i,j};
        }
    }
    
}
return new int[]{};
}
 public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
         System.out.println("Enter the value of target");
         int target=sc.nextInt();
         System.out.println("Enter the number of elements");
         int n=sc.nextInt();
        int nums[] = new int[n];
         System.out.println("Enter the values of the   array:");
         for(int i=0;i<nums.length;i++)
         {
            nums[i]=sc.nextInt();
         }
Solution ob=new Solution();
int result[]=ob.twoSum(nums,target);
System.out.println("["+result[0]+","+result[1]+"]");

    }
}
