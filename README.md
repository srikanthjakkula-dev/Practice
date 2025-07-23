-git init
-git add
-git commit
-git config --global user.name
-git config --global user.email
-git push
-git log
-git status

 public class Maxmin{
  public static void main(String[] args) {
    int arr[]={1,4,20,7,2,6,10,15,20,11,17,16};
   int max1= Integer.MIN_VALUE;  
  int max2= Integer.MIN_VALUE;

   for (int i=0;i<arr.length;i++)
    {
        if(arr[i]>max1)
        {
            max2 = max1;
            max1=arr[i];
        } else if (arr[i] > max2 && arr[i]!=max1)
        {
            max2 = arr[i];
        }
    }
    System.out.println(max1);
    System.out.println(max2);
}
}

Decentralized and centralized system
