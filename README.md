#### Graphs.
npm install chart.js --save.\
npm install ng2-charts --save

Open and edit 'src/app/app.module.ts' the add this import.
import { ChartsModule } from 'ng2-charts';

imports: [
  ChartsModule,
  ..,
  ..
],

#### Date Picker.

[see this.](https://github.com/write2sv/ionic-date-picker)

npm i ionic-calendar-date-picker --save

import { DatePickerModule } from 'ionic-calendar-date-picker';\
imports: [\
    ....\
    DatePickerModule\
]

