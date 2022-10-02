#1


Console.WriteLine("Введи цифру дня недели: ");
int dayNumber = Convert.ToInt32(Console.ReadLine()); 



void CheckingTheDayOfTheWeek (int dayNumber) {

if (dayNumber == 6 || dayNumber == 7) {

Console.WriteLine("(это выходной) -> да");
}
else if (dayNumber < 1 || dayNumber > 7) {

Console.WriteLine("данного дня недели не существует");
}
else Console.WriteLine("(это не выходной) -> нет");
}
CheckingTheDayOfTheWeek(dayNumber);


#2



Console.Write("Введите число: ");
int anyNumber = Convert.ToInt32(Console.ReadLine());

string anyNumberText = Convert.ToString(anyNumber);

if (anyNumberText.Length > 2){
Console.WriteLine("третья цифра -> " + anyNumberText[2]);

}
else {
Console.WriteLine("-> третьей цифры нет");

}

#3


Console.WriteLine("Введите трехзначное число");
while(true) 
{
string input = Console.ReadLine();

if(!input.Equals("exit"))

    Console.WriteLine("{0}->{1}",input, input[1]);
    
else
  break;
}
