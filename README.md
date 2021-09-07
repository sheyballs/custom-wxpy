# custom-wxpy
Various wxPython customizations. Mostly all work in-progress. If you've stumbled upon this repo, everything is free for the taking, customizing, and revising. I'm not very attentive with merges, but I'll do my best.

## SuperScrolledWindow
This class is an attempt at creating a scrolled window with custom scroll bars rather than using the native controls. The scroll bars are created in the .__on_paint method. Adjust the DC commands and other variables to make the bars in your likeness. There's plenty of room for improvement in the overall functionality.

See the __main__ function at the bottom for an example on how to get started.
