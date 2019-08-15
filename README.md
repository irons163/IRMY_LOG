![Build Status](https://img.shields.io/badge/build-%20passing%20-brightgreen.svg)
![Platform](https://img.shields.io/badge/Platform-%20iOS%20-blue.svg)

# IRMY_LOG 

- IRMY_LOG is a log tool for iOS.

## Features

- Save system log in the txt file.
- Save your custom log in the txt file. 

## Usage

```obj-c
- (NSString*)AddHeaderToMessage:(NSString*)message {
    counter++;
    return [NSString stringWithFormat:@"%@ %@%d %@", MyLivewViewStatusLogkey, @"Index:",counter, message];
}

[self AddHeaderToMessage:@"My custom log string."];
```
