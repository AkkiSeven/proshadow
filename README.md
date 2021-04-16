# Proshadow

Create shadows with ease.

## Installation

`npm i -g proshadow`

## Usage

First, create a index.html file.
<br>
Then, create a img tag, with a class of `pshadow`.
<br>
Link the script you want to use.
<br>
In the script, enter the following code.
<br>

```
import { pshadow } from 'proshadow';

pshadow ({
  shadow_type: 'soft',
  padding: true
})
```

The code above shows that the image is going to havea soft shadow, with some padding.
<brZ>
<brZ>

We <strong><em>currently</em></strong> support two options.
<br>
```shadow_type``` which can either be `hard` or `soft`
<br>
and
<br>
```padding``` which can be `true` or `false`.
<br>

### Running (IMPORTANT!!!)
You can run this using any compiler, however, for this demo, I am going to be using `parcel`.

Downloading Parcel:

```
npm i -g parcel
```

Then

```
parcel index.html[or any other html file]
```

## Conclusion

That's it!!! Feel free to make a pull request, or update the package to make it better.
