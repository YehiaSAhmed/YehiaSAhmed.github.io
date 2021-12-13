# CMP2241_Task 3 --> Const and & Report
## Usages of **const** keyword:
### Variables Decleration
```
int main()
{
	 const float pi = 3.14;
}
```
### Making a finite large array
```
int main()
{
    const int x = 1000;
    int m[x];
}
```
### Pointers Decleration
```
int main() 
{
	int x;
	cin >> x ;
	const int* p1 = &x;
	cout << p1 << endl;
}
```
___
## Usages of **&** operator:
### To get the address of the variable.
```
int main ()
{
    int x;
    cin >> x;
    cout << &x << endl;
}
```
### To pass by reference.
```
void duplicate(int& n)
{
    n *= 2;
}
int main()
{
    int x;
    cin >>  x;
    duplicate(x);
    cout << x;
}
```
### As bitwise operator.
```
int main()
{
    int a, b;
    cin >> a >> b;
    int s = a & b;
    cout << s << endl;
]
```
