#include <iostream> 
 
int soma(int a, int b)
{
 return a + b;
}
int subtraçao(int a, int b)
{
 return a - b;
}
int multiplicaçao(int a, int b)
{
 return a * b;
}
float divisao(float a, float b)
{
 return a / b;
}

int main() 
{
 int resultado1 = soma(25,82);
 int resultado2 = subtraçao(78,32);
 int resultado3 = multiplicaçao(42,33);
 float resultado4 = divisao(66,33);

 std::cout << "O resultado da soma e:" << resultado1 << std::endl;
 std::cout << "O resultado da subtraçao e:" << resultado2 << std::endl;
 std::cout << "O resultado da multiplicaçao e:" << resultado3 << std::endl;
 std::cout << "O resultado da divisao e:" << resultado4 << std::endl;
return 0;
}
