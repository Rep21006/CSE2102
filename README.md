# CSE2102
Lab 1:
Hybrid Car MPGe and MPG calculator

This project calculates the The MPG when in fully gas mode, the MPGe when in fully electric mode, and the average MPG when in half-gas/half-electric hybrid mode. Thi also contains the test for each of those functions.


How It's Made:
Tech used: Java

This project was made by creating two interfaces one for gasoline and an electic interface containing the functions to get set and calculate the mpg and the mpge. The hybrid class then impliments those fucntions and the Hybridcar class creates an instance of the hybrid class and has values that it uses to calculate the mpg and mpge. The hybrid test function was made by asserting wheter the values returned by the functions were the correct ones.

I then Used the following commands to compile everything, run HybridCar and test HybridTest:
javac -cp junit-4.13.2.jar "ElectricInterface.java" "GasolineInterface.java" "Hybrid.java" "HybridCar.java" "HybridTest.java"

java HybridCar 

java -cp "junit-4.13.2.jar:hamcrest-core-1.3.jar:" org.junit.runner.JUnitCore HybridTest 
