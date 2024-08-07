# Engineering Documentation / AQUARIM / Team X-FANATIC / MIRZAPUR CADET COLLEGE

![main name banner icclm](https://github.com/user-attachments/assets/db33ed1b-8e17-4d06-b3c5-0e979dd02086)

### This repository is the collection of engineering materials pertaining to AQUARIM, a self-driving vehicle model developed by Team mechaScratch_404, participating in the 2023 WRO International Final (Future Engineers) from BANGLADESH.
----

## Team Members:
> CADET TAJWAR  - email: tajwar185@gmail.com

> CADET ADNAN   - email:

> CADET HASNAIN - email: 

----

<img align="left" alt="NAUT" width="200" src="https://github.com/user-attachments/assets/5aab169c-a433-480e-84c6-989e97a1a890">

## Overview of our Repository

 * `experiments` - codes that were used to do experiments.  
 * `models` - the 3D printable files used in our robot.
 * `schematic` - contains the schematic of the electrical system of our robot.
 * `src` - contains the main code of our robot.
 * `video` - contains the video link of YouTube where our robot can be seen in action.
 * `v-photos` - contains the photos of the robot from all required directions
----
----
----

## ***1. Problem Statement: Why this Idea?***
Bangladesh grapples with a severe sewage problem, especially in dense cities. The outdated system, strained by a booming population, simply can't handle the wastewater. Most sewage flows untreated into rivers and canals, contaminating the water with harmful bacteria and threatening public health. This pollution harms aquatic life and endangers the livelihoods of those who depend on these waterways. While Bangladesh is building new treatment facilities, significant investment and upgrades are needed to overcome this challenge.
Bangladesh's dream of becoming a _"Smart Bangladesh"_ faces hurdles due to its persistent sewage woes. Untreated sewage clogs drains and canals, hindering their ability to effectively channel rainwater during heavy monsoon seasons. This overflow contributes to flooding, a recurring nightmare in Bangladesh. Flooding disrupts infrastructure, displaced people, and damages property, stalling progress towards a smart, resilient nation. Investing in proper sewage treatment is crucial not just for public health but also for Bangladesh's smart city ambitions.

## ***2. Impact of damage in Bangladesh***

### I.	Wealthy:
 *	Potential Issues: Unpleasant odors, clogged drains, property damage from floods (indirect).
 *	Mitigation Strategies: Private septic tanks, residence in better-drained areas.

### II.	Middle Class:
 *	Health Risks: Increased risk of waterborne diseases (diarrhea, dysentery) due to reliance on shared sanitation or older septic systems.
 *	Water Quality: Sewage contamination can affect piped water quality, further jeopardizing health.
 *	Mitigation Strategies: Boiling water, improved hygiene practices (may not fully eliminate risk).




### III.	Poor & Vulnerable (Slums/Informal Settlements):
 *	Health: Highest risk of waterborne diseases due to overcrowded and poorly-maintained sanitation facilities. Sewage overflow can seep into homes, creating a constant health hazard.
 *	Displacement: Floods caused by clogged drains disproportionately affect these communities, displacing them and destroying belongings.
 *	Livelihoods: Sewage pollution harms fish populations, impacting food security and income for many.
 *	Limited Mitigation Strategies: Few resources to invest in private sanitation or relocate to safer areas.
----
----

> [!IMPORTANT]
> #### Example: Dasherkandi plant
> The existing sewage treatment system is outdated and overwhelmed by the growing population. Dhaka's recently built Dasherkandi plant, the largest in South Asia, can only handle a small portion (around 20%) of the city's sewage.
----
----

## ***3. Project Description:***
Trash Wizard, a sewage clearing robot with circular water jets and ROS navigation tackles sanitation challenges in Bangladesh's "Smart Bangladesh" vision. By preventing blockages and clearing stagnant water, it not only improves hygiene and efficiency but also helps prevent flood problems in urban areas. This showcases technological innovation, reduces cleaning costs, improves public health, and utilizes a sustainable water-based method. This versatile robot can create new jobs and contribute to a cleaner, healthier, and flood-resilient Bangladesh.

## ***4. Problems we are solving:***
 *	Water Logging: The robot's air blowing cleaning system effectively removes blockages and clears stagnant water that can cause sewage backups and overflows. This prevents flooding and potential damage to property and infrastructure.
 *	Increased Hygiene: Stagnant water and waste buildup in sewage systems create unsanitary conditions and pose health risks. The robot's regular operation helps maintain a cleaner sewage system, reducing the risk of exposure to harmful pathogens and bacteria.
 *	Worker Safety: Cleaning sewage systems can be dangerous due to exposure to hazardous materials and confined spaces. This robot can operate autonomously, eliminating the need for human workers to enter these hazardous environments.

## ***5. Robot Design***
Trash Wizard, a four-wheeled warrior, conquers clogged drains. A powerful blower at its top blasts away blockages like an air cannon. A tireless conveyor belt follows close behind, scooping up the dislodged debris. A dedicated bin stores the waste until emptying. Guiding this champion through the underground maze is a ROS system, enabling autonomous navigation.
 *	4 Wheels: The Trash Wizard robot utilizes a set of four standard, high-clearance wheels. These wheels provide a stable base and allow the robot to navigate uneven surfaces and potential obstacles within the drain.
 *	Conveyor Belt in Front: Imagine a continuously moving carpet at the front of the robot. This is the conveyor belt system, efficiently scooping up debris dislodged by the powerful blower. It prevents debris from re-accumulating and keeps the path clear for the robot to move forward.
 *	Trash Container: Located behind the conveyor belt, this compartment acts like a temporary dumpster. It holds the collected waste until the robot returns to a designated emptying station.
 *	Blower at the Top: Think of this as a powerful air cannon strategically positioned on the robot's back. This blower utilizes directed air blasts to dislodge and break apart blockages caused by debris buildup within the drain.

## ***6.	Working Mechanism and features of our robot***
The robot tackles clogged drains through a synergistic combination of mechanical components and advanced software:
 *	High-Powered Blower: This directional air cannon dislodges blockages by creating powerful air blasts, effectively fragmenting and propelling debris buildup within the drain.
 *	Integrated Conveyor Belt System: Located downstream of the blower, this continuously operating conveyor belt efficiently collects the dislodged waste material. This prevents re-accumulation of debris and facilitates its removal for proper disposal.
 *	ROS-Enabled Navigation System: The robot employs the Robot Operating System (ROS) framework for real-time obstacle detection and path planning. Sensors onboard the CDE provide critical environmental data to ROS, which translates this information into safe and efficient navigation commands within the complex and often confined underground environment.

