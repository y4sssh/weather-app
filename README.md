# <h1 align="center">Weather App</h1>

<br>

Building a Weather app with JavaScript is an excellent project for beginners. It helps to understand the core basics of the DOM and teaches how to use fetch API, to call and get data from a third-party service.<br>

This is a simple javascript project made with the help of HTML, CSS, and OpenWeather API. We used weather API to fetch data and display it according to the city entered in the search bar.



# Demo of App

![Screenshot (20)](https://user-images.githubusercontent.com/90332218/194750372-b524eec3-5ef9-4f0c-b82b-770ec8850fc1.png)


# check out live 
Web Url: https://avinash201199.github.io/weather-app/

You can contribute to this project by adding some new features or anything in your mind to contribute <br>
[Check for getting started](https://github.com/avinash201199/weather-app/blob/main/CONTRIBUTING.md)

<br> 
For any query dm on  [Linkedin](https://www.linkedin.com/in/avinash-singh-071b79175)

program
import java.util.*;

public class VectorDemo {
    public static void main(String[] args) {

        Vector<Object> v = new Vector<>(3, 2);
        System.out.println("Initial Size: " + v.size());
        System.out.println("Initial capacity: " + v.capacity());

        v.addElement(new Integer(1));
        v.addElement(new Integer(2));
        v.addElement(new Integer(3));
        v.addElement(new Integer(4));

        System.out.println("Capacity after four additions: " + v.capacity());

        v.addElement(new Double(5.45));
        System.out.println("Current capacity: " + v.capacity());

        v.addElement(new Double(6.08));
        v.addElement(new Integer(7));
        System.out.println("Current capacity: " + v.capacity());

        v.addElement(new Float(9.4f));
        v.addElement(new Integer(10));
        System.out.println("Current capacity: " + v.capacity());

        v.addElement(new Integer(11));
        v.addElement(new Integer(12));

        System.out.println("First element: " + v.firstElement());
        System.out.println("Last element: " + v.lastElement());

        if (v.contains(new Integer(3)))
            System.out.println("Vector contains 3.");

        System.out.println("\nElements in vector:");
        Enumeration<Object> vEnum = v.elements();
        while (vEnum.hasMoreElements())
            System.out.print(vEnum.nextElement() + " ");

        System.out.println();
    }
}
