## 📅 Matrix Calendar (364)

The **Matrix Calendar** is a Gregorian-anchored 13×28 fixed-year time system.

It provides:

-   13 equal periods per year
-   28 days per period
-   364-day structural year
-   Perpetual 7-day week alignment
-   Simple computational mapping of dates

Year Day (Jan 1) and Leap Day (Feb 29 when present) are treated as special standalone days outside the weekly cycle.

* * *

## Structure

### Year Layout

Code

Year Day  
A01 → A28  
B01 → B28  
...  
M01 → M28  
Leap Day (Feb 29, leap years only)

### Date Anchoring

-   A01 = January 2
-   M28 = December 31

Each day maps deterministically to a fixed Gregorian date.

* * *

## Philosophy

The Matrix Calendar is designed for:

-   Administrative predictability
-   Equal-length planning periods
-   Stable fiscal and project cycles
-   Preservation of the continuous 7-day week

It is an overlay system and does not replace existing civil, religious, or legal calendars.

* * *

## Files Included

-   `matrix-calendar.ics` — Import into Google Calendar / Android / iOS
-   `index.html` — Simple web interface for download

* * *

## Usage

### Option 1 — Import Calendar

1.  Download `matrix-calendar.ics`
2.  Import into your calendar application
3.  Create a separate calendar for toggling visibility

* * *

### Option 2 — Host Your Own Version

Clone the repository:

Bash

git clone https://github.com/YOUR\_USERNAME/matrix-calendar.git

* * *

## License

MIT License

* * *

## Why Matrix Calendar?

Traditional calendars trade structural symmetry for historical convention.  
Matrix Calendar prioritizes computational simplicity and temporal uniformity.

* * *

## Contributing

Suggestions and improvements are welcome via pull requests.

* * *

## Notes

-   Does not alter the Gregorian civil calendar
-   Does not modify weekday cycles
-   Functions as a planning and coordination overlay

* * *

## Future Development Ideas

-   Dynamic ICS generator
-   Visual grid interface
-   Fiscal and academic variants

