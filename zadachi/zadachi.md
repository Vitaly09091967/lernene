// Задача 34: Задайте массив заполненный случайными 
// положительными трёхзначными числами. Напишите программу, 
// которая покажет количество чётных чисел в массиве.
// [345, 897, 568, 234] -> 2

// int size = ReadInt("Введите длину массива: ");
// int[] numbers = new int[size];
// RandonNumbers(numbers);
// void RandonNumbers(int[] numbers)
// {
//    for (int i = 0; i < numbers.Length; i++)
//     {
//         numbers[i] = new Random().Next(100,1000);
//         Console.Write(numbers[i] + " ");
//     } 
// }
// int count = 0;
// for (int x = 0; x < numbers.Length; x++)
// {
//     if (numbers[x] % 2 == 0)
//     count++;
// }
// Console.WriteLine();
// Console.WriteLine($"из {numbers.Length} чисел, {count} четных");

// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }


// Задача 36: Задайте одномерный массив, заполненный случайными
// числами. Найдите сумму элементов, стоящих на нечётных позициях.
// [3, 7, 23, 12] -> 19
// [-4, -6, 89, 6] -> 0

// int size = ReadInt("Введите длину массива: ");
// int[] numbers = new int[size];
// RandonNumbers(numbers);
// void RandonNumbers(int[] numbers)
// {
//    for (int i = 0; i < numbers.Length; i++)
//     {
//         numbers[i] = new Random().Next(-100,100);
//         Console.Write(numbers[i] + " ");
//     } 
// }
// int sum = 0;
// for (int x = 0; x < numbers.Length; x+=2) 
// {
//      sum += numbers [x];
// }
// Console.WriteLine();
// Console.WriteLine($"из {numbers.Length} чисел, сумма на нечётных позициях = {sum}");

// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }


// Задача 38: Задайте массив вещественных чисел. Найдите разницу 
// между максимальным и минимальным элементов массива.
// [3 7 22 2 78] -> 76

// int size = ReadInt("Введите длину массива: ");
// int[] numbers = new int[size];
// RandonNumbers(numbers);
// void RandonNumbers(int[] numbers)
// {
//    for (int i = 0; i < numbers.Length; i++)
//     {
//         numbers[i] = new Random().Next(1,100);
//         Console.Write(numbers[i] + " ");        
//     } 
// }
// int max = numbers[0];
// int min = numbers[0];

// for (int i = 0; i < numbers.Length; i++)
// {
//     if (numbers[i] > max)
//     {
//         max = numbers[i];
//     }
//     if (numbers[i] < min)
//     {
//         min = numbers[i];
//     }
// }
// Console.WriteLine();
// Console.WriteLine($"Максимальное число: {max}");
// Console.WriteLine($"Минимальное число: {min}");
// Console.WriteLine($"Разница между максимальным и минимальным числами: {max-min}");
// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }
