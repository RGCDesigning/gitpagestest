# Home/Title
Reverse Array Method
```
public static int[] reverseArray(int[] inputArray)
	{
		int x, y;
		if(inputArray.length % 2 > 0)
		{
			for(int i = 0; i < (inputArray.length-1) / 2; i++)
			{
				x = inputArray[i];
				inputArray[i] = inputArray[(inputArray.length-1) - i];
				inputArray[(inputArray.length-1) - i] = x;
			}
		}
		else
		{
			for(int i = 0; i < (inputArray.length) / 2; i++)
			{
				x = inputArray[i];
				inputArray[i] = inputArray[(inputArray.length-1) - i];
				inputArray[(inputArray.length-1) - i] = x;
			}
		}
		return inputArray;
	}
```
