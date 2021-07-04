# -A-Fine-Windy-Day-HackerEarth
Problem  

Moving from traditional energy plans powered by fossils fuels to unlimited renewable energy subscriptions allows for instant access to clean energy without heavy investment in infrastructure like solar panels, for example.  One clean energy source that has been gaining popularity around the world is wind turbines. Turbines are massive structures that are strategically placed in perpetually windy places to generate the most energy. Wind energy is generated when the power of the atmosphere’s airflow is harnessed to create electricity. Wind turbines do this by capturing the kinetic energy of the wind. Factors such as temperature, wind direction, turbine status, weather, blade length, etc. influence the amount of power generated. 

Task

Predict the power that is generated (in KW/h) based on the various features provided in the dataset. 

Data description  
The dataset folder contains the following files:      
train.csv: 28200 x 22     
test.csv: 12086 x 21  

Evaluation metric  

score = max(0 ,100*metrics.r2_score(actual, predicted))

The dataset contains the following columns:

Column name 	Description

tracking_id 	Represents a unique identification number of a windmill
datetime 	Represents the date and time of a record
wind_speed(m/s) 	Represents the speed of wind (in meter per second)
atmospheric_temperature(°C) 	Represents the temperature (in degree Celcius) of a town or village that the windmill is present in
shaft_temperature(°C) 	Represents the temperature of the shaft (in degree Celcius) 
blades_angle(°) 	Represents the angle of the blades of a wind turbine (in degrees)
gearbox_temperature(°C) 	Represents the temperature of a gearbox  (in degree Celcius)
engine_temperature(°C) 	Represents the temperature of an engine (in degree Celcius)
motor_torque(N-m) 	Represents the torque of a motor (in Newton meter)
generator_temperature(°C) 	Represents the temperature of a generator (in degree Celcius)
atmospheric_pressure(Pascal) 	Represents the atmospheric pressure (in Pascals) in that area
area_temperature(°C) 	Represents the temperature (in degree Celcius) of the area within a 100 m radius of the windmill
windmill_body_temperature(°C) 	Represents the temperature of the body of a windmill (in degree Celcius)
wind_direction(°) 	Represents the direction of the wind (in degrees)
resistance(ohm) 	Represents the resistance against the wind
rotor_torque(N-m) 	Represents the torque of a rotor (in Newton meter)
turbine_status 	Represents the status of the turbine (masked)
cloud_level 	

Represents the following levels of the cloud in the sky on a particular day:

    Extremely low
    Low
    Medium

blade_length(m) 	Represents the length of the blades of a windmill (in meter)
blade_breadth(m) 	Represents the breadth of the blades of a windmill (in meter)
windmill_height(m) 	Represents the height of the blades of a windmill (in meter)
windmill_generated_power(kW/h) 	Represents the power generated (in Kilo Watt per hour)


Link to problem: https://www.hackerearth.com/problem/machine-learning/predict-the-power-kwh-produced-from-the-windmills-8-f055f832/
