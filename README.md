#Controlling-color-display-using-PLC-and-Raspberry\

The purpose of this work is to present the color display control system. The whole workplace
consists of an industrial controller, a minicomputer – Raspberry PI, a flexible matrix, a laptop,
a switch and two power supplies.
The target object, which is the matrix, and the method of communication between it and the
industrial controller through the intermediate element, which is the Raspberry PI, have been
described.
There is a photo of the entire workplace with selected devices.
The configuration of the Phoenix Contact controller with PC WORX and Visu+ was described
in detail. This process can form the basics for getting started with controllers from Phoenix
Contact.
The Raspberry PI minicomputer and the installation process of the Raspbian operating
system along with its configuration were described. The method of connecting to a
raspberry via a remote desktop using the VNC Viewer program was shown. Also shown was
the upload of the library necessary to read information from the controller via the Modbus
TCP protocol and the library used to send signals to the matrix.
The cooperation and the method of communication between the Raspberry Pi and the
industrial controller using the Modbus TCP protocol were presented. The method of
configuring the Modbus server on the controller and the method of addressing program
variables were presented.
All programs responsible for the user panel, matrix control functions, LED color selection and
data reading were precisely discussed.
The summary includes the effects of some functions available in the user control panel


Matrix:
![image](https://user-images.githubusercontent.com/106106611/178149168-e208e4a1-3cd2-45e2-9535-2c54f1926b26.png)

Communication shceme:
![image](https://user-images.githubusercontent.com/106106611/178149190-fcb5b9f2-29f8-45df-bee2-f22633f00ab9.png)

Workplace:
![image](https://user-images.githubusercontent.com/106106611/178149214-9c95c912-b095-453d-934a-16bf9fd285db.png)

1) Industrial controller Phoenix Contact ILC 151 ETH 
2) Power supply QUINT PS 230AC/24DC 
3) Raspberry PI 
4) Matrix 16x16 LED RGB
5) Power supply POS 230AC/5DC )
6) Switch
7) Laptop  


Final app:
![image](https://user-images.githubusercontent.com/106106611/178149328-7b630d88-3196-4968-b84b-6ccdb8a677e3.png)
![image](https://user-images.githubusercontent.com/106106611/178149335-ddeaf408-52b6-4b45-8eaa-e7acfc17b55c.png)
![image](https://user-images.githubusercontent.com/106106611/178149401-12ec7d0a-33a2-46d4-aff1-1b847582a795.png)


Results:
![image](https://user-images.githubusercontent.com/106106611/178149369-94ad9292-dd7f-498d-8390-975e868fd12b.png)
![image](https://user-images.githubusercontent.com/106106611/178149377-c198580f-cda1-41ff-a5d8-a6abcb2f9084.png)
![image](https://user-images.githubusercontent.com/106106611/178149379-3cf55dc9-e7c9-42e2-b837-6b9244cb38b4.png)

Configuration:
<to be completed>


