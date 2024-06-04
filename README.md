![Version](https://img.shields.io/static/v1?label=time-blocks&message=0.3&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Flexible management of daily schedule with time blocks

<p align="center">
<img src="/images/inaction.png" width="450" >
</p>
 
## Problem addressed
This form is meant to help academics who have to manage several writing projects (e.g., research articles, grant applications, progress reports, grant reviews, manuscript reviews, lectures, seminars, platform talks, letters of support, letters of recommendation, and books) in parallel. 
They have a finite amount of time that they have to manage wisely.
Often, a time range will be scheduled for a particular writing task.
However, if the writing session is going well, many writers will continue writing and shift other discretionary tasks further down on their schedule.
This downward shifting of other tasks is a pain when using pen and paper.
This can be done perhaps a little more easily in an electronic format.

However, I needed something simple that would work on paper.
Dr. Cal Newport describes a simple approach in his 2016 book *Deep work: Rules for focused success in a distracted world*.
He sets up several columns at the start of the day.
The initial schedule goes in the leftmost column while the others remain blank. 
As soon as a change in the schedule occurs, he writes the updated schedule in the next column to the right.
This process is repeated as changes occur to the schedule.
This form is at the heart of Dr. Newport's comprehensive approach, which includes to-do lists.
He describes his full approach in his 2020 book *Time-Block Planner: A Daily Method of Deep Work in a Distracted World*.

I do not follow his full approach because I manage my to-dos in *org-agenda* in *Emacs*.
I would not need this paper form if org-mode could handle time blocking.
It currently lacks this ability, so I must use this paper supplement.
Nonetheless, I like the portability and flexibility of the paper form.
I carry it around with me on a clipboard.

For Emacsens (a.k.a., Emacs users), the table presented here could be re-implemented as an org table in an org file.
It could also be re-implemented in Mardown and Typst.
I plan to make such templates when time permits.

At the end of the day or during your weekly planning session, you can reflect on the origins of the schedule changes and the amount of time required to complete certain tasks.
These data can drive the setting up of future schedules.
As you gain insights into your work habits, you might be able to minimize the number of schedule revisions you make during the day.

Yes, this is a low-technology solution.
However, it is robust to disruptions in technology.

## Instructions

The file `main.pdf` contains a two-page form. 

- Print out multiple copies of the form.
- Enter planned activities in the leftmost column.
- When an interruption occurs or time spent on one activity is extended, add the extension in the next column to the right and enter the revised schedule below it.
- If you must make more than three revised schedules, you have a time management problem!

The PDF was generated from the `main.tex` file with LaTeX.
Edit the time in the leftmost column in `main.tex` file to suit your own schedule. 
The form eliminates the need for a ruler to draw the columns and time blocks.

## Wired variant for recurring events

The wired variant *wired.pdf* demonstrates how to be more efficient when recurring events occur, such as in a writing schedule.
The recurring nature of these tasks bakes them into your daily schedule, so you do not have to waste time and energy scheduling them.

<p align="center">
<img src="/images/wired.png" width="600" >
</p>

If you follow a rigid writing schedule for generative writing and write when you are unlikely to be disrupted, like before other workers show up, you could modify the form to contain one to three-time blocks of 90-180 minutes dedicated to a writing project.
The example above shows three time blocks of 120, 90, and 90 minutes each.
These are labeled writing blocks A, B, and C.
As professional writers will admit, you can sustain only four to five hours of generative writing daily without burning out.

You can assign these time blocks to different writing projects in the row at the top.
The order of assignments could vary daily to break the temporal context.
Also, the three writing projects selected can be varied during the course of a week. 
I use a project number with a keyword as a memory prompt for the project's name.
I have a simple system, but that is another story.

The schedule for our superhuman academic hardwires five hours of progress on three vital writing projects before the first lab member arrives at 9:00 a.m.
In practice, there should be a 15-minute break between writing projects to ease switching between projects.
In addition, due to mental bandwidth limitations, it is easier to work on two parallel projects rather than on three.
The first three-hour block is enough time to accomplish a lot but not too long to exhaust oneself.
The momentum for generative writing that has been built up can then be transferred to project B for 90-120 minutes.
The file *wired2.pdf* has a three-hour time block for project A and a two-hour block for project B.

The rest of our fantasy day can be spent on supportive activities for the writing projects, such as data analysis, figure preparation, slideshow preparation, literature retrieval, and reading related papers to obtain new ideas for the next writing session.
The remainder of the day is often spent instead on supervising, teaching, meetings, service, and administrative chores, but at least the vital writing activities have been accomplished.

If you print out a week's worth of forms, you can block out the recurring events and calendar events (e.g., classes, committee meetings, seminars, workshops)  throughout the week during a weekly planning session.
This may reduce the time spent on daily planning at the start of the day and free it for generative writing.

This approach can support the continuation of writing during traveling to scientific meetings and service on national committees.
For service on grant review panels, it may be best to use the generative writing blocks to prepare presentations about grant applications being reviewed because these reviews require your full mental bandwidth.

## Coming soon

Variants of wired.tex translated to Markdown, Typst, and Org-mode to ease adoption and customization by non LaTeX users.


## Update history
|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |  Added badges funding, and update table                                                                                                    | 2024 May 4           |
| Version 0.3 | Elaborated on why and how to use this form.  Added the wired variants and included images.                                                 | 2024 June 2          |

## Funding
- NIH: R01 CA242845, R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel); P20GM103640 and P30GM145423 (PI: A. West)
