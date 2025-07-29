# Nepali Date Picker

Nepali Datepicker is a pure javascript plugin that allows us to select date from an interactive calendar. The datepicker can be tied to any standard input field, and shows the calendar on focus. The datepicker is hidden after you select the desired date or when focused out of the input.

You can test out the code, and generate javascript code snippets here:
[View Demo](https://nepalidatepicker.sajanmaharjan.com.np/v5)

## Overview

- Light weight
- Free to use
- No database required
- BS date range from 2000 to 2099
- AD date range from 1944 to 2043
- Redesigned UI
- Tabbed Year Selection
- Easy Month Selection
- Dark Mode
- Mini English Dates
- Multiple Date Selection
- Range Selection
- Inline Datepicker

## Install

```
$ npm install @sajanm/nepali-date-picker
```

Include nepali.datepicker.v5.0.5.min.js

```
/* Use online reference */
<script src="https://nepalidatepicker.sajanmaharjan.com.np/v5/nepali.datepicker/js/nepali.datepicker.v5.0.5.min.js" type="text/javascript"></script>

/* or local */
<script src="/path/to/local/nepali.datepicker.min.js" type="text/javascript"></script>
```

Include nepali.datepicker.v5.0.5min.css

```
/* Use online reference */
<link href="https://nepalidatepicker.sajanmaharjan.com.np/v5/nepali.datepicker/css/nepali.datepicker.v5.0.5.min.css" rel="stylesheet" type="text/css"/>

/* or local */
<link href="/path/to/local/nepali.datepicker.min.css" rel="stylesheet" type="text/css"/>
```

Initialize the nepali datepicker

```
/* Select your element */
var mainInput = document.getElementById("nepali-datepicker");

/* Initialize Datepicker with options */
mainInput.NepaliDatePicker();
```

## Sample

```
<html lang="en">
    <head>
        <title>Nepali Datepicker v5.0.5</title>
        <meta http-equiv="x-ua-compatible" content="ie=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta charset="utf-8" />
        <!-- Nepali Datepicker -->
        <link href="https://nepalidatepicker.sajanmaharjan.com.np/v5/nepali.datepicker/css/nepali.datepicker.v5.0.5.min.css" rel="stylesheet" type="text/css"/>
    </head>
    <body>
        <p>
            <input type="text" id="nepali-datepicker" placeholder="Select Nepali Date"/>
        </p>

        <script src="https://nepalidatepicker.sajanmaharjan.com.np/v5/nepali.datepicker/js/nepali.datepicker.v5.0.5.min.js" type="text/javascript"></script>
        <script type="text/javascript">
            window.onload = function() {
                var mainInput = document.getElementById("nepali-datepicker");
                mainInput.nepaliDatePicker();
            };
        </script>
    </body>
</html>
```

## Bonus – Nepali Date Functions

The nepali.datepicker is built upon nepali.functions, so all the functions available under the nepali.functions are available to use after you include the nepali.datepicker javascript file.

Availabe NepaliFunctions ([View the full documentation](https://nepalifunctions.sajanmaharjan.com.np/documentation/index.html))

- Get2DigitNo
- ParseDate
- ConvertToDateObject
- ConvertToDateFormat
- AD2BS
- BS2AD
- ConvertToUnicode
- ConvertToNumber
- NumberToWords
- NumberToWordsUnicode
- AD.GetCurrentDate
- AD.GetCurrentYear
- AD.GetCurrentMonth
- AD.GetCurrentDay
- AD.GetMonths
- AD.GetMonth
- AD.GetDays
- AD.GetDay
- AD.GetDaysShort
- AD.GetDayShort
- AD.GetDaysInMonth
- AD.DatesDiff
- AD.AddDays
- AD.GetFullDate
- AD.GetFullDay
- BS.ValidateDate
- BS.IsBetweenDates
- BS.GetCurrentDate
- BS.GetCurrentYear
- BS.GetCurrentMonth
- BS.GetCurrentDay
- BS.GetMonths
- BS.GetMonth
- BS.GetMonthsInUnicode
- BS.GetMonthInUnicode
- BS.GetFullDate
- BS.GetDaysUnicode
- BS.GetDayUnicode
- BS.GetDaysUnicodeShort
- BS.GetDayUnicodeShort
- BS.GetFullDay
- BS.GetFullDayInUnicode
- BS.GetDaysInMonth
- BS.DatesDiff
- BS.AddDays
- BS.IsEqualTo
- BS.IsGreaterThan
- BS.IsLessThan
- BS.IsGreaterThanOrEqualTo
- BS.IsLessThanOrEqualTo

## Example

```
<script src="https://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/js/nepali.datepicker.v5.0.5.min.js" type="text/javascript"></script>
<script type="text/javascript">
    console.log(NepaliFunctions.GetCurrentBsDate());
</script>
```
