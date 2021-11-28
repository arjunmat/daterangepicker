# Date Range Picker

![Improvely.com](https://i.imgur.com/UTRlaar.png)

This project is a fork of the DateRangePicker plugin available at [DateRangePicker.com](www.daterangepicker.com). There are a few options added to meet the requirements of the Travel/Hospitality industry.

## Key Enhancements

1. Allow a single month view with date range picking feature
2. Mark days as available/unavailable
3. Show a price on each calendar date
4. Select a minimum # of days
5. Add custom classes to the calendar
6. Show a popup on a particular date with Minimum Stay requirements
7. Custom currency symbols
8. Callbacks when Previous, Next months are clicked

### Options
`options.singleDatePickerWithMulti` - (Boolean) shows a single month view with date range picker

`options.disableOutsideClick` - (Boolean) disables hiding the calendar when clicked outside the calendar area

`options.disableAutoClose` - (Boolean) disables closing the calendar when a date range is selected

`options.minDays` - (Number) Prevents the user from selecting less than the `minDays` specified

`options.pickerClasses` - (String[]) Adds the classes here to the calendar. Useful to target calendars added to the DOM via CSS.

`options.minStayMessage` - (String) Shows a popup with the message appended to the `minStay` attribute of the customData object.

`options.showSpinner` - (Boolean) Shows a spinner to indicate data load and disables user interaction

`options.currencySymbol` - (String) Prepends the currency symbol to the `price` attribute of the customData object.

`options.clickNextMonthFn` - (Function(start, end)) Calls this function when the Next month arrow is clicked. This can be used to load custom data for the next month's view via the customData object.

`options.clickPrevMonthFn` - (Function(start, end)) Calls this function when the Previous month arrow is clicked. This can be used to load custom data for the previous month's view via the customData object.

The customData object can be formatted as below:

`{
     date: "2021-11-28",
     available: "true",
     price: 50",
     currencyCode: "SGD",
     minStay: 3
}`

## [Documentation and Live Usage Examples](http://www.daterangepicker.com)

## [See It In a Live Application](https://awio.iljmp.com/5/drpdemogh)

## License

The MIT License (MIT)

Copyright (c) 2012-2020 Dan Grossman/Arjun Mathai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## Contributors

Arjun Mathai
Lionel D'souza
Raju Choudhary
Fisher Woon Keng
Sachin Prasanth