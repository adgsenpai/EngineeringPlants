# Engineering Plants 

## Purpose 
This repo studies the properties of growing plants in an farming environment.

Consider a plant that is growing in a farm. The plant is growing in a controlled environment, and is being watered and fertilized. The plant is also being monitored for its growth.

Using smart sensors, the plant is being monitored for its growth. The sensors are measuring the following properties of the plant:

```
- Temperature
- Humidity
- Soil Moisture
- Light Intensity
- pH
- CO2
- Water Level
- Nutrient Level
- NPK
        ...
        ...
        ...
- much more
```

The sensors are connected to a Raspberry Pi, which is connected to the internet. The Raspberry Pi is connected to a cloud service, which is connected to a web application. The web application is connected to a mobile application. The mobile application is connected to a user.

For now the user is a farmer. The farmer is using the mobile application to monitor the growth of the plant. The farmer is also using the mobile application to control the watering and fertilizing of the plant.

For now i have gathered and compiled the following information:

- Created Neural Network to compute the Humidity of the plant, Temperature of the plant and Rainfall. Given NPK and pH of the soil


## Directory Structure

```
-root 
    - datasets (all CSV files)    
    - models (all trained models)
- notebooks ...
```