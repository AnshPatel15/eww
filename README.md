# EWW Desktop Widget

A simple desktop widget built with EWW (Elkowar's Wacky Widgets) that displays a greeting message with an interactive button.
(demo, i want to create a widget with a notifications section, media controller and CPU and mem usage)

## Features

- Desktop widget that stays in the background
- Interactive greeting button
- Clean, minimal design
- Positioned on the left side of the screen

## Configuration

The widget is configured in `eww.yuck` with the following properties:
- Window type: dock
- Stacking: background
- Position: Left side of screen
- Size: 20% width, 30px height
- Non-focusable
- Window manager ignored

## Usage

1. Start the EWW daemon:
```bash
eww daemon
```

2. Open the widget:
```bash
eww open example
```

3. Close the widget:
```bash
eww close example
```

4. Kill the daemon:
```bash
eww kill
```

## Dependencies

- EWW (Elkowar's Wacky Widgets)
- A window manager that supports EWMH

## Customization

You can modify the widget by editing:
- `eww.yuck` - Widget layout and behavior
- `eww.scss` - Widget styling (if you add one)

## License

This configuration is open source and available under the MIT License. 