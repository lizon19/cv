## **Elizaveta Semyonova**
## Student of VSU named after P. M. Masherov
## **Contact information:**
##### **Phone:** +375-33-305-23-57 
##### **E-mail:** liza.semenovaama45@gmail.com
##### **Telegram:** @po1lk1
---
## Briefly about myself:
#### I've entered VSU in 2021 to the faculty of mathematics and informational technologies. In the future I'll be working as a content maker. I'm eager to lerning Python and SQL, as I want my profession to be connected with Data science. 
***
## Skills and proficiency
* C++ basic level
* HTML
* Microsoft Office programs
* Photoshop
## Code examples:
### C++ (inheritance):
```c++
    #include <iostream>
    using namespace std;

    class rectangle {
    protected:
	int length;
	int height; 
    public:
	rectangle(int length, int height) {
		this->length = length; 
		this->height = height;
	}
	int get_lenght() {
		return length;
	}
	int get_height() {
		return height;
	}
	int area() {
		return length * height;
	}
    };
     class trapeze : public rectangle {
     protected:
	int a,b;
    public:
	trapeze(int height, int a,int b):rectangle (length,height){
		this->a=a;
		this->b = b;
	}
	int get_a () {
		return a;
	}
	int get_b() {
		return b;
	}
	int area() {
		return ((a+b)/2)*height;
	}
    };
    int main() {
	setlocale(0, "rus");
	int x, y, z, g;
	cout << "введите 4 числа через пробел для задания параметров фигур: ";
	cin >> x >> y >> z >> g;
	rectangle rec(x, y); 
	cout << "S_rec = " << rec.area() << "\n";
	trapeze trap(y, z, g);
	cout << "S_trap = " << trap.area() << "\n";
	system("pause");
	return 0;
    }
    ```
## Languages:
* English B2 (upper-intermediate) according to the online test EFSET and university testing 

