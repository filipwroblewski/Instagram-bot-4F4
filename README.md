<div id="top"></div>

<!-- PROJECT LOGO -->
<br>
<div align="center">

  <h3 align="center">Instagram Bot F4F</h3>

  <p align="center">
    Project of the bot to the Instagram which enables follow for follow actions.  
    <br>
    <br>
    <a href="http://www.youtube.com/watch?feature=player_embedded&v=2TS3ffwVsGs" target="_blank">
      <img src="http://img.youtube.com/vi/2TS3ffwVsGs/0.jpg" alt="YouTUbe video" width="240" height="180" border="0"/>
    </a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

A project meant for gaining follower by follow account and also like with comment in the post of followed account.

Here's why:

- Gaining more traffic on the account
- Gaining more followers
- Try to get around restrictions of Instagram

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

Include all components used in the project.

- [Python 3](https://www.python.org/)
  - [Pyautogui](https://pyautogui.readthedocs.io/en/latest/)
  - [Time](https://docs.python.org/3/library/time.html)
  - [Random](https://docs.python.org/3/library/random.html)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

Instructions on setting up project locally. To get a local copy up and running follow these steps.

### Prerequisites

Things you need to use for the software and how to install them.

- cmd
  ```sh
  pip install pyautogui
  ```

### Installation

_Installing and setting up app._

1. Clone the repo
   ```sh
   git clone https://github.com/filipwroblewski/Instagram-bot-4F4
   ```
2. Install required modules
   ```sh
   pip install pyautogui
   ```
   <p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

Run _TimeTracker.py_ and start your work.

```sh
python "f4f bot.py"
```

<br>
<img src=".\to README\img\search.jpg" alt="Search field"> 
Have to be visible while starting app. 
<br>
All of the Instagram site have to be visible while app is running. 
<br>
<br>

Program automatically locate elements on the site. App find random hashtag and open recent posts, then follow account (if it is not followed yet), like and comment (also using emoticons) post. Comment and emoticon is also chosen randomly. When actions in one posts are done, then app jumps to another post and repeats process. During running there are displayed informations about status of seen posts. At the end of working it is displayed summary about number of seen posts and number of given comments.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Locate essential elements on the site
  - [x] Search field
  - [x] Hashtag image
  - [x] Most recent text
  - [x] Follow text
  - [x] Empty heart icon
  - [x] Comment icon
  - [x] Empty emoticon icon
    - [x] some smiling emoticons (_+/- 6_)
  - [x] Post comment text
  - [x] Next post button
- [x] Locate recent posts
- [x] Open last recent post
- [x] Take actions on the post
  - [x] Follow account
  - [x] Like post
  - [x] Add comment
  - [x] Open emoticons
    - [x] Add emoticon
  - [x] Post comment
  - [x] Go to the next post
- [x] Loop through choosed number of accounts to follow
  - [x] Define range of accounts to follow (_chooseing number to follow by random_)
- [x] Logic: if post's account is already followed jump to the next post
- [x] Create files with data to choose it randomly
  - [x] Comments file
  - [x] Hashtags file
  - [x] Emoticons file
- [x] Display information what action app is taking
  - [x] Display info when accoutn is ready to follow and how many accounts to follow left
  - [x] Display posted comment
  - [x] Display type of used emoticon
  - [x] Display type of used emoticon
- [x] Display summary of actions
  - [x] Seen posts
  - [x] Number of posted comments
  - [x] Suggested next start of app
- [ ] Add more data
  - [ ] Emoticons
  - [ ] Hashtags
  - [ ] Comments
- [ ] Create checker if everything works correctly and if not do something

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

<!-- Distributed under the ________ License. See `LICENSE.txt` for more information. -->

Distributed without any License yet.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

<a href="https://twitter.com/wrobl_ewski" ><img src="https://img.shields.io/twitter/follow/wrobl_ewski.svg?style=social"></a>

<p align="right">(<a href="#top">back to top</a>)</p>
