# CS361-Project
# Microservice - Book of the day
This section of the microservice is designed to generate a randomized book that will be integrated into a library-like application with similarities to Goodreads. Through the use of a hyperlink, the microservice will interface with the application's code. It was agreed upon by both parties that utilizing the school's VPN and flip servers would be the most efficient means of project completion. The microservice's function is to randomly select a book from a pre-established list of tuples and subsequently display pertinent information regarding the book's title, author, and rating to the user.

# UML Sequence Diagram
![alt text](https://raw.githubusercontent.com/miranded/CS361-Project/main/microservice.jpg) 

# Instructions Sending
Flask is handling the sent request when the '@app.route('/')' decorate is evoked. This slice of code communicates to flask that the function is being called. Furthermore in the if __name__ == "__main__": the port parameter is called which specifies which port is being used to listen for incoming requests. 

![alt text](https://raw.githubusercontent.com/miranded/CS361-Project/main/sending.jpg) 

# Instructions Receiving
Install requests in pycharm if you havent done so yet. 
After installing, use get request to connect to the localhost using the provided hyperlink. For the purpose of this instruction sheet, please observe the image below.

![alt text](https://raw.githubusercontent.com/miranded/CS361-Project/main/request1.jpg) 

After following the step above, it is recommended to have some type of check to make sure that proper communication has been made. To do so, adding an if estatement that check if the get has functioned along with the putput is recommended and shown below. The else statement would communicate back to the programmer that an error has occured and need to check connection or hypelink. 

![alt text](https://raw.githubusercontent.com/miranded/CS361-Project/main/request2.jpg) 
