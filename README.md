# StepDance Course Project Portfolio

This repository is your project portfolio for the Creative Motion Control course. You will use it to store code and documentation for each project you complete.

## Repository Structure

```
projects/
  project1/
    code/          ← Your Arduino/C++ code
    docs/
      index.md     ← Project write-up (text, images, video)
      assets/      ← Images and media filesgi
  project2/
    ...
```

## Getting Started

1. Create a new repository in the [Creative-Motion-Control github organization](https://github.com/Creative-Motion-Control-Course) with your team name. 
2. **Clone the [cmc_sample_template](https://github.com/Creative-Motion-Control-Course/cmc_sample_template) repository** to your local computer. Add the remote origin as your new repository with your team name:
```
git remote remove origin
git remote add origin git@github.com:Creative-Motion-Control-Course/<YOUR_REPO_NAME>.git
git branch -M main
git push -u origin main
```
3. **Enable GitHub Pages**: Go to your repo's *Settings → Pages*, set Source to **GitHub Actions**.
4. **Update the front page**: Modify the index.md file with your team name and Team Member Bios and pictures.
4. **Start a new project**: Modify the `projects/project1/` folder.
4. **Add your code**: Place your Arduino `.ino` and any supporting `.h`/`.cpp` files in the `code/` folder.
5. **Write your documentation**: Edit `docs/index.md` to describe your project, embed images and video.
6. **Update the home page**: Add a link to your new project in `index.md` at the repo root.
7. **Push to GitHub**: Your documentation site will automatically deploy to `https://<your-username>.github.io/<repo-name>/`.

## Writing Documentation

Each project's `docs/index.md` is a Markdown file that supports:

- **Images**: Place files in `docs/assets/` and reference them:
  ```markdown
  ![Description](assets/my-image.jpg)
  ```
- **Embedded video** (YouTube, Vimeo, etc.):
  ```html
  <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
  ```
Note, you should not upload videos directly to github as they are generally too large to handle effectively. Instead upload them to Vimeo or YouTube and embed them as shown above.


## Resources
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
