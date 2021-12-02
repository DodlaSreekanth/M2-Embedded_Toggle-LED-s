# TEST PLAN:

![image](![Screenshot (23)](https://user-images.githubusercontent.com/94154289/144221801-11324270-be42-4196-8abd-477480cd73dc.png)
)

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------ |-------------|----------------|------------------|
|  H_01       |If one switch on                                              |one led glow |  led1 glow  |  led1 glow     |condition  based  |
|  H_02       |Both switches on                                              |Both led's glow| led1 and led2 glow | both glow|condiyion based|


## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       |Second switch on first switch off                             |one led glow| 2nd led glow| led2 glow      | condition based  |
|  L_02       |first switch on second switch off                             |one led glow| 1st led glow| led1 glow      | condition based  |

# HIGH LEVEL TEST PLAN

1.Check if the calculator is a normal calculator or a scientific calculator.

2.Verify that all the buttons are present and text written on them is readable.

3.Check the arithmetic operations are working fine- +, -, /, * etc.

4.Verify that BODMAS is applied in case of complex queries and the correct result is returned.

5.Verify that the calculator gives the correct result in case of operations containing decimal numbers.

# LOW LEVEL TEST PLAN

1.Verify the number of digits allowed to enter in the calculator for any operation.

2.Verify the limit of the response value.

3.Verify the functioning of memory functions.

4.Check if the calculator allows navigating through previous calculations

5.Verify that on pressing two operators one after the other, the latest one will override the previous operator.


