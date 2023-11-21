# CS361ms

#CS361 Assignment 9 by James Hill

Partner: Sharyn Miyagi

**How to programmatically REQUEST data:**

In the input.txt file, the first line needs to be the word request, followed by lines for each order item. Finally it should end with the line "Special Instructions". A sample input could look like this:

Request 
Coke 
Chicken Fingers 
Salad 
Special instructions: 

**How to programmatically RECEIVE data:**

Before a request is complete the output.txt file will simply contain the word PENDING. Once complete it will contain a JSON object. To retrieve the object simply wait for the word PENDING to be gone and parse the JSON file. An example output.txt would be the following:

{"money": 15, "time": 5}

**UML Diagram:**


![diagram](https://github.com/c0athanger/CS361ms/assets/83789862/b53cf099-92b8-4411-bc28-62e0343dae60)
