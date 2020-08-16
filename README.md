
# [LITTLE URL](https://liitleurl.tech) &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/littleurl/littleurl.github.io/blob/master/LICENSE) [PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg) <img alt="github actions" src="https://img.shields.io/badge/-Github_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
**(Makes your URL Short)**

The first url shortner for personal use build with (python+Github Actions) 

## How does it work ?
It works as a url redirector the default domain is set inside the [short.py](https://github.com/littleurl/littleurl.github.io/blob/master/short.py) ie.littleurl.tech and the CNAME File. The custom short url are to placed in [urls.json](https://github.com/littleurl/littleurl.github.io/blob/master/urls.json) file which could be generated with our [custom JSON Generator](https://littleurl.tech/#jsongenrator). As soon as the JSON file is edited with New url, github Actions does it job [little url shortner workflow](https://github.com/littleurl/littleurl.github.io/actions?query=workflow%3A%22Little+url+shotner%22) starts running and a new html fine is generated in [gh-pages branch](https://github.com/littleurl/littleurl.github.io/tree/gh-pages) with the url redirection. 

## Requirments (To set Your own)
* 1)Github Account.
* 2)Custom domain name.

## Examples
* Original url:-https://drive.google.com/file/d/1coDzFd1liCH4CUSs0GPv7UiBpSEVcxhk/view?usp=sharing
* Shorten url:- https://littleurl.tech/cv

* Original url:-https://www.huffpost.com/entry/jiff-the-dog-wins-halloween_n_56327e41e4b00aa54a4d7a89?ncid=fcbklnkushpmg00000022&utm_content=buffer83279&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer&guccounter=1
* Shorten url:-https://littleurl.tech/jiffthedog

## Purpose
The main purpose of this repository is to make use of github actions to make task automated , making it faster and easier to use. Development of Littleurl happens in the open on GitHub.

### License
Littleurl is [MIT licensed](./LICENSE).
