# Hey 👋

![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)

My name is Joseph and I'm a self-taught software engineer from Michigan who is passionate about computer science. I am currently a software engineer at [Bluestone Analytics][bluestone analytics].

I love developing in Rust and Python, and plan on implementing future projects in either (or both) languages!

<table style="width:100%;">
	<tr>
		<td>
			<a>
				<img 
					align="center" 
					src="https://github-readme-stats.vercel.app/api?username=JosephLai241&hide=contribs&show_icons=true&theme=gruvbox&count_private=true" />
			</a>
		</td>
		<td>
			<a>
				<img 
					align="center" 
					src="https://github-readme-stats.vercel.app/api/top-langs/?username=JosephLai241&theme=gruvbox&layout=compact&count_private=true" />
			</a>
		</td>
	</tr>
</table>

# Table of Contents

- [Skills](#skills)
  - [Languages](#languages)
  - [Frameworks](#frameworks)
  - [Databases](#databases)
  - [Continuous Integration](#continuous-integration)
  - [Testing Tools](#testing-tools)
  - [VPS](#vps)
  - [Linux](#linux)
- [Ways to Contact Me](#ways-to-contact-me)
  - [General](#general)
  - [For Anything Related to URS](#for-anything-related-to-urs)
  - [On GitHub](#on-github)
- [Accomplishments](#accomplishments)
  - [URS (Universal Reddit Scraper)](#urs-universal-reddit-scraper)
    - [What Is URS?](#what-is-urs)
    - [What Does It Do?](#what-does-it-do)
    - [How Do People Use It?](#how-do-people-use-it)
    - [Future Improvements](#future-improvements)
    - [Contact](#contact)
  - [Personal Blog](#personal-blog)
    - [The Stack](#the-stack)
- [What I'm Currently Working On](#what-im-currently-working-on)

# Skills

This is a list of areas that I'm currently skilled in.

## Languages

![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## Frameworks

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

<a href="https://actix.rs/">
  <img
    alt="Actix Web"
    height="80"
    width="80"
    src="https://avatars0.githubusercontent.com/u/32776943?s=400&v=4" />
</a>

## Databases

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

## Continuous Integration

![TravisCI](https://img.shields.io/badge/travisci-%232B2F33.svg?style=for-the-badge&logo=travis&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/githubactions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![CodeCov](https://img.shields.io/badge/codecov-%23ff0077.svg?style=for-the-badge&logo=codecov&logoColor=white)

## Testing Tools

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=red)

## VPS

![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white)

## Linux

![Arch](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-D70A53?style=for-the-badge&logo=debian&logoColor=white)

# Ways to Contact Me

> **_Note_**: These badges are clickable!

## General

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)][gmail link]
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)][linkedin link]

## For Anything Related to URS

[![Protonmail](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)][urs project]

## On GitHub

You can also directly ask me about anything in this `README`'s [Issues tab][issues].

# Accomplishments

## URS (Universal Reddit Scraper)

<div style="padding-bottom: 5px; padding-top: 5px;">
	<a href="https://www.github.com/JosephLai241/URS">
		<img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=JosephLai241&repo=URS&theme=tokyonight" />
	</a>
</div>

### What Is URS?

URS is an open source intelligence project written in Python. It's a command-line tool that implements PRAW (the Python Reddit API Wrapper), offering users a large suite of tools to scrape various aspects of Reddit.

### What Does It Do?

Its primary scraping tools target submissions within Subreddits, Redditor profiles, and submission comments; however URS also offers the ability to stream submissions or comments created within a Subreddit or by a Redditor in real time and export that data to JSON (or not, depending on the user's preferences).

In addition to scraping tools, URS also includes analytical tools such as the word frequencies and wordcloud generators that may be used after scraping.

It allows users to export scrape data to JSON or CSV, and offers a variety of image formats when exporting wordclouds.

### How Do People Use It?

This project has been featured in various places throughout the web, including:

- Page 58 of [i-intelligence][i-intelligence]'s [September 2020 OSINT Handbook][i-intelligence osint handbook]
- _Medium_'s [Week in OSINT #2019-18][medium week in osint]
- Data analysis projects, such as:
  - [A study of how masculinity is represented through different digital platforms][masculinity study]
  - [A study of how college students are handling COVID-19][covid-19 study]

### Future Improvements

While I believe the current suite of tools is fairly refined, the project is still a work in progress. I've already planned some enhancements for it (located in the [Future kanban][urs future kanban] within the repository), but I'm always looking to hear more about how it is used with the intention of adding additional enhancements that I've not considered.

### Contact

If you have any questions/comments/concerns regarding URS, please send me an email by clicking on the email badge below.

Also feel free to email me by clicking on the badge below if it helped you achieve a goal. I'd love to learn more about how it's used!

[![Protonmail](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)][urs project]

## Personal Blog

### The Stack

| **Frontend**                                                                                                  | **API**                                                                                                | **Database**                                                                                                    | **Web Server**                                                                                            | **VPS**                                                                                                                        |
| ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) | ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) | ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) | ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) | ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white) |

I created a private blog implementing [React][reactjs] for the frontend (plus [Bootstrap][bootstrap] for styling and [Axios][axios] for sending HTTP requests to the API), [Flask][flask] as the API, and [MongoDB][mongodb] as the database which holds various datasets such as blog posts and visitor information.

# What I'm Currently Working On

URS is a project that I'm constantly maintaining.

Since my job entails lots of programming in Python, I plan on writing a majority of my future personal projects in Rust. I think it's good to know an interpreted and a compiled language well; Rust fulfills the compiled language requirement that I set for myself.

<!-- SITE LINKS -->

[bluestone analytics]: https://www.bluestoneanalytics.com/

<!-- SOCIAL LINKS -->

[gmail link]: mailto:jlai24142@gmail.com
[linkedin link]: https://linkedin.com/in/joseph-lai-86390a137
[urs project]: mailto:urs_project@protonmail.com
[issues]: https://github.com/JosephLai241/JosephLai241/issues

<!--  -->

<!-- URS LINKS -->

<!-- Mentions -->

[i-intelligence]: https://i-intelligence.eu/
[i-intelligence osint handbook]: https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf
[medium week in osint]: https://medium.com/week-in-osint/week-in-osint-2019-18-ab45a6c1b810
[masculinity study]: https://smart.inovamedialab.org/2020-digital-methods/project-reports/cross-platform-digital-networks/masculinity/
[covid-19 study]: https://towardsdatascience.com/how-college-students-are-handling-covid-19-3705016205fe?gi=fb8d7260b338

<!-- Project links -->

[urs future kanban]: https://github.com/JosephLai241/URS/projects/13

<!--  -->

<!-- PERSONAL BLOG LINKS -->

[bootstrap]: https://getbootstrap.com/
[axios]: https://axios-http.com/

<!--  -->

<!-- TECH LINKS -->

[reactjs]: https://reactjs.org/
[flask]: https://flask.palletsprojects.com/en/1.1.x/
[mongodb]: https://www.mongodb.com/
[postman]: https://www.postman.com
[gunicorn]: https://gunicorn.org/
[nginx]: https://www.nginx.com/

<!--  -->

<!-- LUKE'S LINKS -->

[clck]: https://github.com/LukeDSchenk/clck
