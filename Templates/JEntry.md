#Daily
**Yesterday's note:** [[<% tp.date.now("YYYY-MM-DD", -1) %>]]

> [!habits]+ Habits 
>- [ ] Walk 
>- [ ] Add New Resource
> - [ ] Add Missing Note
> - [ ] Add New Note (Mini Essay or Story)
> - [ ] Add Previous Knowledge  
> - [ ] Read

> [!Quote]  Quote of the Day
> s
> — Author


<hr>

# {{Title}}




## Classes 
<%*
const day = tp.date.now("dddd"); 

if (day === "Saturday" || day === "Sunday") {
  tR += "No classes today";
} else if (day === "Tuesday" || day === "Thursday") {
  tR += await tp.file.include("Templates/Even School Schedule 11-1.md");
} else if (day === "Monday" || day === )


  if (day === "Tuesday" || day === "Thursday") {
  } else if (isEvenDay) {
    tR += await tp.file.include("Templates/Odd School Schedule 11-1.md");
  } else {
    tR += await tp.file.include("Templates/Trad School Schedule 11-1.md");
  }
}
%>