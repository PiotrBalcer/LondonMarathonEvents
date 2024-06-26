Offline Coding Task
Create a SQLite database and within it create a table which is able to store 4 columns: a char FirstName and LastName, the time of insert accurate to the millisecond, and a globally unique integer key called ID. Design the table schema carefully so that:
    • the ID field is automatically generated by the database at the time of INSERT 
    • the ID value is guaranteed to be unique and larger than any other ID that has ever existed in the table before
Generate 1000 randomly generated names consisting of a FirstName and a Surname taken in any order from the following list: 
    • [‘riley’, ‘james’, ‘ryan’, ‘joshi’, ‘andrew’]
The same name can be generated multiple times, but any single name cannot contain the same FirstName and Surname strings.
Enjoy a refreshing beverage of your choice.
Store the generated names into the SQLite database in parallel.
Read all rows back from the database, and for each row generate a QR code using a free publicly available HTTP QR code generation API, where the QR code payload is the ID value. Image Charts (QR Codes - Image-Charts documentation) is an example of such an API.
Zip up the 1000 QR codes and send this to us as part of your deliverable.
Tips
    • Complete the above task in Python 3.
    • Try to demonstrate to us your expertise in software development, using good principles and demonstrating best practices in your solution wherever you can, producing maintainable readable code
    • Your code should be in a delivered to us with the consideration of making it easy for another developer to run it – no guesswork should be required.
    • Do not spend days on this project, we appreciate you are doing this in your spare time and we will review it with this in mind.

