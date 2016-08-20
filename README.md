# Snake
public class Solution
{
    public static void main(String[] args) throws Exception
    {
        BufferedReader reader  = new BufferedReader(new InputStreamReader(System.in));
        int [] b = new int[5];
        for (int i=0; i<5; i++)
        {
            int a = Integer.parseInt(reader.readLine());
            b[i] = a;
        }
        Arrays.sort(b);
        for (int i=0; i<5; i++)
        {

            System.out.println(b[i]);
        }
        
    }
