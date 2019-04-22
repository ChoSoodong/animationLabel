# animationLabel
数字变化的label

```
[self.label animationTextStartValue:12 endValue:100 duration:1 complete:^(UILabel *label, CGFloat value) {
        label.text = [NSString stringWithFormat:@"%.2f", value];
    }];

```
