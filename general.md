# Hi There! My Name is Jacob Woods

Hi there! My name is Jacob Woods and I am a IT freshman at the Univeristy of Missouri in Columbia, Missouri. **I abosolutely love coding** In addition I have an interest in **aviation**. 

> Feel free to keep reading if you would like to find out more!

## Another Interesting Fact
* About a Year Ago I Knew Nothing About Code

## My Favorite Foods
1. Pizza
2. Pasta
3. Smoked Salmon
4. Iced Coffee 

## My Favorite Sorting Algorithm
`

`using` `namespace` `std;`

`void` `swap(``int` `*xp,` `int` `*yp)`

`{`

`int` `temp = *xp;`

`*xp = *yp;`

`*yp = temp;`

`}`

`// A function to implement bubble sort`

`void` `bubbleSort(``int` `arr[],` `int` `n)`

`{`

`int` `i, j;`

`for` `(i = 0; i < n-1; i++)`

`// Last i elements are already in place`

`for` `(j = 0; j < n-i-1; j++)`

`if` `(arr[j] > arr[j+1])`

`swap(&arr[j], &arr[j+1]);`

`}`

`/* Function to print an array */`

`void` `printArray(``int` `arr[],` `int` `size)`

`{`

`int` `i;`

`for` `(i = 0; i < size; i++)`

`cout << arr[i] <<` `" "``;`

`cout << endl;`

`}`

`// Driver code`

`int` `main()`

`{`

`int` `arr[] = {64, 34, 25, 12, 22, 11, 90};`

`int` `n =` `sizeof``(arr)/``sizeof``(arr[0]);`

`bubbleSort(arr, n);`

`cout<<``"Sorted array: \n"``;`

`printArray(arr, n);`

`return` `0;`

`}`



## My Favorite Kind Of Airplane

![](https://www.piper.com/wp-content/uploads/2019/01/19_Seneca_A2A_Ocean-Sunrise-1650x1100.jpg)