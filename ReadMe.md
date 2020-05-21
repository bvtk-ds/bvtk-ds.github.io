# How to use BVTK!

**BVTK** is a more simplied and larger view of Trello boards, broken into an organized task board in Kanban fashion.
And because you may want to reduce information on the page even more or make things easier to read, we've provided some paramaters that can adjust your experience.

## Parameters
Here are instructions on various parameters that work for BVTK with examples of how it works.

### columns
This is a way to reduce which columns show up on screen. It goes in order from left to right, Backlog being your 0 column and Complete being your 3 column. You can exclude multiple columns at once by using "," as a separater.

***Examples:***
* _Removing Backlog_
  * [https://bvtk-ds.github.io/?columns=0](https://bvtk-ds.github.io/?columns=0)

* _Removing Complete_
  * [https://bvtk-ds.github.io/?columns=3](https://bvtk-ds.github.io/?columns=3)
		
* _Removing Backlog and Complete_
  * [https://bvtk-ds.github.io/?columns=0,3](https://bvtk-ds.github.io/?columns=0,3)
		

### exclude
Exclude is an Trello Board exclusion filter. By default, every kind of board is include except for Organization owned boards. You can exclude multiple boards at once by using "," as a separater.

***Examples:***
* _Removing the Big View Trello Kanban board_
  * [https://bvtk-ds.github.io/?exclude=Big View Trello Kanban](https://bvtk-ds.github.io/?exclude=Big View Trello Kanban)
		

### ts
Adjusts the text size of the task cards only. The size is evaluated as *em* values and defaults to 1 em.

***Examples:***
* _Default size enforced_
  * [https://bvtk-ds-github.io/?ts=1](https://bvtk-ds-github.io/?ts=1)
		
* _Upping to 1.25em_
  * [https://bvtk-ds-github.io/?ts=1.25](https://bvtk-ds-github.io/?ts=1.25)