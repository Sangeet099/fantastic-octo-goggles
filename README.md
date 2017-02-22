class Hathi
{
static void triangleA(int x[][])
{
 for(i=0;i<x.length;i++)
  {
   for(j=0;j<x[i].length;j++)
   {
   System.out.print(" "+x[i][j]+" ");
   }
  } 
}
public static void main(String... s)
{
  triangleA(new int[][]{{2,4,3},{1,8,9},{2,4,9}});
}
}
