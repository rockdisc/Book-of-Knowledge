#Daily
**Yesterday's note:** [[<% tp.date.now("YYYY-MM-DD", -1) %>]]

> [!habits] 
>- [ ] Walk 
>- [ ] Add New Resource 
> - [ ] Add Missing Note 
> - [ ] Add New Note (Mini Essay or Story) 
> - [ ] Add Previous Knowledge 
> - [ ] Read 

> [!Quote]  Quote of the Day
> s
> — Author

## Classes 
<%*
const day = tp.date.now("dddd");
const today = tp.date.now("YYYY-MM-DD");

const holidays = [
  "2025-09-01",
  "2025-11-27",
  "2025-11-28",
  "2025-12-25"
];

const isHoliday = holidays.includes(today);

if (day === "Saturday" || day === "Sunday" || isHoliday) {
  tR += "No classes today";
} else if (day === "Tuesday" || day === "Thursday") {
  tR += await tp.file.include("[[Templates/Even School Schedule 11-1]]");
} else if (day === "Monday" || day === "Wednesday") {
  tR += await tp.file.include("[[Templates/Odd School Schedule 11-1]]");
} else if (day === "Friday") {
  if (isHoliday) {
    tR += "No classes today";
  } else {
    tR += await tp.file.include("[[Templates/Trad School Schedule 11-1]]");
  }
}
%>

<hr>

# {{Title}}


