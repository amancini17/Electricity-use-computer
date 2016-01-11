# Electricity-use-computer
Anthony Mancini and Gideon Yektai

import java.util.*;
public class ProjectSetup {

	public static void main (String[] args){

		  System.out.println("What is the total cost of the computer? ");
		  Scanner reader = new Scanner(System.in);
		  double totalcost = reader.nextInt();
		  System.out.println("your computer total cost is " + totalcost);

		  System.out.println("Is it a laptop or desktop computer? ");
		  Scanner type = new Scanner(System.in);
		  String computertype = type.nextLine();
		  System.out.println("your computer is a " + computertype);
		  
		  System.out.println("Enter screen size: ");
		  Scanner screen = new Scanner(System.in);
		  double screensize = screen.nextInt();
		  System.out.println("the screen size is " + screensize);
		  
		  System.out.println("Enter speed of CPU: ");
		  Scanner speed = new Scanner(System.in);
		  double speedCPU = speed.nextInt();
		  System.out.println("the speed of CPU is " + speedCPU + "MHz");
		  
		  System.out.println("Enter number of cores: ");
		  Scanner number = new Scanner(System.in);
		  double cores = number.nextInt();
		  System.out.println("the number of cores is " + cores);
		  
		  System.out.println("What is the brand/line of the CPU? ");
		  Scanner brand = new Scanner(System.in);
		  String brandline = brand.nextLine();
		  System.out.println("The brand/line is " + brandline);

		  System.out.println("Enter MB of RAM: ");
		  Scanner MB = new Scanner(System.in);
		  double mbram = MB.nextInt();
		  System.out.println("The MB of RAM is " + mbram);

		  System.out.println("What is the size of the hard disk? ");
		  Scanner hard = new Scanner(System.in);
		  double harddisk = hard.nextInt();
		  System.out.println("The size of the hard disk is " + harddisk);

		  System.out.println("Does the mouse need a battery? ");
		  Scanner mouse = new Scanner(System.in);
		  String mousebattery = mouse.nextLine();
		  System.out.println(mousebattery);  

		  System.out.println("Enter Country/State/Province: ");
		  Scanner place = new Scanner(System.in);
		  String location = place.nextLine();
		  System.out.println(location);
		  
		  System.out.println("How long do you expect to keep the computer (in years)? ");
		  Scanner length = new Scanner(System.in);
		  double time = length.nextInt();
		  System.out.println(time + "years");
		  
		  System.out.println("How many hours a day do you leave the computer on? ");
		  Scanner day = new Scanner(System.in);
		  double hours = day.nextInt();
		  System.out.println("hours" + hours);
		  
				}
	}
