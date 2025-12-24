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

![Диаграмма представляет архитектуру системы для отслеживания активности и анализа данных. Слева показаны модули и компоненты, связанные с отслеживанием: 1. Tracker: - Mi Fitness Sleep Tracking - App Usage Android Tracker: ActivityWatch - App Usage Linux Tracker: ActivityWatch 2. Tracker Exporter Layer 3. MeowoTrackerAPI 4. MeowoTracker 5. LLM analyzing Справа показаны платформы и интеграция: 1. Android 2. Fedora KDE 3. awatcher bundle 4. ActivityWatch Диаграмма показывает, что ActivityWatch интегрируется с Android и Fedora KDE через awatcher bundle. MeowoTracker и MeowoTrackerAPI связаны с LLM analyzing, а MeowoTrackerAPI также связан с MeowoTracker. Tracker Exporter Layer связан с Tracker.](./assets/architecture.png) 

</center>
