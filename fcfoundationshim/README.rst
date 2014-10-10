
Foundation Shim for Javascript FullCalendar
===========================================

When I attempted to include `FullCalendar <http://fullcalendar.io/>`_ into a project that used the Foundation framework, I found that the Foundation table styles interfered with the display of the calendar. This was especially pronounced in the Agenda and Day views, but a number of things displayed poorly. I made some adjustments that worked for my own project, and hopefully others can benefit from these as well.

Getting Started
^^^^^^^^^^^^^^^
There's just one file at the moment: fullcalendar-foundation-shim.css. You can include this in your project files wherever FullCalendar is used; just make sure the include for this CSS file occurs after the ones for foundation.css and fullcalendar.css.

Enjoy.

Caveat/Disclaimer
^^^^^^^^^^^^^^^^^
I built this shim for my own purposes and haven't really spent any time trying to make it generic or universal. You may very well find that something looks wonky when you implement this, but I can't promise that I will make any changes if you encounter issues. Your best bet will be to make your own adjustments after the fact. If you discover something you think would be useful for others, feel free to create an issue. Thanks.