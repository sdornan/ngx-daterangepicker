# ngx-daterangepicker

## Installation

To install this library, run:

```bash
$ npm install ngx-daterangepicker --save
```

## Usage

You can import this library in any Angular application by running:

```bash
$ npm install ngx-daterangepicker
```

and then from your Angular `AppModule`:

```typescript
import { BrowserModule } from '@angular/platform-browser';
import { NgModule } from '@angular/core';

import { AppComponent } from './app.component';

import { DateRangePickerModule } from 'ngx-daterangepicker';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    DateRangePickerModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

Once your library is imported, you can use its component in your Angular application:

```xml
<!-- You can now use your library component in app.component.html -->
<daterangepicker startDate="someDate" endDate="anotherDate"></daterangepicker>
```

## Development

To generate all `*.js`, `*.d.ts` and `*.metadata.json` files:

```bash
$ npm run build
```

To lint all `*.ts` files:

```bash
$ npm run lint
```

## License

MIT © [Sam Dornan](mailto:sdornan@gmail.com)
