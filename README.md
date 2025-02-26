Download link :https://programming.engineering/product/hw0-java-practice-introduction/


# HW0-Java-Practice-Introduction
HW0: Java Practice &amp; Introduction
Showing Your Work

There are three ways of showing your work. Any of these ways will help you earn “effort” credit. Following these practices will also help us verify that your work is your own. This helps you avoid being falsely accused of academic dishonesty.

You should add comments that explain the key ideas behind your approach. We’ve added placeholders in HW0.java where you can do this.

You may also add additional test cases in order to ensure that your code is 100% correct.

Remember that you can consult outside resources and work with other students as long as you write up your own solutions and cite any links or people you received help from within citations.txt. See syllabus/collaboration for details.

Q1: maxOfArray (3 points)

int testResult1 = maxOfArray(new int[] {1, 3, 4, 5, 2});

int testResult2 = maxOfArray(new int[] {-1, -3, -4, -5, -2});

System.out.println(testResult1); // should output 5 System.out.println(testResult2); // should output -1

maxOfArray(new int[] {}); // Should throw IllegalArgumentException

Q2: twoSum (3 points)

Write twoSum, which takes in an array of integers and a target sum, and returns a 2-element array that represents two distinct indices of elements that sum up to the target value. Some examples:

int[] testResult3 = twoSum(new int[] {0, 2, 3, 4, 5}, 6); int[] testResult4 = twoSum(new int[] {1, 2, 3, 4, 5}, 10);

System.out.println(Arrays.toString(testResult3)); // should output [1, 3] System.out.println(Arrays.toString(testResult4)); // should output [-1, -1]

● In the first example, arr[1] + arr[3] = 2 + 4 = 6.

In the second example, we returned [-1, -1] because there are not two distinct elements within the array that sum to 10 (you can’t use 5 twice).

Q3 (4 points)

Write add, which given two numbers represented as Lists of single-digit integers, returns their sum as a list of integers. Some examples:

List<Integer> testResult5 = add(Arrays.asList(1, 2, 3), Arrays.asList(2, 4, 2));

List<Integer> testResult6 = add(Arrays.asList(9, 9, 9), Arrays.asList(1));

123 + 242 = 365

[1, 2, 3], [2, 4, 2] => [3, 6, 5] System.out.println(testResult5); // should output [3, 6, 5]

999 + 1 = 1000

[9, 9, 9], [1] => [1, 0, 0, 0] System.out.println(testResult6); // should output [1, 0, 0, 0]
