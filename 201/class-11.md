# Reading Class 11

Video and Audio Content

1) Early videos and audio were utilized through proprietary plugin-based technologies like Flash and Silverlight. These legacy technologies had security issues and accessability issues (like not loading in certain hardware or environments). Video and audio are now favored with HTML solutions `<video>` and `<audio>` and Javascripts controlling them.

2) `src` is the same as for images, it defines the path to the actual file. `controls` is used to indicate which controls to use, either the browser's own control, or interfaces from JS APIs.

3) Fallback content are important because there are cases where the browser cannot load the content. The fallback will at least provide or inidicate what it was supposed to be or even the path to the file itself.

4) Audio and Video are just like Image. They're all HTML elements that behave similar, but Audio and Videos have control, while Image does not.

Guide to Grid

1) Flex is designed for one-dimensional, either the row or column. Grid is designed for 2-dimensional.

2) Grid container is the element where grid is applied. It's the direct parent of all the grid items. Grid items are the direct descendant (one below) of the grid container. Grid lines are the lines that separate the spaces into a grid.

Responsive Images

1) Bandwith is one issue, when the image is large in file size and is very detailed for a large screen, it's a waste of data to put the same detailed page on a small screen that does not have enough resolution to display the details. Images can also be cropped when the screen size gets too small to handle.

2) `srcset` defines a set of images the browser can use. `sizes` are the set of media conditions (like screen width) and indicate what image sizes to use to render.
  srcset="480w.jpg 480w, 00w.jpg 800w"
  sizes="(max-width: 600px) 480px,
         800px"

3) Images are preloaded and downloaded before any CSS or JS. The image cannot be dynamically change it's source to a smaller image if needed be. The original size was already loaded.

## Things I want to know more about

Grid style might be easier to handle or grasp the concept of than flex style.
