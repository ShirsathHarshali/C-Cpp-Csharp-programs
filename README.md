- 👋 Hi, I’m @ShirsathHarshali
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ShirsathHarshali/ShirsathHarshali is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
//demonstration of do while loop
using System;

using System.IO;

using System.Linq;

using System.Collections.Generic;

	public class dowhile
	{
		public static void Main()
		{
			int i = 1; int n;
			Console.WriteLine("Enter A Number:- ");
			n = Convert.ToInt32(Console.ReadLine());

			Console.WriteLine(" table of Given number: ");
			do
			{
				Console.WriteLine(" " + (n * i));
				i++;
			}
			while (i <= 10);
			Console.ReadLine();
		}
	}
