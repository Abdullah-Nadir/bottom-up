
# Bottom Up

## Learning Goals

- Practice working with images
- Learn about metadata
- Learn more about how structs can be useful
## Background

Imagine an image you need to present to your boss for a major presentation somehow got corrupted! Upon investigating, you find that the image is mostly intact. Except, when you view the image, it now appears to be upside down!


## Implementation Details

The program edit's the metadata programmatically so that the bitmap’s top row is first and bottom row last.


## Usage/Example

Your program should behave per the examples below.

```javascript
bottomup/ $ ./bottomup harvard_bottomup.bmp harvard_topdown.bmp
```

When your program is working correctly, you should see a new file, harvard_topdown.bmp in your bottomup directory. Open it up and see if the orientation of the image is correct.

