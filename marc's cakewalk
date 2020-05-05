import java.util.*;
class Solution
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        long count=0;
        int i,j=0;
        int al[]=new int[n];
        for(i=0;i<n;i++)
        {
          al[i]=sc.nextInt();

        }
        Arrays.sort(al);
        for(i=n-1;i>=0;i--)
        {   
              count+=(long)(al[i]*(Math.pow(2, j)));
             j++;
        }
        System.out.println(count);
    }
}
