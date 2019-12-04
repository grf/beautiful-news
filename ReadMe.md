# Get Beautiful News

Each day [Information Is Beautiful](https://informationisbeautiful.net/beautifulnews) publishes an infographic of a
piece of good news (think Hans Rosling). The RSS feed is at:

    http://feeds.feedburner.com/beautifulnewsdaily

This project parses the RSS feed and downloads a local copy of each
graphic. I wrote this primarily to populate a daily dashboard I'm writing,
but the script as delivered is meant to be run daily and will display
each newly-downloaded image (to a maximum of a week's worth).

## Getting Started

These instructions will get you a copy of the project up and running.

### Prerequisites

A working recentish version of ruby, and a shell-level ``open``
command - on my Mac, this opens the ``Preview.app`` on the recently downloaded files.

### Installing

```
gem install nokogiri
git clone
ln -s beautiful-news/get-beautiful-news ~/bin/beautiful-news
```

It will save images to the ``beautiful-news/images`` directory.

## Built With

* ruby
* emacs

## Authors

* **Randy Fischer**

## License

This project is licensed under the MIT License.
