using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using AwesomeCalculator;
using NUnit.Framework;


namespace Calculator_Test
{
    [TestFixture]
    public class CalcTests
    {
        [Test]
        public void GetAddition_Input2point4and8point6_Returns11point0()
        {
            //Arrange
            double number1 = 2.4;
            double number2 = 8.6;

            double expectedResult = number1 + number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }
        [Test]
        public void GetAddition_Input5point5and9point6_Returns15point1()
        {
            //Arrange
            double number3 = 5.5;
            double number4 = 9.6;

            double expectedResult = number3 + number4;
            Calc testCalc = new Calc(number3, number4);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }


        [Test]
        public void GetAddition_Input3point3and7point3_Returns10point6()
        {
            //Arrange
            double number5 = 3.3;
            double number6 = 7.3;

            double expectedResult = number5 + number6;
            Calc testCalc = new Calc(number5, number6);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input3point0and2point0_Returns1point0()
        {
            //Arrange
            double number22 = 3.0;
            double number23 = 3.0;

            double expectedResult = number22 - number23;
            Calc testCalc = new Calc(number22, number23);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetSubtraction_Input12point0and2point0_Returns9point0()
        {
            //Arrange
            double number22 = 12.0;
            double number23 = 9.0;

            double expectedResult = number22 - number23;
            Calc testCalc = new Calc(number22, number23);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input16point0and12point0_Returns4point0()
        {
            //Arrange
            double number33 = 16.0;
            double number34 = 12.0;

            double expectedResult = number33 - number34;
            Calc testCalc = new Calc(number33, number34);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetMultiplication_Input6point0and7point0_Returns42point0()
        {
            //Arrange
            double number43 = 6.0;
            double number44 = 7.0;

            double expectedResult = number43 * number44;
            Calc testCalc = new Calc(number43, number44);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetMultiplication_Input4point5and12point0_Returns54point0()
        {
            //Arrange
            double number53 = 4.5;
            double number54 = 12.0;

            double expectedResult = number53 * number54;
            Calc testCalc = new Calc(number53, number54);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input12point0and14point0_Returns168point0()
        {
            //Arrange
            double number63 = 12.0;
            double number64 = 14.0;

            double expectedResult = number63 * number64;
            Calc testCalc = new Calc(number63, number64);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input10and2_Returns5()
        {
            //Arrange
            double number73 = 10;
            double number74 = 2;

            double expectedResult = number73 / number74;
            Calc testCalc = new Calc(number73, number74);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input200and2_Returns100()
        {
            //Arrange
            double number1 = 200;
            double number2 = 2;

            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input55and5_Returns11()
        {
            //Arrange
            double number1 = 55;
            double number2 = 5;

            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetDivision_Input1and3_Returns0point33()
        {
            //Arrange
            double number1 = 1;
            double number2 = 3;

            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input2and1_Returns2()
        {
            //Arrange
            double number1 = 2;
            double number2 = 1;

            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input9and3_Returns3()
        {
            //Arrange
            double number1 = 9;
            double number2 = 3;

            double expectedResult = number1 / number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

    }





}


   

