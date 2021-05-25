![dynamic-cli](https://socialify.git.ci/IndianOpenSourceFoundation/dynamic-cli/image?description=1&descriptionEditable=A%20Modern%2C%20user-friendly%20command-line%20%20for%20the%20API%20testing%2C%20and%20if%20you%27re%20stuck%20-%20Search%20and%20browse%20StackOverflow%20without%20leaving%20the%20CLI&font=Inter&forks=1&issues=1&language=1&owner=1&pattern=Plus&pulls=1&stargazers=1&theme=Light)

## Setup📦

**1.** Installing pip [Python Package Manager]

```shell
$ sudo apt-get install python3-pip
```

**2.** Clone this repository to your local drive

```shell
$ git clone https://github.com/IndianOpenSourceFoundation/dynamic-cli.git
```

**3.** Install dependencies

```shell
$ pip3 install -r requirements.txt
```

**4.** Install with pip

```shell
$ sudo python3 -m pip3 install -e .
```

## Usage🛠

### Searching 🔎
Dynamic CLI allows users to search for keywords/issues with some relevant tags. It provides fluid viewing of results and dynamic user experience. Press `Enter` key to open the question in a browser.

![search](https://user-images.githubusercontent.com/26577306/119455378-2b3aa480-bd57-11eb-924b-d73bb5018ff4.gif)

### Saving Offline 🖊
Dynamic CLI can save your search results offline in a playbook for you to view later. Just press the `p` key while browsing and it will be saved.

![save](https://user-images.githubusercontent.com/26577306/119455428-3988c080-bd57-11eb-8a50-86d4e14ae7f6.gif)

### View saved results 📖
You can refer to your saved searches later with ease.

![read](https://user-images.githubusercontent.com/26577306/119455466-41486500-bd57-11eb-9830-569c37fdaa09.gif)

### Notion.so incorporation
(Upcoming feature) Login to your Notion account to sync your bookmarked questions

## Arguments⚙

Usage: Dynamic [OPTIONS] <br>

A Modern, user-friendly command-line HTTP client for the API testing, and if you're stuck - Search and browse StackOverflow without leaving the CLI. <br>

Options: <br>

`-st, --start -> Introduces Dynamic CLI` <br>
`-v, --version -> Gives the Version of the CLI` <br>
`-s, --search -> Search a question on Stackoverflow` <br>
`-p, --playbook -> View bookmarked questions in playbook` <br>
`-d, --debug -> Turn on Debugging mode` <br>
`-c, --custom -> Setup a custom API key` <br>
`-h, --help -> Shows this message and exit` <br>
`-GET -> Make a GET request to an API` <br>

## License🗄

### Contributing

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat&logo=git&logoColor=white)](https://github.com/IndianOpenSourceFoundation/dynamic-cli/pulls) [![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/IndianOpenSourceFoundation/dynamic-cli)

**We're accepting PRs for our open and unassigned [issues](https://github.com/IndianOpenSourceFoundation/dynamic-cli/issues)**. Please check [CONTRIBUTING.md](CONTRIBUTING.md). We'd love your contributions! **Kindly follow the steps below to get started:**

**1.** Fork [this](https://github.com/IndianOpenSourceFoundation/dynamic-cli) repository.

**2.** Clone the forked repository. Open terminal and type:

```bash
git clone https://github.com/<your-github-username>/project_name.git
```

**3.** Navigate to the project directory.

```bash
cd dynamic-cli
```

**4.** Make changes in source code.
<br />
P.S. If you want to add emojis 😁, use `unicodes`.
Emoji `unicodes` can be found at [https://unicode.org/emoji/charts/full-emoji-list.html](https://unicode.org/emoji/charts/full-emoji-list.html)
<br />
To include an emoji in a string, copy the unicode (Eg: `U+1F600`), replace `+` with `000` and
prefix it with a `\`.
<br />
Eg: `\U0001F604`

**5.** Stage your changes and commit

```bash
#Add changes to Index
git add .

#Commit to the local repo
git commit -m "<your_commit_message>"
```

**7.** Push your local commits to the remote repo.

```bash
git push
```

**8.** Create a [PR](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) !

**9.** **Congratulations!** Sit and relax, you've made your contribution to Dynamic-CLI project.

# Dynamic CLI is a part of these open source programs

<p align="center">
 <a>
 <img  width="40%" height="10%" src="https://raw.githubusercontent.com/GirlScriptSummerOfCode/MentorshipProgram/master/GSsoc%20Type%20Logo%20Black.png">

## Contributors👨🏽‍💻

### Credit goes to these people:✨

<table>
	<tr>
		<td>
			<a href="https://github.com/IndianOpenSourceFoundation/dynamic-cli/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=IndianOpenSourceFoundation/dynamic-cli" alt="Dynamic Cli Contributors"/>
</a>
		</td>
	</tr>
</table>

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
