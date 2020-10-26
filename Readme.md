# File Organizer

This is a simple python project that moves all the files that comes in a specific directory to other predetermined directory

## formats.json

Contains all the supported formats

## target.json

```json
{
  "root": null,
  "image": "Pictures",
  "archive": "Documents",
  "video": "Videos",
  "audio": "Music"
}
```

- _**root**_ : The root directory for your targets, if set to `null` the default target will be your _home_
- _**image**_ : For images,gif etc
- _**archive**_ : For pdf, archives etc
- _**video**_ : For videos
- _**audio**_ : For audios
