Задача 10: Напишите программу, которая принимает на вход трёхзначное число и
на выходе показывает вторую цифру этого числа

Console.Write("Enter a 3-digit number:");
try {
	int Value = Convert.ToInt32(Console.ReadLine());
	int Length = Value.ToString().Length;
	if (Length == 3) {
		int result = ( Value/10 ) % 10;
		Console.WriteLine($"The second digit is {result}");
	} else {
		Console.WriteLine("Not a 3-digit number");
	}
} catch (System.Threading.ThreadAbortException) {
	System.Threading.Thread.ResetAbort();
} catch (Exception e) {
	Console.WriteLine(e.Message);
}

Задача 13: Напишите программу, которая выводит третью цифру заданного числа или сообщает,
что третьей цифры нет

Console.Write("Enter a number:");
int Value2 = Convert.ToInt32(Console.ReadLine());
int Length2 = Value2.ToString().Length;
if (Length2 >= 3) {
	while (Value2 > 999)
	{
		Value2 = Value2 / 10;
	}
	int result = Value2 % 10;
	Console.WriteLine("The third digit is " + result);
} else {
	Console.WriteLine("The number contains less than 3 digits");
}

Задача 15: Напишите программу, которая принимает на вход цифру, обозначающую день недели, и проверяет,
является ли этот день выходным

Console.Write("Enter a day of week");
int Day = Convert.ToInt32(Console.ReadLine());
if (Day >= 1 && Day <=7) {
	if (Day >= 6) {
		Console.Write("Woohoo... It's a holiday");
	} else {
		Console.Write("It's a working day");
	}
} else {
	Console.Write("Enter a valid day between 1 and 7");
}












