## Overvire
This is a subclass of UILabel to draw outline characters.

## Usage

```objective-c
UIOutlineLabel *label = [[UIOutlineLabel alloc] init];

// configuration of UILabel
label.frame = CGRectMake(0, 0, 100, 50);
label.textColor = [UIColor whiteColor];
label.font = [UIFont boldSystemFontOfSize:30];
label.text = @"Hello world";

// configuration of UIOutlineLabel
label.outlineColor = [UIColor blackColor]; // color of outline
label.outlineSize = 3; // size of outline

[self.view addSubview:label];
```
