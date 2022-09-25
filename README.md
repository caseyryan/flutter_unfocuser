<a href="https://pub.dev/packages/flutter_unfocuser"><img src="https://img.shields.io/pub/v/flutter_unfocuser?logo=dart" alt="pub.dev"></a>[![style: effective dart](https://img.shields.io/badge/style-effective_dart-40c4ff.svg)](https://pub.dev/packages/effective_dart) <a href="https://github.com/Solido/awesome-flutter">
<img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />

## Features
This widget is used to unfocus any text field in Flutter. You don't need
to use any FocusNodes, FocusScope and other things to do it. 
Very easy to use

It's also a part of my other package 
<a href="https://pub.dev/packages/flutter_multi_formatter">Flutter Multi Formatter</a>

But for those, who don't need any formatters

## Usage

Unfocuser allows you to unfocus any text input and hide the onscreen keyboard 
when you tap outside of a text input. Use it like this:

```dart 
@override
Widget build(BuildContext context) {
return Unfocuser(
    child: Scaffold(
    body: SingleChildScrollView(
        child: Padding(
        padding: const EdgeInsets.all(30.0),
        child: Form(
            key: _formKey,
            child: Column(
            children: <Widget>[
                TextFormField(),
            ],
            ),
        ),
        ),
    ),
    ),
);
}
```



## Additional information


