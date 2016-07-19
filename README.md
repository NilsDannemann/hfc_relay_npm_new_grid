![alt tag](https://dl.dropboxusercontent.com/u/7534528/HFC/Relay/relay_logo.jpg)

A grid system and uses flexible sass-mixins instead of fixed classes.<br>


<br>
#Installation
How to get up and running.


<br>
##1. Install Package<br>

Option 1: Install via npm
```sass
npm install hfc-relay-grid --save-dev
```

Option 2: Install via bower
```sass
bower install hfc-relay-grid --save-dev
```

<br>
##2. Create config<br> 
Create a `_hfc-relay-grid-config.scss` with [this content](src/_hfc-relay-grid-config.scss) (but remove all the `!default` statements) <br>

In there you can now:
- safely override any defaults
- easily import/use different fonts 
- toggle features like `debug-grid`

<br>
##3. Import Files<br> 
Import both Files in your sass in this order.
```sass
// HFC Relay
@import 'path/to/your/hfc-relay-grid-config.scss';
@import 'node_modules/hfc-relay/hfc-relay-grid.scss';

// Your other imports below.
```

That's it. <br>
Happy coding.

<br>
##4. Use Snippets (Optional)
The Snippets for Sublime Text are optional but make the workflow much faster. <br>
**Install:** [Download](https://dl.dropboxusercontent.com/u/7534528/HFC/Relay/snippets.zip) the Snippets and place them in your `(path_to_sublime)/Packages/User` folder.<br>
**Usage:** Just type `grid` or `column` and hit `TAB` to place your include.


<br>
#Where to go from there?

- [Container](docs/container.md)
- [The Grid](docs/hfc-relay-grid-guide.md)
- [Mediaqueries](docs/hfc-relay-grid-queries.md)
