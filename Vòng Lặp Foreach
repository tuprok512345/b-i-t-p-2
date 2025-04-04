using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        Console.OutputEncoding = System.Text.Encoding.UTF8;

        // Bài Tập 1: In Tất Cả Các Phần Tử Trong Mảng
        int[] arr1 = { 1, 2, 3, 4, 5 };
        foreach (int num in arr1)
            Console.Write(num + " ");
        Console.WriteLine("\n");

        // Bài Tập 2: Tính Tổng Các Phần Tử Trong Mảng
        int sum = 0;
        foreach (int num in arr1)
            sum += num;
        Console.WriteLine("Tổng = " + sum + "\n");

        // Bài Tập 3: Tìm Phần Tử Lớn Nhất Trong Mảng
        int max = arr1[0];
        foreach (int num in arr1)
            if (num > max)
                max = num;
        Console.WriteLine("Phần tử lớn nhất = " + max + "\n");

        // Bài Tập 4: Đếm Số Lượng Số Chẵn Trong Mảng
        int evenCount = 0;
        foreach (int num in arr1)
            if (num % 2 == 0)
                evenCount++;
        Console.WriteLine("Số lượng số chẵn = " + evenCount + "\n");

        // Bài Tập 5: In Tất Cả Các Chuỗi Trong Danh Sách
        List<string> strings = new List<string> { "apple", "banana", "cherry" };
        foreach (string str in strings)
            Console.WriteLine(str);
        Console.WriteLine();

        // Bài Tập 6: Tìm Chuỗi Dài Nhất Trong Danh Sách
        string longest = strings[0];
        foreach (string str in strings)
            if (str.Length > longest.Length)
                longest = str;
        Console.WriteLine("Chuỗi dài nhất = " + longest + "\n");

        // Bài Tập 7: Tính Tổng Các Số Lẻ Trong Mảng
        int oddSum = 0;
        foreach (int num in arr1)
            if (num % 2 != 0)
                oddSum += num;
        Console.WriteLine("Tổng các số lẻ = " + oddSum + "\n");

        // Bài Tập 8: In Các Số Chẵn Trong Mảng
        foreach (int num in arr1)
            if (num % 2 == 0)
                Console.Write(num + " ");
        Console.WriteLine("\n");

        // Bài Tập 9: Kiểm Tra Sự Tồn Tại Của Một Phần Tử Trong Mảng
        bool exists = false;
        foreach (int num in arr1)
            if (num == 3)
                exists = true;
        Console.WriteLine("Sự tồn tại của 3: " + exists + "\n");

        // Bài Tập 10: Đếm Số Phần Tử Âm Trong Mảng
        int negativeCount = 0;
        int[] arr2 = { -1, -2, 3, 4, -5 };
        foreach (int num in arr2)
            if (num < 0)
                negativeCount++;
        Console.WriteLine("Số phần tử âm = " + negativeCount + "\n");

        // Bài Tập 11: In Các Số Lớn Hơn 10 Trong Mảng
        int[] arr3 = { 5, 12, 15, 8, 20 };
        foreach (int num in arr3)
            if (num > 10)
                Console.Write(num + " ");
        Console.WriteLine("\n");

        // Bài Tập 12: Tìm Chuỗi Có Độ Dài Ngắn Nhất Trong Danh Sách
        string shortest = strings[0];
        foreach (string str in strings)
            if (str.Length < shortest.Length)
                shortest = str;
        Console.WriteLine("Chuỗi ngắn nhất = " + shortest + "\n");

        // Bài Tập 13: Nhân Đôi Tất Cả Các Phần Tử Trong Mảng
        foreach (int num in arr1)
            Console.Write(num * 2 + " ");
        Console.WriteLine("\n");

        // Bài Tập 14: Tìm Số Lớn Thứ Hai Trong Mảng
        int firstMax = arr1[0], secondMax = arr1[0];
        foreach (int num in arr1)
        {
            if (num > firstMax)
            {
                secondMax = firstMax;
                firstMax = num;
            }
            else if (num > secondMax && num != firstMax)
                secondMax = num;
        }
        Console.WriteLine("Số lớn thứ hai = " + secondMax + "\n");

        // Bài Tập 15: Tìm Chuỗi Bắt Đầu Bằng Chữ Cái A
        foreach (string str in strings)
            if (str.StartsWith("a"))
                Console.WriteLine(str);
        Console.WriteLine();

        // Bài Tập 16: Kiểm Tra Xem Danh Sách Có Chứa Một Chuỗi Cụ Thể Không
        bool containsHello = false;
        foreach (string str in strings)
            if (str == "banana")
                containsHello = true;
        Console.WriteLine("Danh sách có chứa 'banana': " + containsHello + "\n");

        // Bài Tập 17: In Tất Cả Các Phần Tử Âm Trong Mảng
        foreach (int num in arr2)
            if (num < 0)
                Console.Write(num + " ");
        Console.WriteLine("\n");

        // Bài Tập 18: Đếm Số Lần Xuất Hiện Của Một Phần Tử Trong Mảng
        int count = 0;
        foreach (int num in arr1)
            if (num == 5)
                count++;
        Console.WriteLine("Số lần xuất hiện của 5 = " + count + "\n");

        // Bài Tập 19: Tạo Một Danh Sách Mới Từ Các Phần Tử Lớn Hơn 10 Trong Mảng
        List<int> newList = new List<int>();
        foreach (int num in arr3)
            if (num > 10)
                newList.Add(num);
        Console.WriteLine("Danh sách mới từ các phần tử > 10:");
        foreach (int num in newList)
            Console.Write(num + " ");
        Console.WriteLine("\n");

        // Bài Tập 20: In Các Chuỗi Có Độ Dài Lớn Hơn 5 Ký Tự
        foreach (string str in strings)
            if (str.Length > 5)
                Console.WriteLine(str);
    }
}
