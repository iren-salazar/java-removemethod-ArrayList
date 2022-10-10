# java-removemethod-ArrayList
showing what is remove in the elements ArrayList in java


package personal;

import java.util.ArrayList;

public class JavaUtilArrayList {
	public static void main(String[] args) {
		
		//create ArrayList
		ArrayList <String> names = new ArrayList <>();
		ArrayList <String> foods = new ArrayList <>();
		ArrayList <String> work = new ArrayList <>();
		
		//ArrayList
		names.add("Elliot ");
		names.add("Cordelia ");
		names.add("Kamaji ");
		//change ArrayList using set method
		names.set(0, "Savanna ");
		names.set(1, "Zacky ");
		names.set(2, "Kevin ");
		
		foods.add("Pizza ");
		foods.add("Pineapple ");
		foods.add("Adobong manok ");
		//change ArrayList using set method
		foods.set(0, "Carbonara ");
		foods.set(1, "Liche Flan ");
		foods.set(2, "Lasagna ");
		
		work.add("Cook ");
		work.add("Nutritionist ");
		work.add("Pro Chief ");
		//change ArrayList using set method
		work.set(0, "Information Technology ");
		work.set(1, "Doctor ");
		work.set(2, "Civil Engineering");
		
		//Select elements in ArrayList using get() method 
		String stranger = names.get(1);
		String dessert = foods.get(1);
		String foodie = foods.get(2);
		String career = work.get(1);
		
		//print ArrayList
		System.out.println("\r" + stranger + "is a " + career + "who likes to eat " + dessert + "and " + foodie + "\r");
		System.out.println();
		System.out.println("\"ArrayLists\"\r");
		System.out.println(names);
		System.out.println(foods);
		System.out.println(work);
		System.out.println();
		String removeThis = names.remove(1);
		System.out.println("Remove element: " + removeThis);
	}
}


