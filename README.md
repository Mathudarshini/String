

class Main {
public static void main(String[] args) {
String name = "John Doe";
String greeting = "Hello, ";

   System.out.println("Name: " + name);
    System.out.println(greeting + name);

    String uppercaseName = name.toUpperCase();
    System.out.println("Uppercase Name: " + uppercaseName);

    String lowercaseName = name.toLowerCase();
    System.out.println("Lowercase Name: " + lowercaseName);

    int length = name.length();
    System.out.println("Name Length: " + length);
}

}

Output:

Name: John Doe
Hello, John Doe
Uppercase Name: JOHN DOE
Lowercase Name: john doe
Name Length: 8# String
