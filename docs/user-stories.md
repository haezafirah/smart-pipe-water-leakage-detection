# User Stories

As a maintenance technician, I want to receive an alert as soon as a possible leak is detected, so that I can repair the pipe before much water is wasted.

**Aceptance criteria**
1. When a leak is detected, an alert showing the pipe location and time is sent within 30 seconds.
2. No alert is sent when readings are within the normal range.
3. The alert stays marked as active on the dashboard until a user acknowledges it.

As a water utility manager, I want to see live flow and pressure readings on a dashboard, so that I can check the pipe condition without visiting the site.

**Aceptance criteria**
1. The dashboard showws the latest flow and pressure values and refreshes at least every 10 seconds.
2. If a sensor stops sending data for more than 1 minute, the dashboard shows it as "offline".
   
As a system administrator, I want view historical readings for a chosen date range, so that I can analyse leak patterns and find weak points in the pipe network.

**Aceptance criteria**
1. Selecting a date range shows only the readings recorded within that range.
2. Leak events are marked on the history chart with their date and time.
3. Clearing the data range shows the most recent readings again.
