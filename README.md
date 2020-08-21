# Nepali Date Picker
Nepali Datepicker is a pure javascript plugin that allows us to select date from an interactive calendar. The datepicker can be tied to any standard input field, and shows the calendar on focus. The datepicker is hidden after you select the desired date or when focused out of the input.

You can test out the code, and generate javascript code snippets here:
[View Demo](http://nepalidatepicker.sajanmaharjan.com.np/)

## Overview
- Light weight
- Free to use
- No database required
- BS date range from 2000 to 2099
- AD date range from 1944 to 2043

## Install
```
$ npm install @sajanm/nepali-date-picker
```

Include nepali.datepicker.v3.min.js
```
/* Use online reference */
<script src="http://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/js/nepali.datepicker.v3.2.min.js" type="text/javascript"></script>
  
/* or local */
<script src="/path/to/local/nepali.datepicker.min.js" type="text/javascript"></script>
```

Include nepali.datepicker.v3.min.css
```
/* Use online reference */
<link href="http://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/css/nepali.datepicker.v3.2.min.css" rel="stylesheet" type="text/css"/>
  
/* or local */
<link href="/path/to/local/nepali.datepicker.min.css" rel="stylesheet" type="text/css"/>
```

Initialize the nepali datepicker
```
/* Select your element */
var mainInput = document.getElementById("nepali-datepicker");
  
/* Initialize Datepicker with options */
mainInput.nepaliDatePicker();
```

## Sample
```
<html lang="en">
    <head>
        <title>Nepali Datepicker v3</title>
        <meta http-equiv="x-ua-compatible" content="ie=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta charset="utf-8" />
        <!-- Nepali Datepicker -->
        <link href="http://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/css/nepali.datepicker.v3.2.min.css" rel="stylesheet" type="text/css"/>
    </head>
    <body>
        <p>
            <input type="text" id="nepali-datepicker" placeholder="Select Nepali Date"/>
        </p>
  
        <script src="http://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/js/nepali.datepicker.v3.2.min.js" type="text/javascript"></script>
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

Availabe NepaliFunctions ([View the full documentation](http://nepalifunctions.sajanmaharjan.com.np/documentation/index.html))
 - ConvertToDateObject: Convert date string to object
 - ConvertDateFormat: Convert date object to string
 - AD2BS: Convert AD to BS
 - BS2AD: Convert BS to AD
 - ValidateBsDate: Validate if the given BS date is valid
 - GetCurrentAdDate: Gets the Current AD Date
 - GetCurrentAdYear: Gets the Current AD Year
 - GetCurrentAdMonth: Gets the Current AD Month
 - GetCurrentAdDay: Gets the Current AD Day
 - GetCurrentBsDate: Gets the Current BS Date
 - GetCurrentBsYear: Gets the Current BS Year
 - GetCurrentBsMonth: Get the Current BS Month
 - GetCurrentBsDay: Gets the Current BS Day
 - GetAdMonths: Get AD Month List
 - GetAdMonth: Get AD Month
 - GetBsMonths: Get BS Month List
 - GetBsMonth: Get BS Month
 - GetBsDays: Get BS Day List
 - GetBsDay: Get BS Day
 - GetBsDaysUnicodeShort: Get BS Day List in Short
 - GetAdDays: Get AD Day List
 - GetAdDay: Get AD Day
 - GetBsMonthsInUnicode: Get BS Month List In Nepali
 - GetBsMonthInUnicode: Get BS Month In Nepali
 - GetDaysInAdMonth: Get Days in the given AD Month
 - GetDaysInBsMonth: Get Days in the given BS Month
 - AdDatesDiff: Difference between two AD dates
 - BsDatesDiff: Difference between two BS dates
 - BsAddDays: Add days to given BS date
 - GetBsFullDate: Get full BS date
 - GetAdFullDate: Get full AD date
 - GetAdFullDay: Get Full AD day

## Example
```
<script src="http://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/js/nepali.datepicker.v3.2.min.js" type="text/javascript"></script>
<script type="text/javascript">
    console.log(NepaliFunctions.GetCurrentBsDate());
</script>
```