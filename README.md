![Version](https://img.shields.io/static/v1?label=time-blocks&message=0.2&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# Form for flexible management of daily schedule as time blocks

## Problem addressed
This form is meant to help academics who have to manage several writing projects in parallel. 
They have to get the impossible done in a finite amount of time.
They have a lot of discretionary time that they have to manage wisely.
Often, a range of time will be dedicated to a particular writing task.

However, if the writing session is going well, many writers will continue writing and shift other discretionary tasks further down on their schedule.
This downward shifting of other scheduled items is a pain when using pen and paper.
This can be done perhaps a little more easily in an electronic format.
This might be the attraction of web services like Monday.com.

However, I needed something simple that would work on paper.
Cal Newport uses a simple approach described in his 2016 book *Deep work: Rules for focused success in a distracted world*.
He sets up several columns at the start of the day.
The initial schedule goes in the leftmost column while the others remain blank. 
As soon as a change in the schedule occurs, he writes the updated schedule in the next column to the right.
This process is repeated as new changes occur to the schedule.
This form is at the heart of Dr. Newport's comprehensive approach, which including TODO lists.
He describes his full approach in his 2020 book *Time-Block Planner: A Daily Method of Deep Work in a Distracted World*.

I do not follow his full approach because I manage my to-dos in *org-agenda* in *Emacs*.
I should not need this paper form and should do everything in *org-agenda*.
However, I like the portability and flexibility of the paper form.
I carry it around with me on a clipboard.

For visitors who are Emacsens, the table present here could be re-implemented as an org table in an org file.

At the end of the day, you can reflect on the origins of the schedule changes and the amount of time required to complete certain tasks.
This information informs the setting up of future schedules.
As you gain insights into your work behavior, you might be able to minimize the times you have to redo your schedule during the day.

Yes, this is a low-technology solution.
However, it is robust to disruptions in technology.

## Instructions

The file `main.pdf` contains a two-page form. 

- Print out multiple copies of the form.
- Enter planned activities in the leftmost column.
- When an interruption occurs or time spent on one activity is extended, add the extension in the next column to the right and enter the revised schedule below it.
- If you must make more than three revised schedules, you have a time management problem!

The PDF was generated from the `main.tex` file with LaTeX.
Edit the `main.tex` file to suit your own schedule. 
The form eliminates the need to carry a ruler around all day to draw the columns and time blocks.

## Potential modifications

If you follow a rigid writing schedule and write when you are unlikely to be disrupted, like really early in the morning, you could modify the form to contain one to three time blocks of 90-180 minutes dedicated to a writing project.
These could be labeled with A, B, and C by editing the main.tex file or by editing a paper version and then scanning and printing it.
You could change which writing project is assigned to time blocks A, B, and C throughout the week as needed.



## Update history
|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |  Added badges funding, and update table                                                                                                    | 2024 May 4           |
| Version 0.2.1 | Elaborated on why and how to use this form.                                                                                              | 2024 June 2          |

## Funding
- NIH: R01 CA242845, R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel); P20GM103640 and P30GM145423 (PI: A. West)
