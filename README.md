Definition List Forms
=====================

A simple mixing for turning definition lists into forms.

### Basic Usage

Just import the mixin into your project like so:

```sass

@import 'dl-form.scss';

```

Then setup your variables, perhaps to match your columns and gutters. $formunit controls the width of the label container. $formgutter merely sets a gutter between label and inputs.

```sass

$formunit: 7em;
$formgutter: 2em;
$font-size: 16px;
$baseline: 24px;

```

Finally, on the container for your form, include the mixin for the magic to happen.

```sass

div.formwrap {

// Include the mixin

@include dlform;

}

```