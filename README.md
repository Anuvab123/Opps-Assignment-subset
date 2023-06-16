# Opps-Assignment-subset:
In this implementation, we create a class ZeroSumSubsetFinder to encapsulate the logic for finding a subset with a zero sum. The input array nums is stored as an instance variable.

The findZeroSumSubset method serves as the entry point for finding the subset. It initializes an empty list and calls the private findSubset method to perform the recursive search.

The findSubset method is a recursive helper function that takes an additional index parameter to keep track of the current element being considered, a sum parameter to keep track of the current sum of elements in the subset, and a subset parameter to store the subset elements.

The logic for finding the zero sum subset remains the same as the previous solution. It includes or excludes the current element from the subset and recursively calls itself with the updated index and sum. If a zero sum subset is found, it returns true. If no such subset is found, it returns false.

The main method creates an instance of ZeroSumSubsetFinder with the input array [-4, 1, 3, -2, -1] and calls the findZeroSumSubset method. It then prints the result accordingly.

The output for the provided example array would be the same as before:
Zero sum subset:
3 -2 -1

This solution follows the principles of object-oriented programming by encapsulating the logic within a class and providing a public interface (findZeroSumSubset method) to interact with the class.

![Screenshot (71)](https://github.com/Anuvab123/Opps-Assignment-subset/assets/112776528/e536e57e-d227-450f-b20c-29468e89c073)
