# maxofanarray


import java.util.Arrays;
public class Main
{
	public static void main(String[] args) {
		System.out.println("Hello World");
		int[][] arr = {
		    { 2,13,4,5},
		    {54,7,8,3},
		    {4,94,12,4}};
		maxRow(arr);
	}
	public static void maxRow(int[][] arr){
	   
	    for(int i=0;i<arr.length;i++){
	     int max=arr[0][0];
	        for(int j=0;j<arr[0].length;j++){
	            if (arr[i][j]>max)
	                max=arr[i][j];
	        }
	        System.out.println("The maximum in row "+(i+1)+" is "+max);
	        
	    }
	}
}
