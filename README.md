# 5. Multimedia tags in HTML 

![Rickroll](https://media.giphy.com/media/KZkiESX3PdP9e/giphy.gif)

HTML (HyperText Markup Language) is the backbone of the web, allowing us to create and structure content for the internet. One of the coolest things about HTML is its ability to handle multimedia—images, audio, and video—bringing websites to life. In this guide, we'll explore how to use multimedia tags in HTML to make your web creations more engaging and interactive.

## 1. Images (img)

Images add visual appeal to websites and help convey information in a more captivating way. The `img` tag is used to display images in HTML.

```html
<img src="path_to_your_image.jpg" alt="Description of the image">
```

- **src (source)**: This is where you specify the path to your image file (e.g., `"path_to_your_image.jpg"`).
- **alt (alternative text)**: This provides a description of the image in case it cannot be displayed. It's important for accessibility.

## 2. Audio (audio)

The `audio` tag allows you to embed audio files into your web page.

```html
<audio src="path_to_your_audio.mp3" controls></audio>
```

- **src (source)**: Specify the path to your audio file (e.g., `"path_to_your_audio.mp3"`).
- **controls**: This attribute adds playback controls like play, pause, and volume.

## 3. Video (video)

The `video` tag is used to embed videos into your web page.

```html
<video src="path_to_your_video.mp4" controls></video>
```

- **src (source)**: Provide the path to your video file (e.g., `"path_to_your_video.mp4"`).
- **controls**: This attribute adds playback controls, just like with audio.

## 4. Embedding YouTube Videos

You can also easily embed YouTube videos into your web page using an iframe:

```html
<iframe width="560" height="315" src="https://www.youtube.com/watch?v=dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
```

- **src(source)**: Provides the link to the video.
- The example creates an iframe to rickroll you 😆

