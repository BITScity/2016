CSV files under located https://github.com/BITScity/2016 —> Downtown Crossing Sensor Data
https://github.com/BITScity/2016/tree/master/Downtown%20Crossing%20Sensor%20Data

Header: description/ explanation

id_wasp: id of the sensor node

environ1:
	Location: Lat: 42.355328, Lon: -71.060311
	sensors included: CO, CO2, NO2, O2
	
environ2:
	Location: Lat: 42.355169, Lon: -71.060828
	sensors included: CO, CO2, NO2, O2

city1:
	Location: Lat: 42.355195, Lon: -71.060131
	sensors included: GP_TC, GP_HUM, LUM, MCP

city2:
	Location: Lat:  42.355662, Lon: -71.060964
	sensors included: GP_TC, GP_HUM, LUM, MCP

sensor: the sensor type, possible values:
	GP_TC	Temperature Celsius, °C
	GP_HUM	Humidity	%RH
	LUM	Luminosity	Ohms
	MCP	Microphone	dBA
	CO	Carbon Monoxide voltage
	CO2	Carbon Dioxide	voltage
	NO2	Nitrogen Dioxide	voltage
	O2	Oxygen	voltage

value:
	measured value.  See sensor type for corresponding units.
	
timestamp
	timestamp in format: yyyy-mm-dd hh:mm:ss (local timezone for Boston, EDT)


Id, id_secret,frame_type, frame_number, raw:
	These variables are related to the transmitting and recording of the data and probably not needed for analyzing the sensor readings..


For further information about the sensor please see:  http://www.libelium.com/downloads/documentation/data_frame_guide.pdf