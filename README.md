#include
using namespace std;

int main() {
setlocale(0, " ");
char operatorSymbol;
double num1, num2;

cout << "Введите оператор (+, -, *, /): ";
cin >> operatorSymbol;

cout << "Введите два числа: ";
cin >> num1 >> num2;

switch (operatorSymbol) {
case '+':
cout << num1 << " + " << num2 << " = " << num1 + num2;
break;
case '-':
cout << num1 << " - " << num2 << " = " << num1 - num2;
break;
case '*':
cout << num1 << " * " << num2 << " = " << num1 * num2;
break;
case '/':
if (num2 != 0)
cout << num1 << " / " << num2 << " = " << num1 / num2;
else
cout << "Ошибка: Деление на ноль запрещено!";
break;
default:
cout << "Ошибка: Введен недопустимый оператор.";
break;
}

return 0;
}
