# Description

DIY Organizer generates monthly and weekly calendars for an entire year.  These caledars are meant to be printed in booklet form.

DIY Organizer was originally from http://www.diyplanner.com/node/6270 under the Creative Commons License.  The program was modified to make greater use of python's calendar module and to make Sunday the first day of the week.


# License

Creative Commons


# Prerequisites

- Python

- LaTeX (pdflatex)


# Configuration

None

# Problems

Monthly calendars requiring more than 5 rows are truncated, losing the days in the
truncated 6th row.  You will have to write them in by hand, better yet, submit a
patch.  The program currently warns you of any truncations.


# Usage

Run the program inside the directory with the TeX templates.

    diy-calendar [-h] [--start-week week] [--start-month month] year

