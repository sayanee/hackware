[![](img/cover.jpg)](https://www.facebook.com/groups/hackware)

# Hackware

> A monthly meetup for electronics, hardware, wireless communication, robotics and iot lovers. Checkout our casual meetups on [Facebook](https://www.facebook.com/groups/hackware) and [Meetup.com](http://meetup.com/hackware).

## Initial setup
1. Install npm which is part of node if you don't have it already. If you are using a Mac with brew, you can use `brew install node`.

2. Install packages `npm i`

## Running the page
- Open the slides in your browser on your machine `npm start` in the cloned repo directory.
- Past meetups are found in [tag releases](https://github.com/sayanee/hackware/releases)

## edit slides

1. Search for `EDIT` in file `index.html` 
- If the meetup has ended, then tag the release with `{HACKWARE_VERION}`

  ```sh
  #git tag -a {HACKWARE_VERSION} -m "Hackware {HACKWARE_VERSION}" # template
  git tag -a v1.4 -m "Hackware v1.4" # example
  git push --tags
  ```
  
