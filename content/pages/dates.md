+++
title = "Date format used on this site"
slug = "dates"
weight = 9
+++

Dates in the post titles use a year-week-day based format.  
- 2 digit year number (eg `25` for 2025, implies years after 2000)
- 2 digit week number (eg `13` for the thirteenth week of the year as per [ISO 8601 week numbering](https://en.wikipedia.org/wiki/ISO_week_date))
- one letter day-of-the-week with unique symbols for each day

## Days of the week

```
| day       | symbol |
| --------- | ------ |
| Monday    | M      |
| Tuesday   | T      |
| Wednesday | W      |
| Thursday  | R      |
| Friday    | F      |
| Saturday  | S      |
| Sunday    | U      |
```
## Examples

`2503R` -> 2025, week 3, Thursday  
`1936T` -> 2019, week 36, Tuesday  
`2411U` -> 2024, week 11, Sunday  

## Note on years

A "weekyear" is not the same as a calendar year! A week belongs to the year that contains it's Thursday.  
Because of this, `2501M` falls on 2024 December 30.