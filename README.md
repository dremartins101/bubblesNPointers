# bubblesNPointers



## main
make constant MAX, for max length of array
function sort(array):
    create integer variables i and j
    for i from 0 to MAX - 1:
        for j from 0 to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)

## printValues
	void printValues(int* )
	step thru array with a for loop
	print each member of the array
print newline at the end
return void

```


## Swap	


```

void swap(int* a, int* b)
	takes two int pointer parameters
	make a temp integer called temp
	copy value at a to temp
