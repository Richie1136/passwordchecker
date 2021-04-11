# passwordchecker

1. Installed the Requests module so that i can make requests to the password API
2. Hash the password which basically means transforming the password into another string
3. Incoporate K anonymity from the hash password K anonymity is used to provide privacy protection
4. Wrote a function and passed in the hashed version of my password. The purpose of this function is to request data and
   give a response

5. Wrote a second function and passed in my actual password to that checks to see if the password exists in the API and
   if it does exists i want to see if this password has ever been hacked by using the password API.

6. Wrote an if statement that will catch any requests that doesn't have a status code of 200 and if the response is a
   status code of 200 then i want to return the response

7. Installed hashlib module which is a way to hash messages easily

8. Hashed the password and then converted the hashed password to hexidecimal digits and then uppercased all of the
   digits

9. Made two variables, one that will store the first 5 charcters and the other variable will store the rest of the
   remaining characters

10. Sending hashed passwords to the password API and getting a response that matches the beginning of the hashed
    password

11. Split the hash response on the : and then looped the line through the hashes text

12. Looped the hash and the count through the hashes generator, so that i get the hashed password and the amount of
    times that the password has been hacked

13. Check to see if the hash which is the tail of the hash is equal to the tail end of our hashed password. If they are
    equal then i want to return the number of times the password has been leaked otherwise i want to return zero

14. I created a main function that will receive the command line arguments that are given. I am going to loop through
    the passwords and then receive the count from the password leaks function.

15. Next set the count equal to the pwnd api check function and passed in the password to see if it has ever been fouund
    in the api. if the password exists in the pwdpassword api then print out the password and the amount of times that
    it was found in the api. Next if the passowrd was not found then print out password not found.
