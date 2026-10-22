AY GALLERY — Starter website
============================

This is a free, beginner-friendly starter for a public black-and-white photo gallery.

FILES
- index.html: the website
- photos.json: list of images shown in the gallery
- photos/: put your photo files here

HOW TO ADD PHOTOS
1. Put your own images inside the photos folder.
2. Open photos.json and add one entry per photo. Example:
   [
     {"src":"photos/photo-001.jpg","title":"My photo 1"},
     {"src":"photos/photo-002.jpg","title":"My photo 2"}
   ]
3. Use exact filenames, including uppercase/lowercase and file extension.
4. Keep image files reasonably compressed (for example, JPG or WebP) so the site loads faster on phones.

PUBLISH FOR FREE FROM ANDROID
1. Sign in or create an account at https://github.com
2. Create a new public repository named ay-gallery.
3. Upload index.html, photos.json, and the photos folder/files.
4. For the simplest free hosting, use Cloudflare Pages: https://pages.cloudflare.com/
   Connect your GitHub repository and follow its setup steps. For a plain HTML site,
   leave the build command blank and use the repository root as the output directory.
5. A free pages.dev address is only available if the chosen name is available.

IMPORTANT
- Anyone with the public website link can view and save/copy published photos.
- Do not publish private or sensitive images.
- Free hosting has file-size and usage limits; 200 full-resolution photos may be too large.
  Resize/compress copies for the website and keep original photos backed up on your phone.
- This starter does not include an online admin upload panel yet; new photos are added by
  uploading files and editing photos.json in your repository. We can improve this later.
