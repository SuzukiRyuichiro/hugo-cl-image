# Setup
1. make a submodule in your themes folder
2. add the theme in the theme array in your `config.toml`
```toml
theme = ["some other theme", "cl-image"]
```
3. add the following to your params portion of `config.toml`
```toml
[params]
  baseURL = "https://res.cloudinary.com/" # This is the same for everyone
  cloudName = "your cloud name" # You can check your cloud name from cloudinary console page
  folderName = "Portfolio" # if you want to put collection of pictures into a single folder, write the name of the folder (optional)
```

