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

