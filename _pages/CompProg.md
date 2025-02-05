---
title: "Seminars"
layout: textlay
excerpt: "Seminars"
sitemap: false
permalink: /Seminars
---
Starting from 21st of January 2025, the Finite Group Schemes seminar takes place each Tuesday at 11:00 am, in A11 lecture hall of our department.

<div id="calendar"></div>
<style>
    body {
        background-color: #f4f4f4;
        font-family: Arial, sans-serif;
    }

    #calendar {
        max-width: 800px;
        height: 600px;
        margin: 0 auto;
        background-color: lightblue;
        border: 1px solid #000;
        padding: 15px;
    }
    .fc-daygrid-day {
    border: 1px solid #000 !important;  /* black border for each day box */
}
</style>

<script src="https://cdn.jsdelivr.net/npm/fullcalendar@5.11.3/main.min.js"></script>
<link href="https://cdn.jsdelivr.net/npm/fullcalendar@5.11.3/main.min.css" rel="stylesheet">

<script>
document.addEventListener('DOMContentLoaded', function() {
    var calendarEl = document.getElementById('calendar');
    var calendar = new FullCalendar.Calendar(calendarEl, {
        initialView: 'dayGridMonth',
        eventContent: function(arg) {
        return { html: `<div style="white-space: normal; font-size: 16px; padding: 5px;">${arg.event.title}</div>` };
    },
        events: [
            { title: 'Kostas Karagiannis: Introduction Part A', start: '2025-01-21'},
            { title: 'Ilias Andreou: Introduction Part B', start: '2025-01-28' },
            { title: 'Ilias Andreou: Lie Algebras', start: '2025-02-04' },
            { title: 'Ilias Andreou: Quotients', start: '2025-02-04' }

        ]
    });
    calendar.render();
});
</script>

(Left click on each image to see the lecture on youtube.)

# Finite Group Schemes (Playlist)

[![IMAGE ALT TEXT HERE](http://arithmeticgeomuoa.github.io/images/seminar/fgs.png){: width="1000" height="600"}](https://www.youtube.com/watch?v=_OdP_YzZYTM&list=PL1HKKfy_YD8ey1ijBLRjK06wr19m75QLm&index=2)

# Witt Vectors

[![IMAGE ALT TEXT HERE](http://arithmeticgeomuoa.github.io/images/seminar/witt.png){: width="1000" height="600"}](https://www.youtube.com/watch?v=agANznqlub4)

# Higher Ramification Groups

[![IMAGE ALT TEXT HERE](http://arithmeticgeomuoa.github.io/images/seminar/ramification.png){: width="1000" height="600"}](https://www.youtube.com/watch?v=JA43RafucyA)

# Introduction to Stacks (Playlist, 7 lectures)

[![IMAGE ALT TEXT HERE](http://arithmeticgeomuoa.github.io/images/seminar/stacks.png){: width="1000" height="600"}](https://www.youtube.com/watch?v=rmf8hEVSgWE&list=PL1HKKfy_YD8dwsuNRQoza7WlJVrhZPRul&index=6)
