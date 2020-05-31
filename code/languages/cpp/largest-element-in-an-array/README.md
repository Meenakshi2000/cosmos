FINDING LARGEST ELEMENT IN AN ARRAY 

We are given an integer array of size N or we can say number of elements is equal to N.
We have to find the largest/ maximum element in an array. 

Approach:
Firstly, program asks the user to input the values. So, user enter the size of array i.e. N and then enter the elements of array. Afterwards, program gives the output i.e. largest element in the entered array.
We assign the first element value to the temp variable.
Then we compare temp with all other elements inside a loop.
If the temp is larger than all other elements,
Then we return temp which store first element value as largest element.
But if the element is larger than the temp,
Then we store that element value into temp.
This way temp will always store the largest value.
Then we return temp.
Time complexity: O(N) where there are N elements in the array
Space complexity: O(1)

Link to the article: https://iq.opengenus.org/largest-element-in-an-array/

A massive collaborative effort by : https://github.com/OpenGenus/cosmos  -OpenGenus Foundation 
