Использование this->: 

this нужно, если поля класса и переменные в методе (конструкторе) одинаковые. 
this->x - обращение к полю x

class Toch{

private:
int x;
int y;


public:
Point(int x, int y)
    {
        this->x = x; 
        this->y = y;
    }


};