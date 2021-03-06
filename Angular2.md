Angular applications are made up of components. A component is the combination of an HTML template and a component class that controls a portion of the screen. Here is an example of a component that displays a simple string:

## src/app/app.component.ts
COPY CODE

```
import { Component } from '@angular/core';

@Component({
  selector: 'my-app',
  template: `<h1>Hello {{name}}</h1>`
})
```
export class AppComponent { name = 'Angular'; }
Try this QuickStart example on Plunker without installing anything. Try it locally with the QuickStart seed and prepare for development of a real Angular application.
Every component begins with an @Component decorator function that takes a metadata object. The metadata object describes how the HTML template and component class work together.

The selector property tells Angular to display the component inside a custom <my-app> tag in the index.html.

## For the Angular!