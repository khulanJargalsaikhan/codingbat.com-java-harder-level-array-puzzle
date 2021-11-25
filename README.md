# codingbat.com-java-harder-level-array-puzzle

*fix34*

	Return an array that contains exactly the same numbers as the given array, 
	but rearranged so that every 3 is immediately followed by a 4. Do not move the 3's, 
	but every other number may move. The array contains the same number of 3's and 4's, 
	every 3 has a number after it that is not a 3, and a 3 appears in the array before any 4.


	fix34([1, 3, 1, 4]) 		-- [1, 3, 4, 1]
	fix34([1, 3, 1, 4, 4, 3, 1]) 	-- [1, 3, 4, 1, 1, 3, 4]
	fix34([3, 2, 2, 4]) 		-- [3, 4, 2, 2]



*canBalance*

	Given a non-empty array, return true if there is a place to split 
	the array so that the sum of the numbers on one side is equal 
	to the sum of the numbers on the other side.


	canBalance([1, 1, 1, 2, 1]) 	- true
	canBalance([2, 1, 1, 2, 1]) 	- false
	canBalance([10, 10]) 		- true

*linearIn*

	Given two arrays of ints sorted in increasing order, outer and inner, 
	return true if all of the numbers in inner appear in outer. 
	The best solution makes only a single "linear" pass of both arrays, 
	taking advantage of the fact that both arrays are already in sorted order.


	linearIn([1, 2, 4, 6], [2, 4]) 		-- true
	linearIn([1, 2, 4, 6], [2, 3, 4]) 	-- false
	linearIn([1, 2, 4, 4, 6], [2, 4]) 	-- true
	
	
	
	
