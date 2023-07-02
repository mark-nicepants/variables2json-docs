
![Cover artwork](https://github.com/mark-nicepants/variables2json-docs/blob/main/artwork/cover%20art.png?raw=true)

# Figma plugin: variables2json
`variables2json` is a plugin for Figma that simplifies the process of exporting publishable variables and saving them in a JSON file. 

With this plugin, you can easily view and export variables of various types, including color, number, string, boolean, and aliasses are automatically resolved. 

When combined with code generation tools it provides a powerful way to integrate Figma designs with your codebase.

## Installation & usage
To install the variables2json plugin, follow these steps:

- Download and install the Figma desktop app.
- Search `variables2json` in the Figma Community plugins section.
- Within your Figma project, type `variables2json` in the command bar to open the plugin.
- Click the download button in the footer to export the variables to a JSON file.

## Supported Variables
`variables2json` supports the following variable types for extraction:
- ✅ Color 
- ✅ Number
- ✅ String 
- ✅ Boolean
- ✅ Alias

## Local styles
`variables2json` supports local styles for typography, effects and grids.
- ✅ Textstyles
- ✅ Effects
- ✅ Grids
  
## Features in Development
The `variables2json` plugin is continuously being improved, and the following features are currently under development:

- 🚧 <b>Composites</b>: Assign metadata to Frames and group variables and styles together for powerful organization and management.
- 🚧 <b>Git Sync</b>: Synchronize variables with a Git repository for version control and collaborative workflows.

## Explantion of the JSON file

<details>
  <summary>Example JSON output</summary>
  
```json
{
  "version": "1.0.2",
  "metadata": {},
  "collections": [
    {
      "name": "Theme",
      "modes": [
        {
          "name": "Light",
          "variables": [
            {
              "name": "insult",
              "type": "string",
              "value": "Yo"
            },
            {
              "name": "bigGap",
              "type": "number",
              "value": 54
            },
            {
              "name": "Colors/panelBg",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 1
              }
            },
            {
              "name": "Colors/divider",
              "type": "color",
              "value": {
                "r": 229,
                "g": 229,
                "b": 229,
                "a": 1
              }
            },
            {
              "name": "Colors/selected",
              "type": "color",
              "value": {
                "r": 0,
                "g": 0,
                "b": 0,
                "a": 0.1
              }
            },
            {
              "name": "Colors/icon",
              "type": "color",
              "value": {
                "r": 0,
                "g": 0,
                "b": 0,
                "a": 1
              }
            },
            {
              "name": "Mr Boolean",
              "type": "boolean",
              "value": false
            },
            {
              "name": "buttonPrimary",
              "type": "color",
              "value": {
                "r": 0,
                "g": 255,
                "b": 25,
                "a": 1
              }
            },
            {
              "name": "Colors/windowBackground",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 1
              }
            },
            {
              "name": "Colors/panelFg",
              "type": "color",
              "value": {
                "r": 44,
                "g": 44,
                "b": 44,
                "a": 1
              }
            },
            {
              "name": "Colors/mutedText",
              "type": "color",
              "value": {
                "r": 0,
                "g": 0,
                "b": 0,
                "a": 0.3
              }
            },
            {
              "name": "smallGap",
              "type": "number",
              "value": 4
            },
            {
              "name": "Colors/primaryText",
              "type": "color",
              "value": {
                "r": 0,
                "g": 0,
                "b": 0,
                "a": 1
              }
            }
          ]
        },
        {
          "name": "Dark",
          "variables": [
            {
              "name": "insult",
              "type": "string",
              "value": "mama"
            },
            {
              "name": "bigGap",
              "type": "number",
              "value": 108
            },
            {
              "name": "Colors/panelBg",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 0.1
              }
            },
            {
              "name": "Colors/divider",
              "type": "color",
              "value": {
                "r": 68,
                "g": 68,
                "b": 68,
                "a": 1
              }
            },
            {
              "name": "Colors/selected",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 0.1
              }
            },
            {
              "name": "Colors/icon",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 1
              }
            },
            {
              "name": "Mr Boolean",
              "type": "boolean",
              "value": true
            },
            {
              "name": "buttonPrimary",
              "type": "color",
              "value": {
                "r": 45,
                "g": 4,
                "b": 4,
                "a": 1
              }
            },
            {
              "name": "Colors/windowBackground",
              "type": "color",
              "value": {
                "r": 44,
                "g": 44,
                "b": 44,
                "a": 1
              }
            },
            {
              "name": "Colors/panelFg",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 1
              }
            },
            {
              "name": "Colors/mutedText",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 0.3
              }
            },
            {
              "name": "smallGap",
              "type": "number",
              "value": 8
            },
            {
              "name": "Colors/primaryText",
              "type": "color",
              "value": {
                "r": 255,
                "g": 255,
                "b": 255,
                "a": 1
              }
            }
          ]
        }
      ]
    },
    {
      "name": "Typography",
      "modes": [
        {
          "name": "Style",
          "variables": [
            {
              "name": "DefaultText",
              "type": "typography",
              "value": {
                "fontSize": 11,
                "fontFamily": "Inter",
                "fontWeight": "Semi Bold",
                "lineHeight": 16,
                "lineHeightUnit": "PIXELS",
                "letterSpacing": -1,
                "letterSpacingUnit": "PERCENT",
                "textCase": "ORIGINAL",
                "textDecoration": "NONE"
              }
            },
            {
              "name": "SmallText",
              "type": "typography",
              "value": {
                "fontSize": 9,
                "fontFamily": "Inter",
                "fontWeight": "Regular",
                "lineHeight": 11,
                "lineHeightUnit": "PIXELS",
                "letterSpacing": -1,
                "letterSpacingUnit": "PERCENT",
                "textCase": "ORIGINAL",
                "textDecoration": "NONE"
              }
            },
            {
              "name": "RegularText",
              "type": "typography",
              "value": {
                "fontSize": 11,
                "fontFamily": "Inter",
                "fontWeight": "Regular",
                "lineHeight": 16,
                "lineHeightUnit": "PIXELS",
                "letterSpacing": -1,
                "letterSpacingUnit": "PERCENT",
                "textCase": "ORIGINAL",
                "textDecoration": "NONE"
              }
            }
          ]
        }
      ]
    },
    {
      "name": "Effects",
      "modes": [
        {
          "name": "Style",
          "variables": [
            {
              "name": "cardDropShadow",
              "type": "effect",
              "value": {
                "effects": [
                  {
                    "type": "DROP_SHADOW",
                    "color": {
                      "r": 84,
                      "g": 255,
                      "b": 0,
                      "a": 0.25
                    },
                    "offset": {
                      "x": 0,
                      "y": 4
                    },
                    "radius": 4,
                    "spread": 0
                  }
                ]
              }
            }
          ]
        }
      ]
    },
    {
      "name": "Grids",
      "modes": [
        {
          "name": "Style",
          "variables": [
            {
              "name": "desktop",
              "type": "grid",
              "value": {
                "layoutGrids": [
                  {
                    "pattern": "COLUMNS",
                    "color": {
                      "r": 233,
                      "g": 27,
                      "b": 200,
                      "a": 0.1
                    },
                    "alignment": "STRETCH",
                    "gutterSize": 5,
                    "offset": 10,
                    "count": 5
                  }
                ]
              }
            }
          ]
        }
      ]
    }
  ]
}
```
</details>

The provided JSON structure represents a configuration file that stores variables for different modes (in this case, "Light" and "Dark") within a collection named "Theme." Here's an explanation of the different components and their meanings:

- <b>version</b>: Specifies the version number of the JSON structure or file format.
- <b>metadata</b>: An empty object that can be used to store additional information about the JSON file.
- <b>collections</b>: An array containing collections of variables.
    - <b>name</b>: The name of the collection ("Theme" in this case).
    - <b>modes</b>: An array of modes within the collection.
    - <b>name</b>: The name of the mode ("Light" or "Dark" in this case).
    - <b>variables</b>: An array of variables within the mode.
        - <b>name</b>: The name of the variable.
        - <b>type</b>: The type of the variable (string, number, color, or boolean).
        - <b>value</b>: The value of the variable, which can be a string, number, color object, text object, effect object or boolean.

In the provided example, there are two modes, "Light" and "Dark," each containing several variables of different types (string, number, color, and boolean). The color values are represented using an object with "r," "g," "b," and "a" properties, representing the red, green, blue, and alpha channels, respectively.

- The "Typography" collection has variables representing typography-related properties, such as font size, font family, etc. 
- The "Effects" collection has variables representing different visual effects, like drop shadow. 
- The "Grids" collection has variables representing different grid layouts.

The JSON structure allows you to define and store variables in a structured format, making it easier to manage and utilize them in your application or project.

## Tips for Users
Here are some tips to enhance your experience with the variables2json plugin:

- <b>Organize your variables</b>: Maintain a clear and consistent naming convention for your variables to ensure easy identification and management.
- <b>Regularly update the JSON file</b>: Whenever you make changes to your variables, remember to export and update the JSON file to keep it up to date.
- <b>Leverage composites</b>: Once the composites feature is released, use it to group related variables and styles together, allowing for more efficient utilization.
- <b>Submit issues for personalized suppor</b>t: If you encounter any problems or have specific requirements, feel free to submit an issue on the plugin's repository. Our team will provide personalized assistance.

## Feedback and Support
We appreciate your feedback and strive to improve the `variables2json` plugin continuously. If you have any suggestions, issues, or feature requests, please visit the [repo](https://github.com/mark-nicepants/variables2json-docs) and submit an issue.