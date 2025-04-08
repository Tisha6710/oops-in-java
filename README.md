# oops-in-java
this programm is to print the students information.
package oopsinjava;

class Student {
    String name;
    int rollNumber;
    double marks;

    // Constructor
    Student(String name, int rollNumber, double marks) {
        this.name = name;
        this.rollNumber = rollNumber;
        this.marks = marks;
    }

    // Method to display student details
    void displayDetails() {
        System.out.println("Student Details:");
        System.out.println("Name: " + name);
        System.out.println("Roll Number: " + rollNumber);
        System.out.println("Marks: " + marks);
    }
}

public class StudentClass {
    public static void main(String[] args) {
        Student s1 = new Student("Tisha", 101, 92.5);
        s1.displayDetails();
    }
}

