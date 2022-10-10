# CS501

A clear structure that helps you check your homework.


(?) stands for unspecific type not mentioned in the instruction.


# MyRectangle2D

double x, y; // (a)

double width, height; // (b)

---

double getX(){} // (a)

double getY(){} // (a)

(?) setX(double newX){} // (a)

(?) setY(double newY){} // (a)

public double getWidth(){} // (b)

public double getHeight(){} // (b)

(?) setWidth(double w){} // (b)

(?) setHeight(double h){} // (b)

MyRectangle2D(){} // (x, y, width, height) = 0, 0, 1, 1 // (c)

MyRectangle2D(double x, double y, double w, double h){} // (d)

public double getArea(){} // (e)

public double getPerimeter(){} // (f)

public boolean contains(double x, double y){} // (g)

boolean contains(MyRectangle2D r){} // if the specified rectangle is **inside this** rectangle // (h)

boolean overlaps(MyRectangle2D r){} // if the specified rectangle **overlaps with this** rectangle // (i)



# Circle2D

double x, y; // (a)

---

double getX(){} // (a)

double getY(){} // (a)

double getRadius(){} // (b)

Circle2D(){} // (x, y, radius) = 0, 0, 1 // (c)

Circle2D(double x, double y, double radius){} // (d)

public double getArea(){} // (e)

public double getPerimeter(){} // (f)

public boolean contains(double x, double y) // (g)

public boolean contains(Circle2D circle) // if the specified circle is **inside this** circle // (h)

public boolean overlaps(Circle2D circle) // if the specified circle **overlaps with this** circle//  (i)



# Account

private int id; // (a)

private double balance; // (b)

private double annualInterestRate = 9.0; // (c)

private Date = new Date(); // (d)

---

Account(){} // (e)

Account(int id, double balance){} // throw an Exception if id or balance is negative // (f)

int getId() // (g)

(?) setId(int newId){} // throw an Exception if negative // (g)

double getBalance() // (g)

(?) setBalance(double amount){} // throw an Exception if negative  // (g)

double getInterest(){} // for annualInterestRate??? // (g)

(?) setInterest(double interest){} // for annualInterestRate???  // throw an Exception if negative  // (g)

public Date getDate(){} // (h)



# AccountNew extends Account

String name; // (a)

---

AccountNew(String name, int id, double balance){} // (b)

public double getMonthlyInterestRate(){} // (c)

public double getMonthlyInterest(){} // (d)

public (?) withdraw(double amount){} // throw an Exception if amount>balance // (e)

public (?) deposit(double amount){} // (f)



