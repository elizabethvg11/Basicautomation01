# Basicautomation01
Selenium Academy Basic Course Selenium w/ Java 

Hello , this is the Basic Course of Selenium, Thanks!

Hello man, I am using Selenium with Java 

 @Test
    public void Testselenium(){
        System.setProperty("webdriver.chrome.driver","drivers/chromedriver.exe");
        WebDriver driver = new ChromeDriver();
        driver.get("https://www.google.com");
    }


package Clase02;

import java.util.Scanner;

public class Exercise02 {

    public static void main(String args[])
    {
        Scanner input = new Scanner(System.in);

        System.out.println("Ingrese su nombre");
        String nombre = input.next();

        System.out.println("Ingrese su ano de nacimiento");
        int ano = input.nextInt();

        System.out.println("Ingrese su nacionalidad");
        String nacionalidad = input.next();

        System.out.println("Ingrese su Escolaridad");
        String escolaridad = input.next();

        System.out.println("Ingrese el ano de nacimiento de su hijo");
        int anonachijo = input.nextInt();

        int edad = 2021 - ano;
        int edadhijo = 2021 - anonachijo;

        System.out.println("Su nombre es:" + nombre);
        System.out.println("Su edad es:" + edad);
        System.out.println("Su nacionalidad es:" + nacionalidad);
        System.out.println("Su Escolaridad es:" + escolaridad);
        System.out.println("La edad de su hijo es:" + edadhijo);

    }
}
