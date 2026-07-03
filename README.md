
def celsius_to_fahrenheit(celsius):
    return (celsius * 9 / 5) + 32

if __name__ == "__main__":
    temperature = 25
    print(f"{temperature}°C = {celsius_to_fahrenheit(temperature)}°F")
