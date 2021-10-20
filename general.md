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

void bubbleSort(int array[], int size) {


  for (int step = 0; step < size - 1; ++step) {
    
  
    int swapped = 0;
    
    for (int i = 0; i < size - step - 1; ++i) {
      

      if (array[i] > array[i + 1]) {

        int temp = array[i];
        array[i] = array[i + 1];
        array[i + 1] = temp;
        
        swapped = 1;
      }
    }
    

    if (swapped == 0) {
      break;
    }
    
  }
}

// print array
void printArray(int array[], int size) {
  for (int i = 0; i < size; ++i) {
    printf("%d  ", array[i]);
  }
  printf("\n");
}


int main() {
  int data[] = {-2, 45, 0, 11, -9};

  int size = sizeof(data) / sizeof(data[0]);

  bubbleSort(data, size);
  
  printf("Sorted Array in Ascending Order:\n");
  printArray(data, size);
}

`


## My Favorite Kind Of Airplane

![](https://www.piper.com/wp-content/uploads/2019/01/19_Seneca_A2A_Ocean-Sunrise-1650x1100.jpg)
