<img width="872" height="741" alt="image" src="https://github.com/user-attachments/assets/b69794c2-636c-4d31-a5ab-063a3ae98c4a" /># Daily Learning

## Morning Planning

- [ ] Check out the [GitHub Blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4


