# practical-work
итоговая проверочная работа

Console.WriteLine ("массив из строк длина которых равна или меньше 3:");
string[] array1 = new string[4] { "hello", "2" , "world", ":)"};
string[] array2 = new string[array1.Length];
int count = 0;
void Array(string[] array1, string[] array2)
{
    int count = 0;
    for (int i = 0; i < array1.Length; i++)
    {
    if(array1[i].Length <= 3)
        {
        array2[count] = array1[i];
        count++;
        }
        
    }
}
void PrintArray(string[] array)
{
    for (int i = 0; i < array.Length; i++)
    {
        Console.Write($"{array[i]} ");
    }
    Console.WriteLine();
}
Array(array1, array2);
PrintArray(array2);
