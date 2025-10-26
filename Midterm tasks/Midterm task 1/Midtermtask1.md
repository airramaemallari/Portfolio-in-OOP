Midterm Lab Task 1


Problem 1: Use Appropriate Escape Sequence( \n, \t \b \ ..etc) for the problem below


<img width="1076" height="616" alt="image" src="https://github.com/user-attachments/assets/d73e840a-267d-4777-96cb-f226516b77be" />



Source Code:

    
    name = "John Doe"
    ‎email = "john.doe@example.com"
    ‎university = "ABC University"
    ‎
    ‎print("Database Record")
    ‎print("\\\\\\\\\\\\\\\\\\\\")
    ‎print(f"Name:\t\t{name}")
    ‎print(f"Email:\t\t{email}")
    ‎print(f"University:\t{university}")


Output:



<img width="974" height="623" alt="image" src="https://github.com/user-attachments/assets/8131f407-2e79-43de-a833-2afd252c385e" />




Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f etc… for this task


<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/59b9f12e-b941-426b-9177-24fde1878044" />



Source Code:


    subject = "Greetings!"
    ‎sender = "Jane"
    ‎version = 1.2
    ‎discount = 10.5
    ‎status = "A"
    ‎code = "ABC123"
    ‎location = "City XYZ"
    ‎age = 30
    ‎company = "ABC Corporation"
    ‎website = "www.example.com"
    ‎phone = "+1 123-456-7890"
    ‎job_title = "Software Engineer"
    ‎department = "Engineering"
    ‎
    ‎print(f"Dear John, I hope this email finds you well.")
    ‎print(f"I wanted to reach out and say hello.")
    ‎print(f"I hope you are doing well and enjoying your day.")
    ‎print(f"It's been a while since we last spoke, and I wanted to catch up with you.")
    ‎print(f"Let's plan to meet up soon and have a great time together!\n")
    ‎
    ‎print(f"Subject: %s" % subject)
    ‎print(f"Version: %.2f" % version)
    ‎print(f"Discount: %2f%%" % discount)
    ‎print(f"Status: %s" % status)
    ‎print(f"Code: %s" % code)
    ‎print(f"Location: %s" % location)
    ‎print(f"Age: %d" % age)
    ‎print(f"Company: %s" % company)
    ‎print(f"Website: %s" % website)
    ‎print(f"Phone: %s" % phone)
    ‎print(f"Job Title: %s" % job_title)
    ‎print(f"Department: %s" % department)


Output:


<img width="932" height="688" alt="image" src="https://github.com/user-attachments/assets/3f0da207-977d-42d9-8e5d-fcb7ab388278" />



Problem 3. Book Reservation; Accept User Input



<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/56bd5a87-8349-4a9c-a602-b7f82f65839d" />



Source Code:


    title = input("Enter the book title: ")
    ‎author = input("Enter the author: ")
    ‎year = int(input("Enter the year of publication: "))
    ‎genre = input("Enter the genre: ")
    ‎library = input("Enter the library: ")
    ‎member_id = input("Enter your member ID: ")
    ‎return_date = input("Enter the return date: ")
    ‎
    ‎print(f"\nYou have successfully reserved the book '{title}' by {author}.")
    ‎print(f"Year of Publication: {year}")
    ‎print(f"Genre: {genre}")
    ‎print(f"Library: {library}")
    ‎print(f"Member ID: {member_id}")
    ‎print(f"Return Date: {return_date}")


Output:



<img width="1054" height="625" alt="image" src="https://github.com/user-attachments/assets/4293c0e8-7c0a-47b0-95dd-cffe342572cb" />



Problem 4. Day Identifier



<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/14a3f068-adbf-44c3-a153-59eff808f8ae" />



Source Code:

 
    ‎
    ‎day = int(input("Enter day (1-7): "))
    ‎
    ‎if day == 1:
    ‎    print("Monday")
    ‎elif day == 2:
    ‎    print("Tuesday")
    ‎elif day == 3:
    ‎    print("Wednesday")
    ‎elif day == 4:
    ‎    print("Thursday")
    ‎elif day == 5:
    ‎    print("Friday")
    ‎elif day == 6:
    ‎    print("Saturday")
    ‎elif day == 7:
    ‎    print("Sunday")
    ‎else:
    ‎    print("Invalid input")


Output:


<img width="763" height="349" alt="image" src="https://github.com/user-attachments/assets/62b3499f-37b1-48ab-bb1e-a1bd4315c10d" />

    ‎


