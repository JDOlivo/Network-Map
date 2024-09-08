# Network-Map
In this project, we will demonstrate how to create a basic network map. There are various programs available for this task, but I chose Draw.io because it’s free and accessible to everyone. I will walk you through the process using screenshots I took as examples.
You can expand or modify your network map as needed. Realistically, your network should include VLANs, firewalls, switches, routers, etc. At the end of this document, I’ll include a more complex merged network diagram that I created using Microsoft Visio for comparison.
Step-by-Step Guide:
1.	Open Draw.io:
Select where to save your diagram.
Click "Create New Diagram" and choose the type of diagram you’d like to create. I used a blank diagram to show how to start from scratch. After these steps, you’ll have a blank canvas to begin with.

       ![1 Blank](https://github.com/user-attachments/assets/641323f0-c065-46bf-ba27-914b5817b8f8)

2.	Starting Point - Server:
A good starting point for a network diagram is a server. Search for "Server" in the “Search Shapes” box in the top-left corner.
Select the server icon you want to use, and it will appear in the center of the grid.

      ![2 Server](https://github.com/user-attachments/assets/11a0a90c-f1bf-469b-89d9-0f8d40c229ff)
 
3.	Duplicating Servers:
You can use Ctrl + D to duplicate servers or manually place your desired number. For this project, I chose six servers.

      ![3 Server  Duplication](https://github.com/user-attachments/assets/f272f7eb-cc35-45c6-9ff5-773fc6b7e70d)

 
4.	Add a Frame for Background:
Place a frame as the background for your network map. Choose a shape that works best for your style. I used a rounded rectangle from the general menu on the left. This can be done before or after placing the servers.

      ![4 Background placement](https://github.com/user-attachments/assets/e5546e37-3531-415f-940e-698bb9d28fad)

 
5.	Adjust the Layering:
You can move diagram elements forward or backward depending on how you want to overlay them. In this case, we want our rounded rectangle to act as a background. Move it behind the servers by right-clicking on it and selecting "To Back."


       ![5 Background move back](https://github.com/user-attachments/assets/225cf02a-c67b-4ce7-9cbc-c376a3fe8c58)

6.	Label Components:
Label the components you’ve placed so far. This step will be repeated throughout the diagram. Click on each item and label it accordingly.

      ![6 Labeling](https://github.com/user-attachments/assets/49659eb9-6a2d-46de-94cc-74d0f8740a25)


 
7.	Place External Servers:
As demonstrated, I placed an external attack server outside of our network for illustration purposes.


      ![7 Move C2 server](https://github.com/user-attachments/assets/14273427-f652-415a-b63a-1107418ba8b0)

 
8.	Add Virtual Private Cloud (VPC):
Now, place a layer showing your Virtual Private Cloud (VPC) connection. Search for "VPC" in the top-left search box and place it around the servers. You may need to reorganize and adjust the layout multiple times.

      ![8 VPC ](https://github.com/user-attachments/assets/655efc69-152c-45ee-9f6d-82fe4f4b0e82)


 
9.	Organize the Layout:
Take a moment to organize the network layout to your preference. Be careful not to lose any items behind other elements. If you do, you can recover them later by adjusting the layers.


      ![9 Organize](https://github.com/user-attachments/assets/c25e0ed4-0116-4bcd-86e7-f1fdcc638dff)

 
10.	Connect the Servers:
Start connecting the servers. Click on the Windows RDP server, then drag the blue arrow to the Fleet Services server to show the connection.


      ![10 Connect Servers](https://github.com/user-attachments/assets/9ce56f26-a497-4fe8-b66d-1287edc0a68b)

 
11.	Label Connection Lines:
After connecting the servers, click on the connection line and label it. Repeat this for all the server connections you want to show.

      ![11 Connection Labels](https://github.com/user-attachments/assets/7d34f19f-f3af-4fdd-95a9-aa5a2f132ba2)


 
12.	Modify Connection Arrows:
By default, connection lines have a one-way arrow. To show bi-directional traffic, click on the connection line, then go to the right-side menu, find the "none" dropdown in the "Line" section, and add an arrow to the other side.

      ![12 Connection Arrows](https://github.com/user-attachments/assets/78251275-2dac-467b-9dff-81325abc0644)


 
13.	Adjust Arrow Styles:
Choose the arrow style you prefer by selecting it from the right-side menu.

      ![13 Connection Arrows 2](https://github.com/user-attachments/assets/aa167993-9903-4900-a35a-69a30702e48b)


 
14.	Connection with Bi-Directional Arrows:
After adjusting, you will now see arrows on both sides of the connection line. This depicts bi-directional traffic between the two servers.

      ![14 Bi Directional Arrows](https://github.com/user-attachments/assets/10f322da-cd92-488e-9954-c756149a60f4)


 
15.	Changing Line Attributes:
You can modify the line's color and pattern style. Click on the colored box on the right-side menu to change the color, and select the line pattern style from the "Line" dropdown menu.

      ![15 Arrow Color and Pattern](https://github.com/user-attachments/assets/cd4d5f8e-96a5-48c2-9157-5ed30c3c4546)


 
16.	Further Labeling:
Add any additional labels to your connections as necessary. This will help clarify the different connections in your diagram.


      ![16 Additional labels](https://github.com/user-attachments/assets/f35b9ed2-170b-4f52-9ffd-a1f0e9d13539)

 
17.	Modify Line Styles:
If you wish to change the shape or pattern of your lines, you can do so in the right-side menu. There are options to switch to straight lines or various other styles.


      ![17 Line style change](https://github.com/user-attachments/assets/59e148cc-b66c-4661-96a9-d0e74d20d3c9)

 
18.	Switching to Straight Lines:
For this diagram, we are changing the connection lines to straight. This can be done by selecting the straight-line option from the available styles.
After making the changes, the connection lines are now displayed as straight lines, which may improve readability depending on the layout.
 

      ![18 Line style change 2](https://github.com/user-attachments/assets/b0d050a3-c3ca-4cb4-bcc4-fa409fa48267)



19.	Adding a Network Range:
Place a text box displaying the network range. The text box is located in the left-side general menu next to the shapes. I positioned it in the top-left corner of our network frame.


    ![19 Network Range and Subnet](https://github.com/user-attachments/assets/1f8057c7-2380-4b2f-bc34-a0d50beacb7b)


 
20.	Double-Check Layers:
Ensure all layers are positioned correctly. For example, I moved the VPC layer back to the front of the background rectangle. You may need to move items around to find any displaced objects.


      ![20 Adjust layers Move VPC forward ](https://github.com/user-attachments/assets/66ccfb25-91ac-4628-87cd-485b070895e7)

 
21.	Add Internet Gateway:
Search for "Internet Gateway" in the top-left search box and place it in the network diagram.


      ![21 Search add internet gateway](https://github.com/user-attachments/assets/39d6efd1-5090-465c-a664-1838daa393e9)


 
22.	Add Cloud Icon:
Search for an internet/cloud icon and place it in the diagram.


      ![22 Search and add cloud](https://github.com/user-attachments/assets/b4d08c26-2bb4-4f3d-89ec-9f0f48283ef5)


 
23.	Connect and Label New Elements:
Connect and label the newly added items.


      ![23 Connect and label Internet an gateway](https://github.com/user-attachments/assets/20c80001-cc11-4656-a864-bc0944cc07d3)


 
24.	Add a Remote User:
Add a remote SOC Analyst user by searching for "Computer" in the search box and connecting them to the network.


      ![24 Search add lable SOC CPU](https://github.com/user-attachments/assets/fbf5f51b-66ef-4352-b52c-9ee9f1a499a4)


 
25.	Add Additional Components:
Take this time to label and connect any additional resources. Here, I added an attack machine to complement the previously added C2 server.
 

      ![25 Add Label and connect attack computer](https://github.com/user-attachments/assets/5f2753c0-b627-4635-92f0-b8e6e691470b)



26.	Final Review:
Your diagram is now complete! Don’t forget to save your work.


      ![26 Save diagram](https://github.com/user-attachments/assets/4c62c5b6-568f-4d26-8dd0-174c90eb12cd)

 
27.	Final Product:
Below is the completed diagram. 


      ![27 Completed Diagram](https://github.com/user-attachments/assets/35ce7a2c-2140-4f0b-81a0-2edbf788da26)

 
Summary:
In this project, we walked through the process of creating a network diagram using Draw.io. As mentioned earlier, this is a simplified example. In a real-world enterprise network, there may be thousands of devices, along with various security appliances and multiple layers of network segmentation. For comparison, below is an example of a more complex merged network diagram that I created for a different project using Microsoft Visio.

  ![Merged Network Diagram](https://github.com/user-attachments/assets/6f410079-99f7-44a1-a56c-59de6034ec69)

 
