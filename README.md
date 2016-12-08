
<!---

This README is automatically generated from the comments in these files:
iban-number.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/iban-number.svg?branch=master)](https://travis-ci.org/PolymerElements/iban-number)

_[Demo and API docs](https://elements.polymer-project.org/elements/iban-number)_


##&lt;iban-number&gt;

`<iban-number>` is a single-line text field with Material Design styling
for entering an email address.

```html
<iban-number></iban-number>
```

It may include an optional label, which by default is "Email".

```html
<iban-number label="your email address"></iban-number>
```

### Validation

The input can be automatically validated as the user is typing by using
the `auto-validate` and `required` attributes. For manual validation, the
element also has a `validate()` method, which returns the validity of the
input as well sets any appropriate error messages and styles.

See `Polymer.PaperInputBehavior` for more API docs.

### Styling

See `Polymer.PaperInputContainer` for a list of custom properties used to
style this element.


