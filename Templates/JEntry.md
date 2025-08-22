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
  "2025-09-02",
  "2025-10-10",
  "2025-10-24",
  "2025-11-10",
  "2025-11-24",
  "2025-11-25",
  "2025-11-26",
  "2025-11-27",
  "2025-11-28",
  "2025-12-22",
  "2025-12-23",
  "2025-12-24",
  "2025-12-25",
  "2025-12-26",
  "2025-12-29",
  "2025-12-30",
  "2025-12-31",
  "2026-01-01",
  "2026-01-02",
  "2026-01-05",
  "2026-01-19",
  "2026-02-13",
  "2026-02-16",
  "2026-03-13",
  "2026-03-16",
  "2026-03-17",
  "2026-03-18",
  "2026-03-19",
  "2026-03-20",
  "2026-03-23",
  "2026-04-20"
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

