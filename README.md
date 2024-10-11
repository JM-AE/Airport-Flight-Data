# Airport-Flight-Data
Project dataset containing sample of FR24 data

adsb - variable description 

1. AircraftId: The model or type of the aircraft. In this case, "B738" refers to the Boeing 737-800 model.


2. Latitude: The current latitude (geographical coordinate) of the aircraft in degrees. For this data, it's 14.6000°.


3. Longitude: The current longitude (geographical coordinate) of the aircraft in degrees. Here, it's -90.5000°.


4. Track: The aircraft's heading or direction of travel in degrees, where 0° is north, 90° is east, 180° is south, and 270° is west. In this case, the aircraft is heading west (270°).


5. Altitude: The aircraft's current altitude in feet. The value 6000 means the aircraft is flying at 6,000 feet.


6. Speed: The aircraft's ground speed in knots (nautical miles per hour). Here, the aircraft is traveling at 400 knots.


7. Squawk: The transponder code assigned by air traffic control (ATC) for identification on radar. The value is "4321", a specific code for the aircraft's current flight.


8. RadarId: The identifier for the radar or data source that tracked the aircraft. In this case, "300" refers to a specific radar station.


9. Type: The aircraft's model designation, which is also listed as "B738" (Boeing 737-800).


10. Registration: The aircraft’s unique registration number. Here, "N826NN" identifies this specific aircraft.


11. LastUpdate: The timestamp of the last recorded data update, in Unix time format (seconds since January 1, 1970). The value "1696350840" corresponds to the last recorded time.


12. Origin: The ICAO code of the airport from which the flight originated. "GUA" refers to La Aurora International Airport in Guatemala City.


13. Destination: The ICAO code of the destination airport. "MIA" refers to Miami International Airport in Miami, Florida.


14. Flight: The flight number. "AAL476" indicates American Airlines flight 476.


15. Onground: A flag indicating whether the aircraft is on the ground or in the air. A value of "0" means the aircraft is airborne.


16. Vspeed: The aircraft's vertical speed, typically measured in feet per minute. A value of "0" means the aircraft is not climbing or descending.


17. Callsign: The radio callsign used by ATC and pilots for communication. "AAL476" is the callsign for American Airlines flight 476.


18. SourceType: The source of the data. In this case, "ADS-B FR24 receivers" refers to data collected from ADS-B (Automatic Dependent Surveillance-Broadcast) receivers, specifically from FlightRadar24.


19. ETA: Estimated Time of Arrival. A value of "0" here may indicate that ETA data is not currently available.

oag - variable description 

1. carrier:

iata: The IATA (International Air Transport Association) airline code. "KE" stands for Korean Air.

icao: The ICAO (International Civil Aviation Organization) airline code. "KAL" is the ICAO code for Korean Air.



2. serviceSuffix: Any suffix for the flight service number. In this case, it's empty.


3. flightNumber: The numerical portion of the flight number, which is 476.


4. sequenceNumber: The sequence of the flight in a series of flights. Here, it's 1.


5. flightType: The type of flight. "Scheduled" indicates it's a regularly scheduled commercial flight.


6. departure:

airport: The departure airport information.

iata: The IATA code for the departure airport. "SGN" is Tan Son Nhat International Airport in Ho Chi Minh City, Vietnam.

icao: The ICAO code for the departure airport. "VVTS" is the ICAO code for Tan Son Nhat.


terminal: The terminal from which the flight is departing. "2" refers to Terminal 2.

date:

local: The local departure date, "2023-10-03".

utc: The UTC (Coordinated Universal Time) date, "2023-10-02".


time:

local: The local departure time, "00:15".

utc: The UTC departure time, "17:15".




7. arrival:

airport: The arrival airport information.

iata: The IATA code for the arrival airport. "ICN" is Incheon International Airport in Seoul, South Korea.

icao: The ICAO code for the arrival airport. "RKSI" is the ICAO code for Incheon.


terminal: The terminal for arrival. "2" refers to Terminal 2.

date:

local: The local arrival date, "2023-10-03".

utc: The UTC arrival date, "2023-10-02".


time:

local: The local arrival time, "07:20".

utc: The UTC arrival time, "22:20".




8. elapsedTime: The flight duration in minutes, which is 305 minutes (5 hours 5 minutes).


9. aircraftType:

iata: The IATA aircraft code. "773" refers to the Boeing 777-300 model.



10. serviceType:

iata: The IATA code for the service type. "J" refers to business class service.



11. segmentInfo:

numberOfStops: The number of stops made during the flight. Here, it’s 0, indicating a direct flight.

intermediateAirports:

iata: A list of intermediate airport codes if there were stops. It’s an empty list here, meaning no stops.




12. codeshare:

cockpitCrewEmployer:

code: The airline employing the cockpit crew, "KE" (Korean Air).

name: The name of the crew employer, which is empty.

number: The number of cockpit crew, which is "4".


jointOperationAirlineDesignators: A list of joint operation airline designators. It's empty here.

marketingFlights: A list of codeshare flights marketed by other airlines:

code: The marketing airline's code (e.g., "DL" for Delta Air Lines, "VN" for Vietnam Airlines, "VS" for Virgin Atlantic).

serviceNumber: The flight service number for each airline (e.g., "7926", "3400", "5520").

suffix: Any suffix for the flight number (empty here).




13. scheduleInstanceKey: A unique key identifying this particular flight schedule instance.


14. statusKey: A unique key representing the flight's status.


15. statusDetails: Information about the flight's status:

state: The current state of the flight. "InGate" means the aircraft is at the gate.

updatedAt: The timestamp of the last status update, "2023-10-02T22:26:29.057".

equipment: Details about the aircraft being used:

aircraftRegistrationNumber: The aircraft’s registration number, "HL7534".

actualAircraftType:

iata: The IATA code for the aircraft type, "773" (Boeing 777-300).

icao: The ICAO code for the aircraft type, "B773" (Boeing 777-300).





16. departure:

estimatedTime: Estimated departure time information.

outGateTimeliness: Status of timeliness at the gate, "OnTime".

outGateVariation: Variation from the scheduled time, "00:00:00" (on time).

outGate:

local: The estimated local departure time, "2023-10-03T00:15:00+07:00".

utc: The estimated UTC departure time, "2023-10-02T17:15:00+00:00".



actualTime: Actual departure time information.

outGateTimeliness: Status of timeliness at the gate, "Delayed".

outGateVariation: The delay from the scheduled time, "00:16:00".

outGate:

local: The actual local time the aircraft left the gate, "2023-10-03T00:31:00+07:00".

utc: The actual UTC time it left the gate, "2023-10-02T17:31:00+00:00".


offGround: The time the aircraft took off:

local: The local time of takeoff, "2023-10-03T00:43:00+07:00".

utc: The UTC time of takeoff, "2023-10-02T17:43:00+00:00".



airport: The departure airport information (same as earlier).



17. arrival:

estimatedTime: Estimated arrival time information.

inGateTimeliness: Status of timeliness at the gate, "Delayed".

inGateVariation: Delay at the gate, "00:02:00".

onGround:

local: The estimated local time of landing, "2023-10-03T07:15:00+09:00".

utc: The estimated UTC landing time, "2023-10-02T22:15:00+00:00".


inGate:

local: The estimated local time the aircraft arrived at the gate, "2023-10-03T07:22:00+09:00".

utc: The estimated UTC time it arrived at the gate, "2023-10-02T22:22:00+00:00".



actualTime: Actual arrival time information.

inGateTimeliness: Status of timeliness at the gate, "Delayed".

inGateVariation: The delay from the scheduled time, "00:01:00".

onGround:

local: The actual local time of landing, "2023-10-03T07:14:00+09:00".

utc: The actual UTC time of landing, "2023-10-02T22:14:00+00:00".


inGate:

local: The actual local time the aircraft arrived at the gate, "2023-10-03T07:21:00+09:00".

utc: The actual UTC time it arrived at the gate, "2023-10-02T22:21:00+00:00".



airport: The arrival airport information (same as earlier).

actualTerminal: The terminal where the aircraft arrived, "T2".

gate: The gate number for the arrival, "231".

baggage: The baggage carousel number, "4".
