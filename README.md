public class Boat {
    int regNum = -1;
    String bClass = "Unknown";
    String name = "Unknown";

    public void print() {
        System.out.println("Boat " + name + ", Class = " + bClass + ", registration # = KA - " + regNum);
    }
}





public class BoatMaker {

    public static void main(String[] args) {
        Boat boat = new Boat();
        System.out.println("Starting Boat Application");
        boat.print();
        myBoat myBoat = new myBoat();
        myBoat.print();
        myBoat2 myBoat2 = new myBoat2();
        myBoat2.print();
        System.out.println("Australia II");
        System.out.println("Harmony Blue");
    }
}
