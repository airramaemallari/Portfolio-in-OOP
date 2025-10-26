Midterm Lab Task 2:


<img width="669" height="701" alt="image" src="https://github.com/user-attachments/assets/bff41219-c1e7-47dc-80bc-9c23b2a2f490" />


Source Code:



    def Calcu_Avg_Rates(quality, price, service):
        """This function calculates the average of three ratings."""
        return (quality + price + service) / 3
    
    
    def Ana_Prod_Rates(brandname, category, quality, price, service):
        """This function displays product details and calls the Calcu_Avg_Rates function."""
        print("\nBrand Name:", brandname)
        print("Category:", category)
        print("Quality Rating:", f"{quality:.2f}")
        print("Price Rating:", f"{price:.2f}")
        print("Service Rating:", f"{service:.2f}")
        
        avg = Calcu_Avg_Rates(quality, price, service)
        print("Overall Average Rating:", f"{avg:.2f}")
    
    
    # Main Program
    brandname = input("Enter Brand Name: ")
    category = input("Enter Category: ")
    quality = float(input("Enter Quality Rating: "))
    price = float(input("Enter Price Rating: "))
    service = float(input("Enter Service Rating: "))
    
    Ana_Prod_Rates(brandname, category, quality, price, service)


Output:



<img width="720" height="255" alt="image" src="https://github.com/user-attachments/assets/1bc2c451-b72b-4a04-ad8a-d734141eefbf" />
