Angular Notes:
	Commands:
		- ng new app-name (creates an angular app)
		- ng serve (runs the app)
		- ng g c components-name (creates a component in the app)
		
	Notes:
		- spec.ts is for testing.
		- .class_name will create div with class name
		- <div *ngFor="let todo of todos; let i = index;" class="todo {{ (todo.completed ? 'done' : '')}}">
			- inside of div element, you can do forloop and use ternary operator
		- <div class="content" (click)="toggleDone(i)">
			- how onClick is used