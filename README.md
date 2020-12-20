# Introduction
## Spanish localisation file for Ag Grid
#### Version: 0.0.1
#### Last updated: 20 Dec 2020

As stated in the Ag Grid docs, the displayed text in the grid is customisable for the purposes of localisation. This is done by providing locale information to the grid for the required language. Either provide an object of key->value pairs via the localeText property, or provide a localeTextFunc callback to hook the grid up to your applications localisation.

# Example in an Angular Project:

* First you'll need to add an import of the locale text

```
import { AG_GRID_LOCALE_ES } from 'src/app/l10n/agGrid';
```

* Then assign it to a variable
```
l10nAgGrid = AG_GRID_LOCALE_ES;
```

* The final step is assign the variable to the grid

```
<ag-grid-angular class="ag-theme-material" [columnDefs]="columnDefs" [rowData]="rowData [localeText]="l10nAgGrid">
```

If you have any questions, feel free to ask!