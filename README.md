
int CutNumber(int number)
/*
{
    int ed = number % 10;
    int sot = number / 100;

    number = sot * 10 + ed;
    return number;
}

int num = new Random().Next(100,1000);

int result = CutNumber(num);
Console.WriteLine($"New version of a number {num} is {result}");
// 345
*/


// Задача 10.Напишите программу,которая принимает на вход трехзначное число и на выходе показывает вторую цифру этого числа.
/*
int ThirdNumber(int number)

{
    int sot = number % 100;
    int ed = number / 10;

    number = ed % 10;
    return number;
}

int num = new Random().Next(100,1000);

int result = ThirdNumber(num);
Console.WriteLine($"New version of a number {num} is {result}");
*/
// 782

// Задача 13.Напишите программу,которая выводит третью цифру заданного числа или сообщает , что третьей цифры нет.
/*
int ProgramNumber(int program)
{
    int ed = program % 10;
    int sot = program / 100;

    program = sot % 10 ;
    return program;
}

int num = new Random().Next(10000,99999);

int result = ProgramNumber(num);
Console.WriteLine($"New version of a number {num} is {result}");
//32679
*/

// Задача 15.Напишите программу,которая принимает на вход цифру,обозначающую день недели,и проаеряет,является ли этот день выходным.
/*
Console.Write("Weekday number: ");
int n = Convert.ToInt32(Console.ReadLine());

if(n > 0 && n <=5)

{
    Console.WriteLine("This is not weekday");
}
else
{
    Console.WriteLine("This is a weekday");
}
*/
