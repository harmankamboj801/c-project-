#include <stdio.h>

    void convertCtoF(float celsius)
{
    float fahrenheit = (celsius * 9.0 / 5.0) + 32;
    printf("%.2f Celsius = %.2f Fahrenheit\n", celsius, fahrenheit);
}

    void convertCtoK(float celsius) 
{
    float kelvin = celsius + 273.15;
    printf("%.2f Celsius = %.2f Kelvin\n", celsius, kelvin);
}

    void convertFtoC(float fahrenheit)
{
    float celsius = (fahrenheit - 32) * 5.0 / 9.0;
    printf("%.2f Fahrenheit = %.2f Celsius\n", fahrenheit, celsius);
}

    void convertFtoK(float fahrenheit)
{
    float celsius = (fahrenheit - 32) * 5.0 / 9.0;
    float kelvin = celsius + 273.15;
    printf("%.2f Fahrenheit = %.2f Kelvin\n", fahrenheit, kelvin);
}

    void convertKtoC(float kelvin)
{
    float celsius = kelvin - 273.15;
    printf("%.2f Kelvin = %.2f Celsius\n", kelvin, celsius);
}

    void convertKtoF(float kelvin)
{
    float celsius = kelvin - 273.15;
    float fahrenheit = (celsius * 9.0 / 5.0) + 32;
    printf("%.2f Kelvin = %.2f Fahrenheit\n", kelvin, fahrenheit);

}

   int main() 
{
    int choice;
    float temperature;

    printf("Temperature Converter\n");
    printf("1. Celsius to Fahrenheit\n");
    printf("2. Celsius to Kelvin\n");
    printf("3. Fahrenheit to Celsius\n");
    printf("4. Fahrenheit to Kelvin\n");
    printf("5. Kelvin to Celsius\n");
    printf("6. Kelvin to Fahrenheit\n");
    printf("Enter your choice (1-6): ");
    scanf("%d", &choice);

    if (choice < 1 || choice > 6)
    {
        printf("Invalid choice!\n");
        return 1;
    }

    printf("Enter temperature: ");
    scanf("%f", &temperature);

    switch (choice)
    {
        case 1:
            convertCtoF(temperature);
            break;
        case 2:
            convertCtoK(temperature);
            break;
        case 3:
            convertFtoC(temperature);
            break;
        case 4:
            convertFtoK(temperature);
            break;
        case 5:
            convertKtoC(temperature);
            break;
        case 6:
            convertKtoF(temperature);
            break;
    }

    return 0;
}
