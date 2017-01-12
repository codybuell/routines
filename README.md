Routines
========

A todo.txt-cli plugin to add special contexts that allow for routines in your task list.

Reserved Contexts
-----------------

@daily
@weekly
@monthly
@quarterly
@yearly
@mondays
@tuesdays
@wednesdays
@thursdays
@fridays
@saturdays
@sundays
@everyotherday | @eod

Config
------

    WEEK_START=[mon|sun] default mon
    Q1_START=[jan|feb|mar|apr|may|jun|jul|aug|sep|oct|nov|dec] default jan

Looks in completed for each task with a special context to see if it is done this _________.  If so it will list it as a task that needs to be done, else it won't show it.  Make todo.sh not show special contexts by default as they will always be there...

Usage
-----

Normal todo usage, just use a special context.

    t routines   <-- lists out by context if context contains

    @daily
        go to gym
        brush teeth

    @weekly
        feed plant

    unused contexts
        @monthly @yearly @mondays @tuesdays @wednesdays @thursdays @fridays ...


