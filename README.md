# ObserveEveryValueChanged.UWP

```
Windows.UI.ViewManagement.ApplicationView.GetForCurrentView()
	.ObserveEveryValueChanged(x => x.VisibleBounds.Width).Subscribe(x => widthText.Text = x.ToString());
Windows.UI.ViewManagement.ApplicationView.GetForCurrentView()
	.ObserveEveryValueChanged(x => x.VisibleBounds.Height).Subscribe(x => heightText.Text = x.ToString());
```

![gif](https://github.com/P3PPP/ObserveEveryValueChanged.UWP/blob/master/ObserveEveryValueChanged_UWP.gif)
