# BUS assignment

## Functional Requirements

### Global View

- The system must allow the user to jump to different locations around the 2D world map and explore them in Augment Reality using the AR View (default).
- The system should also have a search bar that allows the user to instantaneously jump to different locations
- The system must provide the user with overlay options to obtain information from one of the three categories: COVID-19, Travel and user pinned locations.
- The system could have a voice recognition software and reader functionality so that blind people can also access the data provided by the system
- Shouldn’t the system have a help desk?

1. Overlay Options/button
   - COVID-19
   - The system must provide the user with information’s related to:
     - COVID Hotspots
     - COVID guidelines and restrictions within each country
     - Number of Active cases
   - The system must update this information daily

2. The system should be able to provide the user with information regarding:
   - Testing Centres
   - Hospitals
   - Essential stores/Pharmacies
   - Availability of vaccination centres
   - Mental wellbeing helpline

3. The system could provide the user with information regarding:
   - Historical COVID data for areas and public locations
   - Travel
4. The system must provide the user with various travel related information like:
   - Tourist spots
   - Transport hubs
   - Local events

5. User pinned locations
   - The system must allow the user to pin and describe interesting/important locations on the map.
   - The system must allow the pinned locations and related information to be added to the user’s timeline.
   - The system must allow every other user to upvote or downvote the users post to determine the authenticity and uniqueness of the users posts.
   - The system must publish the pins that have reached a certain threshed of upvotes and have been verified by the machine learning system on the user pinned location overlay option on the map.

### Local View

- The system must provide the user with an AR view of their surroundings
- The system should present the building risk level of COVID using a scaled colour system.
- The system should show a safe route to desired locations
- The system could notify the user with information regarding the number of people within a building to allow the user to maintain social distancing while travelling
- The system could notify the user with nearby hospitals, tourist spots and local events within that location (not sure how to phrase it)
- The system could use the AR cameras to detect other humans and notify user for 2 meters distance
- The system could notify the user to wear a face mask and sanitise hands whenever entering an in-door area

## Non-Functional Requirements

1. Usability
   - The system must be able to be used by people with no knowledge of computing

2. Efficiency Performance
   - Speed required to load screens must be within 2 seconds
   - The system must recognise the language the user speaks within 5 seconds if not system should ask the user to speak again.
   - Every 24 hours the data within the system must be updated

3. Space
   - The system must have enough space to allow users to be able to use the system at a given time
   - The system must have enough space to save the where the user has travelled to within the past 1 month.

4. Security
   - The system must ensure that the users private data is not at risk of being lost, manipulated or mistreated in any way

5. Reliability
   - Adaptive evolution of the system
   - If an error occurs within the system, the system must be able to recover from that error without impacting the system or providing incorrect information

6. Availability
   - The system must be available 24/7
