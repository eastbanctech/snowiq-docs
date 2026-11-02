---
layout: page
title: Guide and Term Dictionary
author: EastBanc Technologies
name: EastBanc Technologies
email: contact@eastbanctech.com
parent: SNOWiQ Overview
nav_order: 1
platform: false
---
<section id="Guide-and-Term-Dictionary" markdown="1">
# Guide and Term Dictionary


<section id="What-is-SNOWiQ" markdown="1">
## What is SNOWiQ?
    
SNOWiQ is a snowplow fleet management and reporting tool for municipalities, snow plow operators, and the public. Based on our TERRAiQ platform, SNOWiQ uses a combination of smartphone-based GPS and cloud technology, delivering a 360-degree view of individual contractor vehicles and your overall snow removal fleet, without costly hardware investments.  Your team and drivers simply log into the SNOWiQ app from the smartphones and devices they already own. SNOWiQ is a Software as a Service (SaaS) solution that combines your internal reporting needs with the convenience of a public dashboard—two mobile applications and a citizen web portal that satisfies all your vehicle tracking, business intelligence, and communication needs. SNOWiQ is designed to meet the unique needs of fleet supervisors, snowplow operators, and the public they serve.

**For Storm Operations Managers/Supervisors** - SNOWiQ’s easy-to-use application lets you visualize your contractor fleet in real-time, from city-wide fleet activity, down to individual neighborhoods. Prioritize fleet movements, dynamically assign, re-route, redeploy, or add drivers, from within the app. You can also enforce quality control, improve performance, time management, and customer service. 

**For Snowplow Operators** - Municipal and contractor drivers can use their smartphones they already own to advertise their availability, receive notifications when routes are assigned to them, seamlessly switch to Google Maps for directions, and confirm when routes are completed.  

**For the Public** - SNOWiQ’s public portal provides residents and businesses with much-needed transparency into snow removal efforts. The portal displays when streets will be plowed, weather updates, and snow removal statistics.
</section>

<section id="Application-Summaries" markdown="1">
## Application Summaries

<section id="Storm-Operations-Center-SOC" markdown="1">
### Storm Operations Center (SOC)
**Platform: Web Application** <br />
**Audience: Storm Operations Managers, Supervisors, Inspectors and Contractor Managers**

This application is primarily used for planning purposes by the SOC Manager to plan and create storm events, review and send 311 tickets to their respective depots, and view the current progress of all actions currently involved in the county. This application is Web-based but can be accessed on mobile devices (iPads, tablets, etc.), if needed. Old documentation refers to this web application as Admin Portal.

</section>

<section id="Supervisor-App-SA" markdown="1">
### Supervisor App (SA)
**Platform: iPad and Android Tablets** <br />
**Audience: Supervisors and Inspectors**

This mobile application is used to create driver assignments for an active storm event, create address specific route assignments, view and manage driver assignment progress, and view and manage 311 tickets that are assigned by Storm Operations Managers/Supervisors from the SOC.
</section>

<section id="Driver-App-DA" markdown="1">
### Driver App (DA)
**Platform: iOS and Android Smartphones** <br />
**Audience: Drivers**

This mobile application is accessed on plow drivers’ (contractor or employee) mobile device. This application allows drivers to view their current assigned routes, their progress, and to set the status of their route to "Completed" in order to move on to their next assignment.
</section>

<section id="Resident-Portal-RP" markdown="1">
### Resident Portal (RP)
**Platform: Web Site** <br />
**Audience: Neighborhood Residents**

This web site allows residents of the county to view statistics about the current storm event as well as data on the progress of different phases (salting, plowing, etc.).

</section>
</section>

<section id="Roles-in-SNOWiQ-SOC-User-Management" markdown="1">
## Roles in SNOWiQ (SOC-User Management)
<section id="Admin" markdown="1">
### Storm Operations Manager

The Storm Operations Manager (assigned the 'Admin' role in SNOWiQ) - This user's primary role is to plan work on upcoming storm events. They are responsible for creating the events in the Storm Operations Center (SOC), along with setting up the phases for supervisors to create assignments for resources. They will mainly use the SNOWiQ SOC for planning and management.

</section>

<section id="Supervisor" markdown="1">
### Supervisor

Supervisors are managers over specific depots (potentially more than one) and are responsible for the management of phases and assignments. Supervisors also work with Storm Operations Managers during storm events planning to create phases and assignments. Supervisors have access to the SNOWiQ SOC for planning and the SNOWiQ Supervisor Application (SA) to create assignments, stop and start phases, and review tickets for assignment. Supervisors can only view routes assigned to their depot, which is automatically set to their default depot. Supervisors also manage their Contractor workforce.

</section>

<section id="Chief-Supervisor" markdown="1">
### Chief Supervisor

A Chief Supervisor is responsible for a whole Depot, including the Supervisors and Inspectors who work in it. Chief Supervisors use the same applications as Supervisors.
</section>

<section id="Inspector" markdown="1">
### Inspector

Inspectors are responsible for the management of contractor resources and route assignments, and ensuring the completion of those assignments by reviewing the work done by the drivers onsite when an assignment is completed. Inspectors primarily use the SNOWiQ Supervisor Application (SA).

Currently, Supervisors and Inspectors have the same application access (both SA and SOC). The difference is primarily in who they manage: Inspectors manage Contractors, Supervisors primarily manage employees, and Chief Supervisors are responsible for the whole Depot.
</section>

<section id="Contractor Manager" markdown="1">
### Contractor Manager

A Contractor Manager is an individual who represents a contracted company that acts as a resource to support Snow Storm Events on a part-time basis. The Contractor Manager has access to SOC and is responsible for managing a contractor's fleet, and is responsible for providing up-to-date equipment information and confirming truck availability.

</section>

<section id="Driver" markdown="1">
### Driver

Drivers are responsible for assignments sent to them by Storm Operations Managers, supervisors, or inspectors. This could include a pre-determined route, a specific address, or queued assignments for multiple phases during a storm event. Assignments may include plowing, salting, a combination of plowing and salting, or multi-pass assignments. Drivers will use the SNOWiQ Driver App on their mobile device to receive assignments and act on those assignments to completion.
</section>

<section id="Resident" markdown="1">
### Resident

Residents have the ability to log into the SNOWiQ Resident Portal to view statistics of the current storm event for the entire county, a specific service area (depot), or a route that their address is associated with. This allows users to get a better understanding of what actions are currently underway in reference to the current situation.
</section>
</section>

<section id="SNOWiQ-Vocabulary" markdown="1">
## SNOWiQ Vocabulary

<section id="Season" markdown="1">
### Season

When a Season is referenced in conjunction with SNOWiQ, it typically refers to a period of time in which there is an increased chance of snowfall in the area and that personnel should be available for snow cleanup and emergency request duties.
</section>

<section id="Event" markdown="1">
### Event

An Event is a single entity created by a Storm Operations Manager to create a plan for an upcoming snow storm (typically 1-2 weeks before the actual storm).

<section id="Event-Statuses" markdown="1">

#### Event Statuses

| New | The event has been created but not yet activated. It can still be edited or deleted. |
| Active | The event is in progress. Only one event can be active at a time. |
| Archived | The event is over and closed. Its event log and reports can still be viewed. |

</section>
</section>

<section id="Phase" markdown="1">
### Phase

A Phase in SNOWiQ is a timeframe used during a Storm Event to define certain activities to be performed by drivers. An example of a Phase would be 'Plowing' - a Phase with an Activity set to 'Plowing' would set all assignments to this activity and drivers included in this phase would need to plow their assigned routes. Several phases can be active at the same time; when activating a new phase, a user can choose to complete or pause the currently active phase (see [Phase Management](soc-phase-management.html)).

<section id="Phase-Statuses" markdown="1">

#### Phase Statuses

| New | The phase has been created but not yet activated. |
| Active | The phase has been activated. Several phases can be active at the same time. |
| Completed | The phase has been completed manually by a Supervisor. |
| Archived | The event the phase belongs to has been archived. |

</section>
</section>

<section id="Monitoring-Phase" markdown="1">
### Monitoring Phase

The Monitoring phase is created automatically for every depot when an event is created, and is activated automatically when the event is activated. It covers the time before active work begins, when Supervisors watch conditions and get resources into position, for example by sending Drivers to a [staging location](#Staging-Location). The Monitoring phase must always be completed manually.
</section>

<section id="Activity" markdown="1">
### Activity

An Activity is the type of work to be performed, for example Monitoring, Salting, or Plowing. Every phase and every assignment has an Activity. Drivers see the Activity of each assignment in the Driver App.
</section>


<section id="Depot" markdown="1">
### Depot

A Depot is a centralized hub that manages a number of routes in its [service area](#Service-Area). Typically, a single Supervisor manages a depot. A Depot can potentially have multiple Inspectors that manage individual routes within the service area.
</section>

<section id="Service-Area" markdown="1">
### Service Area

A Service Area is the set of routes that a single depot is responsible for. The service areas of all depots together make up the area covered by SNOWiQ. Throughout the applications, filtering by depot limits the map and lists to that depot's service area.
</section>

<section id="Staging-Location" markdown="1">
### Staging Location

A Staging Location is a point on the map where Drivers are sent to wait, ready to start work, before the active phase of an event begins (usually during the Monitoring phase). Supervisors send Drivers to a staging location by creating a [Staging Location assignment](sa-supervisor-activities.html#Creating-Staging-Location-Assignment) in the Supervisor App.
</section>

<section id="Driver-1" markdown="1">
### Driver

See ‘Driver’ Definition under the ‘Roles’ section above. When logged into the app, Storm Operations Managers, supervisors, and inspectors will be able to see the driver markers on an interactive map along with their current status at the time (notated by a color specified in Status below). Employees can be found on the map with a circular snowplow marker while contractors will be found with a square marker.

</section>

<section id="Truck-1" markdown="1">
### Truck

A Truck is a piece of heavy vehicle equipment that has a profile in the system. All Truck profiles are created by Storm Operations Manager and stored in the system and can be managed in Truck Management module.

<section id="Truck-Statuses" markdown="1">

#### Truck Statuses

| Active | Truck successfully passed inspection and has been certified in the system. |
| Inactive | Truck has been decertified because of a failed inspection. |
| In Review | Contractor's truck has been created and is pending certification by the contractor manager. |

</section>
</section>

<section id="Truck-Class" markdown="1">
### Truck Class

Trucks are grouped by equipment class: Tandem, Heavy, Medium, Light, and Pickup. Truck classes are used when requesting trucks from contractor companies and in the Truck Inventory (see [Contractor Request](soc-contractor-request.html)).
</section>

<section id="Truck-Certification" markdown="1">
### Truck Certification

A truck must be certified before it can be used. Trucks can be certified or decertified in [Truck Management](soc-truck-management.html). A reason is required to decertify a truck, for example a failed inspection. A decertified truck has the 'Inactive' status.
</section>

<section id="Resource-1" markdown="1">
### Resource

A Resource is composed of a Driver and a Truck. Resources are managed in the Storm Operation Center and Supervisor app. Resources can have different statuses depending on the Storm Event stage.

<section id="Resource-Actions" markdown="1">

#### Resource Actions

| Check-in | After logging in to the Driver App, a Driver submits a check-in request with their truck. A Supervisor reviews and confirms it in [Resource Management](sa-resource-management.html#check-in-resources), and the Driver becomes a resource for the event. |
| Shift Handover | Moves a resource's assignments to another resource, for example at the end of a shift. The previous Driver is then released automatically. |
| Release | Releases a Driver from duty. The Driver is logged out of the Driver App, and their truck becomes available to another Driver. |

</section>

<section id="Resource-Checkin-Statuses" markdown="1">

#### Resource Check-in Statuses

| New |  Create a new resource, or import a resource from a previous event. |
| Checked-in | The Storm Event has started and a driver user is logged in to their profile on the Driver app and has confirmed a truck. |
| Released | The driver has been released from the truck. |
| Abandoned | When a driver changes truck, a new resource is created and the old one becomes Abandoned. |

</section>

<section id="Resource-Service-Statuses" markdown="1">

#### Resource Service Statuses

| Logged in (Contractor Only) | A Contractor is logged in to the system, but has not yet accepted any new assignments and is not working on any active assignments. This status is for drivers awaiting a new status after logging in. (This status means no payment is being calculated for the driver, whether they just logged on or have been released.) |
| StandBy (Contractor Only) | is for Contract Drivers who are in position, awaiting assignment. This status is applied manually to a driver by their supervisor. (This status allows for calculation of payment by half of their rate.) |
| Ready | is the default status for County Drivers after logging on. For Contract Drivers, it is applied manually by their supervisor to indicate that the driver is ready to begin work on another assignment. (This status allows for calculation of payment at the Contract Driver's full rate.) |
| In Service | is for Drivers who have accepted and started an assignment. |
| Paused | is for when a supervisor manually pauses a driver. This puts all assignments in the driver's queue on hold until the Supervisor resumes the driver manually. |
| Offline | is for users that are not logged into the SNOWiQ Driver Application, drivers that are out of range of the service area (out of range), or any drivers that are not able to broadcast/receive GPS coordinates to the system (out of service). |

</section>

</section>

<section id="Route" markdown="1">
### Route

A Route is a set of geo-located path lines within a depot, previously uploaded into the SOC, that is used in assignments to drivers along with a status indicator (color-coded based on route status). Route is a combination of route segments with one or more segment types (emergency, primary or neighborhood). A Route can have multiple assignments and drivers attached to it.

<section id="Route-Types" markdown="1">
#### Route Types

* **Emergency:** These routes have priority over Residential routes. When selected in an assignment these routes are to be worked first and, depending on the active route plan settings, an emergency route could be represented by either emergency (red) road segments or a combination of emergency (red) road segments and primary (blue) road segments.

* **Residential:** These routes have a lower priority and are to be worked on after Emergency routes are completed. Depending on the active route plan settings (uploaded into the system in Route Plans), a residential route could be represented by either neighborhood (orange) road segments or a combination of neighborhood (orange) road segments and primary (blue) road segments.

</section>

<section id="Route-Segment-Types" markdown="1">
#### Route Segment Types

A route is made up of road segments. Each segment has a type, shown by its color on the map:

* **Emergency (red):** Roads that must be cleared first.
* **Primary (blue):** Main roads. Primary segments can be part of both Emergency and Residential routes.
* **Neighborhood (orange):** Residential streets.

Segment type is not the same as route type (Emergency or Residential). Route type describes the priority of the whole route.

</section>

<section id="Route-Statuses" markdown="1">

#### Route Statuses

| Unassigned | There are no assignments created for the route. |
| In Progress | The route has one of the four statuses below. This aggregated status is used when using filters throughout all applications for simplification. |
| Pending | There is at least one assignment but it hasn't yet been accepted by the Driver. |
| Assigned | There is at least one accepted assignment for the route. |
| Started | There is at least one started assignment for the route. |
| Completed Pending | There is at least one completed pass on a multi-pass assignment and it's awaiting action from Supervisor. |
| Completed | The route has had its assignment(s) completed by assigned driver(s), or the inspector/supervisor manually set the route to 'completed'. |
| Inspected | The route has had its assignment verified and finalized by an inspector. |

</section>
</section>

<section id="Route-Plan" markdown="1">
### Route Plan

A Route Plan is the geo-data file that defines the routes, road segments, and boundaries of a depot. Admins upload Route Plans in [Route Management](soc-route-plans.html). When a new Route Plan is uploaded, the previous version is archived. Each event uses a specific Route Plan version.
</section>

<section id="Committed-Route" markdown="1">
### Committed Route

A Committed Route is a route that a Supervisor has selected to be worked during a phase. Supervisors choose which routes to commit when activating a phase, and can commit more routes as the event progresses (see [Commit Routes](soc-phase-management.html#Commit-Routes)).
</section>

<section id="Breadcrumbs" markdown="1">
### Breadcrumbs

Breadcrumbs are the trail of GPS points recorded by the Driver App as a Driver works a route. They show on the map which parts of a route have been completed, and are used to calculate route progress. The system also uses breadcrumbs to validate MC311 tickets (see [Ticket Import Validation Rules](soc-mc311-tickets.html#Ticket-Import-Validation-Rules)).
</section>

<section id="Assignment" markdown="1">
### Assignment

An Assignment is a task created by a Supervisor and assigned to a Resource. An assignment can be for an existing route, an address, a staging location, or a ticket.

<section id="Assignment-Statuses" markdown="1">

#### Assignment Statuses

| Pending | Supervisor has created a new Assignment which is pending acceptance from the Driver. |
| Paused | Supervisor has manually paused an Assignment. |
| Accepted | Driver has accepted the assignment. |
| Started | Driver has arrived at the destination, manually started the assignment, or the assignment has resumed from a paused state. |
| Completed | Driver has finished working on assignment, or the supervisor has manually marked the route as complete. |
| Completed Pending | Driver has manually completed a route pass on a multi-pass assignment, and the assignment is pending a review by the Supervisor to determine if another pass is needed. |
| Cancelled | Supervisor manually canceled the assignment. |

</section>
</section>

<section id="Pass" markdown="1">
### Pass, Single-Pass and Multi-Pass Assignments

A Pass is one complete run of a route by a Driver. A **single-pass** assignment is finished after one pass. In a **multi-pass** assignment, the Driver completes a pass and then waits while the Supervisor decides whether another pass is needed (status 'Completed Pending'). The Supervisor either requests another pass or completes the assignment. See [Completing Assignments for Multi-Passes](sa-supervisor-activities.html#Completing-Assignments-for-Multi-Passes).
</section>

<section id="Priority-Task" markdown="1">
### Priority Task

A Priority Task is an assignment that a Supervisor has marked as a priority. It is placed at the top of the Driver's queue of Future assignments. Any type of assignment can be a priority task.
</section>

<section id="Ticket" markdown="1">

### Ticket

A Ticket is a geo-point service request from different users of the system. Once the ticket is created, the system automatically associates it with a route. Depending on the user who requested the service, a ticket can have a different type.

<section id="Ticket-Types" markdown="1">

#### Ticket Types

* **MC311 (or Residential):** Service requests imported from the Montgomery County 311 system where residents report snow storm related issues.

* **Emergency:** Service requests from emergency services (EMS, Fire Dept), or other requests created by a Storm Operations Manager user.

</section>

<section id="Ticket-Status" markdown="1">

#### Ticket Statuses

| New  | The system has validated that the 311 ticket is valid for assignment, or a new emergency ticket was created but not yet sent out for assignment. |
| Sent | The Storm Operations Manager user has reviewed the ticket and sent it to Supervisor App (SA) for assignment creation. |
| Assigned | The Supervisor has created the Assignment in the SA and has sent it to the Driver, but the work has not begun. |
| In Progress | The Driver commenced work on the ticket assignment. |
| Pending | The system has defined the ticket as invalid and is preparing to close it. |
| Closed |  A Supervisor has manually closed a ticket; or the system has checked the service request and found it invalid and set the ticket to closed; or the assigned resource has finished the work and marked the assignment as completed. |

</section>
</section>
</section>

<section id="Contractors" markdown="1">
## Contractors

<section id="Contractor-Company" markdown="1">
### Contractor Company

A Contractor Company is a company contracted to provide trucks and drivers during snowstorm events. Each company has a [Contractor Manager](#contractor-manager). Admins and Supervisors add contractor companies to an event.
</section>

<section id="Contractor-Request" markdown="1">
### Contractor Request

A Contractor Request is a request from a Supervisor to a contractor company for a number of trucks of each class, for a specific depot and inspector. A request is 'On-Hold' until the Contractor Manager confirms it, and then becomes 'Confirmed'. See [Contractor Request](soc-contractor-request.html).
</section>

<section id="Truck-Inventory" markdown="1">
### Truck Inventory

The Truck Inventory shows, for an event and by truck class, how many contractor trucks are available, requested, confirmed, and checked in, and how many confirmed trucks have not yet checked in.
</section>
</section>

<section id="Field-Conditions-and-Materials" markdown="1">
## Field Conditions and Materials

<section id="Road-Hazard" markdown="1">
### Road Hazard

A Road Hazard is a marker on the map that warns users of a hazard on the road. A **road plate** is a permanent hazard, and a **temporary hazard** is something like a fallen tree, downed power line, or traffic accident. Drivers and Supervisors can create and delete road hazards, and they are visible to all users working in the same service area. See [Road Hazards](da-road-hazards.html).
</section>

<section id="Road-Condition" markdown="1">
### Road Condition

A Road Condition is a report of road and air temperature and precipitation at a specific location, created by a Supervisor or Inspector in the Supervisor App. Road Conditions expire 1 hour after they are reported. See [Road Conditions](soc-road-conditions.html).
</section>

<section id="Thermal-Map" markdown="1">
### Thermal Map

The Thermal Map is a statistical heatmap that shows how the temperature of each road segment typically compares to the average for the area. It does not show real-time temperatures. See [Thermal Map](soc-road-conditions.html#thermal-map).
</section>

<section id="Material" markdown="1">
### Material

Material is the salt or brine loaded onto trucks to treat roads. Supervisors and Inspectors log material loadings and returns for each resource in the Supervisor App, and material usage is reported in the Active Storm Report. See [Material Management](sa-material-management.html).
</section>
</section>

<section id="Application-Features" markdown="1">
## Application Features

<section id="Event-Log" markdown="1">
### Event Log

The Event Log is a record of the actions taken during an event: what happened, when, and who did it (a user or the system). It is available in the SOC as the [Active Storm Log](soc-active-storm-log-report.html) and in the Supervisor App.
</section>

<section id="Detached-Mode" markdown="1">
### Detached Mode

Detached Mode is an offline mode of the Driver App. It downloads the map and the Driver's assignments in advance, so the Driver can keep working when the network is unavailable. See [Detached Mode](da-detached-mode.html).
</section>

<section id="Cluster" markdown="1">
### Cluster

A Cluster is a numbered marker that groups nearby markers when the map is zoomed out. Selecting a cluster zooms in to show the individual markers.
</section>

<section id="Map-Layers" markdown="1">
### Map Layers

Map Layers control which markers and road segments are displayed on the map in the Supervisor App. See [Map Layers](sa-login-and-navigation.html#Map-Layers).
</section>
</section>
</section>
