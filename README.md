# Video-Rental-Inventory-System
The goal of this project is to design and implement a simple inventory control system for a small video rental store.
The following are the various classes that are to be implemented.

1. Video  Member variables
• String videoName
• boolean checkout
• int rating  Member functions
• String getName();
• void doCheckout();
• void doReturn();
• void receiveRating(int rating);
• int getRating();
• boolean getCheckout();  Constructor
• Video(String name)

2. VideoStore  Member variables  
• Video[] store;  Member functions  
• void addVideo(String name); 
• void doCheckout(String name);  
• void doReturn(String name);  
• void receiveRating(String name, int rating); 
• void listInventory(); 

3. VideoLaucher  
Contains the main method to test the program 

Sample Output:  D:\Batches\Milestone1> java VideoLauncher  
 
MAIN MENU 
========= 
1.Add Videos:  
2. Check Out Video 
3. Return Video  
4. Receive Rating 
5. List Inventory 
6. Exit 
Enter your choice (1..6): 1   
Enter the name of the video you want to add: Matrix  
Video “Matrix” added successfully. 
 
