# MeowoTracker

## Data agregator for analyzing and activity tracking

## Why?

Existence time-tracking applications not builded for complex activity-analyzing.

On my example:
- Smart-watch count sleep-tracking only in OEM application.
- ActivityWatch much better abstracting platform and have Android support, Linux distibutions and Windows NT distributions

So, for count all that information it requires to take a lot of steps, that also requiring knowledge of platforms.
So, [organisation](https://github.com/MeowoTracker) helps organise my knowledge about activity tracking.

<center style="margin-top: 90px">

![Pie diagram: 33% sleep, 33% device-activity, 33% the rest](./assets/pie.png) 

</center>


<center>

![The diagram represents the system architecture for activity tracking and data analysis. The modules and components related to tracking are shown on the left: 1. Tracker: - Mi Fitness Sleep Tracking - App Usage Android Tracker: ActivityWatch - App Usage Linux Tracker: ActivityWatch 2. Tracker Exporter Layer 3. MeowoTrackerAPI 4. MeowoTracker 5. LLM analyzing The platforms and integration are shown on the right: 1. Android 2. Fedora KDE 3. awatcher bundle 4. ActivityWatch The diagram shows that ActivityWatch integrates with Android and Fedora KDE via the awatcher bundle. MeowoTracker and MeowoTrackerAPI are linked to LLM analyzing, and MeowoTrackerAPI is also linked to MeowoTracker. The Tracker Exporter Layer is linked to Tracker.](./assets/architecture.png) 

</center>

## Installing

- Download latest Pocketbase realease
- Run Pocketbase server
- Upload pb_schema.json from this repository to pocketbase instance

Enjoy another modules!