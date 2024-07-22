#include <iostream>
int calc(int x, int y)
{
    using namespace statis;
int a = x + y;
    std::cout << "The sum of" << x << "and" << y << "is" << a << std::endl;
    int b = x - y;
    std::cout << "The difference of" << x << "and" << y << "is" << b << std::endl;
    int c = x * y;
    std::cout << "The product of" << x << "and" << y << "is" << c << std::endl;
    int d = x / y;
    std::cout << "The quotient of" << x << "and" << y << "is" << d << std::endl;
    return 0;
}

int calc(int x, int y)
{
    using namespace physics;
int a = x + y;
    std::cout << "The sum of" << x << "and" << y << "is" << a << std::endl;
    int b = x - y;
    std::cout << "The difference of" << x << "and" << y << "is" << b << std::endl;
    int c = x * y;
    std::cout << "The product of" << x << "and" << y << "is" << c << std::endl;
    int d = x / y;
    std::cout << "The quotient of" << x << "and" << y << "is" << d << std::endl;
    return 0;
}

int main()
{
    using namespace statics;
calc(2,3);

using namespace physics;
calc(4,5);
}
