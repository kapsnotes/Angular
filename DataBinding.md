# Data binding

4 types

- String interpolation
- Property binding
- event binding
- Two way binding

## String interpolation

Prints value of a ts variable in HTML.

Flow: TS -> HTML

Syntax: `{{ variable }}`

## Property Binding

Bind properties (attributes of html tags) with TS variable

Flow: TS -> HTML

Syntax: `[property]="someVariable"`

## Event binding

Bind JS events with a function in TS

Flow: HTML -> TS

Syntax: `(click)=onClick($event)`

## Two way data binding

Link a variable from HTML to TS and vice versa

Flow: HTML <-> TS

Syntax: `[(ngModel)}="someVariable"`

> For two way binding, we must use
>
> `import { FormsModule } from '@angular/forms';`
>
> and add `FormsModule` in `imports` array of AppModule.ts.

