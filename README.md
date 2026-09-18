//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
void main() {

    int intOperandA = 22;
    int intOperandB = 44;
    int intSum = 0;
    int intProduct = 0;
    int intDifference = 0;
    int intQuotient = 0;
    int intModulo = 0;

    intSum = intOperandA + intOperandB; //sum of 22 and 44
    IO.println("the sum of " + intOperandA + " + " + intOperandB + " is " + intSum);

    intProduct = intOperandA * intOperandB;
    IO.println("The product of " + intOperandA + " * " + intOperandB + " is " + intProduct);

    intDifference = intOperandA - intOperandB;
    IO.println("The product of " + intOperandA + " - " + intOperandB + " is " + intDifference);

    intQuotient = intOperandA / intOperandB;
    IO.println("The product of " + intOperandA + " / " + intOperandB + " is " + intQuotient);

    intModulo = intOperandA % intOperandB;
    IO.println("The modulo of " + intOperandA + " % " + intOperandB + " is " + intModulo);

    double doubleOperandA = 15.50;
    double doubleOperandB = 12.20;
    double doubleSum = 0;
    double doubleProduct = 0;
    double doubleDifference = 0;
    double doubleQuotient = 0;

    doubleSum = doubleOperandA + doubleOperandB;
    IO.println("The sum of " + doubleOperandA + " + " + doubleOperandB + " is " + doubleSum);

    doubleDifference = doubleOperandA - doubleOperandB;
    IO.println("The sum of " + doubleOperandA + " - " + doubleOperandB + " is " + doubleDifference);

    doubleProduct = doubleOperandA * doubleOperandB;
    IO.println("The sum of " + doubleOperandA + " * " + doubleOperandB + " is " + doubleProduct);

    doubleQuotient = doubleOperandA / doubleOperandB;
    IO.println("The sum of " + doubleOperandA + " / " + doubleOperandB + " is " + doubleQuotient);
}
