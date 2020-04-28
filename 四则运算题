#include <iostream>
#include <random>
#include <math.h>
#include <iomanip>
#include <stdio.h>
float num[1000];
float numcreate()//随机数生成
{
	std::random_device rd;
	return rd();
}

float numcreate2(int shuliang,int nummax)//控制随机数大小
{
	int i;
	for (i = 0; i < shuliang ;i++)
	{
		num[i]=numcreate();
		for(;;)
		{
			if (num[i] > nummax||num[i]<-nummax)
			{
				num[i] = num[i] / 10;
			}
			else
			{
				break;
			}
		}
     
	 
	}
	return 0;
}

float print1(int shuliang, int point,int fuhao)//打印无括号的四则运算
{
	int i;
	if (fuhao == 1)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				printf("%.0f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					std::cout << "*";
				}
				else if (i % 3 == 0)
				{
					std::cout << "÷";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "*";
				}
				else
				{
					std::cout << "÷";
				}

				printf("%.0f +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				printf("%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					std::cout << "*";
				}
				else if (i % 3 == 0)
				{
					std::cout << "÷";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "*";
				}
				else
				{
					std::cout << "÷";
				}

				printf("%.2f +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}
	if (fuhao == 2)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				printf("%.0f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					std::cout << "+";
				}
				else if (i % 3 == 0)
				{
					std::cout << "-";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "+";
				}
				else
				{
					std::cout << "-";
				}

				printf("%.0f +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				printf("%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					std::cout << "+";
				}
				else if (i % 3 == 0)
				{
					std::cout << "-";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}

				printf("%.2f +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}

	return 0;
}
float print2(int shuliang, int point, int fuhao)//打印有括号的四则运算
{
	int i;
	if (fuhao == 1)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				printf("%.0f ", num[i]);
				if ((i+1) % 2 == 0)
				{
					std::cout << "*";
				}
				else if (i % 3 == 0)
				{
					std::cout << "÷";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("(%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "*";
				}
				else
				{
					std::cout << "÷";
				}

				printf("%.0f) +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				printf("%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					std::cout << "*";
				}
				else if (i % 3 == 0)
				{
					std::cout << "÷";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("（%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "*";
				}
				else
				{
					std::cout << "÷";
				}

				printf("%.2f） +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}
	if (fuhao == 2)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				printf("%.0f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					std::cout << "+";
				}
				else if (i % 3 == 0)
				{
					std::cout << "-";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("(%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "+";
				}
				else
				{
					std::cout << "-";
				}

				printf("%.0f) +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				printf("%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					std::cout << "+";
				}
				else if (i % 3 == 0)
				{
					std::cout << "-";
				}
				else if (i % 7 == 0)
				{
					std::cout << "-";
				}
				else
				{
					std::cout << "+";
				}
				printf("（%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					std::cout << "+";
				}
				else if (i % 5 == 0)
				{
					std::cout << "-";
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					std::cout << "+";
				}
				else
				{
					std::cout << "-";
				}

				printf("%.2f） +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}

	return 0;
}
float fileprint1(int shuliang, int point, int fuhao)//打印为TXT文件
{
	int i;
	FILE *fp;
	fp = fopen("sizeyunsuan.txt", "w+");
	if (fuhao == 1)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				fprintf(fp,"%.0f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp,"%s","*");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp,"%s", "÷");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else
				{
					fprintf(fp,"%s","+");
				}
				fprintf(fp,"%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp, "%s","+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp, "%s","*");
				}
				else
				{
					fprintf(fp, "%s","÷");
				}

				fprintf(fp,"%.0f +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				fprintf(fp,"%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp,"%s", "*");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp,"%s", "÷");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else
				{
					fprintf(fp,"%s", "+");
				}
				fprintf(fp,"%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp, "%s","+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp, "%s","*");
				}
				else
				{
					fprintf(fp,"%s", "÷");
				}

				fprintf(fp,"%.2f +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}
	if (fuhao == 2)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				fprintf(fp,"%.0f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp, "%s","-");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else
				{
					fprintf(fp,"%s", "+");
				}
				fprintf(fp,"%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp, "%s","+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp, "%s","-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else
				{
					fprintf(fp,"%s","-");
				}

				fprintf(fp,"%.0f +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				fprintf(fp,"%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp, "%s","+");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp, "%s","-");
				}
				else
				{
					fprintf(fp,"%s", "+");
				}
				fprintf(fp,"%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp, "%s","-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else
				{
					fprintf(fp,"%s", "+");
				}

				fprintf(fp,"%.2f +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}
	fclose(fp);
	return 0;
}
float fileprint2(int shuliang, int point, int fuhao)//打印为TXT文件
{
	int i;
	FILE *fp;
	fp = fopen("sizeyunsuan.txt", "w+");
	if (fuhao == 1)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				fprintf(fp, "%.0f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp,"%s", "*");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp,"%s", "÷");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else
				{
					fprintf(fp,"%s", "+");
				}
				fprintf(fp, "(%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp, "%s","*");
				}
				else
				{
					fprintf(fp,"%s", "÷");
				}

				fprintf(fp, "%.0f) +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				fprintf(fp, "%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp,"%s", "*");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp,"%s", "÷");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else
				{
					fprintf(fp,"%s", "+");
				}
				fprintf(fp, "(%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp,"%s", "*");
				}
				else
				{
					fprintf(fp,"%s", "÷");
				}

				fprintf(fp, "%.2f) +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}
	if (fuhao == 2)
	{
		for (i = 0; i < shuliang; i = i + 4)
		{
			if (point == 1)
			{
				fprintf(fp, "%.0f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp, "%s","+");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp, "%s","-");
				}
				else
				{
					fprintf(fp, "%s","+");
				}
				fprintf(fp, "(%.0f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else
				{
					fprintf(fp,"%s", "-");
				}

				fprintf(fp, "%.0f) +%.0f=""\n", num[i + 2], num[i + 3]);
			}
			else if (point == 2)
			{
				fprintf(fp, "%.2f ", num[i]);
				if ((i + 1) % 2 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else if (i % 3 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if (i % 7 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else
				{
					fprintf(fp,"%s","+");
				}
				fprintf(fp, "(%.2f", num[i + 1]);
				if (i % 6 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else if (i % 5 == 0)
				{
					fprintf(fp,"%s", "-");
				}
				else if ((i + 1) * 10 % 3 == 0)
				{
					fprintf(fp,"%s", "+");
				}
				else
				{
					fprintf(fp, "%s","-");
				}

				fprintf(fp, "%.2f) +%.2f=""\n", num[i + 2], num[i + 3]);

			}

		}
	}
	fclose(fp);
	return 0;
}
int main()
{
	int i=0;
	int shuliang=0;
	int nummax=0;
	int point=0;
	int kuohao=0;
	int place=0;
	int fuhao=0;
	std::cout << "请输入出题数量。\n";
	std::cin >> shuliang;
	std::cout << "请输入最大值。\n";
	std::cin >> nummax;
	std::cout << "是否有括号的运算，是请输入1，否输入2.\n";
	std::cin >> kuohao;
	std::cout << "是否带小数的运算，否请输入1，是输入2.\n";
	std::cin >> point;
	std::cout << "请输入运算类型，1加减乘除，2加减\n";
	std::cin >> fuhao;
	std::cout << "打印为TXT文件？是输入1\n";
	std::cin >> place;
	numcreate2(shuliang*4,nummax);
	if(kuohao==2)
	{
		print1(shuliang * 4, point,fuhao); 
		if(place==1)
		{
			fileprint1(shuliang *4, point, fuhao);
		}
	}
	else if (kuohao == 1)
	{
		print2(shuliang * 4, point, fuhao);
		if (place == 1)
		{
			fileprint2(shuliang * 4, point, fuhao);
		}
		return 0;
	}
}
