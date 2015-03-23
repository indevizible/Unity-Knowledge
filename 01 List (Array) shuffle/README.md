# Array Shuffle

## Overview

**ใช้สำหรับ** สุ่มสับเปลี่ยน Array ที่เป็น IList\<T\> .

## Code (Helper.cs)

```c#
static class Helpers
{
	public static void Shuffle<T>(this IList<T> list)  
	{  
		System.Random rng = new System.Random();  
		int n = list.Count;  
		while (n > 1) {  
			n--;  
			int k = rng.Next(n + 1);  
			T value = list[k];  
			list[k] = list[n];  
			list[n] = value;  
		}  
	}
}

```

## Example

```c#
List<int> array = new List<int>{1,2,3,4,5,6}();
array.Shuffle();
```


## Refference 

*	http://stackoverflow.com/questions/273313/randomize-a-listt-in-c-sharp


## Keyword
*	How to shuffle array List<T> [3]

Edit by [Nattawut Singhchai](wut@2bsimple.com)