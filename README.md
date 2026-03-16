# Book quote clock for Rainmeter

## Installation

### Basic
Download the Rainmeter skin from [releases](https://github.com/sandsq/rainmeter-timequotes/releases).

### Advanced
Clone this repository to your Rainmeter skin directory (typically `%USERPROFILE%\Documents\Rainmeter\Skins`) using 

    git clone https://github.com/sandsq/rainmeter-timequotes.git --recurse-submodules TimeQuotes

Then, you can periodically update the submodule to receive new quotes and corrections.

## Configuration
Open TimeQuotes.ini and locate the \[Variables\] section. `WidgetMode = 1` is meant to be used as a desktop background element, while `WidgetMode = 0` is meant to be used as an overlay bar.

Colors can have an optional opacity value as the last two digits, for hex. RGB and RGBA are also supported, e.g., `QuoteFontColor = R, G, B, A`.

    [Variables]
    ; If WidgetMode = 1, use the specified width and display quotes with newlines, etc. 
    ; If WidgetMode = 0, automatically expand the widget to the screen width for use as a top or bottom bar and replace quote newlines with "//".
    WidgetMode = 1
    WindowWidth = 800
    
    QuoteFontFace = Arial
    QuoteFontColor = ADEBB3ff
    QuoteFontSize = 16
    
    QuoteTimeColor = f4d8cdff
    QuoteTimeBoldness = 600
    
    GradientLeftColor = 1f3a4dcc
    GradientRightColor = 8b7b7ccc
    GradientAngle = 60
    BackgroundBorderRadius = 10
    
    LeftPadding = 20
    RightPadding = 20
    TopPadding = 10
    BottomPadding = 10
