# reddit-slideshow
Site that displays a slideshow with images/gifs obtained from reddit. By default images will be fetched from reddit frontpage.

Currently hosted at https://redditslideshow.netlify.com/

## Usage
You can go to the next/previous slide by pressing `A` or `D`, or by using the arrow keys.

You can add, for example, `/r/pics` to the url and data will be fetched from reddit.com/r/pics. Try the following URLs:

- https://redditslideshow.netlify.com/r/pics
- https://redditslideshow.netlify.com/r/art
- https://redditslideshow.netlify.com/r/aww

## Todo
- Detect / handle invalid URLs.
- Better error handling.
- NSFW filter (some logic already implemented).

---

Made with React using `create-react-app`, based on http://redditp.com/
