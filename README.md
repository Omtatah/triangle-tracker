#Application Name.
	Triangle-tracker


#Brief BDD-included description of application.
	Here is a triangle tracker that tracks different types of triangles based on the measurements a user feeds it.

	It follows the following criteria to identify the triangles:

	1.For an equilateral triangle, all sides must be equal.
	2.For an isosceles triangle, two sides are exactly equal.
	3.For a scalene triangle, none of the sides is equal. However, the sum of any two sides of the triangle must be greater than the third 		  side.
	4.Most importantly, if the sum of any two sides of the triangle is equal to or less than the third remaining side, then a triangle 		  CANNOT be formed using those values. (For example, the values 9,4 & 3 cannot form a triangle.)

|		Behavior                |        Input        | Output	               |
|---------------------------------------|:-------------------:|-----------------------:|
|		All sides are equal	|	3 sides	      |	Equilateral triangle   |
|---------------------------------------|---------------------|-----------------------:|
|		Two sides are equal	|       3 sides	      |	Isosceles triangle     |
|---------------------------------------|---------------------|------------------------|
|		All sides are unequal	|       3 sides	      |	Scalene triangle       |
|---------------------------------------|---------------------|------------------------|



	Consider the following circumstances that a user may find him/herself in after prompting the values of his/her triangle:
	The program should return this when the input is not a number:

	Input Example: a
	Output Example: Please enter a valid dimension
	The program should return this when the input is a negative value:


	Input Example: -1
	Output Example: Please enter a valid dimension
	The program should return this when the sum of any two sides is less than or equal to the third side:


	Input Example: first side = 1, second side = 1, third side = 3
	Output Example: It's not a triangle
	The program should return this when all sides are equal:


	Input Example: first side = 4, second side = 4, third side = 4
	Output Example: It's an equilateral triangle
	The program should return this when at most two sides are equal:


	Input Example: first side = 4, second side = 4, third side = 5
	Output Example: It's an isosceles triangle
	The program should return this when all sides are not equal:


	Input Example: first side = 4, second side = 5, third side = 6
	Output Example: It's an scalene triangle





#Date of current version.
	version 1.0


#List of contributor(s).
	1. Murtallah Omtatah



#Setup/Installation Requirements.
	* An internet source
	* A laptop
        *Github


	To start using this project use the following commands:

	git clone https://github.com/Omtatah/triangle-tracker.git
	cd triangle-tracker
	atom .
	code . (this is if Visual Studio Code is your preferred text editor)


#Known Bugs.
	NO bugs identified in this application.


#Technologies Used.
	HTML, CSS and JavaScript
	A laptop
	The internet


#Support and contact details.
	Should one have a concern, issue or idea to let known to the developer, kindly contact me on
	omtatahmurtallah@gmail.com


Link to Live Website:
	http://Omtatah.github.io/triangle-tracker


#MIT License.

Copyright (c) 2019 Murtallah Omtatah

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
				          Copyright (c) 2019{Murtallah Omtatah}
