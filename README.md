# Flutter Day Night Time Picker

A day night time picker for Flutter with Zero Dependencies.

## Installation

Add to pubspec.yaml.

   ```
   dependencies:
  day_night_time_picker:
  ```

## Usage

To use plugin, just import package

   ```
   import 'package:day_night_time_picker/day_night_time_picker.dart';
   ```

## Example

   ```
   TextButton(
    onPressed: () {
        Navigator.of(context).push(
            showPicker(
                context: context,
                value: _time,
                onChange: onTimeChanged,
            ),
        );
    },
    child: Text(
        "Open time picker",
        style: TextStyle(color: Colors.white),
    ),
),
```
