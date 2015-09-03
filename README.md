# repo2
This is my second repo

		double dollar=0;
		double cents=0;
		double total;
		

		Scanner price= new Scanner(System.in); //create scanner
		System.out.println(" Enter amount of Purchases:"); //Prints "Enter amount of purchases"
	
		double amount = price.nextInt();
		dollar= amount/100;
		cents=amount%100;
		
		total=dollar+cents;
		
		double percent= total * 0.10;
		double discount= total - percent;
		
	
		
	
		if (amount >= 1000) {
			System.out.println("Discounted price: " +discount);
			}

			else System.out.println("Your price is: " +amount); 
